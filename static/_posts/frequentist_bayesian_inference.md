---
layout: post
title: "贝叶斯与频率学派"
date: 2015-12-16 00:30
slug: Bayesian and Frequentist Inference
categories: Thinking Beyond Technology
tags:
- Thinking
- Technology
- Bayesian Inference
- Frequentist Inference
description: 贝叶斯与频率学派
coverImage: http://blog.hugochan.net/images/bayesian_frequentist_inference.jpg
metaAlignment: center
coverMeta: out
---

我们知道，因果律是一切科学的基础。人类依靠因果律这一强大的思想武器，企图认识这个世界的本质。无奈，在这个大千世界，我们所能直接观察到的都是这个果……
<!-- excerpt -->


## 从因果律开始
我们知道，因果律是一切科学的基础。人类依靠因果律这一强大的思想武器，企图认识这个世界的本质。无奈，在这个大千世界，我们所能直接观察到的都是这个果，背后的因永远是隐藏起来的。而由果及因，过程中充满无数的陷阱。举个简单而有趣的例子，有一头猪，在它短暂一生的前99天里，它观察到主人对它无微不至，自己吃喝不愁，任它如何推理，都万万想不到第100天它竟被主人拉出去宰杀了。其实，我们面对这个未知世界的认知困境，本质上没有比这位猪兄的幸运多少。

于是我们慢慢意识到，这种东一榔头西一棒槌、乱扯因果关系的思考方式，并不常常奏效。我们需要更深思熟虑一点，我们需要对复杂的外部世界进行建模，私以为建模其实就是***抓住事物发展的主要矛盾，研究矛盾主体间的联系和作用***。比如，我们对A事件的发生产生了兴趣，想研究研究，我们可能觉得事件B和C跟事件A有点关系（比如它们仨老是一块儿出现），于是设计了一个模型，让事件B和C经过怎么怎么一个过程，能驱动事件A。有了这个模型，我们就能通过对比模型的输出结果与现实世界的观测结果，验证或优化模型。正是通过这种日拱一卒的劲头，我们一路走到了今天。想想真为这些前人们感动。

## 频率学派
不知什么时候起，我们对随机事件这类问题产生了兴趣。频率学派的观点是，***随机事件的发生其背后一定有某种深层的产生机制，虽然产生的事件（果）本身是随机的，但这个机制（因）应该是确定的。***用前面提到的方法论，我们首先要提出一个模型来模拟这种机制，但这个模型是待定的（模型参数未知），不过我们可以通过大量的观察结果（evidence）来推理（inference）出模型参数。我们这么做的原因正是我们相信，***随机事件的发生是由其背后的机制决定的，虽然孤立的随机事件不能给我们太多信息，但大量的随机试验结果蕴含着这种机制的重要信息。***一个最典型的例子就是抛硬币，抛一枚硬币，可正可反，但当进行大量抛硬币试验后，试验结果将“告诉”我们有关这枚硬币的一些重要信息（例如正反面是否均匀等）。总结一下，频率学派的典型思维是产生机制是确定的，机制产生的结果是随机的，但大量的随机结果蕴含着某种确定性，由此我们可以认识产生机制。

## 贝叶斯学派
贝叶斯学派不这么看问题。他们爱提一个叫信念（belief）的概念，**其本质是概率，表征人们对某一事件发生的相信程度。**与频率学派正相反，他们认为，人们对产生机制的信念是不确定、可改变的，机制产生的结果（evidence）在发生以后却是确定的。他们从人类认知事物的一般过程角度出发，认为人们对产生机制的信念变化遵守这样一个过程。***在看到任何机制产生的结果前，人们对此抱一个最初的信念（先验信念），然后人们陆陆续续看到了很多结果，再相应地更新信念（后验信念）。***这一迭代的过程使得人们不断接近对机制本质的认识。

举一个简单的例子，有一个外星人在一天夜里来到地球，他想弄清楚地球的太阳从哪边升起。首先，他大胆假设太阳从西边升起，这是他的先验信念。然后他开始仔细观察太阳的实际初升。第一天，他发现太阳竟从东边升起了，与他的先验假设不符，因此他稍稍降低了对此的信念。后面连着观察了99天，他发现无一例外太阳都从东边升起，他对原始假设的信念也降低到了新的低点。**但注意，此时他并没有完全否定太阳从西边升起的可能性，只不过他认为这种可能性很低了。**这是贝叶斯学派的特点。

## 两种认识论
贝叶斯与频率学派实际上代表了人类认识世界的两种思路。举一个不恰当的例子。频率学派的认识论好比唯物主义的观点，他们认为机制决定结果，虽然孤立的结果带有随机性，但大量随机试验的结果一定蕴含着机制的确定性信息。而贝叶斯学派的认识论有点像唯心主义的观点，他们最大的特点是以观察者为主体，观察者对机制的信念会随着观察结果而变，观察结果既然发生了便是确定的。**注意，贝叶斯学派并没有声称机制是随机变化的，变化的是观察者对机制的信念。**其实反过来一样的道理，唯心主义者也没有狂妄到认为外界真实世界随自己的意念而变，变的是外界世界在观察者内心的投影。

## 争论与较量
正如唯物与唯心主义是两种不同的认识论，并无高下优劣之分。贝叶斯与频率学派也无高下优劣之分，它们都能为人们所用，目的都是认识世界。它们各有优劣势，频率学派计算简单，长期占据主流地位，贝叶斯学派随着近几十年计算能力的大幅提升，越来越受人们重视。理论上，当观察的结果集无穷大时，这两种思路的推理结论是一致的。而在小规模结果集上，贝叶斯学派则显示出了它的优势，其效果一般好于频率学派。

#### 参考文献
[[1] Bayesians and Frequentists - Models, Assumptions, and Inference](http://www.stat.ufl.edu/archived/casella/Talks/BayesRefresher.pdf)
