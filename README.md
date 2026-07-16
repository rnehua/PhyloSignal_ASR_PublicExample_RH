# Phylogenetic Signal & Ancestral State Reconstruction

This repository demonstrates a comparative phylogenetics workflow based on methods I developed during my undergraduate research on yeast morphology and evolution at Vanderbilt University.

To avoid sharing unpublished research data, the analyses are performed using the public **BritishBirds** dataset included in the **caper** R package.

---

## Methods Demonstrated

- Data preprocessing and quality control
- Phylogenetic tree and trait-data matching
- Fritz & Purvis' D statistic
- Transition-rate model fitting (ER, SYM, ARD)
- Model comparison using AIC/AICc
- Marginal ancestral state reconstruction using **corHMM**
- Publication-quality phylogenetic visualization

---

## Skills

- R
- phytools
- corHMM
- ape
- caper
- comparative phylogenetics
- evolutionary biology
- ancestral state reconstruction

---

## Example Output

### Marginal ancestral state reconstruction

<p align="center">
<img src="figures/asrTree.png" width="700">
</p>

---

### Estimated transition-rate model

<p align="center">
<img src="figures/transitionModelsARD.png" width="500">
</p>

---

## Repository Contents

```
README.md
phylogenetic_signal_and_asr.Rmd
phylogenetic_signal_and_asr.html
figures/
```

---

## Background

This repository is intended as a public demonstration of the analytical workflow used during my undergraduate evolutionary biology research.

The original project investigated the macroevolution of colony morphology across more than 1,000 yeast species using phylogenetic comparative methods and machine learning. Since those data remain associated with ongoing research, this repository recreates the computational workflow using a fully public dataset.
