---
id: 706
title: Economics and Platform Architecture (Part 1)
date: 2013-02-27T01:05:37+00:00
author: Jonathan
layout: post
guid: http://www.adamalthus.com/?p=706
permalink: /blog/2013/02/27/economics-and-platform-architecture-i/
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
  - Policy
  - SAP
  - Strategy
  - Uncategorized
---
The underlying economics of computing resources have always had a profound impact on development of computing architecture and in-turn the structure of the computer industry. In this regard the emergence of cloud computing is no different. Cloud computing has emerges as the product of a fundamental transition in the underlying economics of computing resources and - as in the past - this economic transition will drive profound changes in the structure of the computing industry. The nature of this change can best be described as a transition from the _economics of_ _scarcity_ to __the _economics of abundance._<!--more-->

Until relatively recently all fundamental computing resources were considered scare. Processors had limited computational capacity and were constantly being outstripped by the demands of software. Limited and expensive computer program memory and disk storage put severe constraints on the size and complexity of computer applications. The earliest network connections could only transmit data slowly and at very high cost. The cost and limited capacity of these foundational components of computing infrastructure - computation, memory, storage and network bandwidth - placed severe limits on the complexity of operating systems and the layers of software which ran on top of them.

In a world of highly constrained hardware resources software needs written for specific hardware architectures and configurations. In the past this _tight coupling_ between software and hardware was essential to extract every last ounce of performance from very expensive systems. IBM produced highly optimized operating systems dedicated to specific mainframe hardware, memory and storage architectures. In his seminal book _<a href="http://www.amazon.com/The-Soul-A-New-Machine/dp/0316491977/ref=sr_1_1?ie=UTF8&qid=1361918918&sr=8-1&keywords=soul+of+the+new+machine&tag=adamalthus-20 " target="_blank" rel="nofollow">The Soul of the New Machine</a>,_ Tracy Kidder describes the very intimate relationship between the development of hardware and software for one of the earliest DataGeneral mini-computers. Digital Equipment Corporation did the same for its each generation of its PDP and VAX mini-computers. Even later generation companies such as Sun Microsystems followed the same approach with its Solaris operating system to extract every last ounce of performance from their workstation and server products.

The early success of Sun Microsystems in markets for engineering workstations and high performance servers for the financial services industry show just how successful this "Tight-coupling" of software and hardware was as an economic model in the computer industry. While the demands of software developers and their algorithms outstripped the capacity of hardware resources this tightly coupled model would hold sway. For the last forty years the _economics of scarcity_ have defined both platform architecture and the very structure of the industry itself.

Customers have always been willing to pay a premium for software and hardware solutions that could optimize scare resources and keep operating costs to a minimum. Oracle, Cisco and EMC are but three companies whose fundamental value proposition was based on the _economics of scarcity_. Each of these companies created value by being best in class in helping customers optimize and manage network bandwidth, database performance and scale and disk storage capacity respectively. They could each charge a premium price for their products and services because the costs of the underlying infrastructure resources were so high that marginal improvements in resource optimization lead to significantly positive outcomes in cost control.

The _economics of scarcity_ have had a profound effects on evolution of computing architecture. Operating systems were tuned for specific hardware platforms. Databases were tuned for specific operating systems environments. Application performance was optimized by targeting specific database technologies. It is interesting to footnote that the fact that we have historically placed application code inside databases - in the form of 'Stored Procedures' - is a direct result of the need to optimize for scare resources rather than as an elegant architectural design decision. Finally, all of this underlying application architecture was then accessed by tightly coupled client interfaces using highly optimized network access protocols. This model of the fully - vertically - integrated application architecture dominates today's enterprise computing landscape and does so as a direct result of the _economics of scarcity_.

The vertically integrated application model may have helped optimize for very scarce and expensive hardware resources but it also lead to significant future costs through fragility and lack of both flexibility and interoperability. Vertically integrated application architectures are very rigid structures. The tight-coupling between layers makes it extremely difficult, costly and often impossible to replace components of the architecture with competing offerings. Migrating an SAP instance originally implemented on Oracle over to Microsoft's competing SQL Server product is a non-trivial and expensive proposition. Swapping out IBM's WebSphere middleware product for a competitor such as JBOSS or Weblogic is a task only the most fearless of IT organizations would take on.

The built in switching costs of such highly optimized application architectures had the effect of cementing the early success of today's leading enterprise software players. These switching costs acted as an accelerant to local network effects within individual vendor ecosystems. IT departments are typically organized around these ecosystems i.e. the IT organizational model becomes vertically integrated as a response to the application architectures they support: The Oracle center of excellence only supports Oracle based applications. The Microsoft center of excellence only Microsoft platforms etc. Unfortunately most organizations are dealing with the ugly reality of the cost structures and lack of flexibility that this approach creates. An approach to optimizing scare computing resources has ended up creating higher acquisition costs, very high switching costs, much higher systems integration costs, dramatically reduced application adaptability and centralization of industry power in the hands of a few select vendors.

Part II of this article will look at how a transition from the _economics of scarcity_ to the _economics of abundance_ in the early 2000's lead to a transformation in platform architectures and lead the foundation for the emergence of cloud computing.