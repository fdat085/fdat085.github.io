---
layout: student
sidebar: true
title: DRAM security issues
author: Alirad Malek
room: EL41
date: 2017/05/23
time: 15:30-17:30
abstract: "Thanks to advances in semiconductor technology, DRAM cells have scaled down to feature sizes of a few nanometers, bringing great opportunities and new challenges to the design of future memory systems. On the one hand, we can have higher memory capacity on the same silicon area, on the other hand shrinking size of transistors and capacitors increases variability and affects the reliability of DRAM chips. One of the fault models which is highly associated with technology scaling in DRAMs in disturbance errors. In 2014, an empirical study of off-the-shelf DRAMs revealed that by repeatedly accessing a row within DRAM, it is possible to force disturbance errors in significant numbers of cells. This phenomena which later became known as RowHammer problem, was initially perceived as a reliability issue. However, in a short while it became evident that the RowHammer effect could possibly be a major security vulnerability. Over the last couple of years, many researchers have proposed exploiting RowHammer, in order to gain kernel privilege on real systems, takeover a Virtual machine in shared environment or using a malicious mobile application to gain root access.  In this short survey, we will have an overview of RowHammer problem, how it could be exploited as a security vulnerability and what are the current counter-measures against it."
intropapers:
- title: "Mutlu, Onur. \"The RowHammer Problem and Other Issues We May Face as Memory Becomes Denser.\""
  url: "https://arxiv.org/pdf/1703.00626.pdf"
advancedpapers:
- title: "Kim, Yoongu, et al. \"Flipping bits in memory without accessing them: An experimental study of DRAM disturbance errors.\" ACM SIGARCH Computer Architecture News. Vol. 42. No. 3. IEEE Press, 2014"
  url: "http://dl.acm.org/citation.cfm?id=2665726"
- title: "van der Veen, Victor, et al. \"Drammer: Deterministic rowhammer attacks on mobile platforms.\" Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications Security. ACM, 2016"
  url: "http://dl.acm.org/citation.cfm?id=2978406"
---

