---
layout: post
title:  "Hello Docker World"
date:   2017-12-04
description: Hello Docker World! In this tiny blog I wanted to share my notes on the process of moving from system that is built on .NET framework, MVC Apps into docker.
---

<p class="intro"><span class="dropcap">D</span>uring my daily work I lead a team of awesome Developers that build a distributed .NET-based system. There are Angular 4 web apps, there are topshelf-based Windows services, there is lots of messaging. In this blog I wanted to rehearse possibilty of moving our efforts to docker.  </p>

## Problem statement

My plan is to go through natural steps that usually one has to go through when dockerizing app. 

1. Set up docker on Windows
2. Dockerize sample windows service
3. Dockerize web app

_(I will probably keep getting back to this list and edit it so that it becomes table of contents)_

Most of the topics covered here are inspired by set of blog posts, presentations, and <a href="https://www.amazon.com/Docker-Windows-Elton-Stoneman-ebook/dp/B0711Y4J9K/">book</a> written by <a href="https://twitter.com/eltonstoneman">Elton Stoneman</a>. Also the direction in which I try to push our Windows apps are driven by Elton's samples. 
