# 4. More combined boolean logic

## Combined boolean logic

Let's look at some more combined logic:

`false && false || true`

The first part `false && false` is `false`. 

So we take that result, and look at the second part `... || true`.

And so that is `false || true`.

So the result is `true`.

## Combined boolean logic with a different order

The result above worked because we did `false && false` first.

But what if we do the second part (`false || true`) first? 

The result of that is `true`. 

Now let's look at the first part again, `false && ...`.

Now let's use our result with the first part, `false && true`.

So the result is `false`.

## Combined boolean logic with parenthesis

In the last section we decided to look at `false || true` first.

We can make Java do this by using parenthesis, `()`.

So these two boolean logic statements have different results: 

0. `false && false || true` is `true`
0. `false && (false || true)` is `false`

**code sample 1_4_0**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("false && false || true:" +  false && false || true);
    System.out.println("false && (false || true)" + false && (false || true));
}
```

The output is:

```
false && false || true: true
false && (false || true): false
```

## Questions to answer ##

0. In boolean logic, what do pathensises do?
