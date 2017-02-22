# Introduction to Neural Prediction

### Step 1: Predict
**This chapter is about prediction**

**What is input data?**

It's a number that we recorded in the real world somewhere. It's usually something
that is easily knowable, like today's temperature, a baseball player's batting
average, or yesterday's stock price

**What is a prediction?**

A prediction is what the neural network tells us given our input data such as
"given the temperature, it is 0% likely that people will wear sweatsuits today" or
"given a baseball player's batting average, he is 30% likely to hit a home run" or
"given yesterday's stock price, today's stock price will be 101.52".

**Is this prediction always right?**

No. Sometimes our neural network will make mistakes, but it can learn from
them. For example, if it predicts too high, it will adjust it's weight to predict lower
next time and vise versa.

**How does the network learn?**

Trial and error! First, it tries to make a prediction. Then, it sees whether it was
too high or too low. Finally, it changes the weight (up or down) to predict more
accurately the next time it sees the same input.

### Making a Prediction with Multiple Inputs
**Neural Networks can combine intelligence from multiple datapoints**
