---
layout: post
title: Hello world!
published: false
---

[GitHub][] finally provides nerds best publishing platform ever:
[GitHub Pages][]. I, as a proud nerd, could not help, but join the
fun.

There was an unresolved tension about where to put my technical posts,
which would be appreciated by very narrow set of my friends. I have
intuitive understanding of effort to outcome ratio which was not very
good for self-written blog, on the other hand there was no blog
platform I liked which would not be obfuscated with technical detailes
unrelated to the very process of writing text. (Blog hostings like
Livejournal or Blogger lack syntax highlighting and markdown support;
custom blog engine requires hosting and maintanance, this was not that
kind of important thing to occupy my attention for maintanance
efforts).

So, when it turned out that [GitHub Pages][] combine pros of both blog
hostings and custom blog engine with the cost of some manual
fine-tuning, it was a bliss.

The minimal set of features I want my blog to have is:

* Markdown support,
* code systax highlighting,
* RSS/Atom feed (routed through FeedBurner),
* comments
* Google Analytics support.

So I had to do the following things:

* write [custom index.html template](https://github.com/elephantum/elephantum.github.com/blob/master/index.html),
* write [posts.xml Atom format feed template](https://github.com/elephantum/elephantum.github.com/blob/master/posts.xml),
* setup FeedBurner account, route posts.xml through it,
* **TODO** setup Disqus account, to turn on comments on static
  html-pages,
* setup Google Analytics account, embed counter to page template.

You can find all the things I did as the source of this post in
[my GitHub repository](http://github.com/elephantum/elephantum.github.com/).

[GitHub]: http://github.com/
[GitHub Pages]: http://pages.github.com/
