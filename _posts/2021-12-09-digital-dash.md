---
layout: post
author: mdr
---

I really liked the way the original dash bezel looked and didn't want to change it. What I ended up doing was gutting the original gauges and replacing them with LCD screens. The outer sections I added a couple AC vents to help in the hot summers.

There are 3 separate LCD screens, each controlled via serial connection to an arduino. I originally had an arduino UNO (in the pics below) but have switched to a pro micro and a can bus shield.

The LCD screens are from 4D systems.

Nearly all the sensor information comes via can bus from the Megasquirt. The fuel gauge goes directly into the arduino, as does the shifter position. Below are the links to the screens, arduino, and the current code (that's always a work in progress).

Some of the biggest challenges have been dialing in how fast I can send data to the screens. The screens will puke if you send data too fast, but for the RPM I wanted to be able to have it look nice. There's a sample video below too. I can change any of the graphics around which is nice. I'm not totally convinced the screens will survive the hot summers... but we'll see!

<ul>
<li>Screens: https://4dsystems.com.au/</li>
<li>Arduino: https://www.sparkfun.com/products/12640</li>
<li>Can Bus: https://www.geraldjustprojects.com/product/mcp25625-mini-canbus-shield/</li>
<li>Arduino Code: https://github.com/rushtonmd/carduino-5000</li>
</ul>

<iframe width="560" height="350" src="https://www.youtube.com/embed/BdDKBbBK5o8" title="Arduino Rambler Dash Test" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

![2020-06-07_14 10 38](https://user-images.githubusercontent.com/1479022/178113368-22d1a061-38f9-474b-aa9f-62d023fd06cb.jpg)
![2020-07-04_16 42 59-1](https://user-images.githubusercontent.com/1479022/178113373-20ec6abd-7c38-4a96-a5e6-03f4334b068f.jpg)
![2020-07-05_08 43 36](https://user-images.githubusercontent.com/1479022/178113374-39a5973c-97df-4571-922c-c0f7c909ed47.jpg)
![2020-07-20_12 48 29-1](https://user-images.githubusercontent.com/1479022/178113376-c4f5b3e5-d63f-4760-ab14-effbd52c26d1.jpg)
![2020-07-30_13 30 53](https://user-images.githubusercontent.com/1479022/178113377-eb81d605-2a94-49d5-a2bf-92e19446ac0b.jpg)
![2020-08-16_12 48 38](https://user-images.githubusercontent.com/1479022/178113379-feac97ab-5bfe-4603-83f0-878b4afa57f5.jpg)
![2020-08-16_13 18 16-1](https://user-images.githubusercontent.com/1479022/178113381-d67a882a-8891-42df-8f51-684e048ab339.jpg)
![2020-08-30_17 30 20](https://user-images.githubusercontent.com/1479022/178113382-a2471057-9249-41a1-91e2-17c16e2d76d5.jpg)
![2020-09-06_10 17 02-1](https://user-images.githubusercontent.com/1479022/178113383-18ba2748-bda9-4a93-a2f7-012867cf9b9b.jpg)
![Screen_Shot_2021-12-09_at_9_2021-12-09_20-32-37 41_2021-12-09_20-32-37 01_AM_2021-12-09_20-32-37](https://user-images.githubusercontent.com/1479022/178113385-dd372e90-9663-4410-97f8-cd25d3745f3d.jpg)
