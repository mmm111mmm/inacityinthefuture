## Using `+=` to concatenate

We saw the code `status = status + " and healthy"`.

This means 

* get the value of `status` (i.e. `"I am fine"`)
* add the string `" and healthy"` to the end
* assign that to the variable `status`.

This is a very common thing to do. Java has a shortcut: `status += " and healthy"`.

For example this program

**code sample 6.2**
```java
class Main {
  public static void main(String[] args) {
    String status = "I am fine";
    System.out.println(status);
    status += " and healthy";
    System.out.println(status);
  }
}
```

outputs the same as the previous program:

```
I am fine
I am fine and healthy
```

0. What is the long form of `name += "!";`?


0. What is the long form of `name += "!";`?

## Adding to an int with `+=`

We saw the code `age = age + 10`.

This means

0. get the value of age (i.e. `36`)
0. add ten to that (i.e. `47`)
0. assign that to the variable `age`.

This is a very common thing to do. Java has a shortcut: age += 10.

For example this program

**code sample 7.2**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age += 10;
    System.out.println(age);
  }
}
```

outputs the same as the previous program:

```
36
46
```


## Subtracting from an int with `-=`

We saw the code `age = age - 10`.

This means

0. get the value of age (i.e. `36`)
0. subtract ten from that (i.e. `27`)
0. assign that to the variable `age`.

This is a very common thing to do. Java has a shortcut: age -= 10.

For example this program

**code sample 7.4**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age -= 10;
    System.out.println(age);
  }
}
```

outputs the same as the previous program:

```
36
26
```

## Adding to an int with `++`

Often we want to type: `age = age + 1;`.

Java has a shortcut for this, `++`. For example:

**code sample 7.5**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age++;
    System.out.println(age);
  }
}
```

outputs the same as the previous program:

```
36
37
```


## Substracting from an int with `--`

Often we want to type: `age = age - 1;`.

Java has a shortcut for this, `--`. For example:

**code sample 7.5**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println(age);
    age--;
    System.out.println(age);
  }
}
```

outputs the same as the previous program:

```
36
35
```
