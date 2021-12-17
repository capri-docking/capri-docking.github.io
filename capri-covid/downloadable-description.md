---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 - Downloadable descriptions
comments: false
image:
  feature: pages/banner_publications.png
---

* CSV file listing residue-residue intersubunit contacts (contact hits) (TXXX_contact_hits.csv)
  * 1st column: **Chain A**: ResX.A where X is the residue number
  * 2nd column: **Chain B**: ResX.B where X is the residue number
  * 3rd column: Number of **contact hits** between the two residues, summed over all models in the scoring set.

<br>
* CSV file for receptor (human protein, in T181-184), listing statistics of residue participation in inter-subunit contacts (TXXX_receptor_*receptor-name*.csv):
  * 1st column: **Residue**: ResX.A where X is the residue number
  * 2nd column: **Residue hits**: Number of times the residue was predicted to be in contact in all the models
  * 3rd column: **Distinct contacts**: Number of different contacts the residue forms in all models
  * 4th column: [**Rate4Site**](https://www.tau.ac.il/~itaymay/cp/rate4site.html) sequence conservation Score (lowest = more conserved)

<br>
* CSV file for ligand (ciral protein, in T181-184), listing statistics of residue participation in inter-subunit contacts (TXXX_ligand_*ligand-name*.csv):
  * 1st column: **Residue**: ResX.A where X is the residue number
  * 2nd column: **Residue hits**: Number of times the residue was predicted to be in contact in all the models
  * 3rd column: **Distinct contacts**: Number of different contacts the residue forms in all models
  * 4th column: [**Rate4Site**](https://www.tau.ac.il/~itaymay/cp/rate4site.html) sequence conservation Score (lowest = more conserved)

<br>
* PyMOL session for receptor (human) (TXXX_receptor_stereo.pse):
  * Non-default parameters:
    * solvent radius = 2
    * surface quality = 2
  * Human protein, with residues colored painted according to  1) sequence conservation, and 2) contact participation. Also shown is the center of mass of every ligand in green (from the different models):
    * orange → teal: sequence conservation (Rate4site Score). Orange: well conserved; teal less conserved
    * red → blue: Number of hits (contacts a residue is involved in in all models). Red: largest number of contacts according to all the models. Blue least number of contacts. For a better visualization, values are capped to a quantile of 0.90.

<br>
* PyMOL session for ligand (S-CoV2) (TXXX_ligand_stereo.pse):
  * Non-default parameters:
    * solvent radius = 2
    * surface quality = 2
  * Viral protein, with residues colored painted according to  1) sequence conservation, and 2) contact participation. Also shown is the center of mass of every receptor in green (from the different models):
    * orange → teal: sequence conservation (Rate4site Score). Orange: well conserved; teal less conserved
    * red → blue: Number of hits (contacts a residue is involved in in all models). Red: largest number of contacts according to all the models. Blue least number of contacts. For a better visualization, values are capped to a quantile of 0.90.


<hr>
For questions, comments or feedback please contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr) or [Théo Mauri](mailto:theo.mauri@univ-lille.fr)
