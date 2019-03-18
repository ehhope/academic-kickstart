+++
title = "MDS Block 2"
date = 2018-12-25T01:43:24-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alex Hope"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["UBC","MDS","Data Science", "Grad School"]
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
My experience and thoughts on block 2 of MDS at UBC. The courses were: DSCI 512, DSCI 523, DSCI 531, and DSCI 552. <!--more-->


## **Introduction to Block 2**

I want to break down my thoughts for this block course by course because I have a lot to say, and it doesn't neatly cut across topics, not to mention, my experiences with courses in this block were quite different. First, a few general thoughts before I dive in. I got the most out of courses that I invested myself in, plain and simple. While that seems like a common trope, it really holds true in data wrangling, and algorithms & data structures where the degree of difficulty is quite high in the content, and the lecturer is forced to feed you complex material quickly given the time constraints. The content in a couple courses was quite difficult, and I found myself scrambling two of the four weeks to get my labs in despite putting a ton of effort into my labs. Learning these skills and forms of thinking requires considerable persistence, and for that reason I was ok with barely finishing. This material is ***supposed*** to be difficult! That's the point! So with that expressed let me talk about each class.

### **Algorithms and Data Structures (DSCI-512: Patrice Belleville)**

This was undoubtedly the most difficult course of the block, and the concepts were at times challenging to grasp. The reason they were hard to follow was primarily because of the speed of the curriculum where we would cover hash tables in 25% of one lecture, and touch on different forms of search trees for the rest of lecture before diving into a single lecture on various kinds of directed and undirected graphs. The material was complex but still digestible, and Patrice was a strong instructor, but the time constraints placed a significant burden on people's learning where there was a tendency to learn to get through the course rather than learn to absorb the material of the course for future reference. When the material scales up significantly in difficulty, this was a common feeling in students and I certainly felt it at times as well. For perspective on the pace, undergraduates will spend an entire semester or two examining the full range of material we covered in a single month. This is not only a huge challenge for students, but also the instructor to curate the material and emphasize what is only crucial while discarding or grazing briefly on an area.

In addition to the pace, there was a huge gap between the lecture material and the questions being asked in labs where the content we covered needed to be implemented but in a way that was far beyond the coding ability of most of the cohort. Given the general class response I knew I wasn't alone in struggling to apply my understanding of recursion to sierpinski's triangle, or image resizing, but I also secretly enjoyed confronting this massive challenge. This was not an easy introduction to algorithms and how they are implemented in data structures, and I need to learn more on these topics after finishing this class to round out my learning given their importance in data science, but I felt it was more of a structural issue with the disconnect between lecture material and lab material than Patrice's poor teaching that really left me with this impression.

To excel in this class you need a strong familiarity with object oriented programming, and should possess an aptitude for reading code that is likely more complex than you can write at this stage. I saw this class as a tough challenge that elevated my thinking on the topic, but didn't provide enough scaffolding to really help me understand the mechanics of how every algorithm worked or how they were implemented in different problems in the labs such as with facebook data that was provided in one lab. That said, if you listen in class you will walk away with an understanding of breadth-first vs depth-first search trees and how they are represented in python. And the different forms of searching whether with rote methods or through recursion. In addition, we spent considerable time looking at how different kinds of graphs can represent information about individual entities, as well as the relationships between these entities. In some cases they were bi-directional and others they were uni-directional depending on the flow of information. The big picture here was, if we wanted to model an algorithm after a particular social media site, or scheduling problem, what would we choose? This high-level planning requires you to know the details about how information is exchanged, referenced and what graphs will and will not allow as far as the flow of that data.

This class really could've been more effective if it had students with a higher coding literacy, and I would beg the instructors to consider scaling up the intro coding classes in block 1 to cover OOP in greater depth and have students write functions sooner in DSCI 511 so they can approach difficult questions in labs with greater confidence. Having to learn to code on top of understanding the algorithms can be daunting, and it would serve all parties involved to make this change I think.

While it seems like I have a lot to say that's negative, part of being a student is also embracing challenge and uncertainty. I learned a lot in this class because I felt like I had to in order to do well, and that pushed me to invest more of myself in it than other classes where I felt it was easier to grab the content quickly and implement the knowledge. Here, I had no choice but to study hard, and that's what being a graduate student is all about..... digging deeper.

### **Data Wrangling (DSCI-523: Jenny Bryant)**

Data wrangling is a fundamental skill in data science, and that is a fact. A significant portion of your time as an analyst will be spent simply preparing a dataset for analysis and deep exploration. Whether it's changing the type of data in columns, creating 2 columns out of information contained in a single column, creating columns that are aggregates of other columns, joining different tables together, or simply grouping variables together to extract meaning when grouped by their factor, data wrangling really matters and it won't take you long to see why.

I enjoyed this class the most of any course in the block and perhaps to date in this degree. It was difficult and frustrating at times banging my head against a problem that required multiple joins or a function I wasn't used to applying like ```lag```. Let's just say I had to take many breaks from the computer to finish these labs but out of this immense frustration was an extreme sense of reward when I would learn to parse data in that column, or adjust the time with respect to timezone, or just manipulate data how I intended. I felt powerful, and these are pivotal skills you need to know.

Having no experience in R prior to this degree, I couldn't imagine a smoother experience wrangling than with the ```Tidyverse```. It's reputation exists for a reason, it's straight forward and sensical to beginner wranglers and our instructor (Jenny Bryant) is the maintainer of this entire package. Most of all, I was really learning a tangible skill that is readily applicable to personal projects and were employable skills. Along with visualization, it instilled a feeling that I could start to hit the ground running on projects and make reasonable progress working with any data I encountered. The course also provided immediate feedback to me on my abilities and I found that to be quite reinforcing in a way that a class like probability or algorithms was not.

As far as Jenny Bryant, her reputation also speaks for itself. She is a world class instructor with quality lecture materials, resources and a great sense of humor that kept me connected to the class and her teaching. I know the cohort genuinely found her lectures to be intriguing, helpful, and balanced in their difficulty as well, introducing us gradually to more and more complex wrangling techniques. It was a pleasure to have her for this class and reassuring that someone heavily involved in the maintenance of the ```Tidyverse``` was teaching us how to use it.

You may be thinking well wait.... what about Python? We covered Python's ```Numpy``` and ```Pandas``` in one class taught by Mike Gelbart, which in my opinion deserved a second lecture given how much Python will be used in ML blocks coming up but mainly focused on R in this class. I believe the thinking was that we can always wrangle in R prior to analyzing in python and while that is fair, python is such a prominent language it would be nice to attend to it's wrangling libraries as well. Admittedly, I didn't really learn anything new in this lecture simply because I knew the Pandas library quite well already. Nonetheless, I am much more confident in my wrangling abilities and genuinely enjoy the challenge of reshaping datasets.

For anyone taking this class, you will be well acquainted with how to join different datasets based on particular keys and the type of join you want, how to select particular information in a dataframe, what a tibble is compared to a dataframe, how to add columns, delete data and replace NA's. All of these things are important skills to possess, and I felt for the month we spent wrangling, we covered this material very well. I banged my head on the practice problems enough that the material was seamlessly drilled into my head, and it was so worth it. These are skills anybody working with data will continue to use in the future.

### **Visualization I (DSCI 531: Vincenzo Coia)**

In general, I thought Vincenzo did a great job with this class. He took us through basic graph theory as far as what various plots convey in their variables and information, but also gradually taught us the relevant syntax for ggplot, which has become a personal favourite for visualizing data. Also, graphing data to gather a sense of patterns is under appreciated and not talked about enough. A common mistake is to want to start analyzing immediately and rely on visualizations for the final results to convey information, but Vincenzo really taught me a lot about patience and understanding data through graphs PRIOR to starting any analyses. Get to know what you are working with before investing your time with analysis! Similar to wrangling, we were only introduced to Matplotlib (Vincenzo) in one lecture and Seaborn (Chris- TA) in another lecture. I got a lot out of the Seaborn lecture from Chris, and was relieved to see visualizations in Python can be as easy as in R, but would have loved to see a bit more with respect to python here to round out the class.

Overall, Vincenzo is a fantastic post-doc who is extremely knowledgeable in R and can convey the basics of graphing extremely well. The only recommendation I have for him as an instructor is to consider a lecture through the lens of a new analyst that wants to understand relationships in the data they have. How can they go about this graphically? What should they look for in the data, what plots should they try, how many different graphs should they plot to get a sense of any patterns? Some form of exploratory thinking would go a long way in adding substance to the syntax we learned and provide much needed direction to students who lack this internal compass. Other than that though he was a good lecturer and whether you have the intuition to explore data or not, anyone who took this class can write the syntax to accomplish what they need.

You'll know what kinds of information bar graphs, scatterplots, pie graphs, box plots, word clouds, heatmaps, and map graphs represent and what variables are required to create these visualizations. Also, you'll learn about the ingredients of graphs, so what is the x and y-axis? Are the scales on a log, or normal axis? Can you facet by a certain group to convey multiple plots within a single graph that are separated by group? These sorts of considerations are all touched on intelligently in lecture, and you'll feel comfortable graphing anything basic that you need by the end. Looking forward to seeing what Data Visualization II has in store for us.

### **Statistical Inference I (DSCI 552: Tiffany Timbers)**

First, Tiffany teaches clearly and crisply with great lecture examples that offer insight into her labs directly, so attending her lectures is informative for the work you'll be doing outside of them. She's also a dynamic instructor that educates with class coding, group discussion, and through classic speech and it definitely helped with holding my attention on a topic that doesn't exactly grab most people's focus at first glance.

Bootstrapping is a powerful method for inferring about the meaning of a sample by generating thousands of samples and comparing your original sample test statistic with ones generated from other samples that were bootstrapped. When you do this you get a distribution of test statistics that resembles a normal distribution. This is how you can begin to compare whether there is anything special with your sample in comparison to the many others you've generated.

While the relevant test statistic you are calculating and assumptions made with a t-distribution (CLT) was nothing new, I still learned the syntax for t-tests, confidence intervals and p-values through ```R```'s ```infer``` package. It was nice to run over basic stats with Tiffany, and learn about applying bootstrapping as a technique in R, but I also recognize the need for more practice to hammer in these concepts on real live datasets where I'm generating my own null/alternative hypotheses and running t-tests and anova's. ```R``` is such a powerful statistical language and can do so much of the heavy lifting for you, just ensure you know what you're entering for inputs and how to read the output of your functions.

Any student that finished this class can tell you what a p-value is and what it signifies with respect to a z-score or t-value in the context of a normal distribution, and what assumptions about normality and standard error exist. Overall, this was a solid class that was a helpful review and introduced us to how R can make our lives infinitely easier once we understand the theory.

### **Closing Thoughts on Block 2**

My overall impression was positive here, there were far more great moments where I felt absorbed by what I was learning than awful ones where I'm overwhelmed but I'd be lying if I said this was an easy block. The feeling of drowning in information is part of diving into a new area, let alone one that is extremely complex, new as a field, and constantly evolving like data science. Block 2 definitely felt like a deeper dive into new territory and you can tell the material has started to take an upward incline in difficulty but I felt like I rose to the occasion and as the difficulty increases you can really start to see the value in what you're learning and how it can be applied. This is itself quite motivating, and definitely helps you see the finish line as far as the skills you'll possess and will be required of you beyond this degree. I grew so much with R in this block, despite having serious doubts about it as a language that I would enjoy using in my work. Now, ```infer```, ```ggplot```, and ```dplyr``` have completely changed my mind and I will happily use the Tidyverse for future work.

At a broader level, the terrain we covered feels like the elementary, foundational skills for data science, and looking at the block 3 course curriculum I'll be curious to see how things progress to the higher-level concepts with regression and machine learning.

One major piece that continues to stick with me is the timing of this degree. If this degree was even 6 weeks longer and the curriculum was the same, I think everything would feel a bit less rushed and I'd have the time to absorb aa bit more deeply. Don't get me wrong, I am learning a ton, but anytime you try and integrate as much info as this degree demands, you are bound to forget things along the way if it is not used. It's an inevitable downside of the human brain, but that said I'm glad I've squeezed what I could and as it stands I know the material extremely well and will continue to as long as I use it.

What a month it was and onto the next block we go! Until next time....
