# How to create a conda environment

Create a new conda environment using the following commands:

```cli
conda create -n dtsa5509 Python=3.9
conda activate dtsa5509
```

(Optional) If you would like to do experimentation in Jupyter, use the following commands to extend just created environment:

```cli
conda install ipykernel
python -m ipykernel install --user --name dtsa5509 --display-name "Python (dtsa5509)"
conda install jupyter
```

Install required packages:

```cli
pip install -r requirements.txt
```
