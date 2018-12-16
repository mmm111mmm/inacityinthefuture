# 2. Booleans and "or".

"If I have my laptop or my mobile phone, I can access the internet."

We have two things: the fact I have my laptop or the fact I have my mobile phone. 

If either is true, then "I can access the internet" is true.

This is simple logic that we use everyday. And Java supports it. It's called "boolean or" logic.

## Or logic

In English we use the word *or*. But in Java we type `||`.  We can *only* use `||` with booleans.

We use two boolean variables and type `||` in the middle.

**code sample 1.2.0**
```
class Main {
  public static void main(String[] args) {
    boolean haveLaptop = false;
    boolean haveMobilePhone = true;
    boolean accessIntnernet = haveLaptop || haveMobilePhone;
    System.out.println("I can access the internet: " + accessInternet);
  }
}
```

This output from this program is:

```
I can access the internet: true
```

If both boolean are true, then the result will still be true.

**code sample 1.2.1**
```
class Main {
  public static void main(String[] args) {
    boolean haveLaptop = true;
    boolean haveMobilePhone = true;
    boolean accessIntnernet = haveLaptop || haveMobilePhone;
    System.out.println("I can access the internet: " + accessInternet);
  }
}
```

This output from this program is:

```
I can access the internet: true
```

However, if both are false, the result is false.

**code sample 1.2.2**
```
class Main {
  public static void main(String[] args) {
    boolean haveLaptop = false;
    boolean haveMobilePhone = false ;
    boolean accessIntnernet = haveLaptop || haveMobilePhone;
    System.out.println("I can access the internet: " + accessInternet);
  }
}
```

This output from this program is:

```
I can access the internet: false
```

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_2_0 (click on the pen icon near the top left)
0. Write a program that defines a boolean named `snow`, a boolean named `rain` and assign true to one and false to another.
0. Then define a boolean named `goOutside` and assign the "boolean or" of both `snow` and `rain`.
0. Print the value of `goOutside`.

## Questions to answer ##

0. What is a "boolean or"?
0. When is a "boolean or" true?
0. Give an example.
0. What data types can use we "boolean or"s with?
