# Logistic Regression for Cat Classification

This is an educational project developed as part of the [Deep Learning Specialization](https://www.deeplearning.ai/) by **Andrew Ng**.

The goal is to implement a **binary image classifier** from scratch using **logistic regression**, structured with a **neural network mindset**. The model is trained to detect whether an image contains a **cat** or **not**.

---

## Dataset

The dataset is already included in this repository under the `datasets/` folder.  
It contains `.h5` files with labeled RGB images of cats and non-cats:

- `train_catvnoncat.h5`
- `test_catvnoncat.h5`

---

## How to run locally

### 1. Clone the repository

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the notebook
```bash
jupyter notebook
```

Then open cat-logistic-regression.ipynb (or the notebook file included in this repo).