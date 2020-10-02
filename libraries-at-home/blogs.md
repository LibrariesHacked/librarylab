---
layout: default
title: Read blogs
nav_order: 3
has_children: false
parent: "Prototype: libraries at home"
---

# Read blogs

Read the latest blog posts from library services
{: .fs-6 .fw-300 }

This page provides a listing of the latest blogs from library services, automatically updated through the use of [RSS feeds](https://en.wikipedia.org/wiki/RSS).

![A screenshot of the blogs page on the libraries at home site showing an example list of latest blog posts from library services](https://raw.githubusercontent.com/librariesHacked/librarylab/master/assets/images/prototype-librariesathome-read.PNG)

## Data source

This page makes use of two fields in the [library services shared spreasheet](https://airtable.com/shrKkzYDUNMMM6qrJ).

* Blog RSS Feed
* Blog URL

A webservice aggregates all the blog RSS feeds together to display a list of the latest posts from library services.

1. Posts are ordered into columns with the latest first
2. The most recent 8 blogs are shown

