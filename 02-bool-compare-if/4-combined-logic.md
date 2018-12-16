# 3. More combined boolean logic



## Combined boolean logic with parenthesis

Imagine we are a noctural penguin. We don't like hot weather. We only go out at night. We could use the "boolean not".

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
