## SF DAT15 Course Repository

Course materials for [General Assembly's Data Science course](https://generalassemb.ly/education/data-science/san-francisco/) in San Francisco, DC (6/15/15 - 8/26/15).

**Instructors:** Sinan Ozdemir (who is awesome)

**Teaching Assistants:**
Liam Foley, Patrick Foley, and Ramesh Sampath (who are all way more awesome)

**Office hours:** All will be held in the student center at GA, 225 Bush Street

* Monday 5:15-6:15pm
* Tuesday 6:30-8:30pm
* Wednesday 5:15-6:15pm
* Friday 12:30-2:30pm
* Saturday 10:00am-12:00pm

**[Course Project information](project.md)**

Monday | Wednesday
--- | ---
6/15: [Introduction / Expectations / Git Intro](#class-1-introduction--expectations--git-intro) | 6/17: [Python](#class-2-python)
6/22: [Data Science Workflow / Pandas](#class-3-data-science-workflow--pandas) | 6/24: [More Pandas](#class-4---more-pandas)
6/29: [Intro to ML / Numpy / KNN](#class-5---intro-to-ml--numpy--knn) | 7/1: Scikit-learn / Model Evaluation<br>**Project Milestone:** Question and Data Set<br> **HW** Homework 1 Due
7/6: Linear Regression | 7/8: Logistic Regression
7/13: Working on a Data Problem | 7/15: Clustering
7/20: Natural Language Processing| 7/22: Naive Bayes <br>**Milestone:** First Draft Due
7/27: Decision Trees | 7/29:Ensembling Techniques <br>**Milestone:** Peer Review Due
8/3: Recommendation Engines | 8/5: Databases / MapReduce
8/10: TBD | 8/17: TBD| 8/12: TBD
8/17: TBD | 8/17: TBD| 8/19: TBD
8/24: Projects | 8/26: Projects


### Installation and Setup
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SF\_DAT\_15 team" and add your photo!

### Resources
* [PEP 8 - Style Guide for Python](http://www.python.org/dev/peps/pep-0008)

### Class 1: Introduction / Expectations / Git Intro
* Introduction to General Assembly
* Course overview: our philosophy and expectations ([slides](slides/01_course_overview.pdf))
* Git overview: ([slides](slides/01_git_github.pdf))
* Tools: check for proper setup of Git, Anaconda, overview of Slack

**Homework:**

* Resolve any installation issues before next class.
* Make sure you have a github profile and created a repo called "SF_DAT_15"
* Clone the class repo (this one!)
* Review this [code](code/00_python_refresher.py) for a recap of some Python basics.

**Optional:**

* Read [Analyzing the Analyzers](http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/Analyzing_the_Analyzers.pdf) for a useful look at the different types of data scientists.
* Look over Data science overview ([slides](slides/01_course_overview.pdf))
* Read about some [Markdown Techniques](http://daringfireball.net/projects/markdown/syntax)

### Class 2: Python
* Brief overview of Python environments: Python interpreter, IPython interpreter, Spyder, Rodeo
* Python quiz ([code](code/02_python_quiz.py))
* Check out some iPython Notebooks!
* Working with data in Python in Spyder
    * Today's data is brought to you by Nate Silver's blog, [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/alcohol-consumption)
    * and also from the [Open Weather Data Project](http://openweathermap.org/) They have a great API!!
    * Reading, writing, and graphing oh my! in Python ([code](code/02_files_and_weather.py))
* [Lab](code/02_files_and_weather_lab.py) on files and API usage

**Homework:**

* Finish the [Python exercise](code/02_files_and_weather_lab.py) 
* Read through the [project page](project.md) in detail.
* Review a few [projects from past Data Science courses](https://github.com/justmarkham/DAT-project-examples) to get a sense of the variety and scope of student projects.

**Optional:**

* If you need more practice with Python, review the "Python Overview" section of [A Crash Course in Python](http://nbviewer.ipython.org/gist/rpmuller/5920182), work through some of [Codecademy's Python course](http://www.codecademy.com/en/tracks/python), or work through [Google's Python Class](https://developers.google.com/edu/python/) and its exercises.
* For more project inspiration, browse the [student projects](http://cs229.stanford.edu/projects2013.html) from Andrew Ng's [Machine Learning course](http://cs229.stanford.edu/) at Stanford.

**Resources:**

* [Online Python Tutor](http://pythontutor.com/) is useful for visualizing (and debugging) your code.

### Class 3: Data Science Workflow / Pandas

**Agenda**

* Slides on the Data Science workflow [here](slides/03_intro_to_ds.pdf)
	* Data Science Workflow
* Intro to Pandas walkthrough [here](code/03_pandas.py)
	* I will give you semi-cleaned data allowing us to work on step 3 of the data science workflow
	* Pandas is an excellent tool for exploratory data analysis
	* It allows us to easily manipulate, graph, and visualize basic statistics and elements of our data
	* [Pandas Lab!](code/03_pandas_lab.py)


**Homework**

* Begin thinking about potential projects that you'd want to work on. Consider the problems discussed in class today (we will see more next time and next Monday as well)
	* Do you want a predictive model?
	* Do you want to cluster similar objects (like words or other)?

**Resources:**

* Pandas
	 * [Split-Apply-Combine](http://i.imgur.com/yjNkiwL.png) pattern
    * Simple examples of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining)
    * Check out this excellent example of [data wrangling and exploration in Pandas](http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_04_wrangling.ipynb)
	    * For an extra challenge, try copying over the code into your own .py file
	* To learn more Pandas, review this [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)
    * For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.

    
    
### Class 4 - More Pandas

#### Agenda
* Class code on Pandas [here](code/04_pandas_2.py)
* We will work with 3 different data sets today:
	* the UFO dataset (as scraped from the [reporting website](http://www.nuforc.org/webreports.html)	
	* Fisher's Iris Dataset (as cleaned from a [machine learning repository](https://archive.ics.uci.edu/ml/datasets/Iris)
	* A dataset of (nearly) every FIFA goal ever scored (as scraped from the website)
* Pandas Lab! [here](code/04_pandas_2_lab.py)
	
	
####Homework
* Please review the [readme](hw/HW1-README.md) for the first homework. It is due NEXT Wednesday (7/1/2015)
* The one-pager for your project is also due. Please see [project guidelines](project.md)
	
	
### Class 5 - Intro to ML / Numpy / KNN

####Agenda

* Intro to numpy [code](code/05_numpy.py)
	* Numerical Python, code adapted from tutorial [here](http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf)
	* Special attention to the idea of the np.array
* Intro to Machine Learning and KNN [slides](slides/05_ml_knn.pdf)
	* Supervised vs Unsupervised Learning
	* Regression vs. Classification
* Iris pre-work [code](code/05_iris_prework.py) and [code solutions](code/05_iris_prework_solutions.py)
	* Using numpy to investigate the iris dataset further
	* Understanding how humans learn so that we can teach the machine!
* [Lab](code/05_knn.py) to create our own KNN model


####Homework
* The one page project milestone as well as the pandas homework!
* Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to discuss it in class on Wednesday. (You can ignore sections 4.2 and 4.3.) Here are some questions to think about while you read:
    * In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
    * In the interactive visualization, try using different values for K across different sets of training data. What value of K do you think is "best"? How do you define "best"?
    * In the visualization, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
    * How does the choice of K affect model bias? How about variance?
    * As you experiment with K and generate new training data, how can you "see" high versus low variance? How can you "see" high versus low bias?
    * Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
    * Does a high value for K cause over-fitting or under-fitting?

    
**Resources:**

* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)

	
	
	### Class 6: scikit-learn, Model Evaluation Procedures
* Introduction to scikit-learn with iris data ([code](code/06_sklearn_knn.py))
* Exploring the scikit-learn documentation: [user guide](http://scikit-learn.org/stable/modules/neighbors.html), [module reference](http://scikit-learn.org/stable/modules/classes.html#module-sklearn.neighbors), [class documentation](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
* Discuss the [article](http://scott.fortmann-roe.com/docs/BiasVariance.html) on the bias-variance tradeoff
* Look as some [code](code/06_bias_variance.py) on the bias variace tradeoff
	* To run this, I use a module called "seaborn" 
	* To install to anywhere in your terminal (git bash) and type in `sudo pip install seaborn`
* Model evaluation procedures ([slides](slides/06_model_evaluation_procedures.pdf), [code](code/06_model_evaluation_procedures.py))

**Homework:**

* Keep working on your project. Your [data exploration and analysis plan](project.md) is due in three weeks!

**Optional:**

* Practice what we learned in class today!
    * If you have gathered your project data already: Try using KNN for classification, and then evaluate your model. Don't worry about using all of your features, just focus on getting the end-to-end process working in scikit-learn. (Even if your project is regression instead of classification, you can easily convert a regression problem into a classification problem by converting numerical ranges into categories.)
    * If you don't yet have your project data: Pick a suitable dataset from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets.html), try using KNN for classification, and evaluate your model. The [Glass Identification Data Set](http://archive.ics.uci.edu/ml/datasets/Glass+Identification) is a good one to start with.
    * Either way, you can submit your commented code to your SF_DAT_15_WORK, and we'll give you feedback.

**Resources:**

* Here's a great [30-second explanation of overfitting](http://www.quora.com/What-is-an-intuitive-explanation-of-overfitting/answer/Jessica-Su).
* For more on today's topics, these videos from Hastie and Tibshirani are useful: [overfitting and train/test split](https://www.youtube.com/watch?v=_2ij6eaaSl0) (14 minutes), [cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes). (Note that they use the terminology "validation set" instead of "test set".)
    * Alternatively, read section 5.1 (12 pages) of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), which covers the same content as the videos.
* This video from Caltech's machine learning course presents an [excellent, simple example of the bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutes) that may help you to visualize bias and variance.


### Class 7: Linear Regression
* Linear regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/SF_DAT_15/blob/master/code/07_linear_regression.ipynb), [notebook code](code/07_linear_regression.py))

**Homework:**

* (Optional) questions [here](hw/optional/07_yelp_reviews.md) with the [Yelp reviews data](hw/optional/yelp.csv). It is not required but your next homework will involve this dataset so it would be helpful to take a look now!
* Watch these videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).

**Resources:**

* Setosa has an excellent [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), from which this lesson was adapted. Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* To learn more about Statsmodels and how to interpret the output, DataRobot has some decent posts on [simple linear regression](http://www.datarobot.com/blog/ordinary-least-squares-in-python/) and [multiple linear regression](http://www.datarobot.com/blog/multiple-regression-using-statsmodels/).
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* A major scientific journal recently banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".

### Class 8: Logistic Regression
* Logistic regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/SF_DAT_15/blob/master/code/08_logistic_regression.ipynb), [notebook code](code/08_logistic_regression_nb.py))
* Confusion matrix ([slides](slides/08_confusion_matrix.pdf))
* Exercise with Titanic data ([instructions](labs/08_titanic.md), [solution](code/08_titanic.py))

**Homework:**

* If you aren't yet comfortable with all of the confusion matrix terminology, watch Rahul Patwari's videos on [Intuitive sensitivity and specificity](https://www.youtube.com/watch?v=U4_3fditnWg) (9 minutes) and [The tradeoff between sensitivity and specificity](https://www.youtube.com/watch?v=vtYDyGGeQyo) (13 minutes).

**Resources:**

* To go deeper into logistic regression, read the first three sections of Chapter 4 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), or watch the [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutes) from that chapter.
* For a math-ier explanation of logistic regression, watch the first seven videos (71 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compiled by a student.
* For more on interpreting logistic regression coefficients, read this excellent [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm) by UCLA's IDRE and these [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) from the University of New Mexico.
* The scikit-learn documentation has a nice [explanation](http://scikit-learn.org/stable/modules/calibration.html) of what it means for a predicted probability to be calibrated.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a very nice comparison of four classifiers we cover in the course (logistic regression, decision trees, KNN, Naive Bayes) and one classifier we do not cover (Support Vector Machines).
* This [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) may be useful to you as a reference.


### Class 9: Working a Data Problem
* Today we will work on a real world data problem! Our [data](data/ZYX_prices.csv) is stock data over 7 months of a fictional company ZYX including twitter sentiment, volume and stock price. Our goal is to create a predictive model that predicts forward returns.

* Project overview ([slides](slides/09_GA_Stocks.pdf))
    * Be sure to read documentation thoroughly and ask questions! We may not have included all of the information you need...


### Class 10: Clustering and Visualization
* The [slides](slides/10_clustering.pdf) today will focus on our first look at unsupervised learning, K-Means Clustering!
* The [code](code/10_kmeans_class_exercise.py) for today focuses on two main examples:
    * We will investigate simple clustering using the iris data set.
    * We will take a look at a harder example, using Pandora songs as data. See [data](data/songs.csv). See code [here](code/10_analyze_pandora.py)
    * Checking out some of the limitations of K-Means Clutering [here](code/10_kmeans_limitations.py)

**Homework:**

* **HW2 and Project Milestone 2 are due in one week!**
* Download all of the NLTK collections.
   * In Python, use the following commands to bring up the download menu.
   * ```import nltk```
   * ```nltk.download()```
   * Choose "all".
   * Alternatively, just type ```nltk.download('all')```
* Install two new packages:  ```textblob``` and ```lda```.
   * Open a terminal or command prompt.
   * Type ```pip install textblob``` and ```pip install lda```.
   * 

**Resources:**

* [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) has a nice [chapter on cluster analysis](http://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf).
* The scikit-learn user guide has a nice [section on clustering](http://scikit-learn.org/stable/modules/clustering.html).

##Class 11: Natural Language Processing

**Agenda**

* Naural Language Processing is the science of turning words and sentences into data and numbers. Today we will be exploring techniques into this field
* [code](code/11_nlp.py) showing topics in NLP
* [lab](code/11_nlp_lab.py) analyzing tweets about the stock market


**Homework:**

* Read Paul Graham's [A Plan for Spam](http://www.paulgraham.com/spam.html) and be prepared to **discuss it in class on Wednesday**. Here are some questions to think about while you read:
    * Should a spam filter optimize for sensitivity or specificity, in Paul's opinion?
    * Before he tried the "statistical approach" to spam filtering, what was his approach?
    * How exactly does his statistical filtering system work?
    * What did Paul say were some of the benefits of the statistical approach?
    * How good was his prediction of the "spam of the future"?
* Below are the foundational topics upon which Wednesday's class will depend. Please review these materials before class:
    * **Confusion matrix:** [a good guide](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) roughly mirrors the lecture from class 10.
    * **Sensitivity and specificity:** Rahul Patwari has an [excellent video](https://www.youtube.com/watch?v=U4_3fditnWg&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (9 minutes).
    * **Basics of probability:** These [introductory slides](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) (from the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php)) are quite good and include integrated quizzes. Pay specific attention to these terms: probability, sample space, mutually exclusive, independent.
* You should definitely be working on your project! First draft and HW2 are both due Wednesday!!



##Class 12: Naive Bayes Classifier

Today we are going over advanced metrics for classification models and learning a brand new classification model called naive bayes!

**Agenda**

* Learn about ROC/AUC curves 
	* 	Slides [here](slides/12_classification_model_evaluation_metrics.pdf)
	* 	Code [here](code/12_confusion_roc.py)
* Learn the Naive Bayes Classifier 
	* 	Slides [here](slides/12_naive_bayes.pdf)
	* 	Code [here](code/12_naive_bayes.py)
	* In the code file above we will create our own spam classifier!


**Resources**

* Video on [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (12 minutes).
* My buddy's [blog post about the ROC video](http://www.dataschool.io/roc-curves-and-auc-explained/) includes the complete transcript and screenshots, in case you learn better by reading instead of watching.
