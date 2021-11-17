<p align="center">
  <img src="https://github.com/name-ethnicity-classifier/.github/blob/main/profile/nec_logo.png" />
</p>


# Name ethnicity classifier

## :earth_africa: What's this organization about?
This GitHub organization contains research experiments, a console interface classifier and the codebase for the name-ethnicity-classifier webapp.

## 🖥️ The CLI classifier:
Using the [name-ethnicity-classifier](https://github.com/name-ethnicity-classifier/name-ethnicity-classifier) repository, you can classify names into their ethnicities.
You can choose between models that are trained on different nationality configurations. Since the dataset is private, you can't train models on your own. Therefore, if you want to classify between specific nationalities, feel free to write an issue, and we might train it for you. You can also wait for our webapp to go live soon!

## 🌈 Research:
Name ethnicity classification can be a useful tool, especially for social science research. Interpreting findings in a dataset containing the name and other information about persons but not their nationalities can lead to the fact that existing coherences based on their background are not recognized. And because this classification problem is highly dependent on the dataset, there may be biases in the models with respect to gender, age, and race. We seek to identify and compare such biases in different existing name ethnicity/nationality classifiers (like ours).

## ☁️ The webapp:
As the dataset is private and therefore cloners can't train custom ethnicity classifiers themselves, we still want to enable that option using a non-profit webapp.
You will be able to choose the nationalities you need and request a model which we will automatically train for you. You can then upload names in a .csv file, classify them and download the results.
