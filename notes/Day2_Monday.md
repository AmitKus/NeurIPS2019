# Dec 9, Monday 

![](pictures/Monday_Day2_Glance.png)

## [Tutorials](https://nips.cc/Conferences/2019/ScheduleMultitrack)

# [Deep Learning with Bayesian Principles](https://nips.cc/Conferences/2019/ScheduleMultitrack?event=13205)
Emtiyaz Khan (RIKEN), RIKEN Center for AI project


**Goal:**\
Human (Bayesian) learning: Life-long learning with small chunks of data.\
Deep Learning: Bulk learning from large amount of data.\
Parsi, German "Continual lifelong learning with neural networks: A review"

**Complementary**:

    * Bayesian learning: can estimate uncertainty, incremental learning\
    * Deep learning: can hadle large data, scalable

**Deep learning vs Bayesian learning**:

    * Deep learning: 
        * Frequentist (Empirical risk minimization or MLE)
        * Scalable to large data and complex model
        * Example of Nate Silver's book (Tohoku data) (**Good example**)
        * Little data on accidents for self-driving cars (data-bias)
        * Differentiation (local)
    * Bayesian principles: https
        * Sample: Prior
        * Score: Liklihood
        * Normalize: Prior*Liklihood
        * A global method: Doesn't scale, enable sequential update
        * Integrations (global)

**Deep learning**:

    * Gradient descent: derived by choosing Gaussian with fixed covariance
    * Newtons methos: derived by choosing Gausian with non-fixed covariance
    * Khan and Rue, "Learning-ALgorithms from Bayesian Principles" (**Good reference**)
    * "Global" to "local": Eq[l(theta)] ~ l(m)
    * RMSProp: 
        * Choose gaussian with diagonal covarince
        * Replace Hessian by square of gradients
        * Add square root for scaling vector
    * For Adam, use  Heavy-ball term with KL divergence as momentum.

### Summary:
    * Gradient descent is derived using a Gaussian with fixed covariance, and estimating the mean
    * Newton’s method is derived using multivariate Gaussian
    * RMSprop is derived using diagonal covariance
    * Adam is derived by adding heavy-ball momentum term
    * For “ensemble of Newton”, use Mixture of Gaussians [1]
    * To derive DL algorithms, we need to switch from a “global” to “local” approximation 
    * Then, to improve DL algorithms, we just need to add some “global” touch to the DL algorithms

## Uncertainty estimation for deep learning

![](Presentations/nate_silver_uncertainity.png)

Ovadia, Yaniv, et al. "Can You Trust Your Model's Uncertainty? Evaluating Predictive Uncertainty Under
Dataset Shift." NeurIPS (2019).

Yarin Gal’s tutorial (http://bdl101.ml/)

![](Presentations/challenges_in_uncertainty_estimation.png)

### Model view vs Data view: Bayes “automatically” defines data-Importance

![](Presentations/model_view_vs_data_view.png)

“Global” to “Local”:

    * Posterior approximations connect “global” parameters (e.g. DNN  eights) to “local” parameters (e.g. data examples)
    * The local parameters can be seen as “dual” variables that define the “importance” of the data

**Continual learning:** Kirkpatrick, James, et al. "Overcoming catastrophic  forgetting in neural networks." Proceedings of the national academy of sciences 114.13 (2017): 3521-3526.

Active deep learning: Select "important" examples while training (By Roman Bachmann).




# [Interpretable Comparison of Distributions and Models](https://nips.cc/Conferences/2019/ScheduleMultitrack?event=13208)
Wittawat Jitkrittum, Dougal J Sutherland, Arthur Gretton



# [Reinforcement Learning: Past, Present, and Future Perspectives](https://nips.cc/Conferences/2019/ScheduleMultitrack?event=13211)
Katja Hofmann



**Invited talk: Celeste Kidd**\
How To Know

