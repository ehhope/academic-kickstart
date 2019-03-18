+++
title = "MDS Block 5"
date = 2019-03-17T18:26:44-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

My experience and thoughts on block 5 of MDS at UBC. The courses were: Collab Soft Dev, Regression II, Time/Spat Analysis, & Bayes. <!--more-->

## MDS Block 5

Alright, here I am after another block of coursework in MDS. If you missed my discussion of block 4 you can find it [here](https://ehhope.github.io/post/mds-block-4/) or any other blocks on my home page under **blog**. This blog post will be a bit shorter, but nonetheless convey my thoughts on each class. Ok,let's dive in.

Unlike block 4 where we focused entirely on the intricacies of machine learning, feature selection, and deep learning, this month covered the classical statistical approaches in ```R```. For myself, this was bar-none the most challenging set of coursework to date, and can speak on behalf of many others in the program who feel similar. Coming in, I had next to no experience with generalized linear models, implementing bayesian models using ```RJAGS```, or how to assess and extract time series data for seasonal or linear trends and forecast this time-series data. These are all vital skills in a Data Scientists toolkit that are heavily relied upon, so it was worth the effort I invested in theses classes to walk away with the understanding I have. Needless to say, a lot has been learned, and I'm excited to grow even further in these areas and apply my understanding to data in the wild. The fourth course was Collaborative Software Development (DSCI-524) and was the group project for the block. Given the freedom to develop any package we desired, our team built ```LibRely``` a library available in Python and R that extracts functions and dependencies from other scripts you provide as input. Developing the package was enjoyable, but the real learning for me came from developing software tests, using ```testthat``` and ```pytest``` as well as working with continuous integration setups such as ```Travis```. 

### Regression II (DSCI-562 - Instructor: Vincenzo Coia)

Building on a previous course on the fundamentals of regression (DSCI-561), this class extended our understanding of simple and multiple linear regression to other forms of data that can be interpreted with linear models. You'll learn about how to deal with response variables that are count data (ex. poisson regression), the consequences of transforming your data versus your model function (ex. log(y) vs link = "log")), survival analysis, ordinal regression, and different forms of data imputation (ex. mean, multiple, etc.). Vincenzo taught me about the power of linear mixed models (LME), how common these approaches are used across domains because of their utility in identifying general trends in groups **and** effects within subgroups. Of course, as we increase the number of parameters in our model our degrees of freedom will lower, and this is a consequnce of LME's, however with enough data it becomes less of an issue.

Vincenzo was in my opinion the best instructor this block, in part because he is a core MDS faculty member, and tailors his content with a detailed understanding of the cohort while connecting the material with our labwork. There was very little disconnect between his lectures and labs, and he can explain statistical technqiues clearly and in numerous ways.

### Spatial & Time-Series Analysis (DSCI 574 - Instructor: Natalia Nolde)

This was one of the harder courses in the block, however, I found the instructor made the material even more difficult than it already was. Natalia is clearly a strong statistician, with an intimate knowledge of time-series and spatial processes in data, but she was more concerned about covering the concepts than ensuring students possessed understanding in her lectures. I learned time-series analysis by reading a **TON** of texts, and referencing both her notes and datacamp where it was convenient to support my learning. So what did I learn? For one thiing, how common it is to encounter time-series data in the wild, and as a result how important it is to be familiar with the models we use to extract patterns out of this kind of data. For example, you'll learn about ARMA and ARIMA models, which are still on the basic side of time-series analysis and compromise both moving average and autoregression models in their process. These models look for patterns across different lengths of time (lag), and the nature of the patterns such whether they are cyclical or trending in a certain direction, or perhaps both. We can use these trends to make projections outward beyond our known series to forecast the future value of a given variable at time ```t```. 

You'll also learn about relationships in spatial data, and these generally adhere to similar concepts as time-series data except using a coordinates system instead of a time variable. Processes such as spatial dependence, variograms, and kriging are all important tools when examining the patterns of values in space. Unfortunately, I had to learn about these on my own as well since our instructor wasn't able to complete time-series until later than she had anticipated, leaving little time to digest the spatial concepts. Overall, this course is a fascinating topic, I just wish it would have been covered more effectively, and by someoene who understood the constraints of MDS.

### Bayesian Inference (DSCI 553 - Instructor: Alexandre Bouchard-Cote)

You would be hard-pressed to find a student in MDS that found this class easy. Thankfully, I felt it had very little to do with the instructor, it was just a class with very difficult concepts crammed into a month.  You'll learn that bayesian statistics is truly the counter point to frequentist approaches and what you've been taught most of your life. At the heart of bayes is the assertion that we **must** model uncertainty, not simply **trust** the data we have to speak about the likelihood of an event occuring. In reality, we almost always have opinions about the likelihood of an event happening (prior), and as we encounter reality and events relating to these beliefs (likelihood), we update our beliefs (posterior) to fit the evidence reality gives us. This is essentially what we do in bayesian analysis, only we simulate these experiences many many times using a probabilistic programming language (PPL) known as RJAGS in order to hopefully converge on an estimate about the chance of an event occuring for example.

The challenge with this class is really learning what the vital concepts (distributions, prior, likelihood, posterior, MCMC, etc.) mean and how they interact in a bayesian model when you merge your conceptual understanding with RJAGS to run your analysis. Once you can reorient yourself around this idea of **uncertainty**, you'll find the maneuver from the prior to the posterior to be an easier task. While many had complaints about the instructor, I found him to be helpful for building my intuition around these core concepts, and that he took unwarranted criticism stemming from engaging bayesian thinking. All in all, a difficult but rewarding course.

### Collaborative Software Development (DSCI-524 - Instructor: Meghan Allen & Jenny Bryant)

Overall, our team worked extremely well together in developing our package from start to finish and I'm very proud of our work. My only real issue with this class was that we are here to be data scientists, not software developers, and study time is crucial in this degree. While some of us may move onto developer roles within organizations, most wanted to prioritize learning statistics. I had already known about pytest, version control, and debugging prior to the course, and knew these weren't essential to being a data scientist. They are undoubtedly useful, but I wanted to strictly delve into statistics this block, and found the course to be a nuissance despite building a great package with my teammates.

You're in great hands with Meghan & Jenny, they have clearly done this before and know how to guide you in the right direction as your group develops the package and moves through various stages of the development process. 


What a block this was! I can't believe how much I was able to learn, and apply in such a short-time, and I intend to build on this knowledge in the coming months as I consider work opportunities and the announcement of our capstone project! Hopefully you found this summary a helpful guide for what to expect from these classes, and I've painted a sense of the dedication required to succeed in these courses. Until next time!