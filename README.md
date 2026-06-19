# 2025/2026

A course on cloud computing applications and services addressing the challenges of deploying, provisioning, and operating complex distributed applications at scale. Modern cloud-native systems — from microservices and container orchestration to distributed storage and observability pipelines — demand a solid understanding of the tools and techniques that make them reliable, manageable, and performant.

This course covers both foundational and cutting-edge cloud technologies, from infrastructure-as-code and virtualization to container orchestration with Kubernetes, distributed storage, and monitoring at scale. By mastering these foundations, students develop deep, transferable knowledge that prepares them to contribute meaningfully to both cutting-edge research and production engineering at scale.

## Learning outcomes

- Understand the main challenges of deploying and operating complex distributed applications in cloud environments.
- Apply infrastructure-as-code tools and techniques to provision, configure, and manage cloud systems in a reproducible and automated fashion.
- Deploy and manage containerized applications using orchestration platforms such as Docker and Kubernetes.
- Monitor and benchmark cloud applications to analyze performance, detect anomalies, and support informed operational decisions.

## Instructors

- [João Paulo](https://jtpaulo.github.io/)
- [Tânia Esteves](https://taniaesteves.github.io/)
- [Cláudia Brito](https://claudiavmbrito.github.io)
- [Pedro Moreira](https://www.di.uminho.pt/~jno/sitedi/nm_14112.html)
- [Bruno Pereira](https://www.di.uminho.pt/~jno/sitedi/nm_14951.html)

## Grading

The grade has two components:

- Group project and discussion (50%), in groups of 5 students, with minimum grade of 10/20.
- Written exam (50%), with at least 8/20.

## Schedule

| # | Date | Topic | Mat. | Read |
|:-:|:----:|:------|:----:|:----:|
| T1 | 22/09 | Introduction. | [&#128462;](editions/2025_2026/materials/1%20-%20Introduction.pdf) | B1; B2 |
| PL1 | 22/09 | Lab 0: Vagrant/VMs + Bash. | [&#128462;](editions/2025_2026/materials/Guide0-slides.pdf) [pdf](editions/2025_2026/materials/Guide0.pdf) [zip](editions/2025_2026/materials/guide0.zip) | |
| T2 | 29/09 | Distributed Applications. | [&#128462;](editions/2025_2026/materials/2%20-%20Distributed%20Applications.pdf) | B2; P1 |
| PL2 | 29/09 | Lab 1: Case-study Application. | [&#128462;](editions/2025_2026/materials/Guide1-slides.pdf) [pdf](editions/2025_2026/materials/Guide1.pdf) | |
| T3 | 06/10 | System Provisioning. | [&#128462;](editions/2025_2026/materials/3%20-%20System%20Provisioning.pdf) | B1; P2 |
| PL3 | 06/10 | Lab 2: Containers. | [&#128462;](editions/2025_2026/materials/Guide2-slides.pdf) [pdf](editions/2025_2026/materials/Guide2.pdf) [zip](editions/2025_2026/materials/guide2.zip) | |
| T4 | 13/10 | Cloud Computing. | [&#128462;](editions/2025_2026/materials/4%20-%20Cloud%20Computing.pdf) | B3; P3 |
| PL4 | 13/10 | Lab 2: Containers (cont.). | | |
| T5 | 20/10 | Virtualization Part I — VMs. | [&#128462;](editions/2025_2026/materials/5%20-%20Virtualization%20Part%201%20-%20VMs.pdf) | B4; P4 |
| PL5 | 20/10 | Lab 2: Containers + Provisioning (cont.). | | |
| T6 | 27/10 | Virtualization Part II — Containers + K8s. | [&#128462;](editions/2025_2026/materials/6%20-%20Virtualization%20Part%202%20-%20Containers.pdf) | B1; B4; B5 |
| PL6 | 27/10 | Lab 3: Kubernetes. | [&#128462;](editions/2025_2026/materials/Guide3-slides.pdf) [pdf](editions/2025_2026/materials/Guide3.pdf) [zip](editions/2025_2026/materials/guide3.zip) | |
| T7 | 03/11 | Storage. | [&#128462;](editions/2025_2026/materials/7%20-%20Storage.pdf) | P5; P6; P7 |
| PL7 | 03/11 | Lab 3: Kubernetes (cont.). | | |
| T8 | 10/11 | Storage (cont.). |  | P5; P6; P7 |
| PL8 | 10/11 | Lab 4: Monitoring. | [&#128462;](editions/2025_2026/materials/Guide4-slides.pdf) [pdf](editions/2025_2026/materials/Guide4.pdf) [zip](editions/2025_2026/materials/guide4.zip) | |
| T9 | 17/11 | Monitoring. | [&#128462;](editions/2025_2026/materials/8%20-%20Monitoring.pdf) | B6; P8; P9 |
| PL9 | 17/11 | Q&A / Project. | | |
| T10 | 24/11 | Benchmarking. | [&#128462;](editions/2025_2026/materials/9%20-%20Benchmarking.pdf) | B6; P10; P11 |
| PL10 | 24/11 | Lab 5: Benchmarking. | [&#128462;](editions/2025_2026/materials/Guide5-slides.pdf) [pdf](editions/2025_2026/materials/Guide5.pdf) | |
| T11 | 15/12 | Q&A. | | |
| PL11 | 15/12 | Q&A. | | |
| P | 02/11 | Checkpoint #1. | | |
| P | 30/11 | Checkpoint #2. | | |
| P | 29/12 | Project submission deadline. | | |
| TE | 05/01 | Exam. | | |
| PD | 12–17/01 | Project discussion. | | |

- Subject to change, watch Blackboard for notifications.
- T — Lectures; PL — Labs; P — Project; TE — Exam; PD — Project Discussion.

## Project

The project consists of automating the installation, configuration, monitoring, and evaluation of the [AirTrail](https://github.com/johanohly/AirTrail) web application on Google Kubernetes Engine (GKE) using Ansible, followed by an experimental analysis of its performance, scalability, and resilience.

Submitted projects must be fully authored by the students and must not contain materials (text, code, ...) from third parties, obtained online, or using AI tools unless explicitly marked and authorized by the instructors. See [Academic Regulations and Code of Ethical Conduct](https://alunos.uminho.pt/pt/estudantes/paginas/infouteisregulamentos.aspx) for more information.

## Bibliography

| # | Title |
|:-:|-------|
| B1 | K. Morris. [Infrastructure as Code: Managing Servers in the Cloud](https://www.oreilly.com/library/view/infrastructure-as-code/9781491924334/). O'Reilly, 2016. |
| B2 | M. Kleppmann. [Designing Data-Intensive Applications](https://dataintensive.net/). O'Reilly, 2017. |
| B3 | T. Erl, R. Puttini, and Z. Mahmood. Cloud Computing: Concepts, Technology and Architecture. Prentice Hall, 2013. |
| B4 | S. Alapati. Modern Linux Administration: How to Become a Cutting-edge Linux Administrator. O'Reilly, 2016. |
| B5 | B. Burns. [Kubernetes Up & Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781492046523/) (Second Edition). O'Reilly, 2019. |
| B6 | R. Jain. The Art of Computer Systems Performance Analysis. Wiley, 1991. |
| P1 | C. Tang et al. Holistic Configuration Management at Facebook. SOSP, 2015. |
| P2 | Ansible Documentation. [https://docs.ansible.com](https://docs.ansible.com). |
| P3 | M. Armbrust et al. A View of Cloud Computing. Communications of the ACM, 2010. |
| P4 | P. Barham et al. Xen and the Art of Virtualization. SOSP, 2003. |
| P5 | R. Macedo, J. Paulo, J. Pereira, and A. Bessani. A Survey and Classification of Software-Defined Storage Systems. ACM Computing Surveys, 2020. |
| P6 | J. Paulo and J. Pereira. A Survey and Classification of Storage Deduplication Systems. ACM Computing Surveys, 2014. |
| P7 | S. A. Weil et al. [Ceph: A Scalable, High-Performance Distributed File System](https://dl.acm.org/doi/10.5555/1298455.1298485). OSDI, 2006. |
| P8 | T. Esteves, F. Neves, R. Oliveira, and J. Paulo. [CaT: Content-aware Tracing and Analysis for Distributed Systems](https://dl.acm.org/doi/10.1145/3491086). ACM/IFIP Middleware, 2021. |
| P9 | T. Esteves, R. Macedo, R. Oliveira, and J. Paulo. Toward a Practical and Timely Diagnosis of Applications' I/O Behavior. IEEE Access, 2023. |
| P10 | F. Coelho, J. Paulo, R. Vilaça, J. Pereira, and R. Oliveira. HTAPBench: Hybrid Transactional and Analytical Processing Benchmark. ICPE, 2017. |
| P11 | B. K. Vangoor, V. Tarasov, and E. Zadok. [To FUSE or Not to FUSE: Performance of User-Space File Systems](https://www.usenix.org/conference/fast17/technical-sessions/presentation/vangoor). USENIX FAST, 2017. |