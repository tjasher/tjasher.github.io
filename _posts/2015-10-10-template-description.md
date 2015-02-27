---
title:  "The Template Description"
description: "An explanation and examples of the front-matter templates for posts"

published_info:
  date: 1980-01-27
  site: The Template Example
  url: http://www.example.com
  logo_url: /images/logos/logoz-sample.png


lede_image:
  banner: true
  url: /images/posts/template-wide-guy-2.jpg
  caption:  "If you want a banner image fill out this lede_image:url field. This is used to represent a post on the homepage (i.e. the art associated with any given item)"


thumbnail_url: "/images/thumbs/template-guy.jpg"
homepage_title: "Another title"
homepage_position: 5
homepage_size: 1
---


## Required attributes

~~~yaml
title:  "The Template Description"
~~~


## Nice to have

~~~yaml
description: "A short description of what the post contains"

thumbnail_url: "/images/thumbs/template-guy.jpg"

lede_image:
  url: /images/posts/template-wide-guy-2.jpg
  banner: true
  caption:  "If you want a banner image fill out this lede_image:url field. This is used to represent a post on the homepage (i.e. the art associated with any given item)"
~~~

## Publication info


If this has been published elsewhere and you want to refer/link to it:

~~~yaml
published_info:
  date: 2002-01-27
  site: Example-Dot-Com
  url: http://www.example.com
  logo_url: /images/logos/logoz-sample.png
~~~


## Things related to the homepage

You have several options for controlling how your post looks like on the homepage. All of these are optional:

~~~yaml
homepage_title: "Alternate title just for the homepage"
homepage_description: "Alternate description just for the homepage"
homepage_position: 5
homepage_size: 1
homepage_theme: invert
redirect_to_url: http://someothersite.com
~~~








