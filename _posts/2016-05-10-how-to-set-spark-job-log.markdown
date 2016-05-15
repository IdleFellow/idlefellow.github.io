---
layout: post
title:  "How to set Spark job's log"
date:   2016-05-15 20:10:10 +0800
categories: Spark
---
1. If you want spark to log your job, you must set two values:

{% highlight ruby %}
spark.eventLog.enabled=true
spark.eventLog.dir=/tmp/spark-events
{% endhighlight %}
this will storage the job info to spark.eventLog.dir as json data.

2. If you want to see the job's info, you can:

{% highlight ruby %}
start-history-server.sh
http://localhost:18080/
{% endhighlight %}

3. Principle:

{% highlight ruby %}
Spark have a template to every job, but the data is null by default,
if you set spark.eventLog.enabled=true, Spark will filling the data and store it
in spark.eventLog.dir, and historyserver will remember the dir.
{% endhighlight %}

Visit my Github [Github home][github-home].

[github-home]: https://github.com/IdleFellow

