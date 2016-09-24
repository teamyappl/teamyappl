---
layout:     post
title:      "Creating a yappl blog post"
subtitle:   "Guide"
date:       2016-09-23 21:00:00
author:     "Max Meldrum"
header-img: "img/posts/creating-posts/bigcity.jpg"
comments: true
tags: General
---

# Creating a blog post


The site is hosted using jekyll and github pages. To contribute with a blog post, all you have to do is to fork the github repo and then create a pull request with the added content.

The repo can be found here [Teamyappl](https://github.com/teamyappl/teamyappl.github.io)

Inside the _posts directory you can see the current posts. The blog posts are made using Markdown, if you are new to it then you can check how the other posts have been made. If you want to add a custom image then you will just have to download one and store it in the img folder.


## Making changes locally

Before creating the pull request, ensure that the site is correctly served. To host it locally you need to install some things.

First of all you need to install jekyll.


    # Installing through gem
    gem install jekyll bundler

Next NodeJS needs to be installed.

    # For systems such as Debian and Ubuntu
    apt-get install nodejs


Assuming you are in the root folder of the repo. 
   
    # Install dependencies
    bundle install
    # Host site at localhost:8888
    bundle exec jekyll serve



## Finishing stuff

1. You can run jekyll on Windows but it seems a bit harder to get up and running.
2. One important thing to notice is that the Markdown files has to have the format YEAR-MONTH-DAY-title.md, otherwise jekyll wont serve it.

If this post made no sense then head over to the [jekyll homepage](https://jekyllrb.com/)

/ Max






