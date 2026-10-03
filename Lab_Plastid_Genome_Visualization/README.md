# Visualize Plastid Genome Structure

## Student Information

* **Name:** BATIGULAO, JEHIAH BLESS T. 

* **Course/Section:** BS BIOLOGY LEVEL III

* **Chosen Genus:** *Allium*

* **Selected Species:** *Allium sativum* L.

* **Common Name:** Garlic

## Genome Information

* **NCBI Accession:** NC_031829.1

* **Genome Type:** Complete chloroplast genome

* **Genome Length:** 153,172 bp

* **Topology:** Circular

* **Source:** [NCBI Nucleotide - NC_031829.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_031829.1)

* **Date Retrieved:** September 30, 2026

## Objective

This activity aimed to visualize the organization of the *Allium sativum* plastid genome using OrganellarGenomeDRAW (OGDRAW). The map was used to examine the major structural regions, gene distribution, transcription directions, and GC content.

## Data and Software

The annotated GenBank file was downloaded from NCBI using accession NC_031829.1. The file was uploaded to OGDRAW to generate a circular plastid genome map.

**Software:** OGDRAW (OrganellarGenomeDRAW)

**Settings used:**

Mode: Standard

Genome map type: Circular

Sequence source: Plastid

GC content graph: Enabled

Direction of transcription: Enabled

Full legend: Enabled

Intron-containing gene labels: Enabled, using an asterisk (*)

Output format: PNG

Resolution: Superfine

## Plastid Genome Map

![Allium sativum plastid genome map](figures/ogdraw_job_215491efefcc4aa22344fc5666a6cc61-outfile.pdf)

## Main Structural Features

The *Allium sativum* chloroplast genome is 153,172 bp long and has a circular organization. Its major regions include the Large Single-Copy (LSC) region, Small Single-Copy (SSC) region, and two Inverted Repeat regions (IRa and IRb). The genome contains protein-coding genes, transfer RNA (tRNA) genes, and ribosomal RNA (rRNA) genes involved in photosynthesis and plastid gene expression.

The map also illustrates gene orientation and the distribution of genes around the genome. The GC content graph shows variation in nucleotide composition along the sequence. The annotated genome provides additional information for identifying genes and other features.

## Galaxy Sequence Statistics

| Statistic                  |     Result |
| -------------------------- | ---------: |
| Genome length              | 153,172 bp |
| Number of sequence records |          1 |
| GC content                 |     36.68% |
| Ambiguous N bases          |          0 |
| Number of gaps             |          0 |

## Files

* Annotated GenBank input: `data/Allium_sativum_NC_031829.1.gb`

* Plastid genome map: `Lab_Plastid_Genome_Visualization/figures/ogdraw_job_215491efefcc4aa22344fc5666a6cc61-outfile.pdf` 
* Written answers: `answers/README.md`



## References

1. National Center for Biotechnology Information. *Allium sativum* chloroplast, complete genome. RefSeq accession NC_031829.1. https://www.ncbi.nlm.nih.gov/nuccore/NC_031829.1

2. Greiner, S., Lehwark, P., & Bock, R. (2019). OrganellarGenomeDRAW (OGDRAW) version 1.3.1: Expanded toolkit for the graphical visualization of organellar genomes. *Nucleic Acids Research, 47*(W1), W59–W64. https://doi.org/10.1093/nar/gkz238

3. OGDRAW - OrganellarGenomeDRAW. CHLOROBOX, Max Planck Institute of Molecular Plant Physiology. https://chlorobox.mpimp-golm.mpg.de/OGDraw.html

