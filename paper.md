---
title: 'Pseudohouseholds: An R package for distributing populations along road networks'
tags:
  - R
  - geospatial analysis
  - road networks
  - population distribution
authors:
  - name: Christopher Belanger
    orcid: 0000-0003-2070-5721
    equal-contrib: true
    affiliation: 1
affiliations:
 - name: University of Ottawa, Canada
   index: 1
date: 27 November 2023
bibliography: paper.bib

---

# Summary

Policymakers and researchers often wish to estimate a population's travel burden when accessing services like healthcare or outdoor recreation. However, while services are usually located at discrete points, population counts are generally given for polgyonal areas like city blocks, neighbourhoods, or census tracts. Since travel burdens are generally calculated from points to points, there is a need to translate polygons to points for analysis.

Pseudohouseholds (PHHs) are representative points placed along road segments and inside regions that provide spatial distributions of properties that are defined over regions (in practice, usually population). They provide an approximate way of "spreading out" regional population distributions that can be helpful when doing travel analyses. We say that PHHs are "pseudo" households because they do not represent actual buildings or households, but they approximate the distribution of households by creating a set of populated points where we think the households are likely to be. This can allow us to create finer-grained travel or coverage analyses.

# Statement of Need



# Description of the Algorithm

# Comparison to Other Methods

By contrast, many travel analyses assume that a region's entire population is concentrated at a single point, usually the region's centroid. While this assumption can be valid for smaller regions like city blocks, it breaks in larger or rural regions where the population may be more dispersed, or regions with unusual shapes that may not contain their own centroids.

# Links to Research


# References


