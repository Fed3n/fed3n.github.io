---
permalink: /
title: "Federico De Marchi"
seo_title: "Federico De Marchi - Homepage"
excerpt: "Ph.D. student in Computer Science at the Max Planck Institute for Informatics, working on networked systems and data center networks."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I am a Ph.D. student in Computer Science at the Max Planck Institute for Informatics and Saarland University in the [Network and Cloud Systems](https://www.mpi-inf.mpg.de/departments/network-and-cloud-systems) group, advised by Dr. Yiting Xia.

My research interests lie in networked systems, with a strong focus on data center networks. As more computing power moves into data centers, I believe there is significant potential for improving efficiency and sustainability by pushing the current boundaries of network engineering. In particular, I am interested in designing specialized network stack solutions for alternative, cost-efficient data center architectures.

More specifically, my work so far has focused on routing and transport protocols for **reconfigurable data center networks** and **flat network topologies**.

Before starting my Ph.D., I completed my M.Sc. in Computer Science at Saarland University. During this time, I worked as a HiWi (student assistant) in the same research group, where I first developed an interest in reconfigurable data center networks. Previously, I received my B.Sc. from the University of Bologna, advised by Prof. Renzo Davoli, working on userspace network virtualization and DNS in his [VirtualSquare](https://wiki.virtualsquare.org/) laboratory.

## News {#news}

<ul class="news">
  <li><span class="news__date">Aug 2026</span> <span class="news__text">Back from an internship at Microsoft Research Cambridge &mdash; great to work with the team there. :)</span></li>
  <li><span class="news__date">Dec 2025</span> <span class="news__text"><em>OpenOptics</em> accepted at NSDI 2026!</span></li>
  <li><span class="news__date">Jul 2025</span> <span class="news__text"><em>Flare</em> accepted at SIGCOMM 2025!</span></li>
</ul>

## Selected publications {#publications}

{% assign selected = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected %}
{% include publication-compact.html %}
{% endfor %}

<p class="pub__all"><a href="{{ base_path }}/publications/">See all publications →</a></p>

## Education {#education}

<ul class="cv-list">
  <li><span class="cv-list__when">2023 &ndash; present</span> <span class="cv-list__what">Ph.D. in Computer Science, <em>Max Planck Institute for Informatics &amp; Saarland University</em></span></li>
  <li><span class="cv-list__when">2021 &ndash; 2023</span> <span class="cv-list__what">M.Sc. in Computer Science, <em>Saarland University</em></span></li>
  <li><span class="cv-list__when">2018 &ndash; 2021</span> <span class="cv-list__what">B.Sc. in Computer Science, <em>University of Bologna</em></span></li>
</ul>

## Experience {#experience}

<ul class="cv-list">
  <li><span class="cv-list__when">2026 &ndash; 2026</span> <span class="cv-list__what">Research Intern, <em>Microsoft Research Cambridge</em></span></li>
  <li><span class="cv-list__when">2022 &ndash; 2023</span> <span class="cv-list__what">Research Assistant, <em>Max Planck Institute for Informatics</em></span></li>
</ul>

<p class="cv-list__note">Full details are in my <a href="{{ base_path }}/files/fdemarc-cv.pdf">CV (PDF)</a>.</p>
