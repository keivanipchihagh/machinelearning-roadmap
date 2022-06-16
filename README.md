# machinelearning-roadmap
A roadmap to learn Machine-Learning and ML-Ops

## Table of Contents
- [Push-ups with Python]()
- [Version Control with Git]()
- [Docker in Action]()

## Push-ups with Python
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
- Interactive notebooks:
  - Run your code locally: [Jupyter Notebook](https://jupyter.org/install)
  - Run your code online: [Google Colaboratory](https://research.google.com/colaboratory/)

**Checkpoint #4**: Learn to use [Telegram Bot](https://github.com/python-telegram-bot/python-telegram-bot) and move your Reddit scraper to the Bot. ([Example bots](https://docs.python-telegram-bot.org/en/v20.0a1/examples.html))

**Checkpoint #5**: Your Bot should run at all times (since it's a service!), so deploy it on [Heroku](https://www.heroku.com/). (See Heroku:[getting-started-with-python](https://devcenter.heroku.com/articles/getting-started-with-python))

_Final Note: I suggest going through a few whole tutorials to build up a solid background on Python, like with [w3Schools](https://www.w3schools.com/python/default.asp), [programiz](https://www.programiz.com/python-programming) or [pythontutorial](https://www.pythontutorial.net/)._

## Version Control with Git
> "The problem with git jokes is that everyone has their own version."
- Creating a repository using Git
- Cloning a Git repository:
  - [Secure your account with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
- Add, Commit and Push
- Pull, Fetch, Stash
- Fork, Pull Requests, Merges
- Reverts, Resets, Branches:
  - [Branching strategy](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy)

There are also many courses out there, like [codecademy](https://www.codecademy.com/learn/learn-git), [tutorialspoint](https://www.tutorialspoint.com/git/index.htm) or [w3schools](https://www.w3schools.com/git)

**Checkpoint #6**: Add your Reddit scraper codes in a GitHub repository and link it to Heroku. Now you can change your code and see the effects in realtime!

## Docker in Action
> What if we put Docker inside of Docker?
- [Why even bother with Docker?](https://medium.com/@kmdkhadeer/docker-get-started-9aa7ee662cea)
- [get-started](https://docs.docker.com/get-started/)
- Components in detail:
  - [docker-compose](https://docs.docker.com/compose/)
  - [Dockerfile](https://docs.docker.com/engine/reference/builder/)
  - [Manage sensitive data with Docker secrets](https://docs.docker.com/engine/swarm/secrets/)

**Checkpoint #7**: Dockerize your Reddit scraper bot and deploy it on Heroku (run it locally first, remember baby steps!).

_Final Note: Getting comfortable with Docker can take some time and practice. However, Docker is the gateway to MLOps which plays an important role in deploying Machine-Learning models!_
