# ML-Live-Class
Machine Learning Datasets implementation Step by step

# Commands Used
```bash
conda env list
mkdir utils
touch utils/__init__.py #to treat utility as a package
touch utils/model.py
touch utils/all_utils.py (keep all helper functions in all_utils folder)
from utils.model import class
touch requirements.txt
conda create -n mltest python==3.8 -y
conda activate mltest
pip freeze > requirements.txt
pip install -r requirements.txt
git add . && git commit -m "docstring updated" && git push origin main
git remote -v #shows the remote repository URL
git pull #to bring changes from remote repository and merge into local branch
git branch -M # to rename current branch
git checkout "committed id no" (to go to specific version)
pip install notebook #to install jupyter notebook in the vs code
jupyter notebook
cp sample\ notebook/demo.ipynb
import utils #to see utils as a pckage, just type python in the terminal
utils.__version__ #check utils package version
```