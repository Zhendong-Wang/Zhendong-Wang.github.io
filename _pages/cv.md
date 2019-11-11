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

* B.S. in Civil Engineering, Tongji University, 2014
* Exchange Student, University of California, Berkeley, 2018
* M.S. in Data Science, Columbia University, 2019 (expected)

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

