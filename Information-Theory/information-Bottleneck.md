<script type="text/javascript"<src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>

### Information bottleneck processing

Coarse quantization -> small bit width.

Mutual information is independent of representation values:

\begin{equation}\begin{split}
H(Y|X)&=\sum_{x\in X} p(x)H(Y|X)\\
&=-\sum_{x\in X} p(x)\sum_{y\in Y}p(y|x)\log p(y|x)\\
&=-\sum_{x\in X} \sum_{y\in Y}p(y,x)\log p(y|x)
\end{split}\end{equation}
