# Machine Learning 101 Course - Andrew Ng 

DAY 1 ( 2019-07-05 )

## *Chapter 01 . What is Machine Learning*

### # What is AI?

when we visit the google we can see they sort the result from lot of visit to lower

when we see Friend's photo, we can search who i want to see in facebook or Photo book



### # Machine Learning

* Grew out of work in AI
* New capability for computers



### # Examples

- Database Mining
  - Large Datasets from growth of automation /  web.
- Application can't program by hand
  - hand writing recongition, NLP, Computer Vision
- Self-customizing programs



### # The Definiton of Machine Learning

* Lot of engineer try defined the Machine Learning but no one can
*  The Example that who Definition ML
  * Arthur Samuel : "Field of Study that gives computers the ability to learn without being explicitly programmed"
  * Tom Mitchell define 'Well-Posed Learning Problem' : "A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E."



#### Question [1]

Suppose your email program watches which emails you do or do not mark as spam, and based on that learns how to better filter spam. what is the task T in this setting?? 

hint : solve this question with the Definition that Tom Mitchell define

> 1. Classifiying emails as spam or not spam
> 2. Watching you label emails as spam or not spam
> 3. **The number( or fraction ) of emails correctly classified as spam / not spam**
> 4. None of the above - this is not a machine Learning problem



### * Read Part [ 1 ]

## What is Machine Learning?

Two definitions of Machine Learning are offered. Arthur Samuel described it as: "the field of study that gives computers the ability to learn without being explicitly programmed." This is an older, informal definition.

Tom Mitchell provides a more modern definition: "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."

Example: playing checkers.

E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.

In general, any machine learning problem can be assigned to one of two broad classifications:

Supervised learning and Unsupervised learning.



### # Machine Learning Algorithms:

* Supervised Learning
* Unsupervised Learning
* others : Reinforcement learning, recommender Systems.



<mark>Ng said : the most important thing is not teaching what it is but how advanced it</mark>



## *Chapter 02 . The Supervised Learning*

### # For?

when right answers given this Algorithm make more many answers!!

### # Regression Problem (회귀 문제)

:: Predict continuous valued output

### # Classification Problem (분류 문제)

:: Discrete valued output ( 0 or 1 // or countable types )



### # The Point of Machine Learning

:: more learn and make answer about infinity Feature

### # How?

:: Use SVM!!



### Question [ 2 ]

You’re running a company, and you want to develop learning algorithms to address each of two problems. Problem 1:You have a large inventory of identical items. You want to predict how many of these items will sell over the next 3 months.

Problem 2: You’d like software to examine individual customer accounts, and for each account decide if it has been hacked/compromised. Should you treat these as classification or as regression problems?

hint : check the definition of two problem!!

> 1. Treat both as classification problems.
> 2. Treat problem 1 as a classification problem, problem 2 as a regression problem.
> 3. **Treat problem 1 as a regression problem, problem 2 as a classification problem.**
> 4. Treat both as regression problems.



### * Read part [ 2 ]

## Supervised Learning

In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

**Example 1:**

Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.

We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

**Example 2**:

(a) Regression - Given a picture of a person, we have to predict their age on the basis of the given picture

(b) Classification - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.



## chapter 03. Unsupervised Learning

we don't know about what is this Data Set?? 

we just get "DATA SET"

<mark>Where Clustering or Unsupervised Learning in?</mark>

> 1. Organize computing clusters
> 2. Social Network Analysis
> 3. Market Segmentation
> 4. Astronomical data Analysis

### # ex ) Cocktail Party Problem

2 people speak same time to 2 Micro Phone that set in different distance

[W,s,v] = svd((repmat(sum(x.\*x, 1) , size(x,1), 1 ).\*x) \*x');



### # The Language OCTAVE!



### Question [ 3 ]

Of the following examples, which would you address using an unsupervised learning algorithm? (Check all that apply.)

> 1. Given email labeled as spam/not spam, learn a spam filter.
> 2. **Given a set of news articles found on the web, group them into sets of articles about the same stories.**
> 3. **Given a database of customer data, automatically discover market segments and group customers into different market segments.**
> 4. Given a dataset of patients diagnosed as either having diabetes or not, learn to classify new patients as having diabetes or not.



### * Read Part [ 3 ]

## Unsupervised Learning

Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.

With unsupervised learning there is no feedback based on the prediction results.

**Example:**

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a [cocktail party](https://en.wikipedia.org/wiki/Cocktail_party_effect)).







