---
layout: page
title: "FEDn - A scalable federated machine learning framework for cross-device and cross-silo environments"
schedule: "October, 2022"
---

Federated machine learning has opened new avenues for privacy-preserving data analysis. Instead of pooling data in a central location, different data owners or IoT devices keep data local and training is decentralized where only model parameters are exchanged. It is an active area of research where most of the current efforts focus on the algorithmic details and communication overhead required to train accurate models. Despite much progress in the field, production-grade federated machine learning frameworks that deal with fundamental properties such as scalability, fault tolerance, security and performance in geographically distributed settings have not been available to the ML-engineer. To fill this gap, Scaleout Systems and ISCL at Uppsala University have designed and developed the FEDn framework. FEDn is an open-source framework dedicated to address federated machine learning challenges at scale. The foundation of the FEDn architecture is based on the map-reduce paradigm, a well-known scalable distributed systems design. The overall architecture consists of three tiers. The first tier consists of geographically distributed clients. The second tier is based on combiners - an intermediate tier of loosely coupled aggregation servers responsible for load balancing and robustness. The third tier consists of a single reducer component - responsible to build global models. In this tutorial, we will provide hands-on experience with the FEDn framework. We will also present the latest experiment results based on large numbers of clients running and jointly training models in a heterogeneous distributed environment.

**Length:** Half-day

**Intended Audience:** Intermediate

**Prerequisite Knowledge:**
- Software
    - Introductory level understanding of neural networks
    - Basic understanding of the Linux command-line environment
    - Basic understanding of Docker containers
    - Intermediate-level Python programming skills
- Hardware
    - A laptop with a Linux and Docker environment (preferably a virtual machine)

### Presenters
- [Salman Toor](mailto:Salman.Toor@it.uu.se)
- [Andreas Hellander](mailto:Andreas.Hellander@it.uu.se)

### Biographies

Salman Toor is Associate Professor in Scientific Computing at Uppsala University. He is an expert in the field of distributed computing infrastructures and applied machine learning. Toor is the co-chair of the Integrative Scalable Computing Lab (ISCL) at Uppsala University and co-founder and CTO at Scaleout Systems AB. He has supervised and reviewed more than forty master thesis projects and is currently the principal supervisor of a Ph.D student. Toor is also one of the lead architects of the FEDn framework, designed and developed for scalable federated machine learning. He was project leader for the project, "A Platform for Privacy-preserving Machine Learning Using the Ethereum Blockchain and Smart Contracts" and currently, he is leading Scaleout’s activities in the SESAR funded AICHAIN project. Toor is a co-PI of the Gigacow project and a named researcher in the HASTE and SustAinimal projects. Together with extensive research experience, Toor has over 15 years of teaching experience in different international institutions. He has designed and developed both masters and PhD level courses in the field of distributed computing infrastructures. From the platform of Scaleout Systems, Toor has organized a number of national and international workshops and tutorials.

Andreas Hellander is Associate Professor in computational science and engineering, co-chair of the Integrative Scalable Computing Laboratory at Uppsala University and CEO of Scaleout Systems. His scientific interests include federated machine learning and scalable digital experiments for complex systems, with 50+ scientific publications in scientific computing and its applications. His teaching experience includes being the main supervisor of 4 PhD students and 6 postdoctoral fellows. He is regularly teaching second cycle data engineering and cloud computing to 100+ students and has participated in the design and implementation of the MSc programme in Data Science at Uppsala University.

### Motivation

Federated machine learning is an increasingly popular approach for privacy-preserving machine learning. The promise is the data never leaves the owner’s environment and the owners have the complete autonomy of their datasets. The approach aligns well with the needs of recent legal regulations related to data privacy and protection. A number of software efforts have been made both in academia and commercial organizations to realize the full potential of the federated machine learning approaches. The suggested architectures for federated machine learning include centralized, hierarchical, and fully distributed environments with a varying focus on security and privacy, performance, and scalability. Scaleout Systems in collaboration with ISCL at Uppsala University have designed and developed the FEDn framework for federated machine learning at scale. To the best of our knowledge, FEDn is the only framework that can effectively manage thousands of clients in geographically distributed settings. In this tutorial, our motivation is to highlight the pressing issues in the field of federated machine learning, discuss different architectures and present FEDn framework with its theoretical details, online demo, and a dedicated hands-on session.

### Brief Outline

The first half of the tutorial will cover the overarching aims of federated machine learning, fundamental challenges related to the approach and ongoing efforts  in academia and industry. In the second half, the focus will be on the FEDn framework and on its design philosophy, architecture, implementation details, and results based on cross-device and cross-silo use cases. In the final half of the tutorial, the attendees will get the opportunity to get the hands-on experience of a federated training environment using the FEDn framework.

### Support Materials
- [GitHub link](https://github.com/scaleoutsystems/fedn)
- [YouTube channel](https://www.youtube.com/channel/UCZVv30LFXMQUOswNDKuQpNA)
- [Weblinks](https://www.scaleoutsystems.com/federated-machine-learning)
- Scientific article: Morgan Ekmefjord, Addi Ait-Mlouk, Sadi Alawadi, Mattias Åkesson, Prashant Singh, Ola Spjuth, Salman Toor, Andreas Hellander (2022) Scalable federated learning with FEDn, to appear in the 2022 IEEE/ACM International Conference on Cluster, Cloud and Grid Computing (CCGrid). [ArXiv preprint](https://arxiv.org/abs/2103.00148)
