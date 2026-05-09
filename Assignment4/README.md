Linear Regression, Regularization, and Constrained Optimization (Python Implementation)

---

## Setup Instructions

### 1. Create virtual environment

```bash
python3 -m venv venv
```

### 2. Activate environment

**macOS/Linux**

```bash
source venv/bin/activate
```

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

---

## Notebooks

### Assignment 4

```
Assignment4.ipynb
```

* XOR neural network
* Manual backpropagation
* Numerical gradient checking

### Regularization & Optimization

```
Regularization.ipynb
```

* Linear regression
* L1 and L2 regularization (penalty form)
* L1 and L2 norm constraints
* Projected gradient methods
* Comparison of penalty vs constraint approaches

---

## Libraries Used

Core:

* numpy
* matplotlib
* jupyter
* ipykernel

Optional:

* sympy (for symbolic/KKT solutions)

---

## Notes
* All optimization routines are implemented manually
* No automatic differentiation is used
* Both numerical and analytical approaches are explored
* L1 optimization is handled using subgradients or case analysis
* Constrained problems are solved using both:
* Lagrangian formulations
* KKT conditions

The emphasis is on understanding how different optimization strategies affect:

* convergence behavior
All optimization routines are implemented manually
No automatic differentiation is used
Both numerical and analytical approaches are explored
L1 optimization is handled using subgradients or case analysis
Constrained problems are solved using both:
Lagrangian formulations
KKT conditions

The emphasis is on understanding how different optimization strategies affect:

* convergence behavior
* stability
* solution geometry

---

## Author

Oskar Andersson

