# 1. Booleans and "and".

`If we have time and money, we will go on holiday.`

So we look at two things: time and money.

If we have those two things, something is true: a holiday.

This is simple **and logic**. We use it everyday. And Java supports it. 

## And logic

In English we use the word *and*. But in Java we type `&&`.  We can *only* use `&&` with booleans.

We use two boolean variables and type `&&` in the middle.

This is called a "boolean and".

**code sample 1.1.0**
```
class Main {
  public static void main(String[] args) {
    boolean time = true;
    boolean money = true;
    boolean holiday = time && money;
    System.out.println("We will go on holiday: " + money);
  }
}
```

This output from this program is:

```
We will go on holiday: true
```

If either boolean is false, the result will be false:

**code sample 1.1.1**
```
class Main {
  public static void main(String[] args) {
    boolean time = true;
    boolean money = false;
    boolean holiday = time && money;
    System.out.println("We will go on holiday: " + money);
  }
}
```

This output from this program is:

```
We will go on holiday: false
```

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_1_0 (click on the pen icon near the top left)
0. Write a program that defines a boolean named `noRain`, a boolean named `hot` and assign true to both. 
0. Then define a boolean named `needUmbrella` and assign the "boolean and" of both `noRain` and `hot`.
0. Print the value of `needUmbrella`.

## Questions to answer ##

0. What is a "boolean and"?
0. Give an example.
0. When is a "boolean and" true?
0. What data types can use we "boolean and"s with?
