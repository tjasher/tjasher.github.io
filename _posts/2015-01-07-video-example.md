---
title:  "Embedding a YouTube video"
content_type: Video
description: "If you have video on youtube, you can embed it by finding its youtube ID and using the correct Liquid shortcode"

lede_image:
  banner: true
  caption: "Ominous clouds on Madison River, Montana. This photo was taken shortly before we made it to land and the hail started coming down."
  url: /images/posts/montana-hailstorm.jpg

thumbnail_url: "/images/thumbs/montana-hailstorm.jpg"
homepage_position: 50
homepage_size: 2
homepage_theme: invert
---

Adding a (Youtube) video is as easy as finding the ID, and making a call like this:

~~~
{{"{%"}} include widgets/youtube_embed.html video_id="Ll5hBN6Dh5M" %}
~~~

The result will look like this:

{% include widgets/youtube_embed.html video_id="Ll5hBN6Dh5M" %}


### More text

Remember that this is just a post, so you can add whatever text/photos/etc you want to this item. You can even embed another video. In the call below, I specify the width and height, which are both optional:

{% include widgets/youtube_embed.html video_id="dfCd2eQfueY" width="400" height="300" %}
