### Link Prediction using Non-negative Matrix Factorization (NMF)

This repository provides a Python implementation of **link prediction** using **standard Non-negative Matrix Factorization (NMF)**. NMF is a dimensionality reduction technique that can uncover latent patterns in adjacency matrices for predicting missing or future links.

### 📊 Method Overview

- **NMF** is applied to the graph's adjacency matrix.
- Matrix factorization decomposes it into two low-rank non-negative matrices.
- The reconstructed matrix is used to infer potential links.

If you use this code in your research or projects, please cite the associated article:

Title [https://doi.org/10.1016/j.engappai.2024.108641]

For your convenience, here is a BibTeX entry for citation:

```
@article{mahmoodi2024enhancing,
  title={Enhancing link prediction through adversarial training in deep Nonnegative Matrix Factorization},
  author={Mahmoodi, Reza and Seyedi, Seyed Amjad and Abdollahpouri, Alireza and Tab, Fardin Akhlaghian},
  journal={Engineering Applications of Artificial Intelligence},
  volume={133},
  pages={108641},
  year={2024},
  publisher={Elsevier}
}
```
We sincerely appreciate proper attribution, as it supports ongoing research.
