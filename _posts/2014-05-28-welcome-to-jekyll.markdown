---
layout: post
title:  "Blogging with Jekyll"
date:   2014-04-18 08:29:03
categories: blogging
description: "Hello Jekyll, the beginning of mirango.io"
---

I've decided it's time I should start another blog.  I've had several blogs in the past, mostly self hosted wordpress blogs.  Last year I discovered something that caught my eye.  Static site generators.  Since my blog will be serving identical pages to everybody, there's really no need for a complicated (and often buggy) backend.  Rather than storing posts and pages on a database, a static site generator generates static HTML from a mix of templates, markdown, and css (less/scss too).  For mirango.io I decided to use Jekyll, one of the most popular static site generators.

The source for Mirango.io is available on [GitHub][mirango] along with the Nginx [configuration file][nginx].

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby linenos=table %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[mirango]: https://www.github.com/sdwalsh/mirango
[nginx]: https://www.github.com/sdwalsh/mirango_nginx
[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
