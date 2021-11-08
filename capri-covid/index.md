---
layout: page
tags: [Jekyll, CAPRI, Docking, Simulation, Structural Biology, Computational Biology, Modelling, Protein Structure]
modified: 2014-08-08T20:53:07.573882-04:00
title: CAPRI COVID-19 Round 51
comments: false
image:
  feature: pages/banner_publications.png
---

This page provides information about the predictions and analyses of the CAPRI COVID Round 51, targets T181, T182, T183 and T184.

#### Table of Contents
{:.no_toc}
* table of contents
{:toc}

<br>
<HR>

### Methodology
The results presented are of the Scorer submissions of Targets 181-184.

*Contacts:* Contacts between entities were determined using a 5 Å distance threshold. Clashes (contacts below 2.5 Å), if any, were ignored. Only inter-chain contacts were considered.

Only heteromeric contacts were kept. Then, for all models, we counted the number of contacts (defined as “contact hits”), the number of contacts a residue makes at the interface (defined as “residue hits”), and the number of different residues a residue interacts with (defined as “contact variability”).

*Sequence conservation:* Sequence conservation was calculated using [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html). Here, a low score means good conservation.
<hr>
### Target 181
The set consists of 180 models.

#### Target description

|Type|Ligand|Receptor|
|---|---|---|
|Species|*SARS-CoV-2*|*Homo sapiens* (Human)|
|Name|Orf3a|HMOX1|
|Uniprot ID|[P0DTC3](https://www.uniprot.org/uniprot/P0DTC3)|[P09601](https://www.uniprot.org/uniprot/P09601)|
|Template|[6XDC](https://www.ebi.ac.uk/pdbe/entry/pdb/6xdc)|[1N3U](https://www.ebi.ac.uk/pdbe/entry/pdb/1n3u)|
|Description|Plays a role in virus egress via lysosomal trafficking (PubMed:33157038, PubMed:33422265).<br>Forms homotetrameric ion channels (viroporin) localized at endosomes and lysosomes, that may induce deacidification of lysosomes thereby allowing safe virion egress through lysosomal trafficking (By similarity) (PubMed:33157038, PubMed:33422265).<br>Also blocks formation of autolysosomes through binding and sequestering host TMUB1/HOPS on late endosomes. This prevents fusion of autophagosomes with lysosomes, disrupting autophagy and facilitating virus egress (PubMed:33422265).|Heme oxygenase cleaves the heme ring at the alpha methene bridge to form biliverdin. Biliverdin is subsequently converted to bilirubin by biliverdin reductase. Under physiological conditions, the activity of heme oxygenase is highest in the spleen, where senescent erythrocytes are sequestrated and destroyed. Exhibits cytoprotective effects since excess of free heme sensitizes cells to undergo apoptosis.|

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

You can find [here](/capri-covid/protein-descriptions/T181_csv.zip) the csv files where every residue is listed with its residue hits, contact variability and Rate4Site scores.<br>
You can also find [here](/capri-covid/contact-hits/T181_contact_hits.csv) the list of contact hits.

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

### Target 183
The set consists of 164 models.

#### Target description

|Type|Ligand|Receptor|
|---|---|---|
|Species|*SARS-CoV-2*|*Homo sapiens* (Human)|
|Name|Nsp8|EXOSC8|
|Uniprot ID|[P0DTD1](https://www.uniprot.org/uniprot/P0DTD1)|[Q96B26](https://www.uniprot.org/uniprot/Q96B26)|
|Template|[2NN6](https://www.ebi.ac.uk/pdbe/entry/pdb/2nn6)|[3UB0.D](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [2AHM.G](https://www.ebi.ac.uk/pdbe/entry/pdb/2ahm), [6XIP](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip)|
|Description|Multifunctional protein involved in the transcription and replication of viral RNAs. Contains the proteinases responsible for the cleavages of the polyprotein.|Non-catalytic component of the RNA exosome complex which has 3'->5' exoribonuclease activity and participates in a multitude of cellular RNA processing and degradation events. In the nucleus, the RNA exosome complex is involved in proper maturation of stable RNA species such as rRNA, snRNA and snoRNA, in the elimination of RNA processing by-products and non-coding 'pervasive' transcripts, such as antisense RNA species and promoter-upstream transcripts (PROMPTs), and of mRNAs with processing defects, thereby limiting or excluding their export to the cytoplasm.|

#### Viral protein analyses
##### Protein visualization
<center><img src="/images/covid/T183/T183_ligand.png" width="900"/></center>
Surface representation of the ligand __Nsp8__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T183/T183_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T183/T183_Nsp8_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Nsp8__ residues.

#### Human protein analyses
##### Protein visualization
<center><img src="/images/covid/T183/T183_receptor.png" width="900"/></center>
Surface representation of the ligand __EXOSC8__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T183/T183_receptor_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T183/T183_EXOSC8_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __EXOSC8__ residues.

You can find [here](/capri-covid/protein-descriptions/T183_csv.zip) the csv files where every residue is listed with its residue hits, contact variability and Rate4Site scores.<br>
You can also find [here](/capri-covid/contact-hits/T183_contact_hits.csv) the list of contact hits.

<hr>

### Target 184
The set consists of 191 models.

#### Target description

|Type|Ligand|Receptor|
|---|---|---|
|Species|*SARS-CoV-2*|*Homo sapiens* (Human)|
|Name|Nsp7|RhoA|
|Uniprot ID|[P0DTD1](https://www.uniprot.org/uniprot/P0DTD1)|[P61586](https://www.uniprot.org/uniprot/P61586)|
|Template|[6XIP.C](https://www.ebi.ac.uk/pdbe/entry/pdb/6xip), [3UB0.C](https://www.ebi.ac.uk/pdbe/entry/pdb/3ub0), [6M5I.A](https://www.ebi.ac.uk/pdbe/entry/pdb/6m5i)|[5C2K.A](https://www.ebi.ac.uk/pdbe/entry/pdb/5c2k), [4LHW.E](https://www.ebi.ac.uk/pdbe/entry/pdb/4lhw), [2J1L.A](https://www.ebi.ac.uk/pdbe/entry/pdb/2j1l)|
|Description|Multifunctional protein involved in the transcription and replication of viral RNAs. Contains the proteinases responsible for the cleavages of the polyprotein.|Small GTPase which cycles between an active GTP-bound and an inactive GDP-bound state. Mainly associated with cytoskeleton organization, in active state binds to a variety of effector proteins to regulate cellular responses such as cytoskeletal dynamics, cell migration and cell cycle|

#### Viral protein analyses
##### Protein visualization
<center><img src="/images/covid/T184/T184_ligand.png" width="900"/></center>
Surface representation of the ligand __Nsp7__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T184/T184_ligand_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T184/T184_Nsp7_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __Nsp7__ residues.

#### Human protein analyses
##### Protein visualization
<center><img src="/images/covid/T184/T184_receptor.png" width="900"/></center>
Surface representation of the ligand __RhoA__ protein __sequence conservation__ (__left__), coloring from orange (conserved) to teal (not conserved) and of the __residue hits__ (__right__), colored from red (high occurrence, capped at the 90th percentile for a better visualization) to blue (few occurrences). Green spheres are the center of mass of receptors for every model.

The PyMOL session where this image comes from can be downloaded [here](/capri-covid/PyMOL-sessions/T184/T184_receptor_stereo.pse)

##### Residue hit and conservation plot 

<center><img src="/images/covid/T184/T184_Rhoa_comparing_contacts_and_sequence_conservation.png" width="900"/></center>
Barplot representing the __residue hits__ (__blue__) and the __sequence conservation__ (__red__) with [Rate4Site](https://www.tau.ac.il/~itaymay/cp/rate4site.html) score where the lowest means the most conserved of the __RhoA__ residues.

You can find [here](/capri-covid/protein-descriptions/T184_csv.zip) the csv files where every residue is listed with its residue hits, contact variability and Rate4Site scores.<br>
You can also find [here](/capri-covid/contact-hits/T184_contact_hits.csv) the list of contact hits.

<hr>
