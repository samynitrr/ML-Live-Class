# ML-Live-Class
Machine Learning Datasets implementation Step by step

# Commands Used
1. conda env list
2. mkdir utils
3. touch utils/__init__.py #to treat utility as a package
4. touch utils/model.py
5. touch utils/all_utils.py (keep all helper functions in all_utils folder)
6. from utils.model import class
7. touch requirements.txt
8. conda create -n mltest python==3.8 -y
9. conda activate mltest
10. pip freeze > requirements.txt
11. pip install -r requirements.txt
12. git add . && git commit -m "docstring updated" && git push origin main
13. git remote -v #shows the remote repository URL
14. git pull #to bring changes from remote repository and merge into local branch
15. git branch -M # to rename current branch
16. git checkout "committed id no" (to go to specific version)
17. pip install notebook #to install jupyter notebook in the vs code
18. jupyter notebook
19. cp sample\ notebook/demo.ipynb
20. import utils #to see utils as a pckage, just type python in the terminal
21. utils.__version__ #check utils package version