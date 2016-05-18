---
layout: post
title:  "HDFS, Yarn and Spark HTTP Service Port"
date:   2016-05-15 20:10:10 +0800
categories: Spark
---
One: HDFS

{% highlight ruby %}
Namenode HTTP Service Port: 50070
Namenode RPC Port: 8020
Datanode RPC Port: 50010
{% endhighlight %}

Two: Yarn

{% highlight ruby %}
ResourceManager HTTP Service Port: 8088
ResourceManager REST Service: 8088/ws/v1/cluster/info and 8088/ws/v1/cluster/metrics
{% endhighlight %}

Three: Spark

{% highlight ruby %}
Spark Cluster Service Port: 8080
Job History Service Port: 18080
{% endhighlight %}


