# Red Wine Quality

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/red-wine-quality/blob/master/notebook.ipynb)&nbsp;[![Open in Kaggle](https://www.kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/jofaval/red-wine-quality-exploratory-analysis-predictions)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objective](#-objective)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at the official archive link:\
[https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

## 📓 Description
[↑ Back to the table](#table-of-contents)

An analysis of the red wine quality. The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.). 

## ✔️ Objective
[↑ Back to the table](#table-of-contents)

To succcessfully predict the quality of the red and white wine variants, as well as to identify which features are actually more important whilst trying to get a "quality" wine.

This is a little bit of spoilers. But there's not that many quality wines in comparison, so, for further detail, we'd have to actually research and collect more data before making any good conclusions

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.
- Tensorflow and Keras, the industry standard for Deep Learning, the way to go, not really, it's just that for now I don't have that many experience with PyTorch

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

In no specific order whatsoever, I'll enumerate the algorithms used, but, let me say that, Random Forest it's the winner of this project, not for much though.

- Logistic Regression, the simplest of them all, but effective nonetheless.
- Random Forest, an old reliable, and it, indeed, did not came short.
- Support Vector Machine, a powerful supervised technique that performed really well, better that the logistic.
- XGBoost, an incredibly powerful technique that, for this project, came in "second place", most likely because of my lack of experience tuning it.

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

There're all sort of visualizations, well, almost. KDE plots to evaluate it's distribution, boxplot for outlier detection and further insight into the data distribution, heatmaps for the correlation, piecharts for the target distribution (it's easier to visualize for a single target since it gives a lot of information). 

And lineplots and histplots, the classic visualization methods, used mainly to evaluate hypothesis. Crazier visualizations could have been made, of that I'm sure, but I did not deemed them necessary for this project's scope, which was a simple evaluation where a couple of hypothesis could, and did lead to good conclusions.

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

Balancement is crucial, and so is to have a numeric dataset, as was given for this project. That being said, have a nice amount of rows and quality data allows us to focus on the important stuff, understanding the data and it's patterns. So we can actually develop models that fit it's problems.

As for the balancement, without it, the scores skyrocketed, that's true, I could have gotten an almost 95% score, but having a balanced score of 68% it's not the victory it may seem. Having a biased model can lead to all sort of problems, and I tried to avoid that as much as possible so that the given score is as reliable as possible.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez
A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal
@2009

Uploaded at Kaggle, a company owned by Google by [https://www.kaggle.com/uciml](https://www.kaggle.com/uciml)