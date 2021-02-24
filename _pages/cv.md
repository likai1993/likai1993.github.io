---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======
* PhD in Electrical and Computer Engineering, Syracuse University, 2022 (expected)
* B.E in Electrical Engineering, Nanjing University of Arenautics and Astronautics, 2015

Research Experience
======

* Spring 2018 - Spring 2021: Research Assistant
  * Syracuse University
  * Identified a severe vulnerability in Ethereum RPC API that leads to DoS attack on the public RPC services. The API (eth_call) allows an attacker to execute any resource-consuming functions. A novel measurement method is proposed to uncover the load balance's policies adopted by the RPC services and facilitate the attacker to mount the DoS attack.
  * Leveraging the public Blockchain to verify the consistency of distributed cloud storage, proposed and implemented an storage consistency auditing protocol in both Bitcoin and Ethereum.
  * Hijacking LLVM on the backend level (llc), adding TSX features, e.g., xbegin, xend when compile X86 binaries, the purpose is partitioning the binary into multiple execution unit by TSX.

Work Experience
======
* 06/2020 - 08/2020: Research Intern
  * IBM Research
  * The internship project aims to improve the buffer hit ratio in popular databases by applying Deep Reinforcement Learning (DRL). My role involves:
    1) reading PostgreSQL source code and learn how the buffer management module works.
    2) drive standard database benchmark queries (such as TPCC/TPCH) and collect the buffer access trace.
    3) profile the buffer module regarding CPU utilization when handling the above queries.
    4) develop DRL in the context of database buffer environment and compare its performance with classic buffer eviction algorithms (e.g., LRU, LFU, MRU, Random).
* 08/2015 - 08/2017: Software Engineer
  * ZTE Corpration
  * Duties included: Develop CDN, research on Multimedia streaming protocols conversions.
  
Skills
======
* Programming Language: C, C++, Java, Python, Lua, Shell, Solidity
* Compiler: gcc, g++, LLVM, clang
* Blockchain: Go-Ethereum/Parity (Read source code), Bitcoin, Multi-Chain.
* CDN: Nginx, Tomcat (Apache)

Awards
===
* NDSS 2021 Student Travel Grant
