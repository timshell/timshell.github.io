---
layout: post
title: Have the Empiricists Won?
description: 
category: articles
blog: true
date: 2016-10-31
tags: 
---

Two of the hottest buzzwords in the tech industry right now are "artificial intelligence" and "machine learning". Machine learning is a subset of artificial intelligence that can be loosely described as automated data analysis. It promises us less human capital intensive methods to teach computers about the world. I previously talked a little about what machine learning is and its potential applications [here](/machine-learning-and-politics).

Large companies (e.g. Google, Facebook, Amazon) are slowly monopolizing the machine learning space because they have the single greatest asset: data. Machine learning algorithms are only as good the datasets they are applied on. Create a bigger database and the accuracy of your algorithms soars.

In this way, machine learning researchers differ from traditional statisticians. Statisticians care about accurately describing their confidence level in some statistic of a dataset. Machine learning researchers just want to get the best predictive accuracy humanly possible and will do anything to accomplish this, from running their algorithm on massive clusters to building a bigger dataset.

The renaissance of deep learning has created much of the current hype in artificial intelligence and machine learning. Deep learning is based on neural networks, a biologically-inspired set of functions. These algorithms are all around us today, whether it be Facebook's automatic photo tagging or Apple's Siri. 

It has been called "[unreasonably effective](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)". Why unreasonably? 

Well, there is actually very little theory behind it. It is not guaranteed to work. Neural networks work by minimizing a given error function. Basic calculus distinguishes between local minima and global minima. The very best solution is at the global minima. Yet, neural networks only find local minima. We hope that the local minima are close to the global minima, but we cannot currently prove that.

Then why is it so effective? The dataset. Throw enough examples at these networks and they will learn to classify objects. Our solution might not be optimal or mathematically elegant, but it works.  

In pre-Kantian epistemology, the two opposing camps  are the rationalists and empiricists. Rationalists, led by Rene Descartes, believe in *a priori* reasoning. Given a set of assumptions, what can you deduce? On the other side are Hume and the empiricists. This camp prioritizes *a posteriori* reasoning, or learning from experience.

Neural networks have so far been on the empiricist side: let's observe a lot of data and make conclusions from them. While other machine learning methods have more theory behind them, they still all also tend to be empiricist-based. Without data, they are nothing. University of Washington Professor Pedro Domingos analogized machine learning to the scientific method. Make a hypothesis and collect some data. Refine your hypothesis and repeat.

Whether we accept that neural networks will lead to an artificial general intelligence or not, it does seem that some combination of machine learning methods will do so. Rule-based (i.e. rationalist) systems have failed in the past and do not achieve an accuracy near modern methods. Empiricists are dominating the field, and it is highly unlikely that data will become less important. Given the vast amount of data we currently have and are generating, why not use it if we can? We have the computing power to do so.

So, what is happening to the rationalists? They've turned their sights to a new issue: the control problem. Let's say we have an artificial agent smarter than humans. How do we make sure its values are aligned with ours? We don't want to make foes of these agents. After all, general consensus to why humans have dominated the planet is because of our intelligence. When we lose this monopoly, how do we ensure our survival? 

Rationalists are working at institutions like the [Future of Humanity Institute](https://www.fhi.ox.ac.uk/) and [MIRI](https://intelligence.org/), trying to assess the existential risk posed by superintelligent agents and how to best avoid such a situation. We can see why an empiricist approach will not work: all it takes is one nonaligned agent to impend world doom. There is no room for error and thus rationalists need to be able to accurately predict and avoid this scenario.

It should be noted that empiricists have been criticizing rationalists for focusing so heavily on this problem. Two famous machine learning professors, Andrew Ng and Pedro Domingos, have respectively called it an "unnecessary distraction" and "completely absurd". They believe the threat is (1) overhyped and (2) too far away to even worth considering.

Empiricists and rationalists are not disjoint. While many have a preference for a side, it often takes collaboration from both sides to produce optimal solutions. Elon Musk (who is famous for his rationalist approach of reasoning from first principals) has recently funded OpenAI, a research organization aiming at developing an artificial general intelligence while being cognizant of its risks. So far, the group has been working on reinforcement learning, learning by trial and error - a very empiricist way of learning.

But it does seem that the empiricists have surged ahead of the rationalists at the moment. It’ll be interesting to see whether the rationalists will contribute to the lack of theory in the machine learning space or focus more on the existential threat posed by artificial intelligence. 

---

Much thanks to Rachel Hottle for providing feedback on earlier drafts of this post.

