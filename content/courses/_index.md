---
type: courses
title: Courses 
description: |
  compilation of course materials
author: Jo Hardin
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only
show_author_byline: true
show_post_date: false
# for series listing page layout
layout: list-sidebar # list, list-sidebar, list-grid
featured: true

# for list-sidebar layout
sidebar: 
  title: Where can I find things?
  type: courses
  author: Jo Hardin
  description: |
    Most of the course materials are here.  For many classes, there is also a textbook (typically available online for free).  All solutions (HW, exams, etc.) will be posted on Sakai.  Please join the class Discord channel (see sign-up information on Sakai).
  text_link_label: all courses
  text_link_url: /courses/
  show_sidebar_adunit: true # show ad container

# set up common front matter for all individual pages in series
cascade:
  type: courses
  layout: single-series       # for a series, do not change
  author: Jo Hardin
  show_author_byline: true
  show_post_date: true
  sidebar:
    text_link_label: all courses
    text_link_url: /courses/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the series _index. This file is a leaf bundle, and provides settings for the listing page layout and sidebar content.**