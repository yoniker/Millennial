---
layout: post
title: "Installation Guide"
author: "Yoni Keren"
categories: documentation
tags: [documentation]
image:
  feature: classification_animation7.gif
---

### Installation Guide


Once you have all the required packages, all you need to do is clone the files I've provided:

```sh
git clone https://github.com/yoniker/Gender-Classifier
```
After that you can literally put any jpg file into the 'test' directory (I've provided one image for you), and then run

```sh
python3 classify.py
```


### Required Packages

- PyTorch (with gpu support) [btw- TensorFlow shouldn't be anyone's first choice](https://www.quora.com/Which-deep-learning-framework-TensorFlow-or-PyTorch-should-I-choose/answer/Yoni-Keren)
- Torchview
- OpenCV
- dlib
- imutils (the face alignment algo (see the 'how was it done' section) is based on [this nice blog post](http://www.pyimagesearch.com/2017/05/22/face-alignment-with-opencv-and-python/))


### Still have questions?

Feel free to [contact me.](/pages/contact.html)
