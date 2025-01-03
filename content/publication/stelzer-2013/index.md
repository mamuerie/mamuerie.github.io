---
title: 'Statistical Inference and Multiple Testing Correction in Classification-Based
  Multi-Voxel Pattern Analysis (MVPA): Random Permutations and Cluster Size Control'
authors:
- Johannes Stelzer
- Yi Chen
- Robert Turner
date: '2013-01-01T00:00:00'
publishDate: '2024-12-24T10:27:56.731426Z'
publication_types:
- article-journal
doi: 10.1016/j.neuroimage.2012.09.063
abstract: An ever-increasing number of functional magnetic resonance imaging (fMRI)
  studies are now using information-based multi-voxel pattern analysis (MVPA) techniques
  to decode mental states. In doing so, they achieve a significantly greater sensitivity
  compared to when they use univariate frameworks. However, the new brain-decoding
  methods have also posed new challenges for analysis and statistical inference on
  the group level. We discuss why the usual procedure of performing t-tests on accuracy
  maps across subjects in order to produce a group statistic is inappropriate. We
  propose a solution to this problem for local MVPA approaches, which achieves higher
  sensitivity than other procedures. Our method uses random permutation tests on the
  single-subject level, and then combines the results on the group level with a bootstrap
  method. To preserve the spatial dependency induced by local MVPA methods, we generate
  a random permutation set and keep it fixed across all locations. This enables us
  to later apply a cluster size control for the multiple testing problem. More specifically,
  we explicitly compute the distribution of cluster sizes and use this to determine
  the p-values for each cluster. Using a volumetric searchlight decoding procedure,
  we demonstrate the validity and sensitivity of our approach using both simulated
  and real fMRI data sets. In comparison to the standard t-test procedure implemented
  in SPM8, our results showed a higher sensitivity. We discuss the theoretical applicability
  and the practical advantages of our approach, and outline its generalization to
  other local MVPA methods, such as surface decoding techniques.
tags:
- Brain Mapping
- Cluster size control
- fMRI
- Humans
- Image Processing
- Magnetic Resonance Imaging/methods
- Models Neurological
- Models Theoretical
- Multiple testing
- MVPA
- Second level analysis
- Sensitivity and Specificity
- Statistics
---
