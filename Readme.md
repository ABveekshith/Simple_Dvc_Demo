create environment
"""bash

conda create -n wineq python=3.7 -y
'''

activate environment
'''bash
conda activate wineq
'''

created a req file
install the req
''' bash
pip install -r requirements.txt
'''

Download
'wine quality data set from kaggle

git init
dvc init
dvc.add data_used/wineqaulity.csv

git add . 
git commit -m "first commit"

git add . && git commit -m "update readme.md"

git remote add origin https://github.com/ABveekshith/Simple_Dvc_Demo.git


git branch -M main
git push origin main



