---
layout: post
title: "how to install ruby in ubuntu 14.04"
date: 2016-05-15 08:00:00 +0800
categories: Ruby
---
One. Install `ruby-install`

{% highlight ruby %}
wget -O ruby-install-0.6.0.tar.gz https://github.com/postmodern/ruby-install/archive/v0.6.0.tar.gz
tar -xzvf ruby-install-0.6.0.tar.gz
cd ruby-install-0.6.0/
sudo make install
{% endhighlight %}

Two. Install `ruby`

{% highlight ruby %}
ruby-install
ruby-install 2.3.1
{% endhighlight %}
