> Masons, when they start upon a building, <br>
Are careful to test out the scaffolding; <br><br>
Make sure that planks won’t slip at busy points, <br>
Secure all ladders, tighten bolted joints. <br><br>
And yet all this comes down when the job’s done <br>
Showing off walls of sure and solid stone. <br><br>
So if, my dear, there sometimes seem to be <br>
Old bridges breaking between you and me <br><br>
Never fear. We may let the scaffolds fall <br>
Confident that we have built our wall. <br>
# Machine Learning
- A classifier is a system that inputs (typically) a vector of *discrete and/or continuous feature values* and outputs *a single discrete value, the class*.
- **Learning = Representation + Evaluation + Optimization**
  - Representation: A classifier must be represented in some formal language that the computer can handle = choosing a set of classifiers that it can possibly learn. This set is called the **hypothesis space**.
  - Evaluation (Objective Function): Distinguish good classifiers from bad ones.
  - Optimization: A method to search among the classifiers in the language for the highest-scoring one.

| Representation | Evaluation | Optimization |
| ---         |     ---     |          --- |
| Instances | Accuracy/Error Rate | Combinatorial Optimization
| K-nearest Neighbor   |   Precision & Recall   | Greedy Search   |
| Support Vector Machines    | Squared Error       | Beam Search     |
| Hyperplanes | Likelihood| Branch-and-bound
| Naive Bayes   |   Posterior Probability   | Continous Optimization   |
| Logistic Regression    | Information Gain       | Unconstrained     |
| Decision Trees    | K-L Divergence | Gradient Descent     |
| Sets of rules    | Cost/Utility | Conjugate gradient     |
| Propositional rules   | Margin | Quasi-Newton methods     |
| Logic programs    |  | Constrained     |
| Neural Networks    |  | Linear programming     |
| Graphical models    |  | Quadratic programming    |
| Bayesian networks    |  |      |
| Conditional random fields    |  |      |
   
## Linear Regression
- Univariate Linear Regression
- Multivariate Linear Regression
- Assumption for Linear Models

## Logistic Regression (Naive Bayes)
- Linear model for **binary classification**
- Maximum Likelihood Estimation
- Assumptions:

## Trees

## Neural Networks
- Feed-forward
- Backpropagation

## Papers
1. [A Few Useful Things to Know About Machine Learning](https://dl.acm.org/doi/10.1145/2347736.2347755)
2. [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
3. [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper_files/paper/2014/hash/a14ac55a4f27472c5d894ec1c3c743d2-Abstract.html)
4. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
5. [Generative Adversarial Nets](https://papers.nips.cc/paper_files/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)
6. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
7. [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
8. [Mastering the game of Go with deep neural networks and tree search](https://research.google/pubs/mastering-the-game-of-go-with-deep-neural-networks-and-tree-search/)
9. [A Survey on Deep Learning in Medical Image Analysis](https://arxiv.org/abs/1702.05747)
