# Large Parsimony Project

## Bioinformatics group project

### Short description

All the code of this project is written in Python.

This project implements algorithms to solve the Large Parsimony problem in computational biology. The goal is to find the most parsimonious tree that explains the evolutionary relationships among a set of species based on their genetic sequences.

Artificially generated DNA sequences are also used in addition to the real data.
First, we solved the small parsimony problem. We used the UPGMA construction method together with the Needleman-Wunsch algorithm to obtain a progressive profile alignment of multiple sequences. Then, we computed the small parsimony score.

Then, we try to approach the large parsimony problem by finding the optimal phylogenic tree and score. For this purpose, we modified the small parsimony resulting tree via:

- the nearest neighbor intechange strategy and
- the pruning and regraphting strategy.

### Key Files

- **`project.ipynb`**: Jupyter Notebook that tells the story of the improvements of this project.
- **`[data].ref.fa`**: Data files containing DNA sequences (sequence of characters).
