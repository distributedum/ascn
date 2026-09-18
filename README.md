# 2025/2026

A course on cloud computing applications and services addressing the challenges of deploying, provisioning, and operating complex distributed applications at scale. Modern cloud-native systems (from microservices and container orchestration to distributed storage and observability pipelines) demand a solid understanding of the tools and techniques that make them reliable, manageable, and performant.

This course covers both foundational and cutting-edge cloud technologies, from infrastructure-as-code and virtualization to container orchestration with Kubernetes, distributed storage, and monitoring at scale. By mastering these foundations, students develop deep, transferable knowledge that prepares them to contribute meaningfully to both cutting-edge research and production engineering at scale.

## Learning outcomes

- Understand the internal organization and management of Cloud Computing infrastructure and services.
- Understand the concepts of scalability, dependability and security for distributed applications and services.
- Acquire expertise on virtualization technologies, for example virtual machines, containers, and Kubernetes.
- Acquire knowledge about large-scale distributed data management (e.g., file systems, object storage systems), while focusing on key features for efficient storage and protection of critical data.
- Perform application setup and installation in a distributed environment, while considering key properties such as performance, dependability and security.
- Implement distributed applications monitoring and evaluation in the cloud.
- Measure the performance of distributed cloud applications.

## Instructors

- [João Paulo](https://jtpaulo.github.io/) ([jtpaulo@di.uminho.pt](mailto:jtpaulo@di.uminho.pt))
- [Tânia Esteves](https://taniaesteves.github.io/) ([d12729@di.uminho.pt](mailto:d12729@di.uminho.pt))
- [Pedro Moreira](https://www.di.uminho.pt/~jno/sitedi/nm_14112.html) ([d14112@di.uminho.pt](mailto:d14112@di.uminho.pt))
- [Bruno Pereira](https://obrunofilipe.github.io/) ([d14951@di.uminho.pt](mailto:d14951@di.uminho.pt))
- [Luís Ferreira](https://www.di.uminho.pt/~jno/sitedi/nm_13234.html) ([d13234@di.uminho.pt](mailto:d13234@di.uminho.pt))
- [Carlos Machado](https://hiddenduck.github.io/) ([d14403@di.uminho.pt](mailto:d14403@di.uminho.pt))

## Grading

The grade has two components:

- **Group project and discussion (50%)**
    - In groups of 5 students
    - Minimum grade of 10 values out of 20
- **Written exam (50%)**
    - Minimum grade of 8 values out of 20

## Schedule

### Key dates
| Milestone | Date |
|:----------|:----:|
| Checkpoint #1 | 08/11/26 |
| Checkpoint #2 | 06/12/26 |
| Project submission deadline | 30/12/26 |
| Exam (test) | 04/01/27 |
| Project discussion | 11–16/01/27 |

### Lectures & Labs

| Week | Date | Lecture | Lab | Read |
|:----:|:----:|:--------|:----|:----:|
| 1 | 21/09/26 | Introduction<br>[ [Slides](editions/2026_2027/materials/1%20-%20Introduction.pdf) ] | Lab 0: Vagrant/VMs + Bash<br>[ [Guide](editions/2026_2027/materials/Guide0.pdf) · [Slides](editions/2026_2027/materials/Guide0-slides.pdf) · [Code](editions/2026_2027/materials/guide0.zip) ] | B1; B2 |
| 2 | 28/09/26 | Distributed Applications | Lab 1: Case-study Application | B2; P1 |
| — | 05/10/26 | *(holiday)* | *(holiday)* | |
| 3 | 12/10/26 | System Provisioning | Lab 2: Containers | B1 |
| 4 | 19/10/26 | Cloud Computing | Lab 2: Containers (cont.) | B3; P2 |
| 5 | 26/10/26 | Virtualization Part I — VMs | Lab 2: Containers + Provisioning (cont.) | B4; P3 |
| 6 | 02/11/26 | Virtualization Part II — Containers + K8s | Lab 3: Kubernetes | B1; B4; B5 |
| 7 | 09/11/26 | Storage | Lab 3: Kubernetes (cont.) | P4; P5; P6 |
| 8 | 16/11/26 | Storage (cont.) | Q&A / Project | P4; P5; P6 |
| 9 | 23/11/26 | Monitoring | Lab 4: Monitoring | B6; P7; P8 |
| 10 | 30/11/26 | Benchmarking | Lab 5: Benchmarking | B6; P9; P10 |
| 11 | 07/12/26 | Q&A | Q&A / Project | |

## Bibliography

| # | Title |
|:-:|-------|
| B1 | K. Morris. *[Infrastructure as Code: Managing Servers in the Cloud](https://www.oreilly.com/library/view/infrastructure-as-code/9781491924334/)*. O'Reilly, 2016. |
| B2 | M. Kleppmann. *[Designing Data-Intensive Applications](https://dataintensive.net/)*. O'Reilly, 2017. |
| B3 | T. Erl, R. Puttini, and Z. Mahmood. *Cloud Computing: Concepts, Technology and Architecture*. Prentice Hall, 2013. |
| B4 | S. Alapati. *Modern Linux Administration: How to Become a Cutting-edge Linux Administrator*. O'Reilly, 2016. |
| B5 | B. Burns. *[Kubernetes Up & Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781492046523/)* (Second Edition). O'Reilly, 2019. |
| B6 | R. Jain. *The Art of Computer Systems Performance Analysis*. Wiley, 1991. |
| P1 | C. Tang et al. *[Holistic Configuration Management at Facebook](https://doi.org/10.1145/2815400.2815401)*. SOSP, 2015. |
| P2 | M. Armbrust et al. *[A View of Cloud Computing](https://doi.org/10.1145/1721654.1721672)*. Communications of the ACM, 2010. |
| P3 | P. Barham et al. *[Xen and the Art of Virtualization](https://doi.org/10.1145/945445.945462)*. SOSP, 2003. |
| P4 | R. Macedo, J. Paulo, J. Pereira, and A. Bessani. *[A Survey and Classification of Software-Defined Storage Systems](https://doi.org/10.1145/3385896)*. ACM Computing Surveys, 2020. |
| P5 | J. Paulo and J. Pereira. *[A Survey and Classification of Storage Deduplication Systems](https://doi.org/10.1145/2611778)*. ACM Computing Surveys, 2014. |
| P6 | S. A. Weil et al. *[Ceph: A Scalable, High-Performance Distributed File System](https://dl.acm.org/doi/10.5555/1298455.1298485)*. OSDI, 2006. |
| P7 | T. Esteves, F. Neves, R. Oliveira, and J. Paulo. *[CaT: Content-aware Tracing and Analysis for Distributed Systems](https://doi.org/10.1145/3464298.3493396)*. ACM/IFIP Middleware, 2021. |
| P8 | T. Esteves, R. Macedo, R. Oliveira, and J. Paulo. *[Toward a Practical and Timely Diagnosis of Applications' I/O Behavior](https://doi.org/10.1109/ACCESS.2023.3322104)*. IEEE Access, 2023. |
| P9 | F. Coelho, J. Paulo, R. Vilaça, J. Pereira, and R. Oliveira. *[HTAPBench: Hybrid Transactional and Analytical Processing Benchmark](https://doi.org/10.1145/3030207.3030228)*. ICPE, 2017. |
| P10 | B. K. Vangoor, V. Tarasov, and E. Zadok. *[To FUSE or Not to FUSE: Performance of User-Space File Systems](https://www.usenix.org/conference/fast17/technical-sessions/presentation/vangoor)*. USENIX FAST, 2017. |

**Legend:** B — Book; P — Paper
