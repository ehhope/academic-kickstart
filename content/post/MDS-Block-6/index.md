+++
title = "MDS Block 6"
date = 2019-03-17T18:26:44-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["AWS", "Cloud Computing", "Ethics in Data Science", "Statistics", "NLP"]
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

My experience and thoughts on block 6 of MDS at UBC. The courses were: Cloud Computing, Privacy & Ethics, Causal Modeling, & Advanced Machine Learning Methods. <!--more-->


## MDS Block 6

Alright, I am here to write about the final block of MDS, what can I say it's been a long journey through the degree filled with many ups and downs. If you missed my discussion of block 5 you can find it [here](https://ehhope.github.io/post/mds-block-5/) or any other blocks on my home page under **blog**. With that out of the way let's dive in.

I can confidently say that Block 6 of MDS was much easier than the prior two blocks of coursework. This was clearly a conscious decision on the part of MDS faculty who recognized some students were quite burnt out. That said, it was far from a cakewalk, particularly Advanced Machine Learning and Causal Modeling.

I'm going to offer a small rant about each course, but not spend a ton of time on each per se. I'm more interested in offering a high-level overview than getting into granular details about a specific course. So, let's start.

We begin with Cloud Computing (**DSCI-525**), which taught me a ton about the power of distributed computing in today's big data age, how to scrape web information from HTML pages and leverage API's in my own projects. 

I had always heard about map/reduce frameworks but this was the first time I was exposed to it using Amazon Web Services (AWS). The power of AWS is quite astounding, even with the free version they offer or the extremely cheap clusters you can access. You'll learn about how to handle massive amounts of data and offload the computing power to several computing sources to do your computation, which in many cases will be complex and fry your computer if you do it yourself. Mike Feeley has a wicked sense of humour, and is a great lecturer. I know he was controversial to the cohort but I really thought he delivered material that was interesting and pragmatic at the same time. Solid instructor.

Next is Experimental & Causal Inference (**DSCI 554**), which was a fantastic walkthrough of the considerations required for performing strong statistical analyses, particularly AB tests. Depending on your role in a company AB testing may or may not be a central responsibility, but the journey of walking through how to sample and test for group differences in A and B is more complex and a lot of foresight is required to ensure you're comparing groups effectively and fairly. Paul Gustafson taught this class and he really was a master at conveying the concerns in a step wise fashion for AB testing, and reiterated over and over the considerations required for distinct parts of the process from sampling and controlling for group charactersitics to performing many tests (Bonfferoni tests, etc.) and the tentative conclusions that can be drawn from AB tests. I won't go much further into this class but to summarise, it took all of the stats we learned over the last year and showed us how to be aware of how we are applying these techniques. Being good at stats is part knowledge of techniques, but also knowledge of the assumptions you are making in applying those techniques. He did a great job of raising our awareness on the latter.

Third was Privacy and Ethics (**DSCI 541**), which in my opinion was a big of waste of our time. It's not say Data Scientists shouldn't be aware of the concerns that arise from data around individual exposure and hte power of tech companies that essentially monitor their users and sell this knowledge to companies. It's the fact that a lot of what we were taught seemed to be core expressions of ethics that were obvious, and didn't require a class. It devolved more to social and political stances than actual learning about how to address deep privacy concerns, and the discussion would often fall into a moral relativistic tone which felt silly and a waste of my time. The instructor really cared about the class and students opinions on various topics, but I can't say what I learned is indispensible or all that useful in my own work. Companies have their systems in place, I am not there to question their practices in privacy and if I do see something I really don't think the class helped me spot that concern any more than common sense. Ed Knorr made the quizzes really tough because he cares deeply about the course and wants to challenge students, but it was hard to take the course seriously at times because of the points I mentioned above. I did learn about hashing though and how public and private keys actually function on the web, so I've got that in my pocket now.... In general though, would've liked a practical stats class where we apply everything we learned on different problems for a month instead.

Finally, the last class is Advanced Machine Learning Methods (**DSCI 575**) with Varada Kolhatkar. This was her first time teaching, and in general did an awesome job introducing us to high-level topics in ML. We started on Markov and Hidden Markov Models, as well as prepping data for NLP using co-occurrence matrices and n-gram formats. We then shifted to Recurrent Neural Networks and LSTM's, which are used across natural language and quantitative problems and I found the complexity of LSTM's to be quite fascinating. It took me back to my days in neuroscience where we aren'y strictly examine neuronal activation, but the processes within the cell that propogate that signal. LSTM's contain distinct gates that serve different purposes within the single network, and these signals are then passed onto the next network and remembered within the same one. It was a great class in general, the quizzes were quite easy but the labs allowed me to dig deep into Markov and NN models. This block I would say had the best group of instructors of any block, all four were pretty solid people who cared about the students and their digestion of the material.

I can't believe I just finished 6 blocks of coursework, and 24 classes of material. It's been a long journey to this point and the amount of information I've learned is hard to even fathom. I can see the challenge will be to take what I either consciously know or residually still have from early blocks and apply it in my work to formulate the foundation that serves the direction I want to move with a career. I really believe if you do not practice what you learn from this degree you won't retain what you were taught, plain and simple, there is too much to know. That said, you can go any direction you want from here.... viz, ml, stats, software dev even if you want. The personal freedom this knowledge grants is pretty astounding.

Looking back though this degree has given me the tools to move out into the world and apply my knowledge to a variety of problems that all seem interesting. Personally, I love the diversity of applications in ML and the fact it enables other industries to simply perform at a higher level. The diverse applications is what excites me, and so I've been fortunate to take a position as an ML intern for 5 months at a tech consultancy, where I'll be tackling healthcare and business oriented problems and I can't wait to get started. 

I may make a summary post of my thoughts on the degree, and whether I got the value out of the degree that I had thought I would. But for now I'm off to work on my capstone for the next 2 months. I hope some of you found these posts worthwhile if you were applying to MDS, a fellow student in the program or just a curious inquirer. I will definitely be posting more in the future though so stay tuned for that if you enjoyed!