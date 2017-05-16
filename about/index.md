---
layout: page 
tags: [Jekyll, CAPRI, Docking, Scoring, Complexes, Assemblies, Protein, Structure]
modified: 2014-08-08T20:53:07.573882-04:00
comments: false
image:
  feature: pages/banner_about.jpg
---
#### Table of contents
{:.no_toc}
* table of contents
{:toc}

<br>

### The challenge of charting the landscape of protein-protein complexes

Protein-protein interactions and protein assemblies, which often also include other macromolecular components, play a crucial role in all cellular processes. Their dysregulation or disruption often leads to disease. Characterizing these interactions and understanding the principles that governs them is therefore more than ever at the center stage of today’s molecular biology.  

Much of what we know about protein complexes is derived from data on the three-dimensional structures of these complexes determined by experimental methods. But the number of protein assemblies for which detailed structural information is available represents only a small fraction of the protein assemblies in the cell that can be detected by proteomics and other methods. On the other hand, structural biology has been very successful in mapping out the structural repertoire of individual proteins, many of which are the building blocs of larger complexes. 

Computational methods for modeling protein complexes by using available information on the structure of protein components and the fast growing data on protein sequences have been playing an very important role in populating the uncharted landscape of protein assemblies.  

<br>

### CAPRI and its role

CAPRI is a community-wide initiative inspired by CASP (Critical Assessment of protein Structure Prediction). It was established in 2001 with the goal of fueling progress in computational methods for modeling protein complexes.  It has done so by offering computational biologists the opportunity of testing their algorithms in blind predictions of experimentally determined 3D structures of protein complexes, the ‘targets’, provided to CAPRI prior to publication. 

CAPRI prediction Rounds are managed by the PDBe team at the European Molecular Biology Institute (EBI) [http://www.ebi.ac.uk/msd-srv/capri/](http://www.ebi.ac.uk/msd-srv/capri/). 

Due to the paucity of available protein complexes that can be used as targets, a CAPRI prediction Round is initiated each time a target (or a few targets) become available, and completed three to six weeks later. Targets are structures of protein [complexes/assemblies](#targets-and-challenges) offered in strict confidence to CAPRI by structural biologists prior to publication.  Registered participant are invited to predict the 3D structure of the target protein assembly starting from sequence information alone, or from the unbound structures when those are available (see [Prediction Experiment](#the-prediction-experiment)). A Round also includes a scoring challenge in which the correct assembly mode(s) must be identified out of a pool of decoys (incorrect models) (see [Scoring Experiment](#the-scoring-experiment)). Groups can participate in either or both challenges (as predictors and scorers).  

Upon completion of a Round, models submitted by all groups are evaluated against the target structure and ranked using a set of criteria established in close collaboration with the CAPRI community. The evaluation is likewise performed blindly, by concealing the identity of the participants submitting the models from the independent team that performs the assessment. To maintain strict confidentiality, only the assessment team has access to the target coordinates until their release by the authors.  

<br>

### The Prediction Experiment

__Crystallographers:__ Submit atomic coordinates for the target complex (prior to publication) -On-going basis “rolling”

__Predictors:__  Are provided with the sequence(s) of the protein subunits and asked to return 10 best atomic models of complex (previously unbound structures were provided) 
	            
__Assessors:__  Are given the 3D structure of the target, and those of the predicted models, establish correspondence. Identity of predictors is withheld from assessors.

<br>

### The Scoring Experiment

__Predictors:__ Are invited to submit (upload) their best 100 models

__Management:__ Shuffles and combines all models into a unique set, while keeping track of their origin internally.

__Predictors:__ Are given access to the shuffled set and asked to return 10 best models

__Assessors:__ Evaluate the models as in the prediction experiment.

<br>

### Targets and challenges

Since its inception, the focus of CAPRI has expanded significantly, to include the following types of targets and challenges:

1. __Complexes of proteins with other large molecules:__
* Protein homo- and hetero-oligomers
* Protein-peptide complexes
* Protein-nucleic acid (RNA, DNA) complexes
* Protein-sugar complexes
* Protein-Lipid complexes 
  

2. __Prediction of protein-protein binding affinities:__
* [Fleishman et al. (2011)](http://dx.doi.org/doi:10.1016/j.jmb.2011.09.031)
* [Moretti et al. (2013)](http://dx.doi.org/doi:10.1002/prot.24356)
  

3. __Modeling positions of interface water molecules:__
* [Lensink et al. (2014)](http://dx.doi.org/doi:10.1002/prot.24439)
* [Lensink et al. (2017)](http://dx.doi.org/doi:10.1002/prot.25215)

<br>

### Statistics

To this day 38 CAPRI prediction Rounds were completed with a total of 121 targets. Results for Rounds 1-35 were presented at 6 Assessment Meetings, held in 2002, 2004, 2007, 2009, 2013, and 2016 across Europe, and in Israel and six special issues about CAPRI were published in Proteins (See [Publications](/publications/)).

<figure>
    <img src="/images/capri/capri-meetings.png">
</figure>

CAPRI has recently teamed up with [CASP](http://www.predictioncenter.org) in running joint prediction experiments in the summers of 2014 (CASP11) and 2016 (CASP12), respectively. The prediction results of the CASP11-CAPRI prediction experiment are reported in the issue of Proteins dedicated to CASP (LINK: Lensink et al. 2016). These results highlight the increasing importance of integrating different modeling techniques with sequence and structural information to successfully model the protein assemblies.

<br>

### Modeling protein assemblies: an integrative approach.

Currently, for most CAPRI targets predictor groups challenged with, the assembly structure must be modeled starting from sequence information alone. This requires the integration of homology-based modeling (also called ‘template-based modeling’) of individual subunits, with docking calculations, or relying entirely on template-based modeling, when adequate templates for the entire complex ware available. This integration is increasingly facilitated by the availability of efficient and easy to use tools for various steps of the modeling process, which now also include a widening palette of docking and scoring procedures developed by the CAPRI community, and made available as software modules or via an increasing number of Web servers. 

The present [capri-docking.org](http://www.capri-docking.org) website aims at further facilitating access to these tools, so that groups participating in CAPRI and other groups developing methods can now focus on optimizing a specific aspect of the modeling pipeline and readily evaluate the impact on the prediction performance.

