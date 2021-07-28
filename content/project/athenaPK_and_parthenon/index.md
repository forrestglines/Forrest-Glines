---
title: AthenaPK and Parthenon
summary: Performance-Portable Astrophysics Simulations with Adaptive Mesh Refinement
tags:
- Code Development
- Performance Portability
- AthenaPK
date: "2021-06-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: "https://gitlab.com/theias/hpc/jmstone/athena-parthenon/athenapk"

#image:
#  caption: Mach number and magnetic pressure from magnetized Taylor-Green simulation
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

AthenaPK is an in-development performance-portable conversion of Athena++ build
on the Parthenon adapative mesh refinement (AMR) framework using the Kokkos
performance portability library. I am one of the main developers for AthenaPK
and a co-developer for Parthenon. The Parthenon framework is designed to be
massively scalable and efficient on both CPUs and GPUs, enabling
next-generation AMR simulations on a variety of hardware architectures. Kernels
and data are managed by Kokkos, which enables high performance on any
architecture supported by Kokkos, including CPUs, NVidia and AMD GPUs, and
future Intel GPUs. AthenaPK uses the robust solvers from Athena++ within the
Parthenon framework to enable future exascale astrophysical simulations.

[Partheon Repository](https://github.com/lanl/parthenon)

[AthenaPK Repository](https://gitlab.com/theias/hpc/jmstone/athena-parthenon/athenapk)
