#### 1. Deep learning methods for improved decoding of linear codes [journal]
  
**Code Selection**: LDPC code
 
**Methods**： RNN

**Description**: 
*Trellis Representation* : Tanner Graph -> Trellis Graph. *l* = number of iterations. *E* = number of edges = nodes in each hidden layer. *N* = code block length = number of variable nodes in the Tanner Graph.

*Deep Learning Model*: input layer is log-likelihood (LLR) of channel outputs with dimensions 1xN. (LLR in AWGN: $L(x_i) = \frac{2y_i}{\sigma}$);
Hidden layer has size E. 

Each neurons associate with message transmitted over edges.

For odd hidden layer, each neuron outputs the message transmitted 


