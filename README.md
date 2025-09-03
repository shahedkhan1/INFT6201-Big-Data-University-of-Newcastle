🔧 Environment Setup (inft6201)
🖥️ macOS / Linux
## Option A — venv + pip
# 1. Create a virtual environment
python3 -m venv inft6201

# 2. Activate it
source inft6201/bin/activate

# 3. Upgrade pip
pip install --upgrade pip

# 4. Install project dependencies
pip install -r requirements.txt

# 5. (Optional) Register kernel for Jupyter
python -m ipykernel install --user --name=inft6201 --display-name "Python (inft6201)"


Start Jupyter:

jupyter lab   # or: jupyter notebook

## Option B — Conda
# 1. Create environment from environment.yml
conda env create -f environment.yml -n inft6201

# 2. Activate
conda activate inft6201

# 3. Register kernel
python -m ipykernel install --user --name=inft6201 --display-name "Python (inft6201)"


Run Jupyter:

jupyter lab

🖥️ Windows
Option A — venv + pip
# 1. Create a virtual environment
python -m venv inft6201

# 2. Activate it
inft6201\Scripts\Activate

# 3. Upgrade pip
pip install --upgrade pip

# 4. Install requirements
pip install -r requirements.txt

# 5. (Optional) Register kernel for Jupyter
python -m ipykernel install --user --name=inft6201 --display-name "Python (inft6201)"


Launch Jupyter:

jupyter lab

Option B — Conda
# 1. Create environment
conda env create -f environment.yml -n inft6201

# 2. Activate
conda activate inft6201

# 3. Register kernel
python -m ipykernel install --user --name=inft6201 --display-name "Python (inft6201)"


Run Jupyter:

jupyter lab
