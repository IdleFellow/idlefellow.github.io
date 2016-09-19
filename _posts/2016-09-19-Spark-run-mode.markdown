---
layout: post
title: "Spark run mode"
date: 2016-05-15 08:00:00 +0800
categories: Ruby
---
One. Yarn基础

{% highlight ruby %}
资源管理层面：master为resourcemanager, slave为nodemanager
应用管理层面：每个Application第一个container为master,后续container为slave.master被成为Application Master.
{% endhighlight %}