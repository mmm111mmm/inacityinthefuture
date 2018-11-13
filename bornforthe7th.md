# 0. Getting started

## What is Java

When you talk to a Swede, you must speak Swedish.

When you talk to a computer, you must speak a language it understands. 

Java is one of these languages.

Sometimes we say we tell Java to do something. For example "Tell Java to print some text".

## What is compiling?

We write program in Java.

We then **compile** that program. 

When we compile it, the program is converted into naughts and ones (010101010010...). 

You can then **run** the program. The program can then do anything - show some graphics, load an address book, open a file, play some music.

## Basic form

```java
class Main {
  public static void main(String[] args) {
    //
  }
}
```

For the moment ignore everything except line three. We will program there.

## Printing and Strings

In Java a piece of text is called a **string**.

A **string** must be surrounded by double quotation marks " ".

When we want to print a string we must do five things:

0. Type `System.out.println`
0. Then an opening parenthesis
0. Then a string
0. Then a closing parenthsis
0. Then, finally, a **semi-colon**.

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

Every statement in Java ends with a **semi-colon**: `;`

We know only one statement at the moment: `System.out.println("Hi!");`

80% of all lines you will type will end in a semi-colon. Don't forget them!

## Exercises ##

0. Write a program that prints the string "My name is <insert your name here".

## Questions to answer ##

0. What is a string?
0. What is a statement?
0. What is compiling?
