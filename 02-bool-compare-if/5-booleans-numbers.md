# 5. Booleans and numbers

We can make numbers produce booleans.

## Less than

You do this everyday: "If the price is less than 10, do not buy the drink".

We call this **"less than"**. And we type `<`. 

**code sample 1_5_0**
```java
class Main {
  public static main(String[] args) {
    int price = 15;
    boolean buyDrink = price < 10;
    System.out.println("I will buy the drink": buyDrink);
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
    System.out.println("I will not buy the drink": dontBuyDrink);
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
    System.out.println("I will buy the drink": buyDrink);
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
    System.out.println("I will not buy the drink": dontBuyDrink);
  }
}
```

## What about floats?

## What about strings?


## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_3_1 (click on the pen icon near the top left)
0. Create a program with two booleans `tastyBreakfast` which is `false`, and `fullStomach` which is `false`.

## Questions to answer ##

0. 
