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



## Set up the sidebar

Open up `content/about/sidebar/index.md` to customize. This is another file where you'll see a long-ish section of YAML with a series of key-value pairs fenced in by three dashes (`---`). There is no content on this page below the YAML.

### Add your info and avatar

Add your name as the `author` and a `role`. To add an avatar:

1. Save an image with the word `"avatar"` in the filename to the `content/about/sidebar/` folder (so it should be alongside the `index.md` file named, for example, `alison-avatar.jpg` or `avatar-haifa.png`), and
1. Then, select a shape for the image to display in the sidebar (one of: circle, square, rounded) in the YAML of `content/about/sidebar/index.md` (as shown below).

```yaml
---
## Configure sidebar content in narrow column
author: "Hugo Apéro"
role: "A Hugo theme"
avatar_shape: rounded # circle, square, rounded, leave blank to exclude
---
```

If you don't want to feature an avatar image, leave this key blank in your YAML.

### Add social links & audio

You may decide to show your social links here and an audio link. To show an audio link, you need to do four things:

1. Record an `.m4a` audio file locally,
1. Name the file with the word `"audio"` in the filename (so `alison-audio.m4a` or `audio-haifa.m4a`, for example), 
1. Save this file in your `content/about/sidebar/` folder, and
1. Add an audio link label in the YAML of `content/about/sidebar/index.md` (as shown below).

```yaml
---
show_social_links: true # specify social accounts in site config
audio_link_label: "How to say my name" # leave blank to exclude
---
```

If you don't want to include an audio link, leave this key blank in your YAML.

### Add additional links

Finally, you may add a list of links. 

```yaml
---
link_list_label: "Interests" # bookmarks, elsewhere, etc.
link_list:
- name: Paris
  url: https://en.wikipedia.org/wiki/Paris
- name: Pastries
  url: https://en.wikipedia.org/wiki/Pastry
- name: People
  url: https://en.wikipedia.org/wiki/People
---
```

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