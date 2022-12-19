---
layout: post
tags: project, tech, app
image: https://michaelmassie.com/assets/img/trailpostApp.JPG
---

![Traipost](https://michaelmassie.com/assets/img/trailpostApp.JPG)

Started a project a couple months ago and this weekend it's finally in a working Beta. 

This is **Trailpost**, a conversation interface connection to [Trailforks](https://www.trailforks.com/). Currently it works with Google Assistant, but the end goal is having it running on Alexa, later, in time to run it in a Rivian (delivery date: April-June).

I've been overdue to get into a coding project that I can dig into AWS Lambda, Chat Apps/NUI, and APIs; this seemed the perfect canidate. Building in AWS allowed me to use what we already have in the home - [Google Digital Assistant](https://developers.google.com/assistant) - and then expand to Alexa for car connectivity. Now I can ask about my favorite trails in the morning and check to see what their most recent condition reports are before heading out to ride.

This project connected to the Trailforks API in order to get the most recent updates on the trails. I then added a list of my favorite trails to the Google Assistant project that can pass thru the intents and I can then return results from Trailforks. As of now, not many people update trail conditions, but that was half the point - it was about the project and maybe even then promote people to update reports.

[![Git Repo](https://michaelmassie.com/assets/img/gitrepoTrailpost.jpg)](https://github.com/mmassie/trailpostBackend)

### TODO

While it's up and working I'll now start adding some extra features, like a human readable (from EPOC) time stamp of when the trail was last updated and then local weather for a little more accuracy so I know how to dress before I head out.

I have some 7 segment LED displays too that I may look to incorporate into a physical version based off the original concept sketches I had made:

![Trailpost Sketch](https://michaelmassie.com/assets/img/trailpostSketch.png)

