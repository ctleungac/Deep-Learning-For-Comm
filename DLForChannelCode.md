#### 1. Deep learning methods for improved decoding of linear codes [journal]
  
**Code Selection**: LDPC code
 
**Methods**： RNN

**Description**: 
*Trellis Representation* : Tanner Graph -> Trellis Graph. *l* = number of iterations. *E* = number of edges = nodes in each hidden layer. *N* = code block length = number of variable nodes in the Tanner Graph.

*Deep Learning Model*: input layer is log-likelihood (LLR) of channel outputs with dimensions 1xN. $L(x_i) = \frac{2y_i}{\sigma}$
