# Companion code for the paper "A General Framework for Block-Sparse Recovery Conditions via Weighted Mixed and Operator Norms"

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fardinafdideh/block-sparse-recovery/blob/main/block_sparse_recovery.ipynb)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX) 

**Authors:** Fardin Afdideh, Ronald Phlypo, Christian Jutten

This repository contains the companion Python/Jupyter notebook to reproduce the numerical experiments presented in the manuscript *"A General Framework for Block-Sparse Recovery Conditions via Weighted Mixed and Operator Norms"*. 

The code computes the attainable sparsity levels that govern the recovery guarantees and thresholds derived in the paper.

## 📊 Numerical Experiments Reproduced

The notebook (`block_sparse_recovery.ipynb`) reproduces:

* **Experiment I (Figure 2):** Evaluates the impact of dictionary type (regular vs. intra-block orthonormal), block length ($d$), and the six tractable operator norms $(q,p)$ on the attainable Sparsity Level (SL). It compares our SLs against the established block-wise and element-wise SLs.
* **Experiment II (Figure 3):** Evaluates the attainable SL as a function of intra-block sub-coherence, comparing the proposed SLs against the existing block-sparse SLs. 

## 🚀 How to Run 

Because this code relies entirely on standard scientific libraries (`numpy`, `matplotlib`), it requires zero local setup. 

1. Click the **"Open in Colab"** badge at the top of this README.
2. Once the notebook opens in Google Colab, click `Runtime` > `Run all` from the top menu.
3. The simulation will run in a few minutes, and the generated figures will be displayed and available for download in the Colab file browser.

## 📖 Citation
```bibtex
@article{afdideh_blocksparse_2026,
  title={A General Framework for Block-Sparse Recovery Conditions via Weighted Mixed and Operator Norms},
  author={Afdideh, Fardin and Phlypo, Ronald and Jutten, Christian},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2026}
}
