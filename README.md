# Fickett TESTCODE (Fickett Score)
The script calculates Fickett TESTCODE (Fickett Score) of given single stranded RNA.
# Requirements
The script requires Biopython to read fasta file. 

# Decision 
Testcode ≤ 0.74 then the Prediction is that the sequence is NONCODING. 
Testcode 0.74 ≥ and ≤ 0.95 then the Prediction is NO OPINION.
Testcode ≥ 0.95 then the Prediction is CODING.

Original publication: Fickett, James W. "Recognition of protein coding regions in DNA sequences." Nucleic acids research 10.17 (1982): 5303-5318.
