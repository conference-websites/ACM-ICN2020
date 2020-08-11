---
layout: default
title: "Half-day Tutorial: Online Learning for Data Caching and Network Service Delivery"
group: Tutorials

data:
  - type: day
    time: TBD
    room: TBD

presenters:
- name: Georgios Paschos
  affiliation: Head of ATS Operations Research Group, Amazon, Luxembourg
  homepage: http://gpasxos.pagesperso-orange.fr/
  photo: speakers/Georgios-Paschos.jpg
  bio: "
  Since July 2019, Dr. Paschos is a Senior Manager, Research Science at Amazon.com, leading the EU Operation Research team of Amazon Transportation Services. Previously, he worked 5 years (’14-’19) as a principal scientist at Huawei Technologies, Paris, France, leading the Network Control and Resource Allocation team. Before that, Dr. Paschos was at LIDS, MIT (’12-’14) while he has held positions at CERTH-ITI, Greece ’08-’12 (researcher), University of Thessaly, Dept. ECE ’09-’11 (adjunct lecturer) and VTT, Finland, ‘07-‘08 (ERCIM Postdoc Fellow). He received his diploma in Electrical and Computer Engineering in 2002 from Aristotle University of Thessaloniki, and his PhD degree in Wireless Networks 2006 from ECE dept. University of Patras, both in Greece. Two of his papers won the best paper award, in GLOBECOM 2007 and IFIP Wireless Days 2009, respectively. In the past, he served as an associate editor for IEEE/ACM Trans. on Networking (’15-’19), IEEE Networking Letters (’18-’19), and as a TPC member of INFOCOM, WiOPT, and Netsoft. He has organized several international workshops on the topics of caching, network slicing and machine learning techniques for communication systems, while he was the co-organizer and editor of the IEEE JSAC Special Issue on Caching for Comm. Systems and Networks.
"

- name: Apostolos Destounis
  affiliation: Senior Researcher in the Mathematical and Algorithmic Sciences Lab, Paris Research Center, Huawei Technologies co. ltd.
  photo: speakers/Apostolos-Destounis.jpg
  bio: "
  Dr. Destounis received the Diploma in Electrical and Computer Engineering from the National technical University of Athens, the M.Sc. in Communications and Signal Processing from Imperial College London and the Ph.D. In Telecommunications from CentraleSupelec, Paris in 2009, 2010 and 2014, respectively. From 2011 to 2014 he also was a Research Engineer in Alcetel-Lucent (now Nokia) Bell Labs France. He was the co-organizer of the first International Workshop on Machine Learning for Communications (WMLC), hosted with WiOpt 2019. His current research interests lie in the fields of optimization and machine learning, with applications to wireless networks and content caching.
"

- name: George Iosifidis
  affiliation: Assistant Professor, School of Computer Science and Statistics, Trinity College Dublin, the University of Dublin, Ireland
  homepage: https://www.futurenetworkstrinity.net/
  photo: speakers/Georgios-Iosifidis.jpg
  bio: "
  Dr. Iosifidis received the Diploma degree in communications from the Greek Air Force Academy, Athens, 2000; and the Ph.D. degree in 2012 from the Dep. of Electrical and Computer Engineering, University of Thessaly, Greece. He was a Post-Doctoral Researcher with CERTH, Greece, 2012-14, and a Post-Doctoral/Associate Research Scientist with Yale University, 2014-17. Since 2016, he is the Ussher Assistant Professor in Future Networks with the School of Computer Science and Statistics, Trinity College Dublin, and a Funded Investigator with the research center CONNECT. He was a co-recipient of the Best Paper Awards in WiOPT 2013 and the IEEE INFOCOM 2017 conferences, a guest editor for the IEEE JSAC Special Issue on Caching, and an Editor for IEEE Transactions on Communications and IEEE/ACM Transactions on Networking. His work on resource sharing and cooperative networks has appeared in Nature Communications (2019), PNAS (2019), and Nature Human Behavior (2018). His interests lie in the area of network optimization and economics, with a recent focus on edge computing and mobile data analytics.
"

---

## {{ page.title }}

### Presenters

{% assign expand=true %}
{% include presenters.html presenters=page.presenters %}

### Outline

Storage resources and caching techniques permeate almost every facet of wired and wireless networks.
From storage-assisted future Internet architectures and cache-enabled 5G systems, to modern analytic services that rely on memory-demanding ML/AI models, caching promises to benefit both the network operators by reducing their expenditures, and the end-users by improving the offered services. In light of the pressing data traffic growth, the increasing number of rich-media services, and the fast emergence of mobile analytic applications, the following question is inevitably raised:
 
> Can we leverage online learning  for maximizing the benefits of storage resources and optimizing the performance of services in modern communication systems?
 
In this tutorial we will start with a brief historical background on caching and will accordingly explain why caching is instrumental for modern network services and user applications beyond content delivery.
We will present, in a novel and unified fashion, fundamental concepts of popularity request models and network graphs, with examples and pointers to real datasets and deployed systems. We will then shift our attention to the basic theory of online learning that has recently taken over the machine learning literature, and explain the key notions and tools that a network/communications researcher needs to know. A series of recent results that apply online learning in wireless edge caching/routing and device-to-device caching will be presented, showing evidence that this powerful analytical tool can address shortcomings of previous optimization approaches. Accordingly, we will discuss online learning techniques for deploying other network services (single-stage or chained functions), placing emphasis on minimizing their costs and reconfiguration delays in dynamic environments with unknown and unpredictable requests. This tutorial will conclude with a series of open questions at the nexus of online learning and deployment of network services and caching.
