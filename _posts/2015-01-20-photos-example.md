---
title:  "How to include photos"
description: "How to add photos and images to any given file"
thumbnail_url: "/images/thumbs/lou-tellegan.jpg"
---


As with everything else on this site, you can always hand-code your own HTML, including `<img>` tags. But I have creatd a helper that you can use: the `{{"{%"}} include widgets/post_image.html %}` statement:

~~~
{{"{%"}} include widgets/post_image.html src="/images/posts/Galli-Curci.jpg" %}
~~~

By default, this will create a full-width image across the page:

{% include widgets/post_image.html src="/images/posts/Galli-Curci.jpg" %}


### Including a caption


To include a caption, use the `caption` attribute:

~~~
{{"{%"}} include widgets/post_image.html src="/images/posts/Galli-Curci.jpg" caption="This photo comes from the Library of Congress" %}
~~~


{% include widgets/post_image.html src="/images/posts/Galli-Curci.jpg" caption="This photo comes from the Library of Congress" %}



### Including sourcing information

If you for some reason are referring to an external photo, or one that requires sourcing, you can use the `source_credit` and `source_url` optional attributes:

~~~
{{ "{%" }} include widgets/post_image.html src="http://upload.wikimedia.org/wikipedia/commons/f/fb/Taser-x26.jpg" caption="A photo of the X26 taser model from Wikipedia." source_url="http://en.wikipedia.org/wiki/Taser#mediaviewer/File:Taser-x26.jpg" source_credit="Photo by jasonesbain - Taser. Licensed under CC BY 2.0 via Wikimedia Commons" %}
~~~

{% include widgets/post_image.html src="http://upload.wikimedia.org/wikipedia/commons/f/fb/Taser-x26.jpg" caption="A photo of the X26 taser model from Wikipedia." source_url="http://en.wikipedia.org/wiki/Taser#mediaviewer/File:Taser-x26.jpg" source_credit="Photo by jasonesbain - Taser. Licensed under CC BY 2.0 via Wikimedia Commons" %}





There is a way to make a gallery (I'll save that for another example), but it's possible to create a "gallery" of photos by making a series of those calls. [It works for BuzzFeed](http://www.buzzfeed.com/erinchack/photos-guaranteed-to-make-you-snicker#.xx9L7kLOa).


The `widgets/post_image.html` snippet takes in a few more parameters, including `pull` (to pull the image left or right) and `width`, which by default is `full`, but can be `third` or `half`.

To display an image at __1/3__-page width on the __right__ side:

~~~
{{"{%"}} include widgets/post_image.html src="/images/posts/lou-tellegan.jpg" caption="Lou Tellegen & Farrar (LOC)" pull="right" width="third" %}
~~~


{% include widgets/post_image.html src="/images/posts/lou-tellegan.jpg" caption="Lou Tellegen & Farrar (LOC)" pull="right" width="third" %}


Notice how the rest of this text will float on the other side.

_Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum repellendus natus consequatur, esse est blanditiis. Nisi cum eius et nobis quod optio. Officia sapiente asperiores vero velit molestiae beatae quaerat._

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est ut molestias necessitatibus quidem ab harum dolorem quasi dolore praesentium modi inventore voluptate culpa, veniam enim! Rem, in reprehenderit asperiores amet.

#### blalblah blah

_Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam distinctio odio excepturi quasi ipsum repellendus at numquam vitae, hic, exercitationem officiis, ipsam placeat recusandae mollitia impedit dolores obcaecati laboriosam non!_

### Try not to pull too many images

Pulling an image to the side is useful for small photos. I wouldn't do this frequently though, as it's best to maintain things in a single-column format as much as possible.
