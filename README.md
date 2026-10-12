# DSCI 552 - Homework 3

AReM activity recognition data set: time-domain feature extraction from the six sensor
time series of each instance, and bootstrap confidence intervals for the standard
deviation of every feature. Also the ISLR exercises 3.7.4, 3.7.3 and 3.7.5.

Name: Mohammad Hasnain Raza
GitHub Username: hasnainrazaa03
USC ID: 1259246355

## Structure

```
data/AReM/          data set (7 activity folders, 88 recordings in total)
notebook/           Raza_MohammadHasnain_HW3.ipynb
requirements.txt    package versions used
```

## Running the notebook

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd notebook
jupyter notebook Raza_MohammadHasnain_HW3.ipynb
```

The notebook reads the recordings with the relative path `../data/AReM`, so it runs from
the `notebook` folder without any change.
