---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true

---

{% include base_path %}

Nikita Sehrawat
=====

Description (from the development team): Poliastro is an open-source Python library for interactive Astrodynamics and Orbital Mechanics, with a focus on ease of use, speed, and quick visualization. It provides a simple and intuitive API and handles physical quantities with units.

Contribution: I had wished to contribute a part of my Master’s research code to the software to expand its use from the two-body problem to the three-body problem. I wrote programs to simulate the Circular Restricted Three Boby Problem and algorithms to compute its equilibrium and periodic solutions.

Current Status (9th January 2023): The functionalities that I intended to be added to a new release of the software can be found here. A part of the code has been added to the source code (1, 2, 3, 4). Due to the organizational changes in the core development team, the updates have been delayed.

Learnings: The most important thing I learned was the importance of separating “the science” and data structures to access the functions that describe the science. This also enabled me to build unit tests for the low-level functions, which simulate the science, to validate them against values in the literature or a property. In addition, I gained experience contributing to open-source software, which has helped me realize how to create meaningful pull requests and about various CI/CD tools to maintain the integrity of the code.

Technologies used: Python, Github, Linux, Command Line Interface

Concepts learned: Dynamics Modeling and Targeting desired Dynamical Structures, Open Source Software, CI/CD Tools, Unit Tests 

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}