# Content to reproduce paper titled "Hello World"

## Content

Data and scripts are contained in the respective folders

## Run in the cloud

Click this link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jsheunis/ohbm-handson-test3/HEAD)

---

## Run locally

## Installation

Python is required. It is recommended to install and run the code in a virtual environment.

1. Install miniconda
2. Create a new environment: `conda create -n mypythonenv python=3.6`
3. Activate environment: `conda activate mypythonenv`
4. Follow next steps

Install required packages with `pip`:

```
pip install -r requirements.txt
```

In addition, also install the `BrainStat` package:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install
```


## Running the analysis

Navigate to the `code` directory, and then run `analysis_01.py`
