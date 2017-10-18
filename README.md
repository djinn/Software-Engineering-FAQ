# FAQ about Software Engineering for new developer
Questions which occur to us however we hesitate to ask

What is the difference between Server-Side and Client-Side Programing?
======================================================================
This question today falls mostly in context of web. In context of web, client which is mostly browser, requests server using protocol HTTP to get content. Server Side program would be run on this server to fetch content from database, files or another server. This content is converted for many possible initial formats like SQL, file stream or JSON into two dominant forms HTML or JSON. All this is done on Server-Side. After result is sent back, on client Client-Side language could pick up this content and further process it for users viewing. 

On server side, Java, PHP, C#, Javascript, Python, Ruby are dominant languages. On client side browser can only execute Javascript.

Server-Side often called Backend and Client-Side is mentioned as Frontend.

I learnt Java in my college. Now I find many people hating Java. Why?
=====================================================================
Java was designed for Object Oriented Programming. In this context, it still has large appeal. Meanwhile, client side applications were transplanted by web applications. Java for this purpose comes across as over-engineered and clunky. The Java Enterprise framework has lost ground to more agile frameworks like Express, Ruby on Rails and Django. Because of developer interest in these frameworks, many evolving technologies like Cloud Computing, noSQL made heavy bets on these frameworks. There is strong awareness in Java community to walk in-step with current trends and we find frameworks like Play have been build to cater to startup web developer audience. Another technology sector where Java still dominates with Hadoop is Big Data. Java Runtime or Java Virtual Machine is also being used as runtime target by languages like Scala and JRuby because of high performance characteristics.

For writing my new game, should I use DirectX or OpenGL?
========================================================
Based on many informed views, take which ever you find easier to code. DirectX largely restricts you to Windows and Xbox as target. But it is a pretty large target. Arguably, DirectX API is easier to step in and start learning. OpenGL has a wider support although, it is harder to grapple as a new developer. There are many libararies like SDL which abstract OpenGL for most part but it will not have as wide support base as DirectX.

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








