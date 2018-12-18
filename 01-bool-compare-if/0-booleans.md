# 0. Booleans

## A new data type

We learnt about ints, floats and strings.

But there is another very important data type: a boolean.

This is named after a man called George Bool.

It is a very simple data type. It can either be `true` or `false`.

But it is very powerful. And in later lessons we will see how.

## Using a boolean

We declare a boolean with the name `boolean`. And we can assign to is as `true` or `false`.

**code sample 1.0.0**
```
class Main {
  public static void main(String[] args) {
    boolean happy = true;
    System.out.println(happy);
  }
}
```

We can also concatenate it onto a string:

**code sample 1.0.1**
```
class Main {
  public static void main(String[] args) {
    boolean tired = true;
    System.out.println("I am tired: " + tired);
    tired = false;
    System.out.println("I am tired: " + tired);
  }
}
```

In the next lessons, we will look at booleans a lot more.

## Questions to answer ##

0. What two values can a boolean be?
