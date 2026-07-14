# IPBR Project
Welcome to my IPBR protein identifier project!
This Jupyter Notebook, GeneSeq, uses Python to transcribe and then translate a gene sequence, then runs the amino acid sequence with an NCBI BLAST search in order to identify what protein it is.


## Project Overview
1. Loading sequence data into Jupyter Notebook: Reads a DNA Sequence from a .txt local file path.
2. Transcription: Converts the DNA sequence into an RNA sequence.
3. Translation: Process the RNA sequence into an amino acid string using a codon chart dictionary.
4. Identification of the protein: Use the Biopython library to run an online blastp search of the amino acid string against the NCBI database.

## Requirements
To run this notebook, you will need Python as well as the following library installed:
* Biopython: For easier biological computation and NCBI BLAST access.

## How to Run This Project:
1. Clone this project.
2. Install Biopython - 'pip install biopython'
3. Input your gene sequence file as a .txt file and make sure to add in your own path for the file, whether using the Mystery_Gene.txt or your own gene sequence.
4. Run all cells sequentially. The last 3 cells will take some time as executing a BLAST search can take some time. The final cell will output the tob BLAST match, identifying the likely organism and protein.
