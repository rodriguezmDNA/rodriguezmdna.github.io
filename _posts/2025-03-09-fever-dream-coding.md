---
layout: post
title: pixel sorting fever dream
date: 2025-03-09
description: weekend coding project
tags:
categories: coding
---

<style>
  .spaced-text {
    line-height: 2;
  }
  .half-hr {
    width: 50%;
    margin: auto;
    border: 0;
    border-top: 1px solid #ccc;
  }

</style>

I rarely get sick, but when I do my brain shuts down and prevents me from <em>being productive</em> at all costs. Since apparently I can't rest like a normal person I started reading Richard Hamming's <em>Art of Doing Science and Engineering</em>. One of my initial takeaways is that one can just do things, and should do things. 

During a rest/doom-scrolling session I came across this tweet by Paul Graham

{% twitter https://twitter.com/paulg/status/1877731782277107952 %}

The top answer caught my eye: A pixel sorting tool. 

It seems that it was built with [Cursor](https://www.cursor.com), and I've been hearing about vibe coding with AI.

So I decided to do a thing: I made [pyXsort](http://rodriguezmdna.github.io/pixsort/). I wanted to see if I could just "make anything". Not a fulll-fleshed app in 20 minutes, but something over a week. It turned out I could do over a weekend. Thanks to ChatGPT I learned that PyScript exists and I could use it to make a simple web app. I also learned that I did not have to set up a server to host it, I could just use GitHub Pages. Everything would be processed on the client side. I tried prompting o3-mini-high as well as the newest 4.5 version, but neither work on the first try. I did a bit of old school Googling and saw that the call to PyScript was wrong. I fixed it with the help of a Hello World example and some trial and error. In the end I got a good-enough working app that anyone (n=3) could use.

Is it useful? No. <br>
Is it dumb? Yes. <br>
Is it fun? Absolutely...maybe? <br>

I don't know...I'm still sick, but I did a thing and it was fun and I got to learn and that was the goal so play with it if you want:

<iframe src="https://rodriguezmdna.github.io/pixsort/" width="800" height="800"></iframe>