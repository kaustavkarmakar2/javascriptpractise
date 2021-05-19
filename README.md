# javascriptpractise
# Question1:
The function getEldest should return the name of the eldest person in the given array.
# Question2:
In The Netherlands, many people go crazy about ice skating on the natural lakes.
Unfortunately for those people it doesn't happen very often that this is possible.

Complete the function below that takes an array of weather data and gives the first date when it will be possible to skate.
If it is not possible it should return the string 'Helaas pindakaas'. Which in Dutch literally means 'Too bad peanutbutter', the peanutbutter is just there for the rhyme.
This function calculates the first day it will be possible to skate in the given data or sends back 'Helaas pindakaas' if it is not possible.
 *
 * The data parameter should be an array of objects. Those objects should have 3 properties:
 *   - date: The date that the temperatures are for
 *   - lowestTemperature: The lowest temperature measured on that day
 *   - highestTemperature: The highest temperature measured on that day
 *
 * To determine if you can skate weeronline says that the temperature should not go above 0 (so 0 is fine) for 5 consecutive days. It is then possible to skate on the day after those 5 days
 # Question3: 
 Let's make a calculation function to solve all calculation issues in one place.
 *
 * The function should take an array of numbers as the first value, and a string representation of the operator as a second parameter.
 * It returns the result of the calculation.
 *
 * At the bottom of the file there is some test code that will log the result to the console. You can use this to check that your code is correct.
 # Question4: 
 Debug and refactor time!

The code below is written without modern js functionality in mind and has some issues.
It is your job to rewrite the code so that the tests at the bottom pass, and that the code is easy to follow.

This code is meant to be hard to follow and have no explanation, 
it is part of the test to see if you can read this code and understand what it is meant to do.
# Question5: 
 A careless developer has defined the password in such a way that the hack function that was injected below got access to the password.
