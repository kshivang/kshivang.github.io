---
layout: post
title: First post
date: 2017-11-21 11:00:00 +0530
categories: posts
comments: true
description: Yet another Blogger
keywords: "firstpost, first post, Blog, kshivang, github.io, Shivang, Kumar Shivang"
authors:
    - Kumar Shivang
---

Greetings readers, I made this blog to share my day to day work progress and my entrepreneurial journey.
This is my **third attempt** to make my personal blog. 

## Androidonism

My first blog was **Androidonism**, idea was to make my personal technical blog where I shall be sharing all of my android know-how. 

I choose [Google-Polymer](https://www.polymer-project.org) as framework due to following reasons :
* It is great way to make [*Progressive Web App*](https://developers.google.com/web/progressive-web-apps/)
* It is [*Angular JS*](https://angularjs.org) library
* It has [*Material Design*](https://material.io) support
* It is [*Google-Project*](https://opensource.google.com/projects/explore/featured)

I will talk about polymer in detail in some other post.
Polymer is way to much complex for simple task like Blogging. At the end though I was able to complete my blogging progressive website, but it was static. Contents were hard coded inside Polymer-components, due to which editing or updating new content was hard. To make it dynamic I have to connect it to some database,and then I should be making another interface to edit database for new post update. That time polymer was very new library, there was very few documentation available, and I was also very naive to web-technology, so never done that.


## [IITK Webpage](https://home.iitk.ac.in/~kshivang)

All of us at [IIT, Kanpur](https://www.iitk.ac.in) get webspace about 50 MB for personal webpage. At first I used this webspace for testing my Hostel([**Hall 2**](https://www.iitk.ac.in/hall2)) website that I was building and maintaing in my second year, then I used that space for second Blog cum Webpage. Since I had constraint of using 50 MB, and restricted scripts. I decided to make barebone and light-weight. I used simple Bootstrap4. And complted the website in less than 1MB. I used rest of the space to host Unity3D built game Space Shooter, Resume, and posts. 

Again in this project problem remain the same, website was static and whenever I have to update anything I have update the whole site, though updating simple modular HTML was easier than updating tightly copouled angularJS.

## [Kshivang Github IO](https://kshivang.github.io)

Finally I developed this blogger after realising the need of blogs to showcase as well track everyday gist. I decided to use old but reliable way to make blogs that is [Jekyll](http://Jekyllrb.com). It is a blog-aware, static site generator in Ruby. Though this also genereate static sites, but it convert markdown file to html code and markdown is greate way to document anything as it is like extension to plaintext.

And after employing continuous integration it can be conneted to storage buckets as well hence blogger can automatically detect new post and updates.

It also has a great plugin support, so I can leverage social plugins to connect my blogs to social sites like facebook, and likedin.



