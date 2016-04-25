---
id: 710
title: Economics and Platform Architecture (Part 2)
date: 2013-02-27T21:22:29+00:00
author: Jonathan
layout: post
guid: http://www.adamalthus.com/?p=710
permalink: /blog/2013/02/27/economics-and-platform-architecture-ii/
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
In this series of articles outlined the impact that the _economics of scarcity_ has had on both software architectures and the structure of the computer industry over the last forty years. Part II of the article will discuss the transition from the _economics of scarcity_ to the _economics of abundance_ and how profoundly that has altered - and continues to alter - the computing landscape.<!--excerpt-->

The introduction of the IBM PC in the early 80's laid the foundation for a transformation in the economic model of the computing industry. IBM broke with its traditional model when it outsourced the supply of the computer processor and operating system for its Personal Computer (PC.) Little did IBM know that this single decision would transform an industry. The decision to source processors from Intel and an operating system from Microsoft and to not bind both these suppliers to exclusive supply agreements created the opportunity to build a 3rd party PC industry based IBM's generic blueprint. The market for PCs grew and other players such as Compaq created competitive alternatives to IBM. The highly competitive dynamics of the PC industry based on the _open_ hardware blueprint created by IBM had very direct consequences.

Rampant competition within the nascent PC industry kept prices under control and yet each vendor's hardware ran the same DOS - and subsequently Windows - operating system licensed from Microsoft. This in turn meant that every PC sold became an available 'socket' for a growing ecosystem of application software developers. The same application would run without modification on every model of PC. The combination of these factors lead to exponential growth in the sales of PCs and this growth lead to vast economies of scale in the production of microprocessors, disk storage and memory chips. All of this was enabled by dramatic improvements in hardware fabrication technology - largely following Gordon Moore's law. As a result we have witnessed an approximate doubling in computational capacity, program memory and disk storage capacity every 12-18 months continuously for over forty years.

In the early 2000's the computing industry reached a tipping point where hardware capacities started to outstrip the demands of application software. The industry was about to transition from _economics of scarcity_ to the _economics of abundance._ The impacts of this transition were - and continue to be - profound. The _economics of abundance_ mean that hardware resources can be viewed as essentially unlimited. It is interesting to note that it was at this time that Intel entered the software business. It did so because it felt the need to incubate new software technologies which would utilize the full capacity of the chips it was producing. If processor capacity far outpaces the demands of Microsoft Windows, Office and a Web Browser then consumers do not need to upgrade their machines that often - and that is bad for Intel's business.

It is hard to understate the impact of this transition from scarce to abundant computing resources. The iPhone is a child of this transition. The economics of producing a completely integrated, highly functional, software services based smartphone could only be achieved in an era of hardware resource abundance. An environment where underlying hardware resources are - to all intents - a limitless commodity changes the calculus of software development. It is helpful to consider the Linux operating systems as an exemplar of these changes.

During the period when the _economics of scarcity_ reined the most direct analog to Linux was its precursor the UNIX operating system invented at AT&T's Bell Labs. UNIX was designed to be a general-purpose operating system which could run on many different types of underlying hardware. However, when hardware resources are scare the operating system needs to be customized to be as efficient as possible on each different hardware platform. But tuning UNIX in this way created so much divergence across the UNIX family that it could no longer be considered a single operating system. Applications written to run on one variant of UNIX were not guaranteed to run on any other variant. The UNIX ecosystem never developed or benefited from the same economies of scale witnessed by the IBM PC ecosystem.

Linux on the other hand is an operating system which benefits from the _economics of abundance_. So much computational capacity is now available that some of this capacity can be "wasted" by layers of software designed to decouple application developers and users from differences in underlying operating system and hardware platforms. This ability to "waste" computing cycles on _decoupling_ means that Linux truly has become a general purpose operating system. From a historic perspective Linux's hardware adaptability is truly astounding. You can now run a single operating system on almost any hardware architecture available; from the smallest Raspberry Pi to the largest IBM Mainframe machine. In general an application written for one Linux distribution will run unchanged on any other. Such adaptability would have been unthinkable in the era of scarce hardware resources.

This Linux examples still relates to an environment where there is a one-to-one relationship between a computer - hardware - and the operating system and application software running on it. Applications written for the Linux operating system still only run on Linux and will not run - without major modification - on Microsoft's Windows or Apple's OS X operating system. But computing resource abundance has now enabled even this problem to be solved, allowing multiple different operating system and application ecosystems to happily share a common underlying hardware platform.

Part III of this article will examine how the ability to now share abundant hardware resources across many application workloads is transforming computing architectures and ultimately lead to the emergence of cloud computing.
