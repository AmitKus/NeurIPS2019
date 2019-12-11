# Dec 10, Tuesday 


## [Orals](https://nips.cc/Conferences/2019/ScheduleMultitrack?text=&session=&event_type=&day=2019-12-10)

10:05 am : West Ballroom C\
[Updates of Equilibrium Prop Match Gradients of Backprop Through Time in an RNN with Static Input](https://nips.cc/Conferences/2019/ScheduleMultitrack?event=15732)\
[3 min video](https://www.youtube.com/watch?v=Xb5sM0NRy_0&feature=youtu.be)\
Maxence Ernoult (Université Paris Sud)\
Benjamin Scellier (Mila, University of Montreal)\
**Yoshua Bengio (Mila)**

Notes:

Backpropagation:

    * Method of choices
    * Non local learning rules
  
Contrastive Hebbing Learning:

    * Used to train Boltzmann Machine

What is equilibrium propagation?

Work: discrete-time version of EqProp

    * Equivalent to BPTT on RNNs
    * Gradients of BPTT = Temporal updates of EP

Summary:

    * EqProp can train a CNN and FC prototypical model
    * EP performs as well as BPTT.
    * Scaling EqProp to Deeper Architectures: The deeper the network, the less the GDU holds.
    * EqProp is difficult to scale

## [Spotlights](https://nips.cc/Conferences/2019/ScheduleMultitrack?text=&session=&event_type=&day=2019-12-10)

West Ballroom C\
[Legendre Memory Units: Continuous-Time Representation in Recurrent Neural Networks](https://nips.cc/Conferences/2019/ScheduleMultitrack?event=15733)\
[3 min video](https://www.youtube.com/watch?v=yr8LZZD1I4o)\
[slides](https://drive.google.com/file/d/18zMik5Ku45QMgczoItZv1GRTv3GSmctM/view)\
Aaron Voelker\
Ivana Kajić\
Chris Eliasmith

### Notes
LSTMs: Multiple application. Difficult to scale for long windows of time.

LMUs: Scalable in time.
Performs better on chaotic time series benchmark compared to LSTMs.
Input is transformed over Legendre Polynomial Basis functions.
Discretized differential equations is used.



[Point-Voxel CNN for Efficient 3D Deep Learning](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15734)\
[3 min video](https://pvcnn.mit.edu/)\
Zhijian Liu (MIT)\
Haotian Tang (Shanghai Jiao Tong University)\
Yujun Lin (MIT)\
Song Han (MIT)

Power requirement and latency main issues for 3D models.

Voxel based methods: Cubically groqing memory.

Point-based models: Sparsity overheads

3D part segmentation (ShapeNet)

3D semantic segmentation (S3DIS)

3D object detection (KITTI)

Point-voxel CNN for efficient 3D deep learning



[Neural Networks with Cheap Differential Operators](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15735)\
[Poster](http://www.cs.toronto.edu/~rtqichen/posters/diffopnet_poster.pdf)\
Ricky Tian Qi Chen (U of Toronto)\
**David Duvenaud (University of Toronto)**

Differential operators: Multiple 

Automatic Differentiation:

HollowNets

detach functionalty in PyTorch.

Application 1: Finding Fixed Points.

Application 1: Continuously Normalizing Flow.


[Sequential Neural Processes
](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15736)\
[Slides](https://drive.google.com/open?id=1wAZD4l7hj_haCKWBbvKtPFOWtQxwhGwN)\
Jaesik Yoon (SAP)\
Youngsung Son (Electronics and Telecommunications Research Institute)\
Sungjin Ahn (Rutgers University)

### Notes:

What if the stochastic process also had some underlying temporal process?



[Deep Equilibrium Models](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15737)\
[Poster](https://github.com/locuslab/deq/blob/master/presentations/DEQ_poster.pdf)\
[Slides](https://github.com/locuslab/deq/blob/master/presentations/DEQ_slides.pdf)
Shaojie Bai (Carnegie Mellon University)\
J. Zico Kolter (Carnegie Mellon University / Bosch Center for AI)\
Vladlen Koltun (Intel Labs)

We can replace many classses of deep models with a single layer, keep the number of parameters same.

Deep Equilibrium Model: Formulate the problem as root-finding problem.

Concept: Weight-tying

How should we understand depth in deep networks?





## [Orals](https://nips.cc/Conferences/2019/ScheduleMultitrack?text=&session=&event_type=&day=2019-12-10)

04:10 am :  West Exhibition Hall C + B3\

Representations of Probability Distribution:

    *Bayesian Networks
    *MRF
    *Autoregressive 

From scores to samples: Langevin Dynamics

Score-Based Generative Modeling

    * No need to be normalized
    * No minmax Optimization

Adding noise and annealing noise levels are critical

Better or comaprable sample quality to GANs

## Spotlight 1: Learning hierarchical priors in VAEs
CMU human motion data

## SPotlight 2: Energy base models to generated high res images
Energy based models: Hard to train

Why EBM?
   1. Implicit generation 
   2. Intriguing properties

EBMs pros:
1. Robust
2. Continual Learning
3. Compositionality
4. Trajectory mapping
   
## SPotlight 3: Invertible convolutional flow


## Spotlight 4: Residual flows

$$y = f(x) = x + g(x)$$

What is Flow based models?


## [Orals](https://nips.cc/Conferences/2019/ScheduleMultitrack?text=&session=&event_type=&day=2019-12-10)

4:50 pm : West Exhibition Hall C + B3\
[HYPE: A Benchmark for Human eYe Perceptual Evaluation of Generative Models](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15857)\
[Slides](https://drive.google.com/file/d/1_Rz1oLBd49woRwwX-v3LHgxn9XteEPkP/view?usp=sharing)\
Sharon Zhou (Stanford University)\
Mitchell Gordon (Stanford University)\
Ranjay Krishna (Stanford University)\
Austin Narcomey (Stanford University)\
**Li Fei-Fei (Stanford University)**\
Michael Bernstein (Stanford University)

### Notes

Evaluation is critcal to measuring progress.

HYPE measures this progress using human evaluation that is consistent.

Why not use automated metrics?
Density estimation has evn been shwon to be misleading.

Why not use human evaluation?

    *Ad-hoc
    *High variance estimation
    *Lack clear separability
    *Expensive and time consuming

Databases: CelebA, FFHQ

hype.stanford.edu


## [Spotlights](https://nips.cc/Conferences/2019/ScheduleMultitrack?text=&session=&event_type=&day=2019-12-10)

West Exhibition Hall C + B3

[Adaptive Density Estimation for Generative Models](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15858)\
[Poster](https://thoth.inrialpes.fr/people/tlucas/poster.pdf)\
Thomas Lucas (Inria)\
Konstantin Shmelkov (Huawei)\
Karteek Alahari (Inria)\
Cordelia Schmid (Inria / Google)\
Jakob Verbeek (INRIA)

Look at slides.

1. MLE
2. Adversarial training




[Twin Auxilary Classifiers GAN](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15859)\
[Slides](https://github.com/batmanlab/twin_ac/blob/master/TAC-GAN.pdf)\
Mingming Gong (University of Melbourne)\
Yanwu Xu (University of Pittsburgh)\
Chunyuan Li (Microsoft Research)\
Kun Zhang (CMU)\
Kayhan Batmanghelich (University of Pittsburgh)

Notes:
Issues with AC-GAN: Low diversity, tends towards mode collapse


[Adversarial Fisher Vectors for Unsupervised Representation Learning](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15860)\
[Poster](https://github.com/apple/ml-afv/blob/master/poster.pdf)\
Joshua Susskind (Apple Inc.)\
Shuangfei Zhai (Apple)\
Walter Talbott (Apple)\
Carlos Guestrin (Apple & University of Washington)

Is the discriminator useful at test time?

Do GANs learn representations of data?

Do you nedd to train an additional encoder?

Energy based model interpretation of GANs

Fisher vectors: Has been successful in computer vision.



[Emergence of Object Segmentation in Perturbed Generative Models](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15861)\
[Poster](http://www.cvg.unibe.ch/media/publications/pdf/neurips19_perturbedseg_poster.pdf)\
Adam Bielski (University of Bern)\
Paolo Favaro (Bern University, Switzerland)

Learning to generate layered scenes with GAN

Random shifts

Learning with perturbations


[Compression with Flows via Local Bits-Back Coding](https://neurips.cc/Conferences/2019/ScheduleMultitrack?event=15862)\
[Slides](https://drive.google.com/open?id=1A6t2F88GJBkhSZgyn26ImjzNi3O1A-FT)\
Jonathan Ho (UC Berkeley)\
Evan Lohn (University of California, Berkeley)\
**Pieter Abbeel (UC Berkeley & covariant.ai)**

Flow modesls: smooth invertible maps between noise and data.

Local bits-back coding: compression with flow models.





# Demonstrations

5:30 pm -- 10:30 PM @ East Exhibition Hall B + C\

802: Streamlit, a new app framework for machine learning tools\
Adrien Treuille · Amanda Kelly

803: Discovering Neural Wirings Neural Network Visualizer\
Alvaro Herrasti · Mitchell Wortsman

813: Realtime Modeling and Anomaly Detection in Multivariate Data Streams\
Christopher Hannon · Andrey Lokhov · Deep Deka


# Socials

Inverse Problems Social\
Tue Dec 10th 07:00 -- 10:00 PM @ West 223 + 224







