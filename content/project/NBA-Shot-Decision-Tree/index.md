+++
title = "NBA Shot Classifier"
date = 2018-12-23T01:26:14-07:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ['supervised learning', 'NBA', "Lebron James", "decision tree"]

# Project summary to display on homepage.
summary = "A shot analysis of NBA players using a decision tree classifier of makes/misses from the 2014-15 season."

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{https://github.com/ehhope/LBJ-for-Tree}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

### Decision Tree Analysis of Makes & Misses in the NBA

###### A case study: Lebron James

This [project](https://github.com/ehhope/LBJ-for-Tree) focuses on the 2014-2015 NBA season with a dataset containing characteristics of every shot (shot distance, defender, shot clock, etc.) taken by every player in the NBA. The approach used a decision tree classifier to predict whether a shot was made or missed based on shot features for each shot taken by the player. Lebron James season with the Cleveland Cavaliers was used as a case example, however, the script is flexible enough to wrangle, visualize with several plots, analyze and report data for any player if specified as an argument when using ```make```.

Our decision tree classifier predicted Lebron James at a marginal ~65% when hyperparameters were optimized, however, other players we were able to score upwards of 85%. The reason for the model's poor accuracy with Lebron James, Steph Curry, and other top shooters is that the features don't segregate makes/misses as cleanly as players who are reliably poor shooters based on changes in particular features such as shot distance. An NBA center will struggle to shoot long range shots, therefore when shot distance increases, our classifier is quite accurate in predicting the outcome.

This project is also reproducible through ```docker```. Inside the repository linked below, you will find a dockerfile with instructions for running all of the scripts with their respective dependencies (R and python libraries). If you don't have all of the dependencies installed locally that's ok, just use the dockerfile written to run the scripts in the container provided.

For easily reproducing and generating data regarding NBA players, this project uses ```make``` to run multiple scripts in terminal as well. If interested, you can find the repository on my github account [here](https://github.com/ehhope/LBJ-for-Tree) with instructions in the README file for using these tools.
