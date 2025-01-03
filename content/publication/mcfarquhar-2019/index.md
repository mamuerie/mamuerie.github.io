---
title: Modeling Group-Level Repeated Measurements of Neuroimaging Data Using the Univariate
  General Linear Model
authors:
- Martyn McFarquhar
date: '2019-01-01T00:00:00'
publishDate: '2024-12-24T10:27:55.348591Z'
publication_types:
- article-journal
doi: 10.3389/fnins.2019.00352
abstract: Group-level repeated measurements are common in neuroimaging, yet their
  analysis remains complex. Although a variety of specialized tools now exist, it
  is surprising that to-date there has been no clear discussion of how repeated-measurements
  can be analyzed appropriately using the standard general linear model approach,
  as implemented in software such as SPM and FSL. This is particularly surprising
  given that these implementations necessitate the use of multiple models, even for
  seemingly conventional analyses, and that without care it is very easy to specify
  contrasts that do not correctly test the effects of interest. Despite this, interest
  in fitting these types of models using conventional tools has been growing in the
  neuroimaging community. As such it has become even more important to elucidate the
  correct means of doing so. To begin, this paper will discuss the key concept of
  the expected mean squares (EMS) for defining suitable F-ratios for testing hypotheses.
  Once this is understood, the logic of specifying correct repeated measurements models
  in the GLM should be clear. The ancillary issue of specifying suitable contrast
  weights in these designs will also be discussed, providing a complimentary perspective
  on the EMS. A set of steps will then be given alongside an example of specifying
  a 3-way repeated-measures ANOVA in SPM. Equivalency of the results compared to other
  statistical software will be demonstrated. Additional issues, such as the inclusion
  of continuous covariates and the assumption of sphericity, will also be discussed.
  The hope is that this paper will provide some clarity on this confusing topic, giving
  researchers the confidence to correctly specify these forms of models within traditional
  neuroimaging analysis tools.
---
