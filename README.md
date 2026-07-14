# IPBR_project
Welcome to my IPBR protein identifier project!
This Jupyter Notebook, GeneSeq, uses Python to transcribe and then translate a gene sequence, then runs the amino acid sequence with an NCBI BLAST search in order to identify what protein it is.


## Project Overview
1. Loading sequence data into Jupyter Notebook: Reads a DNA Sequence from a .txt local file path.
2. Transcription: Converts the DNA sequence into an RNA sequence.
3. Translation: Process the RNA sequence into an amino acid string using a codon chart dictionary.
4. Identification of the protein: Use the Biopython library to run an online blastp search of the amino acid string against the NCBI database.

## Requirements
To run this notebook, you will need Python as well as the following library installed:
Biopython: For easier biological computation and NCBI BLAST access.

