# ML_live_class
machine learning datasets implementation

# commands used
conda env list
mkdir utils
touch utils/__init__.py  # to treat utility as a package
touch utils/model.py
touch utils/aii_utils.py  (keep all helper functon in all_utils folder)
from utils.model import class
touch requirements.txt
conda create -n liveclass python==3.10.0 -y
conda activate liveclass
conda deactivate
pip install -r requirements.txt
pip freeze > requirements.txt
git push origin main
git remote add origin "https://github.com/AmitRanjan235/ML_live_class.git"
git init
git add .
git commit -m 'moduler structure'
git push origin master
git status
touch regressor.py

