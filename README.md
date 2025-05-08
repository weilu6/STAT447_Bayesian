# Logistic regression with spike-and-slab priors
## Introduction
Pumpkin seeds are rich in nutrients, and are widely consumed around the world. Effective
Statistical models for pumpkin seeds will benefit agricultural industries and botanical studies.
The dataset contains two types of pumpkins seeds (Çerçevelik, Ürgüp Sivrisi) and their
morphological features. Previous studies applied machine learning methods and achieved
accuracy rates about 87% (Koklu et al., 2021). In this project, the classification problem is
approached with Bayesian methods. The aim is to investigate the prediction performance
and the feature selection ability of the spike-and-slab prior.

## Conclusion
Both normal and spike-and-slab models have about 80% prediction accuracy with similar
uncertainty on this seed classification problem. The spike-and-slab model shows the ability
to select features, resulting in a simpler reduced model with similar prediction performance,
but less uncertainty. Hence, the spike-and-slab model can be further explored to study the
relationships between features and give guidance to the agricultural industries.
However, the involved features are relatively low-dimensional and not sparse enough to
show the power the the spike-and-slab prior. In addition, the spike-and-slab prior might
be ”washed away” during the MCMC iterations. Further studies might work on a higher
dimensional sparse data with the rescaling methods (Ishwaran and Rao, 2005).
