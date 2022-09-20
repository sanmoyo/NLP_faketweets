# NLP_faketweets
3rd year coursework for **Machine Learning Technology** module at university --- my first software project in **Python**. Unlike my dissertation, this report is fairly short, so feel free to have a look at it in the repo or use the link below. 

**Link:** https://github.com/sanmoyo/NLP_faketweets/blob/main/MLT%20Coursework%20Write%20Up%20(mms2n18).pdf

**Components of the project:**
1. Training data from MEDIAEVAL 2015 event (**not** included here as it is from MEDIAEVAL)
2. Test data from MEDIAEVAL 2015 event (**not** included here as it is from MEDIAEVAL)
3. Jupyter Notebook file of the Machine Learning Technologies Coursework's implementation part by me. (attached in this repo)

Instructions to run the **Jupyter Notebook** file:

Run with **libraries** that are used in the implementation code:

i.e. **pandas, matplotlib.pyplot, timeit, re, and model specific** libraries as shown below:

from sklearn.feature_extraction.text import CountVectorizer

from sklearn.naive_bayes import MultinomialNB

from sklearn.linear_model import SGDClassifier

from sklearn.svm import LinearSVC

from sklearn.feature_extraction.text import TfidfTransformer

from sklearn.feature_extraction.text import TfidfVectorizer

from sklearn.pipeline import Pipeline

from sklearn.metrics import classification_report

from sklearn.model_selection import GridSearchCV
