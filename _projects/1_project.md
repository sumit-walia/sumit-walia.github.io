---
layout: page
title: TALCO
description: Tiling Genome Sequence Alignment using Convergence of Traceback Pointers
img: /TALCO-image.png
importance: 1
category: On-going Projects
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TALCO-image.png" title="TALCO" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-9 mt-md-0">
        **TALCO** is a novel method for **T**iling genome sequence **AL**ignment using **CO**nvergence of traceback pointers, that, similar to prior tiling techniques, maintains a **constant memory** footprint during the acceleration step independent of alignment length; however, unlike previous techniques, TALCO also ensures **optimal alignments under banding constraints**. TALCO does this by leveraging the convergence of traceback paths beyond a tile to a single point on the boundary of that tile – a strategy that seems to generalize well to a broad set of sequence alignment algorithms. To demonstrate generalizability, we apply TALCO to widely-used banded sequence alignment algorithms, X-Drop and WFA-Adapt.
    </div>
</div>
