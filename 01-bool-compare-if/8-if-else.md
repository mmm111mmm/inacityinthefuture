# 8. Making more complex decisions with **if else** statements 

We use if statements everyday. And we use else statement everyday.

Sometimes we use multiple **if** statements.

```
If I have the money, I will eat in a restaurant
If I don't have the money, but my friend pays, I will eat in a restaurant.
If I don't have the money, and my friend doesn't pay, but the food is free, I will eat in a restaurant
Else I will stay at home.
```

The middle two lines are new. They are called **else if** statements.

## How to use `else if` statements

You use `else if` statements by:

0. After the an `if` block statement, you type `else if`
0. Then you type an openining parenthesis, `(`
0. The name of a boolean variable, boolean variables using || and && etc, or true or false
0. A closing parenthesis `)`
0. You start the block statement with a `{`
0. Your statements (System.out.println at the moment)
0. You end the block statement with a `}`

For example:

**code sample 1_8_0**
```java
class Main {
  public static void main(String[] args) {
    boolean weekday = false;
    boolean workEmergency = false;
    boolean iWantToWork = true;
    
    if(weekday) {
      System.out.println("I will go to work because it's a weekday");
    } else if(workEmergency) {
      System.out.println("I will go to work because it's an emergency");
    } else if(iWantToWork) {      
      System.out.println("I will go to work because I want to work");    
    } else {
      System.out.println("I will not go to work.");        
    }
  }
}
```

The output is:

```
I will go to work because I want to work.
```

## Worked example 1

The booleans are like this:

```java
    boolean weekday = false;
    boolean workEmergency = false;
    boolean iWantToWork = true;
```

So it works like this: 

The `if` statement looks at `weekday`. It is `false`, so we skip the first `if` statement. 

Then the first `else if` statement looks at `workEmergency`. It is `false`, so we skip this `else if` statement. 

Then the second `else if` statement looks at `iWantToWork`. It is `true`, so we print `"I will go to work because I want to work""`.

Because the second `else if` statement was `true`, we skip the `else` statement.

## Worked example 2

Imagine the booleans are like this:

```java
    boolean weekday = true;
    boolean workEmergency = true;
    boolean iWantToWork = true;
```

It works like this: 

The `if` statement looks at `weekday`. It is `true`, so we print `"I will go to work because it's a weekday"`

Because the `if` statement was `true`, we skip the `else if` statements and the `else` statement.

## Worked example 2

Imagine the booleans are like this:

```java
    boolean weekday = true;
    boolean workEmergency = true;
    boolean iWantToWork = true;
```

So it works like this: 

The `if` statement looks at `weekday`. It is `true`, so we print `"I will go to work because it's a weekday"`

Because the `if` statement was `true`, we skip the `else if` statements and the `else` statement.


## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_6_0 (click on the pen icon near the top left)
0. 

## Questions to answer ##

0. 

