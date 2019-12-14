# Dec 13, Friday

# Retrospective in Machine Learning

## Opening Remarks

Some possibilities:

    *Talk about flaws in methodology
    *Reveal limitations of approach
    *Discuss new perspectives

ml.retrospectives.github.io

## From Machine Learning to Machine Reasoning by Leon Bottou

### Genesis:

Auxiliary tasks

Ray Mooney statement.

PyTorch BigGraph

* The value of "logical structure" may not show when we use performance metrics that average over training dataset.
* Attention mechanisms seem to be more successful at extracting some structure. 

# The Copycat Project by Melanie Mitchell

Advisor: Douglas Hofstader

## Architecture of Copycat

Concept network (Slipnet)

Demo (Jim Marchall's MetaCat)

## Important ideas from Copycat

* Modeling analogy-making-and other "high-level" cognitive processes-as perception
* Perception unforlds dynamically over time, continually integrating sysmbolic/subsymbolic 
* Continual integration of prior knowledge with bottom up

**Without concepts there can be no thought, and without analogies there can be no concepts.**


# Fairness in Machine Learning & the Dangers of Solutionism by Zach Lipton

## Supervised learning


## Unsupervised learning
GANs are a simple application of Artificial Curiosity where the environment returns whether C's output is in a given set.

nnaisense

## Skin cancer detection

Interpretability:
* Why this lesion instead of only which lesion.
  

# Critical perspectives on computer vision by Emily Denton

Does object recognition work for everyone? DeVries 2019.

Mimi Onuoha, Data & Society

Excavating AI by Kate Crawford and Trevor

# Percy Liang

The unreasonable effectiveness of mathematics in the natural sciences by Eugene Wigner

## Dirichlet process

$$ G \approx DP(\alpha_0, G_0) $$

## Stick breaking construction

## Chinese restaurant process

## Lessons
* Lesson 1: Bayesian inference is hard work.
* Lesson 2: Hyperparameters are still there.
  * Lots of hyperparameter tuning
* Lesson 3: Prior is icing on the cake
  * Context-free grammars are incomplete models of language.
  * Non-parametric prior does not mean not opinionated.

# Lessons:
* Liklihood function and GD is good.
* Leveraging assumptions
  * double edged sword
  * GD is "robust"
* Generality matters


* Focus on model-agnostic research.
* Get back to modeling, leveraging structure of data.
  
# Zoubin Ghahramani: Learning the structure of deep sparse graphical models

How do we choose the structure of network?\
Bayesian non-parametrics + Deep learing?

Bayesian non-parametrics: Indian buffet process

# Neural ODE

Can delegate to ODE solvers

Augmmented Neural ODEs

Three main motivations:
* Replacement for Resnets
* Time series models.
* Invertible normalizing flows.

Do we need ODEs for time series?
* Irregularily-sample data
* Deterministec, so need SDEs


Pointflow: Yang et al.


# Inverse problem

## Neural reparametrization improved structural optimization by Stephan Hoyer

Deep image prior (Ulyanov et al, IJCV 2018)

Differentiable image parametrizations, Mordvintsev et al, Distill 2018

* Without sacrificing exact physics?
* Without excessively large training datasets?


*Hierarchical features
*Multi-scale spatial structure
*Approximate translation invariance

Efficient totpolgy optimization in MATLAB using 88 lines of code. (2011)


# Toward a Generl AI-Agent Architecture by Sutton

**Great presentation: Look at slides**


functiona approximation, partial observability, temporal abstraction, non-stationarity.


















