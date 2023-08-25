# Protein Structure Extraction and Analysis

This Python code demonstrates the extraction of secondary structures from type II proteins and parsing operations using BioPython library.

## Description

This code reads protein data files in a specified directory, extracts amino acid sequences and secondary structure information, calculates frequencies and probabilities of amino acid types and secondary structure elements, and generates a summary report.

## Dependencies

- Python (>= 3.6)
- BioPython

## Usage

1. Clone this repository.
2. Install the required dependencies using: `pip install biopython`
3. Place your input protein data files in the 'dataset' directory.
4. Run the main script: `python protein_structure_analysis.py`
5. Processed data will be saved in the 'output' directory.

## Code Overview

- `generate_fasta`: Function to generate FASTA files from input files.
- `generate_ss`: Function to generate secondary structure (SS) files.
- `calculate_frequency`: Function to calculate amino acid and secondary structure frequencies.
- `calculate_structure_probability`: Function to calculate probabilities of amino acid structures.
- `calculate_binary_seq_probability`: Function to calculate probabilities of binary secondary structure sequences.
- `generate_summary`: Function to generate a summary of processed files and results.
- `amino_acid_dic`: Dictionary mapping three-letter amino acid codes to one-letter codes.
- `amino_structure`: Dictionary to store amino acid structure frequencies.
- `secondary_seq`: Dictionary to store secondary structure sequence frequencies.
- `gz_extract`: Function to extract and process gzipped files.

## Output
#Bioinformatics #ProteinAnalysis #BioPython

Processed data and summary files will be saved in the 'output' directory. The 'summary.txt' file will contain information about the processed files and calculated probabilities.

## Acknowledgements

This code was developed for educational purposes and is part of a project related to protein structure analysis.

