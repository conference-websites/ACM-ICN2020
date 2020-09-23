---
layout: default
title: "Half-day Tutorial: Practical NDN Application Development and Seamless Deployment"
group: Tutorials

presenters:
- name: Alex Afanasyev
  affiliation: Florida International University
  homepage: https://users.cs.fiu.edu/~afanasyev
  photo: speakers/Alex-Afanasyev.jpg
  bio: "
  Alex Afanasyev is an Assistant Professor in Florida International University, Miami. He received his Ph.D. degree in computer science from UCLA in 2013. His research focus is on the next-generation Internet architecture as part of the Named Data Networking (NDN) project. His research interests include a variety of topics that are vital for the success of NDN, including scalability of name-based routing, autoconfiguration, distributed data synchronization, application and network security. Dr. Afanasyev is also leading the development effort of the overall NDN codebase.
"

- name: Lan Wang
  affiliation:  University of Memphis
  photo: speakers/Lan-Wang.jpg
  bio: "
  Lan Wang is Professor and Chair of the Computer Science Department at the University of Memphis. She holds a B.S. degree (1997) in Computer Science from Peking University, China and a Ph.D. degree (2004) in Computer Science from University of California, Los Angeles. Her research interests include future Internet architecture, Internet routing, network security, network performance measurement and sensor networks.
"

- name: Beichuan Zhang
  affiliation: University of Arizona
  photo: speakers/Beichuan-Zhang.jpg
  bio: "
  Beichuan Zhang is an Associate Professor at the Department of Computer Science, the University of Arizona. His research interest is in Internet routing architectures and protocols. He has been working on Named Data Networking, green networking, and inter-domain routing. He received the Applied Networking Research Prize in 2011 by ISOC and IRTF, and best paper awards at IEEE ICDCS in 2005 and IWQoS in 2014. Dr. Zhang received Ph.D. from UCLA and B.S. from Peking University.
"

- name: Jeff Burke
  affiliation: UCLA/REMAP
  photo: speakers/Jeff-Burke.jpg
  bio: "
  Jeff Burke is Professor In-Residence and Associate Dean forTechnology and Innovation at the UCLA School of Theater,Film and Television (TFT), where he has been a faculty member since 2001. His research explores the intersections ofthe built environment, computer networks, and storytelling. Burke co-founded REMAP, a joint center of TFT and the Henry Samueli School of Engineering and Applied Science,which uses a mixture of research, artistic production, and community engagement to investigate the interrelationships among culture, community, and technology. He is Co-PI and application team lead for the Named Data Networking research project.
"

- name: Tianyuan Yu
  affiliation: UCLA
  photo: speakers/Tianyuan-Yu.jpg
  bio: "
  Tianyuan Yu is a Ph.D. student in the Computer Science Department of UCLA, under the supervision of Prof. Lixia Zhang. His main research interests are Named Data Networking, Internet of Things and Network Security. He is also contributing to the development of the NDN software.
"

- name: Xinyu Ma
  affiliation: UCLA
  photo: speakers/Xinyu-Ma.jpg
  bio: "
Xinyu Ma is a Ph.D candidate in the Computer Science Department of UCLA, under the supervision of Prof. Lixia Zhang.
His research focus is applications and algorithms in Named Data Networking (NDN).
He is the main maintainer of python-ndn, an NDN client library in Python 3. He is also contributing to the development of NDN IoT.
"

- name: Lixia Zhang
  photo: speakers/Lixia-Zhang.jpg
  affiliation: UCLA
  bio: "
Lixia Zhang is a Professor in the Computer Science Department of UCLA.  She received her Ph.D in computer science from MIT and was a member of the research staff at Xerox PARC before joining UCLA. She is a fellow of ACM and IEEE, the recipient of IEEE Internet Award, and the holder of UCLA Postel Chair in Computer Science.  Since 2010 she has been leading the effort on the design and development of the NDN architecture."


---

## {{ page.title }}

### Overview
* TOC
{:toc}

### Presenters

{% assign expand=true %}
{% include presenters.html presenters=page.presenters %}

### Introduction

With its built-in security and ad hoc mobility support, Named Data Networking (NDN) offers an ideal substrate to meet the needs of emerging new applications, and NDN trials should meet the least resistance at edges. This tutorial is to share our recent progress on new API and plug-n-play support which address the following two obstacles in experimentation with NDN:

- Limited high-level APIs to explore new application ideas, forcing users to work with low level Interest-Data exchange and reimplement basic mechanics (e.g., reliable data fetching); and

- Complexity in deploying NDN applications in local NDN environments, be it an NDN island connected to the NDN testbed, small-scale local NDN testbed, or an ad hoc NDN environment.

The new API is built by combining the results from existing work, which have been published in recent ICN conferences, namely consumer/producer API, Common Name Library (CNL), and pub-sub support. The plug-n-play support is based on our deepened understanding about the relations between NDN configuration and reachability, and the tools to make the former a turn-key solution and the latter automated.

In this tutorial we start with a quick overview of NDN development, followed by a combination of pilot application and the API library descriptions, and wrap up with NDN plug-n-play discussions and demonstrations.

### Tutorial Description

This short tutorial is expected to run 3 hours including a 20-minute break. It will be mostly real-time presentations with a few pieces of recorded demonstrations.

While NDN brings the concept of fetching data using names via Interest/Data packet exchange at the network level, application developers do not need to directly work with such low-level details. Over the last few years, several application/developer-friendly high-level APIs have been proposed that hide data fetching specifics while providing NDN security and other functionality such as multi-party synchronization. In particular, developers can use consumer/producer API support and publish-subscribe concepts to leverage NDN mechanics without directly dealing with individual Interest and Data packets. Moreover, given the major focus on naming in NDN, the team developed an approach to structure application development around the name strucure—NDN Common Name Library (CNL). With CNL, an application can explore available (discoverable) namespaces, subscribe to a namespace branch (i.e., subscribe to a topic) as well as publish data. Therefore, one goal of this tutorial is to introduce high-level concepts such as pub-sub and CNL API that developers can use to write NDN applications. We note that the consumer/producer API work, complements the CNL API by providing data transport services beneath the namespace.

### Preliminary Tutorial Program

{% assign abstractTitle="" %}
{% assign expanded=true %}
{% include program-online.html type="tutorial-ndn" %}
