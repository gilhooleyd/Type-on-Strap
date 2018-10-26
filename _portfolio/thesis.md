---
layout: post
title: Verified/Secure Boot - Formal Verification of Hardware and Software
feature-img: "assets/img/portfolio/Vboot.png"
img: "assets/img/portfolio/Vboot.png"
date: 20 October 2018
tags: [Portfolio]
---

This is my senior thesis for Princeton University.
It won the [Hisashi Kobayashi Award](http://ee.princeton.edu/news/class-2017-celebrated-ee-department-awards-ceremony) for the "Best Thesis in the Field of Computing".
The full PDF is [available here]({{ site.url }}/assets/data/thesis.pdf)
and the code is
[available on github](https://github.com/gilhooleyd/CBMC-Vboot).

This project investigates the use of a new
Instruction Level Abstraction (ILA) framework for Formal Verification
by applying the framework to Google's Verified Boot.
The ILA framework allows a programmer to create provably correct
models of hardware at the instruction level.
These hardware models can be verified against C and Verilog.
For this project, an ILA model of a TPM was created and inserted
into the Verified Boot codebase. CBMC was then used to formally
prove data and flow properties across hardware and software.

