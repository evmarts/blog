---
layout: post
title: creating a web app that helps increase user engagement on Instagram accounts
topics: [node.js, express.js, react.js, PostgreSQL, Heroku, Surge.sh]
description: In this project we set up a web application that communicates with Instagram to host a leaderboard that ranks participants based on their level of engagement with a particular Instagram account. 
preview: img/figs/leaderboard/leaderboard-arch.png
---

The goal of this project is to host a leaderboard to facilitate a contest on an Instagram account. The leaderboard will rank contestants based on how much they engage with the account. 

### motivation

We want to drive engagement on an Instagram account. 

### how it works

The leaderboard communicates with the Instagram API to give us access to the data pertaining to the Instagram account hosting the contest. We are then able to look at this data and award points to the users who engaged with the account. 

### architecture

The architecture of the system consists of four main entities:

1. **Instagram** is where users engage with the account. This system uses the ```instagram-private-api``` project to communicate with Instagram 
2. **leaderboard-api** is the back-end of the system. It talks to Instagram, updates a database and supplies data to the front-end. It is hosted on Heroku.
3. **Postgres database** is where we keep all the data for the leaderboard. It is also hosted on Heroku. 
4. **leaderbaord-app** is the front-end of the system (this repo). See the *Example* section below for what it looks like. It is hosted on Surge.

![](img/figs/leaderboard/leaderboard-arch.png){:class="img-responsive" align = "center"}

### examples

The following is an example of a contest held on one of my Instagram accounts:

![](img/figs/leaderboard/leaderboard.png){:class="img-responsive" align = "center"}

### authors

* Evan James Martin