# 3. Passing variables to methods

We looked at our `main` method before.

```java
public static void main(String[] args) {
   ...
}
```

We said to ignore the `(String[] args)` part.

We made our other methods and we used only `()`.

```java
public static void anotherMethod() {
   ...
}
```

We will now look at the part of the method that comes after the name, i.e. the `()` part.

## Declaring variables in methods (introducing parameters)

We learnt how to declare variables many lessons ago i.e. `String hello`, `int age` etc.

We can declare variables in methods:

```java
public static void anotherMethod() {
   String name;
   ...
}
```

We can also declare variables within the parenthesis in methods:

```java
public static void anotherMethod(String name) {
   ...
}
```

We can declare multiple variables when we use a comma (`,`) to separate them.

```java
public static void anotherMethod(String name, String city) {
   ...
}
```

When we declare variables in the method parenthesis we call these **parameters**.

## Giving values to parameters

We give values to parameters when we call the method.

When we called a method before, we typed its name then typed `();`.

Now we will put something within that `()`.

If the method is:

```java
public static void anotherMethod(String name, String city) {
   ...
}
```

Then the method call is `anotherMethod("Aaron", "Berlin");`.

When you give a method a value, we call that an **argument**.

`"Aaron"` and `"Berlin"` are examples of arguments in the example above.

They give values to the parameters `name` and `city` in `anotherMethod`.

For example:

```java
class Main {
  
  public static void main(String[] args) {
    printGreeting("Aaron", "Berlin");
    printGreeting("Alien", "Mars");    
  }

  public static void printGreeting(String name, String city) {
    System.out.println("Hello " + name + "! I see you live in " + city);
  }
}
```

The output will be:

```
Hello Aaron! I see you live in Berlin
Hello Alien! I see you live in Mars
```


## Exercises

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_2_3_0 (click on the pen icon near the top left)
0. Create a method that has two parameters `number1` and `number2` and prints out the addition of `number1` and `number2`.
0. Call that method from `main` with `2` and `5`.
0. Make sure you see `7` printed out.


## Questions

0. What is a parameter?
0. What is an argument?
