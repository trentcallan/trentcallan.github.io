[Home](https://trentcallan.github.io/) | [Resume](resume.md)

# Music Reactive Lights

I was inspired and used a lot from this video on youtube by Nerdforge, feel free to check it out - <https://www.youtube.com/watch?v=yninmUrl4C0&t=1s>

This project was a great way to get introduced to using the esp8266 arduino wifi microcontrollers.  I followed the same idea in the youtube video where I planned on creating a lamp controller box that contains an esp8266 and a microphone and a lamp with an esp8266 controlling the LEDs.   The esp8266’s would connect to wifi and communicate with each other by sending udp packets.  It was pretty easy to set that up and get them working to be able to communicate.  The hardest part of this project was soldering.

I had to solder connections between about 40+ wires.  It was tough because some of the pins for different pieces were really close together and I didn’t realize I had other sizes of soldering iron tips.  So I was using a relatively thicker tip for soldering all these connections together.  It was doable but it definitely took my awhile, especially since I was learning for the first time.  I would suggest trying smaller tip sizes when there are a lot of wires in the way.  I would also emphasize that tinning the tip before using it each time is very important.

Once connections were soldered and it worked I thought it would be cool to add a website to the lamp controller that has options for settings of the lamp (instead of using physical items such as potentiometers and buttons).  So I added that in order to be able to choose the mode of the lamp.  You can choose between music reactive, rainbow and choosing your own color based on rgb values.

My final advice for anyone creating their own project like this or any project with soldering really would be to create enclosures for the electronics first so you know how long the wires you solder need to be.  I made my long enough that I could get it to work but I think it would’ve been a lot easier to make it work if I had made the enclosure first!

![photo](https://trentcallan.github.io/content/led_controller_1.JPG "led lamp")

![photo](https://trentcallan.github.io/content/led_controller_2.JPG "led lamp")

![photo](https://trentcallan.github.io/content/led_lamp_1.JPG "led lamp")

![photo](https://trentcallan.github.io/content/led_lamp_2.JPG "led lamp")

![photo](https://trentcallan.github.io/content/webserver.png "selection menu")

<video width="320" height="240" controls>
  <source src="https://trentcallan.github.io/content/music_reactive_test_480p.mov" type="video/mp4">
</video>

<video width="320" height="240" controls>
  <source src="https://trentcallan.github.io/content/test_webserver_720p.mov" type="video/mp4">
</video>
