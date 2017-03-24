---
layout: post
title:  "Making a flight checker program"
date:   2017-03-19 03:41:38 -0500
categories: code
---
A couple of years ago, I read about a student's Southwest flight checker. I decided
to try and make a less intense version of the application using some Python models, and
thus set out to write a comprehensive script that would:

{% highlight ruby %}
import webbrowser
from datetime import datetime
from threading import Timer
{% endhighlight %}


{% highlight python %}
current_time = datetime.today()
check_in_time = current_time.replace(day= current_time.day, hour = current_time.hour,
minute = 18, second = 0, microsecond = 0)
change_in_time = check_in_time - current_time
{% endhighlight %}

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
