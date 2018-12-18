# 6. Making decisions with booleans 

We use **if statements** everyday: "If it is raining, take an umbrella." 

And in Java too. 

## `if` statement

`if` statements are block statements like `switch` statements. This means they start an end with `{` and `}`.

You type:

0. The word `if`
0. A opening parenthesis `(`
0. The name of a boolean variable, boolean variables using `||` and `&&` etc, or `true` or `false`
0. A closing parenthesis `)`
0. And you start an end a block statement with `{` and a `}`.

**code sample 1_6_0**
```java
class Main {
  public static void(String[] args) {
    boolean raining = true;
    if(raining) {
      System.out.println("You should take an umbrella for the rain.");
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

If `raining` is `false` in the above code, then Java skips the `if` statement:

**code sample 1_6_1**
```java
class Main {
  public static void(String[] args) {
    boolean raining = false;
    if(raining) {
      System.out.println("You should take an umbrella for th rain.");
    }
    System.out.println("This is the end of the weather news.");    
  }
}
```

The output is:
```
This is the end of the weather new.
```


