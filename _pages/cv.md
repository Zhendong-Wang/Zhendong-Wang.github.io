---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Details is in [CV](../files/cv.pdf).  

## Education

* PhD in Statistics & Data Science, The University of Texas, Austin, 2020
* M.S. in Data Science, Columbia University, 2019
* Exchange Student, University of California, Berkeley, 2018
* B.S. in Civil Engineering, Tongji University, 2014

## Pulications

* Zhendong Wang and Mingyuan Zhou. 
Thompson Sampling via Local Uncertainty. 
In International Conference on Machine Learning, 2020. 
* Xinjie Fan, Yizhe Zhang, Zhendong Wang and Mingyuan Zhou. 
Adaptive Correlated Monte Carlo for Contextual Categorical Sequence Generation. 
In International Conference on Learning Representations, 2020.
* Anonymous*, Zhendong Wang* and Anonymous.
Implicit Distributional Reinforcement Learning. 
In Neural Information Processing Systems, 2020 (Under Review).


## Research Experience

Summer 2019: Graduate Research Assistant  
*Department of Statistics & Data Science, University of Texas, Austin*  
* Topic 1: Correlated MC for Categorical Sequence Generation  
  * Engaged in the Augmented-Reinforce-Swap-Merge (ARSM) gradient approximator derivation for contextual categorical sequence generation.
  * Used ARSM approximator to implement adaptive correlated Monte Carlo based policy gradient for
sequence generation, in Pytorch. 
  * Evaluated our proposed correlated MC policy gradient method on image captioning and neural
program synthesis (NPS) tasks.
  * Compared our correlated MC based method with independent ones, and found that our model 
achieved greater variance reduction and could adaptively modify the number of MC samples 
according to the uncertainty on token generation. 

* Topic 2: Thompson Sampling with Local Uncertainty  
  * Developed a new probabilistic modeling framework for Thompson sampling with the power of 
local variable uncertainty.  
  * Merged semi-implicit variational inference structure into the framework to further improve the 
expressiveness of latent distribution.  
  * Evaluated our framework on classical sequence decision making problem, contextual bandits, with
comparison to current state-of-the-arts baselines, which leverages the global variable uncertainty. 
  * Found that local uncertainty based framework can capture the underlying uncertainty in data well, 
and achieved state-of-the-arts performance, while having low computational complexity.  

Fall 2019: Capstone Research Project	  
*Institute of Data Science, Columbia University*    
* Topic: Superresolution and Prediction of Ocean Sea-Surface Temperature  
  * Preprocessed ocean temperature image data into applicable deep learning format.  
  * Implemented the proposed Super Resolution Generative Adversarial Network (SRGAN).  
  * Evaluated the SRGAN model on the one channel ocean temperature data with 4x resolution upscaling. 
  * Designed regularization term in objective function to make the generated new ocean temperature data satisfying ocean physical constraints. 

## Skills

* Programming Languages: Python (Numpy, Scikit-Learn, Matplotlib), R, Java, SQL, C++, MATLAB  
* Deep Learning Packages: Tensorflow, Pytorch  
* Language: Chinese, English  
  
## Teaching

Fall 2019: Course Assistant, Personalization Theory and Application  
*Institute of Data Science, Columbia University*
* Hold office hour and Piazza question answering to help students accomplish homeworks and understand course materials better.
* Assisted instructor in grading course assignments and final project to monitor student learning. 

## Projects

Text generation with GAN, Natural Language Processing in CU	Spring 2019
* Implemented base GAN structure, generator and discriminator, for text generation in Tensorflow.
*	Employed transformer with attention involved as generator to improve performance. 
*	Applied Conditional GAN (CGAN) to text migration tasks. 

Visual Navigation by Deep Reinforcement Learning, Reinforcement Learning in CU	Fall 2018
*	Used AI2THOR simulator to establish reinforcement learning environments.
*	Implemented deep-siamese network by Tensorflow. 
*	Implemented A3C method with python and got excellent convergence with only image inputs.
*	Achieved scene and target generalization in indoor-navigation.

Bayesian Clustering, Bayesian Method Machine Learning in CU	Fall 2018
*	Used EM algorithm and Variational Inference algorithm to cluster data.
*	Implemented Bayesian nonparametric Gibbs sampler to cluster data.
*	Implemented simple version LDA model.

Columbia Data Science Hackathon 2018, CU	Fall 2018
*	Cleaned and explored Bitcoin related dataset (Reddit comment data and BTC transaction data).
*	Analyzed the polarity of Bitcoin comments by NLP tools.
*	Analyzed the relationship between comment polarity and tendency of Bitcoin price.

Humana Healthcare Analytics 2018 Case Competition, CU	Fall 2018
*	Cleaned and explored data related to patients’ history and AMI disease record.
*	Built machine learning models and implemented the models by Scikit-Learn tools.
*	Obtained business recommendation according to the result of machine learning prediction.

Weather Events Data Analysis, Data Visualization in CU	Fall 2018
*	Used R-Studio to clean the data and analyze the relationship between variables.
*	Visualized the result in R-Studio by ggplot, d3 and shiny app. 

Game Developments, Data Structures in UCB  	Fall 2017
*	Developed 2048 Game with Java.
*	Visualized the game process and analyzed the stability of the game with 1000 tests.
*	Designed simple AI by game tree theory and developed Qirkat chess game.
*	Compared the speed of AI by AI contests.

Database Management System Development, Data Structure in UCB  	Fall 2017
*	Described command syntax according to SQL syntax. 
*	Implemented commands including 'create', 'exit', 'insert', 'load', 'print', 'store', 'select' and 'quit'.

