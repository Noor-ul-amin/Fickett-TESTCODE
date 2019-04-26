# Fickett TESTCODE (Fickett Score)
The script calculates Fickett TESTCODE (Fickett Score) of given single stranded RNA.
# Requirements
The script requires Biopython to read fasta file.

To install Biopython from pip
```
pip install biopython
```
to install biopython form conda
```
conda install -c anaconda biopython
```

# Protein-coding and non-coding Decision 
Testcode ≤ 0.74 then the Prediction is NONCODING. 
Testcode 0.74 ≥ and ≤ 0.95 then the Prediction is NO OPINION.
Testcode ≥ 0.95 then the Prediction is CODING.

# Reference
Fickett, James W. "Recognition of protein coding regions in DNA sequences." Nucleic acids research 10.17 (1982): 5303-5318.
