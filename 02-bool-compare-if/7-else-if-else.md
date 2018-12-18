# 7. Making more complex decisions with `if` statements 


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
      System.out.println("You should take an umbrella for the rain.");
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

We often ask more complex if questions.

"If it is raining take an umbrella, if it is hailing take an umbrella, if you love your umbrella take an umbrella, else leave your umbrella at home."

We have multiple `if` questions. Java supports this. It calls them `if-else` statments.


## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_6_0 (click on the pen icon near the top left)
0. 
## Questions to answer ##

0. 

