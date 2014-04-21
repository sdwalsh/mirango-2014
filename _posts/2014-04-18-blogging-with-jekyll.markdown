---
layout: post
title:  "Blogging with Jekyll"
date:   2014-04-18 08:29:03
categories: blogging
description: "Hello Jekyll, the beginning of mirango.io"
md: "April 18"
---

I've decided it's time I should start another blog.  I've had several blogs in the past, mostly self hosted wordpress blogs.  Last year I discovered something that caught my eye.  Static site generators.  

Since my blog will be serving identical pages to everybody, there's really no need for a complicated (and often buggy) backend.  Rather than storing posts and pages on a database, a static site generator generates static HTML from a mix of templates, markdown, and css.  For mirango.io I decided to use Jekyll, one of the most popular static site generators.

Take the time and look at the source for Mirango.io.  It's available on [GitHub][mirango] along with the Nginx [configuration file][nginx].

Short Guide to Installing Jekyll on Your Local Computer
--------------------------------

# Install rvm and ruby (stable)
{% highlight bash %}
$ \curl -sSL https://get.rvm.io | bash -s stable --ruby

# Install the jekyll gem
$ gem install jekyll

# Create a new jekyll site (jekyll will create the basic file structure and configuration files)
$ jekyll new siteName

# Move into the newly created file
$ cd siteName

# Builds the site (takes all the files and outputs the static site in the _site folder)
$ jekyll build
# Creates a development server at localhost:4000
$ jekyll serve
{% endhighlight %}

If you're interested in hosting a jekyll site, GitHub will host the site for free.  Check out [https://pages.github.com][pages].

[mirango]: https://www.github.com/sdwalsh/mirango
[nginx]: https://www.github.com/sdwalsh/mirango_nginx
[pages]: https://pages.github.com
