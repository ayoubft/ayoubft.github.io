---
layout: archive
title: Compression of Geospatial Data with Varying Information Density (Code for Earth 2023 - ECMWF)
---

## Presentation

<iframe width="220" height="110" src="https://www.youtube-nocookie.com/embed/CJ7KnQgIi7E?si=LV9HVGIzVdM537Gb&amp;start=25207;end=26536&rel=0" title="YouTube video player" frameborder="0"  allowfullscreen></iframe>

[[Slides]](https://www.slideshare.net/AyoubFatihi2/ayoub-fatihis-presentation-for-code4earthecmwf-2023)

## The Challenge

* Challenge on [GitHub](https://github.com/ECMWFCode4Earth/challenges_2023/issues/3)
* [Code](https://github.com/ECMWFCode4Earth/data-scruncher-extra)

Geospatial data can vary in its information density from one part of the world to another. A dataset containing streets will be very dense in cities but contains little information in remote places like the Alps or even the ocean. The same is also true for datasets about the ocean or the atmosphere. The variability of sea surface temperatures and currents is much larger in the vicinity of the golf stream than in the middle of the Atlantic basin. This variability might also change in time. A hurricane, for example, has a lot of variability in winds, temperature and rain rates, and travels in addition across entire ocean basins.

The challenge of this project is to improve `xbitinfo` to preserve the natural variability of these features but not to save random noise where the real information density is rather low. This means in particular that the number of bits needed to preserve in compression changes with location. A hurricane has a different information density than a same-sized area in the steadily blowing trade-wind regimes. Compressibility of climate data therefore can change drastically in time and space, which we want to exploit.

Currently in the bitinformation framework, to preserve all real information, the maximum information content calculated by `xbitinfo` needs to be used for the entire dataset. However, bitinformation can also be calculated on subsets, such that the ‘boring’ parts can therefore be more efficiently compressed.

### MENTORS

* Miha Razinger
* Juan Jose Dominguez
* Milan Klöwer
* Hauke Schulz
