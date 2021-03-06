---
layout: post
author: Chel
title: Introduction to Generative Models and GANs - What are GANs?
seo: Generative models GANs Generative Adversarial Networks deep learning branches computer vision with GANs
description: Using generative models, we first learn the distribution of the training set and then generate some new observations or data points using the learned distribution with some differences.
img-src: ../assets\images\Blog\generative-nets
---
<h3>Overview</h3>
* Generative Models and GANs - This article will give a simplified intoduction to GANs that you can fully grasp without prior knowledge of the basics
* This article will explain briefly the structure of GANs, what they achieve and how they are trained
* Some Intruiging-real world applications of GANs awaits you-- Let's begin!






<h3>Introduction</h3>

I first heard about GANs not quite long ago, as it is, I'm relatively a new-comer to the field. I came across it first while scrolling a filtered results for Computer Vision on Analytics Vidyha website. The title of the article was actually what made me click it "Generative Models: The Magic of Computer Vision". I started reading this article and I was nothing short of amazed-completely, you know, I never knew something like what I read and saw was possible at this time, but well, it actually isn't even <em>that</em> new. If you are somewhat just hearing it for the first time, try and be amazed by this.

Can you guess where the below collection of images came from:

<img class="img-fluid" src="../assets\images\Blog\Blog-img\Gans2.webp">

How about these ones:

<img class="img-fluid" src="../assets\images\Blog\Blog-img\Gans3.webp">

Well, all of the object and faces you see in these images have been generated single-handedly by a computer-vision model called Generative Adversarial Networks (GANs)!. Awesome right? There's so much more to see.

Being someone with a growing interest in Computer Vision and Virtual Reality, I loved it so much. In short, my mind started racing through the wonderful possibilities of GANs in Virtual Reality, of course, all those would take a lot of work in reserach but who knew we would have GANs performing at this level in just 2020. 

With this article, I hope to give you a simple Introduction to GANs with all the necessary and important aspects of it, that you can go on with to explore ideas in branches of your interest. We would also look at some of their applications and how GANs come to give such exciting results that spells creativity.




<h2>Table of Contents</h2> 


<ol>
  <li>What are Generative Models</li>
  <li>Structure of Generative Models</li>
  <li>Types of Generative Models</li>
  <li>Applications of Generative Models</li>
  <li>Getting Started with GANs - Projects & Opensource</li>
</ol>




<h3>What are Generative Models</h3>

"<em>Generative Adversarial networks is the most interesting idea in the last 10 years in Machine Learning</em>"- <b>Yann Le Cun</b>
 

Generative Adversarial Networks, or GANs for short, are a type of neural network used for machine learning, computer vision, and other forms of artificial intelligence. Generative modeling is an unsupervised learning task in machine learning in which regularities and patterns of input data are discovered and learned so that a model can be used to generate and output new examples that can plausibly be taken from the original data set.

Generative Adversarial nets were recently introduced (In the past 7 years or so) as a novel way to train a generative model, i.e create a model that is able to generate data. They consists of two 'adversarial' networks: a generative model G that captures the data distribution and a distributive model D that estimates the probability that a sample came from the training data rather than from G.

A generative adversarial network, GAN for short, consists of two main structure that makes up the whole basis of its operation. They are called the <b>Generator</b> and <b>Discriminator</b>. These two neural networks are pitted against each other in a zero-sum game, whereby the first network, the generator, is tasked with fooling the second network.


A simple GAN can be said to be made up of two dataset, one of them is called the true or real-world dataset, the other can be called the fake dataset. The Generator is the model that distributes fake data into the system while the discriminator gives as input X, the real data. This two inputs are passed into the model, and every iteration/epochs, the discriminator would have to discern if each image sample comes from the real or fake dataset. At the start of training, the discriminator almost always spots the fake data, whereby, the generator model has to change its weights(during training) inorder to reduce the cost/error made and once again pushes a new improved set of data to the discriminator for inspection. This is what happens at training periods, on each epochs until a desired level of accuracy is achieved. The overall system and purpose of GANs is to obatin a level of cost that the discriminator starts to guess datas from the generator as "real ones".
    
While the discriminator tries to distinguish between the real and fake sets of data , the generator attepts to create a plausible example of the same data set by updating its weights/parameters. The Generator models are designed to deceive the discrimination model, by trying  to generate plausible examples that fits among the real dataset. Our hope is that the two networks, when they face each other, will get better and better until the end result is a generator network that produces photorealistic outputs.

The fake samples are generated by some randon noise from looking at the real data, they are passed on to the discriminator whose input is both fake samples as well as samples from our real data set. The discriminator than makes a binary decision about whether the image supplied, z, is a real image D(z)= 1, or a fake image, D(z)=0.

<img class="img-fluid" src="../assets\images\Blog\Blog-img\D&G_Gans.webp">

    
For example, a GAN trained on photographs can create a new photograph that appears to human observers at least superficially authentic and has many realistic characteristics. A popular real-world application of GAN; GANs have been used to produce new celebrities who are not real people. Using a training kit, the technique learns to create images of real-life celebrities, real-face celebrities and non-real face celebrities.
        
So a GAN (generator network) can start with a matrix of noise pixels and try to change them in what an image classifier would call a "cat." Instead of taking raw data, the generator can trace back to the original input data (e.g. a photo of a cat) and then try to generate output from which the input of the data would be mapped. The new data is not bound to a single data set, but is created from a set of data points (i.e. an array of images or a set of data sets).
    
Back in 2014, Ian Goodfellow suggested the idea of two neural networks competing or working together. For some networks, parallel training means an improvement in skills, for others it is a question of perspective. 
    
One neural network tries to generate realistic data, the other network tries to distinguish what the generator network generates. The discrimination network updates its parameters to ensure that the fake data is selected from the real data. Note: GANs can be used to model data distributions, but nowadays they are mainly used for images). The generator networks use the discriminators as a loss function and update their parameters after generating data that appears more realistic.

    
GAN is a recently developed machine learning framework that proposes creative realistic representations of the real data distribution of images and other data. As mentioned above, a sample image can be used to create images that are superficially authentic to human observers by mapping sets of feature noise from the input to an output with close relation
    


Cited works from:
* <a href="https://towardsdatascience.com/comprehensive-introduction-to-turing-learning-and-gans-part-2-fd8e4a70775">towardsdatascience(medium)</a>

* <a href="https://machinelearningmastery.com/what-are-generative-adversarial-networks-gans/">MachineLearning Mastery</a>
    
* <a href="https://deepai.org/machine-learning-glossary-and-terms/conditional-adversarial-network">Deepai.org</a>

* <a href="https://en.wikipedia.org/wiki/Generative_adversarial_network">Wikipedia</a>
    
* <a href="https://bdtechtalks.com/2018/05/28/generative-adversarial-networks-artificial-intelligence-ian-goodfellow/">BDtechtalks</a>   


    



