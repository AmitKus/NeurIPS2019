# Dec 8, Sunday 


# [Hudson River Trading: AI in Financial Services and Markets](https://nips.cc/ExpoConferences/2019/schedule?workshop_id=22)

**Notes**

[Sameena Shah](https://www.linkedin.com/in/sameenashah/)

## Presentation 1: Link Prediction

Predicting missing data flows in large communication networks.

Multiplex network: Undirected graph -> Set of undirected graph
Given a network: 
    What link are supposed to showup in future (predict future missing links)?

Applications:

    * Biological networks
    * Transportation Networks
    * Global trade networks
    * Social networks

Approach:

    * Simple, interpretable for unsupervised link prediction
    * Highly structured correlation

Concepts:

    * Erdos-Renyi Graph
    * Pierre-Auger Physics Collaboration Network
    * European Airlines Networks
    * Global Trade Network
    * The link prediction problem for social network (Liben-Nowell)


## Presentation 2: Privacy Preserving Analytics

Private Data ----> Train Model <------Secret Model

Secure multi-party Computation

Salary example: R+x1 -> R+X1+X2 -> R+X1+X2+X3 -> R+X1+X2+X3-R


## Presentation 3: Applying machine learning in financial markets (HRT)

Kevin Lee
Ian 

HRT: Deep Learning in production since 2014.

**Data**: Market data

    * Candelstick plots (interesting way of looking data)

**Financial market data**:

    * How much independent data?
    * Non-stationarity
    * Low signal to noise

**Questions**:

    * What to predict?
    * How should we sample/filter/augment data?
    * How fast do we need to be?
    * Is deep learning viable?

**Architectures**:

    * Temporal concolutional networks (Koltun et. al.)
        * Long term dependencies
        * Efficient to train
        * Partial update possible
        * Sampling? Featurization?
    * RNN (Olah picture, C,F. Bradbury et al.):
    * Transformers
        * Heavy-weight model of the data
        * Expensive but parralelizable
        * O(N^2) in input length, updating?
        * Not a natural fit for the domain? Do they incode right prior for the problem?
    

## Presentation 4:

**How to use predictive models:**

    * Simple rules of thumb
    * Learn a policy
    * Holy Grail: end-to-end learning
       
Reinforcement learning and optimal control:
    * Inventory management
    * Portfolio optimization

Traversing through different elements of RL:

    * Agent and states: Building ML models for financial models
    * Actions:
        * How to chose an action space?
        * Small action spaces {No action, Buy maket order for 100 shares}
        * Large action spaces
        * Higher level actions (if in state X run algorithm Y and observed results)
    * Environment:
        * Typically model trained in offline fashion. Replicating the real market is hard
    * Rewards:
        * How to penalize underdelivery?
        * How to capture market impact rewards?
    * Performance and benchmarking:
        * Similar to recommendation systems.
        * Online experiments are costly
            * A/B testing
            * Bandits
        * What metric to use for offline performance evaluation?
            * Similar issues to defining rewards

## Presentation 5: Forecasting financial returns using machine learning

Dai Shi, PingXing Yi

Fama Eugene: Efficient market hypothesis

ALpha research @ 2sigma

NLP: Sentence -> Embedding -> LSTM -> Classification

Feature engineering to express the hypothesis more precisely.

Portfolio optimization:

**Why do we need simulations:**

    * Trading costs
    * Regulations
    * Risks controls

**Challenges**

    * Extremely signal-to-noise ration: 10% R-squared
    * Short data history
    * Non stationarity


# Panel Discussion: Bridging gap between effective algorithms and medical adoption

Companies: Anthem.ai, Doc.ai

Validating models in medicine?

    * One hospital system to other system generalization
    * One year to other year generalization
    * Lots of insights are not directly actionable





## Talks

05:35 pm: West Ballrooms A + B\
# [Sony: Computational Creativity for Music and Gastronomy Applications](https://nips.cc/ExpoConferences/2019/schedule?talk_id=59)

 Michael Spranger

 Alxmusic

 DeepBach: a steerable moel for Bach chroale generation

 NONOTO: A model-agnostic web interface for interactive music composition by inpainting.

 NONOTO -> Ableton

 DrumNet

 AlxGastronomy

 Can we build an AI that wins 3 michellin star?

 Sony AI: Gaming, Imaging and Sensing, Gastronomy

 




## Demo

West 211 - 214 #8\
[SigOpt: Advanced Hyperparameter Optimization Methods](https://nips.cc/ExpoConferences/2019/schedule?demo_id=27)

West 211 - 214 #9\
[Sony: ML-based music generation tools](https://nips.cc/ExpoConferences/2019/schedule?demo_id=29)

West 211 - 214 #2\
[BAIDU: PaddlePaddle – An industry-grade end-to-end deep learning platform](https://nips.cc/ExpoConferences/2019/schedule?demo_id=21)