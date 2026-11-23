---
layout: post
tags: project
image: https://michaelmassie.com/assets/img/duet.jpeg
---
# Duet: a winter build, and what "making" means now

*A book and a music player that fit in one hand.*

'Tis the season for this year's winter project.

I'm calling it **Duet**. It's a Kindle-sized e-ink reader with an MP3 player built in, which plays through headphones or Bluetooth. The case is 3D-printed, the boards are off-the-shelf ESP32s, and every file it took to make it is open source.

![Duet](https://michaelmassie.com/assets/img/duet.jpeg)

## Why build it

I wanted a device that:

- **Needs no subscription.** You own the books and music on the card. Nothing expires, and nothing gets pulled from your library.
- **Needs no server.** No account, no cloud, no app. It works the same in ten years as it does today.
- **Is open source.** Firmware, case files and wiring are all GPL. If something breaks, you can open it, see how it works and fix it. That's what the right to repair looks like when it's designed in from day one, not fought for later.
- **Can be upgraded.** The case is parametric, the boards are off-the-shelf, and the code is yours to change.

## How it got made

The other half of the story is how it got made. I built Duet with Claude.

So is it still "making"? I think so, more than ever.

AI didn't decide what this device should be or why it should exist. It didn't hold the soldering iron. It didn't notice that the side buttons wouldn't seat, or see the mounting posts snap on the first print, and it didn't make the UI decisions. It didn't decide to swap two boards so the wires would run shorter. Every one of those came from my hands and my eyes, then went back into the design.

What changed is the distance between an idea and a working thing. Skills that used to take years, like embedded C, CAD and EPUB parsing, now sit one conversation away. That doesn't make the maker less important. It makes taste, judgment and stubbornness the whole job.

And because it's open source, the next person doesn't start from zero. They start from here.

## Build one

The repo has the build guide, the STLs and the firmware:
[github.com/mmassie/duet-media-player](https://github.com/mmassie/duet-media-player)

If you build one, or break one, I'd love to hear about it.