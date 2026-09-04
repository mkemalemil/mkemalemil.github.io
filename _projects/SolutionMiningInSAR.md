---
layout: page
title: Solution-mining induced land subsidence
description: An interactive visualization of InSAR-derived land motion associated with solution mining at Eti Soda site, Ankara, Turkey
img: assets/img/SolutionMiningInSAR.png
importance: 3
category: work
related_publications: false
---

This demo app visualizes InSAR-derived land motion associated with solution mining at the Eti Soda site in Ankara, Turkey. It uses Sentinel-1 data collected between 2014 and 2024, with interferograms generated through the [HyP3 platform](https://hyp3-docs.asf.alaska.edu/) and time series analyses performed with [MintPy](https://github.com/insarlab/MintPy).

### Quick Links

- [**Live demo app**](https://www.esrs.wmich.edu/webmap/SolutionMining/EtiSoda/)

#### Tools

- [**HyP3**](https://hyp3-docs.asf.alaska.edu/)
- [**MintPy**](https://github.com/insarlab/MintPy)

### Overview

This web application provides an interactive platform to visualize surface displacement patterns and time series. It demonstrates how remote sensing can help identify deformation linked to solution mining and support early interpretation of subsidence or uplift patterns.

This visualization is preliminary. The InSAR-based estimates are not yet calibrated and still require field validation, data refinement, and further analysis before they should be interpreted as definitive results.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <a href="https://www.esrs.wmich.edu/webmap/SolutionMining/EtiSoda/" target="_blank" rel="noopener">
            {% include figure.liquid loading="eager" path="assets/img/SolutionMiningInSAR.png" title="Eti Maden solution-mining deformation demo" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
</div>
<div class="caption">
    Demo view of the web application highlighting InSAR-derived land motion patterns associated with solution mining.
</div>
