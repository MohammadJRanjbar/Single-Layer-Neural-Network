# Single-Layer-Neural-Network
Implementation of "and" function with single layer neural network
# AND: 
The AND gate is a basic digital logic gate that implements logical conjunction - it behaves according to the truth table provided below.

<img src="Image/And.png" width="200" class="center" />

# Neural Network: 
logic gates like “OR”, “AND” or “NAND” can have 0's and 1's separated by a single line. As you can see in the picture below we have a blue and orange class which we can sperate using a single line, therefore, we use single layer neural network to implemnet this gate.

<img src="Image/AB.png" width="200" class="center" />

in addition to the input data(A, B) We added a Bias=1 to the network, it is somehow similar to the constant b of a linear function

y = ax + b

It allows you to move the line up and down to fit the prediction with the data better.

<img src="Image/NN.png" width="200" class="center" />

You can run this code from your terminal/prompt/shell with typing
```python
python Perceptron.py
```
