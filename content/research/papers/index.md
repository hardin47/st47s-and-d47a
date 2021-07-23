---
title: "Papers + Projects"
subtitle: "."
excerpt: "."
date: 2021
author: "Jo Hardin"
draft: false
# layout options: single, single-sidebar
layout: single
---

## Set up the main section

Open up `content/about/main/index.md` to customize. You can add a title, intro, and outro to frame out this section. The meat of this section is the featured content, which pulls from the rest of your website to give visitors a glimpse of what else there is to read.

Here, you can choose the number of featured items *per section* to show. 

```yaml
---
number_featured: 1 # pulling from mainSections in config.toml
use_featured: false
---
```

If you want to limit the sections here, open up your site's `config.toml` file and find the `mainSections` key:

```toml
[params]
  <!--snip snip-->
  mainSections = ["blog", "project", "talk"]
```

By default, the theme will select the most recent content pages to show. If you'd prefer to control this and flag individual pages to feature instead, set `use_featured: true` and add `featured: true` to each page (make sure the page is in one of the `mainSections` you selected too!).

Finally, you can highlight some featured categories of content; set to `0` to exclude this section. The theme chooses the categories based on number of pages in that category, so if you set to `1` only your most used category will show up.

```yaml
---
number_categories: 3 # set to zero to exclude
---
```

These categories show up as clickable buttons above the outro.

## Sharing image for the about page

The about page will default to your site's default sharing image, set up in your `config.toml` file.

```toml
[params]
  <!--snip snip-->
  # Default image for social sharing and search engines. 
  # Place image file in `static` folder and specify image name here.
  sharing_image = "/img/papillons.jpg"
```