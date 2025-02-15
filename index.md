---
layout: page
title: Can i run?
permalink: /
---

Hello. My name is Lyosha. I live in Tbilisi and love to run. But I am concerned about the poor air quality in this city. Therefore, I decided to write a bot that will check the level of pollution every hour and report on dangers. After all, when the level is dangerous - it is better not to run.

## A bit of theory 

There is a general air condition index (AQI), which is calculated using a special formula. I don’t count anything, but I take data from free sources, namely from the service [https://www.iqair.com/georgia/t-bilisi/tbilisi](https://www.iqair.com/georgia/t-bilisi/tbilisi)

Please note that there are very few of these sensors in Tbilisi, so the accuracy of the determination suffers and much depends on the specific area.  

From the general index, you can characterize the air, namely:

* 0 to 50 is good air
* From 51 to 100 is valid,
* 101 to 150 bad
* From 151 to 200 is very bad.


## I propose the following version of the channel 

Every morning a message will be sent here with the current value of the air indicators.
If during the day the indicators fall sharply, or rise, my script will signal this.

That is, if the air was clean in the morning (for example, 13), and by the evening it crossed the boundaries of good air (became above 50), a notification will be sent to the channel. Then, let's say the growth continued to 101 - again we get a message. And in the evening I went down to 13 - again a message will come.


## Why do You need it? 

By controlling air pollution, you can perform certain actions. For example, if the air is very dirty, you need to reduce physical activity outside. If the air is clean, you can go for a walk or run.

## Where you can monitor the air

### Tbilisi (Georgia)
[https://t.me/canirun](https://t.me/canirun) (telegram)<br>

### Yerevan (Armenia)
[https://t.me/airinyerevan](https://t.me/airinyerevan) (telegram)

## How can I help?

We have a technical telegram chat <a href="https://t.me/tbilisi_air">@tbilisi_air</a> where information is collected about where and what you can order in order to build your own weather station in order to increase the number of in the sensors around the city and the picture was more objective.

## How to contact me

Telegram: <a href="https://t.me/gnupg">@gnupg</a><br>
Email: <a href="mailto:nullbsd@gmail.com">nullbsd@gmail.com</a>

## Donate

bitcoin: `bc1qs7v6vfp0xpe2slcpwlhftdeqj2w92r3pkykjn6`<br>
IBAN: `GE47TB7765045068100010` (Aliaksei Sakalou, swift: TBCBGE22, Georgia)<br>
<img src="/images/qrdonate.png" style="width: 30%; display: inline" /><br>
[https://www.donationalerts.com/r/belarusuli](https://www.donationalerts.com/r/belarusuli)
