# 8. A little logic

If it's raining outside, you wear a coat. But if it's sunny and hot outside, you wear a t-shirt.

This is simple logic. And Java supports it.

## Our first logic statement: `switch`

Java has a statement called `switch`.

`switch` looks at a variable, for example a string variabled named `weather`.

Then `switch` looks at **cases** of a variable. This means: 

* In the case `weather` is `"Raining"`, it does something.
* But in the case `weather` is `"SunnyAndHot"`, it does something else.
* Etc.

## Switch is a block statement 

We previously learnt single statements: printing, defining a variable and assigning a variable.

But `switch` has multiple statements: one in the case `weather` is `"Raining"`, another if `weather` is something else, etc.

We use **curly brackets**, `{ }`, to mark the beginning and the end of the multiple statements.

When we start with a `{` and ending with a `}` this is called a **block statement**.

So far, our `switch` looks like this:

```java
switch(weather) {
  ...
}
```

## Cases

Our `switch` statements deals with **cases**.

When we deal with the case `weather` is `"Raining"` we:

0. Type word `case`
0. Type a space
0. Type the value (i.e. `"Ranining"`, `"SunnyAndHot"`, `"Snowing"` etc)
0. Type a colon, `:`

We then have `case "SunnyAndHot":`.

After this we can type any other statement we want, e.g.:

```java
    case "SunnyAndHot":
      System.out.println("Oh great!");
      System.out.println("Let's go outside!")
```

When we want to end this case we **break**. We break by typing: `break;`:

```java
    ...
    case "SunnyAndHot":
      System.out.println("Oh great!");
      System.out.println("Let's go outside!");
    break;
    ...
```

## Dealing with lots of cases

`switch` can deal with lots of statements:

```java
switch(weather) {
    case "SunnyAndHot":
      System.out.println("Oh great!");
      System.out.println("Let's go outside!");
    break;
    case "Raining":
      System.out.println("Stay inside.");
    break;
    case "Snowing":
      System.out.println("Make a snowman!");
    break;        
}
```

When `weather` is none of the above cases nothing happens.

We can, however, use a `default` case. The statements in the default case are performed if no other cases match:

```java
switch(weather) {
    case "SunnyAndHot":
      System.out.println("Oh great!");
      System.out.println("Let's go outside!");
    break;
    case "Raining":
      System.out.println("Stay inside.");
    break;
    case "Snowing":
      System.out.println("Make a snowman!");
    break;
    default:
      System.out.println("I'm not sure. Go to a bar maybe?");
}
```

## `break` is very important.

# 10. Calculator project

# 11. Order of operation 

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_8_0 (click on the pen icon near the top left)
0. 

## Questions to answer

0. 
