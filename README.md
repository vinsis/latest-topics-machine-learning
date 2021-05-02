Links to some important research papers or links. I plan to add notes as I go through each topic one by one.


## ✔ 1. Information theory based (unsupervised) learning
* [x] [Invariant Information Clustering](https://arxiv.org/abs/1807.06653)
   * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/iic.md)
* [x] [Mutual Information Neural Estimation](https://arxiv.org/abs/1801.04062)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/mine.md)
* [x] [Deep Infomax](https://arxiv.org/abs/1808.06670)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/deepinfomax.md)
* [x] [Learning Representations by Maximizing Mutual Information Across Views](https://arxiv.org/abs/1906.00910)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/amdim.md)
* [x] How Google decoupled MI maximization and representation learning: [On Mutual Information Maximization for Representation Learning](https://arxiv.org/abs/1907.13625)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/on_mi_maximization.md)

---

## 1.1 Self-supervised learning
* [ ] Emerging Properties in Self-Supervised Vision Transformers [PDF](https://arxiv.org/pdf/2104.14294.pdf) | [Official Code](https://github.com/facebookresearch/dino)

---

## ✔ 2. Disentangled representations
* [x] [Quick overview by Google](https://ai.googleblog.com/2019/04/evaluating-unsupervised-learning-of.html)
  *  [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/unsupervised_disentanglement.md)
* [x] [β-VAE, pdf](https://openreview.net/pdf?id=Sy2fzU9gl)
  *  [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/betavae.md)
* [x] [Understanding disentangling in β-VAE](https://arxiv.org/abs/1804.03599)
  *  [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/understanding_betavae.md)

```
Decided not to delve deeper into this topic. It is not mature yet.
* [Disentangling Disentanglement in Variational Autoencoders](https://arxiv.org/abs/1812.02833)
* [Isolating Sources of Disentanglement in Variational Autoencoders](https://arxiv.org/abs/1802.04942)
* [InfoGAN-CR: Disentangling Generative Adversarial Networks with Contrastive Regularizers](https://arxiv.org/abs/1906.06034)
* [Disentangling by Factorising, pdf](https://www.cs.toronto.edu/~amnih/papers/disentangling_nips_ws.pdf)
```
---

## ✔ 3. Contrastive Coding
* [x] [Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)
* [x] [Data-Efficient Image Recognition with Contrastive Predictive Coding](https://arxiv.org/abs/1905.09272)
  *  [__Combined notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/contrastive_predictive_coding.md)
* [x] [Contrastive Multiview Coding](https://arxiv.org/abs/1906.05849)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/cmc_notes.md)
* [x] [Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/moco.md)
* ~~Google dispelling a lot of misconceptions about disentangled representations~~: [Challenging Common Assumptions in the Unsupervised Learning of Disentangled Representations](https://arxiv.org/abs/1811.12359)
  * I have become sort of disillusioned with disentangled representations. I feel they are not at a mature stage yet. So I have decided not to spend time on this paper.

---

## ✔ 4. Automatic differentiation
* [x] [Automatic differentiation in machine learning: a survey](https://arxiv.org/abs/1502.05767)
  * [__Annotated pdf__](https://github.com/vinsis/math-and-ml-notes/blob/master/pdfs/1502.05767.pdf)
* [x] [Automatic Reverse-Mode Differentiation: Lecture Notes](http://www.cs.cmu.edu/~wcohen/10-605/notes/autodiff.pdf)
  * [__Annotated pdf__](https://github.com/vinsis/math-and-ml-notes/blob/master/pdfs/autodiff.pdf)
* [x] [Reverse mode automatic differentiation](https://rufflewind.com/2016-12-30/reverse-mode-automatic-differentiation)

---

## 5. NNs and ODEs
* [ ] [Neural Ordinary Differential Equations](https://arxiv.org/pdf/1806.07366.pdf)
  * [ ] [Adjoint tutorial](https://cs.stanford.edu/~ambrad/adjoint_tutorial.pdf)
* [ ] [Augmented Neural ODEs](https://arxiv.org/abs/1904.01681)
* [ ] [Invertible ResNets](https://arxiv.org/pdf/1811.00995.pdf)
* [ ] [Universal Differential Equations for Scientific Machine Learning](https://arxiv.org/abs/2001.04385)

---

## 6. Probabilistic Programming
* [x] [Probabilistic models of cognition](http://probmods.org/)
  * [__Notes__](https://github.com/vinsis/math-and-ml-notes/blob/master/notes/probmods/)
* [ ] [The Design and Implementation of Probabilistic Programming Languages](http://dippl.org)
* [ ] [Composition in Probabilistic Language Understanding](http://gscontras.github.io/ESSLLI-2016/)

---

## 7. Miscellaneous
### Memorization in neural networks
* [Blog post by BAIR](https://bair.berkeley.edu/blog/2019/08/13/memorization/)
* [Identity Crisis: Paper](https://arxiv.org/abs/1902.04698)

### Online Learning
* [A Modern Introduction to Online Learning](https://arxiv.org/abs/1912.13213)

### Graph Neural Networks
* [ ] [A Gentle Introduction to Deep Learning for Graphs, pdf](https://arxiv.org/pdf/1912.12693.pdf)

### Normalizing Flows
* [x] [Tutorial and implementations for UCB DUL course](https://github.com/TinyVolt/normalizing-flows)

### Transformers
* [x] [Attention is all you need](https://arxiv.org/abs/1706.03762)
  * [x] [A nice visual introduction](http://jalammar.github.io/illustrated-transformer/)
  * [x] [Annonated paper](http://nlp.seas.harvard.edu/2018/04/03/attention.html)
  * [__Python notebook with illustrations and working code__](https://github.com/vinsis/math-and-ml-notes/blob/master/notebooks/Transformer%20-%20Illustration%20and%20code.ipynb)
* [Reformer: The Efficient Transformer](https://arxiv.org/abs/2001.04451)

### Others
* [Zero-shot knowledge transfer](https://arxiv.org/abs/1905.09768)
* [SpecNet](https://arxiv.org/abs/1905.10915)
* [Deep Learning & Symbolic Mathematics](https://arxiv.org/abs/1912.01412)
* [Deep Equilibrium Models](https://papers.nips.cc/paper/8358-deep-equilibrium-models)

---

## 8. Theory of neural networks
### Lottery tickets
* [Lottery ticket hypothesis](http://news.mit.edu/2019/smarter-training-neural-networks-0506)
* [Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask](https://arxiv.org/abs/1905.01067)
* [Rigging the Lottery: Making All Tickets Winners](https://arxiv.org/abs/1911.11134)

### Others
* [What's Hidden in a Randomly Weighted Neural Network?](https://arxiv.org/abs/1911.13299)
* [Topological properties of the set of functions generated by neural networks of fixed size](https://arxiv.org/abs/1806.08459)
* [YOUR  CLASSIFIER  IS  SECRETLY  AN  ENERGY  BASED MODEL AND YOU  SHOULD TREAT IT LIKE ONE](https://arxiv.org/abs/1912.03263)
* [Neural Persistence: A Complexity Measure for Deep Neural Networks Using Algebraic Topology](https://openreview.net/pdf?id=ByxkijC5FQ)

---

## 9. Advanced Variational Inference
* [Amortized Population Gibbs Samplers with Neural Sufficient Statistics](https://arxiv.org/abs/1911.01382)
* [Evaluating Combinatorial Generalization in Variational Autoencoders](https://arxiv.org/abs/1911.04594)

---

## 10. Causal Inference
* [Elements of Causal Inference, pdf](https://www.dropbox.com/s/gkmsow492w3oolt/11283.pdf)
* [Causal Inference: What If, pdf](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1268/2019/10/ci_hernanrobins_1oct19.pdf)
* [Theoretical Impediments to Machine Learning With Seven Sparks from the Causal Revolution](https://arxiv.org/abs/1801.04016)
