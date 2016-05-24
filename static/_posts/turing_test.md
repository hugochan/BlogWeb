
---
layout: post
title: "Can AlphaGo pass the Turing test?"
date: 2016-5-21 22:00
slug: Can AlphaGo Pass the Turing Test
categories: Computer Science
tags:
- Computer Science
- Artificial Intelligence
description: Can AlphaGo pass the Turing test?
thumbnailImagePosition: left
coverImage: http://blog.hugochan.net/images/turing_test.jpg
metaAlignment: center
coverMeta: out
---

A few months ago, Google AI machine AlphaGo defeated the leading player in Go Li Sedol in the man-machine war...
<!-- excerpt -->


A few months ago, Google AI machine AlphaGo defeated the leading player in Go Li Sedol in the man-machine war. People were surprised at the superb skills AlphaGo showed. One may ask is artificial intelligence really coming, will it surpass our own? 

In order to answer these questions, we need to trace back to the fundamental question, that is, can machines like AlphaGo think? Well, that’s a knotty question as “think” is hard to define. Around 60 years ago, Alan Turing who is widely considered to be the father of artificial intelligence proposed the same question, “Can machines think?” He proposed a pragmatic framework to answer such a difficult philosophical question. This framework is often called Turing test which is what we’re going to discuss today. Has any of you heard of Turing test before? Don’t worry! I promise you’ll know more about it soon.

As we said, “think” is hard to define, Turing replaced the original question with a new one, which I would rephrase as “Can machines imitate a human?” Basically, you could regard the Turing test as a test of a machine's ability to exhibit intelligent behavior equivalent to, or indistinguishable from, that of a human.

Let’s see how we do a Turing test. Assume there’re two players and an interrogator. Player A is a human while player B is a computer. The role of the interrogator is to determine which is a human and which is a computer by making text-only conversations with each player separately.
If the interrogator cannot distinguish them at most time, the computer is considered to pass the Turing test. And we claim this computer can think like a human.

Now, going back to our original question “Can machines like AlphaGo think?”, can we do a Turing test on AlphaGo? Yes! If you watch the way AlphaGo plays Go, it’s quite similar to how humans do it. Actually, AlphaGo does better than most human players. In this case, AlphaGo absolutely passed the Turing test as there is no way for us to figure out whether we’re playing Go with a human or machine. However, I claim that AlphaGo should not be considered to pass the Turing test for two reasons. First, AlphaGo knows nothing but playing Go. In other words, it’s not a general thinking machine. Second, although AlphaGo is a master in terms of Go skills, does it really understand the philosophy of Go? If an interrogator asks AlphaGo for some intuitions or thoughts of Go, can it answer well and pass the test? Probably not.

Well, in this short article, I introduced the basic idea of the Turing test and how it works. We together applied it in a real problem.
