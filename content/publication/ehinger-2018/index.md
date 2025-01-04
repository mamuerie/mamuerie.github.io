---
title: 'Unfold: An Integrated Toolbox for Overlap Correction, Non-Linear Modeling,
  and Regression-Based EEG Analysis'
authors:
- Benedikt V. Ehinger
- Olaf Dimigen
date: '2018-01-01T00:00:00'
publishDate: '2024-12-24T10:27:53.585585Z'
publication_types:
- book
doi: 10.1101/360156
abstract: Electrophysiological research with event-related brain potentials (ERPs)
  is increasingly moving from simple, strictly orthogonal stimulation paradigms towards
  more complex, quasiexperimental designs and naturalistic situations that involve
  fast, multisensory stimulation and complex motor behavior. As a result, electrophysiological
  responses from subsequent events often overlap with each other. In addition, the
  recorded neural activity is typically modulated by numerous covariates, which influence
  the measured responses in a linear or nonlinear fashion. Examples of paradigms where
  systematic temporal overlap variations and low-level confounds between conditions
  cannot be avoided include combined EEG/eye-tracking experiments during natural vision,
  fast multisensory stimulation experiments, and mobile brain/body imaging studies.
  However, even “traditional”, highly controlled ERP datasets often contain a hidden
  mix of overlapping activity (e.g. from stimulus onsets, involuntary microsaccades,
  or button presses) and it is helpful or even necessary to disentangle these components
  for a correct interpretation of the results. In this paper, we introduce unfold,
  a powerful, yet easy-to-use MATLAB toolbox for regression-based EEG analyses that
  combines existing concepts of massive univariate modeling (“regression ERPs”), linear
  deconvolution modeling, and non-linear modeling with the generalized additive model
  (GAM) into one coherent and flexible analysis framework. The toolbox is modular,
  compatible with EEGLAB and can handle even large datasets efficiently. It also includes
  advanced options for regularization and the use of temporal basis functions (e.g.
  Fourier sets). We illustrate the advantages of this approach for simulated data
  as well as data from a standard face recognition experiment. In addition to traditional
  and non-conventional EEG/ERP designs, unfold can also be applied to other overlapping
  physiological signals, such as pupillary or electrodermal responses. It is available
  as open-source software at http://www.unfoldtoolbox.org.
tags:
- EEG
- Methods
- Unfold
- Unfold Toolbox
---
