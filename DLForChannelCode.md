#### 1. Deep learning methods for improved decoding of linear codes [journal]
  
**Code Selection**: LDPC code
 
**Methods**： RNN

**Description**: 
*Trellis Representation* : Tanner Graph -> Trellis Graph. *l* = number of iterations. *E* = number of edges = nodes in each hidden layer. *N* = code block length = number of variable nodes in the Tanner Graph. e = (v,c) each edge.

*Deep Learning Model*: input layer is log-likelihood (LLR) of channel outputs with dimensions 1xN. (LLR in AWGN: $L(x_i) = \frac{2y_i}{\sigma}$); 
Input node associate to one variable node.

Hidden layer has size E. Each neurons associate with message transmitted over edges.
For odd hidden layer, each neuron outputs the message over corresponding edge, transmitted from variable node to check node. (for even layer is opposite)

For all hidden nodes in layer *i*, (odd) is connected to all nodes in layer *i-1* associated with the edges e'=(v,c') for all *c'!=c*, and also connected to the v-th input node.
