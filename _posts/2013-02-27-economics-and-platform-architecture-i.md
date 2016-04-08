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
The underlying economics of&nbsp;computing resources have always had a&nbsp;profound impact on&nbsp;development of&nbsp;computing architecture and in-turn the structure of&nbsp;the computer industry. In&nbsp;this regard the emergence of&nbsp;cloud computing is&nbsp;no&nbsp;different. Cloud computing has emerges as&nbsp;the product of&nbsp;a&nbsp;fundamental transition in&nbsp;the underlying economics of&nbsp;computing resources and&nbsp;&mdash; as&nbsp;in&nbsp;the past&nbsp;&mdash; this economic transition will drive profound changes in&nbsp;the structure of&nbsp;the computing industry. The nature of&nbsp;this change can best be&nbsp;described as&nbsp;a&nbsp;transition from the _economics of_ _scarcity_ to __the _economics of&nbsp;abundance._<!--more-->

Until relatively recently all fundamental computing resources were considered scare. Processors had limited computational capacity and were constantly being outstripped by&nbsp;the demands of&nbsp;software. Limited and expensive computer program memory and disk storage put severe constraints on&nbsp;the size and complexity of&nbsp;computer applications. The earliest network connections could only transmit data slowly and at&nbsp;very high cost. The cost and limited capacity of&nbsp;these foundational components of&nbsp;computing infrastructure&nbsp;&mdash; computation, memory, storage and network bandwidth&nbsp;&mdash; placed severe limits on&nbsp;the complexity of&nbsp;operating systems and the layers of&nbsp;software which ran on&nbsp;top of&nbsp;them.

In&nbsp;a&nbsp;world of&nbsp;highly constrained hardware resources software needs written for specific hardware architectures and configurations. In&nbsp;the past this _tight coupling_ between software and hardware was essential to&nbsp;extract every last ounce of&nbsp;performance from very expensive systems. IBM produced highly optimized operating systems dedicated to&nbsp;specific mainframe hardware, memory and storage architectures. In&nbsp;his seminal book _<a href="http://www.amazon.com/The-Soul-A-New-Machine/dp/0316491977/ref=sr_1_1?ie=UTF8&qid=1361918918&sr=8-1&keywords=soul+of+the+new+machine&tag=adamalthus-20 " target="_blank" rel="nofollow">The Soul of&nbsp;the New Machine</a>,_ Tracy Kidder describes the very intimate relationship between the development of&nbsp;hardware and software for one of&nbsp;the earliest DataGeneral mini-computers. Digital Equipment Corporation did the same for its each generation of&nbsp;its PDP and VAX mini-computers. Even later generation companies such as&nbsp;Sun Microsystems followed the same approach with its Solaris operating system to&nbsp;extract every last ounce of&nbsp;performance from their workstation and server products.

The early success of&nbsp;Sun Microsystems in&nbsp;markets for engineering workstations and high performance servers for the financial services industry show just how successful this &laquo;Tight-coupling&raquo; of&nbsp;software and hardware was as&nbsp;an&nbsp;economic model in&nbsp;the computer industry. While the demands of&nbsp;software developers and their algorithms outstripped the capacity of&nbsp;hardware resources this tightly coupled model would hold sway. For the last forty years the _economics of&nbsp;scarcity_ have defined both platform architecture and the very structure of&nbsp;the industry itself.

Customers have always been willing to&nbsp;pay a&nbsp;premium for software and hardware solutions that could optimize scare resources and keep operating costs to&nbsp;a&nbsp;minimum. Oracle, Cisco and EMC are but three companies whose fundamental value proposition was based on&nbsp;the _economics of&nbsp;scarcity_. Each of&nbsp;these companies created value by&nbsp;being best in&nbsp;class in&nbsp;helping customers optimize and manage network bandwidth, database performance and scale and disk storage capacity respectively. They could each charge a&nbsp;premium price for their products and services because the costs of&nbsp;the underlying infrastructure resources were so&nbsp;high that marginal improvements in&nbsp;resource optimization lead to&nbsp;significantly positive outcomes in&nbsp;cost control.

The _economics of&nbsp;scarcity_ have had a&nbsp;profound effects on&nbsp;evolution of&nbsp;computing architecture. Operating systems were tuned for specific hardware platforms. Databases were tuned for specific operating systems environments. Application performance was optimized by&nbsp;targeting specific database technologies. It&nbsp;is&nbsp;interesting to&nbsp;footnote that the fact that we&nbsp;have historically placed application code inside databases&nbsp;&mdash; in&nbsp;the form of 'Stored Procedures' - is&nbsp;a&nbsp;direct result of&nbsp;the need to&nbsp;optimize for scare resources rather than as&nbsp;an&nbsp;elegant architectural design decision. Finally, all of&nbsp;this underlying application architecture was then accessed by&nbsp;tightly coupled client interfaces using highly optimized network access protocols. This model of&nbsp;the fully&nbsp;&mdash; vertically&nbsp;&mdash; integrated application architecture dominates today&rsquo;s enterprise computing landscape and does so&nbsp;as a&nbsp;direct result of&nbsp;the _economics of&nbsp;scarcity_.

The vertically integrated application model may have helped optimize for very scarce and expensive hardware resources but it&nbsp;also lead to&nbsp;significant future costs through fragility and lack of&nbsp;both flexibility and interoperability. Vertically integrated application architectures are very rigid structures. The tight-coupling between layers makes it&nbsp;extremely difficult, costly and often impossible to&nbsp;replace components of&nbsp;the architecture with competing offerings. Migrating an&nbsp;SAP instance originally implemented on&nbsp;Oracle over to&nbsp;Microsoft&rsquo;s competing SQL Server product is&nbsp;a&nbsp;non-trivial and expensive proposition. Swapping out IBM&rsquo;s WebSphere middleware product for a&nbsp;competitor such as&nbsp;JBOSS or&nbsp;Weblogic is&nbsp;a&nbsp;task only the most fearless of&nbsp;IT organizations would take on.

The built in&nbsp;switching costs of&nbsp;such highly optimized application architectures had the effect of&nbsp;cementing the early success of&nbsp;today&rsquo;s leading enterprise software players. These switching costs acted as&nbsp;an&nbsp;accelerant to&nbsp;local network effects within individual vendor ecosystems. IT&nbsp;departments are typically organized around these ecosystems i.e. the&nbsp;IT organizational model becomes vertically integrated as&nbsp;a&nbsp;response to&nbsp;the application architectures they support: The Oracle center of&nbsp;excellence only supports Oracle based applications. The Microsoft center of&nbsp;excellence only Microsoft platforms etc. Unfortunately most organizations are dealing with the ugly reality of&nbsp;the cost structures and lack of&nbsp;flexibility that this approach creates. An&nbsp;approach to&nbsp;optimizing scare computing resources has ended up&nbsp;creating higher acquisition costs, very high switching costs, much higher systems integration costs, dramatically reduced application adaptability and centralization of&nbsp;industry power in&nbsp;the hands of&nbsp;a&nbsp;few select vendors.

Part&nbsp;II of&nbsp;this article will look at&nbsp;how a&nbsp;transition from the _economics of&nbsp;scarcity_ to&nbsp;the _economics of&nbsp;abundance_ in&nbsp;the early 2000's lead to&nbsp;a&nbsp;transformation in&nbsp;platform architectures and lead the foundation for the emergence of&nbsp;cloud computing.