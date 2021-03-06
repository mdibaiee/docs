---
layout: page
title: "Current Environment"
category: community
date: 2016-10-19 21:08:18
---

A list of data science and machine learning algorithms we would like to have,
along with existing implementations (if any).

Machine Learning
----------------

### Supervised Learning

#### Classification

- Neural Networks
  - Simple Neural Networks
    - sibe - [hackage](http://hackage.haskell.org/package/sibe), [github](https://github.com/mdibaiee/sibe)
    - neural - [hackage](http://hackage.haskell.org/package/neural), [github](https://github.com/brunjlar/neural)
  - Recurrent Neural Networks
  - Convolutional Neural Networks
  - Generating Neural Networks
  - Basically everything of: [NNL-Speak for Haskellers](https://colah.github.io/posts/2015-09-NN-Types-FP/)


- Nearest Neighbors
  - HLearn: [Blogpost](https://izbicki.me/blog/fast-nearest-neighbor-queries-in-haskell.html) (including github-links)

- Naive Bayes
  - Gaussian Naive Bayes
  - Multinomial Naive Bayes
       - sibe - [hackage](http://hackage.haskell.org/package/sibe), [github](https://github.com/mdibaiee/sibe)
  - Bernoulli Naive Bayes


- Support Vector Machines
  - with custom Kernel-Function (beside Gaussian, Chi², etc.)

- Core Vector Machines
  - including approximative Center-Constrained-Minimum-Enclosing-Ball via Core-Set
  - Classification & Regression
  - O(n), but with huge constants

- Ensemble methods
  - Decision Trees
      - Random Forests
  - AdaBoost    

#### Regression

- Linear Regression
  - statistics - [hackage](http://hackage.haskell.org/package/statistics), [github](https://github.com/bos/statistics)

### Reinforcement Learning
- Policy gradient
- Q-Learning
     - Neural Network Q-Learning

### Clustering
- K-Means
  - kmeans - [hackage](https://hackage.haskell.org/package/kmeans), [darcs](http://hub.darcs.net/gershomb/kmeans)
- Self-Organising Maps (SOM)
  - Hyperbolic-SOM
  - Hierarchical (H)SOMs
- Mean-shift
- Affinity propagation
- Spectral Clustering
- Ward hierarchical clustering
- Birch


### Dimensionality Reduction
- Principal Component Analysis (PCA)
  - sibe - [hackage](http://hackage.haskell.org/package/sibe), [github](https://github.com/mdibaiee/sibe)
  - Kernel PCA
  - Incremental PCA
  - Truncated SVD

- Independent Component Analysis (ICA)

- t-SNE (t-distributed stochastic neighbor embedding)

Contribute
====

If you know a library that has to do with Data Science, please consider [adding](https://github.com/DataHaskell/docs/edit/gh-pages/_posts/2016-10-19-wishlist.md) it, if the category it belongs to doesn't exist, suggest a category for it.

Add sections related to data science and not only Machine Learning such as Data Mining, Distributed Processing, etc
