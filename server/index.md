---
title: Server
nav:
  order: 5
  tooltip: Lab computing resources
---

# {% include icon.html icon="fa-solid fa-server" %}Server

{% include figure.html image="images/server.png" width="220px" %}

## Computing Resources

- [SFSU POLARIS High-Performance Computing Cluster](https://athelp.sfsu.edu/hc/en-us/articles/31706916588819-Accessing-the-High-Performance-Computing-HPC-cluster)
- [MIC Lab GPU Server Setup Guidance](https://docs.google.com/document/d/1H7wFVQ3mjRTOPsb-oXuqkTiZ--8petIGM2F5whSmlmQ/edit?usp=sharing)

{% include section.html %}

## Lab GPU Servers

| Server | GPU | Note |
|---|---|---|
| [Server 1](http://server1.sfsu-miclab.org/) | RTX 3080, 10 GB | |
| [Server 2](http://server2.sfsu-miclab.org/) | RTX 3060, 12 GB | App hosting. Don't use for model training. |
| [Server 3](https://server3.sfsu-miclab.org/) | RTX 3080 Ti, 12 GB | |
| Server 4 | DGX Spark, 128 GB | |

{%
  include alert.html
  type="warning"
  content="Please avoid creating multiple workspaces, as each workspace allocates at least 16 GB of storage. Only create a new workspace when necessary."
%}
