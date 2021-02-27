# Cifar10

The CIFAR-10 small photo classification problem is a standard dataset used in computer vision and deep learning.

The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc. The class labels and their standard associated integer values are listed below.

0: airplane   

1: automobile                                                                            

2: bird

3: cat

4: deer

5: dog

6: frog

7: horse

8: ship

9: truck

we use 50,000 for train and 10,000 as test data set.
PCA(We have applied Principal Conponent Analysis by rotating axis of graph between all possible feature pair and calculated Eigen vectors,Eigen values in direction and reduced the data from 60,000x32x32x3 to 60,000x658 maintaning 99% of information intact.
We than further used the data with different Machine Learning algorithms like:

Decision Tree.

Random Forest.

Naive Bayes.

Support vector Machine.

K nearest neighbors.

and check which one works best to predict the category photo belongs to. This can be used in: 
# Recaptcha, I am not a robot
