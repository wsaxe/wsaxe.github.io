---
layout: post
title:  "Adventures in Gem-Craft"
date:   2016-07-25 22:24:54 -0400
---


One of the most interesting aspects of the Ruby programming language is the ability to stitch together various fully functional modules called "gems" to make a larger program. 

![Ruby Gem](https://stormpath.com/wp-content/uploads/2016/04/preview_COLOURBOX4628597.jpg)

As a student of programming, I have been asked to build one of these gems that scrapes data from the the web and displays it through a [Command Line Interface (CLI)](https://en.wikipedia.org/wiki/Command-line_interface). 

This program won't be useful to most users on it's own, but as part of a larger program, it can be used to add essential functionality without the developer needing to "re-invent the wheel" when this fucntionality exists in the gem program already.

SInce this is the most complex project I have been asked to do so far, I was a bit intimidated. Looking at some of the examples, I didn't believe that I had the skills yet to create something so complex:

[https://github.com/learn-co-curriculum/now-playing-cli-gem](https://github.com/learn-co-curriculum/now-playing-cli-gem)

[https://github.com/dannyd4315/worlds-best-restaurants-cli-gem](https://github.com/dannyd4315/worlds-best-restaurants-cli-gem)

For a while, I just stared at this blank terminal/text editor:

![Coder's Block](http://cacm.acm.org/system/assets/0000/4887/032011_CACMpg34_Coders-Block.large.jpg?1300392330&1300392329)

I had a few false starts, but my breakthrough came when I listened to some coaching from [@aviflombaum](https://twitter.com/aviflombaum) . Avi did an awesome job of describing his personal coding process, which I've tried to adopt since:

To paraphrase, Avi used an "outline" approach. 

Essentially, step 1 is to create a basic shell of a program that outputs pre-fomatted text to the terminal in the format that the final data would be if the program were fully written. In effect, you are "faking" the final result as if the program is working. Of course, this isn't the final product, and it doesn't have the needed functionality, but it serves as an "outline" of what the program might do in the future.

Step 2 is to work on replacing the "fake" code with real methods, objects, etc. that have real functionality. Work on this level by level until you have fully replicated the essential functionality. 

Using this method, I was able to create a working program right away, and incrementally improve it until it was performing all needed functionality. 

You can check out the finished CLI Gem here:

[https://github.com/wsaxe/bookworm-best-sellers](https://github.com/wsaxe/bookworm-best-sellers)

[https://rubygems.org/gems/bookworm_best_sellers](https://rubygems.org/gems/bookworm_best_sellers)
