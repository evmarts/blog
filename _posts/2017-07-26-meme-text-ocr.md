---
layout: post
title: Recognizing Text from Memes
---

The goal of this project is to recognize the text in an image of text. 

This project is also the second stage of [another project.](https://github.com/evmarts/meme-recycler)

## Motivation

In a [previous project](https://github.com/evmarts/meme-cropper), images of memes were partitioned into a text component and an image component: 

![image-title-here](/blog/_img/figs/meme-text-ocr/fig1.jpg){:class="img-responsive"}


We may want to convert the text component into a string so that we can reuse, modify or analyze it. 

## Getting Started

Follow the instructions [here](https://github.com/tesseract-ocr/tesseract/wiki) to install tesseract optical character recognition.

Clone:
```git clone https://github.com/evmarts/meme-text-ocr.git```

Run the script:
```python meme-text-ocr.py```

### Prerequisites

- Python

- tesseract ocr

## Built With

* [tesseract ocr](https://github.com/tesseract-ocr/tesseract) - The optical character recognition engine used

* Python Imaging Library (PIL)

## Examples

Suppose we have the following meme:


![image-title-here](/blog/_img/figs/meme-text-ocr/sample_meme.jpg){:class="img-responsive"}

Assume we have [some way](https://github.com/evmarts/meme-cropper) of partition the meme into two components,

an image component,

![image-title-here](/blog/_img/figs/meme-text-ocr/sample_meme_image.jpg){:class="img-responsive"}

and the text component, say *text.jpg*,


![image-title-here](/blog/_img/figs/meme-text-ocr/fig2.jpg){:class="img-responsive"}

After placing the image of the text in the ```in/``` directory, we can run the script:

~~~
evmarts$ python meme-text-ocr.py
Image of text to recognize: in/text.jpg
~~~

The script then outputs the following: 

~~~
Text recognized as: 'When you call shotgun but end up in the back'
~~~


## Authors

Evan Martin

## Acknowledgments

* Tesseract Open Source OCR Engine