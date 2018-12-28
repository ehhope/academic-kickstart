+++
title = "MDS Block 1"
date = 2018-10-10T20:06:21-07:00
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
My experience and thoughts on block 1 of MDS at UBC. The courses were: DSCI 511, DSCI 521, DSCI 542, and DSCI 551. <!--more-->

Hey! My name is Alex Hope, if you've made it this far I'll spare you the full introduction, however, this post is the first of an ongoing series I'll be doing as I progress through my Master's degree in Data Science (MDS) at the University of British Columbia (UBC). There's a bunch of reasons why I decided to write this blog, but a major one was to track my own growth as I transition into this field from healthcare research so I can look back on how far I've come and recall concepts from the coursework of MDS in the process. I'm excited to dive into this new degree and learn more about the analytical and computational skills I knew were important but never had the time to cultivate while working. In addition, I wanted to use this blog as a resource for future students in MDS who like myself may have been unsure about what to expect as a student in MDS, so I hope any of this may be helpful. This blog is a perspective from someone who is simply going through the program as a student, not as a vested employee of UBC. So, you'll hear my thoughts and advice about courses and instructors and I will do my best to convey my feelings about each class as honestly as I can. First a bit of background about what I did prior to getting here.

The resources I used to prepare for this degree:
  * Work experience writing code to do basic analysis in Python and building a basic site with HTML/CSS
  * Jose Portilla's: Python for Data Science, and Complete Python Programming Bootcamp
  * ProjectEuler.com - bunch of coding problems on there
  * Probability and Statistics materials from a one day trial of a bootcamp called "Metis"
  * DataCamp: 4 courses (python and basic statistics)

#### **Block 1**

With that in mind lets kick this off! My cohort contained about 70 students with people of all ages, genders, and countries with diverse skill sets. We have former business owners, rehabilitative therapists, engineers, mathematicians, fellow neuroscientists, programmers, even a practicing doctor. As far as the coursework, there are 6 blocks in MDS with each lasting ~ 1 month. Each block contains 4 classes, the first four being: **DSCI 511 (Intro to Programming)**, **DSCI 521 (Computing Platforms for Data Science)**, **DSCI 542 (Communication & Argumentation)**, & **DSCI 551 (Descriptive Statistics & Probability)**. Essentially, every class has a lab due on the Saturday (4 labs due each week), with midterms taking place during the 2nd week of the block and then finals being the 4th week of the block. So it's pretty fast-paced. Without further a due, let's dive in.

#### **Introduction to Programming (DSCI 511)**

This class was an interesting split between R and Python, with separate instructors that taught us for each language. Heading into the fall I knew I needed to sharpen my programming skills to be able to hit the ground running in this degree and the last thing I wanted was to fall behind early on. Having used Python in my past work, I wasn't worried about keeping up for this part of the class but was concerned about the fact I had zero experience using R. I had heard that R was this language of the past and that it would be overtaken by languages like Python and Julia eventually, so I chose to focus on Python than splitting my learning between languages. In truth, I loved learning about R, and found the in-class tutorials by Vincenzo Coia to be extremely helpful and easy to grasp. Now that I've used R I feel like it's arguably an even easier language to learn and use immediately than Python, and can see why it's recommended as a great starting language. On the python side, I would say I over-prepared for this class, I wasn't challenged much to be honest. If I had looked at even a little R I think I would've been fine getting through this block 1 class. I enjoyed the in-class programming tutorials that linked the ideas they were trying to convey with motor-learning, it always helps to write the code yourself and follow along I find, and both instructors took their time conveying the material while providing notes for you to refer back to if needed.

In general, the class lectures were well paced with more difficult labs than exams, and they truly distill the basics of what is required to get comfortable writing functions, understanding object-oriented programming (OOP), lists, vectors, dictionaries, and using different kinds of loops, which I trust we will be deploying on an everyday basis in future blocks. There were students that barely used either language or had zero programming experience heading into the fall who did fine, so while the requirements suggest you need to have all of these mathematical, statistical and programming skills to be ready for the degree, I wouldn't say it's **absolutely necessary**, but it definitely won't hurt. I'll be curious to see how they emphasize these languages differently as we progress to different parts of the data science process (graphs, analysis, reports, slides, etc.) where perhaps having a greater proficiency will help. As far as getting through this class though and performing well, you don't need much of a background honestly.

#### **Computing Platforms in Data Science (DSCI 521)**

I wasn't quite sure what to expect from this class heading in as I had never really used any platforms aside from Jupyter that were for data science per se (SPSS and Tableau aren't really considered DS platforms in my opinion). Tiffany Timbers taught this class and introduced us to the beauty of GitHub, RStudio (Markdown and RMarkdown) and Jupyter Notebooks (RISE).

GitHub is a well-known service that allows people to share all kinds of projects, tools, code, webpages, among other things seamlessly to the web and between people. It's a big part of advertising your own work as well as collaborating with others on things so I'm glad we focused on it because it's a great way to gain traction with employers to show them what you can do. On a practical note, we will be using it across all of our classes throughout the degree to pull labs and quizzes from the cloud to our local machine and I suspect we will be cloning, adding, committing, pulling, pushing and forking a lot over the next year...

Having learned about RStudio in DSCI 511, it wasn't completely foreign to me, but there is lots to learn that you simply can't cover in one class as well, so I'm glad we covered it in two classes. One aspect I did learn was how to change the output of md and Rmd files to knit different sorts of files into slides, pdf's, or any other useful file imaginable! In addition to RStudio is Jupyter Notebook, which is a complimentary tool used to write code, as well as write documents and will be a staple within the program's learning technologies. I had used Jupyter in the past while learning Python so I was familiar with how it worked in some ways, but I was unaware of ```RISE``` which is a way to use notebooks as a powerpoint presentation but with additional features that allow you to have interactive code embedded in your presentations. Very cool.

In general, this DS stack seems useful across personal and business settings and I could see myself continuing to use all of these in the future for presentations, writing, sharing documents and coding. Tiffany was great at conveying the basics, showing us directly how they work and providing resources to take our learning even further beyond lecture if we wanted. I didn't find the material overly challenging, and really you will learn to use these technologies simply through sheer practice because you will lean on them heavily across almost all of your classes in this block and future ones. Tiffany also demonstrated how to host your own website through GitHub (which becomes a digital CV for all your work), how to fork other people's repositories that provide the framework for writing a book, and how to post issues and comments to other repositories as a means of helping correct for bugs. One day I will write that bio technology book... one day. No time right now in MDS... but one day.

### **Communication and Argumentation (DSCI 542)**

David Laing (a former MDS student) was the instructor for this class, which was the only one of it's kind that you wouldn't consider 'technical' and I have to say I really enjoyed the material. The class focused on 'softer skills' in data science around how to frame problems, communicate the meaning of statistical results and build awareness for how complicated it can be to communicate ideas to different audiences, and I thought David's strong organization and focus on communicative clarity in lectures helped with digesting the material and got you thinking. He also provided ample time to discuss with classmates problems he had framed, and asked us to participate in daily exercises that incorporated the material he was teaching. Overall, he did a great job.

A common saying hammered into me from this class that was handed down from Hadley Wickham - "it doesn't matter how good your analysis is unless you can explain it to others: you need to communicate your results". Start to finish communication is an important aspect of data science and the more I progressed through this class the more I realized the truth behind this fact. From the beginning to the end of a data science project, communication is an important component and can save enormous amounts of time and energy when done well, but haunt you for hours/days/weeks on end when done poorly. Writing code and planning the overarching pieces of an individual project can be challenging because you aren't always clear with yourself on what's required let alone when you have to work with others on a large project.

We spent time talking about the barriers to communication, mainly, struggling to imagine how to explain a concept to someone who doesn't understand data science or does but at a different level than you. This includes the tendency to use jargon you comprehend that others don't, employ complex examples and make assumptions in your writing that may need to be spelled out. Understanding the literacy of your audience and how to present information in a way that makes it easy for people to digest is a crucial skill that I'm glad we could learn to harness here. One concept was to use bottom-up perspectives where examples are presented to convey the critical point of your message in a simple way before elaborating further on the topic once a case has been presented to the listener.

In the end, each student was asked to write a blog post on any topic they wanted in Data Science that attempted to capitalize on the techniques we had learned for presenting information clearly. I thought it was an excellent exercise that summarized the course well, and gave us something to contribute to our webpage that we had developed in DSCI 521 (you can see how these courses start to gel together). At the end of the course, we gave a presentation on our blog post or a data science problem we had formulated from a later lab. I thought the public component really forced students to integrate the knowledge from lecture, and you could tell MDS was organized because they recommended that we use RStudio or RISE to present our topic to the class to further consolidate what we were learning.

I really enjoyed this class and it was a nice twist from the technical classes we had been focused on. I thought David was fantastic and hope he continues to teach as you can tell her clearly enjoys it. At worst David got you thinking about the challenges of explaining data science, and at best he changed your thinking, writing and speaking so that you delivered content in a more conscientious way to the end consumer, whoever that may be.

### **Descriptive Statistics and Probability (DSCI 551)**

This was probably the one class that you would like to have had some background in coming into MDS block 1. As someone who always struggled with statistics in undergrad, it would've been nice to look at some basic stats & probability a bit more than I did. The class isn't hard if you invest yourself in it and listen closely in lecture, but make no mistake it was the toughest class of block 1 for English speaking students (DSCI 542: Communication was supposedly tougher for many ESL students).

Mike really focused on descriptive stats (variance, standard deviation, entropy, mean, median, and mode), probability (conditional, joint, and marginal distributions) and examining what different kinds of distributions look like using graphs. As a data scientist, probability is a fundamental knowledge base for all sorts of ML and statistical procedures (Ex. Bayesian Theory) and I knew this was pivotal for what we would learn moving forward in MDS.

I thought Mike Gelbart (professor) did a pretty good job educating us on how distributions work (Bernoulli, Gaussian, Multinomial), and showing us how R can help derive different measures of distributions using it's functionality as well as emphasizing theory. Similar to all of the professors, the notes were in Jupyter notebooks and I found playing around with the interactive notebooks for this class to be helpful for learning about the behavior of distributions. Mike is very good at explaining concepts simply, and presenting it with multiple perspectives which I appreciated since this class was by far the least intuitive to me. I left with a strong grasp of parameters for distributions, visualizing conditional and joint distributions, correlations in graphs, and how differences in variance and entropy can effect the shape of distributions when graphed. I had to work the hardest in this class but like anything, you get what you invest into these things.

To conclude, this was a great first block and the organization between courses in how they integrate is unparalleled. It's a huge help to have people curate material in a way that's intelligent and efficient, and you truly do get the impression this has been well thought out since the program's first inception. The effort MDS faculty have put into designing the program does offload some of the burden of having to 'know all the prerequisites' before you start your degree despite MDS being a fast-paced learning environment, make no mistake.

In my opinion, students who feel they aren't prepared will most likely be just fine for this intro block. Of course, the more you know going in the more free time you have to focus on side projects and dig deeper into material you know the basics of already so there is that. I can tell there's a lot of talented, driven people to work with this coming year, which is exciting.

One last point that I think is important is the program encourages us to learn as much as we can by specifically **NOT** breeding a sense of competition amongst peers. I think this is awesome as I have already learned and helped others so much, and as this program picks up I suspect we will lean on each other more! It's also bred an awesome collaborative spirit within the cohort that certainly will resonate with most students' careers once they graduate as well. With all that said, can't wait for what block 2 has in store.
