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











