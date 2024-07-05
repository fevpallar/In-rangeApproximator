**My netwrk. specification summary:**

- neurons for the hidden layer (with bias ($b$)) is

```math
H_{n, l}= 1/ ( 1+ exp( -(\sum_{j=1}^{N}w_{j} * I_{j})+b_{k}) )) 
```
where $n\in\\{1,2,.,5\\}$ in _layer_ ($l$) $\in\\{1,2,.,9\\}$ and $k\in\\{1,2\\}$

- neuron for the final output layer (with bias($b$)) is

```math
O = 1/ ( 1+ exp( -(\sum_{j=1}^{N}w_{j} * H_{n, l})+b_{k}) )) 
```


<ins>The backward-pass</ins>

Then the weight($w$) & bias($b$) adjustment ( with error $E$ ) is


$\partial{E} / \partial{w_{jk}}$ where $j \in \\{1,2,..,5\\}$ and $k\in\\{I,H,O\\}$

$\partial{E} / \partial{b_{k}} ,  k \in \\{1,2,..5\\}$

---



![TrainingOutput](https://github.com/fevpallar/In-rangeNeuralNet/assets/17115595/a7fadfc9-5c00-4828-88a2-6dcf7deca3c5)


![9H](https://github.com/fevpallar/In-rangeNeuralNet/assets/17115595/4ca8b79a-5ce4-48bb-9dd2-b8d48884663e)


