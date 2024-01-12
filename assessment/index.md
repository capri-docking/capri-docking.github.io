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

### Round 55

CAPRI Round 55 had four targets, three of them with antibodies,
including one (T231) binding a peptide. The remaining target (T232)
was an EM structure of an existing X-ray structure, however with a
different binding mode.  For all four targets, the Brysbaert group in
collaboration with the assessors had made AlphaFold2 models available,
which were also assessed.

The results for all four targets of Round 55 can be found in [this
comma-separated file](files/round55.csv).

#### Target T231

The 25 AlphaFold models featured 22 acceptable quality models,
including the first 10 models, 2 medium quality models with models
ranked 13 and 14, and one incorrect model.  Seven predictor groups
(Pierce, Zou, Venclovas, Karaca, Huang, Vakser, Kozakov/Vajda) and 3
servers (LZERD, HDOCK, CLUSPRO) produced medium-quality models in
their top-5 submission.  An additional 6 predictor groups (Kihara,
Furman, S_Chang, Fernandez-Recio, Brysbaert, Bates) and one server
(PYDOCKWEB) produced acceptable models.  Scorer groups Zou, Giulini,
Huang and server HDOCK recognized medium quality models, while scorer
groups Kihara, Venclovas, Karaca, Bates and server LZERD recognized
acceptable models.

#### Target T232

The 25 AlphaFold models were all of medium quality.  More than half of
the predictor groups and 80% of the scorer groups also produced 5/5**
models.  With a few rare exceptions, there were no models of
acceptable quality.

#### Targets T233 and T234

These two targets featured binding of two different Fab's to a major
histocompatibility complex-I.  All AlphaFold models were incorrect.
Interestingly, while there were no good solutions for T234, a few
groups managed medium-quality solutions (and no acceptable) for T233.
These were S_Chang, Kihara, Zou, Venclovas and scorer group Zou.

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

### Round 49 Target T163

Target T163 features a 2:2 hetero-tetramer, with 2 copies of SYCE2 and
2 copies of TEX12.  It has now been published as PDB 6R17.  T163
contains 2 homo-dimeric interfaces: T163.1 (SYCE2) and T163.5 (TEX12);
and 3 hetero-dimeric interfaces: T163.2 (SYCE2.Nt/TEX12), T163.3
(SYCE2'.Ct/TEX12) and T163.4 (SYCE2.Ct/TEX12').

A homo-dimeric structure of TEX12 existed, but it did not correspond
to the binding mode in T163.  This might have complicated the
prediction of this target.  The assessment results for the 5
interfaces can be found in [this comma-separated
file](files/target163_selection.csv).

Predictors and Scorers with models of acceptable quality or better in
their top-5 submitted models are listed in the following table:

|Interface|Predictors|Scorers|
|---|---|---|
|T163.1|-|Fernandez-Recio|
|T163.5|Kihara (medium)|Kihara (medium)|
|T163.2|Venclovas, Kihara, Gray|Seok (medium), Oliva, Perthold|
|T163.3|-|-|
|T163.4|LZERD|-|

<hr />

### Round 47 Target T160

Target T160 features the structure of the Bacillus anthracis Sap
S-layer assembly domain, now published as PDB 6HHU.  It consists of 6
individual domains that are organized in two dimensions.  To it are
bound two nanobodies.  The individual interfaces bury between 150 and
610 &Aring;<sup>2</sup>.  The interfaces are indicated in the
following picture of the target.

<center>
<img src="files/T160_2D.png" width="600" />
</center>

Nanobody Nb694 is bound to domain D1 through interface T160.2, while
Nb684 is bound to domains D1 and D2 through interfaces T160.1 and
T160.5.  Whereas the interface between domains 1 and 2 was best
predicted, nobody managed to identify the nanobody binding modes.  The
results for all interfaces can be found in [this comma-separated
file](files/target160_selection.csv).  Predictors and Scorers with
models of acceptable quality or better in their top-5 submitted models
are listed in the following table:

|Interface|Predictors|Scorers|
|---|---|---|
|T160.2|-|-|
|T160.1|-|-|
|T160.5|-|-|
|T160.6|GALAXYPPDOCK, Fernandez-Recio,|Fernandez-Recio, Kihara, |
|      |Andreani/Guerois|LZERD, Venclovas, Bates|
|T160.8|Andreani/Guerois (medium),|Venclovas (medium)|
|      |Kozakov/Vajda (medium), Venclovas (medium)||
|T160.7|Gray|-|
|T160.3|CLUSPRO (medium), Kozakov/Vajda (medium),|Venclovas (medium)|
|      |Andreani/Guerois (medium), Venclovas (medium)||
|T160.9|-|HDOCK|
|T160.4|-|-|

<hr />
For questions or comments please contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr)
