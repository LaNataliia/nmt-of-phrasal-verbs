# Neural Machine Translation of Discontinuous Units: A Case Study of Phrasal Verbs

This repository stores the code and the dataset of my master's thesis on the topic
**Neural Machine Translation of Discontinuous Units: A Case Study of Phrasal Verbs**

* `dataset.xlsx` - working dataset -> the **final version of the dataset** after removing false positive and adding data annotation for verb types
* `data_collection.ipynb` - code for:
  - *combining raw TED Talks files*
  - *spaCy parsing*
  - *getting a subcorpus of sentences with phrasal verbs*
  - *translating*
* `data_exploration.ipynb` - code for:
  - *obtaining descriptive statistics of the working dataset*
  - *plotting data*
  - *running chi-square tests for independence*
* `raw_ted_files` - collection of raw TED Talks files; `ted_en.txt`, `ted_de.txt` - combined TED Talks parallel corpora
* `TFM Nataliia Zolotukhina.pdf` - the manuscript
