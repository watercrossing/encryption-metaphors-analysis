# Summary
Supplementary data to USEC '18 paper: "Metaphors considered harmful? An exploratory study of the effectiveness of functional metaphors for end-to-end encryption" by Albese Demjaha, Jonathan Spring, Ingolf Becker, Simon Parkin and M. Angela Sasse. [Fulltext of paper](http://sec.cs.ucl.ac.uk/fileadmin/sec/publications/Demjaha-2018-metaphors-considered-harmful.pdf).

The content of this repository was first published as an archive at DOI [10.14324/000.ds.10042529](http://dx.doi.org/10.14324/000.ds.10042529).


This archive contains the survey itself, the (annonymized) raw data and the functions used to analyse the data. The analysis was performed in IPython notebooks. Rendered version of these notebook are also included.

## Content

Contained in this repository are the following files:
- `requirements.txt`: The pip requirements file that can be used to recreate the exact setup (use `pip install -r requirements.txt`, preferably within a virtualenv)
- `data/E2E-coding-toPublish.csv`: The codes assigned by three coders to the end-to-end encryption statement
- `data/Encryption-coding-toPublish.csv`: The codes assigned by three coders to the encryption statements
- `data/survey-toPublish.csv` Raw, valid responses to the survey
- `metaphor-agreement-topublish.ipynb`: The IPython notebook containing the agreement analysis
- `metaphor-agreement-topublish.html`: A rendered version of the IPython notebook containing the agreement analysis
- `survey-analysis-to-publish.ipynb`: The IPython notebook containing the survey analysis
- `survey-analysis-to-publish.html`: A rendered version of the IPython notebook containing the survey analysis
- `survey.htm`: The full survey

To reproduce the results with python 3.6:
- unpack this zip file and enter the directory
- create a virtualenv (`python -m venv metaphor-study`)
- enter the virtualenv (`source metaphor-study/bin/activate` or similar for other OSs)
- install packages (`pip install -r requirements.txt`)
- run IPython notebook server: (`jupyter notebook`)
- your browser should start with jupyter interface
- open the notebooks `metaphor-agreement-topublish.ipynb` and `survey-analysis-to-publish.ipynb`
- select 'Cell' and 'Run All'.
- wait for graphs and tables to be produced.

For queries please contact Ingolf Becker at i.becker@ucl.ac.uk.
