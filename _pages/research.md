---
layout: page
title: Research
permalink: /research/
description: 
nav: true
---

---

#### <b>Compressive Pangenomics using PanMANs</b>
<p><b>Nature Genetics (Accepted) </b>
| GitHub <a href="https://github.com/TurakhiaLab/panman" title="GitHub"><i class="fab fa-github"></i></a>
| Wiki <a href="https://turakhia.ucsd.edu/panman/" title="Documentation"><i class="fas fa-book"></i></a>
| BioRxiv <a href="https://www.biorxiv.org/content/10.1101/2024.07.02.601807v2" title="Paper"><i class="fas fa-newspaper"></i></a></p>
<strong>Scientific motivation:</strong> <br>
Genomics is moving from studying a single reference genome to analyzing entire pangenomes, representing thousands of individuals. While scientifically powerful, these datasets are extremely large and challenging to store and process efficiently.

<strong>What PanMAN enables:</strong><br>
PanMAN introduces a compact representation of large genomic populations using mutation-annotated network structures that preserve meaningful evolutionary and biological information while dramatically shrinking data size.

<strong>Overall contributions:</strong>
<ul>
  <li>Developed a novel data structure and file format to store shared mutational and evolutionary information at scale (millions of genome sequences)</li>
  <li>Enabled storage and analysis of ultra-large genomic datasets by reducing memory and storage requirements by more than <b>600X</b> compared to common formats.</li>
  <li>Preserved biological interpretability while making large-scale pangenomic studies computationally practical.</li>
</ul>

---

#### <b>Ultrafast & Ultralarge Phylogenetic Tree Construction using DIPPER</b>
<p><b>Nature Computational Science (Under Review) </b>
| GitHub <a href="https://github.com/TurakhiaLab/dipper" title="GitHub"><i class="fab fa-github"></i></a>
| Wiki <a href="https://turakhia.ucsd.edu/DIPPER/" title="Documentation"><i class="fas fa-book"></i></a>
| BioRxiv <a href="https://www.biorxiv.org/content/10.1101/2025.08.12.669583v1" title="Paper"><i class="fas fa-newspaper"></i></a></p>
<strong>Scientific motivation:</strong><br>
Phylogenetic trees help scientists understand how species, pathogens, and viral strains evolve. However, traditional tools do not scale well to the millions of genomes now commonly generated in large-scale studies.

<strong>What DIPPER enables:</strong><br>
DIPPER is designed to construct very large phylogenetic trees extremely quickly, supporting real-time biological discovery and global-scale genomic surveillance.

<strong>Overall contribution of this work:</strong>
<ul>
  <li>Delivered a high-performance GPU-accelerated tool capable of scaling to ultra-large datasets (up to 10 million sequences).</li>
  <li>Introduced memory-efficient strategies (such as divide-and-conquer and on-the-fly distance computation) that allow trees to be built without exceeding the limited GPU capacity.</li>
  <li>Achieved up to <b>40X</b> speedup while improving memory efficiency by up to <b>6X</b> over state-of-the-art tools, expanding what is computationally feasible in evolutionary genomics.</li>
</ul>

---

#### <b>Ultrafast & Ultralarge Multiple Sequence Alignment using TWILIGHT</b>
<p><b>ISMB'25 | Bioinformatics</b> <a href="https://academic.oup.com/bioinformatics/article/41/Supplement_1/i332/8199405" title="Paper"><i class="fas fa-newspaper"></i></a>
| GitHub <a href="https://github.com/TurakhiaLab/twilight" title="GitHub"><i class="fab fa-github"></i></a>
| Wiki <a href="https://turakhia.ucsd.edu/TWILIGHT/" title="Documentation"><i class="fas fa-book"></i></a></p>
<strong>Scientific motivation:</strong><br>
Multiple sequence alignment (MSA) is a cornerstone of genomic analysis, but aligning millions of sequences traditionally requires enormous compute time and resources.

<strong>What TWILIGHT enables:</strong><br>
TWILIGHT makes it possible to perform massive, high-quality multiple sequence alignments efficiently, supporting applications in evolution, disease tracking, and large-scale biological discovery.

<strong>Overall contribution of this work:</strong>
<ul>
  <li>Introduced a heterogeneous CPU–GPU execution pipeline that scales alignment to previously impractical dataset sizes - up to millions of sequences.</li>
  <li>Utilized parallel processing, asynchronous data transfer, and dynamic load balancing to maximize throughput.</li>
  <li>Delivered over <b>50X</b> speedup while maintaining high alignment accuracy, making large-scale MSA much more practical for real research workflows.</li>
</ul>

---

#### <b>High-Performance Genome Sequence Alignment using TALCO</b>
<p><b>HPCA'24</b> <a href="https://ieeexplore.ieee.org/document/10476438" title="Paper"><i class="fas fa-newspaper"></i></a>
| GitHub <a href="https://github.com/TurakhiaLab/talco" title="GitHub"><i class="fab fa-github"></i></a>/p>
<strong>Scientific motivation:</strong><br>
Genome sequence alignment is fundamental in bioinformatics, yet most approaches struggle to simultaneously achieve high accuracy, high speed, and energy efficiency.

<strong>What TALCO enables:</strong><br>
TALCO introduces a tiling-based alignment strategy leveraging the convergence of traceback pointers to deliver highly accurate alignments with exceptional computational efficiency.

<strong>Overall contribution of this work:</strong>
<ul>
  <li>Designed a hardware accelerator for TALCO alignment strategy and deployed it on AWS F1 cloud infrastructure.</li>
  <li>Demonstrated approximately <b>2000X</b> improvement in throughput-per-Watt compared to leading CPU/GPU methods.</li>
  <li>Recognized as an <b>HPCA Best Paper Nominee</b>, underscoring its impact and significance.</li>
</ul>
