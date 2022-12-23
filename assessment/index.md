---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI Assessment results
comments: false
image:
  feature: pages/banner_publications.png
---

<hr />

### Round 54 CASP15-CAPRI

CAPRI Round 54 comprised 37 targets, divided into 38 Assessment Units
(AU). The assessment results of the top-5 submitted models for
Predictors, Scorers, and CASP Assembly Prediction participants for all
individual target interfaces are collected in [this comma-separated
file](files/casp15_selection.csv).  For explanation of the invididual
columns we refer to the [CAPRI Scoreset v2022 help
page](https://scoreset.org/index.php?csv).

Most AUs are single-target single-interface, with the exception of the
following:

|Target|AU 1|AU 2|
|---|---|---|
|T203 | average of interfaces 1-3 | interface 4|
|T204 | best of interfaces 1-2 | average of interfaces 3-8|
|T219/T220/T221|best of interfaces 1-3|best of interfaces 4|

You can find the slides of Marc Lensink's CAPRI presentation in the
CASP assembly session
[HERE](https://predictioncenter.org/casp15/doc/presentations/Day2/Assessment_Assembly-CAPRI_MLensink.pdf).

The image below shows the CAPRI ranking. "AF2-MULTIMER" is the
off-the-bench AlphaFold-Multimer modeling as submitted by the Elofsson
group.

<center>
<img src="files/casp15_ranking.png" width="800" />
</center>

<hr />

### Round 53 Target T187 and T188

Targets T187 and T188 featured a large conformational change upon
binding to dsDNA.  However, the AlphaFold monomer structure captured
this conformational change perfectly.  Unfortunately, no predictors or
scorers were able to produce acceptable models for T187.  The
assessment results for the top-5 submitted models are collected in
[this comma-separated file](files/round53_selection.csv).  In this
file, interface 1 corresponds to the whole target; interface 2 is the
protein dimer alone.

For T188 the bound dsDNA structure was given. This resulted in
acceptable models for 2 predictor groups: Fernandez-Recio (top-1) and
Pierce (top-5); and 5 scorer groups: Fernandez-Recio, Zou and server
PYDOCKDNAWEB (top-1), and Kihara and server MDOCKPP (top-5).

Medium-quality models for the protein dimer were produced (in top-5
submission) by Venclovas, Zacharias, Huang, Chang, Kihara, and servers
LZERD and HDOCK. Scorers Kihara, Bates, Huang, Chang, Zou, Shen, and
servers HDOCK, LZERD and PYDOCKDNAWEB recognized these (again, top-5).

The quality of the protein-dnDNA models strongly depended on the
protein dimer modelling quality, as can be seen in the image below.

<center>
<img src="files/round53_irms.png" width="800" />
</center>

<hr />
For questions or comments please contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr)
