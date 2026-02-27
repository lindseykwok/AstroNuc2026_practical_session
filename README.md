# AstroNuc 2026 Practical Session

Workshop materials for the AstroNuc 2026 practical session.

This repository contains interactive Jupyter notebooks and supporting data, models, and images. The practical session slides are also available.

---

## 📥 Step 1 - Get the Materials

### Option 1 — Download as a ZIP (no Git required)

1. Go to:
   `https://github.com/lindseykwok/AstroNuc2026_practical_session`

2. Click the green **Code** button → **Download ZIP**.

3. Unzip the folder.

You should now see a folder named something like:
   ```code
   AstroNuc2026_practical_session-main
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

## 🛠 Step 2 - Create the Environment
We recommend using a fresh environment

### Conda (recommended)
  ```bash
  conda create -n astronuc2026 python=3.11
  conda activate astronuc2026
  ```

Now navigate into the repository folder.
If you downloaded the ZIP:
   ```bash
  cd AstroNuc2026_practical_session-main
   ```
If you cloned with Git:
   ```bash
  cd AstroNuc2026_practical_session
   ```

Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Step 3 - Launch Jupyter

Make sure you are in the conda environment (`code conda activate astronuc2026`) before launching Jupyter:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```


### ✅ Quick sanity check
In python:
  ```python
  import numpy, matplotlib, pandas, scipy, astropy, imageio, tqdm
  print("Imports OK!")
  ```

## 📄 License
MIT License (see LICENSE)
