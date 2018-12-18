# 6. Making decisions with booleans 

We use **if statements** everyday: "If it is raining, take an umbrella." 

And in Java too. 

## `if` statement

`if` statements are block statements like `switch` statements. This means they start an end with `{` and `}`.

And an `if` statement takes a boolean:

**code sample 1_6_0**
```java
class Main {
  public static void(String[] args) {
    boolean raining = true;
    if(raining) {
      System.out.println("You should take an umbrella.");
    }
    System.out.println("This is the end of the weather news.");    
  }
}
```

The output is:
```
You should take an umbrella.
This is the end of the weather new.
```

## What happens if the boolean in `if` statement is `false`?

In the code above, if `raining` is `false` then Java skips the `if` statement. Java prints the following:

**code sample 1_6_1**
```java
class Main {
  public static void(String[] args) {
    boolean raining = false;
    if(raining) {
      System.out.println("You should take an umbrella.");
    }
    System.out.println("This is the end of the weather news.");    
  }
}
```

The output is:
```
This is the end of the weather new.
```

## `else` statement

But we can give the `if` statement an `else` statement.  The `else` statement is a block statement too. 

The `else` statement comes after the `if` block statement.

Java runs everything in the `else` block if the `if` statement is false:

**code sample 1_6_2**
```java
class Main {
  public static void(String[] args) {
    boolean raining = false;
    if(raining) {
      System.out.println("You should take an umbrella.");
    } else {
      System.out.println("There is no need for an umbrella.");      
    }
    System.out.println("This is the end of the weather new.");    
  }
}
```

The output is:
```
There is no need for an umbrella.
This is the end of the weather new.
```

## And if-else statement


## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_6_0 (click on the pen icon near the top left)


## Questions to answer ##

0. 
