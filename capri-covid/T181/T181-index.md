---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 Round 51 - Target 181
comments: false
image:
  feature: pages/banner_publications.png

---

This page provides information about the predictions and analyses of the CAPRI COVID Round 51, target T181.

#### Table of Contents
{:.no_toc}
* table of contents
{:toc}

<br>
<HR>

### Methodology
The results presented are of the Scorer submissions of Target 181.

*Contacts:* Contacts between entities were determined using a 5 Å distance threshold. Clashes (contacts below 2.5 Å), if any, were ignored. Only inter-chain contacts were considered.

Only heteromeric contacts were kept. Then, for all models, we counted the number of contacts (defined as “contact hits”), the number of contacts a residue makes at the interface (defined as “residue hits”), and the number of different residues a residue interacts with (defined as “distinct contacts”).

*Sequence conservation:* Sequence conservation was calculated using [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html). Here, a low score means good conservation.

* [Target 181](/capri-covid/T181/T181-index)
* [Target 182](/capri-covid/T182/T182-index)
* [Target 183](/capri-covid/T183/T183-index) 
* [Target 184](/capri-covid/T184/T184-index)

<hr>
### Target 181
The set consists of 184 models.

All the downloadble file can be found at the end of this page.

#### Target description

| Type|| Ligand|| Receptor|
|---|---|---|---|---|
| Species|| *SARS-CoV-2*|| *Homo sapiens* (Human)|
| Name|| Orf3a|| HMOX1|
| Uniprot ID|| [P0DTC3](https://www.uniprot.org/uniprot/P0DTC3)|| [P09601](https://www.uniprot.org/uniprot/P09601)|
| PDB Template|| [6XDC](https://www.ebi.ac.uk/pdbe/entry/pdb/6xdc)|| [1N3U](https://www.ebi.ac.uk/pdbe/entry/pdb/1n3u)|
| Description|| Plays a role in virus egress via lysosomal trafficking (PubMed:33157038, PubMed:33422265).<br>Forms homotetrameric ion channels (viroporin) localized at endosomes and lysosomes, that may induce deacidification of lysosomes thereby allowing safe virion egress through lysosomal trafficking (By similarity) (PubMed:33157038, PubMed:33422265).<br>Also blocks formation of autolysosomes through binding and sequestering host TMUB1/HOPS on late endosomes. This prevents fusion of autophagosomes with lysosomes, disrupting autophagy and facilitating virus egress (PubMed:33422265).|| Heme oxygenase cleaves the heme ring at the alpha methene bridge to form biliverdin. Biliverdin is subsequently converted to bilirubin by biliverdin reductase. Under physiological conditions, the activity of heme oxygenase is highest in the spleen, where senescent erythrocytes are sequestrated and destroyed. Exhibits cytoprotective effects since excess of free heme sensitizes cells to undergo apoptosis.|


#### Viral protein analyses
##### Protein visualization
<center><img src="/images/covid/T181/T181_ligand.png" width="900"/></center>
Surface representation of the ligand __Orf3a__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for a better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.


The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T181/T181_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T181/T181_Orf3a_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Orf3a__ residues.

#### Human protein analyses
##### Protein visualization
<center><img src="/images/covid/T181/T181_receptor.png" width="900"/></center>
Surface representation of the ligand __HMOX1__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T181/T181_receptor_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T181/T181_HMOX1_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __HMOX1__ residues.

<hr>
### Downloadable files

| Target| PyMOL sessions| Contact hits| CSV files for receptor and ligand|
|---|---|---|---|
| T181| [T181_ligand](/capri-covid/PyMOL-sessions/T181/T181_ligand_stereo.pse) / [T181_receptor](/capri-covid/PyMOL-sessions/T181/T181_receptor_stereo.pse)|[T181_contact-hits](/capri-covid/contact-hits/T181_contact_hits.csv)|[T181_csv](/capri-covid/protein-descriptions/T181_csv.zip)|

The description of every dowloadables can be found [here](/capri-covid/downloadable-description)
<hr>

<sup><sub>If you have any problem or comment you can contact [Marc Lensink](mailto:marc.lensink@univ-lille.fr) or [Théo Mauri](mailto:theo.mauri@univ-lille.fr)</sub></sup>
