---
layout: post
title: automated twitter memes
topics: [Python, PIL, social media]
description: In this project we automate the process of creating a Twitter-screenshot meme. The goal of this project is to create an interface that we can use to automate the process of making memes given a collection of (string, image) tuples.
---

The goal of this project is to automate the process of creating the basic Twitter-screenshot style meme.

### motivation

What I like to call the "Twitter-screenshot meme" is a meme format that was invented by taking a screenshot of a tweet with an image attachment. For example, the following image is a Twitter-screenshot meme: 

![](img/figs/meme-maker/meme.png){:class="img-responsive" height="300px" width="300px" align = "center"}

To format this way, I would go through these steps:

1. Open Twitter on my phone
2. Compose a new Tweet and attach an image
3. Post the Tweet
4. Take a screenshot of the Tweet
5. Crop the screenshot to a square

I was able to go through these steps in about 45 seconds when I had a string of text and image ready.

Normally, I would want to create about 7-9 of these memes for each account at the beginning of the week, and then post once or twice a day throughout the week. I had 5 accounts so this would take me around 30 minutes a week *just doing the mechanical work of steps 1-5*. 

### getting Started

Clone:
```git clone https://github.com/evmarts/meme-maker.git```

Run the script:
```python meme-maker.py```

#### prerequisites

- Python

### built With

* Python Imaging Library (PIL)

### examples

Suppose we have a string of text, an image and we would like to make a meme out of them:

```
You win this round, cheese
```
![](img/figs/meme-maker/img.jpg){:class="img-responsive" height="300px" width="300px" align = "center"}

Once the image is stored in the  ```in/``` directory, we can run the Python script: 

~~~
$ python meme-maker.py
path of image to use: in/img.jpg
enter a caption: You win this round, cheese
saved image as: meme.png
~~~

and the image *meme.jpg* will be stored in the ```out/``` directory:

![](img/figs/meme-maker/meme.png){:class="img-responsive" height="300px" width="300px" align = "middle"}


### authors

* Evan James Martin