---
title: "I changed my blogging platform... again"
categories:
  - Random
---

I recently started using Github Pages and Jekyll for blogging. This post summarizes my reasons.

<!--- more --->

I started blogging around 2012 using a local WordPress copy. Honestly, none of those posts survived the posterior changes, and even though many were quite awful, I liked a few of them. However, I ran into many problems back then. First and foremost, the infamous interface. Having all my posts of WordPress didn't allow me to blog except when online (something quite difficult in the pre-2019 Cuba) or have a local copy I would sync with the online version. Second, I had to use the WordPress UI, which I totally hate.

To overcome those problems I tried everything from hosting a local WordPress that I would `rsync` with the online version to using Windows Live Writer... yeah, I know... I was different back then.

Then came the era of static websites, I transitioned through Jekyll, Pelican and finally Hugo and settled there for a while. I hosted my own Hugo at a private VPS in Digital Ocean and would automatically `git pull` and regenerate using Github and Caddy. However, the major problem was that I was serving from my VSP hence, no `HTTPs` (this was before Let's Encrypt) and a bunch of maintenance problems. Let's Encrypt came alive around that time, and for a while I rejoiced in having my own domain with `HTTPs` served directly from my own VPS.

There was something cool about that, I felt like I owned something. I was the sole owner of my website, and I could decide exactly how everything was served and delivered...

Then I grew up, and realized this was nonsense. Getting things done is what actually matters. So I decided to try Github Pages. It's not super customizable, it does take away some basic freedoms that deep down in my mind create a small struggle, but I rug it off. I just can blog easier and with better quality if I'm not concerned with backend details. That is not my job, that's not what matters in my case.

It's delivering the message, not building the channel what I'm interested in. Github Pages let's me do that now, for free, easily and with sensible restrictions. If, and when, it starts to become more a problem than a solution, I will dump Github Pages without a second thought and move on to the next option.

And I'll probably write another post about it.
