<p align="center">
  <img src="https://github.com/name-ethnicity-classifier/.github/blob/main/profile/nec_logo.png" />
</p>


# Name Ethnicity Classifier Project

## 🔎 About:

#### :earth_africa: What's this name-ethnicity classification?
Name-ethnicity classification is about finding out the most likely ethnical origin of a personal name (e.g Cixin Liu -> Chinese, Rita Papadopulo -> Greek). It can useful tool, especially for social science research: Interpreting findings in a dataset containing the name and other information about persons but not their nationalities can lead to the fact that existing coherences based on their background are not recognized. This can reult in biased research which benefits some groups of peoples more than others.

#### 🌈 Research:
Classifying names into ethnicities is highly dependent on the dataset, since it might bias models in regards of gender, age, and - of course - race. In our paper [Equal accuracy for Andrew and Abubakar—detecting and mitigating bias in name-ethnicity classification algorithms](https://link.springer.com/article/10.1007/s00146-022-01619-4) wee seek to identify and compare such biases in different existing name ethnicity/nationality classifiers (like ours).

#### 🖥️ The CLI classifier:
Using the [name-ethnicity-classifier](https://github.com/name-ethnicity-classifier/name-ethnicity-classifier) repository, you can classify names into their ethnicities locally.
You can choose between models that are trained on different nationality configurations. Since the dataset is private, you can't train models on your own. Therefore, if you want to classify between specific nationalities, feel free to write an issue, and we might train it for you. You can also use [www.name-to-ethnicity.com](https://www.name-to-ethnicity.com) to request custom models for free.

#### ☁️ The webapp:
###### ✨ [www.name-to-ethnicity.com](https://www.name-to-ethnicity.com) ✨
As the dataset is private and therefore you can't train custom ethnicity classifiers yourself, we still want to enable that option using a non-profit webapp.
You will be able to choose the nationalities you need and request a model, which we will automatically train for you. You can then upload names in a .csv file or use the API to classify them.

#### ❤️ Consider donating!
If you find our tool useful, please consider donating any amount to help us cover our server and maintenance fees, which we currently pay out of our own pockets. But we're also thrilled if you simply let us know that our tool contributed to your project—whether through a star on GitHub or a quick email!

👉 https://www.buymeacoffee.com/theodorpeih

---

## ⚙️ Development:

#### How to contribute:
I'm currently in the progress of rewriting the backend codebase.

You can find open tasks in the [📋 Kanban Board](https://github.com/orgs/name-ethnicity-classifier/projects/4/).



