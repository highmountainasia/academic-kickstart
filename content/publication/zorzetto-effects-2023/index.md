---
title: 'Effects of complex terrain on the shortwave radiative balance: a sub-grid-scale
  parameterization for the GFDL Earth System Model version 4.1'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Enrico Zorzetto
- Sergey Malyshev
- Nathaniel Chaney
- David Paynter
- Raymond Menzel
- Elena Shevliakova

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-07-17T16:47:23.877041Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '2'

# Publication name and optional abbreviated publication name.
publication: '*Geoscientific Model Development*'
publication_short: ''

doi: 10.5194/gmd-16-1937-2023

abstract: Parameterizing incident solar radiation over complex topography regions
  in Earth system models (ESMs) remains a challenging task. In ESMs, downward solar
  radiative fluxes at the surface are typically computed using plane-parallel radiative
  transfer schemes, which do not explicitly account for the effects of a three-dimensional
  topography, such as shading and reflections. To improve the representation of these
  processes, we introduce and test a parameterization of radiation–topography interactions
  tailored to the Geophysical Fluid Dynamics Laboratory (GFDL) ESM land model. The
  approach presented here builds on an existing correction scheme for direct, diffuse,
  and reflected solar irradiance terms over three-dimensional terrain. Here we combine
  this correction with a novel hierarchical multivariate clustering algorithm that
  explicitly describes the spatially varying downward irradiance over mountainous
  terrain. Based on a high-resolution digital elevation model, this combined method
  first defines a set of sub-grid land units (“tiles”) by clustering together sites
  characterized by similar terrain–radiation interactions (e.g., areas with similar
  slope orientation, terrain, and sky view factors). Then, based on terrain parameters
  characteristic for each tile, correction terms are computed to account for the effects
  of local 3D topography on shortwave radiation over each land unit. We develop and
  test this procedure based on a set of Monte Carlo ray-tracing simulations approximating
  the true radiative transfer process over three-dimensional topography. Domains located
  in three distinct geographic regions (Alps, Andes, and Himalaya) are included in
  this study to allow for independent testing of the methodology over surfaces with
  differing topographic features. We find that accounting for the sub-grid spatial
  variability of solar irradiance originating from interactions with complex topography
  is important as these effects led to significant local differences with respect
  to the plane-parallel case, as well as with respect to grid-cell-scale average topographic
  corrections. We further quantify the importance of the topographic correction for
  a varying number of terrain clusters and for different radiation terms (direct,
  diffuse, and reflected radiative fluxes) in order to inform the application of this
  methodology in different ESMs with varying sub-grid tile structure. We find that
  even a limited number of sub-grid units such as 10 can lead to recovering more than
  60 % of the spatial variability of solar irradiance over a mountainous area.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://gmd.copernicus.org/articles/16/1937/2023/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
