---
title: AGN Feedback Heating Kernels
summary: Abstracting AGN feedback with a thermal-only heating model
tags:
- Astrophysics
- Active Galactic Nuclei
- Galaxy Clusters
- Enzo
date: "2021-06-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Cooling rate and entropy mass densities of three representative simulations
  focal_point: Smart

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
Using hydrodynamic simulations of idealized galaxy clusters with Enzo, we investigated whether purely thermal AGN feedback models could replicate the cool-core clusters produced by kinetic jet AGN feedback models. Such a purely thermal feedback model would serve as a theoretical approximation of energy deposition by AGN jets. Although we found no such purely thermal heating kernel that maintained a cool-core cluster, we did develop a model between the radial deposition of energy by the AGN, the entropy profile of the cluster, and the stability of the cluster.

![](hc_schematic.png "Schematic of Heating kernel outcomes")

We identified three potential outcomes:
- Centrally underheating kernels, which lead to early cooling catastrophes.
-  Centrally overheating kernels, which lead to unphysically elevated central entropies but ultimately stable clusters.
-  Centrally intermediately heating kernels, which balance a reasonable central entropy
These outcomes were borne out in the simulations depending on how centrally concentrated the AGN heating was.

![](featured.png "Cooling rate and entropy mass densities of three representative simulations")

Full explanations and descriptions are available in our paper [in the Astrophysical Journal](https://doi.org/10.3847/1538-4357/abb08c)
