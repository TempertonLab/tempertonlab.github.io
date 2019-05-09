---
title: "Single-cell Amplified Genomes"
layout: single
author_profile: true
author: Ashley Bell
permalink: /research/ashley/sags
toc: true
toc_label: "Contents"
toc_icon: "cog"
---
## Intro
With the world’s oceans covering roughly 70% of the earth surface; its impact on the global carbon cycle, climate change, and acid-base biochemistry remains crucial to our understand of the natural world. Considering 90% of the ocean’s biomass comprise of marine microorganisms; their impact on global systems remain largely understudied. Marine microorganisms are critical in both energy and carbon cycles and are the foundation for marine life. However, studying these microorganisms remains challenging with only a small fraction being culturable for _in situ_ experimentation. Alternative study methods include obtaining genomes via metagenomics studies and Single-cell Amplified Genomes (SAGs). Both of these methods have advantages and drawbacks with marine metagenomes being highly complex to analyse and SAGs suffering from both low completeness and bias. This study aims to explore both approaches and provide improvements to aid analysis.

## Single-cell Amplified Genomes
Single-cell Amplified Genomes are genomes sequenced from single cells via [multiple-displacement amplification technology](https://en.wikipedia.org/wiki/Multiple_displacement_amplification). This enables genomic tools to be used for both cells that can't be isolated, and for studying population genetics at a single-cell level.

## SAR11 and its importance
SAGs are a valuable tool for studying [SAR11](https://microbewiki.kenyon.edu/index.php/Pelagibacterales_(SAR11) , a marine organism that dominates the ocean's microbial biosphere. SAR11 is somewhat more difficult to culture, with long doubling times and needing to grow in a nutrient "broth" akin to its natural habitat - the open oceans. SAGs allow us to investigate how genomic differences translate into niche-differentiation, i.e. how different types of SAR11 occupy different parts of the oceans.

## 451 SAR11 SAGs 
451 SAR11 SAGs were sequenced using short read Illumina technology, assembled and displayed here. With a large amount of assemblies, genomic content was compared between organisms to look at differing gene content, phylogenetics and lysogenic viral content. Differing nucleotide content was performed via [Average Nuclotide Identitiy (ANI)](https://img.jgi.doe.gov/docs/docs/ANI.pdf) where nuclotide content in protein coding regions are compared. Phylogentics was done via [Multiple Sequence Alignment (MSA)](https://en.wikipedia.org/wiki/Multiple_sequence_alignment) of protein coding regions as well as comparing 16S regions. [Viral signatures](/research/ashley/metagenomics/#global-abundance) were extracted from SAGs and its coding regions analysed. 

## Phylogenetic Tree
Below contains the 16S rRNA phylogentic tree of SAR11 SAGs.

![](../../../assets/images/Sar11_tree.png){:height="500%" width="500%"}


## Average Nuclotide Identity
ANI is the measurement of how different nuclotide composition of coding regions differ from each other. All SAR11 SAGs ANI was calculated between each other and visualised as a heatmap in the link below. Darker squares indicate a higher ANI or closer genetic identity to each other. Clusters of colour suggest differing populations. 

[ANI between SAGs](/research/ashley/sags/ani)
