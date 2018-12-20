# 8. Making more complex decisions with `if else` statements 

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
    boolean money = false;
    boolean friendPays = false;
    boolean foodIsFree = true;    
    
    if(money) {
      System.out.println("I will eat in a restaurant because I have the money.");
    } else if(friendPays) {
      System.out.println("I will eat in a restaurant because my friend will pay.");
    } else if(foodIsFree) {      
      System.out.println("I will eat in a restaurant because the food is free.");    
    } else {
      System.out.println("I will not eat in a restaurant.");        
    }
  }
}
```

The output is:

```
I will eat in a restaurant because the food is free.
```

## Worked example 1

The booleans are like this:

```java
    boolean money = false;
    boolean friendPays = false;
    boolean foodIsFree = true;
```

So it works like this: 

The `if` statement looks at `money`. It is `false`, so we skip the first `if` statement. 

Then the first `else if` statement looks at `friendPays`. It is `false`, so we skip this `else if` statement. 

Then the second `else if` statement looks at `foodIsFree`. It is `true`, so we print `"I will eat in a restaurant because the food is free."`.

Because the second `else if` statement was `true`, we skip the `else` statement.

## Worked example 2

Imagine the booleans are like this:

```java
    boolean money = true;
    boolean friendPays = true;
    boolean foodIsFree = true;    
```

It works like this: 

The `if` statement looks at `money`. It is `true`, so we print `"I will eat in a restaurant because I have the money."`

Because the `if` statement was `true`, we skip the `else if` statements and the `else` statement.

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_6_0 (click on the pen icon near the top left)
0. Make a program that has the booleans `weekday`, `workEmergency` and `iWantToWork` that are all `false`.
0. If it's a weekday print `"I'll work because it's a weekday"`
0. If it's not a weekday, but there's a work emergency print `"I'll work because there's a work emergency"`.
0. If it's not a weekday, and there's no work emergency, but you want to work print `"I'll work because I want to."`
0. Otherwise print `"I will not work today."`
0. Now change the booleans so `"I'll work because I want to."` is printed

## Questions to answer ##

0. What comes before else-if statements?
0. Give an example of an if, else-if and else statment in real life.

