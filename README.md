# Decision-Tree-Classifier-for-SNLI
This page contains the adjusted code of Dr. L. Abzianidze, written by group 9 of the Logic and Language Course 2024-2025 (Aniek, Anne and Jennifer)

This project explores feature-based approaches for Natural Language Inference (NLI), by using the Scikit-Learn decision tree classifier. 
Two types of features, smart and shallow, are extracted in various methods. Some make use of spaCy and WordNet among other Python libraries.

### Installation & Set-Up
The code is written in a Jupyter Notebook using Google Colab.

*Necessary datasets*
- SNLI

*Necessary packages*
- SpaCy # omschrijven waarvoor gebruikt
- WordNet
- SciKit Learn

Additional supporting packages:
- Numpy
- MatplotLib
- tqdm

### Stucture
1. Reading data (#import-SNLI–splitting-data
  - SNLI dataset import
  - Datasplit

    
(1) [Processing with spaCy](#obtain-spaCydocs)
(2) [Create Features](#feature-extraction--feature-combination)
Shallow feature functions
Smart features functions
Combining feature functions (sentence-level and problem-level)
⿤ [Training and Evaluation](#model-training--evaluation) 
First evaluation on pre-dev set
Finding optimal hyperparameters with SNLI dev set
Final evaluation on SNLI test set
⿥ [Analysis](#analysis--interpretation) 
Smart feature effectiveness
Shallow feature effectiveness
Displaying decision tree splits

### How to run the Notebook
The Notebook is one file containing all the necessary links and downloads to run the code. To make it work, it is needed to start at the beginning.

### References
Code used from Dr. L. Abzianidze (l.abzianidze@uu.nl).
Adjusted by:
- Anne Leendertse (a.leendertse@students.uu.nl)
- Jennifer Batchelor (j.s.batchelor@students.uu.nl)

For more information about the Stanford Natural Language Inference (SNLI) dataset: https://nlp.stanford.edu/projects/snli/ 

