---
layout: student
sidebar: true
title: Authenticated Encryption
author: Elena Pagnin
room: EL41
date: 2017/05/17
time: 10:00-12:00
pdf: "elena.pdf"
abstract: "Encryption (Enc) is the cryptographic primitive to achieve data con- fidentiality. Intuitively, encryption schemes enable Alice and Bob to communicate while Eve cannot understand the content of their conversation. Despite its ?hiding power?, encryption does not directly guarantee message integrity, that is, no one can prevent Eve from modifying Alice?s encrypted data in such a way that Bob decrypts a message different from the original one. The cryptographic primitive to guarantee that the data in transit from Alice to Bob has not been modified by Eve, is called Message Authentication Codes (MAC). In this short paper, we discuss the combination of Enc and MAC: Authenticated Encryption (AE) and present a motivating example for this new cryptographic tool. Moreover, we provide a simplified overview of the algorithms that define AE schemes and compare the three possible ways to combine Enc and MAC. We conclude presenting an overview of the evolution of AE schemes and describing the current state of the CAESAR competition, which aims at defining a candidate for the first standard AE scheme (essentially the authenticated encryption equivalent of AES or SHA-3)."
intropapers:
- title: "M. Bellare, C. Namprempre: Authenticated Encryption: Relations among Notions and Analysis of the Generic Composition Paradigm (ASIACRYPT 2000)"
  url: "https://link.springer.com/chapter/10.1007/3-540-44448-3_41"
advancedpapers:
- title: "D. Maimut, R. Reyhanitabar: Authenticated Encryption: Toward Next-Generation Algorithms (S&P 2014)"
  url: "http://ieeexplore.ieee.org/document/6798548/"
- title: "F. Abed, C. Forler, and S. Lucks: General Classification of the Authenticated Encryption Schemes for the CAESAR Competition (Computer Science Review 2016)"
  url: "http://www.sciencedirect.com/science/article/pii/S1574013715300290"
---

