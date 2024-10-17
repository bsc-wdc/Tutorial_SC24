# Optimising workflow lifecycle management: development, HPC-ready containers deployment and reproducibility 

## SC24 tutorial, Atlanta, November 18th, 2024

## Abstract

With Exaflop systems already here, the application communities are eager to leverage these large and complex systems. The complexity is further increased by the applications' need to combine different aspects beyond traditional HPC solvers and simulators, with artificial intelligence (AI) and data analytics (DA). The eFlows4HPC project proposed a software stack and the HPC Workflows-as-a-Service (HPCWaaS) methodology to provide tools to simplify the development, deployment, execution, and reuse of workflows. These results are leveraged in the DT-GEO and CAELESTIS projects. These tools also aim to support the reproducibility, portability and ease of use of complex workflows. 

The tutorial will focus on a set of tools and methodologies for managing the whole application workflow lifecycle. In particular, the tutorial will cover aspects of developing computational workflows with PyCOMPSs and new extensions to better integrate with AI and DA with examples from DT-GEO and CAELESTIS projects. The tutorial will also describe how to automatically record workflow provenance with PyCOMPSs to share FAIR workflows in public repositories, enabling their reproducibility. Finally, we will explain how to generate specific containers that leverage HPC systems features and use them in the workflow deployment phase. The tutorial will include hands-on sessions on different aspects.

## Agenda

| Time | Session | Presenter |
| :---- | :---- | :---- |
| 08:30 – 08:45 | Overview of tutorial agenda  | Rosa M Badia  |
| 8:45 \- 9:10  | Part 1.1: Hybrid HPC+AI+DA workflow development with PyCOMPSs Context of the eFlows4HPC project and HPCWaaS methodology Overview of workflow development with PyCOMPSs Extensions for the integration of HPC with AI and DA  | Rosa M Badia |
| 9:10 \- 9:40 | Part 1.2: Workflows’ reproducibility through provenance   Motivation for workflow provenance Design of the recording mechanism Sharing experiments for reproducibility | Raül Sirvent |
| 9:40 \- 10:00 | Part 1.3: HPC ready container images  Motivation for architecture specific containers  Overview of the Container Image Creation service  Example of HPC ready container generation  | Rosa M Badia  |
| 10:00 \- 10:30 | Break (30 min)  |  |
| 10:30 \- 10:45 | Hands-on preparation (credentials distribution, how to access, etc) (15 min) | All presenters |
| 10:45 \- 11:15 | Part 2.1: Hands-on session: Sample workflows with PyCOMPSs, execution with containers, task-graph generation, tracefile generation (optional) | Rosa M Badia |
| 11:15 \- 11:55 | Part 2.2: Hands-on session: How to automatically record workflow provenance and use it to share experiments in WorkflowHub  | Raül Sirvent |
| 11:55 \- 12:00 | Tutorial conclusions (5 min) | All presenters  |

<<<<<<< HEAD
=======
Test update

Another update 

>>>>>>> f371b9fe401779ab986dedb6d1da6c2ca2c6e3e4
