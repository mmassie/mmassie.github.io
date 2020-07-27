---
layout: post
tags: art
image: https://michaelmassie.com/assets/img/errorArt.png
---
### From a chaotic start, illuminating disorder to clarify upon resolution

** Work in Progress **

Recently left feeling inspired to work on some art again after picking up [Speculative Everything](https://mitpress.mit.edu/books/speculative-everything), I decided to start building cases for a project I had conceptualized a year ago. Although in contradiction to the book and its focus on "Radical Design", it is art to bring focus to a corporate concern. 

The art is a combination of 2 parts: 1) The projection of a falling data point/music note via video projection or portrait mounted TV, and (2) A servo animated xylophone player to play the note as it reaches the bottom of the screen.

![](/assets/img/errorArt.png)

This artwork intends to play a song, but if error rates are too high the resulting composition will be too chaotic to be able to be recognized.

The concept came from a few sources. First, we were discussing what a tech + art event could look like for the city of Milwaukee. I had proposed offering up an API for a single value and then offer that up to artists to build a sculpture around the data it receives; think of it as a Burning Man around data. The second point was to make an installment as an example. It also turns out I know of a process that has a high rate of error and the error leads to extra processing time for the customer. I though maybe if we demonstrate how significant that error rate is, we could inspire action to fix, and if the results are real-time there is a direct reward to changes made to improve the experience.

### How does it work?
Data collected over [time] to establish composition to play during “open hours”. Data is collected in a simple boolean database capturing if each entry over times was entered TRUE or FALSE.
0 - Standard entry falls at 1x rate
1 - Error entry falls at [random] rate

The images representing the collected data falls from the top of the artwork toward the bottom to its respective musical input/key.

A hardware switch offers 2 options of playback:
A - Xylophone or piano actuates hit to the tempo of the image to composition.
B - Speaker or Headphones plays the tone associated to the composition

Result: As error rates decrease due to us fixing the services in our client solution the composition becomes more apparent = Great Unveil

