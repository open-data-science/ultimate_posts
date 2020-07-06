# ODS #wheretostart recommendations

This article collects public knowledge on how to start learning field commonly addressed as Data Science. We are adressing what is called DS, what spheres and disciplined are covered by it and suggest recipes for stepping on path of getting familiar with this field.

Data Science is a term describing everything related to processing, storing and mining any information. This includes different disciplines, cources and spheres of our life. General undestanding (helicopter overview) can be derived from reading Google's brilliant [web comic](https://cloud.google.com/products/ai/ml-comic-1/) (~5 min) and reading great Vas3k's post [Machine Learning for Everyone](https://vas3k.com/blog/machine_learning/) (~15 min).


There is now way to be taught to be data scientist, but you can learn how to become one yourself. There is no right way, but there is a way, which was adopted by a number of data scientists and it lies with online courses (MOOC). With this article we aim at anwering those common questions:

1. Where to start with data science?
2. How to become a data scientist?

We are looking up at the awesome resource [Teach Yourself CS](https://teachyourselfcs.com) and aim at providing useful and actionable insights on how to learn skills and get knowledge to get onto data-driven way. However if you don't like our guide there are some alternatives included into the appendix.

### Buzzwords disclaimer

We want to provide most inclusive and open information, therefore we do not explicitly distinquish skills between what one would name different job specialisations: ML engineers, Data engineers, Deep Learning specialists, Data Analytics etc.

## TL;DR:

We assume that you have at least some background with programming, if not, you can address the aforementioned [Teach Yourself CS](https://teachyourselfcs.com) to learn basics of [programming](https://teachyourselfcs.com/#programming) and [algorithms](https://teachyourselfcs.com/#algorithms).

Then you can get at least an overview of these topics, ideally studying suggested courses and/or watching videos.



#### General Math for Data Science

Why matters: you need to know basic stuff to understand what's happening on the low level

Book: [Introduction to Applied Linear Algebra – Vectors, Matrices, and Least Squares](https://web.stanford.edu/~boyd/vmls/)

Web page: [The Matrix Calculus You Need For Deep Learning](https://explained.ai/matrix-calculus/index.html)

#### Statistics

Why matters: research can go wrong if you don't check for fundamental flaws.

Courses:

#### General Machine Learning. 

Why matters: general concepts of how computers can generalize. 

Courses: [Andrew Ng’s Machine Learning](https://www.coursera.org/learn/machine-learning), [CS229 @ Stanford](http://cs229.stanford.edu/index.html), [COMS W4995 Applied Machine Learning](https://www.cs.columbia.edu/~amueller/comsw4995s19/schedule/), [Google's crash-course on ML](https://developers.google.com/machine-learning/crash-course/)

#### Data Engeneering.

Why matters: You need to know how industry leaders are processing Terabytes of data, collect and store them.

Courses: 

#### General Neural Networks

Why matters: neural networks tend to be unreasonably effective sometimes.

Courses: [Neural Networks for Machine Learning](https://www.coursera.org/learn/neural-networks)

#### Natural Language Processing.

Why matters: NLP allows to percieve sentiment, extract knowledge, perform search and machine translation.

Course: [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/syllabus.html) from Stanford

#### Computer Vision.

Why matters: CV allows to classify images, segment them, identify objects and process visual information. 

Course: [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/syllabus.html) from Stanford

#### Reinforcement learning.

Why matters: Reinforcement Learning or RL covers self-driving / autonomous vehicles as well as any other acting agents in any environment.

Courses: [UCL Course on RL](https://www.davidsilver.uk/teaching/), [Udacity's course Repo](https://github.com/udacity/deep-reinforcement-learning) & [nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)

#### Graph Learning

Why matters: different proceses can be described with graphs: from social connections to food analysis.

Courses: [CS224 Stanford's course](http://cs224w.stanford.edu)




## Some common questions answered

There are some common pitfals and 'hacks' which any data scientist will encounter. Below is a cherry-picked collection of great articles on the matters:


### ​​Bayesian Statistics explained to Beginners in Simple English

Now some #entrylevel material, which still might be useful to review, because repetitio est mater studiorum.

Link: https://www.analyticsvidhya.com/blog/2016/06/bayesian-statistics-beginners-simple-english/


### P-value, explained, one more time with demos

Article includes not only great explanation of what is #pvalue, but how it works and how it can be used to make a correct conclusions.

Link: https://www.freecodecamp.org/news/what-is-statistical-significance-p-value-defined-and-how-to-calculate-it/

### ​​🥇Parameter optimization in neural networks. 

Play with three interactive visualizations and develop your intuition for optimizing model parameters.

Link: https://www.deeplearning.ai/ai-notes/optimization/


### Probabilistic foundations of econometrica: part 1

Great intro into #statistics basics.

Link: https://freakonometrics.hypotheses.org/57649


### Implementing Transfer Learning in PyTorch

Fine-tuning and feature extraction with PyTorch

Link: https://medium.com/analytics-vidhya/transfer-learning-in-pytorch-f7736598b1ed



### Yet another good intro into difference between artificial neural network and biological one.

If you're getting started in Data Science, you need to start with the basic building building block of Neural Networks - a Perceptron. To understand what it is, there's this good link to get started with.

Link: https://towardsdatascience.com/the-differences-between-artificial-and-biological-neural-networks-a8b46db828b7


### Time series basics

Time series — data, with points having timestamps. Some might think that #timeseries are mostly used in algorithmic trading, but they often used in malware detection, network data analysis or any other field, dealing with some flow of time-labeled data. These two resources provide deep and easy #introduction into #TS analysis.

Github: https://github.com/akshaykapoor347/Time-series-modeling-basics

Data Camp presentation: https://s3.amazonaws.com/assets.datacamp.com/production/course_5702/slides/chapter3.pdf


### Hitchhiker’s guide to Exploratory Data Analysis

Exploratory Data Analysis — stage of finding out distribution of the data, volume, number  of missing values and all the other characteristics of the available dataset.

Part 1: https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-6e8d896d3f7e

Part 2: https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-part-2-36ab72201e1d


### Free online ODS.AI course on ML

Another great free course will start on February 11. Taught through #Kaggle notebooks and competitions.

Link: https://www.kaggle.com/general/77771


### Introduction for machine learning for coders

Fast.ai launching new course for coders, having at least 1 year of experience. This is a practical-oriented course covering wide range of areas: classical Machine Learning with Random Forest and Gradient Decent, Regularization, NLP, Embeddings,

Link: http://www.fast.ai/2018/09/26/ml-launch/

Course itself: http://course.fast.ai/ml



### ​​GANs from Scratch 1: A deep introduction. 

Great introduction and tutorial. With code in PyTorch and TensorFlow

Link: https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f



### Classification and Loss Evaluation - Softmax and Cross Entropy Loss

Nice notes on softmax cross entropy loss and how to implement it in numpy.

Link: https://deepnotes.io/softmax-crossentropy



### Simple comic on how #ML works from #Google

Make sure you save the link (or this message) to show it to people without great technical background for it is one of the best and clear explanations there is.

Link: https://cloud.google.com/products/ai/ml-comic-1/




### New free Deep Learning course from #FastAI

This course shows how to build a state of the art deep learning model from scratch. 
FastAI’s mission is to make neural nets uncool again by teaching as many people from as many backgrounds as possible. 

Link: https://www.fast.ai/2019/06/28/course-p2v3/



### 🔥🎓New FastAI's free online course on NLP

It is called «A Code-First Introduction to Natural Language Processing». All code & videos are available for free online, make sure you save this link into bookmarks and at least review the content, because it provides opportunity not only to learn new skills, but to actually understand how NLP works.

Link: https://www.fast.ai/2019/07/08/fastai-nlp/


### Python Data Science Handbook: Essential Tools for Working with Data by Jake VanderPlas

This book provides basic knowledge about using NumPy, Pandas, Matplotlib and Scikit-Learn with Jupyter Notebook for beginners from scratch. The link below leads to a repository containing the entire book and training materials.

Link: https://github.com/jakevdp/PythonDataScienceHandbook




## Alternative guides


1. [A long-term Data Science roadmap which WON’T help you become an expert in only several months](https://towardsdatascience.com/a-long-term-data-science-roadmap-which-wont-help-you-become-an-expert-in-only-several-months-4436733e63ff). By Andrew Lukyanenko.
2. [LEARNING DEEP LEARNING - MY TOP-FIVE LIST](http://thegrandjanitor.com/2016/08/15/learning-deep-learning-my-top-five-resource/).
3. [A survivor’s guide to Artificial Intelligence courses at Stanford](https://huyenchip.com/2018/03/30/guide-to-Artificial-Intelligence-Stanford.html).
4. [Resources collection](https://hackmd.io/@chanderA/aiguide)
