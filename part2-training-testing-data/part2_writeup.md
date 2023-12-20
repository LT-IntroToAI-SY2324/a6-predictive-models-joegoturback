# Part 2 - Training and Testing Data Writeup

After completing `a6_part2.py` answer the following questions

## Questions to answer

1. What makes this model more effective than the model you created in the previous lesson?
Part 1's graph uses only testing data to determin the line of best fit. Part 2 uses training data, which are the all the plots on the graph that it reads to make a better prediction. I think that this is because part 2's graph omits the outliers of the graph and mainly includes the points that are closer together, leading to a better overall prediction. 

2. What does the R squared coefficient tell you about the model?
The R square coefficient shows that the graph has slightly more reliable results, as it was 0.65, as opposed to 0.60 in part 1.

3. Would you say that your model is accurate? What evidence supports your conclusion? Consider the meaning of the predicted and actual values in the context of the chart below from the American Heart Association’s website on understanding blood pressure.
I would say the model is somehwt accurate compared to the charts I saw online, but only for the yonunger ages. The estimations for people over 50 were a lot higher in the model's predictions than the healthy levels I saw online for those ages.