---
date: '2018-01-03 00:25 +0100'
layout: post
published: true
title: The How and Why of this Website
tags:
  - project
---
Well, I guess the first post on a blog or personnal website is always the more awkward so, here it is. First with the "Why" of this website.

The reason is simple : I wanted a place to put on a few projects I do, practice a little HTML/CSS and design, and basically have a little portfolio available. Since this isn't something I hope to earn something with, I wanted to have little to no maintenance to do. Or 0 maintenance, if possible, since there is a chance I'd get lazy with it. This rules out CMS, due to the need of frequent updates to patch security holes. I also wanted something simple and cheap to host. Again the idea here is to ease maintenance and make it as painless as possible.

The solution chosen here is [Jekyll](https://jekyllrb.com/), a static site generator. To make it short, Jekyll is a tool in Ruby which HTML templates, static resources (CSS, images...) and Markdown files to generate a static website composed of pure HTML. Since the generated website is only composed of static resources, it can be hosted with any web server. Even the most basic hosting services can host such a website. Actually, GitHub proposes a hosting service, [GitHub Pages](https://pages.github.com/), which can be used to deploy a static website for free, provided it is hosted in a public repository. Plus, Jekyll is well supported and [documented](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/).

In terms of development effort, most of the work is concentrated on the setup of the website, to develop the templates of the different pages and the CSS decoration. However, since no content is added in the templates, all HTML files are short and without much complexity, as can be seen in [the repository](https://github.com/P-D-G/P-D-G.github.io). The maintenance of the website mainly includes bugfixes and creation of new post. No interface is provided by Jekyll to add new posts in the same way of traditionnal CMS such as wordpress. As a workaround, I use [prose.io](http://prose.io), which enables me to edit and add markdown files directly in the GitHub repository. GitHub Pages then regenerates the website and add the new content. Using this, I have a setup close to a traditionnal blog, except my interface to add new posts is hosted on a third party service.

All in all, I'm pretty satisfied with this setup :

* The hosting service is free
* The website is static, so very few updates required
* I have a web interface to add posts

However, there is still a few things lacking :

* No comment system - which isn't that bad, since no comment are really needed at this point
* No hand on the web server, which remove pretty much all possible performance tweakings
* Basically, if I want something, I have to get my hands dirty, but this is fine.

And we'll see in the future how well it holds!
