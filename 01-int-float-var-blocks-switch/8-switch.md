# 8. A little logic

If it's raining outside, you wear a coat. But if it's sunny and hot outside, you wear a t-shirt.

This is simple logic. And Java supports it.

## Our first logic statement: `switch`

Java has a statement called `switch`.

`switch` looks at a variable, for example a string variabled named `weather`.

Then `switch` looks at **cases** of a variable. This means: 

* In the case that `weather` is `"Raining"`, it does something.
* But in the case that `weather` is `"SunnyAndHot"`, it does something else.
* Etc.

## Switch is a block statement 

We previously learnt single statements: printing, defining a variable and assigning a variable.

But `switch` has multiple statements: one in the case that `weather` is `"Raining"`, another if `weather` is something else, etc.

We use **curly brackets**, `{ }`, to mark the beginning and to mark the end of multiple statements.

When we start with a `{` and end with a `}` this is called a **block statement**. `switch` is a block statement. We will learn others.

So far, our `switch` looks like this:

```java
switch(weather) {
  ...
}
```

We do **not** end a block statement with a semi-colon (`;`).

## Cases

Our `switch` statements deals with **cases**.

When we deal with the case that `weather` is `"Raining"` we:

0. Type word `case`
0. Type a space
0. Type the value (i.e. `"Ranining"`, `"SunnyAndHot"`, `"Snowing"` etc)
0. Type a colon, `:`

For example, `case "SunnyAndHot":`.

We then can type statements, e.g.:

```java
  ...
    case "SunnyAndHot":
      System.out.println("Oh great!");
      System.out.println("Let's go outside!")
  ...
```

When we want to end this case, we **break** out of this block statement. We break by typing: `break;`:

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

We can, however, use a `default` case. The statements after the default case are performed if no other cases match.

You must also use `break;` after the default case.

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
    break;
}
```

## `break` is very important

We use `break` to break out of the block statement.

If we forget, we will perform all the other statements until the next `break;`.

Let's remove the `break;` after the first case:

**code sample 8.0**
```java
class Main {
  public static void main(String[] args) {
    String weather = "SunnyAndHot";
    switch(weather) {
      case "SunnyAndHot":
        System.out.println("Oh great!");
        System.out.println("Let's go outside!");
      // I AM MISSING A BREAK STATEMENT!!!!
      case "Raining":
        System.out.println("Stay inside.");
      break;
      case "Snowing":
        System.out.println("Make a snowman!");
      break;      
      default:
         System.out.println("Sup");
      break;
    }
  }
}
```

Can you guess what is printed?

```
Oh great!
Let's go outside!
Stay inside.
```

If we don't remove the `break;` statement above, we get:

```
Oh great!
Let's go outside!
```

## Using a `switch` block statement on other data types

We used `switch` on a string data type. 

But we can use ints and floats too:

**code sample 8.1**
```java
class Main {
  public static void main(String[] args) {
    int favouriteNumber = 2;
    switch(favouriteNumber) {
      case 2:
        System.out.println("I like the number two, but it's not my favourite.");
      break;
      case 6:
        System.out.println("That's my favourite number!");
      break;
      default:
         System.out.println("I don't like that number.");
      break;  
    }
  }
}
```

The above will print:

```
I like the number two, but it's not my favourite.
```

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_8_0 (click on the pen icon near the top left)
0. Type code sample 8.1. Change the program so the `6` case is performed.

This exercise is easy. But will use `switch` calculator project in the new chapter. 

## Questions to answer

0. What does a `switch` statement do?
0. What does `case` in a `switch` statement do?
0. What does the `default` case do?
0. What is a block statement?
0. What does a block statement begin and end with?
0. Does a block statement end with a semi-colon? (`;`)
