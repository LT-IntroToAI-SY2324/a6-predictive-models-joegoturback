# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
The rsquared value for my data is 0.86 when I ran it. 

2. Is your model accurate? Why or why not?
The model is accurate for the most part, however some of the predicted values stray far away from the actual values for some of the cars.

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
a 12 year odl car with 145000 miles is worth 5300, and a 20 year old car with almost 200,000 miles is worth -389 dollars.

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening? 
I think this is because the computer's predictions follow a linear way of calculating the car's worth based off the mileage and age, so for cars that have traveled very far and/or is very old, the value can go under zero, which we know of course is inaccurate.