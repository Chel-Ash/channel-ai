---
layout: post
author: Chel
title: 9 Key Skills Every Deep Learning Practitioner Should Have (How many in the List do you Have?)
seo: deep learning deep learner data scientist skills for kaggle deep learning deep learning beginner skills for deep learner time management skills for data scientist.
description: Are there specific skills important in deep learning?. You shouldn't be surprised if you ask yourself this question. At a time or another, all budding deep learner ask themselves the same question. Are you a deep learner that flows with the tides that comes along with projects or are you set on building important skills that can make you more effective. In this article, I share 9 skills backed by stactics that guarantees exponential growth in your deep learning career.
img-src: ../assets\images\Blog\keyskills-dl
---

Are there specific skills important in deep learning?. You shouldn't be surprised if you ask yourself this question. At a time or another, all budding deep learner ask themselves the same question. Are you a deep learner that flows with the tides that comes along with projects or are you set on building important skills that can make you more effective. In this article, I share 9 skills backed by stactics that guarantees exponential growth in your deep learning career.

Skills are very important. In some cases, more important than others. They help us to go from zero to one in any new field of our interest. This being the case, why do we have learners that never really attain the peaks of their careers since the skills necessary for success is available for all to master?. Could it be that they are learning the <i>wrong</i> skills, learning it the wrong way or more critical, having a skewed perspective to skill gathering.

What then is the correct answer to successful skill gathering for deep learning?. The answer, as you might have guessed lies in the tactful combinations of several skills. Deep learning is a broad field encompassing a number of skills we need to succeed. There is no one-size-fits-all approach. But there are a few key skills you can pick up to ensure that you'll become a good deep learning practitioner.

The deep learning domain has shifted from being just a degree focused industry to a skill-based industry. Relying on just a degree to become a professional for whahtever sub-domain you choose is now a thing of the past.
Education lands you a job but skills scale up your prospects for growth. In this article, we are going to explore the most important skills required by a deep learner - professional or newcomer.


<h3>Overview</h3>

* Difference between a Deep Learner and a Deep Learning Practitioner
* Technical Skills in Deep Learning
	* Data Preparation
	* Data Visualization
	* Functional Programming with Python or R
	* Deep Learning Frameworks and Libraries
* Soft Skills in Deep Learning
	* Problem Solving
	* Communication


<h3>Difference Between a Deep Learner and a Deep Learning Practitioner</h3>

Often I have seen how people use the above 2 terms in a similar context. When people say "I want to be a Deep learner", In reality and in their heads they mean a Deep Learning Practitioner. So what's the difference between the two terms? Let's clarify.


A <b>Deep Learner</b> is more on the theoretical side, refers to a person that is of course enthusiastic about Deep learning as a topic and focuses on learning about it's concepts, theories and advancement from research papers, blogs and personal research. It is not necessarily a person that puts theory into practise aimed at developing models that solves a problem.

A good and popular example of a deep learner is <a href="https://en.wikipedia.org/wiki/Geoffrey_Hinton">Geoffery Hinton</a>. You can read about him on wikipedia but basically he is a computer scientist and professor at the University of Toronto. He has brought about tremendous advancement to the fields of Deep learning and computer vision through notable research papers and milestones.


A <b>Deep Learning Practitioner</b> focuses more on practical, technical, analysis, and data side of deep learning. They aim to solve real-world problems by applying Artificial Neural Networks on data to learn functions, build models and deploy for scalable predictions or use-cases. In short, they are the one that 


Also a good example in this case woule be Andrew Ng who is less focused on publishing papers(that ofcourse provides groundbreaking ideas which community can build on) and more on building solutions to real-world problems.

In the following sections, we are going to read about the key skills a Deep learning Practitioner should have


<h3>Technical Skills for Deep Learning Practitioners in 2020</h3>


<h4 style="color: blue;">Data Preparation</h4>

Preparing data may be the most important part of a predictive modeling project and the most time-consuming, although it seems to be the least discussed. The ability to prepare data effectively for use in your projects is as essential as the steps of training the models themselves. Although I know training can feel a lot more fun, afterall that's where you derive feelings of achievement and effort realised but don't be fooled to think training is a more important step than preparation. If we're all being honest, it takes way lesser effort at training stage and if you are using google colab for your work, then that's just unchallenging to say the least. 

Data preparation is usually the first skills needed in any deep learning project. The truth is that, lack of this important skill would reduce your pace in projects completion - every single time. Why? Data comes in different ways and formats. If you choose to rely on stack overflow every time for different and unique data arrangements, they wouldn't always deliver. You would end up spending valuable time that could have been channeled to advancement in your project. 

To give you a sense of the full context of what I mean by data preparation:

<i>Data preparation is the process of cleaning and transforming raw data prior to processing and analysis. It is an important step prior to processing and often involves reformatting data, making corrections to data and the combining of data sets to enrich data.</i> 

Random data are never collected in a format or situations that appeal to the analyst that work with them - Except in some specialised cases of course!

As a useful resource and getting started path for you, below is a list of the 4 areas that will get you started and productive with Data Preparation in Deep Learning:

* <b>Data Cleaning</b>: Identifying and correcting mistakes or errors in the data. It is hard to find a huge data collection that isn't messy - containing error and missing values. The easiest tool to use to combat this issue is <a href="">Pandas</a>. What's better is that you can install/import this python library into almost any environment - locally or online like colab. Pandas is a very easy library to master, for the purpose of data cleaning you can get helpful tutorials on their website. You would learn simple to advanced techniques of how to find missing vales, fill them or remove data rows with erros.
* <b>Feature Selection</b>: Identifying those input variables that are most relevant to the task. Preparing data for use means to polish it into a state that you can readily use in your modeling project. Feature Selection is step in the data preparation process where you filter and use specific data of your choice. 

	Recursive Feature Elimination, or RFE for short, is a popular feature selection algorithm. The scikit-learn Python machine learning library provides an implementation of RFE for machine learning. To get started, visit the scikit-learn docs for RFE where you can learn process that can be repeated for your projects.
* <b>Normalization</b>: Changing the scale or distribution of variables. One of the most popular techniques for scaling numerical data prior to modeling is normalization. Normalization scales each input variable separately to the range 0-1, which is the range for floating-point values where we have the most precision. This can be done very easily on tensorflow with keras and scikit-learn using the object MinMaxScaler, follow either link for <a href="https://www.tensorflow.org/tutorials/keras/classification#preprocess_the_data">tensorflow</a> or for <a href="http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html">scikit-learn</a>.
* <b>Data Transforms</b>: Transform Data into other Feature types including One-Hot and categorical Encoding . In some of your Deep Learning projects your models may require all input and output variables to exist in a transform different from it's source. This means that you would need to transform in a manner that is useable for training. Popular DL frameworks has libraries that make this process effortless. 
As before, practicing on tutorials covering this subject would build up the skills for future use. This resource on tensorflow explains the Different <a href="https://www.tensorflow.org/tutorials/structured_data/feature_columns">Feature Types</a> and how to convert/map your values to a specific type. scikit-learn also has a similar tutorial covering <a href="https://scikit-learn.org/stable/auto_examples/compose/plot_column_transformer_mixed_types.html?highlight=feature%20types">Column Transformer with Mixed Types</a>. depending on the platform you use up till now, make a choice


<h4 style="color: blue;">Data Visualization</h4>

Data is visualized in every industry in the 21st century.Data visualization is the act of taking information (data) and placing it into a visual context, such as a map, charts and graph. Data visualizations make big and small data easier for the human brain to understand, and visualization also makes it easier to detect patterns, trends, and outliers in groups of data. Usually, visualization makes it easier to understand the dataset you are working on and to work out the necessary steps it would take you for modeling.

In Python, there are libraries that are widely used for visualization like <a href="https://matplotlib.org/">Matplotlib</a>. To use this tool effectively for various data types and sizes, you would need learn how it works form tutorials you can find on the official page.

Matplotlib is a great tool when you just want to visualize data on a notebook conveniently but for more interactive displays and plots, some more platforms should be used:

* <a href="https://www.tableau.com/">Tableau</a>: By far the most popular, Tableau is a visual analytics platform transforming the way we use data to solve problems
<img src="https://www.tableau.com/themes/custom/tableau_www/logo.png">

* <a href="https://powerbi.microsoft.com/en-us/">Power BI</a>: Power BI is a business analytics service by Microsoft. It aims to provide interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards. To use it for Deep Learning and Machine Learning, you would need to import a few libraries like PyCaret. To get stated in this, follow this guide by towardsdatascience <a href="https://towardsdatascience.com/machine-learning-in-power-bi-using-pycaret-34307f09394a">Machine Learning in PowerBI using PyCaret</a>
<img src="">


<h4 style="color: blue;">Functional Programming with Python</h4>
In Deep Learning fields, the process of cleaning, preparing, processing, visualizing and others usually needs you to have intermediate to advanced python skills for writing functions that can execute multiple steps at once therby saving time. For example: You want to build an image classify that differentiates between horses and humans and returns the correct answer. The dataset available for training happened to be coupled together i.e the both horses and humans pictures are in the same folder. Luckily, the names of the files are correctly named as either horse/humans. You know you can use naming as a way to separate the files into four folders: train_horses, train_humans, test_horses and test_humans. I write this example from experience. I knew python way back then, but really just the beginner side of it. There are a few libraries you need to accomplish that task. that's why Python or R language is a must have for Deep Learning, else u would waste valuable time searching online for a solution. Python is one of the easiest languages to learn and there are hundreds of sites you can learn it by practising on. To learn functional programming, use the resources you can find in these platforms:

* <a href="https://www.codecademy.com/">Codecademy</a>
* <a href="https://www.w3schools.com/python/">w3 schools</a>
* <a href="https://www.geeksforgeeks.org/python-programming-language/">Geeks for Geeks</a>
* <a href="https://www.pluralsight.com/browse/software-development/python">Pluralsight</a>
* <a href="https://www.learnpython.org/">Python Official</a>


<h4 style="color: blue;">Deep Learning Frameworks and Libraries</h4>

Skills in using Deep Learning frameworks is a must have for any DL Practitioner. They make your work easier and more productive. Some Machine Learning algorithms are ofcourse still used by some engineers but now in every case would they be the best option to go for. In fact, Tensorflow the most popular tools for Machine Learning Enginners is a DL Framework. To build up skills in any framwork is now a very easy ordeal. Every tool now has an immnense library of tutorials to take you from beginner to expert level. Some of the most widely used frameworks and libraries are:

* <a href="https://www.tensorflow.org/">Tensorflow</a>: TensorFlow is a free and open-source software library for dataflow and differentiable programming across a range of tasks. It is a symbolic math library, and is also used for machine learning applications such as neural networks.

* <a href="https://keras.io/">Keras</a>: Keras is an open-source library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library. Up until version 2.3 Keras supported multiple backends, including TensorFlow, Microsoft Cognitive Toolkit, R, Theano, and PlaidML.

* <a href="https://scikit-learn.org/">Scikit-Learn</a>: Scikit-learn (formerly scikits.learn and also known as sklearn) is a free software machine learning library for the Python programming language.[3] It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.

* <a href="https://pytorch.org/">Pytorch</a>: PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab.

* <a href="https://numpy.org/">Numpy</a>: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays



<h3>Soft Skills Required for Deep Learning</h3>
There are a number of qualitative skills that make a technically efficient deep learning candidate. The following are some of the prominent soft skills that a deep learning practitioner should have.

<h4 style="color: blue;">Problem Solving</h4>

Problem Solving in Deep Learning and ML requires the person to logically apply a combination of thoughts, processes, and actions to effectively and correctly reach the end goal they want.

A good problem solver tackles a task by making less assumptions and instead researching more to find out what works. Before you can solve a problem, you must first understand it in your own language. How to break it down to understand might be the problem for most of us. There are a few qualities and behaviours you can employ that is guaranteed to help you comprehend and interpret any Deep Learning task:

* Eliminate fear: The first step is to keep a neutral and positive mind. Thinking or feeling that the task is too tough for you is killing the process of problem-solving even before starting. To eliminate fear, simply believe that you can do it, you may be a beginner but know this: Every expert was once a beginner.

* Think Accurately: While reading the problem to be solved, try to see the words in your mind's eye and create patterns of what they mean as you read. As you do this, surely you would find tasks that you totally do not understand. Which takes us to the next step

* Reserach: The internet is full of resources in whatever subject you are researching. While browsing how-tos and guides make sure to not find the exact task you are working on but unstead something similar that sheds light on your task and can be employed in solving it.

With these four steps you can iterate through problem discovery and completion. On the process, you may discover other process that works best for you. Do ensure to practise it in your work, if it inproves effectiveness and productivity. At the core of it, every Deep Learning Practitioner requires Problem Solving ability


<h4 style="color: blue;">Application of Deepl-learning</h4>
Solving problems is good, building an application with your Deep learning model is Priceless. If you want to be a deep learning practitioner, then you must know that applying model in a real-world case is essential, not just that, this can benefit you in a number of ways:

* Interest to prospective Employers: You probably want to be noticed and get a full-time job in a deep learning field. What you should know is that, it's better to show employers a web application that works thatn to show them notebooks where you built your model. Remember that, the model doesn't have to be advanced, not at all, that would come naturally if you keep up with your goals.

* Learning process for you: Learning Model Deployment earlier on would give you a very important skill. Learning about model deployment is a process 80% of beginners ignore, but if you master the process you give yourself an edge among the crowd. Deployment can be done in different ways; cloud, self-hosting, third-party services etc. this post on deployment, <a href=""></a> would teach you everything you need to start.



<h3>End Notes</h3>
To conclude, in this article, we understood the skills required for a deep learning practitioner. Also, we explained in brief, the difference between a deep learner and a deep learning practitioner and why you should strive to achieve the latter.
Have other skills in mind? What skills do you think is the best for aspiring deep learning practitioners? Let us know in the comments below.