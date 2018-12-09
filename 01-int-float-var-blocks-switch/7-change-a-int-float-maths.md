# 7. Changing an int and a float

We can use basic maths to change an int or float variable.

## Adding to an int with `+`

We can add to an int with `+`.

We type the variable name, then a `+` and then a int value: `age + 10`. This makes the value `47`.

Then we assign that to a variable: `age = age + 10`. 

In this case, we replace the existing value in `age`.

For example:

**code sample 7.1**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age = age + 10;
    System.out.println(age);
  }
}
```

This outputs 

```
36
46
```

## Subtracting from an int with `-`

We can substract from an int with `-`.

**code sample 7.2**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age = age - 10;
    System.out.println(age);
  }
}
```

This outputs 

```
36
26
```

## Doing the same with floats

We can do the same with floats. But the data types must all be floats.

**code sample 7.3**
```java
class Main {
  public static void main(String[] args) {
    float score = 10.5;
    System.out.println(score);
    score = score + 2.1;
    System.out.println(score);
    score = score - 2.2;
    System.out.println(score);    
  }
}
```

This outputs 

```
10.5
12.6
10.4
```

## Other operators

`+` and `-` are called **operators**.

We can use other mathematical operators on ints and floats.

We can divide with `/`. We can multiply with `*`. We can find the remainder with `%`.

For example:

**code sample 7.4**
```java
class Main {
  public static void main(String[] args) {
    float score = 10.0;
    System.out.println(score);
    score = score * 2;
    System.out.println(score);
    score = score / 4;
    System.out.println(score);
    score = score % 2;
    System.out.println(score);    
  }
}
```

This will output: 

```
10.0
20.0
5.0
1.0
```

## Using parentheses `()` to specify order

Normal mathematical order applies: 

* multiplication, division and remainder first
* then addition and substraction
* left to right

In other words `1 + 3 * 4 / 2` is: 

0. `3 * 4` which equals `12`
0. Then `12` divided by `2` which equals `6`.
0. Then add `1`. Then answer is `7`.

This is called **operator precedence**.

We can use parentheses give a different order. When Java sees paraentheses it calculates everything inside those first, from left to right.

So `(1 + 3) * (4 / 2)` is:

0. `1 + 3` equals `4`
0. Then `4 / 2` equals `2`.
0. Then multiply `4` by `2`. The answer is `8`.


**code sample 7.5**
```java
class Main {
  public static void main(String[] args) {
    int number = (1 + 3) * (4 / 2);
    System.out.println(number);
  }
}
```

The output is:

```
8
```

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_7_0 (click on the pen icon near the top left)
0. Create a program that declares an int variable called `money`, then assigns `100` to that variable, then prints the variable, then multiples the variable by 50, then divides the variable by 2, and finally prints the variable again. 

And

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_7_1 (click on the pen icon near the top left)
0. Create a program that prints the result of `(10 + 1) * (10 / 5)` and on the next line the result of `10 + 1 * 10 / 5`.


## Questions to answer

0. Give five examples of mathematical operators we can use.
0. What is the operator precedence?
0. How can we specify a different order of operations?
