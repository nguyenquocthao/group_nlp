### k-fold
- Steps for k-fold cross-validation :
    1. Split data into k subsets of equal size
    2. For each subset, use that subset to validate, the remainder for training and calculate error estimates
- The subsets are often stratified before the cross validationis performed
- Final error estimates is average of error estimates for each time.
- K-fold helps error estimates more accurate
![k-fold](images/k-fold.png)