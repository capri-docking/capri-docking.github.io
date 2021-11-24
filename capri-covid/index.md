---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: Round 51 CAPRI-COVID-19 Open Science Initiative - Part I - Prediction result summary, version November 2021
comments: false
image:
  feature: pages/banner_publications.png
---
### Introduction
This CAPRI prediction Round was carried out as part of the [CAPRI COVID-19 Open Science initiative](https://www.ebi.ac.uk/pdbe/complex-pred/capri/round/51/). The Round offered 4 targets: T182, T183, T184, T185. The first three of these are complexes of SARS-CoV-2 proteins with human host proteins. The complexes were prioritized from the interaction proteomics study of Gordon et al. (2020) [1].  
The fourth target (T185) is a multi-component complex of SARS-CoV-2 proteins and RNA, suggested by Prof. Shozeb Haider (UCL).  
Target T181 - also a virus-host complex - was offered in the joint CASP14-CAPRI prediction (CAPRI Round 50) in 2020 and has been added to this analysis as its three-dimensional structure to-date has not been resolved.


Here we present initial results on the 4 virus-host complexes (T181-T184) listed above. Prediction results for T185, the multi-component viral protein-RNA complex will be made available later. For information on Round 50/51 targets T181-T184 see “[Target Information](/capri-covid/target-descriptions)”


For all the targets for which submitted models are evaluated here, experimental structures are so far not available. Evaluating the predicted models against the experimental structure of each target was therefore not possible. Instead, a novel alternative protocol was used to evaluate the prediction results. This protocol was developed based on an initial consultation with participants of Round 51, and was further defined by the working group composed of
[Marc Lensink](mailto:marc.lensink@univ-lille.fr)<sup><sub>1</sub></sup> and [Shoshana Wodak](mailto:shoshana.wodak@gmail.com)<sup><sub>2</sub></sup> (the CAPRI assessment team), [Théo Mauri](mailto:theo.mauri@univ-lille.fr)<sup><sub>1</sub></sup>, [Guillaume Brysbaert](mailto:guillaume.brysbaert@univ-lille.fr)<sup><sub>1</sub></sup>, members of Marc Lensink’s team, and [Paul Bates](mailto:paul.bates@crick.ac.uk)<sup><sub>3</sub></sup>.


The evaluation of submitted models for T181-T184 consists of three main parts, representing analyses of increasing complexity and different finality. **Part I**, presented here, involves evaluating the propensity of residues in each protein (receptor or ligand) to contribute to the interaction interface, and the number of distinct inter-molecular residue-residue contacts a residue engages, in the ensemble of submitted models for each target. In addition, the frequency with which protein residues engage in inter-molecular contacts in the predicted models, is compared to residue conservation levels, which tend to indicate involvement in biological function. **These properties taken together may be used to prioritize protein regions for drug binding experiments, or targeted mutations that may interfere with the formation of the virus-host complex in question, or simply indicate ‘sticky’ regions that may engage in promiscuous interactions**.


The analyses of **parts II and III** are still in progress. In part II, the models submitted for each target are clustered on the basis of structural similarity and clusters are ranked using a set of objective criteria. Highly ranking clusters may be considered as containing more reliably predicted complexes.  In part III, AlphaFold 2 and ClusPro are used in combination to generated models for all 4 targets. For targets where the human and/or SARS-CoV-2 protein is involved in higher order assemblies, the predictions are performed in the context of these additional assemblies. This analysis is carried out in collaboration with [Dima Kozakov](mailto:midas@laufercenter.org) and [Dzmitry Padhorny](mailto:dnpodgorny@gmail.com).


<sup><sub>1</sub></sup><sub>: Univ. Lille, CNRS; UMR8576 - UGSF - Unité de Glycobiologie Structurale et Fonctionnelle, Lille, F-59000, France</sub>  
<sup><sub>2</sub></sup><sub>: Center for Structural Biology, VIB-VUB, Brussels, Belgium</sub>  
<sup><sub>3</sub></sup><sub>: Biomolecular Modelling Laboratory, The Francis Crick Institute, London, UK.</sub>
<hr>

### Results

Go directly to results for target:

* [T181](/capri-covid/T181/T181-index) - **Orf3a / HMOX1**
* [T182](/capri-covid/T182/T182-index) - **Nsp15 / NUTF2**
* [T183](/capri-covid/T183/T183-index) - **Nsp8 / EXOSC8**
* [T184](/capri-covid/T184/T184-index) - **Nsp7 / RhoA**


<hr>
### Material and Methods

#### Submitted models

||Predictors||Scorers||
|Target ID|Groups|Models|Groups|Models|
|:--|---|---|---|---|
|T181|26|1257|19|185|
|T182|30|1972|19|181|
|T183|27|1523|19|164|
|T184|30|1811|19|190|

*__Table 1__: summary of target participation; number of models submitted and evaluated.*


| Target ID |  ||||
| CAPRI | CASP | Components | Uniprot IDs| PDB Templates |
|---|---|---|:--|---|
| T181| H1103| **Orf3a** / **HMOX1**| [P0DTC3](https://www.uniprot.org/uniprot/P0DTC3) / [P09601](https://www.uniprot.org/uniprot/P09601)| [6XDC](https://www.ebi.ac.uk/pdbe/entry/pdb/6xdc) / [1N3U](https://www.ebi.ac.uk/pdbe/entry/pdb/1n3u)|
| T182| NA| **Nsp15** / **NUTF2**| [P0DTD1](https://www.uniprot.org/uniprot/P0DTD1) / [P61970](https://www.uniprot.org/uniprot/P61970)| [6WLC](https://www.ebi.ac.uk/pdbe/entry/pdb/6WLC) / [1GY5](https://www.ebi.ac.uk/pdbe/entry/pdb/1gy5)|
| T183| NA| **Nsp8** / **EXOSC8**| [P0DTD1](https://www.uniprot.org/uniprot/P0DTD1) / [Q96B26](https://www.uniprot.org/uniprot/Q96B26)| [2NN6](https://www.ebi.ac.uk/pdbe/entry/pdb/2nn6) / [3UB0:D](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [2AHM:G](https://www.ebi.ac.uk/pdbe/entry/pdb/2ahm), [6XIP](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip)|
| T184| NA| **Nsp7** / **RhoA**|[P0DTD1](https://www.uniprot.org/uniprot/P0DTD1) / [P61586](https://www.uniprot.org/uniprot/P61586)| [6XIP:C](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip), [3UB0:C](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [6M5I:A](https://www.ebi.ac.uk/pdbe/entry/pdb/6m5i) / [5C2K:A](https://www.ebi.ac.uk/pdbe/entry/pdb/5c2k), [4LHW:E](https://www.ebi.ac.uk/pdbe/entry/pdb/4lhw), [2J1L:A](https://www.ebi.ac.uk/pdbe/entry/pdb/2j1l)|

*__Table 2__: summary of target information.*


#### Analysis method

**Part I.**

Part I of the analysis comprised the following steps.  
1- Using the **ensemble of scorer-submitted models**, the following quantities were computed: (a) the number of times a residue of the Receptor and Ligand proteins, respectively, makes contacts with a residue of the partner protein (with a contact being defined as atoms of both residues coming within a distance of ≤ 5Å of one another)  (defined as **residue hits**), (b) the total number of inter-molecular residue-residue contacts a residue engages in, denoted as **contact hits**, and (c) the number of distinct inter-molecular residue-residue contacts a residue engages in, denoted as **distinct contacts**

*Rationale:* Previous work has shown [2-4] that predicting the residues that contribute to the interaction interface (Recall ≥ 0.5) is easier than producing a correct model
of the assembly (e.g. a model of acceptable quality or better). Therefore, the residues of the receptor or ligand protein predicted to engage most often in contacts with the partner protein in the **ensemble of submitted models**, may indicate regions of the proteins that are part of the interaction interface even for a significant fraction of incorrect modes. 

2- For each of the interacting proteins the level or residue conservation was computed using the [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) algorithm, where a low score indicates high conservation.  
*Rationale:*  a higher than average level of residue conservation likely indicates involvement in biological function (which includes binding to an interaction partner). It was therefore deemed of interest to compare the level of residue conservation in the target proteins and to investigate the extent of overlap with the frequency with which they engage in inter-molecular contacts in the predicted models.



<hr>
### References

1. A SARS-CoV-2 protein interaction map reveals targets for drug repurposing, Gordon DE et al., Nature. 2020 Jul;583(7816):459-468. doi: 10.1038/s41586-020-2286-9. Epub 2020 Apr 30.
2. Lensink MF, Wodak SJ. Blind predictions of protein interfaces by docking calculations in CAPRI. Proteins 2010;78(15):3085-3095.
3. Lensink MF, Velankar S, Baek M, Heo L, Seok C, Wodak SJ. The challenge of modeling protein assemblies: the CASP12-CAPRI experiment. Proteins 2018;86 Suppl 1:257-273.
4. Lensink MF, et al. Prediction of protein assemblies, the next frontier: The CASP14-CAPRI experiment. Proteins. 2021 Aug 28. doi: 10.1002/prot.26222.

<hr>
### Download description

The description of target dowloadables can be found [here](/capri-covid/downloadable-description)

<hr>
<sub>For questions or comments please contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr) or [Théo Mauri](mailto:theo.mauri@univ-lille.fr)</sub>
