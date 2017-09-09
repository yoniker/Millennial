---
layout: post
title: "How Was It Made"
author: "Yoni Keren"
categories: documentation
tags: [documentation]
image:
  feature: classification_animation4.gif
---

After studying 2 superb Machine Learning courses from Stanford (See Learning Resources if this looks cool!), I wanted to do something in practice. I've figured out that while visual data is complicated, We do understand it very precisly and quickly. My [advisor](mailto:sromanka@tx.technion.ac.il) thankfully allowed me to take that path.

So I took [a third course by Stanford](http://cs231n.stanford.edu/).
Anyways, when I ran [this excellent article's](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/) dataset on a net that I've created as part of the HW,which involved [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) eg I reduced the resolution to 32 by 32 pixels, and using [a hyper parameters search suggested by Bengio](http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf), I got a better performance on the validation set than the original article(!). I'm still not sure if reducing the resolution, when it comes to smaller datasets, improved the overall performance (but I suspect it does).


Using [an Android app that I've coded](https://github.com/yoniker/FBProfiles) I've downloaded over 100K profile pictures which are semi labeled (We know the person's first name, and for most names there's a strong coorelation between the name and the gender).
Using the classifier that I've got before that, it was way quicker to label pictures than doing so manually.

That's it for now. At this point I intend to have as much insight into cases where the classifier fails as I can.



