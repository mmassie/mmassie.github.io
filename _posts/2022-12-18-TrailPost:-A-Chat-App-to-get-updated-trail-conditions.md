---
layout: post
tags: project, tech, app
image: https://michaelmassie.com/assets/img/trailpostApp.JPG
---

![Traipost](https://michaelmassie.com/assets/img/trailpostApp.JPG)

Started a project a couple of months ago and this weekend it's finally in a working Beta. 

This is **Trailpost**, a conversational interface connection to check on trail conditions (Powered by [Trailforks](https://www.trailforks.com/)). Currently it works with Google Assistant, but the end goal is having it running on Alexa in time to run it in a Rivian (delivery date: April-June). No real rocket science here, it's a fairly straighforward build, but fun none-the-less.

As an intial prototype I dropped the Trailpost widget into a Chrome Extension to get a feel for how often trails are updating and a general feel for usefulness of the data:
![Chrome Extension](https://michaelmassie.com/assets/img/chromeextension.png)


The data getting posted was few and far between but the overall experience was very convenient and sometimes bothersome to see great trail conditions while sitting at my desk. 







I've been overdue to get into a coding project that I can dig into AWS Lambda, Chat Apps/NUI, and APIs for some time; this seemed the perfect canidate. Building in AWS allowed me to use what we already have in the home - [Google Assistant](https://developers.google.com/assistant) - and then expand to Alexa for car connectivity. Now I can ask about my favorite trails in the morning and check to see what their most recent condition reports are before heading out to ride/run. 

This project connected to the Trailforks API in order to get the most recent updates on the trails. I then added a list of my favorite trails to the Google Assistant project that can pass thru the intents and I can then return results from Trailforks. As of now, not many people update trail conditions, but that was half the point - it was about the project and maybe even then promote people to update reports.

[![Git Repo](https://michaelmassie.com/assets/img/gitrepoTrailpost.jpg)](https://github.com/mmassie/trailpostBackend)



### Updates

1. With Goodle Conversational Actions shuttered I am currently moving everyhing to just Alexa.


2. Hardcoded results to test in a Rivian: [https://www.instagram.com/p/CvSUoEmAkP6/](https://www.instagram.com/p/CvSUoEmAkP6/) ✅




### To-Do

1.  Once ported over I'll now adding some extra features, like local weather for a little more accuracy so I know how to dress before I head out.


#### Hardware Build

2.  I have some 7 segment LED displays too that I may look to incorporate into a physical version based off the original concept sketches I had made below:

![Trailpost Sketch](https://michaelmassie.com/assets/img/trailpostSketch.png)

Home for the Holidays!