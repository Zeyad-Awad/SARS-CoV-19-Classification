# SARS-CoV-2 Variants Analysis: Omicron and Delta

## Description
This repository contains code for analyzing the genetic sequences of the Omicron and Delta variants of the SARS-CoV-2 virus. The analysis includes data collection, preprocessing, computation of Chaos Game Representations (CGRs), computation of pairwise distances, Multidimensional Scaling (MDS), and visualization.

## Setup

### Import Libraries
The following libraries are used for the analysis:
<ul>
<li>NumPy</li>
<li>scikit-learn (for pairwise distances and MDS)</li>
<li>Matplotlib (for visualization)</li>
</ul>

## Define Functions
Several utility functions are defined to facilitate data processing, including reading FASTA files, cleaning sequences, writing FASTA files, computing CGRs, and performing MDS.

## Data Collection and Preprocessing

Data files for the Omicron and Delta variants are read and preprocessed. The sequences are cleaned and organized for further analysis.

## Computing CGRs - Chaos Game Representations

Chaos Game Representations are computed for both Omicron and Delta variant sequences. CGRs provide insights into the genomic structures of the variants.

## Computing Pairwise Distances

Pairwise distances are calculated using Manhattan distance metric. These distances serve as a measure of dissimilarity between sequences.

## MDS - Multidimensional Scaling

Multidimensional Scaling is performed to visualize the high-dimensional data in three dimensions. MDS helps in understanding the relationships and structures within the data.

## Visualization

The results of MDS are visualized in a three-dimensional scatter plot, with each point representing a sequence. Both Delta and Omicron variants are plotted for comparison.