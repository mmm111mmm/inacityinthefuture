# Calling methods

We created methods in the last lesson. We will now **call** them.

When we **call** a method, Java runs the statements in that mehod.

At the end of the method, Java returns to where the method was **call**ed.

## Calling a method

The `main` method is where Java starts.

From `main`, we then **call** other methods. 

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

## Questions

0. What does calling a method do?
0. How do you call a method?
