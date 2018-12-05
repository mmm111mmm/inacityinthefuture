# 6. Changing a string

We learnt how to declare a string variable. And we learnt how to assign value to that variable.

We also learnt how to assign a value to a variable multiple times:

**code sample 6.0**
```java
class Main {
  public static void main(String[] args) {
    String status = "I am fine";
    System.out.println(status);
    status = "I am even better";
    System.out.println(status);
  }
}
```

## Concatenating a value with `+`

We can also change a string using **concatenation** (which we learnt in a previous lesson).

We 

0. type the variable name
0. type a `+`
0. type a new string

For example: `status + " and healthy"`.

This makes the string `"I am even better and healthy"`.  

We then assign that to a variable: `status = status + " and healthy";`. (In this case, we assign it to the same variable.)

For example:

**code sample 6.1**
```java
class Main {
  public static void main(String[] args) {
    String status = "I am fine";
    System.out.println(status);
    status = status + " and healthy";
    System.out.println(status);
  }
}
```

The output is:

```
I am fine
I am fine and healthy
```

## Concatenating a string with another type

We saw in a previous lesson that we can concatenate a value with another type.

*But* only if the string is first:

**code sample 5.2**
```java
class Main {
  public static void main(String[] args) {
    String status = "My age is...";
    System.out.println(status);
    status = status + 36;
    System.out.println(status);
  }
}
```

The output is:

```
My age is...
My age is...36
```

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_6_0 (click on the pen icon near the top left)
0. Write a program that: declares and assigns a your name to a string variable, prints that, adds the string " and Java" to the end, and finally prints that.

## Questions to answer

0. How do we concatenate a string to another value?
0. When we concatenate what data type must we start with?
