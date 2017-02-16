## Chapter2

> “Machine Learning will cause every successful IPO win in 5 years”
>    -Eric Schmidt (Google CEO)

### What is Deep Learning
**Deep Learning is a subfield of methods for machine learning**

Deep Learning is a subset of Machine Learning, which is a field dedicated to the
study and development of machines that can learn (sometimes with the goal of eventually
attaining General Artificial Intelligence). In industry, Deep Learning is used to solve
practical tasks in a variety of fields such as Computer Vision (Image), Natural Language
Processing (Text), and Automatic Speech Recognition (Audio). In short, Deep Learning is a
subset of methods in the Machine Learning toolbox, primarily leveraging Artificial Neural
Networks, which are a class of algorithm loosely inspired by the human brain.

#### 2 Main Types of Machine Learning
1. **Supervised**
    - Direct imitation of a pattern between two datasets.  
    - It is always attempting to take an input dataset and transform it to an output dataset
    - For Example:  Using the movies you've liked to predict movies you may like
    - Trying to use one dataset to predict the other.

2. **Unsupervised**
    - Find patterns in this data and tell me about them.
    - All forms of Unsupervised learning can be viewed as a form of clustering.


### Supervised Machine Learning
**Supervised Machine Learning transforms one dataset into another**

Supervised machine learning is the bread and butter of applied Artificial Intelligence.  it is useful for taking what we do know as input and quickly transforming it into what we want to know.  This allows supervised machine learning algorithms to extend human intelligence and capabilities in a seemingly endless number of ways.

### Unsupervised Machine Learning
**Unsupervised learning groups your data**

Shares property with supervised learning in that it transforms one dataset into another.  However with Unsupervised learning the dataset it transforms into is not previously known or understood.  There is right answer we are trying to duplicate. Common to start with a bunch of data points that are transformed into a bunch of labels.

### Parametric vs Non-Parametric Learning
**Oversimplified: Trial and error learning versus counting and probability**

Algorithms is either unsupervised or supervised and it is either parametric or Non-Parametric
parametricism is about the way the learning is stored and often by extension, the method for learning.

### Supervised Parametric Learning
**Oversimplified: Trial and error learning using knobs**

Supervised parametric learning machines are machines with a fixed number of knobs (that's
the parametric part), wherein learning occurs by turning the knobs. Input data comes in, is
processed based on the angle of the knobs, and is transformed into a prediction.

Learning is accomplished by turning the knobs to different angles.

**Example**

If we're trying to predict
the probability that the Red Socks will win the World Series, then this model would first
take data (such as sports stats like win/loss record or average number of toes) and make a
prediction (such as 98% chance). Next, the model would observe whether or not the Red
Socks actually won. After it knew whether they won, our learning algorithm would update
the knobs to make a more accurate prediction the next time it sees the same/similar input
data.

#### Steps

**Step 1: Predict**

Gather data send them through the "machine" and make a prediction on the probability of an outcome.

**Step2: Compare to truth pattern**

Compare the prediction with the pattern we care about


**Step3: Learn the pattern**

Adjust the knobs by studying both how much the model missed and what the input data was at the time of the prediction.  Then turn the knobs to make a more accurate prediction given the input data.  Each knob represents the prediction's sensitivity to different types of input data.  This is what we change when we "learn".

### Unsupervised Parametric Learning

Leverages similar approach.  Except that it uses knobs to group your data, and it normally has several knobs for each group.

### Conclusion
**Deep learning is Parametric**

Deep learning leverages neural networks to perform both supervised and non-supervised prediction.  Neural Networks are incredibly powerful parametric models that transform your input data into output data using a combination of matrices and differentiable functions.
 
