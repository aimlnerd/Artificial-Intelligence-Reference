# Machine Learning & Deep Learning Tutorials [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- This repository contains a topic-wise curated list of Machine Learning and Deep Learning tutorials, articles and other resources. Other awesome lists can be found in this [list](https://github.com/sindresorhus/awesome).

- If you want to contribute to this list, please read [Contributing Guidelines](https://github.com/deepakiim/Artificial-Intelligence-Tutorials/blob/master/contributing.md).


## Contents
- [General](#general)
- [Text Classifcation](#textclassification)  
- [CNN](#cnn)
- [RNN](#rnn)
- [SVM](#svm)
- [Chatbot](#chatbot)
- [Interview Resources](#interview)
<a name="general" />

## General

- [Tom Mitchell's Machine Learning Class recording](https://www.cs.cmu.edu/~ninamf/courses/601sp15/lectures.shtml)
- [Machine Learning Course by Andrew Ng (Stanford University)](https://www.coursera.org/learn/machine-learning)
- [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)


<a name="textclassification" />

## Text Classifcation
- [Microsoft Text Analytics Guide](https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/text-analytics)
- [Microsoft Text Classification Guide](https://gallery.azure.ai/Experiment/f43e79f47d8a4219bf8613d271ea2c45)
- [Google Text Classification Guide](https://developers.google.com/machine-learning/guides/text-classification/)


<a name="cnn" />

## CNN
- [Convolutional Neural Networks cheatsheet - Stanford](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks)

<a name="rnn" />

## RNN
- [Recurrent Neural Networks cheatsheet - Stanford](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)


<a name="SVM" />

## SVM
### RBF kernel parameter
Kernel gives simillarity between any two points(i.e. rows) in the data

![RBF Kernel](https://www.mathworks.com/responsive_image/150/0/0/0/0/cache/matlabcentral/mlc-downloads/downloads/submissions/67021/versions/2/screenshot.jpg)
~~~
Technically, the gamma parameter is the inverse of the standard deviation of the RBF kernel (Gaussian function), which is used as similarity measure between two points.  
            γ=1/(2σ^2) 
Intuitively, a small gamma value define a Gaussian function with a large variance. 
In this case, two points can be considered similar even if are far from each other. 

In the other hand, a large gamma value means define a Gaussian function with a small variance. 
In this case, two points are considered similar just if they are close to each other.
~~~
#### Influence of Gamma on decision boundary
~~~
High gamma --> low variance --> Points closer will have very high simillarity score.
So points closer to decision boundary will have very high influence on decision boundary compared to far away training points.
So the points closer will pull the decision boundary towards itself leading to wiggly decision boundary.

Low gamma --> high variance --> Points far away will have also have sufficient simillarity score. 
So points far away from decision boundary will have sufficient influence on decision boundary.
So the points closer will not pull the decision boundary towards itself unlike the other case. So this leads to more linear decision boundary.
~~~
* [SVM Gamma Parameter - Udacity](https://www.youtube.com/watch?v=m2a2K4lprQw)
* [SVM Parameters When Using RBF Kernel](https://chrisalbon.com/machine_learning/support_vector_machines/svc_parameters_using_rbf_kernel/)

<a name="chatbot" />

## Chatbot

- [Building ML models is hard. Deploying them in real business environments is harder.](http://ocadotechnology.com/blog/building-ml-models-is-hard-deploying-them-in-real-business-environments-is-harder/)
- [How Ocado uses machine learning to improve customer service](http://ocadotechnology.com/blog/how-ocado-uses-machine-learning-to-improve-customer-service/index.html)
- [Understanding Architecture Models of Chatbot and Response Generation Mechanisms](https://dzone.com/articles/understanding-architecture-models-of-chatbot-and-r)
- [Chatbots with Machine Learning: Building Neural Conversational Agents](https://blog.statsbot.co/chatbots-machine-learning-e83698b1a91e)
- [Building a FAQ Chatbot in Python using RASA NLU](https://www.analyticsvidhya.com/blog/2018/01/faq-chatbots-the-future-of-information-searching/?utm_source=linkedin.com&utm_medium=social)

### Evaluating Chatbot
- [Should I make decisions based on micro-averaged or macro-averaged evaluation measures?](https://stats.stackexchange.com/questions/156923/should-i-make-decisions-based-on-micro-averaged-or-macro-averaged-evaluation-mea)


<a name="interview" />

## Interview Resources

- [41 Essential Machine Learning Interview Questions (with answers)](https://www.springboard.com/blog/machine-learning-interview-questions/)
- [How can a computer science graduate student prepare himself for data scientist interviews?](https://www.quora.com/How-can-a-computer-science-graduate-student-prepare-himself-for-data-scientist-machine-learning-intern-interviews)
- [How do I learn Machine Learning?](https://www.quora.com/How-do-I-learn-machine-learning-1)
- [FAQs about Data Science Interviews](https://www.quora.com/topic/Data-Science-Interviews/faq)
- [What are the key skills of a data scientist?](https://www.quora.com/What-are-the-key-skills-of-a-data-scientist)
- [The Big List of DS/ML Interview Resources](https://towardsdatascience.com/the-big-list-of-ds-ml-interview-resources-2db4f651bd63)
