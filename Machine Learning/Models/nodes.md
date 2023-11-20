
## Activation Functions

### Step-Function/threshold 
$$
\text{F}(x) =
\begin{cases} 
      1 & x\leq 0 
      \\
      0 & x\geq 0 
\end{cases}
$$
![[nodes-20231120140409278.webp|219]]
### Linear

$$\text{F}(x) = x$$
  
![[nodes-20231120141152171.webp|227]]
### Non-Linear
#### Soft-max

  $$\text{Softmax}(x_{i}) = \frac{\exp(x_i)}{\sum_j \exp(x_j)}$$
  
  
#### Sigmoid/Logic  11-Function
##### Equation 
$$\sigma(z) = \frac{1} {1 + e^{-z}}$$

![[nodes-20231120140120487.webp|225]]

## Links
-  [Softmax Activation Function || Softmax Function || Quick Explained || Developers Hutt - YouTube](https://www.youtube.com/watch?v=8ah-qhvaQqU&t=12s) 
- [Activation Functions | Deep Learning Tutorial 8 (Tensorflow Tutorial, Keras & Python) - YouTube](https://www.youtube.com/watch?v=icZItWxw7AI)
- [Activation Functions in Neural Networks [12 Types & Use Cases]](https://www.v7labs.com/blog/neural-networks-activation-functions)