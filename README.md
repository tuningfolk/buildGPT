# buildGPT
Let's see how far we can get with this one.

Broadcasting:
    Align the dimensions of the two operands to the right
    and then check each pair of dimensions
Train - (used to train the parameters)  
Validation - (used to train the hyperparameters)  
Test - (used to evaluate the perfomance at the end)  
  
As the model gets more complex and deeper, it becomes less forgiving, ie you need to fine-tune your hyperparameters very scrupulously.  

For a batch size of 32, 0.1 dangerously big to estimate the running mean and bias of the batch.  We have used 0.001 for the same batch size/