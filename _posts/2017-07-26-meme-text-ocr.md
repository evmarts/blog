---
layout: post
title: recognizing text from memes
---

The goal of this project is to recognize a string of text in an image of text. 

### motivation

In a [previous project](https://github.com/evmarts/meme-cropper), images of memes were partitioned into a text component and an image component: 

![](img/figs/meme-text-ocr/sample/meme9_contours.jpg){:class="img-responsive" height="300px" width="300px" align = "center"}

We may want to convert the text component into a string so that we can reuse, modify or analyze it. 

### getting Started

Follow the instructions [here](https://github.com/tesseract-ocr/tesseract/wiki) to install tesseract optical character recognition.

Clone:
```git clone https://github.com/evmarts/meme-text-ocr.git```

Run the script:
```python meme-text-ocr.py```

#### prerequisites

- Python

- tesseract ocr

### built With

* [tesseract ocr](https://github.com/tesseract-ocr/tesseract) - The optical character recognition engine used

* Python Imaging Library (PIL)

### examples

Suppose we have the following meme:

![](img/figs/meme-text-ocr/sample/sample6.jpg){:class="img-responsive" height="300px" width="300px" align = "center"}

Assume we have [some way](https://github.com/evmarts/meme-cropper) of partition the memes into two components:

A text component and an image component:

![](img/figs/meme-text-ocr/pics/sample6pic.jpg){:class="img-responsive" height="300px" width="300px" align = "center"}

![](img/figs/meme-text-ocr/fig2.jpg){:class="img-responsive" align = "center"}

After placing the image of the text in the ```in/``` directory, we can run the script:

~~~
evmarts$ python meme-text-ocr.py
Image of text to recognize: in/text.jpg
~~~

The script then outputs the following: 

~~~
Text recognized as: 'When you call shotgun but end up in the back'
~~~

### authors

Evan Martin
