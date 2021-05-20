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
* B.E. in Information Technology, Chandigarh University, 2025

Work experience
======
* Network Engineer & System Administration - Freelencer
  * Remote, Local

* Network Administrator
  * Bout International - Mohali, Punjab

* Systems Engineer Support
  * Cyberrack Systems - Hyderabad

Skills
======
* Networking & Network Security:
  * TCP/IP, DNS, VPN, Routing & Switching, Network Design, Network Security, Security Protocols, Firewalls, VPN Configuration

* Operating Systems & System Administration:
  * Linux (Ubuntu, CentOS), Windows Server, Windows Desktop, Active Directory, System Administration

* Virtualization & Automation:
  * Virtualization, Bash, PowerShell, Python, Ansible, Docker

* Network Tools & Simulation:
  * Wireshark, Cisco Packet Tracer, GNS3

* Soft Skills:
  * Analytical Thinking, Problem Solving, Team Collaboration, Communication

Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
