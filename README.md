# CodeClause_Fake_News_Detection

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)<br>

## What It Does:
Fake news on different platforms is spreading widely and is a matter of serious concern, as it causes social wars and permanent breakage of the bonds established among people. A lot of research is already going on focused on the classification of fake news.


1️⃣ Data Collection <br>
2️⃣ Data Preprocessing <br>
3️⃣ Exploratory Data Analysis <br>
4️⃣ Dataset Balancing & Scaling <br>
5️⃣ Machine Learning Models Training & Evaluation

## Prerequisites:
I would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like: <br>


1️⃣ `Python`<br>
2️⃣ `scikit-learn` / `sklearn`<br>
3️⃣ `Pandas`<br>
4️⃣ `NumPy`<br>
5️⃣ `Swaborn`<br>
6️⃣ An environment to work in - something like `Jupyter` or `colab`<br>

For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Dataset:

> You can collect raw dataset from [here](news.csv).

Attribute Information:<br>
1️⃣ `Title` <br>
2️⃣ `Text` <br>
3️⃣ `Lable` <br>

## Machine Learning Model:

1️⃣**TfidfVectorizer**

**TF (Term Frequency):** The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

**IDF (Inverse Document Frequency):** Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.


2️⃣**PassiveAggressiveClassifier**

Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

#
