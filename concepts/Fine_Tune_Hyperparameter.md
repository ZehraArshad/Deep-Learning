## Hyperparameters


### Hidden Layers

- Rather than having a single layer with losts of neurons, add multiple layers with less neurons
- Continue to increases hidden layers until you start to overfit



### Neurons / Layer

- Input layer = equal to features
- Output layer -> Reg = one, classification = classes
 #### Hidden Layers
- People used to think that payramid (increase -> dec of neurons *left to right* was useful but it was false)
- Neurons should be sufficients esp in the first layers as they capture small details. If we loose these details we cannot recover them later on. 
- Beg layers are also used as base in other models -> **Transfer Learning**


### Learning Rate

### Optimizer

### Batch Size
- Small batch size -> better results on new data but very slow
- Large batch size (depends on GPU Ram) -> gradually increase learning rate -> this is called *warming up the learning rate*. It is also fast.

### Epoch 

- Apply early stopping
