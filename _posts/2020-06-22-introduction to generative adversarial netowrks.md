---
layout: post
author: Chel
title: Introduction to Generative Models and GANs - What are GANs?
seo: Generative models GANs Generative Adversarial Networks deep learning branches computer vision with GANs
description: Using generative models, we first learn the distribution of the training set and then generate some new observations or data points using the learned distribution with some differences.
img-src: ../assets\images\Blog\coming-soon.jpg
---
<h3>Overview</h3>
* Generative Models and GANs - This article will give a simplified intoduction to GANs that you can fully grasp without prior knowledge of the basics
* This article will explain briefly the structure of GANs, what they achieve and how they are trained
* Some Intruiging-real world applications of GANs awaits you-- Let's begin!






<h3>Introduction</h3>

I first heard about GANs not quite long ago, as it is, I'm relatively a new-comer to the field. I came across it first while scrolling a filtered results for Computer Vision on Analytics Vidyha website. The title of the article was actually what made me click it "Generative Models: The Magic of Computer Vision". I started reading this article and I was nothing short of amazed-completely, you know, I never knew something like what I read and saw was possible at this time, but well, it actually isn't even <em>that</em> new. If you are somewhat just hearing it for the first time, try and be amazed by this.

Can you guess where the below collection of images came from:

<img class="img-fluid" src="../assets\images\Blog\Blog-img\Gans2.jpg">

How about these ones:

<img class="img-fluid" src="../assets\images\Blog\Blog-img\Gans3.jpg">

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

Generative Adversarial Networks, or GANs for short, are a type of neural network used for machine learning, computer vision, and other forms of artificial intelligence. Generative modeling is an unsupervised learning task in machine learning in which regularities and patterns of input data are discovered and learned so that a model can be used to generate and output new examples that can plausibly be taken from the original data set.

A generative adversarial network, GAN for short, consists of two main structure that makes up the whole basis of its operation. They are called the <b>Generator</b> and <b>Discriminator</b>. These two nodes/models are built into a single system that forms the whole GAN. Let's look at a simple illustration of what they are both trying to achieve


A simple GAN can be said to be made up of two dataset, one of them is called the true or real-world dataset, the other can be called the fake dataset. The Generator is the node that gives out fake data while the discriminator gives as input X, the real data. This two inputs are passed into the model, and at an iteration or training, the discriminator would have to discern if each image(data) that comes its way is from the real or fake dataset. At the start of training, the discriminator succesfully guesses right, on this process, the generator has to change its weights(during training) inorder to reduce the cost/error made and once again pushes a new improved set of data to the discriminator for inspection. This is what happens at training periods, on each epochs until a desired level of accuracy is achieved. The overall system and purpose of GANs is to obatin a level of cost that the discriminator starts to guess datas from the generator as "real ones".
    
While the discriminator tries to discern the difference between what the real an the fake database is, the generator tries to create a plausible example of the same data set by updating its weights/parameters. The Generator models are designed to deceive the discrimination model, by trying  to generate plausible examples that fits among the real dataset. Our hope is that the two networks, when they face each other, will get better and better until the end result is a generator network that produces realistic outputs.

    
For example, a GAN trained on photographs can create a new photograph that appears to human observers at least superficially authentic and has many realistic characteristics. A popular real-world application of GAN; GANs have been used to produce new celebrities who are not real people. Using a training kit, the technique learns to create images of real-life celebrities, real-face celebrities and non-real face celebrities.
    
We take a look at Generative Adversarial Networks (GANs), a new class of neural networks with a wide range of applications in computer science. GANS learns to model input distributions by forming two competing and cooperating networks known as generators and discriminators (also known as critics). We propose to use two neural networks to generate and refine new data: a generator and a discriminator. [Sources: 7, 8] 
    
For example, a GAN (generator network) can start with a matrix of noise pixels and try to change them in what an image classifier would call a "cat." Instead of taking raw data, the generator can trace back to the original input data (e.g. a photo of a cat) and then try to generate output from which the input of the data would be mapped. The new data is not bound to a single data set, but is created from a set of data points (i.e. an array of images or a set of data sets).
    
Generative enemy networks were first developed in 2014 and are most commonly used to create images of people and objects (I. Goodfellow). Generators try to produce realistic images, and discriminators try to see the difference between what the generators generate and what the competing neural networks are working on. Generative opposing networks (GANs) work in the same way as a discrimination network, but with different parameters.
    
Back in 2014, Ian Goodfellow suggested the idea of two neural networks competing or working together. For some networks, parallel training means an improvement in skills, for others it is a question of perspective. [Sources: 0, 3] 
    
One neural network tries to generate realistic data, the other network tries to distinguish what the generator network generates. The discrimination network updates its parameters to ensure that the fake data is selected from the real data. Note: GANs can be used to model data distributions, but nowadays they are mainly used for images). The generator networks use the discriminators as a loss function and update their parameters after generating data that appears more realistic. [Sources: 3] 
    
The generator algorithm tricks the evaluator by generating a data distribution that seems to come from the true data distributions, but is actually just a fake. [Sources: 2] 
    
While the discriminator is a convolutional neural network, the generator is designed as a deconventional neural network. The generator network processes the data in such a way that the artificial constructs are recognized by the evaluator, but not the real data distributions, such as the actual data distribution. [Sources: 2] 
    
A GAN is a recently developed machine learning framework that proposes creative realistic representations of the real data distribution of images and other data. As mentioned above, an organ can be used to create images that are superficially authentic to human observers. [Sources: 2, 4] 
    
The opposing structure can consist of two competing deep neuron networks, each of which has its own set of neurons, and a number of different types of opponents. [Sources: 4] 
    
In this blog post, we will explore how this research is related to the development of generative enemy networks (GANs) for deep neural networks and how they work. In a Gan-based strategy, a discriminatory network uses a series of pixels, each corresponding to one of its two opponents, to match pixels corresponding to an isotropic Young Modulus (HS) bound by an upper HS. In the meantime, the generative network, equipped with the knowledge of these connections, is able to fast - advance through the network and generate thousands of new configurations to achieve the desired properties (e.g. the upper limit of the isotropy of Young's modules). [Sources: 4, 6] 
    





Sources:
    
[0]: https://www.wwt.com/white-paper/obscuring-analyzing-gan-generative-adversarial-networks
    
[1]: https://machinelearningmastery.com/what-are-generative-adversarial-networks-gans/
    
[2]: https://deepai.org/machine-learning-glossary-and-terms/conditional-adversarial-network
    
[3]: https://blog.floydhub.com/gans-story-so-far/
    
[4]: https://advances.sciencemag.org/content/6/17/eaaz4169
    
[5]: https://poloclub.github.io/ganlab/
    
[6]: https://www.intel.com/content/www/us/en/artificial-intelligence/posts/training-generative-adversarial-networks-in-flexpoint.html
    
[7]: https://bdtechtalks.com/2018/05/28/generative-adversarial-networks-artificial-intelligence-ian-goodfellow/
    
[8]: https://dzone.com/articles/working-principles-of-generative-adversarial-netwo
    
[9]: https://en.wikipedia.org/wiki/Generative_adversarial_network
    


