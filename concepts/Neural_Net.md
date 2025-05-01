
- No of classes = no of neurons
- weights are decided by neurons in the prev layer

![alt text](image-4.png)


<br/>

In the above pic y1 = cat, y2= dog if there was a third class it would be called y3

- z= w0 + (Xt*W)
- w0 = bias, Xt = features, W = weights


### WRT 'Z2' neuron from hidden layer

![alt text](image-5.png)

<br/>

### How do neural net learn? 

- First pass 

<br/>

![alt text](image-6.png)

<br/>

- To update the model we then use empiral loss:
    - MSE

    ![alt text](image-8.png)
    
    - Cross Entropy loss
    
    ![alt text](image-9.png)

### Computing Losses

- Then we look for weights that will minimize our losses through a function like **Gradient Descent**   

<br/>

![alt text](image-7.png)

<br/>


![alt text](image-10.png)

### Updating Loss

<br/>

![alt text](image-11.png)

<br/>
