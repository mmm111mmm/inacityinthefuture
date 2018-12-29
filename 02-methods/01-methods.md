
# Methods

We will use methods to reduce this duplication that we mentioned..

## What does a method look like?

You know what they look like. Look at this outline of Java program:

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

## What makes up a method?

The method starts like this: `public static void main(String[] args)`. It contains:

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

We must have only one `main` method. Java looks for this method to start our program.

The main method must contain `(String[] args)`.  But our other methods can just contain `()`. (We will look at this next lesson).

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
    System.out.println("I am in the method called 'hello'.");
    System.out.println("Goodbye from 'hello!'");
  }
  
  public static void helloAgain() {
    System.out.println("I am in them method called 'helloAgain'.");
    System.out.println("Goodbye from 'helloAgain!'");
  }
  
}
```

## Calling a method

The `main` method is where Java starts.

From `main`, we then **call** other methods. When we **call** them we perform all the statments in that method. And then go back to where we were before we called the method.

We call the method by typing its name, then `()` and finally a semi-colon, `;` (because calling a method is a statement).

```
class Main {
  
  public static void main(String[] args) {
    hello();
    helloAgain();
    hello();
    System.out.println("End of program.");
  }

  public static void hello() {
    System.out.println("I am in the method called 'hello'.");
    System.out.println("Goodbye from 'hello!'.");
  }
  
  public static void helloAgain() {
    System.out.println("I am in them method called 'helloAgain'.");
    System.out.println("Goodbye from 'helloAgain!'.");
  }
  
}
```

Output:

```
I am in the method called 'hello'.
Goodbye from 'hello!`.
I am in the method called 'helloAgain'.
Goodbye from 'helloAgain!`.
I am in the method called 'hello'.
Goodbye from 'hello!`.
End of program.
```

Java starts in the `main` method. It sees the call to the `hello` method. It then performs all the statements in `hello`. It then returns to `main` and see the `helloAgain()` method call. It then performs all the statements in `helloAgain`. It then returns to `main` and see the `hello()` method call.  It then performs all the statements in `hello` (again). It finally prints out "End of program." in `main`.

## Exercises

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_2_1_0 (click on the pen icon near the top left)
0. Make a program with the new methods, `newMethod1` and `newMethod2`.
0. Make `main` call `newMethod1`.
0. Make `newMethod1` call `newMethod2`
0. Make `newMethod2` print `"I'm in newMethod2`
0. After that, from `main`, print `"I am finished."`

## Questions

0. What does calling a method do?
0. What method does Java look at first?
