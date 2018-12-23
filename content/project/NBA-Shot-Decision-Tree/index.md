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

###### [A case study: Lebron James](https://github.com/ehhope/LBJ-for-Tree)

This project focuses on the 2014-2015 NBA season with a dataset containing characteristics of every shot (shot distance, defender, shot clock, etc.) taken by every player in the NBA. The approach used a decision tree classifier to predict whether a shot was made or missed based on shot features for each shot taken by the player. Lebron James season with the Cavaliers in 2014-15 was used as a case example, however, the script is flexible enough to wrangle, visualize with several plots, and analyze data for any player if specified as an argument.

This project uses ```make``` to run multiple scripts and contains a ```docker``` file for containerization as well. You can find the repository on my github account [here](https://github.com/ehhope/LBJ-for-Tree).
