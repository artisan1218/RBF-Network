# RBF-Network
Python implementation of Radial Basis Function network with no external packages

### Sample data setup
Function defination: 

where x ranges from 0~1 and the noise ranges from -1 to 1

![image](https://user-images.githubusercontent.com/25105806/113526487-17e93500-956f-11eb-83e8-341c9bbfa64a.png)


The final curve looks like this:

![image](https://user-images.githubusercontent.com/25105806/113526244-28e57680-956e-11eb-835a-d2588bf3dd16.png)

### Training process
The training process includes forward-pass, backward-pass and online update for the weights. Using k-means to dertermine the centers and variance of the training data and use these two parameters as the initial setup

### Result
![image](https://user-images.githubusercontent.com/25105806/113526204-f9366e80-956d-11eb-980b-e0318db205ae.png)
