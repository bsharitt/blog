---
layout: post
title: "I Finally C Something Interesting"
date: 2020-04-12 10:11:00 -05:00
---

In my last post I talked about finding a side project, and I had narrowed down my options to diving 
deeper into Go, making a game with Godot, or writing something mobile with flutter. I could never make 
myself try out flutter, right now mobile just isn't interesting to me at all. While I'd to get to know 
Go a bit better, I'll have opportunities for that in my day to day job as I get deeper into the 
Kubernetes world, but I really like the idea of either learning a general purpose programming language 
that has a bit more going on than my current go to language, Python. At the same time, while playing 
Godot, I found that while I do like the idea of a making a game, pasting my own scripts on top of 
other peoples' pre-made engine isn't terribly satisfying. Of course if my goal was to ship a game then 
using an existing engine would make the most sense, but this is a hobby project just to scratch my own 
creative itch, so starting from scratch isn't a crazy idea. I briefly considered Go for this, but 
after a brief skimming of some forums, it appears to be possible to write games in Go, but it's not a 
great match for the task. More of a fun thing for existing Go aficionados to do, which isn't me yet 
and didn't seem to be the best way for me to learn Go. So I thought about what libraries I'd be using 
and even today, SDL seems like a decent choice for basic game development. So while it does have 
bindings to several languages, even Go, it's a C library at its core. I'm no stranger to C, I learned 
a bit of it when I was in high school, even doing some rudimentary operating system development, and 
learned it a bit more properly in college, but I've probably not touched it for a serious project in 
about 15 years. The amount of forgotten is far more than what I remember, but it should be fun to pick 
back up.

Some of you may be asking why I don't use Rust, C++, or some other supported language. One additional 
thing I realized when I picked C, is that it'll dovetail nicely with the various microcontroller 
boards I have in the closet. Right now they're mostly set up for arduino or maybe micropython, but 
learning C again would give me a lot more options with those. I really like the idea of low level 
system programming and maybe I could even get back into some operating system development. So that 
leaves out most of the languages on list. Rust seems interesting, but it's still growing and a lot of 
the tooling is still maturing, especially on the game development side where I plan to start out, so 
it's off the table for now, but who know, once I have a taste for learning programming languages again 
I may pick it up down the line. Finally we get to C++. Honestly I don't have a good answer for this 
one except personal preference. Back when I did play around with C before I also picked up some C++, 
and I alway just found C to feel "cleaner". I might pick up some C++ down the line as needed, but for 
now I'm going to stick with plain C as much possible. I've been playing around with it this weekend 
and I'm finding that I remember more than I thought(probably helps that nearly every other language 
I've used in recent years has ripped off C in someway) and I'm feeling about computers in a way that I 
haven't felt in a long time. Sort of a feeling of excitement and awe just being a bit less abstracted 
away. Compared to Python, Go, or Java I'm basically playing without any guard rails and it's fun. I 
guess after so many years being stuck far further up the stack, it's nice to be reminded that there's 
lower level that can mucked around with too. 