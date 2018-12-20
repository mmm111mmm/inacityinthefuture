# 9. Weather project

We have learnt about 

* booleans
* combining booleans
* using parentheses with booleans
* making booleans from number comparisons
* if statements
* if-else statements
* else statements.

## The weather project

We will create a project that looks at the weather and tells us if we should:

* wear a coat or not
* take an umbrella or not
* wear shorts or jeans
* wear sunglasses or not

For the morning, afternoon and evening.

## Weather data

We can get the weather data from the internet. But we have not learnt enough Java for that yet.

So we will use booleans at the moment. In later lessons we will learn how to get the weather data from the internet.

Then we will update this project.

## Design of the project

We will use booleans to specify the weather. The weather can be very complex but we will simplify the weather for our program. 

The weather can:

* be raining or not
* can have a temperature (0.0, 20.0, 30.0, etc)
* can have minutes of sunlight (0 minutes, 160 minutes, etc)

Our logic will be like this

* If it is raining, take a coat
* If it is raining, take an umbrella
* If it above 25.0 degrees, wear shorts
* But even if it is above 25.0 and it is raining, wear jeans
* If there is more than or equal to 160 minutes of sunshine, wear sunglasses
