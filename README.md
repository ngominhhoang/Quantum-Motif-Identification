# QOMIC: Quantum optimization for motif identification
## Abstract
Network motif identification problem aims to find topological patterns in biological networks. Identifying non-overlapping motifs is a computationally challenging problem using classical computers. Quantum computers enable solving high complexity problems which do not scale using classical computers. In this paper, we develop the first quantum solution, called QOMIC (Quantum Optimization for Motif IdentifiCation), to the motif identification problem. QOMIC transforms the motif identification problem using a integer model, which serves as the foundation to develop our quantum solution. We develop and implement the quantum circuit to find motif locations in the given network using this model. Our experiments demonstrate that QOMIC outperforms the existing solutions developed for the classical computer, in term of motif counts. We also observe that QOMIC can efficiently find motifs in human regulatory networks associated with five neurodegenerative diseases: Alzheimers, Parkinsons, Huntingtons, Amyotrophic Lateral Sclerosis (ALS), and Motor Neurone Disease (MND).
## How to cite
Please cite the paper corresponding to this repository:
```
```
## How to run
- Generate synthetic datasets by Generate_synthetic.ipynb
- Construct real datasets by Generate_real.ipynb
- Run QOMIC with synthetic datasets by QOMIC_synthetic_X.ipynb with X is the corresponding motif pattern.
- Run QOMIC with real datasets by QOMIC_real_X.ipynb with X is the corresponding motif pattern.
- Reconstruct experimental synthetic results by plot/synthetic/plot_X_results.ipynb with X is the corresponding motif pattern.
- Reconstruct experimental real results by plot/real/plot_real_datasets.ipynb.
