# CS256_ann_practice_assmt

Following things are implemented in this assmt:-

1. In function minibatch_random_generator(), 32 data samples are randomly chosen to form a mini data batch for finding gradient descent.

2. In the 2nd part I have implemented 3 methods for annealing of the learning rate.
Line 126-134 have these 3 functions.
Uncomment  corresponding lines to run one of the moethods.
Right now, 1/t decay method is in use.

3. In third change I have used sigmoid function instead of tanh function for forward propogation(changes for forward propogation are made at 3 places, line 52,69,101). In the backpropgation i have used derivative of sigmoid, which is 'sigmoid_function(x)(1-sigmoid_function(x))'-> change on line 114.

Pls note that train_img.csv was too big a file. So use alternate data or use some portion of test data for training and some for testing.
