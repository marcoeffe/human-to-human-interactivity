# Human to human interactivity
A curated list of papers and resources about mutual human behavior and human to human interactivity, inspired by [awesome-action-recognition](https://github.com/jinwchoi/awesome-action-recognition).

## Contents
 - [Datasets](#datasets)
 - [Action Recognition](#action-recognition)
 - [Action Detection](#action-detection)
 - [Action Prediction](#action-prediction)
 - [Action Progress](#action-progress)
 - [Handcrafted methods - State of the art](#handcrafted-methods)
 - [Miscellaneus](#miscellaneus)
 
## Datasets
* [UT-Interaction dataset](http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html#Data) - The UT-Interaction dataset contains videos of continuous executions of 6 classes of human-human interactions: shake-hands, point, hug, push, kick and punch. Ground truth labels for these interactions are provided, including time intervals and bounding boxes.

* [BIT-Interaction dataset](https://sites.google.com/site/alexkongy/software) - Consists of 8 classes of human
interactions (bow, boxing, handshake, high-five, hug, kick, pat,and push), with 50 videos per class.

* [TV-Interaction dataset](http://www.robots.ox.ac.uk/~alonso/tv_human_interactions.html) - Contains 300 videos clips with
human interactions. These videos are categorized into 4 interaction categories: handshake, high five, hug, and kiss, and annotated with the upper body of people, discrete head orientation and interaction.

## Action Recognition

* [Deep Learning for Videos: A 2018 Guide to Action Recognition](http://blog.qure.ai/notes/deep-learning-for-videos-action-recognition-review) - Summary of major landmark action recognition research papers till 2018

* [Human Action Recognition and Prediction: A Survey](https://arxiv.org/pdf/1806.11230.pdf)

## Action Detection

* [Deep Learning for Detecting Multiple Space-Time Action Tubes in Videos](https://arxiv.org/abs/1608.01529) - It proposes an approach to the spatiotemporal localisation (detection) and classification of multiple concurrent human actions within temporally untrimmed videos.

## Action Prediction

* [A Comprehensive Survey on Human Activity Prediction](https://www.researchgate.net/publication/318229650_A_Comprehensive_Survey_on_Human_Activity_Prediction) -  In this survey, we give a systematic review of current methods for activity prediction and how they overcome the above challenge. Moreover, this paper also compares performances of various techniques on the common dataset to show the current state of research.

* [Human Interaction Prediction Using Deep Temporal Features](https://www.researchgate.net/publication/309640804_Human_Interaction_Prediction_Using_Deep_Temporal_Features) - Introduces a new method to capture deep temporal information in videos for human interaction prediction. Proposes to use flow coding images to represent the low-level motion information in videos and extract deep temporal features using a deep convolutional neural network architecture. 

## Action Progress

* [Am I Done? Predicting Action Progress in Videos](https://arxiv.org/abs/1705.01781) - We introduce the problem of predicting human action progress in videos.

* [Learning Activity Progression in LSTMs for Activity Detection and Early Detection](http://openaccess.thecvf.com/content_cvpr_2016/papers/Ma_Learning_Activity_Progression_CVPR_2016_paper.pdf) - In this work we improve training of temporal deep models to better learn activity progression for activity detection and early detection tasks.

* [Human Action Forecasting by Learning Task Grammars](https://arxiv.org/abs/1709.06391) -  It proposes a novel deep recurrent architecture that takes as input features from a two-stream Residual action recognition framework, and learns to estimate the progress of human activities from video sequences.

## Handcrafted methods

* [Human Activity Prediction: Early Recognition of Ongoing Activities from Streaming Videos](http://michaelryoo.com/papers/iccv11_prediction_ryoo.pdf) - We represent an activity as an integral histogram of spatio-temporal features, efficiently modeling how feature distributions change over time. (dynamic bag-of-words)

* [A Hierarchical Representation for Future Action Prediction](http://cvgl.stanford.edu/papers/lan_eccv14.pdf) - Proposes hierarchical movemes - a new representation to describe human movements at multiple levels of granularities, ranging from atomic movements (e.g. an open arm) to coarser movements that cover a larger temporal extent.

## Miscellaneus

* [Deep SORT](https://github.com/nwojke/deep_sort) - This repository contains code for Simple Online and Realtime Tracking with a Deep Association Metric (Deep SORT). We extend the original SORT algorithm to integrate appearance information based on a deep appearance descriptor.
