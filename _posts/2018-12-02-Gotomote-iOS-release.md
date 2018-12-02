---
layout: post
title: Gotomote iOS application release
categories:
- blog
---

Gotomote is a very special project to <a href="https://github.com/29satnam/">me</a>. I&#8217;m proud to say that it&#8217;s a part of the project OnStep. OnStep is a DIY computerized Goto controller for Telescope mounts. <a href="https://groups.io/g/onstep/wiki/home">OnStep</a> is led by <a href="https://github.com/hjd1964">Howard Dutton</a> and <a href="https://github.com/hjd1964">Khalid Baheyeldin</a>. Hundreds of hours of work have gone into OnStep, and we&#8217;re dedicated to making it better every day. Thank you for making it part of your world.

---

# It's all in the game.

## How does it work?

Gotomote app can connect to OnStep over IP. It communicates to a 'Serial Port' terminal server listening to a TCP socket. Gotomote opens a network connection to a socket and any data app send on the output stream get sent out of the serial port and any data sent to the serial port gets delivered over the input stream associated with the connection.

---

## Features: What does it do?

- It's easy-to-use and built over powerful asynchronous socket.
- Queued non-blocking reads and writes, with optional timeouts.
- App has a database of Quasar, Messier and a vast database of Galaxy with a named bright star catalog.
- Initialization of date/time/location, and align with one, two, or three stars.  Align with one-star to quickly get going or two/three stars to correct for polar axis misalignment, cone error, etc.
- Parking functionality includes the ability to set the park position (anywhere you like), park, and to unpark.
- The guide are for pulse-guiding, centering objects, etc.
- PEC programming and much more.

---

## Credits

- Development credits for this app obviously goes to me.
- Design and user interface for the same by my friend <a href="https://www.instagram.com/Zac.wolff/">Zachary</a>.
- <a href="https://github.com/hjd1964">Howard Dutton</a> and <a href="https://github.com/hjd1964">Khalid Baheyeldin</a> for OnStep.
- Brightest stars database by <a href="http://www.atlasoftheuniverse.com/stars.html">atlasoftheuniverse.com</a></li>
- Messier, Quasar, Galaxy data by <a href="https://github.com/lorenzoriano/astro-organizer/tree/master/catalogues/SAC_DeepSky_ver81">astro-organizer</a></li>
