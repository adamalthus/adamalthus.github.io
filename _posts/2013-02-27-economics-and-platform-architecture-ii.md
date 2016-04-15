---
id: 710
title: Economics and Platform Architecture (Part 2)
date: 2013-02-27T21:22:29+00:00
author: Jonathan
layout: post
guid: http://www.adamalthus.com/?p=710
permalink: /blog/2013/02/27/economics-and-platform-architecture-ii/
image:
  - 
quote-author:
  - Unknown
quote-url:
  - http://
quote-copy:
  - Unknown
audio:
  - http://
link-url:
  - http://
categories:
  - Apple
  - Cloud
  - Competition
  - CompSci
  - Economics
  - Futures
  - Intel
  - internet
  - Microsoft
  - Networks
  - Oracle
  - Platforms
  - Uncategorized
---
[Part I](http://www.adamalthus.com/blog/2013/02/27/economics-and-platform-architecture-i/) in&nbsp;this series of&nbsp;articles outlined the impact that the _economics of&nbsp;scarcity_ has had on&nbsp;both software architectures and the structure of&nbsp;the computer industry over the last forty years. Part&nbsp;II of&nbsp;the article will discuss the transition from the _economics of&nbsp;scarcity_ to&nbsp;the _economics of&nbsp;abundance_ and how profoundly that has altered&nbsp;&mdash; and continues to&nbsp;alter&nbsp;&mdash; the computing landscape.<!--more-->

The introduction of&nbsp;the IBM&nbsp;PC in&nbsp;the early 80's laid the foundation for a&nbsp;transformation in&nbsp;the economic model of&nbsp;the computing industry. IBM broke with its traditional model when it&nbsp;outsourced the supply of&nbsp;the computer processor and operating system for its Personal Computer (PC.) Little did IBM know that this single decision would transform an&nbsp;industry. The decision to&nbsp;source processors from Intel and an&nbsp;operating system from Microsoft and to&nbsp;not bind both these suppliers to&nbsp;exclusive supply agreements created the opportunity to&nbsp;build a&nbsp;3rd party&nbsp;PC industry based IBM&rsquo;s generic blueprint. The market for PCs grew and other players such as&nbsp;Compaq created competitive alternatives to&nbsp;IBM. The highly competitive dynamics of&nbsp;the&nbsp;PC industry based on&nbsp;the _open_ hardware blueprint created by&nbsp;IBM had very direct consequences.

Rampant competition within the nascent&nbsp;PC industry kept prices under control and yet each vendor&rsquo;s hardware ran the same DOS&nbsp;&mdash; and subsequently Windows&nbsp;&mdash; operating system licensed from Microsoft. This in&nbsp;turn meant that every&nbsp;PC sold became an&nbsp;available 'socket' for a&nbsp;growing ecosystem of&nbsp;application software developers. The same application would run without modification on&nbsp;every model of&nbsp;PC. The combination of&nbsp;these factors lead to&nbsp;exponential growth in&nbsp;the sales of&nbsp;PCs and this growth lead to&nbsp;vast economies of&nbsp;scale in&nbsp;the production of&nbsp;microprocessors, disk storage and memory chips. All of&nbsp;this was enabled by&nbsp;dramatic improvements in&nbsp;hardware fabrication technology&nbsp;&mdash; largely following Gordon Moore&rsquo;s law. As&nbsp;a&nbsp;result we&nbsp;have witnessed an&nbsp;approximate doubling in&nbsp;computational capacity, program memory and disk storage capacity every 12&minus;18 months continuously for over forty years.

In&nbsp;the early 2000's the computing industry reached a&nbsp;tipping point where hardware capacities started to&nbsp;outstrip the demands of&nbsp;application software. The industry was about to&nbsp;transition from _economics of&nbsp;scarcity_ to&nbsp;the _economics of&nbsp;abundance._ The impacts of&nbsp;this transition were&nbsp;&mdash; and continue to&nbsp;be&nbsp;&mdash; profound. The _economics of&nbsp;abundance_ mean that hardware resources can be&nbsp;viewed as&nbsp;essentially unlimited. It&nbsp;is&nbsp;interesting to&nbsp;note that it&nbsp;was at&nbsp;this time that Intel entered the software business. It&nbsp;did so&nbsp;because it&nbsp;felt the need to&nbsp;incubate new software technologies which would utilize the full capacity of&nbsp;the chips it&nbsp;was producing. If&nbsp;processor capacity far outpaces the demands of&nbsp;Microsoft Windows, Office and a&nbsp;Web Browser then consumers do&nbsp;not need to&nbsp;upgrade their machines that often&nbsp;&mdash; and that is&nbsp;bad for Intel&rsquo;s business.

It&nbsp;is&nbsp;hard to&nbsp;understate the impact of&nbsp;this transition from scarce to&nbsp;abundant computing resources. The iPhone is&nbsp;a&nbsp;child of&nbsp;this transition. The economics of&nbsp;producing a&nbsp;completely integrated, highly functional, software services based smartphone could only be&nbsp;achieved in&nbsp;an&nbsp;era of&nbsp;hardware resource abundance. An&nbsp;environment where underlying hardware resources are&nbsp;&mdash; to&nbsp;all intents&nbsp;&mdash; a&nbsp;limitless commodity changes the calculus of&nbsp;software development. It&nbsp;is&nbsp;helpful to&nbsp;consider the Linux operating systems as&nbsp;an&nbsp;exemplar of&nbsp;these changes.

During the period when the _economics of&nbsp;scarcity_ reined the most direct analog to&nbsp;Linux was its precursor the UNIX operating system invented at&nbsp;AT&T's Bell Labs. UNIX was designed to&nbsp;be a&nbsp;general-purpose operating system which could run on&nbsp;many different types of&nbsp;underlying hardware. However, when hardware resources are scare the operating system needs to&nbsp;be&nbsp;customized to&nbsp;be&nbsp;as efficient as&nbsp;possible on&nbsp;each different hardware platform. But tuning UNIX in&nbsp;this way created so&nbsp;much divergence across the UNIX family that it&nbsp;could no&nbsp;longer be&nbsp;considered a&nbsp;single operating system. Applications written to&nbsp;run on&nbsp;one variant of&nbsp;UNIX were not guaranteed to&nbsp;run on&nbsp;any other variant. The UNIX ecosystem never developed or&nbsp;benefited from the same economies of&nbsp;scale witnessed by&nbsp;the IBM&nbsp;PC ecosystem.

Linux on&nbsp;the other hand is&nbsp;an&nbsp;operating system which benefits from the _economics of&nbsp;abundance_. So&nbsp;much computational capacity is&nbsp;now available that some of&nbsp;this capacity can be&nbsp;&laquo;wasted&raquo; by&nbsp;layers of&nbsp;software designed to&nbsp;decouple application developers and users from differences in&nbsp;underlying operating system and hardware platforms. This ability to&nbsp;&laquo;waste&raquo; computing cycles on _decoupling_ means that Linux truly has become a&nbsp;general purpose operating system. From a&nbsp;historic perspective Linux&rsquo;s hardware adaptability is&nbsp;truly astounding. You can now run a&nbsp;single operating system on&nbsp;almost any hardware architecture available; from the smallest Raspberry Pi&nbsp;to&nbsp;the largest IBM Mainframe machine. In&nbsp;general an&nbsp;application written for one Linux distribution will run unchanged on&nbsp;any other. Such adaptability would have been unthinkable in&nbsp;the era of&nbsp;scarce hardware resources.

This Linux examples still relates to&nbsp;an&nbsp;environment where there is&nbsp;a&nbsp;one-to-one relationship between a&nbsp;computer&nbsp;&mdash; hardware&nbsp;&mdash; and the operating system and application software running on&nbsp;it. Applications written for the Linux operating system still only run on&nbsp;Linux and will not run&nbsp;&mdash; without major modification&nbsp;&mdash; on&nbsp;Microsoft&rsquo;s Windows or&nbsp;Apple&rsquo;s&nbsp;OS X&nbsp;operating system. But computing resource abundance has now enabled even this problem to&nbsp;be&nbsp;solved, allowing multiple different operating system and application ecosystems to&nbsp;happily share a&nbsp;common underlying hardware platform.

Part III of&nbsp;this article will examine how the ability to&nbsp;now share abundant hardware resources across many application workloads is&nbsp;transforming computing architectures and ultimately lead to&nbsp;the emergence of&nbsp;cloud computing.