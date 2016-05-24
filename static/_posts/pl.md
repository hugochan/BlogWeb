
---
layout: post
title: "Two ways of thinking about programming language"
date: 2016-5-24 11:00
slug: Two Ways of Thinking About Programming Language
categories: Computer Science
tags:
- Computer Science
- Programming Language
description: Two ways of thinking about programming language
thumbnailImagePosition: bottom
coverImage: http://blog.hugochan.net/images/pl.jpg
metaAlignment: center
coverMeta: out
---

Even at the early stage of programming language when von Neumann languages were monopolistic, John Backus began to challenge...
<!-- excerpt -->


Even at the early stage of programming language when von Neumann languages were monopolistic, [John Backus](https://en.wikipedia.org/wiki/John_Backus) began to challenge this convention and think about some fundamental problems of programming language. In his famous paper “Can Programming Be Liberated from the von Neumann Style”[1], he proposed some crucial issues of von Neumann languages which can be summarized as follows:

a) Von Neumann languages are flabby, complex, and inflexible.
b) Their semantics are too closely coupled to the state which makes it hard to reason about programs.
c) They lack expressive power. They’re unable to effectively use powerful combining forms for building new programs from existing ones.

He found that this kind of programming style is closely related to von Neumann architecture of computer systems where the word-at-a-time tube connecting the CPU and the store. Hence, this kind of language “concerns itself with this word-at-a-time traffic through the bottleneck rather than with the larger conceptual units of our problems.” It’s too detailed and over-controlled but lose the big picture of problem-solving. It splits programing into two worlds: “an orderly world of expressions, a world that has useful algebraic properties” and “a disorderly world of statements, with few useful mathematical properties.” A program is a sequence of statements. Programmers have to teach computers how to solve a problem in very detail which is terrible when dealing with large-scale and complex problems.

In addition to pointing out the issues of von Neumann languages, he proposed an alternative functional style of programming which aims to avoid all of the above problems. In his word, it’s supposed to be a language having a small framework which could accommodate a great variety of powerful features entirely as changeable parts. It doesn’t have side effects. It’s easy to combine existing functions to form a new one. It should overcome the history-sensitive problem of lambda-calculus languages. So "Applicative state transition" (AST) systems were proposed as history-sensitive alternatives to von Neumann systems. 

I regard his contributions in this paper as follows: He summarized the major issues of von Neumann languages which were monopolistic at that time. He proposed many important programming concepts as well as a formal functional programming (FFP) system. Overall, what he mentioned are quite to the point and widely accepted today. I think his work has pushed forward the rise of functional programming. However, his arguments were still not quite complete as he ignored some obvious advantages (e.g., performance) of von Neumann languages which are exactly the disadvantages of functional language. Of course, because of the historic limitations, he couldn’t forecast the boom years of object-oriented programming (OOP) which has saved von Neumann languages in some sense.

Furthermore, I think his early work indicated some beliefs or natures of programming language. As said, programming language is designed for humans, but happens to be able to run on machines. I agree a good programming language should help liberate programmers’ creativity and make programmers focus on high-level aspects (e.g., strategy, framework, etc.) of problem-solving. With the rapid development of hardware performance, programmers’ time becomes much more important than machines’ running time in most scenarios. I believe this trend will inevitably continue and we will have more advanced (e.g., abstract, intelligent, etc.) programming languages in the future which make programmers much more like a program designer than a program writer. All the low-level stuff in current programming practice will be hidden from programmers and automatically finished by machines. As the daily problems programmers may deal with become more and more complex, programmers should be liberated from controlling the very detail of a software and focus more on high-level reasoning of a software.

Based on our beliefs or expectations of programming language, mainstream programming language in the feature should have a concise and elegant framework, have the strong expressive power to model the world effectively and naturally as well as being user-friendly. A high-level programming language should be away from hardware but close to logic and problem-solving. This kind of programming language becomes an assistant of a programmer, while as a programmer, our job is to tell machines what should be done to solve the problem instead of how to solve the problem step by step. We can see that many of the above ideas can be found explicitly or implicitly in Backus’s paper.


## references
[[1] Can Programming Be Liberated from the von Neumann Style.](http://dl.acm.org/citation.cfm?id=359579)
