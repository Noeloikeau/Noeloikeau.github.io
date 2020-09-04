---
layout: post
title:  "Welcome to my blog!"
date:   2020-09-04 10:09:14 -1000
categories: intro
---
This is my first post. I can write code snippets using the tilde key ~ without shift, `_likethis`.
The file used to make this goes in my `_posts` directory. I published it by running `bundle exec jekyll serve` after re-writing the post file to `2020-09-04-welcome-to-my-blog.markup`. I changed the file by editing the layout, title, categories, and text, as well as the extension. I ran it locally by navigating to `http://localhost:4000`.

I can write code snippets like:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
