---
abstract: null
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Philipp Grete
  - admin
  - Brian W. O'Shea
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *TPDS*
url_source: ""
url_video: ""
publication: In *Transactions on Parallel and Distributed Systems*
featured: true
date: 2020-07-17T00:00:00Z
url_slides: ""
title: " K-Athena: a performance portable structured grid finite volume
  magnetohydrodynamics code "
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2020-07-17T00:00:00Z
url_poster: ""
url_code: ""
doi: 10.1109/TPDS.2020.3010016
---
Large scale simulations are a key pillar of modern research and require
ever-increasing computational resources. Different novel manycore architectures
have emerged in recent years on the way towards the exascale era. Performance
portability is required to prevent repeated non-trivial refactoring of a code
for different architectures. We combine ATHENA++, an existing
magnetohydrodynamics (MHD) CPU code, with KOKKOS, a performance portable
on-node parallel programming paradigm, into K-ATHENA to allow efficient
simulations on multiple architectures using a single codebase. We present
profiling and scaling results for different platforms including Intel Skylake
CPUs, Intel Xeon Phis, and NVIDIA GPUs. K-ATHENA achieves $> 10^8$ cell-updates/s
on a single V100 GPU for second-order double precision MHD calculations, and a
speedup of 30 on up to 24,576 GPUs on Summit (compared to 172,032 CPU cores),
reaching $1:94\times10^12$ total cell-updates/s at 76 percent parallel efficiency.
Using a roofline analysis we demonstrate that the overall performance is
currently limited by DRAM bandwidth and calculate a performance portability
metric of 62.8 percent. Finally, we present the implementation strategies used
and the challenges encountered in maximizing performance. This will provide
other research groups with a straightforward approach to prepare their own
codes for the exascale era. K-ATHENA is available at
https://gitlab.com/pgrete/kathena.
