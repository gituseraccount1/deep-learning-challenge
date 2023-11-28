# Report

Alphabet Soup, a nonprofit foundation, is trying to figure this following question:  Which applicants will have the best chance of success in their ventures Alphabet Soup would want to fund? We can use machine learning, specifically neural network, to help Alphabet Sound with their question. 

They have provided a CSV containing more than 34,000 organizations that has received funding from them over the years. There are three main steps we need to do with the data:
1.	Preprocess the Data
2.	Compile, Train, and Evaluate the Model
3.	Optimized the Model

For my “y” variable, I used the “IS_SUCCESSFUL” column which consists of 1s and 0s. For my “X” variable, I used the rest of the columns besides the “IS_SUCCESSFUL” column.

You will see two different jupyter files:
1. Starter_code
2. OptimizedModel

The starter code model had a accuracy of 0.73411 while my OptimizedModel model had a 0.733877. This was interesting since I added a second hidden layer and expected the accuracy to increased, in my case it decreased.