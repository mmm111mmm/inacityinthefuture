# 7. Making more complex decisions with `if` statements 

When we decide something, we sometimes say **else**. 

```
If it is a weekday I will go to work.
Else I will stay at home.
```

Java supports this with the `else` statement.

## `else` statement

The `else` statement comes after the `if` block statement.

Java runs everything in the `else` block if the `if` statement is false.

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

## More complex decisions

We often ask more complex if questions.

```
If it is a weekday I will go to work.
If it is not a weekday, but there is a work emergency, I will go to work.
If it is not a weekday, and there is no work emergency, but I want to do more work, I will go to work.
Else I will stay at home.
```

The middle two lines are new. Java support this with `if else` statements.

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_6_0 (click on the pen icon near the top left)
0. 

## Questions to answer ##

0. 

