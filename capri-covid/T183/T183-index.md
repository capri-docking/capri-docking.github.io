---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 Round 51 - Target 183
comments: false
image:
  feature: pages/banner_publications.png
---

This page provides information about the predictions and analyses of the CAPRI COVID Round 51, target T183.

### Methodology
The results presented are of the Scorer submissions of Target 183.

*Contacts:* Contacts between entities were determined using a 5 Å distance threshold. Clashes (contacts below 2.5 Å), if any, were ignored. Only inter-chain contacts were considered.

Only heteromeric contacts were kept. Then, for all models, we counted the number of contacts (defined as “contact hits”), the number of contacts a residue makes at the interface (defined as “residue hits”), and the number of different residues a residue interacts with (defined as “distinct contacts”).

*Sequence conservation:* Sequence conservation was calculated using [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html). Here, a low score means good conservation.

* [Target 181](/capri-covid/T181/T181-index)
* [Target 182](/capri-covid/T182/T182-index)
* [Target 183](/capri-covid/T183/T183-index) 
* [Target 184](/capri-covid/T184/T184-index)

<hr>

### Target 183
The set consists of 164 models.

All the downloadble file can be found at the end of this page.

#### Target description

| Type|| Ligand|| Receptor|
|---|---|---|---|---|
| Species|| *SARS-CoV-2*|| *Homo sapiens* (Human)|
| Name|| Nsp8|| EXOSC8|
| Uniprot ID|| [P0DTD1](https://www.uniprot.org/uniprot/P0DTD1)|| [Q96B26](https://www.uniprot.org/uniprot/Q96B26)|
| PDB Template|| [2NN6](https://www.ebi.ac.uk/pdbe/entry/pdb/2nn6)|| [3UB0.D](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [2AHM.G](https://www.ebi.ac.uk/pdbe/entry/pdb/2ahm), [6XIP](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip)|
| Description|| Multifunctional protein involved in the transcription and replication of viral RNAs. Contains the proteinases responsible for the cleavages of the polyprotein.|| Non-catalytic component of the RNA exosome complex which has 3'->5' exoribonuclease activity and participates in a multitude of cellular RNA processing and degradation events. In the nucleus, the RNA exosome complex is involved in proper maturation of stable RNA species such as rRNA, snRNA and snoRNA, in the elimination of RNA processing by-products and non-coding 'pervasive' transcripts, such as antisense RNA species and promoter-upstream transcripts (PROMPTs), and of mRNAs with processing defects, thereby limiting or excluding their export to the cytoplasm.|

#### Viral protein analyses
##### Protein visualization
<center><img src="/images/covid/T183/T183_ligand.png" width="900"/></center>
Surface representation of the ligand __Nsp8__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T183/T183_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T183/T183_Nsp8_comparing_residue_hits_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Nsp8__ residues.

#### Human protein analyses
##### Protein visualization
<center><img src="/images/covid/T183/T183_receptor.png" width="900"/></center>
Surface representation of the ligand __EXOSC8__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T183/T183_receptor_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T183/T183_EXOSC8_comparing_residue_hits_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __EXOSC8__ residues.

<hr>
### Downloadable files

| Target| PyMOL sessions| Contact hits| CSV files for receptor and ligand|
|---|---|---|---|
| T183| [T183_ligand](/capri-covid/PyMOL-sessions/T183/T183_ligand_stereo.pse) / [T183_receptor](/capri-covid/PyMOL-sessions/T183/T183_receptor_stereo.pse)|[T183_contact-hits](/capri-covid/contact-hits/T183_contact_hits.csv)|[T183_csv](/capri-covid/protein-descriptions/T183_csv.zip)|

The description of every dowloadables can be found [here](/capri-covid/downloadable-description)
<hr>
<sup><sub>If you have any problem or comment you can contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr) or [Théo Mauri](mailto:theo.mauri@univ-lille.fr)</sub></sup>
