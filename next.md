# 4. Changing data - Varying data

We currently print data directly:

**code sample 4.0**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My age is: " + 36 + ".");
  }
}
```

## We need to change data

However, programs need to change data.

A computer game needs to print your score, do something, then print the new score.

A banking program needs to print your balance, withdraw money from your account, then print your new balance.

## Introducing variables

We can say: "we need to change data". Or we can say: "we need to **vary** data".

If we need to vary data, we use **variables**.

## What is a variable made of?

A variable is made of two things:

0. A variable data type
0. A variable name

Java needs to know the **type** of variable. We looked at data types previously: a string, an int, a float, a bool.

The name can be anything you want.

For example: 

```
String name
```

or 

```
int age
```

## What does a variable type look like?

We know four types of data: a string, a int, a float and a bool.

* When we want to specify a int variable, we say: `int something`
* When we want to specify a float variable, we say: `float something`

*But*:

* When we want to specify a bool variable, we say: `boolean something`
* When we want to specify a string variable, we say: `String something`

Note that a string has a **uppercase** S. And that a bool is **boolean**.

In later lessons, we will explain why string has an uppercase S.

## What can I name my variable?

We said it can be whatever you want.

But 

* It must start with a letter: `String hello`.
* Or it can start with an **underscore**: `String _hello`.
* And it must include no spaces: `String helloIAmALongerName`.
* And it can include numbers, but not at the beginning: `String hello43`.

## How can I put data in my variable?

After you tell Java about your variable, you must give it some data. You must give it a **value**.

You use the equals symbol, `=`, to give a variable to a value.

For example: `String name = "Aaron";` or `int age = 36;`, or `boolean happy = true;`.

When we give a variable a value, we say we **assign** a value to a variable.

## An example

one.

two.

three.

four.

five.

# Changing data - Changing your name and age

This lesson deals with: ++ numbers, -- numbers, + numbers, - numbers, + strings, printing and assignment.
