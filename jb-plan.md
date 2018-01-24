
Title : Neuro Data Science
============================

key words: data-science, teaching, python, statistical toolbox, reproducible science, 
computational toolbox 

Syllabus:
-----------

Neuroscientists rely increasingly on data accessible online and on data science
procedures for their investigations. Data science now offers a key set of
tools and methods to efficiently analyse, visualize and interpret neuroscience
data. Concurrently, there is a growing concern in the life sciences that many
results produced are difficult or even impossible to reproduce. This is
referred to as the reproducibility crisis, which concerns most biomedical
fields ([F. Collin](https://www.nature.com/news/policy-nih-plans-to-enhance-reproducibility-1.14586) 2014).

This course will bring together computational and analytical tools and methods.
It will teach students how to best use the fundamentals of data science in
their daily work to produce reproducible results. We will take examples in
neuroimaging or imaging genetics, and see how to use computational tools,
statistical and machine learning techniques, and collaborative and open science
methodology to generate results that are statistically solid and
computationally reproducible. While a large part of this course is language
agnostic, we will teach and use python throughout the course and work on small
projects. 

The course will require that participants have some basic programming experience
and some notion of statistical analysis, but will be aimed at life scientists
(neurologists, psychiatrists, pyschologists, neuroscientists) who wish to
improve their research practices, or students who want an introduction to
data science with examples in neuroscience and neuroimaging. We will strive to avoid
the classic problem described in Figure 1.
 
Part I: Introduction
============================================

Introduction to the course: (1h)
---------------------------------
	- Let me know what you know 
	- Motivations
	- Objective
	- Content
	- Evaluation

Lesson 1: Epistemiolgy and lesson from the past (2h)
-----------------------------------------------------------------
	- A word on Popper (falsifiability)
	- A word on Kuhn  (what makes a scientific revolution)
	- Beyond Popper and Kuhn, lessons for today's neuroscience
	- Reproducibility in life science

Part II: The computational tools
============================================


Lesson 2: Computational Basics : shell and git (3h)
-----------------------------------------------------------------
	- Know your shell
	- Know your editor
	- Git: the model
		* Never lose anything 
		* How do I best collaborate with myself

Lesson 3: Computational Basics : python for programmers (3h)
-----------------------------------------------------------------
	- Python as a software glue
	- Python key data structures
	- Beyond simple python: class, decorators, getter/setters, etc

Lesson 4: Git distributed and collaboratif (3h)
-----------------------------------------------------------------
	- Git distributed
	- Github and other web based infrastructures for git
	- Git and data: introducing git-annex (and git-lfs)
	- Handling data, the future: Datalad

Lesson 5: Scientific python ecosystem (3h)
-----------------------------------------------------------------
	- The basics: Numpy, Scipy, Matplotlib 
	- Python random generator
	- Pandas
	- Seaborn and others
	- unit testing framework

Lesson 6: Docker and dockerhub (3h)
-----------------------------------------------------------------
	- Containers versus virtual machines
	- Docker and singularity 
	- Neurodocker 

Part III: Data analysis : concept and tools
============================================

Lesson 7: Statistical tools - the basics (3h)
-----------------------------------------------------------------
	- The Sampling questions
	- Distributions, Cumulative density functions (and survival functions), 
	- Null hypothesis significance testing paradigm, notion of effect size

Lesson 8: Statistical tools - inference and power (3h)
-----------------------------------------------------------------
	- NHST: non parametric methods, permutations
	- p-values: the controversies
	- power analysis by example 
	- Scipy stats module 

Lesson 9: General Linear Model (3h) and the SVD 
-----------------------------------------------------------------
	- The GLM: estimation and testing 
	- Correlated regressors
	- The SVD
	- Statsmodels

Lesson 10: The Bayesian framework (3h)
-----------------------------------------------------------------
	- Bayes basics 
	- Positive predictive values
	- Introduction to pyMC3 / python tools for Bayesian analyses

Lesson 11: Model comparison, cross validation, Sampling techniques  (3h)
-----------------------------------------------------------------
	- Notion of model validation and model comparison
	- Bootstrap - Jacknife
	- Cross-validation
	- Distributing computation 
 
Lesson 12: Machine learning (3h)
-----------------------------------------------------------------
	- Prediction and prediction error
	- SVM - Random Forest
	- An introduction to deep learning
	- scikit-learn and ni-learn 

Lesson 13: Recap and miscellaneous
-----------------------------------------------------------------
	- Reproducibility best practices
	- Collaboration best practices
	- Improving and teaching this module 

![How to draw an owl?][owl] 

[owl]:draw-an-owl.jpg "How to avoid this issue?"

==============================================================================



Lesson ??: missing stuff (3h)
-----------------------------------------------------------------
	- jupyter notebook  
	- Continuous Integration
	- AWS S3 / U2 
	- web communication / backend DB



