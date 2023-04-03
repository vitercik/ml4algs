---
layout: home
title: Machine Learning for Algorithm Design (MS&E/CS 331, Spring 2023)
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: MS&E/CS 331
---

# Machine Learning for Algorithm Design (MS&E/CS 331, Spring 2023)

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Description

Machine learning has become a powerful tool for algorithm design. This is because in practice, we often have ample data about the application domain in which the algorithm will be used---data that can be used to optimize the algorithm's performance. This course covers how machine learning can be used within the algorithm design pipeline from a variety of perspectives, including how to design novel algorithms with machine-learned modules and how to configure existing algorithms' parameters to optimize performance. Topics will include both applied machinery as well as theoretical tools for providing provable guarantees. The format will include equal-parts lecture and discussion.

## Getting Started

Getting started with Just the Class is simple.

1. Create a [new repository based on Just the Class](https://github.com/kevinlin1/just-the-class/generate).
1. Update `_config.yml` and `README.md` with your course information. [Be sure to update the url and baseurl](https://mademistakes.com/mastering-jekyll/site-url-baseurl/).
1. Configure a [publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages). Your course website is now live!
1. Edit and create `.md` [Markdown files](https://guides.github.com/features/mastering-markdown/) to add more content pages.

Just the Class has been used by instructors at Stanford University ([CS 161](https://stanford-cs161.github.io/winter2021/)), UC Berkeley ([Data 100](https://ds100.org/fa21/)), UC Santa Barbara ([CSW8](https://ucsb-csw8.github.io/s22/)), Northeastern University ([CS4530/5500](https://neu-se.github.io/CS4530-CS5500-Spring-2021/)), and Carnegie Mellon University ([17-450/17-950](https://cmu-crafting-software.github.io/)). Share your course website and find more examples in the [show and tell discussion](https://github.com/kevinlin1/just-the-class/discussions/categories/show-and-tell)!

### Local development environment

Just the Class requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler. To setup a local development environment, clone your template repository and follow the GitHub Docs on [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).
