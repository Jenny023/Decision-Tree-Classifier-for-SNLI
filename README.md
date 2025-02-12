# Decision-Tree-Classifier-for-SNLI
This page contains the adjusted code of Dr. L. Abzianidze, written by group 9 of the Logic and Language Course 2024-2025.

This project explores feature-based approaches for Natural Language Inference (NLI), by using the Scikit-Learn decision tree classifier. 
Two types of features, smart and shallow, are extracted in various methods. Some make use of spaCy and WordNet among other Python libraries.

### Installation & Set-Up
The code is written in a Jupyter Notebook using Google Colab.

*Necessary datasets*
- SNLI

*Main packages*
- Assigntools LoLa (to download and read the SNLI dataset)
- SpaCy (to annotate sentences with POS tagging, dependency parcsing etc.)
- NLTK WordNet (library which captures conceptual word meaning via associations)
- VADER (sentiment analysis tool)
- SciKit Learn (Decision Tree model)

*Additional supporting packages*
- Numpy
- NLTK Tree
- MatplotLib
- tqdm
- pandas
- seaborn

### Notebook Stucture
1. Reading data
      - SNLI dataset import
      - Datasplit

2. Processing with spaCy

3. Create Features 
      - Shallow feature functions
      - Smart features functions
      - Combining feature functions (sentence-level and problem-level)
   
4. Training and Evaluation
      - First evaluation on pre-dev set
      - Finding optimal hyperparameters with SNLI dev set
      - Final evaluation on SNLI test set
   
5. Analysis
      - Smart feature effectiveness
      - Shallow feature effectiveness
      - Displaying decision tree splits

### How to run the Notebook
The Notebook is one file containing all the necessary links and downloads to run the code. To make it work, it is needed to start at the beginning since files and functions are used in an accumulative way.

### References
Code used from Dr. L. Abzianidze (l.abzianidze@uu.nl).
Adjusted by:
- A. Leendertse (a.leendertse@students.uu.nl)
- J.S. Batchelor (j.s.batchelor@students.uu.nl)

For more information about the Stanford Natural Language Inference (SNLI) dataset: https://nlp.stanford.edu/projects/snli/ 

