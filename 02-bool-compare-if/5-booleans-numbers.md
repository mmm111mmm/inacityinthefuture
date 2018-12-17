# 5. Booleans and numbers

We can make numbers produce booleans.

## More than

You do this everyday: "If the price is less than 10, do not buy the drink".

The symbol we use for this in Java is `<`. We call this **"less than"**.

**code sample 1_5_0
```java
class Main {
  public static main(String[] args) {
    int price = 15;
    boolean buyDrink = price < 10;
    System.out.println("I will buy the drink": buyDrink);
  }
}
```

## Less than

The opposite this is **"less than"** and the symbol is `>`.

**code sample 1_5_0
```java
class Main {
  public static main(String[] args) {
    int price = 15;
    boolean dontBuyDrink = price > 10;
    System.out.println("I will not buy the drink": dontBuyDrink);
  }
}
```



## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_3_1 (click on the pen icon near the top left)
0. Create a program with two booleans `tastyBreakfast` which is `false`, and `fullStomach` which is `false`.

## Questions to answer ##

0. What is a "boolean not"?
0. Give an example of a "boolean not".
