---
layout: post
tags: prototype
image: https://michaelmassie.com/assets/img/Gent4AtOffice.jpg
---

With a late finish close out to the 2019 year, I was awarded a patent for some work I've been doing on a side project here at Northwestern Mutual, and now finally able to share.

I made a new kind of Piggy Bank; one for a digital age and an increasingly currency-less society.

![Gen 4 at the office](https://michaelmassie.com/assets/img/Gent4AtOffice.jpg)

This concept originally stemmed from research we had been conducting about how chatbots could help guide a client with their financial goals - for instance, raise awareness about all those coffee charges aka the budget's "death by 1000 cups". The decision came fairly quick that if you're asking a chatbot about your savings than it's already at the forefront of your mind and attention. Therefore, the target audience would be those that aren’t thinking of it. In order to reach that audience the information would need to be always present visually. Something more in the way of an always-on “Glancable UI”, similar to the [Ambient Orb](http://www.ambientdevices.com/about/consumer-devices) - a desk light that displayed a data point based off a color spectrum that could connect to weather, stock market, etc.

With inspiration from an old favorite tech gadget, I was still in search of clearer opportunity to give useful nudges on the financial data point(s).

I didn't need to look much further than looking at the trends in currency and how cash transactions are being replaced by “tap to pay” and “buy now” buttons. While tech companies rush to remove the "friction" of making purchases the reality and the dark patterns are that they are effectively removing a very important ceremony that kept us aware of our spending. The ceremony of seeing and participating in the exchange of cash for goods played a key role in balancing the pleasure sensory of getting something new with the pain sensory of handing over your money.

Additionally, we have a young daughter at home and my wife and I just happen to be going over our investment options to put her thru college around the same time. With this research in the office, combined with what we were doing in our own home, one more thought came to mind: Could something like this work better to a younger audience?

Could we marry these ideas together with the concepts like Deferred Gratification - like the [Marshmallow Test](https://en.wikipedia.org/wiki/Stanford_marshmallow_experiment) - to see how an Ambient Orb-like glanceable UI could illuminate a positive experience on saving.

The idea came to be to build a prototype to promote financial literacy. A redesign of the iconic piggy bank for an age where currency is becoming less and less tangible, making visualizing savings even harder, not just for adults but also children.

So how are we doing in teaching financial literacy, anyway? Well it turns out the US has been on a steady decline since 2002 from a global stage. That's not good. It's been dropped from school curriculums and parents have limited modern tools to help tell this story. This illuminates an opportunity in educating the community in what is seemingly a starved market. 

![Mobile UI](https://michaelmassie.com/assets/img/screenshots.png)

![Gen 1](https://michaelmassie.com/assets/img/day1.jpg)

So here we are; an IoT Piggy Bank that connects to a mobile app that parents can control to show savings over up to four goals - save, spend, invest and donate (based off a popular savings teaching model). We baked in tools like allowance and weighted goals - so that money that goes into savings doesn't equally go toward college and a new game console. And now when Grandma and Grandpa give money for a birthday, holiday etc, even if it was sent digitally to the parent, the child can see it represented in their Piggy Bank.


![Gen 2 on workbenck](https://michaelmassie.com/assets/img/workbenchsitter.jpg)

![Workbench Madness](https://michaelmassie.com/assets/img/workbenchmidmadness.jpg)


The original design started on a Raspberry Pi but with the help of peers (all thanks below) it was recognized that we’d have to snub out a lot of extra services. So the build pivoted to [Particle's Photon](https://www.particle.io/) board offering better ability to scale and also cloud management. A custom PCB board was printed in order to hold the LED banks and then some tweaks and touches in case design (more on that below). More recently I added a Passive Infrared Sensor (PiR) to wake the device when there is movement in front of it. Don't worry, we also added wake/sleep hour settings in the app quickly after running some home tests. The rest is fairly straight forward, cloud services to manage state of the app and piggy bank. For connections to finances it’s relying on “sneaker banking” - aka the parents have to move the money in their bank of choice manually.

Throughout this journey, it's really been a coin toss about approach for a device like this - is it a finished off the shelf product or is it a deconstructed STEM hardware development teaching kit? Any option is available to pursue. While it’s still in very much a prototype form - see: too Storm Trooper for a kid’s room - I yearn for access to cheap injection molding to create something like a soft mint flat green fully enclosed piggy bank with lights that emit thru the plastic. It's hard not to get caught up in the aesthetics of the device, but the order of importance really lies in creating a compelling interaction between a child and this product.

That all being said, for now I am appreciating a major patent milestone as well as the ability to share this work.

### Final Update
I got a box of the final prototypes that went out to a pilot group to shelf, most likely indefintely. It was a fun run and a ton was learned. That'll do, pig. That'll do.
![One Last Pluggin](https://michaelmassie.com/assets/digipig/lastshot.png)
![Boxing](https://michaelmassie.com/assets/digipig/boxPigs.png)




Specials thanks, again: Danijela M, Chris M, Matt K, Chris He, Tony G, & Chris Ho.