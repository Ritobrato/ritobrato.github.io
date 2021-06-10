---
layout: post
title: Hello World
date: 2021-06-09 22:30:10 +0530
permalink: /:categories/:year/:month/:day/:title
published: false
---

`Hello world` this is my first custom blog post on Jekyll. The satisfaction is immense!

Lately at work we've been using a combination of vim/tmux to make pair programming a lot easier. This is especially helpful when working remotely or under a crappy internet connection, as you won't need a lot of bandwidth.

#### Anonymous callback function example

While both vim and tmux allow you to highly customize your shortcuts, changing them too much will make your pair's life harder, since they'll have to memorize your specific shortcuts, so keeping the defaults will make everybody's lives easier.

{% highlight ruby %}
app.get("/", function (req, res) {
  res.sendFile(__dirname + "/index.html");
});
{% endhighlight %}

vim is a big beast on its own, but in a good way. You can find a huge number of plugins out there that will make you go crazy, so to keep sanity levels to a maximum, I use a single one: Janus.

Janus bundles together a lot of really useful plugins to make a devs' life simpler (fuzzy search, ack, git commands, additional syntaxes, and more). As such, most (if not all) shortcuts I list here will really only work with it:
