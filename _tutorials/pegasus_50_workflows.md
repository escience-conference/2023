---
layout: page
title: "Pegasus 5.0 Workflows"
schedule: "October, 2022"
---

Workflows are a key technology for enabling complex scientific computations. They capture the interdependencies between processing steps in data analysis and simulation pipelines as well as the mechanisms to execute those steps reliably and efficiently. Workflows can capture complex processes to promote sharing and reuse, and also provide provenance information necessary for the verification of scientific results and scientific reproducibility. 

[Pegasus](https://pegasus.isi.edu) is being used in a number of scientific domains doing production grade science. In 2016 the LIGO gravitational wave experiment used Pegasus to analyze instrumental data and confirm the first detection of a gravitational wave. The Southern California Earthquake Center (SCEC) based at USC, uses a Pegasus managed workflow infrastructure called Cybershake to generate hazard maps for the Southern California region. In March 2017, SCEC conducted a CyberShake study on DOE systems ORNL Titan and NCSA BlueWaters. Overall, the study required 450,000 node-hours of computation across the two systems. Pegasus is also being used in astronomy, bioinformatics, civil engineering, climate modeling, earthquake science, molecular dynamics and other complex analyses. In 2020, we released Pegasus 5.0 that is a major improvement over previous releases. Pegasus 5.0 provides a brand new Python3 workflow API developed from the ground up so that, in addition to generating the abstract workflow and all the catalogs, it now allows you to plan, submit, monitor, analyze and generate statistics of your workflow.

The goal of the tutorial is to introduce the benefits of modeling pipelines in a portable way with use of scientific workflows. We will examine the workflow lifecycle at a high level and issues and challenges associated with various steps in the workflow lifecycle such as creation, execution and monitoring and debugging. Through hands-on exercises in a hosted Jupyter notebook environment, we will describe an application pipeline as a Pegasus workflow using Pegasus Workflow API and execute the pipeline on distributed computing infrastructures. The attendees will leave the tutorial with knowledge on how to model their pipelines in a portable fashion using Pegasus workflow and run them on varied computing environments.

**Length:** Half day

**Intended Audience:** Scientific Domain Application Developers, Application Scientists, System Architects doing large-scale scientific analysis

**Prerequisite Knowledge:** Familiarity with Unix environments

### Presenters

- [Karan Vahi](mailto:vahi@isi.edu)
- [Mats Rynge](rynge@isi.edu)

### Biographies

Karan Vahi is a Senior Computer Scientist in the Science Automation Technologies group at ISI. He is the lead developer of Pegasus and is in charge of the core development. Karan has been working on Pegasus since 2002. https://scitech.isi.edu/staff/vahi/

Mats Rynge is a Senior Computer Scientist at the University of Southern California’s Information Sciences Institute. His research interests include distributed and high-performance computing. Mats has a BS in computer science from University of California, Los Angeles. https://scitech.isi.edu/staff/rynge/ 

### Motivation 

The goal of the tutorial is to introduce application scientists to the benefits of modelling their pipelines in a portable way with use of scientific workflows. We will examine the workflow lifecycle at a high level and issues and challenges associated with various steps in the workflow lifecycle such as creation, execution and monitoring and debugging. Via a fully web-based Jupyter notebook environment, we will model an application pipeline, bundle the application codes in containers, and execute the pipeline as a Pegasus workflow. The attendees will leave the tutorial with knowledge on how to implement their own computations using containers and workflows.

Workflows with container support is a solution for multi-step applications to leverage various computing resources available as part of national cyber-infrastructure, and provide replicability and shareability. We believe this tutorial would be relevant to EScience 2022 as we address the importance of formal descriptions of the computations, data management, and usability issues in workflows such as monitoring and debugging in distributed environments.

### Brief Outline

The tutorial involves hands on exercises in a Jupyter notebooks environment. The tutorial presented will be a mix of presentation slides and hands on tutorial exercises using Pegasus. We will give an overview of scientific workflows, followed by an introduction to Pegasus WMS covering basic concepts and system architecture. We will then have hands on exercises, walking attendees through submitting and monitoring their workflows using Pegasus Workflow Dashboard and command line tools. By means of exercises, we will illustrate why it makes sense to package application code into containers and then update the tutorial workflow to use application containers. This will be followed by exercises on job clustering and fault tolerance. We will end the tutorial with slides on advanced issues in scientific workflows just such as data integrity etc

### Support Materials

The tutorial exercises and presentation will be available as a self guided tutorial available on the web. This will allow the attendees to continue or revisit the tutorial later, using their training accounts. The instructors will also make their presentation slides available to the attendees. Similar material from a tutorial from last year is available here
- [Self Contained Tutorial with Hands on Exercises in Jupyter Notebooks](https://pegasus.isi.edu/documentation/user-guide/tutorial.html)
- [Presentation Slides](https://pegasus.isi.edu/tutorial/escience21/escience21-pegasus5-tutorial-final.pdf)
