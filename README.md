Ultradian Timer
===============

This timer is based on research from [Peretz Lavie] [2] on "ultradian rhythms" which matches our human's natural attention rythm and break requirements.

The concept is based on having a longer work session (typically around 90 minutes) followed by shorter break sessions (around 15 minutes).

Basic Description
-----------------

The Ultradian Timer is a simple HTML5/Javascript script that produces an adjustable timer intended to follow the Ultradian Rythms in order to improve productivity for any given activity on any given workday.

When the countdowns reached 0, an alarm will ring

Version
-------
1.0.1

Usage
-----

Simply clone/download the repo and run index.php on your favorite browser (tested on Google Chrome only, should work fine on Firefox and the latest version of IE).

* Use the sliders to change the work session and break timers
* Press "Start Session" to start your day session
* Press "Take Break" to take a break (timer will change to selected break value)
* Press "Resume work" to resume work and restart a work session
* Press "Stop session" to stop and reset the timer  

####Note: the break/resume needs to be activated manually by the user in order to switch the timers - the timer will count positively after it has reached 0 and until the break/resume button is pressed. 

Future Versions and TODO
--------
* Add a nap button and slider (a nap timer) following research and articles on the [productivity benefits of napping] [4] 
* Add Checkbox for automatic start of break when countdown reaches 0

Attributions
------------

* Sounds obtained from [Oringz.com] [3]
* [Jquery] [jquery]
* [Jquery-UI] [jquery-ui]
* [TimeCircles] [timecircles]

License
----

MIT

[2]:http://www.dtic.mil/cgi-bin/GetTRDoc?AD=ADA296199
[3]:http://oringz.com/
[4]:http://blog.bufferapp.com/how-naps-affect-your-brain-and-why-you-should-have-one-every-day
[jquery]:http://jquery.com/
[jquery-ui]:http://jqueryui.com/
[timecircles]:https://github.com/wimbarelds/TimeCircles

