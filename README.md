# Data Science Toolbox 4

There is a Jupyter notebook containing the practical part of this report at `./project/report.ipynb`. This can be downloaded and run locally, or within Google Colab. A copy of the PDF is also in this repo, located at `./project/report.pdf`.

## Running locally
We've frozen our dependencies in `requirements.txt`, so the following should get a local installation up and running:
```
pip install -r requirements.txt
```

## Running with Google Colab
Following [this link](https://colab.research.google.com/github/sydneyvert/dst4/blob/master/project/report.ipynb) will open the main report in colab. Then run the following in a code cell:

```
!pip install cleverhans
```

(this is commented out in the top code cell). The rest of our requirements come pre-installed.

## Data
We've included a compressed version of the data set in this repo (sourced from http://www.schonlau.net/intrusion.html). However, the code in our notebook will download and unzip the data directly into memory (i.e. the data directory in this repo isn't needed to run the notebook, but an internet connection is).
