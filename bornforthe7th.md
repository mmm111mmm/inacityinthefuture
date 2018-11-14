# 0. Getting started - Printing your name

## What is Java?

When you talk to a Swede, you must speak Swedish.

When you talk to a computer, you must speak a language it understands. 

Java is one of these languages.

Sometimes we say "tell Java to do x, y or z". For example "Tell Java to print some text".

## What is Java used for?

All kinds of things: 

* Games such as Minecraft
* Mobile phone apps such as Android apps
* Banking software

## Why should I learn Java and not another language?

You should learn many languages. You must start with one, and learn that well.

Once you learn one major computer language well, such as Java, others will be easy.

## What is a Java program?

A computer program is like Microsoft Word, Apple Mail, Tetris, Minecraft.

A Java program is a computer program written in Java.

## What is compiling?

We write Java in a text file.

We then **compile** that file. 

When we compile it, it is converted into naughts and ones (010101010010...). 

You can then **run** this. 

When we run it, it can do anything we want - show some graphics, load an address book, open a file, play some music.

## What do we mean when we talk about the compiler?

When we talk about **a compiler** we mean something that takes the Java code and converts it into a naughts and ones.

Sometimes we use the term **Java**, **the Java compiler** and **the compiler** interchanagably. 

For example, "Java does not understand this line" and "The compiler does not understand this line" and "The Java compiler does not understand this line" all mean the same thing.

## How do we compile?

Another computer program helps us. We just press a button - labelled go or run - and the Java file is compiled and run for us.

## Basic form

A very basic Java program looks like this:

```java
class Main {
  public static void main(String[] args) {
    // this is a comment
  }
}
```

For the moment ignore everything except line three. 

We will explain the other lines in later lessons.

For now we will program on line three.

## Comments

**Comments** are lines Java ignores.

Comments start with two forward slashes: `//`. 

We use them to keep notes about a program. Or to help a friend understand our program.

Another way to write them is: `/* This is a comments */`

## Printing and Strings

In Java a piece of text is called a **string**.

A **string** must be surrounded by double quotation marks: `"Hello"`.

When we want to print a string we must do five things:

0. Type `System.out.println`
0. Then an opening parenthesis
0. Then a string
0. Then a closing parenthsis
0. Then, finally, a **semi-colon**.

**code sample 0.1**

```java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello world!");
  }
}
```

## Statements and semi-colons

A **statement** is an instruction you give to Java.

For example, "Print a string".

Every statement *must* end with a **semi-colon**: `;`

We know only one statement at the moment: `System.out.println("Hi!");`

80% of all lines you will type will end in a semi-colon. Don't forget them!

## Start coding ##

0. Make a github account on https://github.com
0. Go to https://repl.it and press signup, then press login, and login with your Github account
0. Press the add button
0. Select the Java language
0. Type in the code you saw in code sample 0.1.

## Exercises ##

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_0_1 (click on the pen icon near the top left)
0. Write a program that prints the string "My name is <insert your name here>!"`.
0. Add a comment that says what your program does!

## Questions to answer ##

0. What is Java?
0. What is compiling?
0. What is a comment?
0. What does a comment look like?
0. What is a string?
0. What is a string surrounded by?
0. What is a statement?
0. What must a statement end with?
