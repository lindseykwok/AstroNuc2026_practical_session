# AstroNuc 2026 Practical Session

Workshop materials for the AstroNuc 2026 practical session.

This repository contains Jupyter notebooks and helper code for working with models, profiles, and generating animations.

---

## 📥 How to Get the Materials

### Option 1 — Download as a ZIP (recommended if you're not familiar with Git)

1. Go to this repository on GitHub:
   `https://github.com/lindseykwok/AstroNuc2026_practical_session`

2. Click the green **Code** button → **Download ZIP**.

3. Unzip the folder.

4. Open a terminal and `cd` into the folder:
   ```bash
   cd AstroNuc2026_practical_session
   ```
5. Launch Jupyter:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```

### Option 2 — Clone with Git (recommended if you use Git)
  ```bash
  git clone https://github.com/lindseykwok/AstroNuc2026_practical_session.git
  cd AstroNuc2026_practical_session
  ```
To pull updates later:
  ```bash
  git pull
  ```
Then launch Jupyter:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```
## 🛠 Setup / Installation
We recommend using a fresh environment

### Conda (recommended)
  ```bash
  conda create -n astronuc2026 python=3.11
  conda activate astronuc2026
  pip install -r requirements.txt
  ```
### ✅ Quick sanity check
In python:
  ```python
  import numpy, matplotlib, pandas, scipy, astropy, imageio, tqdm
  print("Imports OK!")
  ```

## 📄 License
MIT License (see LICENSE)
