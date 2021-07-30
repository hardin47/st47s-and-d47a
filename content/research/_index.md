---
type: research
title: Research projects
description: |
  so many fun projects, so little time
author: "Jo Hardin"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
show_post_time: false
# for listing page layout
layout: list # list, list-sidebar

# for list-sidebar layout
sidebar: 
  title: Research projects
  description: |
  
    Check out the _index.md file in the /research folder 
    to edit this content. 
  author: "Jo Hardin"
  text_link_label: research
  text_link_url: /research/_index.md
  show_sidebar_adunit: true # show ad container

# set up common front matter for all pages inside blog/
cascade:
  type: research
  author: "Jo Hardin"
  show_author_byline: true
  show_post_date: true
  show_post_time: false
  show_comments: false # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent talks
    text_link_url: /research/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the talk _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside talk/. You may still override any of these by changing them in a page's front matter.**
