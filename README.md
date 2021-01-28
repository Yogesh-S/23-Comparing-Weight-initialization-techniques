# Weight-initialization-techniques-Fashion-MNIST-dataset

### Weight Initialization
In this notebook, we'll learn how to find good initial weights for a neural network. Weight initialization happens once, when a model is created and before it trains. Having good initial weights can place the neural network close to the optimal solution. This allows the neural network to come to the best solution quicker.
![alt text](https://github.com/Yogesh-S/23-Comparing-Weight-initialization-techniques/blob/main/neuron_weights.png?raw=true)
### Initial Weights and Observing Training Loss

To see how different weights perform, we'll test on the same dataset and neural network. That way, we know that any changes in model behavior are due to the weights and not by virtue of data or model structure.

#### `Let us consider 7 different cases of weight initialization and see how the training loss decreases over time.`
>``` 
>  • Initialilize all 0s
>  • Initialize all 1s
>  • Weights from Uniform Distribution, Range(0,1)
>  • Weights from Uniform Distribution, Range(-.5,.5)
>  • Weights from Uniform Distribution, Range(-1/√n,1/√n); n - input to the node
>  • Weights from Normal Distribution, Range(-1/√n,1/√n); n - input to the node
>  • Auto Initialization (No explicit initialization); directly call model_func()


Sometimes the differences in training loss, over time, will be large and other times, certain weights offer only small improvements.
