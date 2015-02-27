# README

This is a minimalist portfolio built on Jekyll and Twitter Bootstrap. By default, it is configured to be used on Github Pages.

It is responsive, relatively lightweight, and easy to maintain. There's very little template magic.


## Philosophy

This portfolio template is built around the expectation that you know exactly what you want to show. And that the best portfolios are well-edited to show the best things.

This means:

1. No databases. If you aren't trying to show more than 1,000 items, you don't need a database
2. Everything is text (except for the images and assets you might link to). You can use HTML, but Markdown is easier.
3. Hand-code the details: there's no template magic to auto-place an image for you. If you want an image somewhere on the page, you put the appropriate code there.
4. Stick to single-column when possible. 






## Create a new organization

## Create a new repo
dansnguyen.github.io


## From the commandline

git remote add origin git@github.com:dansnguyen/dansnguyen.github.io.git
git push -u origin master


## The hacker's path
## (optional) install jekyll

http://jekyllrb.com/docs/quickstart/



## How to make a post

### Create a new file in the _posts/ directory

In the `_posts/` directory, make a new post, and __put a date at the beginning of the filename__ (the format is important), followed by just some slug of lowercase letters and hyphens. You can use either the file extension of `md` for markdown (recommended) or `.html` if you plan on writing custom HTML for some reason:

        _posts/_
            2015-01-10-this-is-my-post.md
            2013-12-02-this-is-some-other-post.md

The filename doesn't really affect the actual URL of the post (that's based on the title). Just name the file something that you can easily recognize as you go through your own files. Also, the _dateslug_ does not really matter, though you can choose to have it refer to the original publish date of something if you want.

To reiterate: the filename is just to make it easy _for you_ to keep track of what you have.


### Fill out the attributes in the top matter


