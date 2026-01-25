# Wine categorizer
This repo is used as an introduction for a course in Machine Learning and touches slightly the steps of a ML project (see: https://ictresearchmethods.nl/machine-learning/). The case focuses on a [classification](https://www.geeksforgeeks.org/machine-learning/getting-started-with-classification/) problem, utilizing the [Titanic dataset](https://archive.ics.uci.edu/dataset/109/wine) to determine to which cultivar a wine belongs to.

![house-price-predictor](https://github.com/Fontys/nearest-neighbors/blob/main/BANNER.jpeg)
*Image by Stable Diffusion: a robot tasting wine*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. 

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - You know the basics of [scikit-learn](https://scikit-learn.org/stable/getting_started.html)
 - You know the basic structure of k-Nearest Neighbors [theoretically](https://www.geeksforgeeks.org/machine-learning/k-nearest-neighbours/) and in [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
 - You understand the reasons for making [train, validate and test](https://en.wikipedia.org/wiki/Training%2C_validation%2C_and_test_data_sets) datasets
 - You understand the purpose and value of classification evaluation metrics like [accuracy, precision, recall and F1-scores](https://medium.com/@ml_dl_explained/an-overview-of-classification-model-metrics-8e25432d36ea)

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
- A brief analysis of the data
- A k-Nearest Neighbours classifier model used for training
- Evaluating the model's performance using standardized evaluation metrics for classification problems
- An inference to see how the model would respond.

## 🤔 Considerations for improvement
This notebook is an example on how to get started, it is open for improvements and enhancements. Feel free to clone my work and use it to study and learn. Things to consider if you want to improve this work:
- Domain Understanding: which features of a wine determine the cultivar it belongs to?
- There are more classification models than decision trees. How do other models compare to decision trees in this case?
- Calculating the R² and the RMSE of this model would help judging the model's performance. What do their values mean in relation to the case? 

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!
> Konings, Hans H.H.M. (2026) "Wine categorizer" GitHub: https://github.com/Fontys/nearest-neighbors/
