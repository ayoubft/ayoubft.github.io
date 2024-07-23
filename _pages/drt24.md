---
layout: archive
title: "DRT Conference 2024 (Barcelona)"
permalink: /drt24/
author_profile: true
---

# Mapping of Geological Fractures: A CNN Approach

## Poster download

Download poster: [PDF (30.5 MB)](../files/pdf/DRT24-A0.pdf), [optimized PDF (1.4 MB)](../files/pdf/DRT24-A0-opt.pdf), [PPT](https://unils-my.sharepoint.com/:p:/g/personal/ayoub_fatihi_unil_ch/EbEqG_wtAZJGvxNP9ozopkcBkuNuRstNcU3a2xYdjAFzDQ?e=FBXIkU) (to use as template)

## Interactive comparison

<!-- Credits: https://img-comparison-slider.sneas.io/examples.html -->
<script defer src="https://cdn.jsdelivr.net/npm/img-comparison-slider@8/dist/index.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/img-comparison-slider@8/dist/styles.css" />

<style>
    .slider-example-focus:focus {
        outline: none;
        box-shadow: 0px 0px 15px 5px #736D1A;
    }
</style>

### Ground truth

<img-comparison-slider class="slider-example-focus">
    <img slot="first" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3-gt.png" />
    <img slot="second" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3.png" />
    <svg slot="handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
        <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#736D1A" vector-effect="non-scaling-stroke"></path>
    </svg>
</img-comparison-slider>

### DeeplabV3+

<img-comparison-slider class="slider-example-focus">
    <img slot="first" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3-dlv3p.png" />
    <img slot="second" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3.png" />
    <svg slot="handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
        <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#736D1A" vector-effect="non-scaling-stroke"></path>
    </svg>
</img-comparison-slider>

### PAN (Pyramid Attention Network)

<img-comparison-slider class="slider-example-focus">
    <img slot="first" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3-pan.png" />
    <img slot="second" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3.png" />
    <svg slot="handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
        <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1"
            fill="#736D1A" vector-effect="non-scaling-stroke"></path>
    </svg>
</img-comparison-slider>

### U-Net

<img-comparison-slider class="slider-example-focus">
    <img slot="first" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3-unet.png" />
    <img slot="second" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3.png" />
    <svg slot="handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
        <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#736D1A" vector-effect="non-scaling-stroke"></path>
    </svg>
</img-comparison-slider>

### Manet (Multi-scale Attention Net)

<img-comparison-slider class="slider-example-focus">
    <img slot="first" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3-manet.png" />
    <img slot="second" src="https://github.com/ayoubft/ayoubft.github.io/raw/master/_data/drt24/og1_3.png" />
    <svg slot="handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
        <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#736D1A" vector-effect="non-scaling-stroke"></path>
    </svg>
</img-comparison-slider>

## References

- [1] Matthäi, Stephan K., and Mandefro Belayneh. 2004. “Fluid Flow Partitioning between Fractures and a Permeable Rock Matrix.” Geophysical Research Letters 31(7). doi: [10.1029/2003GL019027](https://doi.org/10.1029/2003GL019027).
- [2] Bemis, Sean P., Steven Micklethwaite, Darren Turner, Mike R. James, Sinan Akciz, Sam T. Thiele, and Hasnain Ali Bangash. 2014. “Ground-Based and UAV-Based Photogrammetry: A Multi-Scale, High-Resolution Mapping Tool for Structural Geology and Paleoseismology.” Journal of Structural Geology 69:163–78. doi: [10.1016/j.jsg.2014.10.007](https://doi.org/10.1016/j.jsg.2014.10.007).
- [3] Nordbäck, Nicklas, and Nikolas Ovaskainen. 2022. “UAV-Acquired Orthomosaics of Loviisa Shoreline Outcrops.” doi: [10.5281/zenodo.7077519](https://doi.org/10.5281/zenodo.7077519).
- [4] Ronneberger, Olaf, Philipp Fischer, and Thomas Brox. 2015. “U-Net: Convolutional Networks for Biomedical Image Segmentation.” Pp. 234–41 in Medical Image Computing and Computer-Assisted Intervention – MICCAI 2015, Lecture Notes in Computer Science, edited by N. Navab, J. Hornegger, W. M. Wells, and A. F. Frangi. Cham: Springer International Publishing. doi: [10.1007/978-3-319-24574-4_28](https://doi.org/10.1007/978-3-319-24574-4_28).
- [5] Chen, Liang-Chieh, Yukun Zhu, George Papandreou, Florian Schroff, and Hartwig Adam. 2018. “Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation.” doi: [10.48550/arXiv.1802.02611](https://doi.org/10.48550/arXiv.1802.02611).
- [6] Li, Hanchao, Pengfei Xiong, Jie An, and Lingxue Wang. 2018. “Pyramid Attention Network for Semantic Segmentation.” doi: [10.48550/arXiv.1805.10180](https://doi.org/10.48550/arXiv.1805.10180).
- [7] Ovaskainen, Nikolas, and Nicklas Nordbäck. 2022. “Manually Mapped Traces from UAV-Acquired Images of Loviisa Shoreline Outcrops.” doi: [10.5281/zenodo.7077846](https://doi.org/10.5281/zenodo.7077846).
- [8] Ovaskainen, Nikolas. 2023. “Fractopo: A Python Package for Fracture Network Analysis.” Journal of Open Source Software 8(85):5300. doi: [10.21105/joss.05300](https://doi.org/10.21105/joss.05300).