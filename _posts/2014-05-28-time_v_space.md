---
layout: post
title: Time vs. Space
published: true
comments: true
tags:
- ia
---

![[Space-Time]](/assets/space-time.png)

My **favorite** living thinker [Scott Aaronson](http://www.scottaaronson.com/) maintains a blog called [Shtetl-Optimized](http://www.scottaaronson.com/blog/) which I love reading. A **large** percentage of my future posts will just be comtemplating his posts! The one Im currently working on is called ["Time: Different from Space"](http://www.scottaaronson.com/blog/?p=368). I came across it listed as a reference in his *fantastic* paper called ["Why Philosophers Should Care About Computational Complexity"](http://arxiv.org/abs/1108.1791) (blog post to follow for that paper!).

Scott wrote this post as his entry into the Foundational Questions Institute [(FQXi)](http://www.fqxi.org/) "The Nature of Time" competition. To put it simply (deceptively so), the article explains how because of relativity, people have learned to think of time as being "another spatial dimension". We have $x$,$y$,$z$ and $t$. The laws of physics work in any direction on *any* axis (forward or backward in time - see a future post about what gives time its foward flow!). However, coming from a computational complexity/information perspective Scott argues that time is fundamentally different from space.

He starts out explaining how even in the formalism of relativity, time behaves differently from space. "In special relativity, the invariant distance between two points $p$ and $q$ - meaning the real physical distance, the distance measure that doesn’t depend on which coordinate system we happen to be using - is called the **interval**.  If the point $p$ has coordinates $(x,y,z,t)$ (in any observer’s coordinate system), and the point $q$ has coordinates $(x’,y’,z’,t’)$, then the interval between $p$ and $q$ equals:"

$$(x-x’)^2+(y-y’)^2+(z-z’)^2-(t-t’)^2$$

The *tiny little* $-$ sign infront of the $t$ is a key marker that something is different! "If the interval between two points $p$ and $q$ is positive, then $p$ and $q$ are *spacelike* separated, meaning that there’s no way for a signal emitted at $p$ to reach $q$ or vice versa.  If the interval is negative, then $p$ and $q$ are *timelike* separated, meaning that either a signal from $p$ can reach $q$, or a signal from $q$ can reach $p$. If the interval is zero, then $p$ and $q$ are *lightlike* separated, meaning a signal can get from one point to the other, but only by traveling at the speed of light." Don't really get the *lightlike* seperation, but then again, havent really studied special relativity in quite sometime.

The key point is that the minus sign ensures time has a *causual* structure - basically that things in the *past* causually affect things in the *future* and not the other way around (stay tuned for a future post about the statistical notion(s) of causality!). He then goes on to say that "Put another way, the minus sign in front of the $t$ coordinate reflects what a sufficiently-articulate child might tell you is the main difference between space and time: you can go backward in space, but you can’t go backward in time." Scott has set the scene in the post for a key argument he made in the paper mentioned above, a complexity theoretic one: You can reuse the same interval of space to compute, but you can't reuse the same interval of time.

Im spending more and more time thinking about computability, and complexity (the more and more I read Scotts blog) and am increasingly fascinated by it. The rest of the article goes on to examine the $P \neq PSPACE$ conjecture, resting on the fact that in some sense, computationally speaking "polynomial space is more powerful than polynomial time". Ill write a seperate post about this later, as I expand on more of his posts and his book that I just ordered!

### Further Resources
* Complexity Theory Wiki [[link]](https://en.wikipedia.org/wiki/Complexity_theory)
* Complexity Zoo Wiki [[link]](https://complexityzoo.uwaterloo.ca/Complexity_Zoo)
* Scotts Book - Quantum Computing since Democritus [[amazon]](http://www.amazon.com/Quantum-Computing-since-Democritus-Aaronson/dp/0521199565)


*Note:* This post (and most of the ones to follow) is a combination of paraphrasing, copy/pasting, and my own thoughts/questions.

Image Credit: Wikipedia article on space-time [[link]](http://en.wikipedia.org/wiki/Spacetime)