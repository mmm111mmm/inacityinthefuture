## 0. Duplication and methods

In our weather project there was duplication.

We had the same if-else statements. The variables were different but the statements were the same.

# Another example of duplication

Here's an example of the same problem:

**code sample 2_0_0**
```java
class Main {
  public static void main(String[] args) {
  
    float morningWeatherTemperature = 18.0f;
    
    if(morningWeatherTemperature > 23.0f) {
      System.out.println("Wear shorts and a t-shirt.");
    } else if(morningWeatherTemperature > 17.0f) {
      System.out.println("Wear jeans and a t-shirt.");    
    } else {
      System.out.println("Wear jeans and a pullover");    
    }
    
    float afternoonWeatherTemperature = 25.0f;
    
    if(afternoonWeatherTemperature > 23.0f) {
      System.out.println("Wear shorts and a t-shirt.");
    } else if(afternoonWeatherTemperature > 17.0f) {
      System.out.println("Wear jeans and a t-shirt.");    
    } else {
      System.out.println("Wear jeans and a pullover");    
    }    
    
    float eveningWeatherTemperature = 10.0f;    

    if(eveningWeatherTemperature > 23.0f) {
      System.out.println("Wear shorts and a t-shirt.");
    } else if(eveningWeatherTemperature > 17.0f) {
      System.out.println("Wear jeans and a t-shirt.");    
    } else {
      System.out.println("Wear jeans and a pullover");    
    }    

  }
}
```

The logc in the if-else statments is the same. Only the variables differ.

## Getting rid of the duplication: methods

In Java we use methods to remove this duplication. (In some languages, functions are used and do a similar thing).

A method tells Java to do the something many times but you only type the method once.

## What does a method look like?

You know this already. But you don't know you know. Look at this outline of Java program:

```
class Main {
  public static void main(String[] args) {
  }
}
```

Lines two and three are the start and end of a method.

We told you to ignore these lines (just type them) at the start of the course.

Now we will explain them (or at least partially).

## Explaining the method

The method you typed many times starts like this `public static void main(String[] args)`.

It contains

0. the word `public`
0. the word `static`
0. the word `void`
0. its name -- we will look at this later
0. an openening parenthesis, `(`
0. the text `String[] args` -- which we look at later
0. a closing parenthesis, `)`

