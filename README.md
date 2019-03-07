# Human to human interactivity
A curated list of papers and resources about mutual human behavior and human to human interactivity, inspired by [awesome-action-recognition](https://github.com/jinwchoi/awesome-action-recognition).

## Contents
 - [Datasets](#datasets)
 - [Action Recognition](#action-recognition)
 - [Spatio-Temporal Action Localization](#spatio-temporal-action-localization)
 - [Action Prediction](#action-prediction)
 - [Action Progress](#action-progress)
 - [Handcrafted methods - State of the art](#handcrafted-methods)
 - [Detector](#detector)
 
## Datasets
* [UT-Interaction dataset](http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html#Data) - The UT-Interaction dataset contains videos of continuous executions of 6 classes of human-human interactions: shake-hands, point, hug, push, kick and punch. Ground truth labels for these interactions are provided, including time intervals and bounding boxes.

* [BIT-Interaction dataset](https://sites.google.com/site/alexkongy/software) - Consists of 8 classes of human
interactions (bow, boxing, handshake, high-five, hug, kick, pat,and push), with 50 videos per class. DOWNLOAD IS NOT MORE AVAILABLE.

* [TV-Interaction dataset](http://www.robots.ox.ac.uk/~alonso/tv_human_interactions.html) - Contains 300 videos clips with
human interactions. These videos are categorized into 4 interaction categories: handshake, high five, hug, and kiss, and annotated with the upper body of people, discrete head orientation and interaction.

* [The Kinetics Human Action Video Dataset](https://deepmind.com/research/open-source/open-source-datasets/kinetics/) -  The dataset contains 400 human action classes, with at least 400 video clips for each action. Each clip lasts around 10s and is taken from a different YouTube video. For this task we take in consideration a small subset (touching person).

* [Volleyball group activity dataset](https://github.com/mostafa-saad/deep-activity-rec) - A new dataset using publicly available YouTube volleyball videos. We annotated 4830 frames that were handpicked from 55 videos with 9 player action labels and 8 team activity labels.

## Action Recognition

* [Human Action Recognition and Prediction: A Survey](https://arxiv.org/pdf/1806.11230.pdf)

* [Deep Learning for Videos: A 2018 Guide to Action Recognition](http://blog.qure.ai/notes/deep-learning-for-videos-action-recognition-review) - Summary of major landmark action recognition research papers till 2018

* [Hierarchical Deep Temporal Models for Group Activity Recognition](https://arxiv.org/pdf/1607.02643.pdf) - This paper presents an approach for classifying the activity performed by a group of people in a video sequence. This problem of group activity recognition can be addressed by examining individual person actions and their relations.

## Spatio-Temporal Action Localization

* [Online Real-time Multiple Spatiotemporal Action Localisation and Prediction](https://github.com/gurkirt/realtime-action-detection) - It proposes a deep-learning framework for real-time multiple spatio-temporal (S/T) action localisation and classification.

* [Action Tubelet Detector for Spatio-Temporal Action Localization](https://arxiv.org/pdf/1705.01861.pdf) - We propose the ACtion Tubelet detector (ACT-detector) that takes as input a sequence of frames and outputs tubelets, i.e., sequences of bounding boxes with associated scores. We build upon the SSD framework. 

## Action Prediction

* [A Comprehensive Survey on Human Activity Prediction](https://www.researchgate.net/publication/318229650_A_Comprehensive_Survey_on_Human_Activity_Prediction) -  In this survey, we give a systematic review of current methods for activity prediction and how they overcome the above challenge. Moreover, this paper also compares performances of various techniques on the common dataset to show the current state of research.

* [Predicting Human Interaction via Relative Attention Model](https://arxiv.org/pdf/1705.09467.pdf) - Built on a tricoupled deep recurrent structure representing both interacting subjects and global interaction status, the proposed network collects spatio-temporal information from each subject, rectified with global interaction information, yielding effective interaction representation.

* [Human Interaction Prediction Using Deep Temporal Features](https://www.researchgate.net/publication/309640804_Human_Interaction_Prediction_Using_Deep_Temporal_Features) - Introduces a new method to capture deep temporal information in videos for human interaction prediction. Proposes to use flow coding images to represent the low-level motion information in videos and extract deep temporal features using a deep convolutional neural network architecture. 

## Action Progress

* [Am I Done? Predicting Action Progress in Videos](https://arxiv.org/abs/1705.01781) - We introduce the problem of predicting human action progress in videos.

* [Learning Activity Progression in LSTMs for Activity Detection and Early Detection](http://openaccess.thecvf.com/content_cvpr_2016/papers/Ma_Learning_Activity_Progression_CVPR_2016_paper.pdf) - In this work we improve training of temporal deep models to better learn activity progression for activity detection and early detection tasks.

* [Human Action Forecasting by Learning Task Grammars](https://arxiv.org/abs/1709.06391) -  It proposes a novel deep recurrent architecture that takes as input features from a two-stream Residual action recognition framework, and learns to estimate the progress of human activities from video sequences.

## Handcrafted methods

* [Human Activity Prediction: Early Recognition of Ongoing Activities from Streaming Videos](http://michaelryoo.com/papers/iccv11_prediction_ryoo.pdf) - We represent an activity as an integral histogram of spatio-temporal features, efficiently modeling how feature distributions change over time. (dynamic bag-of-words)

* [A Hierarchical Representation for Future Action Prediction](http://cvgl.stanford.edu/papers/lan_eccv14.pdf) - Proposes hierarchical movemes - a new representation to describe human movements at multiple levels of granularities, ranging from atomic movements (e.g. an open arm) to coarser movements that cover a larger temporal extent.

## Detector

* [SSD: Single Shot MultiBox Detector](https://arxiv.org/pdf/1512.02325.pdf) - Presents a method for detecting objects in images using a single deep neural network. This approach, named SSD, discretizes the output space of bounding boxes into a set of default boxes over different aspect ratios and scales per feature map location.

* [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/pdf/1506.01497.pdf) -  This work introduces a Region Proposal Network (RPN) that shares full-image convolutional features with the detection network, thus enabling nearly cost-free region proposals.
