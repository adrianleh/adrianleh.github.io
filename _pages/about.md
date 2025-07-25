---
layout: archive
title: ""
excerpt: "About me"
permalink: /
author_profile: true
redirect_from:
  - /resume
  - /about
  - /about.html
  - /cv
  - /cv.html
---

Hi!
======
I'm a PhD candidate at the University of Chicago. My research develops tools and techniques for improving software reliability challenges applicable to high-assurance systems, specifically but not limited to Quantum Computing and CUDA.
**I automatically parallelized a domain-specific language for scientific computing with CUDA and unified memory.**
After that, I verified the ZX calculus and am building automation on top of this effort. See my projects below for more details.

Before my PhD, I worked as a software engineer in infrastructure at LogMeIn, building scalable and reliable systems for a private cloud with >4000 VMs spanning three continents. During my PhD, I’ve kept an eye on improving the maintainability and automation of open-source formal verification projects. I built a linter to help manage these projects at scale and integrated CI pipelines to ensure reliability and make managing pull requests easier.

I thrive at the intersection of engineering and problem-solving. I want to build and take ownership of high-quality software but also streamline the development.

I’m excited to be start solving complex problems at scale at Optiver as a Software Engineer in 10/25!

{% include base_path %}

Education
======
* B.Sc. in Computer Science, Karlsruhe Institute of Technology, Germany, 2019
* MS in Computer Science, The University of Chicago, USA, 2023
* Ph.D. in Computer Science, The University of Chicago, USA, 09/2025 (expected)
  * Advised by [Robert Rand](https://rand.cs.uchicago.edu) and [John Reppy](https://people.cs.uchicago.edu/~jhr/)

Languages
======
* German, English (bilingual)

Currently working on
======

* Formalizing ZX Calculus to create a verified ZX calculus optimizer
  * Co-Leading with Ben Caldwell under guidance of Robert Rand & John Reppy
  * [This work won a grant from the Air Force Office of Scientifc Research (AFOSR)](https://cs.uchicago.edu/news/assistant-professor-robert-rand-receives-air-force-young-investigator-grant/)
  * In submission
* Proof automation using E-Graph systems
  * What if proof search was smart and avoided re-computation? Right now, proof search tools built into proof assistants can solve basic problems. But many times in the real world, we work with complex, yet somewhat repetitive proof problems. This project is built to fill this gap: Provide a smart proof search for concrete, real problems to make proof engineering less heavy weight. Can we use it to solve interesting domain-specific applications?
  * Submission/arXiv expected in the coming months
* Rocq Linter "Chickenscratch"
  * Rocq, formerly Coq, is a great tool for verification but the proof engineering tools are lacking. Pull requests are hard to review, APIs hard to use, and it's hard to join other projects, because there are a lot of implicit stylistic and completeness rules the engineer needs to follow. I'm working on building a linter specific to Rocq and proof to make it easier to ship quality proof projects.
  * Release expected late 05/2025


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %} 
    {% include archive-single-talk-cv.html %} 
  {% endfor %}
  </ul>


Other Research Experience
======
* Sep 2020 - Today: Graduate Student Researcher
  * University of Chicago
  * Sep 2020 - Sep 2021: Worked on NSF Grant to build a CUDA backend to a DSL ''[Diderot](http://diderot-language.cs.uchicago.edu/)'' for data visualization and analysis in StandardML under advisement of John Reppy.
  * Jan 2022- Jun 2022: Part of NSF expedition "EPiQC" to formalize the ZX calculus 

* Oct 2018 - Mar 2019: Research Project
  * Karsruhe Institute of Technology
  * Built a compiler for a subset of Java with custom backend and optimization framework 

* Oct 2017 - Mar 2018: Research Project
  * Karsruhe Institute of Technology
  * Prototyped and analyzed BLE beacon based indoor navigation system based on multilateration as part of practice in software engineering program at Karlsruhe Institute of Technology

Work experience
======

* Jun 2022 - Sep 2022: Research Intern
  * Microsoft Quantum, Remote, US
  * Created quantum algorithm samples (Entanglement Swapping, Solving Sudoku with Grover's Search, and Numerical Integration using Quantum Amplitude Estimation) using Q#, Qiskit, and the Microsoft Quantum Development Kit for the Azure Quantum platform.

* Dec 2019 - Aug 2020: Assosicate Software Engineer
  * LogMeIn, Karlsruhe, Germany
  * Built a system to mass deploy files, scripts to virtual machines in a private cloud. For this I worked in a cross functional Software Engineering and DevOps team with members on multiple continents managing a global private cloud with thousands of active virtual machines. Built out the high availability deployment on a container infrastructure.  Built a Terraform provider for private cloud. Was repeatedly recognized for outstanding work by my superior. Conducted multiple technical interviews
  * Technologies used: Java, Spring, (Postgres)SQL, Docker, Kubernetes, Go, Terraform, Ansible

* Sep 2018 - Nov 2019: Software Engineering Intern (part-time)
  * LogMeIn, Karlsruhe, Germany
  * Working on internal tools for developing products used by millions everyday. Won Team Quality Award. Built end-to-end testing framework. Built Terraform provider prototype for private cloud
  * Technologies used: Java, Spring, Docker, Go, Terraform, Selenium

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Misc. Projects
======

* I created a bunch of study guides during undergrad. So if you are a KIT computer science student please find them on my [GitHub](https://github.com/adrianleh?tab=repositories&q=revision&type=public&language=&sort=). (Note: Some of them are in German language)

* I [benchmarked](https://github.com/adrianleh/quantum-compiler-benchmark) a bunch of quantum compilers to see if juxtaposition with other compilers would improve performance

* [Here](https://github.com/adrianleh/ntfs-paper) is an overview of NTFS I wrote for a seminar

* There's more on my [GitHub](https://github.com/adrianleh)

Service and leadership
======
* Jan 2023 POPL Student volunteer
  * POPL Conference, Boston, MA, USA

* May 2017 - Jun 2018 Hack & Söhne Hackathon Organization, Sponsorship Management
  * Hack & Söhne, Karlsruhe, Germany
  * Organizing events such as the [OpenCodes Hackathon](https://opencodes.io) and the [Hacktival](https://hacktival.io), which themselves were Germany's biggest student run hackathons in 2018 and 2019. I was invloved in all aspects of organizing these events, from hands-on work at the event, to financial planning. My main focus though lay on sponsorship acquisition and management to make sure the event's funding is secured.

* Jun 2019 - Jun 2019 Joint Chairman Hack & Söhne, talKIT - The technology symposium 
  * Hack & Söhne, Karlsruhe, Germany
  * talKIT - The technology symposium  is a student organisation that annually organizes the largest European student technology symposium and is the parent organization of Hack & Söhne. In my role I got to represent Hack & Söhne both internally and externally. During my time two sucessful events were run and the stability of the organization was ensured. 

* May 2016 - Nov 2017 Webmaster at Local Sports Club
  * TFC Ludwigshafen, Ludwigshafen am Rhein, Germany
