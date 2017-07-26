---
layout: post
title:  "Making a flight checker program"
date:   2017-03-19 03:41:38 -0500
categories: code
---
A couple of years ago, I read about a web application developed by a CS student that automatically checked people into their flights. He was (too) successful and unfortunately later asked to cease and desist his application because it actually worked. For educational purposes and to try and dabble with some Python scripting,  I decided to try and write a more basic of the application that, ideally, would:  

- Ask the user what Airline they are using, their flight number, and what time check in opens. For a simple start, I'll use Southwest Airlines because their check-in page seems nice to work with. I'll also later want to have the program calculate check-in time itself, because this time is usually 24 hours before the flight departs. This part of the program will, for now, just be in the command line. (Easy) 
- Open a user's web browser at the time of check in. (Easy)
- Enter in the flight details necessary on the online check-in form. (Hard)
- Progress through the online check in form to complete check-in. Buttons would need to be pressed. (Hard) 

First, we need to import the Python webbrowser controller to be able to open webpages, as well as the datetime and timer modules for being able to open at check in time: 

{% highlight python %}
import webbrowser
from datetime import datetime
from threading import Timer
{% endhighlight %}

It was a bit tricky to learn how to set the timing the program would use, but a current_time.replace() seemed to work: 

{% highlight python %}
current_time = datetime.today()
check_in_time = current_time.replace(day= current_time.day, hour = current_time.hour,  
minute = 18, second = 0, microsecond = 0)
change_in_time = check_in_time - current_time
{% endhighlight %}

And here's the open function I wrote, with error handling for whether or not an instance of a web browser is already open: 

{% highlight python %}

def open(): # need to figure out way to have input here
	url = 'https://www.southwest.com/air/flight-status/index.html'
	try: webbrowser.open_new_tab(url)  
	# Open URL in a new tab, if a browser window is already open.
	except: webbrowser.open_new(url)
	print ("Check in page opened!")
  return
{% endhighlight %}




