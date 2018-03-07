---
author: "Evan Gaustad"
date: 2018-03-06
linktitle: Detecting Similarity
next: /tutorials/github-pages-blog
prev: /tutorials/automated-deployments
title: Detecting Similarity
weight: 10
---


## Introduction

As defenders, our job is often to analyze suspicious activity and determine whether or not we can reliably detect or prevent the adversary's activity.  By far, the most common way this is done in practice is with regular expressions.  Regular expressions for pattern matching is absolutely a valid technique that can get us very far, very fast.  But in no means is it the right tool for every job.

In this post, we'll explore a number of other options that can be used to detect whether other events or data is similar to example events we'd like to find.

## Follow Along

If you'd like to follow along with the examples in this post, pull down the Jupyter notebook [on github](https://github.com)

Install Jupyter Notebook and start up the server:

```
$ pip install jupyter
$ jupyter-notebook
```


