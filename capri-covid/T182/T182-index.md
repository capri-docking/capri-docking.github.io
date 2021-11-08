---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 Round 51 - Target 182
comments: false
image:
  feature: pages/banner_publications.png
---

This page provides information about the predictions and analyses of the CAPRI COVID Round 51, target T182.

### Methodology
The results presented are of the Scorer submissions of Targets 182.

*Contacts:* Contacts between entities were determined using a 5 Å distance threshold. Clashes (contacts below 2.5 Å), if any, were ignored. Only inter-chain contacts were considered.

Only heteromeric contacts were kept. Then, for all models, we counted the number of contacts (defined as “contact hits”), the number of contacts a residue makes at the interface (defined as “residue hits”), and the number of different residues a residue interacts with (defined as “contact variability”).

*Sequence conservation:* Sequence conservation was calculated using [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html). Here, a low score means good conservation.
<hr>

### Target 182
The set consists of 180 models.

#### Target description

|Type|Ligand|Receptor|
|---|---|---|
|Species|*SARS-CoV-2*|*Homo sapiens* (Human)|
|Name|Nsp15|NUTF2 (homodimer)|
|Uniprot ID|[P0DTD1](https://www.uniprot.org/uniprot/P0DTD1)|[P61970](https://www.uniprot.org/uniprot/P61970)|
|Template|[6WLC](https://www.ebi.ac.uk/pdbe/entry/pdb/6WLC)|[1GY5](https://www.ebi.ac.uk/pdbe/entry/pdb/1gy5)|
|Description|Multifunctional protein involved in the transcription and replication of viral RNAs. Contains the proteinases responsible for the cleavages of the polyprotein.|Mediates the import of GDP-bound RAN from the cytoplasm into the nucleus which is essential for the function of RAN in cargo receptor-mediated nucleocytoplasmic transport. Thereby, plays indirectly a more general role in cargo receptor-mediated nucleocytoplasmic transport. Interacts with GDP-bound RAN in the cytosol, recruits it to the nuclear pore complex via its interaction with nucleoporins and promotes its nuclear import.|

#### Viral protein analyses
##### Protein visualization
<center><img src="/images/covid/T182/T182_ligand.png" width="900"/></center>
Surface representation of the ligand __Nsp15__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T182/T182_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T182/T182_Nsp15_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Nsp15__ residues.

#### Human protein analyses
##### Protein visualization
<center><img src="/images/covid/T182/T182_receptor.png" width="900"/></center>
Surface representation of the ligand __NUTF2__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T182/T182_receptor_stereo.pse)

##### Residue hit and conservation plot 
**Chain A**
<center><img src="/images/covid/T182/T182_NUTF2-A_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __HMOX1 chain A__ residues.

**Chain B**
<center><img src="/images/covid/T182/T182_NUTF2-B_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __HMOX1 chain B__ residues.


You can find [here](/capri-covid/protein-descriptions/T182_csv.zip) the csv files where every residue is listed with its residue hits, contact variability and Rate4Site scores.<br>
You can also find [here](/capri-covid/contact-hits/T182_contact_hits.csv) the list of contact hits.
<hr>
