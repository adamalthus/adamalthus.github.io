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
<a href="http://www.adamalthus.com/blog/2013/02/27/economics-and-platform-architecture-ii/" target="_blank">Part 2</a> of&nbsp;this series of&nbsp;articles looked at&nbsp;how transitioning from scarcity to&nbsp;an&nbsp;abundance of&nbsp;fundamental computing resources enabled the historic one-to-one relationship between operating systems, applications and underlying hardware to&nbsp;be&nbsp;broken_._ Part 3 will examine how the ability to&nbsp;decouple hardware and software evolved into a&nbsp;new strategy for managing&nbsp;IT systems&nbsp;&mdash; saving company&rsquo;s millions of&nbsp;dollars in&nbsp;the process&nbsp;&mdash; and laid the foundation for today&rsquo;s cloud computing architectures.<!--more-->

The Mac on&nbsp;which this article was written can run not only Apple&rsquo;s native&nbsp;OS X&nbsp;operating system, but also Microsoft Windows, multiple variants of&nbsp;Linux and&nbsp;&mdash; if&nbsp;needed Oracle&rsquo;s Open Solaris operating system. A&nbsp;modern personal laptop computer has such an&nbsp;abundance of&nbsp;computational capacity that multiple distinct hardware architectures can be _emulated_ in&nbsp;software.

This ability to _virtualize_ the link between hardware and software with little or&nbsp;no&nbsp;performance penalty is&nbsp;a&nbsp;direct benefit of&nbsp;the _economics of&nbsp;abundance_. New layers of _virtualization_ software allow us&nbsp;to&nbsp;run a&nbsp;copy of&nbsp;Microsoft Windows or&nbsp;Linux on&nbsp;a&nbsp;Mac computer alongside the Mac&rsquo;s native operating system with each system sharing the same computational, storage, memory and network resources. This ability to _decouple_ hardware and software provides significant economic benefits.

The ability to&nbsp;run multiple&nbsp;&mdash; but distinct&nbsp;&mdash; software architectures on&nbsp;the same physical hardware allows companies to&nbsp;amortize hardware costs across a&nbsp;wider range of&nbsp;application workloads. _Virtualization_ is&nbsp;interesting and helpful on&nbsp;a&nbsp;laptop, but is&nbsp;truly transformative when applied to&nbsp;multi-million dollar computer server infrastructures.

Under the _economics_ _of&nbsp;scarcity_ a&nbsp;single enterprise software application would typically be&nbsp;tightly coupled to&nbsp;a&nbsp;single hardware platform. Often the underlying hardware would be&nbsp;running at&nbsp;only a&nbsp;small fraction of&nbsp;its available capacity. The ability to&nbsp;run multiple application workloads on&nbsp;the same hardware through _virtualization_ enables&nbsp;IT departments to&nbsp;manage their hardware resources much more efficiently by&nbsp;running them at&nbsp;higher levels of&nbsp;utilization.

The use of _virtualization_ strategies is&nbsp;now standard practice in&nbsp;many&nbsp;&mdash; if&nbsp;not most&nbsp;&mdash; enterprise computing environments. In&nbsp;many cases a&nbsp;few hundred servers running _virtualized_ workloads have replaced 1,000s of&nbsp;servers previously dedicated to&nbsp;individual workloads. Applying this approach has saved many millions of&nbsp;dollars across enterprise&nbsp;IT departments.

At&nbsp;least one company&nbsp;&mdash; VMWare&nbsp;&mdash; became successful by&nbsp;meeting the market demand for virtualization solutions and was perhaps the first child of&nbsp;this new era of&nbsp;resource abundance. VMWare is&nbsp;no-longer the only player. The economic benefits of&nbsp;this approach to&nbsp;software architecture have spawned a&nbsp;diverse and increasingly competitive ecosystem including offerings from Microsoft, Oracle, Citrix and Parallels and the open source based Xen.

The ability to&nbsp;turn the compute, program memory, storage and network resources of&nbsp;many independent servers into a _virtualized_ pool of&nbsp;resources to&nbsp;be&nbsp;allocated as&nbsp;needed by&nbsp;software applications has laid the foundation for emergence of&nbsp;Cloud Computing.

Part 4 of&nbsp;this series will look at&nbsp;how the commoditization of&nbsp;computing resources and the ability for them to&nbsp;be&nbsp;managed and allocated on&nbsp;demand forms the foundation of&nbsp;new cloud computing architectures and a&nbsp;radical change in&nbsp;the way software applications and services are created, managed and consumed.