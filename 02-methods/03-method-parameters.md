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

## Exercises

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_2_3_0 (click on the pen icon near the top left)
0. 


## Questions

0. 
