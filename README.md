# thesis-uva
A curated list of papers and resources about self driving cars, inspired by [awesome-action-recognition](https://github.com/jinwchoi/awesome-action-recognition).

## Contents
 - [Datasets](#datasets)
 - [Action Recognition](#action-recognition)
 - [Action Detection](#action-detection)
 - [Action Progress](#action-progress)
 - [Miscellaneus](#miscellaneus)
 
## Datasets
* [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php) - We take advantage of our autonomous driving platform Annieway to develop novel challenging real-world computer vision benchmarks.

* [nuScenes](https://www.nuscenes.org/) - A public large-scale dataset for autonomous driving. It enables researchers to study challenging urban driving situations using the full sensor suite of a real self-driving car.

* [Oxford RobotCar Dataset](https://robotcar-dataset.robots.ox.ac.uk/) - The Oxford RobotCar Dataset contains over 100 repetitions of a consistent route through Oxford, UK, captured over a period of over a year. The dataset captures many different combinations of weather, traffic and pedestrians, along with longer term changes such as construction and roadworks. [Paper](https://robotcar-dataset.robots.ox.ac.uk/images/robotcar_ijrr.pdf)

* [Berkeley DeepDrive](https://bdd-data.berkeley.edu/) - 100,000 HD video sequences of over 1,100-hour driving experience across many different times in the day, weather conditions, and driving scenarios. Our video sequences also include GPS locations, IMU data, and timestamps.

* [ApolloScape](http://apolloscape.auto/) - This large-scale dataset contains a diverse set of stereo video sequences recorded in street scenes from different cities, with high quality annotations of 5000+ frames.

## Action Recognition

* [Deep Learning for Videos: A 2018 Guide to Action Recognition](http://blog.qure.ai/notes/deep-learning-for-videos-action-recognition-review) - Summary of major landmark action recognition research papers till 2018

## Action Detection

* [Deep Learning for Detecting Multiple Space-Time Action Tubes in Videos](https://arxiv.org/abs/1608.01529) - It proposes an approach to the spatiotemporal localisation (detection) and classification of multiple concurrent human actions within temporally untrimmed videos.

## Action Progress

* [Am I Done? Predicting Action Progress in Videos](https://arxiv.org/abs/1705.01781) - Wwe introduce the problem of predicting human action progress in videos.

* [Human Action Forecasting by Learning Task Grammars](https://arxiv.org/abs/1709.06391) -  It proposes a novel deep recurrent architecture that takes as input features from a two-stream Residual action recognition framework, and learns to estimate the progress of human activities from video sequences.

* [RSDNet: Learning to Predict Remaining Surgery Duration from Laparoscopic Videos Without Manual Annotations](https://arxiv.org/abs/1802.03243) - We propose a deep learning pipeline, referred to as RSDNet, which automatically estimates the remaining surgery duration (RSD) intraoperatively by using only visual information from laparoscopic videos.

## Miscellaneus

* [Deep SORT](https://github.com/nwojke/deep_sort) - This repository contains code for Simple Online and Realtime Tracking with a Deep Association Metric (Deep SORT). We extend the original SORT algorithm to integrate appearance information based on a deep appearance descriptor.

* [Modeling Trajectories with Recurrent Neural Networks](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4849&context=sis_research) -  We design two RNNbased models which can make full advantage of the
strength of RNN to capture variable length sequence and meanwhile to address the constraints of topological structure on trajectory modeling.

* [ORB-SLAM](http://webdiis.unizar.es/~raulmur/orbslam/) - Versatile and accurate SLAM solution for Monocular, Stereo and RGB-D cameras. It is able to compute in real-time the camera trajectory and a sparse 3D reconstruction of the scene in a wide variety of environments.
