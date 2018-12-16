# 3. Boolean "not" and combined logic

## Boolean not

The final boolean operation is the **boolean not**. And this is very simple. 

If the boolean is `true` it makes it `false`. If the boolean is `false` it makes it `true`.

We type `!` before the boolean variable to make it false:

**code sample 1.3.0**
```
class Main {
  public static void main(String[] args) {
    boolean hotWeather = true;
    System.out.println("The weather is hot: " + hotWeather);
    hotWeather = !hotWeather;
    System.out.println("The weather is hot: " + hotWeather);
  }
}
```

This output from this program is:

```
The weather is hot: true
The weather is hot: false
```

## Combined boolean logic

We learnt three types of boolean logic: boolean and, boolean or and boolean not.

We can combine these to make more complex logic.

For example, we can say thing: "If it is hot and in the daytime I will go outside. However, if I have no food I will go outside, in any  weather or time."

So, imagine it's hot but it's not the daytime. Then we stay home. But we need food, so we go outside.

In Java this is: 

**code sample 1.3.1**
```
class Main {
  public static void main(String[] args) {
    boolean daytime = false;
    boolean hot = true;
    boolean needFood = true;
    System.out.println("I will go outside: " + daytime && hot || needFood);
  }
}
```

So we see `daytime` is `false` and `hot` is `true`. So `daytime && hot` is `false`. 

Then we take that `false` and do `false || needFood`. `needFood` is true. Together the result is `true`.

So `daytime && hot || needFood` is `true`.

## Combined boolean logic with parenthesis

However, imagine we are a noctural penguin. We don't like hot weather. We only go out at night. We could use the "boolean not".

class Main {
  public static void main(String[] args) {
    boolean daytime = false;
    boolean hot = true;
    boolean needFood = true;
    System.out.println("I am a noctural penguin. I will go outside: " + !daytime && hot || needFood);
  }
}
```

We have used a `boolean not` on `!daytime && hot`. But this now reads: 

"If **it is not** daytime and it is hot, go outside." And we want to say: "If **it is not** daytime and **it is not** hot, go outside."

We can do this with parenthesis `(` and `)`, like we did in maths to say: `2 * (1 + 2)`.

When we wrap boolean logic in parenthesis, Java will do that logic first. So we can say:

class Main {
  public static void main(String[] args) {
    boolean daytime = false;
    boolean hot = true;
    boolean needFood = false;
    System.out.println("I am a penguin. I will go outside: " + !(daytime && hot) || needFood);
  }
}
```

Java will look at `daytime && hot` first because it's wrapped in parenthesis. The result will be `false`. 

Then Java uses the "boolean not" on that. So the result will be `true`.

So it look like this `true || needFood`. And, in this case, `needFood` is false. But with a "boolean or" the result is `true`.

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_2_0 (click on the pen icon near the top left)
0. 

## Questions to answer ##

0. What is a "boolean not"?
0. Give an example of a "boolean not".
