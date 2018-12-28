
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

0. the word `public` -- we will look at this later
0. the word `static`  -- we will look at this later
0. the word `void` -- we will look at this in a few lessons
0. its name, `main` -- we will look at this now
0. then `(String[] args)`  -- we will look at this in a few lessons

Methods (like `if` and `switch` statements) are "blocks" of code. So they start and end with curley brackets, `{` and `}`.

Inside these curley brackets we have statements:

```
class Main {
  public static void main(String[] args) {
    System.out.println("I am the only statement in this method");
  }
}
```

## The method `main`

We used the method name `main`. This is special in Java.

We must have one (and only one) `main` method. Java looks for this method to start our program.

The main method must also contain `(String[] args)`. 

But our other methods can just contain `()`. (We will look at this next lesson).

## Other methods and method names

After the `main` method, we can have other methods. But they must have different names.

Method names can contain letters, underscores and numbers, but they must start with a letter or underscore, and cannot include spaces.

And our methods should have statements in them:

```
class Main {
  
  public static void main(String[] args) {
    ...
  }

  public static void hello() {
    System.out.println("I am in them method called 'hello'.")
    System.out.println("Goodbye from 'hello!'")
  }
  
  public static void helloAgain() {
    System.out.println("I am in them method called 'helloAgain'.")
    System.out.println("Goodbye from 'helloAgain!'")  
  }
  
}
```

