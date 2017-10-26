# Software Engineering questions from freshers and their answers
Questions we hesitate to ask not to be deemed dumb, stupid or naive.

Can I find popular interview questions?
=======================================
Github repositories of interview questions and solutions

* [Frontend developer interview questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)
* [Awesome interview questions](https://github.com/MaximAbramchuck/awesome-interview-questions)
* [Android interview questions and answers](https://github.com/MaximAbramchuck/awesome-interview-questions)
* [Linux sysadmin/devops questions and answers](https://github.com/chassing/linux-sysadmin-interview-questions)
* [iOS/iPhone developer and designer interview questions](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions)
* [Backend developer interview questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions)
* [Diary of programming puzzles](https://github.com/davidadamojr/diary_of_programming_puzzles)

Popular books for job interviews

* [Cracking the coding interview](http://amzn.to/2yAvtRQ)
* [Programming Interviews Exposed](http://amzn.to/2zClvhp)
* [Cracking the PM Interview](http://amzn.to/2l5Zfth)
* [Elements of Programming Interviews](http://amzn.to/2l3n2JZ)
* [Elements of Programming Interviews in Python](http://amzn.to/2zC0vaE)
* [The Algorithm Design Manual](http://amzn.to/2hRB90e)
* [Elements of Programming Interviews in Java](http://amzn.to/2l2VdSg)

I want to learn programing Android Apps. Where do I start?
==========================================================
Please start with this [brief guide](https://github.com/djinn/Software-Engineering-Questions-and-Answer-FAQ/blob/master/Android.md) 

What is the difference between Server-Side and Client-Side Programing?
======================================================================
This question today falls mostly in context of [web](https://en.wikipedia.org/wiki/World_Wide_Web). In context of web, client which is mostly [browser](https://en.wikipedia.org/wiki/Web_browser), requests server using protocol [HTTP](http://amzn.to/2yzHhSY) to get content. Server Side program would be run on this server to fetch content from database, files or another server. This content is converted for many possible initial formats like [SQL](http://amzn.to/2xPxAgZ), file stream or [JSON](http://amzn.to/2gPILR9) into two dominant forms [HTML](http://amzn.to/2zAdA43) or JSON. All this is done on Server-Side. After result is sent back, on client Client-Side language could pick up this content and further process it for users viewing. 

On server side, Java, PHP, C#, Javascript, Python, Ruby are dominant languages. On client side browser can only execute [Javascript](http://amzn.to/2zxXo3v).

Server-Side often called Backend and Client-Side is mentioned as Frontend.

Github repositories for popular Server-Side frameworks
* Java - [zk](https://github.com/zkoss/zk), [akka](https://github.com/akka/akka), [play framework](https://github.com/akka/akka), [resty](https://github.com/Dreampie/Resty)
* PHP - [laraval](https://github.com/laravel/laravel), [symfony](https://github.com/laravel/laravel), [CodeIgniter](https://github.com/bcit-ci/CodeIgniter), [yii2](https://github.com/yiisoft/yii2)
* C# - [nancy](https://github.com/NancyFx/Nancy), [Piranha](https://github.com/PiranhaCMS/Piranha), [web](https://github.com/neosmart/web)
* Javascript - [express](https://github.com/expressjs/express), [serverless](https://github.com/serverless/serverless)
* Python - [django](https://github.com/django/django), [tornado](https://github.com/tornadoweb/tornado), [bottle](https://github.com/bottlepy/bottle)
* Ruby - [Rails](https://github.com/rails/rails), [sinatra](https://github.com/sinatra/sinatra), [grape](https://github.com/ruby-grape/grape)

Github repositories for popular Client-Side frameworks are
[react](https://github.com/facebook/react), [vue](https://github.com/vuejs/vue), [angular](https://github.com/angular/angular.js), [jquery](https://github.com/jquery/jquery)



I learnt Java in my college. Now I find many people hating Java. Why?
=====================================================================
[Java](http://amzn.to/2xQArq8) was designed for [Object Oriented Programming](http://amzn.to/2yywTuF). In this context, it still has large appeal. Meanwhile, client side applications were transplanted by web applications. Java for this purpose comes across as over-engineered and clunky. The [Java Enterprise framework](http://amzn.to/2gRy5Sn) has lost ground to more agile frameworks like [Express](http://amzn.to/2xRDl2R), [Ruby on Rails](http://amzn.to/2xRM7O6) and [Django](http://amzn.to/2yxtdZV). Because of developer interest in these frameworks, many evolving technologies like [Cloud Computing](http://amzn.to/2yz3MZA), [noSQL](http://amzn.to/2xS4BhK) made heavy bets on these frameworks. There is strong awareness in Java community to walk in-step with current trends and we find frameworks like [Play](http://amzn.to/2xRm1ej) have been build to cater to startup web developer audience. Another technology sector where Java still dominates with [Hadoop](http://amzn.to/2gtknrJ) is [Big Data](http://amzn.to/2xQ1pOv). Java Runtime or Java Virtual Machine is also being used as runtime target by languages like [Scala](http://amzn.to/2yyL9DA) and [JRuby](http://amzn.to/2yTVwVo) because of high performance characteristics.

For writing my new game, should I use DirectX or OpenGL?
========================================================
Based on many informed views, take which ever you find easier to code. [DirectX](http://amzn.to/2yTdG9R) largely restricts you to Windows and Xbox as target. But it is a pretty large target. Arguably, DirectX API is easier to step in and start learning. [OpenGL](http://amzn.to/2xQ6bRf) has a wider support although, it is harder to grapple as a new developer. There are many libararies like [SDL](http://amzn.to/2zzxM6h) which abstract OpenGL for most part but it will not have as wide support base as DirectX.

Before making my site public, what are the basic things to check or implement?
==============================================================================
 The list of things to take care is very large but these are basics which are pretty important

 * Use HTTPS in production since it helps maintain your sites consumers privacy 
 * Hash the password before storing anywhere. Secure the location where users data is stored
 * Validated every input from the users. You never know which input, people can use to escalate priviledges on your site
 * Check each form for cross site scripting. There can be exceptions, just be aware which forms are exceptions

What is the best setup for development, Mac OS X, Windows or Linux?
===================================================================
Preference of Operating System or Setup is very personal. It is effected by ease, constraints or plain fashion. In case of Mac, it has an appeal for previous Linux developers because of its unix roots. Mac is quite popular. Linux and Windows are in no way inferior as development setup. Linux comes with another advantage if you plan to be a backend developer that your setup if closer to production.

As a sidenote: Mac is required for developing iPhone Apps

Tabs vs Spaces for indenting code?
==================================
Frankly there is no right answer. Most large projects like Wordpress, Drupal or Python, define their preferred indentation specs. Also most editors and IDEs have an easily configurable option to switch.

I learnt C++ and C in college. Where can I use it? Why scripting languages like Python seem popular?
====================================================================================================
C and C++ are compiled languages which required involved understanding of data. 

* **Construction** How data will be created? 
* **Type** What will be shape of data?
* **Interface** How data will flow from one module to another?
* **Destruction** When will data be removed from memory?

This takes time. Many software engineering jobs do not provide enough time and Python another scripting languages have far easier data flow requirements. 

C and C++ are still main stay of system programing, where performance matters more than ease of coding.

I have learnt Python. For finding jobs in Python, what are the key skills? What are popular Jobs site?
======================================================================================================
Python is used extensively in the industry. It is rated second in top most languages used in industry. The appeal of language is wide and so is its application. As a very non-comprehensive list of key skills related to python

* Web framework - django, flask
* Database - Psycopg2, pymongo
* Core - urllib2, csv, sys, collections, threading
* Machine learning - Tensorflow, caffe2, sklearn
* Data Analytics - pandas
* Time Series Analysis - zipline

Looking for jobs 

* Python website has a job board
* Django Jobs
* Github jobs
* Stackoverflow jobs
* We work remotely








