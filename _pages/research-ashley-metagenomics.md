---
title: "Marine Metagenomics"
layout: single
author_profile: true
author: Ashley Bell
permalink: /research/ashley/metagenomics
toc: true
toc_label: "Contents"
toc_icon: "cog"
---
## Intro
With the world’s oceans covering roughly 70% of the earth surface; its impact on the global carbon cycle, climate change, and acid-base biochemistry remains crucial to our understand of the natural world. Considering 90% of the ocean’s biomass comprise of marine microorganisms; their impact on global systems remain largely understudied. Marine microorganisms are critical in the energy cycle and are the foundation for marine life. However, studying these microorganisms remains challenging with a small fraction being culturable for in situ experimentation. Alternative study methods include obtaining genomes via metagenomics studies and Single-cell Amplified Genomes. Both of these methods have advantages and drawbacks with marine metagenomes being highly complex to analyse and SAGs suffering from both low coverage and bias. This study aims to explore both approaches and provide improvements to aid analysis.

## Metagenomics
Metagenomics is the study of any genetic content recovered from an environmetal sample, usually used to describe population dynamics and gene content. Normally, organisms are isolate, cultured and DNA harvested for sequencing. With metagenomics, samples are collected are sequencing without isolation of any specific organism. This allows for entire populations to be captured within a sample. Various studies can be perform like extraction and sequencing of 16S sequences for population profiling or any other gene for that matter. Metagenomes can also be assembled to produce multiple whole genomes of organisms using specalised computer algorithims. However, increasing numbers of simularily related organisms within a sample pose higher conplexity and challenges to obtain whole genomes sequences.  

## Visualisation
A metagenomic assembly - organisms whole genomes are assembled using metagenomic assembliers are often poorly assemblied due to the large amount of simular genetic code present. Here contigs - sequences of genetic code that align together are plotted on a scatter plot via a t-SNE technique for visualisation. Colours are overlayed over contigs based on their phylogentic content. 

![](../../../assets/images/metagenomics_tSNE.png){:height="500%" width="500%"}


## Global Abundance
With metagenomes, all genetic components within a sample are sequenced, allowing for a snapshot of a microbial population with a certain space and time. Mapping or comparing an exisiting isolate to a metagenome can reveal the abundance of that isolate with that metagenome and therefore that space and time. This provides a mechanism to predict sample presence absence within a large timeframe and spatial zone, without the need to take new genetic samples. Below is an example of [SAR11 Single-cell Amplifed Genome](/research/ashley/sags) abundance, a dominant marine microorganism at differing times and depths at the Bermuda Atlantic Time Series, and its isolate corrisponding bacteriophage.

[Heatmap BATS](/research/ashley/metagenomics/bats-heatmap)
