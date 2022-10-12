---
layout: page
title: "How to write Parallel Programs: The Python Edition"
schedule: "October, 2022"
---

Everyone wants to write parallel programs, right?  Well, of course not.  Parallel programming is hard. We’d all rather write code using whatever languages and APIs we know best and leave parallelism to others. Unfortunately, parallelism is here to stay. Most of working in scientific computing will need to use parallel systems.

This tutorial will demystify parallel computing. We’ll say a bit about hardware and why parallel computing (including with heterogeneous processors) is something you just can’t avoid. Then we will review the key concepts and fundamental design patterns of parallel computing.  With that conceptual basis in place, we’ll review some of the common approaches to expressing parallelism in Python programs. Then with an eye to the future, we’ll look at some research systems under development that should make parallel programming in python even better.
The goal is a conceptual foundation for parallel programming, not mastery of any one approach. Basically, you need to know a bit about parallel programming before making an informed decision on which API to use for parallel programming. This tutorial will give you that information.

**Length:** Half day (lecture style tutorial)

**Intended Audience:** 75% introductory, 25% intermediate

**Prerequisite Knowledge:** none

**Presenters:** 
- [Tim Mattson](mailto:timothy.g.mattson@intel.com)

### Biographies

Tim Mattson is a senior principal engineer in Intel Parallel Computing lab. He has been writing parallel code since 1985 using more parallel programming languages than he can keep track of. He was an early contributor to MPI and played a leadership role in OpenMP and OpenCL. Frankly, the list of parallel programming models he has worked on is embarrassingly long. Tim has written five books on parallel computing and has extensive experience teaching the topic both in universities and as tutorials at various conferences.

### Motivation
We go to quickly to DASK or mpi4py without spending time on the fundamentals. If someone really wants to be a productive parallel programming, it makes sense to spend some time understanding the core ideas that cut across various APIs. That is the purpose of this tutorial.

### Brief Outline

- What every scientific programmer should know about parallel hardware
- Understanding performance in parallel programs
- The fundamental design patterns of parallel programming
- The most common APIs for parallelism in Python using the patterns we just learned
- Some interesting research systems for parallelism in Python
- Closing thoughts and reflections on how to choose a parallel API for use in your own projects

### Support Materials

This is a lecture-based tutorial. It is the foundational tutorial for what will become a long series of hands-on tutorials. The hands-on content, however, has not been created yet.
- [Presentation slides](https://drive.google.com/file/d/1CXWTfDeWFWeP0MR8uTL0HUJ0Vl4Q2wz_/view)
