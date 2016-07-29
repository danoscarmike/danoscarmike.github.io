---
layout: post
title: "Developing a mean MEAN Elo rating application"
date: 2016-07-30
category: post
published: true
comments: true
---
Despite the abundance of political fodder in this week's news I couldn't bring myself to write about it.  The U.S. presidential campaigns are technically only beginning and I am already fatigued.  Instead I have decided to chronicle over a many, quantity to be determined, installments the development of my next project.  For me, an amateur coder this is an ambitious goal but one that encompasses many, maybe all, of my interests - application development (back-end), web development (front-end), statistics (of the Bayesian variety) and sport.

At a high level this is the plan:
+ Develop a statistical algorithm based on the [Elo Rating system](https://en.wikipedia.org/wiki/Elo_rating_system) (name after Arpad Elo, something of a legend it would appear) and incorporating a Bayesian approach to predict outcomes.  
+ The algorithm will be tunable to the nuances of various sporting contests (e.g. rugby, football - Gaelic, soccer, American, Australian) and be applied to an interactive web application serving visualizations predicting the outcome of each week's play.
+ The logic and data will sit in the backend exposed to web and mobile interfaces with an application programming interface (API);
+ Continue my exploration of D3.js in the front end visualizations;
+ Stretch goal: build in user engagement by allowing users to contribute predictions each week.  The user data may be added to the Bayesian analyses;
+ Just for kicks and because I've never done it before I'm going to develop this on the MEAN stack.  (MEAN = MongoDB, Express.js, Angular.js, Node.js);

![Watchoo talking about Willis?]({{site.url}}/resources/blog-images/2016-07-30-watchoo-willis.jpg){: .blog }  '*Traditional*' web development is on the LAMP stack (Linux, Apache, MySQL and PHP) the very idea of Javascript for the front-end && the back-end must have caused quite a few "Watchoo talking about Willis?" moments.  The world moved on and so I can now develop this prototype and name it with a big fat pun: my mean MEAN Elo predictor!
