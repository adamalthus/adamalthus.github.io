---
id: 716
title: Economics and Platform Architecture (Part 3)
date: 2013-02-28T23:47:53+00:00
author: Jonathan
layout: post
guid: http://www.adamalthus.com/?p=716
permalink: /blog/2013/02/28/economics-and-platform-architecture-part-3/
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
  - Strategy
---
<a href="http://www.adamalthus.com/blog/2013/02/27/economics-and-platform-architecture-ii/" target="_blank">Part 2</a> of this series of articles looked at how transitioning from scarcity to an abundance of fundamental computing resources enabled the historic one-to-one relationship between operating systems, applications and underlying hardware to be broken_._ Part 3 will examine how the ability to decouple hardware and software evolved into a new strategy for managing IT systems - saving company's millions of dollars in the process - and laid the foundation for today's cloud computing architectures.<!--more-->

The Mac on which this article was written can run not only Apple's native OS X operating system, but also Microsoft Windows, multiple variants of Linux and - if needed Oracle's Open Solaris operating system. A modern personal laptop computer has such an abundance of computational capacity that multiple distinct hardware architectures can be _emulated_ in software.

This ability to _virtualize_ the link between hardware and software with little or no performance penalty is a direct benefit of the _economics of abundance_. New layers of _virtualization_ software allow us to run a copy of Microsoft Windows or Linux on a Mac computer alongside the Mac's native operating system with each system sharing the same computational, storage, memory and network resources. This ability to _decouple_ hardware and software provides significant economic benefits.

The ability to run multiple - but distinct - software architectures on the same physical hardware allows companies to amortize hardware costs across a wider range of application workloads. _Virtualization_ is interesting and helpful on a laptop, but is truly transformative when applied to multi-million dollar computer server infrastructures.

Under the _economics_ _of scarcity_ a single enterprise software application would typically be tightly coupled to a single hardware platform. Often the underlying hardware would be running at only a small fraction of its available capacity. The ability to run multiple application workloads on the same hardware through _virtualization_ enables IT departments to manage their hardware resources much more efficiently by running them at higher levels of utilization.

The use of _virtualization_ strategies is now standard practice in many - if not most - enterprise computing environments. In many cases a few hundred servers running _virtualized_ workloads have replaced 1,000s of servers previously dedicated to individual workloads. Applying this approach has saved many millions of dollars across enterprise IT departments.

At least one company - VMWare - became successful by meeting the market demand for virtualization solutions and was perhaps the first child of this new era of resource abundance. VMWare is no-longer the only player. The economic benefits of this approach to software architecture have spawned a diverse and increasingly competitive ecosystem including offerings from Microsoft, Oracle, Citrix and Parallels and the open source based Xen.

The ability to turn the compute, program memory, storage and network resources of many independent servers into a _virtualized_ pool of resources to be allocated as needed by software applications has laid the foundation for emergence of Cloud Computing.

Part 4 of this series will look at how the commoditization of computing resources and the ability for them to be managed and allocated on demand forms the foundation of new cloud computing architectures and a radical change in the way software applications and services are created, managed and consumed.
