---
layout: post
title: Batch Watermarking Images
---

The goal of this project is to automate the process of adding a simple watermark to an image.

## Motivation

The sharing of images on social media platforms has become notorious for the recycling of content amongst their users. If a user has posted an image that has gained popularity, other users will see the success of the image and post it to their own account in hopes of attracting more followers to their account. This is usually done without credit to the original user. 

A common strategy is for the original poster to watermark their userhandle in their image to retain some credit for their content.


## Getting Started

Clone:
```git clone https://github.com/evmarts/watermarker.git```

Run the script:
```python watermarker.py```

### Prerequisites

- Python

## Built With

* Python Imaging Library (PIL)

* Python textwrap module

## Examples

Suppose we have the following images we would like to watermark with our usersname, *@userhandle*:

<img src="../blog/_img/figs/watermarker/meme0_clean.jpg" alt="fig1" height="42" width="42">

![image-title-here](/blog/_img/figs/watermarker/meme1_clean.jpg){:class="img-responsive"}

After placing the images of the text in the ```in/``` directory, we can run the script:

~~~
 evanmartin$ python watermarker.py
Enter watermark text: @userhandle
Enter a location to place the watermark on the image: (1-9)
  locations: 
  1 | 2 | 3 
 ----------- 
  4 | 5 | 6 
 ----------- 
  7 | 8 | 9 
4
Watermark added to meme0.jpg
Watermark added to meme1.jpg
~~~

![image-title-here](/blog/_img/figs/watermarker/meme0_marked.jpg){:class="img-responsive"}![image-title-here](/blog/_img/figs/watermarker/meme1_marked.jpg){:class="img-responsive"}


## Authors

Evan Martin