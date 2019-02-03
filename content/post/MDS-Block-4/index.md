+++
title = "MDS Block 4"
date = 2019-02-02T17:02:05-08:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alex Hope"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Machine Learning","Regression","Shiny","Neural Networks","Optimization"]
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
My experience and thoughts on block 4 of MDS at UBC. The courses were: DSCI 532, DSCI 563, DSCI 572, and DSCI 573. <!--more-->

## MDS Block 4


Another month another block, if you haven't read my past reviews you can find the previous summary of Block 3 [here](https://ehhope.github.io/post/mds-block-3/) Generally speaking, the coursework in this block was one of the major reasons I decided to apply to MDS in the first place.... machine learning, machine learning, machine learning. Three of our four courses were centered on ML with a fourth class that was part II of visualization. A **ton** and I mean a **ton** of material was covered in this block plain and simple, and I'm not here to regurgitate everything I've learned here, but let me offer some meta-thoughts on the structure of the program this block, and some opinions on the ML and Viz coursework.

***

###Block 4 Overview

This is considered the toughest block of coursework in MDS for a reason. The difficulty of the content and large amount of material you are asked to learn in each course for the month it is covered is asking alot of students. I spent many, many nights late at the library or in my room reading resources, watching videos, and deciphering code in addition to my lab work. The workload definitely translated to burnout I could see on the faces of many students, including myself at times. I wouldn't say these expressions are a bad thing though because it was also a very valuable month. On the one hand I learned a lot about ML, but more then that I realized how deep this field is, in what I learned content-wise and for my own perspective. Standing at the top of the block 4 mountain, I'm realizing two camps seem to have emerged that roughly summarize student sentiment about this block.

**Camp 1:** These students are burnt out and frustrated with the difficulty of the material and labwork, and don't believe the program is structured well to deliver what they feel MDS should..... a thorough understanding of machine learning. This camp has high self-expectations and wants to understand on a very granular level how everything works, which is admirable for such a tough topic but not very realistic if your background isn't comp sci or math and your studying ML for a month.

**Camp 2:** These students are also burnt out and have a hard time with the material and labwork, however, they see that some of the math behind ML algorithms and the code that represents them is not deeply acquired in the time they are given plain and simple. Because of this they believe that MDS' role is to introduce us to these complex topics not help us master them. They know they arne't walkiing away with a PhD, but if they work hard they can learn a ton and lay a great fundation for future work. The darker areas around math and some complicated code simply need to be explored more in capstone or once you graduate.

This isn't to say there aren't other opinions because there are, but these were two very common themes I kept hearing and thinking about myself week after week. Both camps make reasonable points about what MDS should offer, and I can say for myself I started in Camp 1 and as each week progressed slowly moved over to Camp 2.

Data Science is a really hard field to grasp because it requires a breadth of tools to follow an idea through, but also a depth with those tools to generate the real value. It's not a fault of the program for being unable to condense something very complicated it's just the state of the field, in fact, they did an amazing job across the board. The entire MDS staff was very sensitive to the fact it was a difficult month for students, and made as many accomodations for us as they could. Without their support, this could've been a much tougher experience so big thank you to them. Ok, without further adue, the coursework.




###Machine Learning Coursework
- *Unsupervised Learning (DSCI-563, Rodolfo Lourenzutti)*

- *Supervised Learning II (DSCI-572, Mike Gelbart)*

- *Features and Model Selection (DSCI-573, Mark Schmidt)*


These courses all covered machine learning in some capacity, with significant overlap so I'm going to clump them together here. Here are some examples of the questions you address in this block: How do we group/classify unlabelled data? How do algorithms optimize their loss when they are 'fitted' to data? How do we figure out if our features are helping or hurting model performance? If we have too many dimensions (features) in our data how can we reduce them and visualize relationships? How do we build neural networks and what advantage do convoluted neural networks have over fully connected networks? How does Amazon's recommendation system work?

The main focus can be boiled down to two basic questions: 1) How do neural networks work? 2) How do we 'tune' algorithms so that we optimize their performance and what things do we need to consider in order to do this? Well, you need to pick your base model, choose your features wisely (domain-specific expertise), optimize your hyperparameters, consider your loss function and how you penalize errors in your model. All of these considerations are delicate questions that aren't answered easily and have massive implications for how your model will perform. For example, picking how your model penalizes error (L1 or L2 regularization) has significant effects on model performance becuase you are handling 'error' in completely different ways. We saw this in the context of linear regression where our penalizer would dictate the number of features we actually used in our model to predict targets with L1 keeping a significant number of features and L2 attempting to reduce as many feature weights to 0 as possible.

So how do full and semi connected neural networks work? Well, you're going to find out when you start building them with a library called 'Keras'. You'll learn a bit about other packages but Keras is a very accessible way to start building quickly because it's intuitive and simpler than other libraries. It's pretty amazing that anyone can build a massive network in 4 lines of code now.... just specify your neurons in your input, hidden layers and shape of your output before you compile and you've built a neural network. Now, it's simple on the surface when I explain it that way but the more you start building the more you realize the difficult of building them **well**. Nonetheless, the ease in which anybody can build a NN is pretty profound. Unlike the majority of algorithms we've learned to this point, you have much more control over the architecture of a neural network than anything you'll learn in sklearn. You can have a hidden layer with 5 neurons or 100 if you want, the only real restrictions you may have are the inputs and outputs depending on the data you are working with. Mike Gelbart knows his material extremely well, and is talented at explaining complicated topics from many angles so that students can understand what's happening even if they miss one perspective of what he's explaining. It's very helpful in that sense, and I'm glad he taught this course given his history with us in this program.

For DSCI 563, we covered a range of content tied to clustering techniques (K-Means, K-Medians, DBSCAN, Hierarchical Clustering (linkages) and dimensionality reduction approaches (Principal Component Analysis (PCA) and Non-Negative Matrix Factorization (NMF)). The essential question of this class is, how can I make sense of data that isn't labelled and utilize different algorithms to characterize relationships in this data? Using the techniques I described above, you can tackle a range of different questions and arrive at some very interesting solutions. You will learn how different mathematical approaches (euclidean, cosine similarity, etc.) can model 'similarity' between items in Amazon's database. You'll also learn how images of faces can be condensed and reconstructed using PCA and NMF, and understand the differences in how these techniques function in both their reduction and reconstruction. The face data is well chosen because it helps build your intuition about how these methods work when you can compare original faces with reconstructed ones and gauge their similarities/differences between the two. Let's just say if you take enough components you can store high dimensional data extremely accurately, and reconstruct that information with high precision. These are very powerful techniques that any data scientist needs to have in their toolbox, and Rodolfo did a solid job of explaining concepts in intuitive ways while only bringing in heavy math when it was needed.

### Visualization II (DSCI-532, Cydney Nielsen)

This class admittedly did not get enough attention from students as it deserved. The reason for this is because students were completely absorbed by 3 classes on machine learning that it inevitably became the 'tag along' course that students focused less on. That said, I thought Cydney was a great instructor who knew a ton about data visualization and how to display information in impactful ways for different audiences. You could tell she had ample experience in visualization as a computational biologist, and that it translated to her work as a data scientist with Microsoft quite well. Her lectures were a basic run down of 'the science of visualization', a crash course in human perception and graphing theory. This course contained the group project for block 4, where we were assigned a partner and taught to build Shiny dashboards for displaying data. I can confidently say that I can go to any company now and build simple, sleek dashboards that help people visualize information they care about. Not only did I learn the code behind shiny dashboards, but just as importantly how to think about design processes for the end consumer. Your target consumer will dictate the **kind** of information you convey from a dataset, **how** you present the information and the aspects you allow the user to **customize** to address their questions. These are all valuable skills a designer needs, and the class will definitely help you from a coding and design perspective.


I could talk for days about this block, but I think what I've said paints a detailed enough picture to convey my feelings on the program for the last month and the topics we covered. Hopefully you found this information helpful, and see you at the end of block 5!
