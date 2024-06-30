---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in University of Chinese Academic of Science *Sept. 2021-Jan. 2025*
* B.S. in Nanjing University of Posts and Telecommunications *Sept. 2017-July. 2021*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Patents
======
* Container migration methods, systems, and computer-readable storage media(Chinese Patent)
  * Wenhao Wang, Zhaoyang Geng, Xiangyi Xu, Yier Jin

Project experience
======
* Security Container for Virtual Machine Level Trusted Execution Environment *Agu. 2023-Feb. 2024*
  * Build a Kata confidential container environment
  * Implement live migration of confidential containers in AMD SEV environment using remote authentication
  * Add ID to Virtio driver to recognize container
  * Add support for device state migration in CRIU using kernel modules
  * Test the migration system using MySQL and Sysbench

* New network architecture and key technologies supported by endogenous security *Mar. 2023-Jul. 2023*
  * Design TRRP trusted routing protocol
  * Using trusted routing protocols to defend against route hijacking attacks
  * Add trusted network identifiers for packet tracing
  * Build Apache, Redis in memory databases, FTP, SNMP and other services for evaluation and testing
  * Responsible for server installation, configuration, debugging, security management, vulnerability repair, etc

* Two party genetic data privacy calculation project based on SGX *Nov. 2021-Jan. 2022*
  * Analysising the genome evolution of COVID-19 through SGX trusted execution environment
  * Constructing a privacy computing scheme for gene data based on Graphene-SGX
  * Use SGX to complete remote authentication between two parties
  * Using Python to Perform Multiple Sequence Alignment of Genes and Generate NJ Trees

* Classroom efficiency detection system based on facial recognition *Mar. 2021-Jun. 2021*
  * Build a face recognition system using Open-CV and Face recognition frameworks
  * Design a focus recognition algorithm based on facial angle and facial features size
  * Testing facial recognition systems using FDDB and Wider Face datasets

* Research on kernel hiding attack technology in IoT environment *Apr. 2019-Dec. 2019*
  * Understand the startup process of embedded systems
  * Understand the BeagleBone development kit launch process
  * Complete rootkit implantation based on remote weak password vulnerabilities such as Telnet and SSH
  * Constructing a payload based on binary vulnerabilities for rootkit implantation
  * Implement rootkit hiding and application name tampering at the application layer

  
Social experience
======
* Minister of the Student Union, Nanjing University of Posts and Telecommunications *Sept. 2018-Sept. 2019*
  * Lead the department in daily work
  * design and organize activities
  * complete material writing and application
  * responsible for writing mid year and year-end summary reports

Awards
======
* University Scholarship of Chinese Academy of Sciences *2021, 2022, 2023*
* First World Privacy Protection Computing Competition (WPPCC) First Prize *2021*
* Nanjing University of Posts and Telecommunications High Morality Prize *2019*
* Nanjing University of Posts and Telecommunications Social Work Award *2018, 2019*
* 23rd Nanjing University of Posts and Telecommunications Science and Technology Festival Network Attack and Defense Competition Second Prize *2018*
* Nanjing University of Posts and Telecommunications Social Work Award *2018*

Skills
======
* Language
  * CET-6(463)
* Programming
  * C/C++
  * Python

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
