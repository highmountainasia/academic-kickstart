---
title: Mapping proglacial headwater streams in High Mountain Asia using PlanetScope
  imagery

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jonathan A. Flores
- Colin J. Gleason
- Craig B. Brinkerhoff
- Merritt E. Harlan
- M. Malisse Lummus
- Leigh A. Stearns
- Dongmei Feng

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-07-17T16:47:23.822626Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '2'

# Publication name and optional abbreviated publication name.
publication: '*Remote Sensing of Environment*'
publication_short: ''

doi: 10.1016/j.rse.2024.114124

abstract: Headwater streams transport nutrients, sediment, and mineral-rich groundwater
  downstream. In High Mountain Asia (HMA), headwater streams also funnel glacier and
  snow melt to sustain continuous water supply for the downstream region. These channels
  remain poorly mapped because of their inaccessibility and because they are smaller
  than the resolution of Landsat (30 m) and Sentinel-2 (10 m). In this study, we assessed
  the ability of 3 m resolution PlanetScope imagery to detect the proglacial headwaters
  downstream of all high-altitude glaciers larger than 5 km2 in HMA. We created 3000
  manually labeled image tiles to train and evaluate computer vision (CV) against
  techniques common in the hydrologic remote sensing literature, specifically normalized
  difference water index (NDWI) thresholding and random forests (RF). Results indicate
  that CV best detects the headwater streams with textgreater0.60 F1-scores, nearly
  0.20 points higher than RF and 0.45 points higher than thresholding. We also assessed
  how errors in CV propagate to derived hydrologic information, exemplified by the
  biogeochemically critical measurement of stream surface area. We found that CV classifications
  produced surface areas with 0.98 R2, 0.01 km2 MAE, and 0.02 km2 RMSE against manually
  labeled surface areas. We also observed the best CV performance during the spring
  season with 30% more skillful classification performance than in summer and fall.
  Our results prove the ability of PlanetScope imagery to detect and map headwater
  streams accurately and at scale, and that classification errors stemming from the
  imagery or the CV methods do not greatly impair our ability to quantify stream surface
  area meaningful for biogeochemical exchange and hydrology studies.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer vision
- Headwaters
- High Mountain Asia
- PlanetScope
- Rivers
- Surface water

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
  url: https://www.sciencedirect.com/science/article/pii/S0034425724001354
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
