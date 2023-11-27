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

`Pseudohouseholds` is an R package for generating representative points along road networks within regions--"pseudohouseholds," or "PHHs"--that can be used for population-weighted travel analyses.


# Description of the Algorithm

# Comparison to Other Methods

We are unaware of any publised prior software for producing pseudohouseholds. This algorithm was inspired by prior work by the Government of Canada, which has produced "Pseudo-Household Demographic Distributions" for Canada in census years 2016 and 2021, although their methods are not published and we were unable to obtain details upon request [@secretariat_pseudo-household_2023]. 

There are other methods of converting polygons to points for travel analysis. One common method assigns a region's entire population to a single point, usually the centroid. This assumption can be problematic in regions which are larger, are more rural, or that are concave and do not contain their centroids.

# Links to Research


# References


