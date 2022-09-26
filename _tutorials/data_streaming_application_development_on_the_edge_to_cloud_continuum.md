---
layout: page
title: "Data Streaming Application Development on the Edge-to-Cloud Continuum"
schedule: "October, 2022"
---

Using knowledge from multiple data sources and integrating it with large-scale computational models has the potential to address today's global grand challenges in science, engineering, and society. However, integrating this diverse data with applied models across advanced cyberinfrastructure is hindered by a lack of abstractions and software stacks that can support reactive behaviors.

This tutorial addresses the development of data streaming applications across the Edge-to-Cloud Continuum. Using a fire science use-case, we will go through the process of creating an event-driven pipeline to trigger on-demand computational models. R-Pulsar is an open-source framework dedicated to implement and manage analytics between the edge of the network and the cloud. In this tutorial, we will go through a complete example of a fire science data pipeline that combines smoke detections and wildfires simulations. The tutorial will be delivered by the two presenters, but participants will be able to deploy the tools and access the data.

**Length**: Half day

**Intended Audience:** Intermediate, Data-driven application developers, Application scientists

**Prerequisite Knowledge:** 
- Basic understanding of docker containers
- Basic understanding of linux environment

### Presenters

- [Daniel Balouek-Thomert](mailto:daniel.balouek@utah.edu)
- [Ismael Perez](mailto:i3perez@sdsc.edu)

### Biographies

Daniel Balouek-Thomert is a Research Associate at the SCI Institute at the University of Utah. His research interests  focused on the control and advanced use of Edge computing systems in regard to the content of the data, the cost of computations, and the urgency of the results. Cyberinfrastructures, AI/ML applications, and data-centric/middleware systems are some of the applications of his research. 

Ismael Perez is a computational and data science research specialist with the Workflows for Data Science (WorDS) Center of Excellence and WIFIRE Lab at the San Diego Supercomputer Center, UCSD. He is currently developing cyberinfrastructure for numerous projects: Sage: A Software Defined Sensor Network, BurnPro3D, WIFIRE Commons, WIFIRE Firemap, and Expanses Composable System. His research interests are edge computing, distributed computing, parallel computing, and composable systems. 

### Motivation

The goal of the tutorial is to introduce application scientists to on-demand analytics using applied models on advanced cyberinfrastructure. Numerous constraints often restrict these features. First, the target infrastructure and context are unknown during the design phase of applied models, making it impossible for the domain scientist to meet the need for time restrictions or utility measures alone. Second, when choosing resources or carrying out actuations, it is important to consider the shared nature of the sensors and resources.

### Brief Outline

In this tutorial, we will teach you how to implement a data-driven workflow composed of geo-distributed data sources and applied models from different domains. The first part of the tutorial will cover the context and fundamental challenges related to data-driven workflows and advanced cyberinfrastructure. In the second half, the focus will be on the fire science use case and its architecture, implementation details, and results based on a deployment between sensors located between California and Utah.
