---
layout: post
title: Build github pages blog with jekyll on windows
published: True
categories: [tech,log]
tags: [github,jekyll,bootstrap,ruby,windows]
---
Again, I'm back to windows :). This is a summary about how to build this [blog](upson.github.io) on [github pages](https://help.github.com/categories/20/articles) with [jekyll](https://help.github.com/articles/using-jekyll-with-pages) in windows. The major references are the [english guide](http://jekyll-windows.juthilo.com/) and the [chinese guide](http://www.cnblogs.com/purediy/archive/2013/03/07/2948892.html).

# Create Github User Pages
> For User Pages, use the master branch in your username.github.io repository. For Project Pages, use the gh-pages branch in your project's repository.

Also install [github windows](https://windows.github.com/help.html). It's the official tools from github on windows **WITHOUT SSH**. 

# Installing Jekyll on my windows computer
> We highly recommend installing Jekyll on your computer to preview your site and help diagnose troubled builds before publishing your site on GitHub Pages.

## Installing Ruby
Thanks [rubyinstaller](http://rubyinstaller.org/)! I use ruby 1.9.3 for the stability. Also need [devkit](http://rubyinstaller.org/downloads/).

## Installing Jekyll
I just follow [github's introduction](https://help.github.com/articles/using-jekyll-with-pages) to install Bundler and Jekyll. In this way, there will be a default site that should be replaced by one below.

# Init blog with Jekyll-Bootstrap
Just [clone Jekyll-bootstrap's git repo](http://jekyllbootstrap.com/usage/jekyll-quick-start.html) to init my blog.

# Learning time
> Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

> Read [jekyllrb documents](http://jekyllrb.com/docs/home/)

> Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

> Update Author Attributes In `_config.yml` remember to specify your own data:

# Test and publish

# TODO
* Home page!
* Learning from [other sites based on jekyll](https://github.com/jekyll/jekyll/wiki/sites)
* Markdown
* Tools: sublime? notepad++?
* Multi-language: [ref 1](http://jekyll-langs.liaohuqiu.net/cn/) [ref 2](http://jekyll-langs-sample.liaohuqiu.net/)
* Private: [ref](http://chenjun.com/blog/2014/07/use-bitbucket-and-ftploy-to-private-jekyll.html)
* Online editing and publishing: Travis-CI + PRose [chinese ](http://xuhehuan.com/1761.html) [english](http://rogerz.github.io/blog/2013/02/21/prose-io-github-travis-ci/)
