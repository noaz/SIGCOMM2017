---
layout: default
title: "ACM SIGCOMM 2017 Tutorial (Half-Day): Named Data Networking (NDN) Tutorial"
group: Tutorials

data:
  - type: day
    time: TBD
    room: TBD

  - title: Welcome and Introduction
    type: tutorial
    time: 9:00am - 9:05am

  - title: NDN Architecture (Van Jacobson)
    type: tutorial
    time: 9:05am - 10:30am

  - title: Coffee Break
    type: break
    time: 10:30am - 11:00am
    room: Foyer

  - title: "NDN Research (NDN project team)"
    type: tutorial
    time: 11am - 12:30am

presenters:
- name:        Alexander Afanasyev
  affiliation: University of California, Los Angeles
  bio:         "<p>Alexander Afanasyev is an Adjunct Assistant Professor in University of California, Los Angeles.  He received his Ph.D. degree in computer science from UCLA in 2013.  His research focus is on the next-generation Internet architecture as part of the Named Data Networking (NDN) project. His research interests include a variety of topics that are vital for the success of NDN, including scalability of name-based routing, auto-configuration, distributed data synchronization, application and network security.  Dr. Afanasyev is also leading the development effort of the overall NDN codebase.</p>"

- name:        Jeff Burke
  affiliation: UCLA School of Theater, Film and Television (TFT)
  bio:         "<p>Jeff Burke is Assistant Dean for Technology and Innovation at the UCLA School of Theater, Film and Television (TFT), where he has been a faculty member since 2001.  His research explores the intersections of the built environment, computer networks, and storytelling. He has produced, managed, programmed, and designed performances, short films, new genre art installations and new facility construction internationally for over fifteen years, incorporating emerging technologies as part of these projects and creative works.  Burke co-founded REMAP, a joint center of TFT and the Henry Samueli School of Engineering and Applied Science, which uses a mixture of research, artistic production, and community engagement to investigate the interrelationships among culture, community, and technology. From 2006-2012, Burke was the area lead for participatory sensing at the NSF Center for Embedded Networked Sensing (CENS). He is Co-PI and application team lead for the Named Data Networking research project. </p>"

- name:        Patrick Crowley
  affiliation: Washington University in St. Louis
  bio:         "<p>Patrick Crowley is Professor of Computer Science & Engineering at Washington University in St. Louis, where he directs the Applied Research Lab. He is also founder and CTO of Observable Networks, a cloud-native network security company. His research interests are in computer and network systems architecture, with a current focus on information-centric networking, programmable network systems design, and the invention of superior network monitoring and security techniques.</p>"

- name:        Van Jacobson
  affiliation: University of California, Los Angeles / Google
  bio:         "<p>Van Jacobson has been a long-term contributor to the Internet. His algorithms for the Transmission Control Protocol (TCP) saved Internet from congestion collapse in 1980's and are used by over 90% of Internet hosts today. He developed the blueprint of Named Data Networking (NDN) 10 years ago and continues to serve as the NDN architect.</p>"

- name:        Beichuan Zhang
  affiliation: University of Arizona
  bio:         "<p>Beichuan Zhang is Associate Professor at the Department of Computer Science, the University of Arizona. His research interest is in Internet routing architectures and protocols. He has been working on Named Data Networking, green networking, and inter-domain routing. He received the Applied Networking Research Prize in 2011 by ISOC and IRTF, and best paper awards at IEEE ICDCS in 2005 and IWQoS in 2014. Dr. Zhang received Ph.D. from UCLA and B.S. from Peking University.</p>"

---

## {{ page.title }}

### Call For Participation

This is a half-day tutorial on Named Data Networking (NDN), a newly developed data-centric Internet architecture. The morning starts with an introduction of the NDN architecture by Van Jacobson, followed by research topics and recent results.

### Presenters

{% include presenters.html presenters=page.presenters %}

### Tutorial Program

{% include program.html type="tutorial-ndn" data=page.data %}

### Motivation

This half-day tutorial aims to provide a comprehensive overview of [Named Data Networking (NDN)](https://named-data.net/), a newly developed Internet architecture. NDN replaces TCP/IP architecture's focus on "where", i.e., the addresses and hosts, with "what", i.e., the content that users and applications care about. This fundamental shift brings profound impacts to enhancing Internet security, enabling mobility support, scaling both data disseminations as well as data collection (e.g., from IoT devices), and facilitating new application development.

Launched in 2010 under the NSF's Future Internet Architecture program, the NDN project has attracted researchers from both academia and industry around the world to explore all aspects of its design, implementation, and applications.  It is arguably the most prominent inspiration and realization of the Information-Centric Networking (ICN) vision, around which a growing research community has formed over the past several years.

Together with an increasing interests in NDN, there are also a number of questions as well as misconceptions regarding NDN.  This tutorial aims to bring NDN to the broader networking community by explaining NDN's basic architectural concepts, articulating research issues, demonstrating NDN operations and applications, and introducing its open-source code development. We expect the tutorial to benefit network researchers and students with different levels of background knowledge on NDN/ICN, from people who want to learn what NDN really is, to people who are looking for new topics to explore, or for ways to contribute to NDN design and development.

The tutorial will start with an introduction to the NDN architecture by Van Jacobson, followed by an overview of the NDN research topics and recent results by the NDN project team researchers.

### Topics Include

- Introduction of the basic concepts, fundamental principles, key mechanisms, and articulation on how to take NDN to the next stage.

- Survey on existing NDN research work, with emphasis on research challenges and recent results, including

    - Routing
    - Forwarding
    - Caching
    - Mobility
    - Security
    - Applications

### Expected Audience and Prerequisites

This tutorial targets the general networking research community with no specific prerequisite. We expect the tutorial to benefit network researchers and students with different levels of background knowledge on NDN/ICN, from people who want to learn what NDN really is, to people who are looking for new topics to explore, or for ways to contribute to NDN design and development.
