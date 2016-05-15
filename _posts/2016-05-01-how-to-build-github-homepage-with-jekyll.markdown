---
layout: post
title:  "How to build Github homepage with jekyll"
date:   2016-05-01 20:10:10 +0800
categories: Spark
---
1. Install `Ruby`.

{% highlight ruby %}
Ubuntu: sudo apt-get install ruby
Mac: http://www.cnblogs.com/daguo/p/4097263.html
{% endhighlight %}

2. Change `gem sources`.

{% highlight ruby %}
gem sources --remove https://rubygems.org/
gem sources -a https://ruby.taobao.org/
gem sources -l
{% endhighlight %}

3. Install `jekyll`.

{% highlight ruby %}
gem install jekyll
{% endhighlight %}

4. Make a new space for your articles and `initialize` it.

{% highlight ruby %}
mkdir idlefellow.github.io
cd idlefellow.github.io
jekyll new .
{% endhighlight %}

5. Use `git` for management.

{% highlight ruby %}
git init
git add remote origin https://github.com/IdleFellow/idlefellow.github.io.git
git add .
git commit -m 'use jekyll'
git push origin master
{% endhighlight %}


