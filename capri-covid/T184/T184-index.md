---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 Round 51 - Target 184
comments: false
image:
  feature: pages/banner_publications.png
---

This page provides information about the predictions and analyses of the CAPRI COVID Round 51, target T184.

#### Table of Contents
{:.no_toc}
* table of contents
{:toc}

<br>
<HR>

### Methodology
The results presented are of the Scorer submissions of Target 184.

*Contacts:* Contacts between entities were determined using a 5 Å distance threshold. Clashes (contacts below 2.5 Å), if any, were ignored. Only inter-chain contacts were considered.

Only heteromeric contacts were kept. Then, for all models, we counted the number of contacts (defined as “contact hits”), the number of contacts a residue makes at the interface (defined as “residue hits”), and the number of different residues a residue interacts with (defined as “distinct contacts”).

*Sequence conservation:* Sequence conservation was calculated using [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html). Here, a low score means good conservation.

* [Home page](/capri-covid/)
* [Target 181](/capri-covid/T181/T181-index)
* [Target 182](/capri-covid/T182/T182-index)
* [Target 183](/capri-covid/T183/T183-index) 
* [Target 184](/capri-covid/T184/T184-index)

<hr>


### Target 184
The set consists of 190 models.

All the downloadable file can be found at the end of this page.

#### Target description

| Type| | Ligand|   | Receptor|
|---|---|---|---|---|
| Species| | *SARS-CoV-2*|   | *Homo sapiens* (Human)|
| Name| | Nsp7|   | RhoA|
| Uniprot ID| | [P0DTD1](https://www.uniprot.org/uniprot/P0DTD1)|   | [P61586](https://www.uniprot.org/uniprot/P61586)|
| PDB Template| | [6XIP.C](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip), [3UB0.C](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [6M5I.A](https://www.ebi.ac.uk/pdbe/entry/pdb/6m5i)|   | [5C2K.A](https://www.ebi.ac.uk/pdbe/entry/pdb/5c2k), [4LHW.E](https://www.ebi.ac.uk/pdbe/entry/pdb/4lhw), [2J1L.A](https://www.ebi.ac.uk/pdbe/entry/pdb/2j1l)|
| Description| | Multifunctional protein involved in the transcription and replication of viral RNAs. Contains the proteinases responsible for the cleavages of the polyprotein.|   | Small GTPase which cycles between an active GTP-bound and an inactive GDP-bound state. Mainly associated with cytoskeleton organization, in active state binds to a variety of effector proteins to regulate cellular responses such as cytoskeletal dynamics, cell migration and cell cycle|

#### Analysis of viral protein
##### Visualization
<center>
<a href="/images/covid/T184/T184_ligand.png">
<img src="/images/covid/T184/T184_ligand.png" width="900"/>
</a>
</center>
Surface representation of the ligand __Nsp7__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T184/T184_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center>
<a href="/images/covid/T184/T184_Nsp7_comparing_residue_hits_and_sequence_conservation.png">
<img src="/images/covid/T184/T184_Nsp7_comparing_residue_hits_and_sequence_conservation.png" width="900"/>
</a>
</center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Nsp7__ residues.

#### Analysis of human protein
##### Visualization
<center>
<a href="/images/covid/T184/T184_receptor.png">
<img src="/images/covid/T184/T184_receptor.png" width="900"/>
</a>
</center>
Surface representation of the ligand __RhoA__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for a better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T184/T184_receptor_stereo.pse)

##### Residue hit and conservation plot 

<center>
<a href="/images/covid/T184/T184_Rhoa_comparing_residue_hits_and_sequence_conservation.png">
<img src="/images/covid/T184/T184_Rhoa_comparing_residue_hits_and_sequence_conservation.png" width="900"/>
</a>
</center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __RhoA__ residues.

<hr>
### Downloadable files

| Target| PyMOL sessions| Contact hits| CSV files for receptor and ligand|
|---|---|---|---|
| T184| [T184_ligand](/capri-covid/PyMOL-sessions/T184/T184_ligand_stereo.pse) / [T184_receptor](/capri-covid/PyMOL-sessions/T184/T184_receptor_stereo.pse)|[T184_contact-hits](/capri-covid/contact-hits/T184_contact_hits.csv)|[T184_csv](/capri-covid/protein-descriptions/T184_csv.zip)|

The description of the dowloadable files can be found [here](/capri-covid/downloadable-description)
<hr>

For questions, comments or feedback please contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr) or [Théo Mauri](mailto:theo.mauri@univ-lille.fr)
