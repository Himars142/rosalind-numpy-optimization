# NumPy-Optimized Rosalind Solutions

This repository demonstrates how to significantly accelerate Rosalind bioinformatics problems by refactoring vanilla Python solutions using **NumPy** vectorization, broadcasting, and efficient array operations. Each notebook compares a clean **vanilla Python** solution with its **NumPy-optimized** counterpart, highlighting both correctness and runtime performance.

## Notebooks

| Notebook                                                                                                         | Rosalind Problem                                                                        | Speedup                   |
| ---------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------- |
| [`comparing_spectra_with_the_spectral_convolution.ipynb`](comparing_spectra_with_the_spectral_convolution.ipynb) | [Comparing Spectra with the Spectral Convolution](https://rosalind.info/problems/conv/) | **~21×**                  |
| [`counting_point_mutations.ipynb`](counting_point_mutations.ipynb)                                               | [Counting Point Mutations](https://rosalind.info/problems/hamm/)                        | **~7×**                   |
| [`inferring_protein_from_spectrum.ipynb`](inferring_protein_from_spectrum.ipynb)                                 | [Inferring Protein from Spectrum](https://rosalind.info/problems/spec/)                 | **~2×**                   |
| [`introduction_to_random_strings.ipynb`](introduction_to_random_strings.ipynb)                                   | [Introduction to Random Strings](https://rosalind.info/problems/prob/)                  | **~2×** (on large input)  |
| [`sex_linked_inheritance.ipynb`](sex_linked_inheritance.ipynb)                                                   | [Sex-Linked Inheritance](https://rosalind.info/problems/sexl/)                          | **~15%** (on large input) |

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Himars142/rosalind-numpy-optimization.git
   cd rosalind-numpy-optimization.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## All Rosalind Solutions

My complete collection of solved Rosalind problems (vanilla Python) is available in the main repository:

→ **[Rosalind-Solutions](https://github.com/Himars142/Rosalind-Solutions)**
