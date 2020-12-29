# How You Should Learn Data Science

Findings derived from 2020 Kaggle Data Science & Machine Learning Survey. The data is available [here](https://www.kaggle.com/c/kaggle-survey-2020/data).

## Getting Started

This repository uses Python 3.8.

* We use [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) to manage python version and virtual environment.
* The `requirements.txt` is provided just in case you want to use other virtual environment management.

## Motivation

I was interested using 2020 Kaggle Survey Data to find insights about:

1. How are data talents in Indonesia compare to other SEA countries and Globally?
2. What are the most used tools and platforms?
3. How does someone should learn to break into the field of data science?

## Usage

1. First, make sure you have everything in requirements.txt installed. For quick installation, run below
```bash
pip install -r requirements.txt
```
2. Download the [2020 Kaggle Data Science & Machine Learning Survey](https://www.kaggle.com/c/kaggle-survey-2020/data) data and put it inside folder `data/kaggle_survey_2020`.
3. For quick run, open up Jupyter Notebook or JupyterLab, and then just **Run All**.
4. There is a json file `kaggle_question_cols.json` contains mapping of column name and the corresponding question.

## Results and Findings

All findings and other necessary visualization can be found at the Medium post available [here](https://medium.com/@syahrulhamdani/how-you-should-learn-data-science-b657977841f9).

## License

See `LICENSE`.
