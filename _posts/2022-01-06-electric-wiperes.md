---
layout: post
author: mdr
title: Electric Wiper Motor Conversion
---

I had previously gotten the vacuum wipers rebuilt and they worked... you know... as well as vacuum wipers do 😊 Since it's a turbo car I don't have a ton of vacuum to start with, so I was using an external vacuum pump for the wipers and brakes. The major issue is that there is no reservoir so the pump takes the entire burden of building vacuum, and the vacuum wipers take a TON of volume, and even when not operating the wipers aren't 100% sealed. This is pretty apparent and negatively affects braking power to the point of being quite noticeable. Once I removed the wipers the brakes work soooo much better.

I read a few threads on electric wipers and decided to give it a shot. I wanted to keep things as reversible as possible and not destroy things.

Here is the wiper motor I used:
Autotex Wiper Motor: [AutoTEX Motor](https://getautotex.com/products/4r2-12-r110d-two-and-a-half-inch-2-5-shaft-12v)

I got it because it does oscillate (instead of spin) and it says it's adjustable... which is sorta is.

I started by marking off where the vacuum wiper motor starts, ends, and is parked. This would be the pattern for setting up the new one:

![2021-12-29_16 35 53](https://user-images.githubusercontent.com/1479022/178315218-238fac5a-6cdc-43a3-bab6-f74d75fa21d5.jpeg)

Here I was test fitting the new wiper motor:

![2021-12-30_14_2022-01-07_19-44-17 53_2022-01-07_19-44-17 02-1_2022-01-07_19-44-17](https://user-images.githubusercontent.com/1479022/178315239-67d23dc8-6ecc-4c88-9651-2a6832644133.jpeg)

![2022-01-02_11 25 23](https://user-images.githubusercontent.com/1479022/178315246-665ec648-809d-4958-b634-5b1f16d32a27.jpeg)

I ended up shortening the shaft and threading the end of it which kinda worked ok. I had to play with a bunch of different shims and bushings to get it tight. 

![2021-12-30_14 50 42](https://user-images.githubusercontent.com/1479022/178315243-63ff5350-cde5-4443-a5cd-765580faac41.jpeg)

So here's the inside of the wiper motor. The idea is that you change the position of the arm on the gear and it'll change the park position as well as the stroke (sweep angle). The problem is that the start/stop position also changes, so you can't just change the sweep angle without affecting everything else. The other problem is that the screw holes in the gear didn't line up correctly, so I ended up drilling my own hole in the position I wanted which is kinda crappy but it works fine. 

![2021-12-29_21 20 11](https://user-images.githubusercontent.com/1479022/178315230-d56d6940-ce1d-4e5a-a497-c09571d17615.jpeg)

I made a little arm and after about 50 tries I got the position correct. I ended up tack welding the nut on the end to make sure it didn't move around. 

![2022-01-02_11_2022-01-07_19-44-56 25_2022-01-07_19-44-56 15_2022-01-07_19-44-56](https://user-images.githubusercontent.com/1479022/178315244-0ed38fe5-2cdd-4e1c-8f52-b58ae4f87ae6.jpeg)

The other things I wanted to do was keep the dash switch - which is a cable that operates the vacuum wipers. I ended up getting a 15amp lever switch so that when it's OFF, the wipers park, when it's ON the wiper.. wipe. I had an old arduino case that I used for the cable actuated switch and it hides under the dash. I didn't want to cut up the cable switch in case I want to go back to vacuum. 

![2022-01-06_08 27 45](https://user-images.githubusercontent.com/1479022/178315253-801847c4-b527-40e9-aff1-02e3a52d6c27.jpeg)

![2022-01-03_12 47 36](https://user-images.githubusercontent.com/1479022/178315248-e0d36b51-d070-449f-8cc1-8137d965da02.jpeg)

![2022-01-04_20 07 49-1](https://user-images.githubusercontent.com/1479022/178315250-2465583f-5478-400e-aef5-43d28439cc1b.jpeg)

And here it is almost wired up and installed. I made a little bracket to hold the motor in place.  

![2022-01-06_08 35 56](https://user-images.githubusercontent.com/1479022/178315254-09b5344a-17bd-45b0-8ac9-7925d5257a55.jpeg)

Here's a little video of a San Diego cold start and operation. The wiper motor has PARK, FAST, and SLOW settings. It's currently on FAST but I may switch it over... it's quite a lot considering I'm in San Diego and it's mostly used to wipe off bugs and fog drip. The other grump of mine is that PARK isn't any farther along the sweep than the normal operation, so during normal operation it has to go all the way to the park position which kinda bumps a little bit on the window. Not a huge deal, but sort of annoying. I'm not entirely convinced I'd recommend this wiper motor, but not sure what alternatives there would be either.

<iframe width="560" height="350" src="https://www.youtube.com/embed/2oCY2xdx2Rs" title="Rambler Wipers Test" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
