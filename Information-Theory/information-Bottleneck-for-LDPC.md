### Information bottleneck processing

Coarse quantization -> small bit width.

Mutual information is independent of representation values:
![image](https://user-images.githubusercontent.com/25514021/115112179-dcab2500-9fb6-11eb-8864-dc8a609a16b8.png)

$I(X;Y) = \sum_{x}sum_y p(x,y) log \frac{p(x,y)}{p(x)p(y)}$

log-likelihood ratio:

For long LDPC code
- wiring (routing) is the major problem
- unrolled architecture
- Serial message transfer  -> become bottleneck for high throughput decoding -> low bit-width required![image](https://user-images.githubusercontent.com/25514021/115112175-d9b03480-9fb6-11eb-89b8-6a8f51ae1974.png)

