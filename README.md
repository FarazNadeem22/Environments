# Environments-
Environments 
### Use the following command to create your environment. You will need an anaconda distribution and you will need to make it available on you base path while installation
conda env create -f cs109a.yml

### To remove this environment 
conda env remove -n cs109a

### How to check your environments 
conda env list

### Creating a virtual enveronment with python -m. This will created a virtual environment that will show in the tree view  
$ python -m venv venv


### yml alternative 
$ python -m pip install -r requirements.txt

"""
-- requrements.txt
alembic==1.6.5
Faker==8.5.1
Flask==2.0.1
Flask-Migrate==3.0.1
Flask-SQLAlchemy==2.5.1
psycopg2-binary==2.9.1
SQLAlchemy==1.4.17
"""
