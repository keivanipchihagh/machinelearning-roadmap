# machinelearning-roadmap
A hands-on roadmap to learn Data-Science, Machine-Learning and MLOps. This roadmap is more practical than theoratical (great news!); So it's best to do more research as you reach sections of this roadmap.

## Table of Contents
- [Push-ups with Python]()
- [SQL is your friend]()
- [Version Control with Git]()
- [Docker in Action]()
- [The Era of Data Science]()
  - [Building Blocks]()
  - [A Gentle Approach to Machine-Learning]()

## Push-ups with Python
> How do functions break-up? Well, they stop calling each other.

You can use any programming language you'd like, but _Python_ is the widest used language among Data Scientists and Machine Learning Engineers. It's also super easy to master!

### Basics
- [Syntax](https://www.w3schools.com/python/python_syntax.asp) and [Comments](https://www.w3schools.com/python/python_comments.asp)
- [Variables](https://realpython.com/python-variables/) and Data Types:
  - [Strings](https://www.w3schools.com/python/python_strings.asp) and [formatting them with f-string](https://towardsdatascience.com/a-simple-guide-to-string-formatting-in-python-using-f-strings-39e5c39589c3)
  - [Formatting datetime](https://stackabuse.com/how-to-format-dates-in-python/)
- Data Structures: [Tuples](https://www.w3schools.com/python/python_tuples.asp), [Lists](https://www.w3schools.com/python/python_lists.asp), [Sets](https://www.w3schools.com/python/python_sets.asp) and [Dictionary](https://www.programiz.com/python-programming/dictionary)
- [Functions](https://www.programiz.com/python-programming/function)
- Flow Control:
  - [If-elif-else](https://www.programiz.com/python-programming/if-elif-else)
  - Loops: [while](https://www.w3schools.com/python/python_while_loops.asp) and [for](https://www.w3schools.com/python/python_for_loops.asp)
  - [Pass, Break or Continue](https://betterprogramming.pub/how-to-use-pass-break-and-continue-in-python-6e0201fc032a)?
- Working with files:
  - [Basic file-operations](https://www.programiz.com/python-programming/file-operation)
  - [Working with JSON Data](https://realpython.com/python-json/)
  - [YAML: The Missing Battery in Python](https://realpython.com/python-yaml/)

**Checkpoint #1**: Solve as many problems as you can in [Hackerrank](https://www.hackerrank.com/domains/python) and put your skills at use! Need more practice? Try [pynative](https://pynative.com/python-exercises-with-solutions/) and [practicepython](https://www.practicepython.org/).

### Intermediate
- Working with Web: [requests](https://realpython.com/python-requests/) and [Beautiful Soup](https://www.dataquest.io/blog/web-scraping-python-using-beautiful-soup/) libraries
- [Multithreading and Multiprocessing](https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29)
- [Object Oriented Programming](https://www.pythontutorial.net/python-oop/)
- Regular Expression (Regex):
  - [Regex native](https://regexone.com/)
  - [Regex in Python](https://www.programiz.com/python-programming/regex)
- [Decorators](https://www.freecodecamp.org/news/python-decorators-explained-with-examples/)
- Exception Handling:
  - [Basic try-catch-finally](https://realpython.com/python-exceptions/)
  - [Handling exceptions a cleaner way](https://medium.com/swlh/handling-exceptions-in-python-a-cleaner-way-using-decorators-fae22aa0abec)
- [Unit-Testing](https://realpython.com/python-testing/)
- [Saving your configurations file](https://towardsdatascience.com/from-novice-to-expert-how-to-write-a-configuration-file-in-python-273e171a8eb3)

**Checkpoint #2**: Build a simple scraper for Reddit Memes given the sub-reddit ([API docs](https://www.reddit.com/dev/api/)) and store them into a JSON file as you scrape.

**Checkpoint #3**: Upgrade the Reddit scraper to get memes from multiple sub-reddits at the same time (_multithreading_) with enhanced exception handling. Also, save your API configurations into a file.

### Advanced
- [Keep calm and write logs](https://realpython.com/python-logging/) and even more [logs](https://machinelearningmastery.com/logging-in-python/)!
- Write docs the proper way:
  - [Google style](https://google.github.io/styleguide/pyguide.html)
- [Manage your packages with PIP](https://www.w3schools.com/python/python_pip.asp)
- Managing your Environments:
  - [Isolate your project with Virtual Environment](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)
  - [Store your Environmental Variables](https://pypi.org/project/python-dotenv/)
- [Structuring your application](https://realpython.com/python-application-layouts/)
- Code scheduling: [Cron-Job](https://phoenixnap.com/kb/set-up-cron-job-linux) or [schedule](https://pypi.org/project/schedule/) librry.

**Checkpoint #4**: Learn to use [Telegram Bot](https://github.com/python-telegram-bot/python-telegram-bot) and move your Reddit scraper to the Bot. ([Example bots](https://docs.python-telegram-bot.org/en/v20.0a1/examples.html))

**Checkpoint #5**: Your Bot should run at all times (since it's a service!), so deploy it on [Heroku](https://www.heroku.com/). (See Heroku:[getting-started-with-python](https://devcenter.heroku.com/articles/getting-started-with-python))

_Final Note: I suggest going through a few whole tutorials to build up a solid background on Python, like with [w3Schools](https://www.w3schools.com/python/default.asp), [programiz](https://www.programiz.com/python-programming) or [pythontutorial](https://www.pythontutorial.net/)._

## SQL is your friend
> A SQL query goes into a bar, walks up to two tables and asks: "Mind if I join you?"

- [Basics](https://www.sqlcourse.com/beginner-course/): Select, Create, Insert, Update, Delete or Drop
  - [Aliases](https://www.w3schools.com/sql/sql_alias.asp)
  - [Where](https://www.w3schools.com/sql/sql_where.asp) - Conditions
  - Kaggle: [hands-on course](https://www.kaggle.com/learn/intro-to-sql)
- [Intermediate](https://www.sqlcourse.com/advanced-course/): Aggregate, Group By, Having, Order By and Joins
  - Aggregations: Count, Sum, Avg
  - [Joins](https://www.freecodecamp.org/news/sql-joins-tutorial/): Inner Join, Outer Join, Left Join, Right Join, Full Join, Self Join, Union (Read more [here](https://www.dataquest.io/blog/sql-joins-tutorial/))
  - Kaggle: [More on SQL](https://www.kaggle.com/learn/advanced-sql)
- Advanced:
  - [Wildcards](https://www.w3schools.com/sql/sql_wildcards.asp) and [Like](https://www.w3schools.com/sql/sql_like.asp)
  - [SQL Injection](https://portswigger.net/web-security/sql-injection) in [Action](https://www.hacksplaining.com/exercises/sql-injection#/start)
  - [Auto Increment](https://www.w3schools.com/sql/sql_autoincrement.asp)
  - [Index](https://www.sqlservertutorial.net/sql-server-indexes/) - To speed up your query!
  - Choose an engine: [postgresql](https://www.postgresql.org/), [mysql](https://www.mysql.com/), [SQL-Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads), [SQLite](https://www.sqlite.org/index.html), etc.
- Off Topic: SQL doesn't end anywhere near here! There are many more advanced topics like [Views](https://www.sqlservertutorial.net/sql-server-views/), [Procedures](https://www.sqlservertutorial.net/sql-server-stored-procedures/), [Functions](https://www.sqlservertutorial.net/sql-server-user-defined-functions/), [Triggers](https://www.sqlservertutorial.net/sql-server-triggers/) and a lot more. You can learn them if you want, but they are not something a _Data Scientiest_ should worry about (hopefully!).

Preferably, go through courses like [w3schools](https://www.w3schools.com/sql) and [sqlservertutorial](https://www.sqlservertutorial.net). 

**Checkpoint #6**: You know SQL commands, but must put your skills to work [here](https://www.wiseowl.co.uk/sql/exercises/standard/).

**Checkpoint #7**: Connect your python to a Database (I suggest, postgresql - see [how](https://www.tutorialspoint.com/postgresql/postgresql_python.htm)) and scrape lots of memes of Reddit and store then into your database; then alter your Bot to read the memes from database instead of scraping each time.

## Version Control with Git
> The problem with git jokes is that everyone has their own version.
- Creating a repository using Git
- Cloning a Git repository:
  - [Secure your account with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
- Add, Commit and Push
- Pull, Fetch, Stash
- Fork, Pull Requests, Merges
- Reverts, Resets, Branches:
  - [Branching strategy](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy)
- [Choosing the right License](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)

There are also many courses out there, like [codecademy](https://www.codecademy.com/learn/learn-git), [tutorialspoint](https://www.tutorialspoint.com/git/index.htm) or [w3schools](https://www.w3schools.com/git)

**Checkpoint #8**: Add your Reddit scraper codes in a GitHub repository and link it to Heroku. Now you can change your code and see the effects in realtime!

## Docker in Action
> What if we put Docker inside of Docker?
- [Why even bother with Docker?](https://medium.com/@kmdkhadeer/docker-get-started-9aa7ee662cea)
- [get-started](https://docs.docker.com/get-started/)
- Components in detail:
  - [docker-compose](https://docs.docker.com/compose/)
  - [Dockerfile](https://docs.docker.com/engine/reference/builder/)
  - [Manage sensitive data with Docker secrets](https://docs.docker.com/engine/swarm/secrets/)

**Checkpoint #9**: Dockerize your Reddit scraper bot and deploy it on Heroku (run it locally first, remember baby steps!).

_Final Note: Getting comfortable with Docker can take some time and practice. However, Docker is the gateway to MLOps which plays an important role in deploying Machine-Learning models!_

## The Era of Data Science
> "The first rule of data science is: _don’t ask how to define data science!_"

### Building Blocks
- Interactive notebooks:
  - Run locally with [Jupyter Notebook](https://jupyter.org/install), or move to the cloud with [Google Colaboratory](https://research.google.com/colaboratory/)
  - [Tips and tricks (video)](https://www.youtube.com/watch?v=YuWZNV4BkkY&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=3)
- Learn [Numpy](https://numpy.org/):
  - Official [quick-start](https://numpy.org/devdocs/user/quickstart.html)
  - [Numpy Essentials](https://towardsdatascience.com/numpy-essentials-for-data-science-25dc39fae39)
  - See in Action (video): [Numpy tutorial](https://www.youtube.com/watch?v=GB9ByFAIAH4&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=8)    
  - [cheatsheet](https://assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf)
- Learn [Pandas](https://pandas.pydata.org/):
  - [Kaggle hands-on course](https://www.kaggle.com/learn/pandas)
  - See in Action (video): [Pandas tutorial](https://www.youtube.com/watch?v=vmEHCJofslg&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=2) and [Data Analysis with Pandas on Lego-Dataset](https://www.youtube.com/watch?v=BzQDi4D0B_M&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=18)
  - [cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
  - See in Action: [Generating mock data with Pandas and Numpy](https://www.youtube.com/watch?v=VJBY2eVtf7o&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=10)
- Data Visualization with [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/):
  - Kaggle [hands-on course](https://www.kaggle.com/learn/data-visualization)
  - See in Action (video): [Intro to data visualization with matplotlib](https://www.youtube.com/watch?v=DAQNHzOcO5A&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=4) and [Plotting with Pandas and matplotlib](https://www.youtube.com/watch?v=0P7QnIQDBJY)
  - [cheatsheet](https://matplotlib.org/cheatsheets/cheatsheets.pdf)

**Checkpoint #10**: At this point, you have followed the _See in Action_ parts of each library and you are good to go! I strongly recommand not to stop here and make yourself comfortable with these libraries, because they are the bulding blocks of everything from now on.

**Checkpoint #11**: You could alter your Reddit scraper bot to give your some numbers (likes, number of comments, votes, awards, etc.) and save them along side memes in Pandas. You can then do some analysis and visualization work!

### A Gentle Approach to Machine-Learning
> If you torture the data long enough, it will finally confess.

It's perfectly **okay** if what you are about to read sounds crazy and that you have no idea how some things work (and why they work!), but they will start to make sence after some time, hang tight!

#### Starting Off: 
- Official [scikit-learn tutorial](https://scikit-learn.org/stable/tutorial/index.html)
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

By now, you probably have tons of questions and are panicing! Good, let's get into action and see how it's really done.

**Checkpoint #12**: _Compeition time with [Titanic Machine Learning from Disaster](https://www.kaggle.com/c/titanic)_! Explore the competition page, read [other's notebooks](https://www.kaggle.com/competitions/titanic/code?competitionId=3136&sortBy=voteCount) (it's not cheating), create a notebook and start coding (lacking ideas? get help from other notebooks!). Submit your results (might have to try a few times to get it right). **Take your days and improve your code**!!!

#### Diving even Deeper
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
