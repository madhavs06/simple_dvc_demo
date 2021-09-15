create env
'''bash
conda create -n wineq python=3.7
'''
activate env
'''bash
conda activate wineq
'''

create a req file
'''bash
touch requirements.txt
'''

install the req
'''bash
pip install -r requirements.txt
'''

#download the data from

*gdrive link*

git init

dvc init

dvc ad data_give/winequality.csv

git add .

git commit -m "first commit"

#updating readme

git add . && git commit -m "update Readme.md"

git remote add origin main https://github.com/madhavs06/simple_dvc_demo.git

git branch -M  main

#local changes will reflect in repo

git push origin main