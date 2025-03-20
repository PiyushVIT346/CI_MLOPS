D:\projects\DVC project2\dvc+mlflow+ci>cookiecutter -c v1 https://github.com/drivendata/cookiecutter-data-science

D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>python -m venv myenv
D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>myenv\Scripts\activate
(myenv) D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>git init
(myenv) D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>git remote add origin https://github.com/PiyushVIT346/CI_MLOPS.git
(myenv) D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>git push origin master

open dagshub website
click on create button on right top, select new repository option . Now chosse connect a repository option. add your repository of CI_MLOPS. click on remote option and choose experiment option and click on open mlflow ui option. A new tab on google will open of mlflows
pip install mlflow
pip install dagshub
pip install seaborn

create a file dagshub_test.py in notebooks folder. write a test code and run using command :"python .\notebooks\dagshub_test.py"
Now check in mlflow website

in terminal write the command: "dvc init"

To create its version enter command in terminal:
(myenv) D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>dvc remote add -d myremote C:\Users\HP\AppData\Local\Temp

enter the code of file data_collection.py,prep.py,model_building.py,model_eval.py and params.yaml,dvc.yaml and model_reg.py
To run command dvc repro
now we can chevk mlflow for the best model and parameters. also check the versions.


(myenv) D:\projects\DVC project2\dvc+mlflow+ci\CI_MLOS>p
ip freeze > requirements.txt


CI_MLOPS
==============================

mlops project

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
