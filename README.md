# cov-pl-analysis

A playground for crunching # cases of SARS-CoV-2 in Poland.

## getting started

1. set up the environment

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. get access to source data

Source date is stored in a Google spreadsheet. You need to get
Google API credentials by following
[this guide](https://gspread.readthedocs.io/en/latest/oauth2.html).

3. start the notebook

```
source .venv/bin/activate
jupyter notebook
```
