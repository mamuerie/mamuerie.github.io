---
title: Improving the Accuracy of Single-Trial fMRI Response Estimates Using GLMsingle
authors:
- Jacob S. Prince
- Ian Charest
- Jan W. Kurzawski
- John A. Pyles
- Michael J. Tarr
- Kendrick N. Kay
date: '2022-01-01T00:00:00'
publishDate: '2024-12-24T10:27:56.018796Z'
publication_types:
- article-journal
doi: 10.7554/eLife.77599
abstract: 'Advances in artificial intelligence have inspired a paradigm shift in human
  neuroscience, yielding large-scale functional magnetic resonance imaging (fMRI)
  datasets that provide high-resolution brain responses to thousands of naturalistic
  visual stimuli. Because such experiments necessarily involve brief stimulus durations
  and few repetitions of each stimulus, achieving sufficient signal-to-noise ratio
  can be a major challenge. We address this challenge by introducing GLMsingle, a
  scalable, user-friendly toolbox available in MATLAB and Python that enables accurate
  estimation of single-trial fMRI responses (glmsingle.org). Requiring only fMRI time-series
  data and a design matrix as inputs, GLMsingle integrates three techniques for improving
  the accuracy of trial-wise general linear model (GLM) beta estimates. First, for
  each voxel, a custom hemodynamic response function (HRF) is identified from a library
  of candidate functions. Second, cross-validation is used to derive a set of noise
  regressors from voxels unrelated to the experiment. Third, to improve the stability
  of beta estimates for closely spaced trials, betas are regularized on a voxel-wise
  basis using ridge regression. Applying GLMsingle to the Natural Scenes Dataset and
  BOLD5000, we find that GLMsingle substantially improves the reliability of beta
  estimates across visually-responsive cortex in all subjects. Comparable improvements
  in reliability are also observed in a smaller-scale auditory dataset from the StudyForrest
  experiment. These improvements translate into tangible benefits for higher-level
  analyses relevant to systems and cognitive neuroscience. We demonstrate that GLMsingle:
  (i) helps decorrelate response estimates between trials nearby in time; (ii) enhances
  representational similarity between subjects within and across datasets; and (iii)
  boosts one-versus-many decoding of visual stimuli. GLMsingle is a publicly available
  tool that can significantly improve the quality of past, present, and future neuroimaging
  datasets sampling brain activity across many experimental conditions.'
tags:
- Artificial Intelligence
- Design
- Humans
- Magnetic Resonance Imaging
- Neuroimaging
- Reproducibility of Results
- Signal-To-Noise Ratio
---
