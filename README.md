# moldesc-app

### Create conda environment
Firstly, we will create a conda environment called *moldesc*
```
conda create -n moldesc python=3.7.9
```
Secondly, we will login to the *moldesc* environement
```
conda activate moldesc
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/moldesc-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/Ankeet123/molecularDescriptor_Calculator/archive/master.zip

###  Launch the app

```
streamlit run app.py
```
