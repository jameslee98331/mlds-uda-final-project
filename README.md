# Unsructured Data Analysis - Final Project

_Imperial College London - MSc Machine Learning and Data Science Year 2 - Unstructured Data Analysis Final Project._

## Introduction
This repository stores the input data, code, and output plots and data for the Unstructured Data Analysis module Final Project.
- The input text data is [vaccination_all_tweets.csv](./datasets/vaccination_all_tweets.csv),
- the processed text data is [reduced_and_balanced_vaccination_tweets.csv](./datasets/reduced_and_balanced_vaccination_tweets.csv),
- the notebook that stores the code used in this project is [UDA_FinalProject_Lee.ipynb](./UDA_FinalProject_Lee.ipynb), and
- The output plots generated for the report are stored in [report_media](./report_media/).

This notebook is developed on a desktop computer with the following hardware information:
- CPU: Intel(R) Core(TM) i7-7700 CPU @ 3.60GHz, 3601 Mhz, 4 Core(s), 8 Logical Processor(s)
- Total Physical Memory: 47.9 GB
- GPU: NVIDIA GeForce GTX 1070, 8.0GB dedicated memory

The GPU was used in the sentiment labelling step to speed up processing.

The run time of the notebook in the above environment is ~2,500 seconds (42 minutes).

## Running the code
It is recommended to use a virtual environment to manage the dependencies. [`pyenv`](https://github.com/pyenv/pyenv) was used for this project and can be installed using the [pyenv installer](https://github.com/pyenv/pyenv-installer). A virtualenvironment with Python version 3.9.14 was used for this project.

The libraries needed to run the notebook are stored in [`requirements.txt`](./requirements.txt).

To install the dependencies:
```bash
pip install -r requirements.txt
```

Additionally, the `en_core_web_sm` pipeline from `spacy` must also be downloaded using:
```bash
python -m spacy download en_core_web_sm
```
