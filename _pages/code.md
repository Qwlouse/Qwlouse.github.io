---
permalink: /code/
layout:    single
title:     "Code"
author_profile: false
---

{% include base_path %}

## [Sacred](https://github.com/IDSIA/sacred)
Sacred is a python infrastructure tool, to help with running machine-learning experiments.
It helps to configure, organize, log and reproduce experiments. 

## [Brainstorm](https://github.com/IDSIA/brainstorm)
Brainstorm is a deep-learning framework with a focus on modularity and support for Recurrent Neural Networks.

## Other

### [LSTM](https://gist.github.com/Qwlouse/45d5bdc2047ee5a23e27) implementation in numpy
A Jupyter notebook with a reference implementation of a Long Short-Term Memory 
recurrent neural network in numpy alongside all the formulas. 
It is meant for educational purposes and not optimized for speed or efficiency. 

### [TIMIT preprocessing](https://gist.github.com/Qwlouse/3d33c8529f446b9fc5c0)
A Jupyter notebook that reads and preprocesses the TIMIT corpus. 
It can extract MFCCs or raw signals and supports the most common train/test splits.
This is the preprocessing used for the 
[LSTM: A Search Space Odyssey](http://arxiv.org/abs/1503.04069) paper
and it closely mimics the preprocessing used by many others.  

### [Binding](https://github.com/Qwlouse/Binding)
The code accompanying the paper [Binding via Reconstruction Clustering](http://arxiv.org/abs/1511.06418).

### [PyLSTM](https://github.com/Qwlouse/pylstm)
The now discontinued predecessor of brainstorm. 
A deep learning framework that we used for the 
[A Clockwork RNN](http://arxiv.org/abs/1402.3511) and 
[LSTM: A Search Space Odyssey](http://arxiv.org/abs/1503.04069) papers.

### [Prophet](https://github.com/Qwlouse/prophet)
A very early prototype of a browser-based interface for querying sacred
experiments stored in a MongoDB.

### [Hyperimp](https://github.com/Qwlouse/hyperimp)
A pure-python reimplementation of the [FANOVA framework](https://github.com/automl/fanova) 
for assesing hyperparameter importance (see [this paper](http://jmlr.org/proceedings/papers/v32/hutter14.html)). 
At this point it is largely undocumented. 
