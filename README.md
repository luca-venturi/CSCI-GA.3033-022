# CSCI-GA.3033-022
NYU CIMS 'Deep Generative Models' course

https://cs.nyu.edu/courses/spring18/CSCI-GA.3033-022/

## Final Project - Numerical Tests

The aim is to understand if sub-optimal discriminator in GANs define a meaning-ful distance between two distributions.
We generated two sets of Gaussian distributions. The first set consists of one fixed distribution P.
The second set consists of a collection of distributions Q_i approaching P in some sense.
For each Q_i we train a classic GAN discriminator (100 rounds, with L2 regularization) and we report the loss.

### Test 1

In this case P is taken to be a d-dimensional standard Gaussian distribution projected on the vector e_1.
Q_i is taken to be a d-dimensional standard Gaussian distribution projected on a vector v_i.
The vectors v_i converge to e_1 as i increases. 
The plot below reports the loss as a function of i.

![Loss](test1.png)

Here i belongs to {0.,0.1,...,0.9,1.}

### Test 2

In this case P is taken to be a d-dimensional standard Gaussian distribution projected on the vector e_1.
Q_i is taken to be a d-dimensional standard Gaussian distribution projected on a vector v_i.
The vectors v_i converge to e_1 as i increases. 
The plot below reports the loss as a function of i.
