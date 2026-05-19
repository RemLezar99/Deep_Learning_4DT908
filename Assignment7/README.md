# # Variational Inference - Spam Detection

# Bayesian Inference Assignments

This repository contains two notebooks related to Bayesian inference.

The first notebook introduces the foundations of Bayes' theorem using both discrete and continuous examples. It implements likelihoods, priors, evidence, and posterior distributions, and shows how the evidence can be computed either by summation in the discrete case or by integration in the continuous case.

The second notebook applies variational inference to spam detection using the UCI SMS Spam Collection dataset. Instead of training a single fixed classifier, the model learns a variational distribution over the parameters and evaluates posterior predictive uncertainty and calibration.

---

## Notebooks

Foundations of Bayes' Theorem.ipynb
Variational Inference - Spam Detection.ipynb


## Setup Instructions

### 1. Create a virtual environment

```bash
python -m venv venv
**Windows**

```powershell
venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```
### Notes

Run each notebook from top to bottom after restarting the kernel to ensure that all variables and outputs are generated correctly. The notebook expect the file '2048d_sms_spam_albert-xlarge-v2.npz' to be located in the 'data' folder.
---
## Author

Oskar Andersson

