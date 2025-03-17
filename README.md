# Trygve draft

# Spinal Cord Cell Type Atlas: Annotation Coordination Hub

This repository is a central resource for annotators collaborating on a cross-species consensus atlas of spinal cord cell types. Our collaborative goal is to integrate molecular, anatomical, and developmental insights to refine spinal cord cell type taxonomies in human, macaque, and mouse. 

### Goals of the Annotation Effort:
- **Establish** a consensus cell type nomenclature across species.
- **Identify** robust marker genes (including transcription factors and neurotransmitters) and assess conservation across species.
- **Clarify** neuronal diversity through anatomical and developmental characterization.
- **Reorganize** and refine clusters into biologically meaningful hierarchical groups.


### How to Participate:
- **Annotate draft cross-species cell types** based on snRNA-seq in the [Cell Annotation Platform (CAP)](URL).
- **Deadline April 16** when a virtual meeting will be held to discuss annotation progress.


### Additional Resources:
- **[CAP Orientation Videos](https://www.youtube.com/playlist?list=PLKRocgU6P8sIXJKtoyhBtOm38sMH1Z7gq)** led by Evan Biederstedt
- **[Cell type metadata](URL)** including marker genes and anatomical distributions.
- **[Spatial distributions](URL)** of consensus cell types in mouse spinal cord.

---

### Coordination Team:
Trygve Bakken, Nelson Johansen, Matthew Schmitz, Yuan Gao, Zizhen Yao, Cindy van Velthoven (Allen Institute for Brain Science)

---



# Move to separate page for BICAN collaborators only

## Data

Sequencing data is in AIT (LINK) .h5ad format. ... EXPLAIN MORE ...

### RNA-seq 

Stored in s3 here ... FILL IN ...

* Macaque: `manuscript/RNA/Macaque_harmonized_20250224.h5ad`
* Human: `manuscript/RNA/Human_harmonized_20250224.h5ad`
* Mouse: `manuscript/RNA/Mouse_harmonized_20250224.h5ad`
* ConsensusTaxonomy: `manuscript/RNA/AIBS_SpC_consensus_taxonomy_harmonized_20250224.h5ad`
* AllStudyIntegration: ``
* External: `external/`
* External (Re-Aligned): `external-realigned/`

---






## Consensus Cross-species Spinal Cord Atlas

To create a consensus atlas and nomenclature of spinal cord across species, we have performed 10X Multiome and RNA-seq across the entire Macaque and Mouse cord as well as Human cervical and lumbar segments.

## Cell Annotation Platform (CAP)

![image](https://github.com/user-attachments/assets/10a6ade5-99c4-4fa4-b850-0e76ba879ee8)


To facilitate collaborative annotation with members of the spinal cord community we are using the Cell Annotation Platform ([CAP](https://celltype.info/)) to put our work into the hands of spinal cord researchers to provide feedback, thoughts and expert information about the consensus nomeclature system being proposed. 

We have provided the Consensus Cross-species Taxonomy as an integrated object containing nuclei/cells from Human, Macaque and Mouse as a complete Atlas and various sub-groupings of taxonomic terms to provide a higher-resolution view for each Class of cell types.

* [Cross-species Spinal Cord Atlas](https://celltype.info/project/598/dataset/1364)
   * [Cross-species Spinal Cord: GABAergic](https://celltype.info/project/598/dataset/1361)
   * [Cross-species Spinal Cord: Glutamatergic](https://celltype.info/project/598/dataset/1362)
   * [Cross-species Spinal Cord: Cholinergic](https://celltype.info/project/598/dataset/1360)
   * [Cross-species Spinal Cord: Non-Neurons](https://celltype.info/project/598/dataset/1363)

The main [Cell Annotation Platform project](https://celltype.info/project/598) requires an invite to access. If you are interested please reach out to either Nelson Johansen (nelson.johansen@alleninstitute.org) or Trygve Bakken (trygveb@alleninstitute.org).

## Allen Institute Taxonomy (AIT) data files

Single-nuclei RNA sequencing data is being hosted in [Allen Institute Taxonomy (AIT)](https://github.com/AllenInstitute/AllenInstituteTaxonomy) AnnData format on s3 in the exact format as presented on Cell Annotation Platform (CAP). Each link below is a public s3 URL to download the respective dataset.

* [Cross-species Spinal Cord Atlas](https://released-taxonomies-802451596237-us-west-2.s3.us-west-2.amazonaws.com/CAP/SpinalCord/AIBS_SpC_Consensus_AIT_CAP.h5ad) (12GB)
   * [Cross-species Spinal Cord: GABAergic](https://released-taxonomies-802451596237-us-west-2.s3.us-west-2.amazonaws.com/CAP/SpinalCord/AIBS_SpC_Consensus_AIT_CAP_subset_GABAergic.h5ad)
   * [Cross-species Spinal Cord: Glutamatergic](https://released-taxonomies-802451596237-us-west-2.s3.us-west-2.amazonaws.com/CAP/SpinalCord/AIBS_SpC_Consensus_AIT_CAP_subset_Glutamatergic.h5ad)
   * [Cross-species Spinal Cord: Cholinergic](https://released-taxonomies-802451596237-us-west-2.s3.us-west-2.amazonaws.com/CAP/SpinalCord/AIBS_SpC_Consensus_AIT_CAP_subset_Cholinergic.h5ad)
   * [Cross-species Spinal Cord: Non-Neurons](https://released-taxonomies-802451596237-us-west-2.s3.us-west-2.amazonaws.com/CAP/SpinalCord/AIBS_SpC_Consensus_AIT_CAP_subset_Non-Neurons.h5ad)

## Analysis

* [Conserved marker gene table](S3_LINK)
