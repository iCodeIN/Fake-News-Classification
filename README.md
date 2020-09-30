![Banner](https://github.com/SauravMaheshkar/Fake-News-Classification/blob/master/Banner.png)

# Fake News Classification

We have all seen fake news forwards on our WhatsApp messages. Generally, these articles are generated by bots and internet trollers and are used with an intent to intrigue the audience and mislead them. Fake news can be very dangerous as it can spread misinformation and inflict rage in public. It is now becoming a serious problem in India due to more and more people using social media and lower levels of digital awareness.


# Table of contents

- [Table of contents](#table-of-contents)
- [Demo](#demo)
- [Aim](#aim)
- [Installation](#installation)
- [Stack](#stack)
- [Development](#development)
- [Request](#request)
    -[Bug](#bug)
- [Contribute](#contribute)
- [License](#license)
- [Credits](#credits)


# Demo
[(Back to top)](#table-of-contents)

Here's a screenrecording of the Model in action. I copied a article from a authentic and reputed news source, pasted it on the text block and ran inference. As you can see the model gave the correct prediction of the article being Real

![Demo GIF](https://github.com/SauravMaheshkar/Fake-News-Classification/blob/master/demo.gif)


# Aim
[(Back to top)](#table-of-contents)

The aim of this project is to make a Fake News Classification using various techniques like Recurrent Neural Networks and RandomForestClassification and figure out which performs the best for this use case.


# Installation
[(Back to top)](#table-of-contents)

To use this project, first clone the repo on your device using the command below:

```git init```

```https://github.com/SauravMaheshkar/Fake-News-Classification.git``` 



# Stack

[(Back to top)](#table-of-contents)

The following libraries and modules were used in this software:

- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [sklearn](https://scikit-learn.org/stable/)
- [matplotlib](https://matplotlib.org/)
- [nltk](https://www.nltk.org/py-modindex.html)


# Development
[(Back to top)](#table-of-contents)

## Method 1: Random Forest Classification
Random forests or random decision forests are an **ensemble learning** method for classification, regression and other tasks that operate by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees. Random decision forests correct for decision trees' habit of overfitting to their training set. Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees. However, data characteristics can affect their performance.

## Method 2: Bidirectional Recurrent Neural Networks
**Bidirectional Recurrent Neural Networks (BRNN)** connect two hidden layers of opposite directions to the same output. With this form of **generative deep learning**, the output layer can get information from past (backwards) and future (forward) states simultaneously. Invented in 1997 by Schuster and Paliwal, BRNNs were introduced to increase the amount of input information available to the network. Standard recurrent neural network (RNNs) also have restrictions as the future input information cannot be reached from the current state. On the contrary, BRNNs do not require their input data to be fixed. Moreover, their future input information is reachable from the current state.


# Request
[(Back to top)](#table-of-contents)

### Bug 
[(Back to top)](#table-of-contents)

If you spot a bug in the program kindly raise a issue. Instructions for raising an issue can be found [here](https://docs.github.com/en/enterprise/2.15/user/articles/creating-an-issue)


# Contribute
[(Back to top)](#table-of-contents)

If you want to contribute to the project kindly mail me at `sauravvmaheshkar@gmail.com`.

### Step 1
 - **Option 1**
   🍴 Fork it!  
 - **Option 2**
    👯‍♂️ Clone this repo to your local machine using `https://github.com/SauravMaheshkar/Fake-News-Classification.git`
### Step 2

- **HACK AWAY!** 🔨🔨🔨

### Step 3

- 🔃 Create a new pull request using `https://github.com/SauravMaheshkar/Fake-News-Classification/compare/`


# License
[(Back to top)](#table-of-contents)

[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)

The data for this project was taken from kaggle datasets. The owner of the dataset is [Clément Bisaillon](https://www.kaggle.com/clmentbisaillon). You can find the dataset [here](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset).

- Copyright 2020 @[Saurav Maheshkar](https://sauravmaheshkar.github.io/)
- [MIT License](https://opensource.org/licenses/MIT)


# Credits

The inspiration for this readme file came from
- [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46#license)
- [Navendu Pottekkat](https://github.com/navendu-pottekkat/awesome-readme/blob/master/README-template.md)

