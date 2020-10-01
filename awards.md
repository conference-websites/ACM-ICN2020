---
layout: default
title: Awards
group: Conference

awards:
  - type: 2020 ACM ICN Best Paper Award Winner
    papers:
    
    - title: 'Named-Data Transport: An End-to-End Approach for an Information-Centric
    IP Internet'
      authors: Abdulazaz Albalawi and J.J Garcia-Luna-Aceves (UC Santa Cruz)
      abstract: "<p>Named-Data Transport (NDT) is introduced to provide efficient content
        delivery by name over the existing IP Internet. NDT consists of the integration
        of three end-to-end architectural components: The first connection-free reliable
        transport protocol, the Named-Data Transport Protocol (NDTP); minor extensions
        to the Domain Name System (DNS) to include records containing manifests describing
        content; and transparent caches that track pending requests for content. NDT uses
        receiver-driven requests (Interests) to request content and NDT proxies that provide
        transparent caching of content while enforcing privacy. The performance of NDT,
        the Transmission Control Protocol (TCP), and Named-Data Networking (NDN) is compared
        using off-the-shelf implementations in the ns-3 simulator. The results demonstrate
        that NDT outperforms TCP and is as efficient as NDN, but without making any changes
        to the existing Internet routing infrastructure.</p>"
      bio: ''
      photo: ''
      link: https://dl.acm.org/doi/10.1145/3405656.3418714
      slides: 7-3-albalawi.pdf
      video: https://youtu.be/I8REHovFoiE
      remote: ''
      remote-qa: ''
      COL_UID: ''

  - type: 2020 ACM ICN Best Poster Award Winner
    papers:

    - title: 'NFDFuzz: A Stateful Structure-Aware Fuzzer for Named Data Networking'
      authors: George Torres, Davide Pesavento, Junxiao Shi, and Lotfi Benmohamed (National
        Institute of Standards and Technology)
      abstract: "<p>Fuzzing is a very popular automated testing technique that has yet
        to be applied in any significant way to NDN (Named Data Networking). NDN and its
        software forwarding daemon NFD present interesting challenges for fuzzing. To
        be effective, a fuzzer for NFD needs to be both stateful, due to the nature of
        the NDN data plane, and aware of the packet structure and the rules governing
        the NDN wire protocol. In this work we present the design of our NFD fuzzer and
        provide an overview of its most salient implementation details.</p>"
      bio: ''
      photo: ''
      link: https://dl.acm.org/doi/10.1145/3405656.3420234
      slides: 3-DP-8-Torres.pdf
      video: https://youtu.be/zcKNSSvYcF0
      remote: ''
      remote-qa: ''
      COL_UID: ''

runnerups:
  - type: Runner Ups
    papers:

    - title: 'NDN-DPDK: NDN Forwarding at 100 Gbps on Commodity Hardware'
      authors: Junxiao Shi, Davide Pesavento, and Lotfi Benmohamed (National Institute
        of Standards and Technology)
      abstract: "<p>Since the Named Data Networking (NDN) data plane requires name-based
        lookup of potentially large tables using variable-length hierarchical names as
        well as per-packet state updates, achieving high-speed NDN forwarding remains
        a challenge. In order to address this gap, we developed a high-performance NDN
        router capable of reaching forwarding rates higher than 100 Gbps while running
        on commodity hardware. In this paper we present our design and discuss its tradeoffs.
        We achieved this performance through several optimization techniques that include
        adopting better algorithms and efficient data structures, as well as making use
        of the parallelism offered by modern multi-core CPUs and multiple hardware queues
        with user-space drivers for kernel bypass. Our open-source forwarder is the first
        software implementation of NDN to exceed 100 Gbps throughput while supporting
        the full protocol semantics. We also present the results of extensive benchmarking
        carried out to assess a number of performance dimensions and to diagnose the current
        bottlenecks in the packet processing pipeline for future scalability enhancements.
        Finally, we identify future work which includes hardware-assisted ingress traffic
        dispatching, dynamic load balancing across forwarding threads, and novel caching
        solutions to accommodate on-disk content stores.</p>"
      bio: ''
      photo: ''
      link: https://dl.acm.org/doi/10.1145/3405656.3418715
      slides: 2-1-Shi.pdf
      video: https://youtu.be/iOvmIQz4nvQ
      remote: ''
      remote-qa: ''
      COL_UID: ''

    - title: '(Poster) Multi-Worker NFD : an NFD-compatible High-speed NDN Forwarder'
      authors: Sung Hyuk Byun, Jongseok Lee, Dong Myung Sul, and Namseok Ko (Electronics
        and Telecommunications Research Institute)
      abstract: "<p>The NDN Forwarding Daemon (NFD) has been a reference forwarder implementation
        of Named Data Networking. Its good modularity and extensibility make it easy to
        experiment with new ideas, but it shows limited forwarding performance even with
        multi-core CPUs because its forwarding structure uses only single core. We present
        the Multi-Worker NFD (MW-NFD), an NFD-compatible NDN forwarder with parallel forwarding
        capability on multi-core CPUs. Since the NFD’s forwarding architecture is maintained
        as is, MW-NFD inherits the advantages (modularity and extensibility) of NFD, and
        it is fully compatible with NFD and existing NDN applications. In this demo, we
        shows that MW-NFD can yield high forwarding performance, about 13 times higher
        than NFD’s performance.</p>"
      bio: ''
      photo: ''
      link: https://dl.acm.org/doi/10.1145/3405656.3420233
      slides: 3-DP-7-byun.pdf
      video: https://youtu.be/5tErWbHl1go
      remote: ''
      remote-qa: ''
      COL_UID: ''

---

# Awards

{% include awards.html awards=page.awards %}

<br/>

{% include awards.html awards=page.runnerups %}
