# 5. Booleans and comparing numbers

We can compare numbers to make booleans.

## Less than

You do this everyday: "If the price is less than 10, buy the drink".

We call this **"less than"**. And we type `<`. 

**code sample 1_5_0**
```java
class Main {
  public static main(String[] args) {
    int price = 15;
    boolean buyDrink = price < 10;
    System.out.println("I will buy the drink: " + buyDrink);
  }
}
```

## More than

The opposite this is **"more than"**. And we type `>`.

**code sample 1_5_1**
```java
class Main {
  public static main(String[] args) {
    int price = 15;
    boolean dontBuyDrink = price > 10;
    System.out.println("I will not buy the drink: " + dontBuyDrink);
  }
}
```

## Less than or equals to

We wanted to buy the drink when it is less than 10.

Sometimes we will buy it when it is 10 **or below**. 

This is called **"less than or equal to"**. And we type "<=".

We can do this in Java. We type 

**code sample 1_5_2**
```java
class Main {
  public static main(String[] args) {
    int price = 10;
    boolean buyDrink = price <= 10;
    System.out.println("I will buy the drink: " + buyDrink);
  }
}
```

## More than or equals to

We can also do **"more than or equal to"**. And we type `>=`.

**code sample 1_5_3**
```java
class Main {
  public static main(String[] args) {
    int price = 10;
    boolean dontBuyDrink = price >= 10;
    System.out.println("I will not buy the drink: " + dontBuyDrink);
  }
}
```

## Equals

We can compare two numbers. "If the price is 1. then buy it".

In Java, we type `==` and we call this "equals".

**code sample 1_5_4**
```java
class Main {
  public static main(String[] args) {
    int price = 1;
    boolean buyDrink = price == 1;
    System.out.println("I will buy the drink: " + buyDrink);
  }
}
```

## What about floats?

We can use `>`, `>=`, `<`, `<=` and `==` with floats too.

But we cannot mix comparing ints and floats. (But we will learn how to later)

**code sample 1_5_4**
```java
class Main {
  public static main(String[] args) {
    float yourScore = 11.5;
    float topScore = 10.5;
    boolean newTopScore = yourScore > topScore;
    System.out.println("Your score is bigger than the top score:" + buyDrink);
  }
}
```

## What about strings?

We cannot compare strings like this. 

In later lessons we will learn how to compare strings.

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_5_0 (click on the pen icon near the top left)
0. Create a program with an int variable `age` which a value of `18`.
0. Create a boolean `oldEnough`. Its value is the result of the boolean logic "if age is more than or equal to 18".
0. Print out the value of `oldEnough`.

## Questions to answer ##

0. What does `>` do?
0. What does `>=` do?
0. What does `<` do?
0. What does `<=` do?
0. What does `==` do?
0. What data types can we use the above on?
0. What happens when we try to compare an int variable and a float variable?
