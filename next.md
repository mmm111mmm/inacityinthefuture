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

## How to change data

There are four steps:

* Tell Java about the data
* Print the data
* Change the data
* Print the data again

This lesson will only talk about the first point: **Tell Java about the data**

## How do we tell Java about data?

We can say: "we need to change data". Or we can say: "we need to **vary** data".

When we tell Java about data that we need to **vary**, we use **variables**.

## What is a variable made of?

A variable is made of two things:

0. A variable data type
0. A variable name

A variable data type is a type we looked at previously: string, int, float, bool.

A variable name can be anything you want.

## What does a variable type look like?

We know four types of data: a string, a int, a float and a bool.

* When we want to specify a int variable, we say: `int something`
* When we want to specify a float variable, we say: `float something`
* When we want to specify a bool variable, we say: `boolean something`
* When we want to specify a string variable, we say: `String something`

Note that a string has a **uppercase** S. 

Note that a bool is **boolean**.

In later lessons, we will explain why string has an uppercase S.

## What can I name my variable?

We said it can be whatever you want. But:

* It must start with a letter: `String hello`.
* Or it can start with an **underscore**: `String _hello`.
* And it *must not* include spaces: `String helloIAmALongerName`.
* And it can include numbers, but not at the beginning: `String hello43`.

## Examples

If we want to tell Java about a string variable, named `hello`:

```java
String hello;
```

If we want to tell Java about a int variable, named `age`:

```java
int age;
```

If we want to tell Java about a float variable, named `score`:

```java
float score;
```

If we want to tell Java about a boolean variable, named `happy`:

```java
boolean happy;
```

When you tell Java about variables, you **declare** a variable.

And declaring variables, like most things, means you make a **statement**. 

And the semi-colon, `;`, comes after a statement.

## How can I put data in my variable?

We told Java about your variable. And your variable has a name.

We can now use this name to give your variable a **value**.

If you create a string variable called name, you can say:

```java
name = "Aaron";
```

This is called **defining** your variable. Defining a variable is a statement. So you end it with a semi-colon, `;`.

If you create a int variable called age, you can say:

```java
age = 36;
````

If you create a boolean variable called age, you can say:

```java
happy = true;
````

If you create a float variable called score, you can say:

```java
score = 10.50;
````

## Printing the variable

We have declared a variable. And we have defined it. 

We can use the variable name to print it.

**code sample 4.1**
```java
class Main {
  public static void main(String[] args) {
    int age;
    age = 36;
    System.out.println("My age is: " + age);
  }
}
```

## You can define variables many times

When we define a variable, we give the variable a value.

We can do this many times

**code sample 4.1**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println("One year passes.");
    age = 37;
    System.out.println("One year passes.");
    age = 38;
    System.out.println("My age is now: " + age);
  }
}
```

The output is:

```
My age is now: 38
```

## Exercise

# Changing data - Changing your name and age

This lesson deals with: ++ numbers, -- numbers, + numbers, - numbers, + strings, printing and assignment.
