# 0. Duplication and methods

In our weather project there was duplication.

We had the same if-else statements. The variables were different but the statements were the same.

## Another example of duplication

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

A method tells Java to do the something. You can do this something many times. But you only type the method once.

In the next lessons we will look at methods. At the end of the lessons you will use methods to remove this duplication.

## Excerise

0. No exericses so far but we'll have one next lesson

## Questions

0. What does a method do?
