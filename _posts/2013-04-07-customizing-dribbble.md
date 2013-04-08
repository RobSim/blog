---
layout: post
title: Customizing Dribbble
date: 2013-04-07 18:54:19
---

I'm addicted to [Dribbble](http://dribbble.com/Robs.im). I'm on there all the time. The reasons don't really matter, as that's not what this post is about. This post is about customizing [Dribbble](http://dribbble.com) to suit your browsing style. Before we get started, you need a couple of things. First, you need a computer, and second you need [Chrome](https://www.google.com/intl/en/chrome/browser/). I have no idea how to do any of this stuff on iOS, but if you do, please [let me know](mailto:me@robs.im).

If you're on [Dribbble](http://dribbble.com), you probably end up adding things to [buckets](http://blog.dribbble.com/post/5674008788/buckets). As time goes on, you get more and more buckets. Of course the bucket pop up only shows about 3 buckets before you have to scroll to find more. I can't stand this, so using [stylebot](https://github.com/ankit/stylebot) I made a solution.
>div.lightbox {
>    height: 750px; // (# of Buckets)*(100) + 50
>}
>
>ol.buckets.group {
>    height: 630px; // (# of buckets)*(100) - 70
>}
What this does is it expands the space on the bucket pop up, saving you from scrolling. Kind of a minor thing, but I wish the Dribbble team implemented it instead of the user having to do it themselves.

Some other chrome extensions I use are [Alex Pankratov](http://swapped.cc/)'s [Is A Follower](http://swapped.cc/#!/is-a-follower), which tells you if a user is following you when you view their profile, [Dribbble HD](https://github.com/Darsain/chrome-dribbblehd), which shows you HD shots everywhere instead of thumbnails and [Endlesss](https://github.com/dedene/endlesss), which gives Dribbble infinite scrolling. Endlesss and Dribbble HD don't quite play well together, so I'm only using Dribbble HD right now, but they both contribute greatly to the experience. If you have your own tips and tricks, [let me know](mailto:me@robs.im).
