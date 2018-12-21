# 7. Making more complex decisions with `if` statements 

When we decide something, we sometimes say **else**. 

```
If it is a weekday I will go to work.
Else I will stay at home.
```

Java supports this with the `else` statement.

## `else` statement

The `else` statement comes after the `if` block statement.

Java runs everything in the `else` block if the `if` statement is `false`.

The `else` statement is a block statment, so a `{` and a `}` surrounds the statements in the `else`.

So you type

0. The word `else`
0. An opening curly bracket, `{`
0. All the statements 
0. A closing curly bracket, `}`


**code sample 1_7_0**
```java
class Main {
  public static void(String[] args) {
    boolean weekday = false;
    if(weekday) {
      System.out.println("I will go to work.");
    } else {
      System.out.println("I will stay at home.");      
    }
    System.out.println("End of if and else statement.");    
  }
}
```

The output is:
```
I will stay at home.
End of if and else statement.
```

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_7_0 (click on the pen icon near the top left)
0. Make a program with the boolean `sunshine` which is `true`.
0. Make an `if` statement with an `else` statement
0. If `sunshine` is `true` print `"Let's go outside!"
0. if `sunshine` is `false` print `"Let's watch a film!"`

## Questions to answer ##

0. When do the statements within an `else` block run?
0. What comes before an `else` block statement?

