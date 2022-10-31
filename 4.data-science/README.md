# The Era of Data Science
> "The first rule of data science is: _don’t ask how to define data science!_"

<p align="center">
  <img src="https://github.com/keivanipchihagh/machinelearning-roadmap/blob/master/images/data-science.jpg?raw=true" width="600" />
</p>

## Building Blocks
- Interactive notebooks:
  - Run locally with [Jupyter Notebook](https://jupyter.org/install), or move to the cloud with [Google Colaboratory](https://research.google.com/colaboratory/)
  - [Tips and tricks (video)](https://www.youtube.com/watch?v=YuWZNV4BkkY&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=3)
- Learn [Numpy](https://numpy.org/):
  - Numpy Official: [quick-start](https://numpy.org/devdocs/user/quickstart.html)
  - [Numpy Essentials](https://towardsdatascience.com/numpy-essentials-for-data-science-25dc39fae39)
  - See in Action (video): [Complete Python NumPy Tutorial (Creating Arrays, Indexing, Math, Statistics, Reshaping)](https://www.youtube.com/watch?v=GB9ByFAIAH4&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=8)    
  - [cheatsheet](https://assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf)
- Learn [Pandas](https://pandas.pydata.org/):
  - Kaggle: [Pandas](https://www.kaggle.com/learn/pandas)
  - See in Action (video): [Pandas tutorial](https://www.youtube.com/watch?v=vmEHCJofslg&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=2) and [Data Analysis with Pandas on Lego-Dataset](https://www.youtube.com/watch?v=BzQDi4D0B_M&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=18)
  - See in Action (video): [Generating mock data with Pandas and Numpy](https://www.youtube.com/watch?v=VJBY2eVtf7o&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp)
  - [cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- Data Visualization with [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/):
  - Kaggle: [Data Visualization](https://www.kaggle.com/learn/data-visualization)
  - See in Action (video): [Intro to data visualization with matplotlib](https://www.youtube.com/watch?v=DAQNHzOcO5A&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=4) and [Plotting with Pandas and matplotlib](https://www.youtube.com/watch?v=0P7QnIQDBJY)
  - [cheatsheet](https://matplotlib.org/cheatsheets/cheatsheets.pdf)

**Checkpoint #10**: I strongly encourage to pause here and make yourself comfortable with these libraries, because they are the bulding blocks of everything from now on. There are many courses and videos out there you can get help from.

**Checkpoint #11**: Alter your Reddit scraper bot to store some useful features (likes, number of comments, votes, awards, posted datetime, etc.) in your database. You can then do some analysis and visualization work using the data! Your bot can also return memes in categories of **most viewed**, **most recent**, **most likes** etc. PROGRESS!

## A Gentle Approach to Machine-Learning
> If you torture the data long enough, it will finally confess.

It's perfectly **okay** if some of the contents you are about to read don't make much sense, or you wonder how they work. We've all been there at all you got to do is to be patient.

### Get to Know the Concepts
- Google Developers: [Machine Learning crash course](https://developers.google.com/machine-learning/crash-course/ml-intro) (stick to the concepts for now)
- Kaggle: [Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)
  - Splitting your data:
    - official [_train_test_split_](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) documentations
    - [Understanding train test split](https://towardsdatascience.com/understanding-train-test-split-scikit-learn-python-ea676d5e3d1)
    - [Follow-up](https://realpython.com/train-test-split-python-data/)
  - Underfitting vs Overfitting:
    - [A complete example](https://towardsdatascience.com/overfitting-vs-underfitting-a-complete-example-d05dd7e19765)
    - [More on what it is and how to prevent it](https://elitedatascience.com/overfitting-in-machine-learning#how-to-detect)
  - [How Random Forest actually works?](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)
- Kaggle: [Intemediate Machine Learnng](https://www.kaggle.com/learn/intermediate-machine-learning)
  - Missing Values:
    - [How to deal with Missing Values](https://towardsdatascience.com/6-different-ways-to-compensate-for-missing-values-data-imputation-with-examples-6022d9ca0779)
    - [Imputing Missing Data](https://www.theanalysisfactor.com/seven-ways-to-make-up-data-common-methods-to-imputing-missing-data)
    - Scikit-Learn [Imputer Library](https://scikit-learn.org/stable/modules/impute.html)
  - Categorical Encoding:
    - [4 Categorical Encoding concepts](https://towardsdatascience.com/4-categorical-encoding-concepts-to-know-for-data-scientists-e144851c6383)
    - Clearing the confusion: [LabelEncode vs OneHotEncode](https://datascience.stackexchange.com/questions/9443/when-to-use-one-hot-encoding-vs-labelencoder-vs-dictvectorizor)
  - Scikit-Learn: [Cross-validate function](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_validate.html)
- Kaggle: [Intro to DeepLearning](https://www.kaggle.com/learn/intro-to-deep-learning)
- Kaggle: [Feature Engineering](https://www.kaggle.com/learn/feature-engineering)
- scikit-learn: [tutorial](https://scikit-learn.org/stable/tutorial/index.html)

**Checkpoint #12**: _Compeition time with [Titanic Machine Learning from Disaster](https://www.kaggle.com/c/titanic)_! Explore the competition page, read [other's notebooks](https://www.kaggle.com/competitions/titanic/code?competitionId=3136&sortBy=voteCount) (it's not cheating ^_^), create a notebook and start coding (lacking ideas? get help from other notebooks!). Submit your results (might have to try a few times to get it right). **Take your days and improve your code as much as you can**!!!

### Q&A Session
Answers to your questions:
- Overfitting vs underfitting
  - [Underfitting and Overfitting](https://stats.stackexchange.com/questions/395197/overfitting-and-underfitting) explained
  - [How to know if Underfitting or Overfitting is occuring](https://stackoverflow.com/questions/52009816/how-to-know-if-underfitting-or-overfitting-is-occuring)
  - [7 Simple Techniques to Prevent Overfitting](https://www.kaggle.com/getting-started/157623)
- Train Test Split
  - [Splitting data into Train-Test and Keeping the ratio](https://stackoverflow.com/questions/52610332/splitting-data-set-into-training-and-test-data-keeping-the-ratio)
  - [How to Decide a Train-Test-Split](https://ai.stackexchange.com/questions/32029/how-to-decide-a-train-test-split)

### Dive Even Deeper
  - Pipeline:
    - Official [Pipeline Module](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) documentations
    - [Add custom transformers to your Pipeline](https://towardsdatascience.com/pipelines-custom-transformers-in-scikit-learn-the-step-by-step-guide-with-python-code-4a7d9b068156)
  - Hyperparameter Tuning:
    - Official [modules](https://scikit-learn.org/stable/modules/grid_search.html)
    - [Hyperparameter Optimization with RandomSearch and GridSearch](https://machinelearningmastery.com/hyperparameter-optimization-with-random-search-and-grid-search/)
  - Ensembling:
    - [Basics and Introduction](https://builtin.com/machine-learning/ensemble-model)
    - [Further reading](https://machinelearningmastery.com/tour-of-ensemble-learning-algorithms/)
    - Official [methods](https://scikit-learn.org/stable/modules/ensemble.html)
    - [Ensemble Models](https://towardsdatascience.com/ensemble-models-5a62d4f4cb0c): RandomForst, AdaBoost, XGBoost, etc.