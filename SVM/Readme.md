 # Support Vector Machine 
 
  SVM is a supervised learning model that looks at data and sort it into one of the two categories. 
  It analyze the data for classification and regression analysis. 
  
  
  ### Support vectors 
  Supprt Vectors are the extreme points of the data set.
  
  ### Hyperplane :
  Hyper plane has the maximum distance between two support vectors of any classes.
  Hyperplane is just not a line but a plane of intersections.
  
  ### MATH Behind the SVM :
  1. We will take D+ as the shortest distance to the closest positive point. 
  2. and We will take D- as the shortest distance to the closest negative point.
  3. Sum of the D+ and D- is called the distance margin.

After finding the optimal distance margin we will get the optimal hyperplane. Based on the new hyperplane we can decide where will be the data optimized.
Once we created the optimal hyperplance we can see in which side the new data point can fits.


### What happens when we select a hyper plance with low margins :
If we select a hyperplane with low margin their is a chance of misclassification.
