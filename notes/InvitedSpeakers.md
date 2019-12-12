# Veridical Data Science by Bin Yu

Leo Papers:

    *Statistical Modeling: The Two Cultures
    *Random Forest

Talk points:

    *PCS framework for veridical data science
    *Iterative Random forest
    *PDR framekwork for interpretable machine learning

PCS Framework: Workflow incorporates P, C, S into each step of DSLC. 

Three principles of data science:

    *Predicability 
    *Computability
    *Stability

**Stability** tests DSLC by "shaking" every part.

## Data Perturbation

    *Data modality choices
    *Syntheic data
    *data under differenc environment
    *Differntial privacy
    *Adverserarial attacks to deep learning algorithms

**Data pre-processing (cleaning) matters: stability principle calls for replication**

## Model/algortihms perturbation

    *Robust statistics
    *Semi-parametric
    *Lasso and ridge regression
    *Modes of a non-convec empirical minimization
    *Researcher to researcher perturbation

PCS doc. bridges relaity and modeles on github

How to choose perturbations in PCS? It's $\infty$
 * One can never consider all possible perturbations
 * A pledge to the stability principle in PCS would lead to numm results if too many perturbationswere considered
 * PCS requires documentation on the appropriateness of the perturbations.
  
P-value statement by Yoav Benjamini

Inference beyond probabilstic models. (PDEs)

Proposed PCS inference (basic):

    * Problem formulation
    * Prediction screening for reality checking
    * Target value perturbation distribution
    * Perturbation interval

## Making Random Forest interpretable

Random Intersection Trees (Shah)

**Molnar (2019) book**

Model-based interpretability
 * Sparsity
 * Simulatability
 * Modularity
 * Domain driven
  
Murdoch et al (2019)

Cosmological example which is doing the inverse problem.


# Machine learning in single cell biology by Dana Pe'er

How do we develop from a single cell to ~40 trillion cells that form the human body?

Cells are like tiny computers: Profileration, differntiation, activation

One genome - Many cell types

NN-graphs have no dimension, but retain much of the high-dimensional information.

Wanderlust: FInd shortest path trajectory through graph.

Wishbone: Using graph to detect bifurcation in path

The human cell atlas: www.humancellatlas.org/joinhca

**Computational Biology:**
   * Our goal is not to predict, but rather understand.
   * In Biology the outlier is often the most important.

While talking about her company the speaker mentioned:
**Computational people are treated as partners.**

A symphony of data types: Generative process.

Most cells in tumor are not cancer.

COVARIATE STRUTURE is robust.

Diffusion maps


# Test of time award talk


Stochastic gradient descent (SGD):

Online convex optimization

Compressed sensing/ sparse optimization: 
greedy algorithms: matching pursuit, LARS etc

Proximal gradient method:
 * forward-backward splitting
 * soft-thresholding


## Nonconvex optimization
very active in recent years because of deep learning problems

    *stochastic grdient and online algorithms are mainstays in ML
    *(structured) sparsity is essential in scaling up large models.


# Social Intelligence by Blaise Aguera y Arcas (Google Research)

Brain, 2011-\
Cerebra, 2014- (many, plural, local, heterogeneous, individual, small, low power, personal, private)

coral.ai

Running worloads locally is an important (but not sufficient) tool for implementing privacy.

Energy cost is bascially involved in moving data from A to B. More computing near where data is stored the more efficient in terms of power.

federated.withgoogle.com

    * Data are both abundant and rare/precious
    * Compute is both massive and limited/precious
    * Premium on quick convergence, i.e. < 1 pass over data
    * FL both enables ML fairness and can be in tension with it.

Generative models are really important in the Federated setting.

Patricia Churchland

Nagarajan and Kolter, Gradient descent GAN optimization is locally stable. NeurIPS 2017

Optimization is not exactly how life works

Optimization as a model for few-shot learning

Self-organizing neural cellular automata.

cool demo: etr.users.x20web.corp

Grand challenges:

    * Brains with fully evolved architestures and rules
    * Understanding and characterizing evolved systems.
    * Problem solving by artificial society.
    * Large-scale meta-learning in the Federated learning
    * Purposive "artifical ecology: engineering
    * Dynamical systems theory for neural ensembles?
    * Can we define quantitative "SOTAs" for sociality?
    * Practical "curved space" approach to AI ethics?


# From system 1 deep learning to system 2 deep learning by Youshu Bengio

* Narrow AI
* Sample efficeincy
* Human-provided labels
* Robustness and stupid errors

Missing to extend DL to reach human-level AI
* Out-of-distribution generalization & transer
* Higher-level cognition: system 1 -> system 2
* Agend perspective
  * Better world model
  * Causality
  * Knowledge-seeking

## Consiousness functionalities: Roadmap for priors empowering system 2

1. ML goals: handle changes in distribution, necessary for agents.
2. System 2 basics: attention & consiousness
3. COnsiousness prior: sparse factor graph.
4. Theoretical framework: meta-learning, localized cahnge hypothesis -> causal discovery.
5. Compsotional DL architectures: operating on sets of pointable objects dynamically recombined modules


## From IID to OOD

* Classical ML theory for iid data\
L. Bottou 2019: Nature does not shuffle data, we shouldn't

* Out-of-distribtuion generalization and transfer
  * Agents face non-stationarities
  * Changes in distribution due to:
    * their actions
    * actions of others
    * differnt places, times, sensors, actuators, goals, policies etc

## Compositionality helps IID and OOD generalization:

* Distributed representations
* Compostion of layers in deep net
* Systematics generalization in language analogies
  * Studied in linguistics
  * Dynamically recombine existing concepts
  * Even when new combinations have 0 probability under training distribution, e.g. science fiction

## Core ingredient for consiousness: Attention

* Focus on a one or a fewelements at a time
* Content-based soft attention
* Attention is an internal action, needs a learned attention policy
* Attention = dynamic connection

## From attention to consiousness

Global workspce theory

## The consiousness prior: sparse factor graph

* Attention: to form consious state, thought
* A thought is a low-dimensional object
  
## Meta-learning for training towards OOD generalization

* Meta-learning or learning to learn
* Multiple time scales of learning
* End-to-end learning to generalize to OOD
  
  
  































 









