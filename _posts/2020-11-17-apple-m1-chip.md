---
layout: post
title: "Apple M1 chip"
date: 2020-11-17
excerpt: "The new Apple M1 chip has recently been launched, but what's so different about it?"
tags: [Apple, CPU]
feature: https://user-images.githubusercontent.com/36279762/101106251-851a9880-3584-11eb-911a-f17c97411223.png
comments: true
---
The new Apple M1 chip has recently come to light with the launch of the 2020 13-inch Macbook Pro, MacBook Air, and Mac mini models that all come with the M1 chip. But why is everyone buzzing about this new chip? It's because since 2006, Apple has been using Intel processors to power their line of Mac computers. This transistion isn't the first time, but with benchmarks already being released, we can see that the M1 chip Mac models are blowing Intel version out of the water. Erik Engheim's article ["Why Is Apple's M1 Chip So Fast?"](https://debugger.medium.com/why-is-apples-m1-chip-so-fast-3262b158cba2) expertly explains the reasons why the M1 chip is so fast to readers who aren't too familiar with computer archtecture and hardware in general. The big reason that the M1 chips are so fast is because of its' heterogeneous multi-core design. Instead of Intel or AMD's approach to multi-core where all cores are homogenous, or identical, the M1 chip has multiple cores that do specialized tasks. Obviously since his article is geared towards the broad audience, Engheim doesn't go too in-depth with how much of a performance boost this design gives. For more information on that, UCSD's CSE department had published the paper *[Single-ISA Heterogeneous Multi-Core Architectures for Multithreaded Workload Performance](https://passat.crhc.illinois.edu/multicore_isca04.pdf)* on this exact topic more than 15 years ago. This research paper details the reasons why there is a performance gap between the two designs and shows the testing behind it. I recommend this paper to anyone interested in hardware design and computer architecture.
