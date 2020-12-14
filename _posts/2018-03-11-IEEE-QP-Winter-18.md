---
layout: post
title: "Get Posturized"
date: 2018-03-11
excerpt: "A prototype posture correction device using gyroscope technology."
project: true
comments: false
---
<b>Get Posturized</b> is a prototype device that helps correct unhealthy posture and alleviates their negative effects. It uses a gyroscope to detect the optimal position relative to the body posture. The overall device was created using an Arduino Uno board and an MPU 6050 device.

{% capture images %}
    https://user-images.githubusercontent.com/36279762/55611836-91a97680-573b-11e9-9425-d007576538d1.jpg
{% endcapture %}
{% include gallery images=images caption="Here, the device is being worn by a user along with a shot of the app." cols=3 %}

## How to Use
 * Using a t-shirt with pockets, preferably, put the Arduino side of the device into the pocket.
 * Tape the other end of the device over the shoulder onto the back of your shoulder blades.
 * Open up the Android App and connect your phone to the Bluetooth module on the device.
 * Stand straight and start caliberating your ideal posture on the app.
 * Afterwards, the device will vibrate whenever you lean to far forwards or backwards from the ideal posture and the app will notify you of the incorrect posture.
 
This project was created for the IEEE Winter Quarterly Project 2018 which is a competition that IEEE UCSD holds every quarter of the school year. Since the theme of this competition was "Health", we opted for creating a device that would help assist users in correcting back posture as the amount of people suffering from back pain due to working white-collar jobs or using mobile phones is rapidly increasing. Some of the challenges we faced included lack of experience with Arduinos and the lack of documentation on the MPU 6050 device that we were using. Another challenge included time constraints, having to balance working on this competition with working/studying for school.

## Tools Used  
 * Arduino Uno
 * MPU 6050
 * Mini vibration motor disc
 * HM-10 Bluetooth module
 * C++
 * Soldering
 * Circuit building
 * Android app creating software
