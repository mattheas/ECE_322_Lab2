# ECE_322_Lab2

Lab 2 explores more semi-formal Black Box testing techniques like Extreme Point Combination (EPC) and Weak nx1 testing strategy on the provided exectuable files Drone.jar and RemoteCar.jar.


## Task1:

Task 1 concerns the Drone.jar executable and EPC. The drone software has a non-trivial explanation that is discussed in full in the lab manual. In short the command line program takes 3 inputs, where each input is bound by a certain range. Using the EPC approach you look at extreme point combinations of all inputs, with the extreme points being slightly under min, min, max & slighlty over max, for each variable. In the case of 3 variables this yields 64 tests cases + 1 for an interior point. The Weak nx1 approach was also used and a set of test cases were generated which were in turn compared to the EPC test suite. 


## Task2:

Task 2 concerns the RemoteCar.jar which also has a non-trivial explanation discussed in the lab manual. The input domain must be approximated with 4 linear boundaries as specified in the manual before the EPC & Weak nx1 testing approach can be conducted. Again the two testing approaches are compared with a major limitation of the EPC testing strategy being discovered (i.e shape of approximated subdomain). 
