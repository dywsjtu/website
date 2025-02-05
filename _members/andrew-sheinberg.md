---
name: Andrew Sheinberg
image: images/photos/andrew-sheinberg.jpg
role: phd
# affiliation: University of Colorado
# aliases:
#   - J. Smith
#   - J Smith
links:
  home-page: https://andrewsheinberg.com/
#  orcid: 0000-0001-7002-5033
---

Hi, I'm Andrew Sheinberg. I am a second-year CS PhD student at Princeton University advised by Professor Kai Li. Prior to Princeton, I graduated from Yale where where I studied Computer Science & Mathematics. I grew up in Barrington, RI.

I am researching high-performant, machine learning systems. More specifically, I focus on understanding the relationships between operating systems and accelerator + networking software stacks. I am guided by a hypothesis that a coarse-grained, job-level interface for reserving cluster hardware coupled with "inefficient" higher-level software frameworks leads to excessive resource underutilization + overall energy consumption.

I am working towards developing a cleaner interface for linear-algebra based workloads to both improve the developer experience and reduce costs (via higher hardware utilization). This entails investigating the low-level details of:

Accelerator Memory-Management
Accelerator Computation Scheduling
Asynchronous Data Transfers across filesystems/host memory/PCIe/accelerator memory/accelerator interconnects/network
InfiniBand/RoCE
