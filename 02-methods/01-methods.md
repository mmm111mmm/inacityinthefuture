
# What does a method look like?

You know what they look like. You've written them lots of times. But you don't know you know. 

Look at this outline of Java program:

```
class Main {
  public static void main(String[] args) {
    ...
  }
}
```

Lines two and four are the start and end of a method.

We told you to ignore these lines (just type them) at the start of the course.

Now we will explain them (or at least partially).

## Explaining methods

The method you typed many times starts like this `public static void main(String[] args)`.

It contains

0. the word `public`
0. the word `static`
0. the word `void`
0. its name (we will look at this below)
0. an openening parenthesis, `(`
0. the text `String[] args` (which we look at later)
0. a closing parenthesis, `)`

Methods (like `if` and `switch` statements) are "blocks" of code. So they start and end with curley brackets, `{` and `}`.

Inside these curley brackets we have statements:

```
class Main {
  public static void main(String[] args) {
    System.out.println("I am the only statement in this method");
  }
}
```

## The method name

We have used the method name `main` so far. This is special in Java.

You must have one (and only one) `main` method. Java looks for this method to start your program.

## Other method names

We can use many methods. But they must be called different things (and `main` must always exist).

