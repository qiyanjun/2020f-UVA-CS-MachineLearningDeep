---
layout: post
title: Introduction
lecture: S0-Intro
lectureVersion: current
extraContent: 
notes: <a href="http://cs231n.github.io/python-numpy-tutorial/"> Numpy Tutorial </a>
video: <a href="https://www.youtube.com/watch?v=4tGQiWXlsLM">M1</a> / <a href="https://youtu.be/0wEjstWjE_0">M2</a> / <a href="https://youtu.be/LkPmTGw1jqo">M3</a> / <a href="https://youtu.be/UGqLe7Rf9aU">M4</a>  
tags:
- 1Basic
---

# UVA CS 4774:Machine Learning Lecture 1: Introduction

# Dr. Yanjun Qi

University of Virginia 
Department of Computer Science

# Roadmap

<span style="color:#4D39C5">Course Logistics</span>

History and Now

A Rough Plan of Course Content

ATT:

I will video\-record only when I talk/teach

One TA will act as coordinator\, please type in questions via Chats / He will read out and ask me to answer

Each session will include multiple small modules \-\-\- each about 20mins \(each into a different recorded video\)

# Welcome

* Course Website:
* https://qiyanjun\.github\.io/2020f\-UVA\-CS\-MachineLearningDeep/

We focus on learning fundamental principles\, algorithm design and deep learning methods and applications\.

Yanjun Qi / UVA CS

# Objective

* To help students get able to build simple machine learning tools
  * \(not just a tool user\!\!\!\)
* Key Results:
  * Able to build a few simple machine learning methods from scratch
  * Able to understand a few complex machine learning methods at the source code level
  * To re\-produce / or invent one cutting\-edge machine learning application / algorithm for GOOD USE

Dr\. Yanjun Qi / UVA CS

# Course Staff

* Instructor: Prof\.YanjunQi
  * QI: /chee/
  * You can call me “professor”\, “professor Qi”;
  * I have been teaching Graduate\-level and Under\-Level Machine Learning course for years\!
  * My research is about machine learning
* TA and Office Hour information @CourseWeb

Yanjun Qi / UVA CS

# Course Material

* Text books for this class is:
  * NONE
  * Multiple good reference books are shared viaCourseWeb
* My slides – __if it is not mentioned in my slides\, it is not an official topic of the course__
* Your UVACollabfor Assignments and Project
* Google Forms for Quizzes

Yanjun Qi / UVA CS

# Course Background Needed

* __Background Needed__
  * Calculus\, Basic linear algebra\,
  * Basic probability and Basic Algorithm
  * Statistics is recommended\.
  * <span style="color:#FF0000">Python</span> is required for all programming assignments

Yanjun Qi / UVA CS

# Assignments

Assignments \(50%\, with five assignments\)

See policy inhttps://qiyanjun\.github\.io/2020f\-UVA\-CS\-MachineLearningDeep//About/

Yanjun Qi / UVA CS

# Quiz

* Class quizzes \(20%\): Each takes 10 mins via google form;
  * We will have a total of 12 quizzes
  * Your top 10 scored will be counted into 20%
  * Within Our Zoom Synchronous sessions
  * Will be close book \(please follow honor code\!\)
* See policy inhttps://qiyanjun\.github\.io/2020f\-UVA\-CS\-MachineLearningDeep//About/

Yanjun Qi / UVA CS

# Course Project

Final project \(30%\):  Three potential types:

\- a\. To produce one machine learning project on cutting\-edge data applications with health or social impacts

\- b\. Survey and benchmark multiplepytorch\(ortensorflowif you prefer\) libraries with a shared goal

\- c\. To Reproduce a cutting\-edge machine learning paper\, for instance from Top Venues' most cited recent papers

See policy inhttps://qiyanjun\.github\.io/2020f\-UVA\-CS\-MachineLearningDeep//About/

Yanjun Qi / UVA CS

# Thank you

# Roadmap

Course Logistics

<span style="color:#3E2EB0">History and Now</span>

A Rough Plan of Course Content

# Artificial Intelligence Today

DeepMind \(Google\)

_Impact: Good and Bad?_

Economic\, cultural\, social\,health… endless disruption

Labor \- McKinsey > _50%_ of jobs automated

Martin Ford\,Rise of the Robots

Elon Musk\, artificial intelligence\.\.\.existential threat

Image credits:sibaraki@acm\.org

# Artificial intelligence (AI)

The study of computer systems that attempt to model and apply the intelligence of the human mind\.

  * What defines “intelligence”?
  * Why is it that we assume humans are intelligent?
  * Are monkeys intelligent?  Dogs?  Ants?  Pine trees?

# How to build more intelligent computer / machine ?

  * <span style="color:#000000">Able to</span>  <span style="color:#3E2EB0">perceive</span>  <span style="color:#000000">the world\,</span>
    * <span style="color:#000000">e\.g\.\, objective recognition\, speech recognition\,</span>  <span style="color:#000000">…</span>
  * <span style="color:#000000">Able to</span>  <span style="color:#3E2EB0">understand</span>  <span style="color:#000000">the world\,</span>
    * <span style="color:#000000">e\.g\.\, machine translation\, text semantic understanding</span>
  * <span style="color:#000000">Able to</span>  <span style="color:#3E2EB0">Interact</span>  <span style="color:#000000">with the world\,</span>
    * <span style="color:#000000">e\.g\.\, AlphaGo\,</span>  <span style="color:#000000">AlphaZero</span>  <span style="color:#000000">\, self\-driving cars\,</span>  <span style="color:#000000">…</span>
  * <span style="color:#000000">Able to</span>  <span style="color:#3E2EB0">think / reason / learn</span>  <span style="color:#000000">\,</span>
    * <span style="color:#000000">e\.g\.\, learn to program programs\, learn to search</span>  <span style="color:#000000">deepNN</span>  <span style="color:#000000">architecture\,</span>  <span style="color:#000000">…</span>
  * <span style="color:#000000">Able to</span>  <span style="color:#3E2EB0">imagine</span>  <span style="color:#000000">/ to make</span>  <span style="color:#3E2EB0">analogy</span>  <span style="color:#000000">\,</span>
    * <span style="color:#000000">e\.g\.\, learn to draw with styles\,</span>  <span style="color:#000000">……</span>

History \( on a functional line\)

# History ( on a time line)

1950s~60s

2015

2016

2017

Rule / Knowledge based

__Classic ML like SVM__

ImageNet / Deep Learning Breakthroughs

CNN / RNN invented

Start / NN popular

# Early History

* In 1950 English mathematician <span style="color:#1C33F4">Alan Turing wrote a landmark paper titled “Computing Machinery and Intelligence”</span> that asked the question: <span style="color:#FF0000">“Can machines think?”</span>
* Further work came out of a <span style="color:#1C33F4">1956 workshop at Dartmouth sponsored by John McCarthy\.</span> In the proposal for that workshop\, he coined the phrase a “study of artificial intelligence”
* Expert systems \(70s\, 80s\)
  * A software system based the knowledge of human experts;
  * <span style="color:#3300FF"> __Rule\-based system__ </span>
  * processes rules to draw conclusions
  * Idea is to give AI systems lots of information to start with

Generative

Adversarial

Network \(GAN\)

Deep Reinforcement Learning

__1952\-1969 Enthusiasm:__ Lots of work on neural networks

__1990s:__ Convolutional neural network \(CNN\) and Recurrent neural network \(RNN\) were invented

Y\.LeCun\, L\.Bottou\, Y\.Bengio\, and P\. Haffner\, Gradient\-based learning applied to document recognition\, Proceedings of the IEEE 86\(11\): 2278–2324\, 1998\.

Adapt from From NIPS 2017 DL Trend Tutorial

# Deep Learning is Changing the World

Yanjun Qi / UVA CS

# Reason of Recent Deep Learning breakthroughs:

# Reason: Plenty of (Labeled) Data

<span style="color:#FF0000">Text</span> : trillions of words of English \+ other languages

<span style="color:#FF0000">Visual</span> : billions of images and videos

<span style="color:#FF0000">Audio:</span> thousands of hours of speech per day

<span style="color:#FF0000">User activity:</span> queries\, user page clicks\, map requests\,etc\,

<span style="color:#FF0000">Knowledge graph:</span> billions of labeled relational triplets

Genomics data:

Medical Imaging data:

Yanjun Qi / UVA CS

# Reason: Advanced Computer Architecture that fits DNNs

http://www\.nvidia\.com/content/events/geoInt2015/LBrown\_DL\.pdf

Yanjun Qi / UVA CS

# Reason: Data-Driven Machine Learning Algorithms and Platforms

* <span style="color:#FF0000">Inductive reasoning</span>
  * Generalizations from observed data to unseen data

Able toto build computer systems that can <span style="color:#1C33F4">learn and adapt from their experience</span>

<span style="color:#1C33F4">Well\-engineered software architectures</span> to build upon

Provide prediction <span style="color:#1C33F4">accuracy</span>

Create software that <span style="color:#1C33F4">improves over time</span>

<span style="color:#C00000"> __Learn f\(x\) to Generalize to Unseen X’__ </span>

_Traditional Programming_

_Machine Learning_

Algorithm / Model

Math / Statistics / Information Theory / …

Final Solution should be at the intersection

<span style="color:#3E2EB0">ML \+ Digital Data Platforms: Unprecedented Era</span>

<span style="color:#3E2EB0">Hyper time compression</span>  <span style="color:#3E2EB0">new disruptive innovations</span>

  * <span style="color:#3E2EB0">Extreme convergence</span>  <span style="color:#3E2EB0">of multiple domains</span>

  * <span style="color:#3E2EB0">Exponential accelerating automation</span>  <span style="color:#3E2EB0">– smart sensors and the billion IoT devices</span>

  * <span style="color:#3E2EB0">Universal connectivity linked</span>  <span style="color:#3E2EB0">by a digital mesh</span>

Image credits:sibaraki@acm\.org

<span style="color:#3E2EB0">We always overestimate the change</span>

<span style="color:#3E2EB0">that will occur in the next two years</span>

<span style="color:#3E2EB0">and underestimate the change</span>

<span style="color:#3E2EB0">that will occur in the next ten\.</span>

<span style="color:#3E2EB0">\- Bill Gates\, The Road Ahead\, 1996</span>

# General Lessons for Excellence

Good breath in fundamentals is key

Strength in particular targeted topics help standing out

# Highly Recommend Two Extra-curriculum books:

1\. Book: By Dr\.Domingos: Master Algorithm

So How Do Computers Discover New Knowledge?

1\. __Symbolists__ \-\-Fill in gaps in existing knowledge

2\. __Connectionists__ \-\-Emulate the brain

3\. __Evolutionists__ \-\-Simulate evolution

4\. __Bayesians__ \-\-Systematically reduce uncertainty

5\. __Analogizers__ \-\-Notice similarities between old and new

SRC: Pedro Domingos ACM Webinar Nov 2015http://learning\.acm\.org/multimedia\.cfm

* 2\. Book: _Homo Deus\- A Brief History of Tomorrow_
  * https://www\.goodreads\.com/book/show/31138556\-homo\-deus
  * “Homo Deus explores the projects\, dreams and nightmares that will shape the twenty\-first century—from overcoming death to creating artificial life\. It asks the fundamental questions: Where do we go from here? And how will we protect this fragile world from our own destructive powers? This is the next stage of evolution\. This is Homo Deus\.””

Dr\. Yanjun Qi / UVA CS

# Thank you

# Roadmap

Course Logistics

History and Now

<span style="color:#4D39C5">A Rough Plan of Course Content</span>

# My Teaching Guide: Bloom’s Taxonomy on Cognitive Learning

Yanjun Qi / UVA CS

# BASICS OF MACHINE LEARNING

“The goal of machine learning is to build computer systems that can <span style="color:#0000FF">learn and adapt from their experience\.</span> ”– TomDietterich

<span style="color:#0000CC">“</span>  <span style="color:#0000CC">Experience</span>  <span style="color:#0000CC">”</span> in the form of available <span style="color:#0000CC">data</span>  <span style="color:#0000CC">examples</span> \(also called as instances\, samples\)

Available examples are described with properties <span style="color:#0000CC">\(data points in feature space X\)</span>

Yanjun Qi / UVA CS

_Traditional Programming_

_Machine Learning \(training phase\)_

Program

/ Model  f\(\)

Dr\. Yanjun Qi / UVA CS

# e.g. SUPERVISED LEARNING

I believe that this book is not at all helpful since it does not explain thoroughly the material \. it just provides the reader with tables and calculations that sometimes are not easily understood …

Find function to map <span style="color:#0000FF">input</span> space  X  to <span style="color:#0000FF">output</span> space Y

So that the <span style="color:#0000FF">difference</span> between <span style="color:#0000EB">y and f\(x\)</span> of each example x is small\.

<span style="color:#FF0000">Output Y:    \{1 / Yes \,  \-1 / No \}</span>

<span style="color:#FF0000">e\.g\.</span>  <span style="color:#FF0000">Is this a positive product review ?</span>

Yanjun Qi / UVA CS

<span style="color:#FF0000">Input X : e\.g\. a piece of English text</span>

# SUPERVISED Linear Binary Classifier

Now let us check out a <span style="color:#3366FF">VERY SIMPLE</span> case of

f\(x\, <span style="color:#00CC00">w\,b</span> \) = sign\( <span style="color:#00CC00">w</span>  <span style="color:#00CC00">T</span> x\+ <span style="color:#00CC00">b</span> \)

<span style="color:#0000FF">e\.g\.: Binary</span> y <span style="color:#0000FF">/ Linear</span> f <span style="color:#0000FF">/ X as R</span>  <span style="color:#0000FF">2</span>

Yanjun Qi / UVA CS

<span style="color:#D800D8">SUPERVISED</span> Linear Binary Classifier

<span style="color:#FF0000">“Predict Class = \+1” zone</span>

f\(x\, <span style="color:#00CC00">w\,b</span> \) = sign\( <span style="color:#00CC00">w</span>  <span style="color:#00CC00">T</span> x\+ <span style="color:#00CC00">b</span> \)

<span style="color:#FF0000">“Predict Class = \-1” zone</span>

denotes \+1 point

denotes \-1 point

Courtesy slide from Prof\. Andrew Moore’s tutorial

Yanjun Qi / UVA CS

<span style="color:#D800D8">SUPERVISED</span> Linear Binary Classifier

<span style="color:#FF0000">“Predict Class = \+1” zone</span>

f\(x\, <span style="color:#00CC00">w\,b</span> \) = sign\( <span style="color:#00CC00">w</span>  <span style="color:#00CC00">T</span> x\+ <span style="color:#00CC00">b</span> \)

<span style="color:#FF0000">“Predict Class = \-1” zone</span>

denotes \+1 point

denotes \-1 point

denotes future points

Courtesy slide from Prof\. Andrew Moore’s tutorial

Yanjun Qi / UVA CS

# Two Modes of Machine Learning

Predicted

Output

Consists of <span style="color:#FF0000"> __input__ </span> \- <span style="color:#0000FF"> __output__ </span> pairs

Dr\. Yanjun Qi / UVA CS

_Traditional Programming_

_Machine Learning \(training phase\)_

Program

/ Model  f\(\)

Dr\. Yanjun Qi / UVA CS

* <span style="color:#0000CC">Training</span> \(i\.e\. learning parameters <span style="color:#00CC00">w\,b</span> \)
  * <span style="color:#FF0000">Training set</span>  <span style="color:#0D0D0D">includes</span>
    * <span style="color:#0D0D0D">available examples</span>  <span style="color:#FF0000">x</span>  <span style="color:#FF0000">1</span>  <span style="color:#FF0000">\,…\,</span>  <span style="color:#FF0000">x</span>  <span style="color:#FF0000">L</span>
    * <span style="color:#0D0D0D">available corresponding labels</span>  <span style="color:#FF0000">y</span>  <span style="color:#FF0000">1</span>  <span style="color:#FF0000">\,…\,</span>  <span style="color:#FF0000">y</span>  <span style="color:#FF0000">L</span>
  * Find <span style="color:#FF0000">\(</span>  <span style="color:#00CC00">w\,b</span>  <span style="color:#FF0000">\) by minimizing loss / Cost</span> function L\(\)
    * \(i\.e\. difference betweeny and f\(x\) on available examples <span style="color:#FF0000">in training set</span> \)

Yanjun Qi / UVA CS

* <span style="color:#0000CC">Loss function</span>
  * e\.g\. hinge loss for binary classification task
* <span style="color:#0000CC">Regularization</span>
  * E\.g\. additional information added
  * on loss function to control f

Yanjun Qi / UVA CS

* <span style="color:#0000CC">Testing</span> \(i\.e\. evaluating performance on“ <span style="color:#C700C7">future</span> ”points\)
  * Difference between true <span style="color:#FF0000">y</span>  <span style="color:#FF0000">?</span> and the <span style="color:#FF0000">predicted</span>  <span style="color:#FF0000">f\(x</span>  <span style="color:#FF0000">?</span>  <span style="color:#FF0000">\)</span> on a set of  testing examples\(i\.e\. <span style="color:#FF0000">testing set</span> \)
  * Key:example <span style="color:#FF0000">x</span>  <span style="color:#FF0000">?</span> not in the training set
* <span style="color:#0000CC">Generalisation</span> : learn function / hypothesis from <span style="color:#DE2FFF">past data</span> in order to “explain”\, “predict”\, “model” or “control” <span style="color:#DE2FFF">new</span> data examples

Yanjun Qi / UVA CS

# A Typical Machine Learning Application’s Pipeline

<span style="color:#FFFFFF">A model to Perform Inference\, Prediction\,  Recognition</span>

e\.g\. Data Cleaning

<span style="color:#FFFFFF">Learn/ Select / Represent  Feature</span>

<span style="color:#FFFFFF">Low\-level sensing</span>

<span style="color:#FFFFFF">Learn / Search/ Optimization</span>

<span style="color:#0000CC">Generalisation</span> : learn function / hypothesis from <span style="color:#DE2FFF">past data</span> in order to “explain”\, “predict”\, “model” or “control” <span style="color:#DE2FFF">new</span> data examples

<span style="color:#FFFFFF">Score/ Loss/ Evaluation</span>

<span style="color:#FFFFFF">Label Collection</span>

Dr\. Yanjun Qi / UVA CS

# When to use Machine Learning (Adapt to / learn from data) ?

  * 1\. <span style="color:#0000EB">Extract knowledge</span> from data
      * Relationships and correlations can be hidden within large amounts of data
      * The amount of knowledge available about certain tasks is simply too large for explicit encoding \(e\.g\. rules\) by humans
  * 2\. Learn tasks that are <span style="color:#0000EB">difficult to formalise</span>
      * Hardto be defined well\, except by examples\, e\.g\.\, face recognition
  * 3\. Create software that <span style="color:#0000EB">improves over time</span>
      * New knowledge is constantly being discovered\.
      * Rule or human encoding\-based system is difficult to continuously re\-design“by hand”\.

Yanjun Qi / UVA CS

_Machine Learning in a Nutshell_

ML grew out of work in AI

Optimize a performance criterion using example data or past experience\,

Aiming to generalize to unseen data

Search/Optimization

Models\, Parameters

Dr\. Yanjun Qi / UVA CS

# What we have covered

Dr\. Yanjun Qi / UVA CS

# What we will cover

Dr\. Yanjun Qi / UVA CS

Yanjun Qi / UVA CS

_Machine Learning in a Nutshell_

ML grew out of work in AI

Optimize a performance criterion using example data or past experience\,

Aiming to generalize to unseen data

Search/Optimization

Models\, Parameters

Dr\. Yanjun Qi / UVA CS

# A Dataset

__Data__  _/points/instances/examples/samples/records_ : <span style="color:#0000FF">\[ rows \]</span>

__Features__  _/attributes/dimensions/independent variables/covariates/predictors/_  _regressors_ : <span style="color:#0000FF">\[ columns\, except the last\]</span>

__Target__  _/outcome/response/label/dependent variable_ : special column to be predicted <span style="color:#0000FF">\[ last column \]</span>

Dr\. Yanjun Qi /

# Main Types of Columns

<span style="color:#0000FF"> _Continuous_ </span> : a real number\, for example\, weight

<span style="color:#0000FF"> _Discrete_ </span>  <span style="color:#0000FF">:</span> a symbol\, like “Good” or “Bad”

Dr\. Yanjun Qi /

Dr\. Yanjun Qi / UVA CS

_Machine Learning in a Nutshell_

ML grew out of work in AI

Optimize a performance criterion using example data or past experience\,

Aiming to generalize to unseen data

Search/Optimization

Models\, Parameters

Dr\. Yanjun Qi / UVA CS

# e.g. SUPERVISED Classification

Training dataset consists of <span style="color:#FF0000">input</span> \- <span style="color:#0000FF">output</span> pairs

e\.g\. target Y can be a <span style="color:#0000FF">discrete</span> target variable

Dr\. Yanjun Qi /

# e.g. SUPERVISED Regression

Training dataset consists of <span style="color:#FF0000">input</span> \- <span style="color:#0000FF">output</span> pairs

e\.g\. target Y can be a <span style="color:#0000FF">continuous</span> target variable

Dr\. Yanjun Qi /

_Machine Learning in a Nutshell_

ML grew out of work in AI

Optimize a performance criterion using example data or past experience\,

Aiming to generalize to unseen data

Search/Optimization

Models\, Parameters

Dr\. Yanjun Qi / UVA CS

* <span style="color:#0000CC">Training</span> \(i\.e\. learning parameters <span style="color:#00CC00">w\,b</span> \)
  * <span style="color:#FF0000">Training set</span>  <span style="color:#0D0D0D">includes</span>
    * <span style="color:#0D0D0D">available examples</span>  <span style="color:#FF0000">x</span>  <span style="color:#FF0000">1</span>  <span style="color:#FF0000">\,…\,</span>  <span style="color:#FF0000">x</span>  <span style="color:#FF0000">L</span>
    * <span style="color:#0D0D0D">available corresponding labels</span>  <span style="color:#FF0000">y</span>  <span style="color:#FF0000">1</span>  <span style="color:#FF0000">\,…\,</span>  <span style="color:#FF0000">y</span>  <span style="color:#FF0000">L</span>
  * Find <span style="color:#FF0000">\(</span>  <span style="color:#00CC00">w\,b</span>  <span style="color:#FF0000">\) by minimizing loss</span>
    * \(i\.e\. difference betweeny and f\(x\) on available examples <span style="color:#FF0000">in training set</span> \)

Yanjun Qi / UVA CS

* <span style="color:#0000CC">Loss function</span>
  * e\.g\. hinge loss for binary classification task
* <span style="color:#0000CC">Regularization</span>
  * E\.g\. additional information added
  * on loss function to control f

Yanjun Qi / UVA CS

_Machine Learning in a Nutshell_

ML grew out of work in AI

Optimize a performance criterion using example data or past experience\,

Aiming to generalize to unseen data

Search/Optimization

Models\, Parameter\, Metric

Dr\. Yanjun Qi / UVA CS

# How to know the program works well: Measure Prediction Accuracy on Test Data

Training dataset consists of <span style="color:#FF0000">input</span> \- <span style="color:#0000FF">output</span> pairs

<span style="color:#FF0000">Measure Loss on pair</span>  <span style="color:#FF0000"> Error</span>  <span style="color:#FF0000">\( f\(x</span>  <span style="color:#FF0000">?</span>  <span style="color:#FF0000">\)\,  y</span>  <span style="color:#FF0000">?</span>  <span style="color:#FF0000">\)</span>

Dr\. Yanjun Qi / UVA CS

# More Metrics: e.g., ML and AI  Research @ UVA CS

__Human Centric Machine Intelligence__

__Understand Human__

__Be Communicative__

__Model Human Intent__

__Interact with Human__

__Efficient & Fast__

__Theoretically Sound__

<span style="color:#0000FF">Nutshell for the simple Linear</span>  __Supervised Classifier__

<span style="color:#006600">Output Y is categorical</span>

__Linear Decision Boundary__

__Search/Optimization__

__Models\, Parameters\, Metrics__

__Many metric to measure classification on future points__

Dr\. Yanjun Qi / UVA CS

<span style="color:#D800D8">SUPERVISED</span> Linear Binary Classifier

<span style="color:#FF0000">“Predict Class = \+1” zone</span>

f\(x\, <span style="color:#00CC00">w\,b</span> \) = sign\( <span style="color:#00CC00">w</span>  <span style="color:#00CC00">T</span> x\+ <span style="color:#00CC00">b</span> \)

<span style="color:#FF0000">“Predict Class = \-1” zone</span>

denotes \+1 point

denotes \-1 point

denotes future points

Courtesy slide from Prof\. Andrew Moore’s tutorial

Yanjun Qi / UVA CS

# Rough Sectioning of this Course

1\. Basic Supervised Regression \+ Tabular Data

2\. Basic Deep Learning \+ 2D Imaging Data

3\. Advanced Supervised learning \+ Tabular Data

4\. Generative and Deep \+ 1D Sequence Text Data

5\. Not Supervised

Yanjun Qi / UVA CS

Yanjun Qi / UVA CS

Yanjun Qi / UVA CS

Yanjun Qi / UVA CS

# Thank you

# References

Prof\. Andrew Moore’s tutorials

Prof\. Raymond J\. Mooney’s slides

Prof\. Alexander Gray’s slides

Prof\. Eric Xing’s slides

http://scikit\-learn\.org/

Hastie\, Trevor\, et al\. The elements of statistical learning\. Vol\. 2\. No\. 1\. New York: Springer\, 2009\.

Prof\. M\.A\.Papalaskar’sslides

Yanjun Qi / UVA CS

