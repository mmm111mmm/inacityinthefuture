
# What does a method look like?

You know what they look like. But you don't know you know. 

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

Now we will explain them.

## Explaining methods

The method starts like this `public static void main(String[] args)`.

It contains

0. the word `public`
0. the word `static`
0. the word `void`
0. its name, `main` (we will look at this below)
0. an openening parenthesis, `(`
0. the text `String[] args` (which we will look at later)
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

We used the method name `main`. This is special in Java.

We must have one (and only one) `main` method. Java looks for this method to start your program.

## Other method names

After the `main` method, we can have other methods. But they must have different names.

```
class Main {
  public static void main(String[] args) {
    ...
  }
  public static void hello(String[] args) {
    ...
  }
  public static void helloAgain(String[] args) {
    ...
  }
}
```

We have two extra methods, `hello` and `helloAgain`.

## What is `String[] args`?

The `main` method must have `(String[] args)`. We will explain this later.

But our other methods don't need it. But we will explain in next lesson. For now, let's just remove them:

```
class Main {
  public static void main(String[] args) {
    ...
  }
  public static void hello() {
    ...
  }
  public static void helloAgain() {
    ...
  }
}
```
