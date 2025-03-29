---
layout: post
tags: bike
---


![UI Prototype](https://michaelmassie.com/assets/img/UIController2.png)

I am not sure why this isnt more standard in ebikes as good battery hygiene is the same as it would be for any EV. Never-the-less, I wanted to bring the same experience that I have with my connected car to the e-bike.

Features like:

1) Check on charge status from phone’s Lock Screen

2) Set the charge limit to 80% to better extend the life of the bike battery

3) Set charge times

4) Drop charge down to 40% over the winter when it’s less in use

5) Phone notification when charging is complete


![Charge Controller Prototype](https://michaelmassie.com/assets/img/chargeController.jpeg)

Adding a Sonoff (POWR316D) between the  wall outlet and battery get’s me almost 95% there, just looking to use their API it make a custom app to serve up the lock screen widget and handle custom settings.

Next challenge is if I can measure resistance to understand how full the battery is. 
