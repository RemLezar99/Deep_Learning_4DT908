# XOR Neural Network with Manual Backpropagation (Python Implementation)

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

Then open:

```
Assignment3.ipynb
```

## Libraries Used

* numpy
* matplotlib

Optional (bonus verification only):

* jax (for autodiff gradient verification)

## Notes

* No automatic differentiation is used during training.
* Gradients are derived and implemented manually
* A numerical gradient check is included for validation.
* Bonus: Autodiff (e.g., JAX) can be used to verify gradients, but not for training.
* The model is kept as small as possible while still solving XOR.

## Author

Oskar Andersson
