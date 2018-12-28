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

We will use booleans at the moment. In later lessons we will learn how to get the weather data from the internet.

Then we will update this project.

## Design of the project 1

We will use booleans to specify the weather. The weather can be very complex but we will simplify the weather for our program. 

The weather can:

* be raining or not
* can have a temperature (0.0, 20.0, 30.0, etc)
* can have minutes of sunlight (0 minutes, 160 minutes, etc)

Our logic will be like this. *(note: there will be multiple if statements.)*

* If it is raining, take a coat
* If it is not raining, and below or equal to 20.0, take a coat
* If it not raining, and the temperature is above 20.0, don't take a coat
* If it above 20.0 degrees, wear shorts
* If it is below or equal to 20.0, wear jeans
* If it is above 20.0 and it is raining, wear jeans
* If there is more than 160 minutes of sunshine, wear sunglasses
* If there is less than or equal to 160 minutes of sunshine, don't wear sunglasses
* If it is raining, take an umbrella
* If it is not raining, don't take an umbrella

## Design of the project 2

We will first set the boolean for raining, the float for temperature and the int for minutes of sunshine.

Then we will have `if`, `if else` and `else` statements. They will deal with the above logic.

In the if else statements we will use `System.out.println` to tell the user if they should wear a coat or not, etc.

We will do the same thing but we will use a new boolean, int and float for the afternoon weather.

We will do the same thing but we will use a new boolean, int and float for the evening weather.

## Sample output

```
IN THE MORNING:
Take a coat
Wear jeans
Wear sunglasses
Don't take an umbrella
IN THE AFTERNOON:
Take a coat
Wear jeans
Wear sunglasses
Don't take an umbrella
IN THE EVENING:
Take a coat
Wear jeans
Don't wear sunglasses
Take an umbrella
```

## Duplication

Your program should have duplicated `if`, `if else` and `else` statements but with different boolean variables for the morning, afternoon and evening.

Don't worry. We will fix this in the next module.

## Start

Now go to repl.it and call the file `project_1_weather`.

## Tests

Make sure your project does this:

0. If the morning weather is raining, has a temperature above 20.0, then use see the text `"Wear a coat"`
0. If the morning weather is not raining, has a temperature above 20.0, then use see the text `"Don't wear a coat"`
0. If the morning weather is not raining, has a temperature above 20.0, then use see the text `"Wear shorts"`
0. If the morning weather is raining, has a temperature above 20.0, then use see the text `"Wear jeans"`
0. If the morning weather is raining, has a temperature above 20.0, then use see the text `"Take an umbrella"`
0. If the morning weather is not raining, has a temperature above 20.0, then use see the text `"Don't an umbrella"`
0. If the morning weather is raining, and we have 180 minutes of sunshine, then use see the text `"Wear sunglasses"`
0. If the morning weather is raining, and we have 160 minutes of sunshine, then use see the text `"Don't sunglasses"`

Make sure this is also true for the weather in the afternoon and evening.

## Congratuations

You've now completed a project that demonstrates everything we learnt in this module.
