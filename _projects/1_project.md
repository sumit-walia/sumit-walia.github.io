---
layout: page
title: TALCO
description: Tiling Genome Sequence Alignment using Convergence of Traceback Pointers
img: assets/img/talco.png
importance: 1
category: On-going Projects
---

<div class="row">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/talco.gif" height="480" title="TALCO" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-9 mt-3 mt-md-0">
        <b>TALCO</b> is a novel method for <b>T</b>iling genome sequence <b>AL</b>ignment using <b>CO</b>nvergence of traceback pointers, that, similar to prior tiling techniques, maintains a <b>constant memory</b> footprint during the acceleration step independent of alignment length; however, unlike previous techniques, TALCO also ensures <b>optimal alignments under banding constraints</b>. TALCO does this by leveraging the convergence of traceback paths beyond a tile to a single point on the boundary of that tile – a strategy that seems to generalize well to a broad set of sequence alignment algorithms. To demonstrate generalizability, we apply TALCO to widely-used banded sequence alignment algorithms, X-Drop and WFA-Adapt. [<a href="../_data/TALCO.pdf">Paper</a>]
    </div>
</div>
