---
permalink: /glb2023/call-for-papers
title: "Call for Papers - GLB 2022"
layout: splash
browser-title: "GLB 2022"
masthead-title: "GLB 2022"
masthead-subtitle: "@TheWebConf 2022"
masthead-url: "/"
# classes: wide
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/images/glb-bg.jpg
---

{% capture notice-text %}
**You are viewing the archived site for GLB 2022.** To learn more on the latest edition of the workshop, [click here](/).
{% endcapture %}

<!-- <div class="notice--warning">
  <!-- <h4 class="no_toc">Notice Headline:</h4> ~~>
  {{ notice-text | markdownify }}
</div> -->


We encourage paper submissions relevant to (but not limited to) the following topics:

- **Real-World Datasets**: Novel real-world graph-structured datasets---especially large-scale, application-oriented, and publicly accessible datasets. 
- **Synthetic Datasets**: Synthetic graph-structured datasets that are well-supported by graph theory, network science, or empirical studies, and can be used to reveal limitations of existing graph learning methods.
- **Software Packages**: Software packages which enable streamlined benchmarking large-scale online graphs, crawling or crowdsourcing of graph data, and generation of realistic synthetic graphs. 
- **Data Collection**: Novel approaches to collect and annotate graph-structured data. Crowdsourcing and sampling methods on large networks.
- **Data Processing**: Novel approaches to clean and impute noisy/missing graph-structured data. Data augmentation approaches for self-supervision. 
- **Tasks**: New learning tasks and applications on different types of graphs, at different levels (e.g., node, edge, subgraph, graph), with a special focus on real-world science-, health- or industry-oriented problems.
- **Metrics**: New evaluation procedures and metrics of graph learning associated with the various tasks and datasets. 
- **Benchmarks**: Works benchmarking multiple existing GNNs on non-trivial tasks and datasets. We explicitly encourage works that reveal limitations of existing models or optimize matches between network designs and problems. 
- **Task Taxonomy**: Discussions towards a more comprehensive and fine-grained taxonomy of graph learning tasks.

The contributed papers will be evaluated based on the meaningfulness of proposed tasks or datasets, their potential to become new benchmarks for graph learning, and their contributions to understanding the pros and cons of state-of-the-art graph learning techniques. 

## Important Dates
All deadlines are in **Anywhere on Earth (AoE)** time zone.
- **Submission deadline**: ~~May 30, 2023~~ Extended to Jun. 8, 2023
- **Acceptance notification**: ~~Jun. 13, 2023~~ ~~Jun. 23, 2023~~ Jun. 27, 2023
- **Camera-ready version due**: ~~Jun. 27, 2023~~ Jul. 5, 2023
- **Workshop**: Aug. 6, 2023

## Submission
Abstracts and papers can be submitted through CMT: <br>
[https://cmt3.research.microsoft.com/GLB2023](https://cmt3.research.microsoft.com/GLB2023)

## Format

- For unpublished submissions, please submit a paper no longer than *4 pages* (excluding references and the appendices) using [the ACM “sigconf” LaTeX template](https://www.overleaf.com/latex/templates/association-for-computing-machinery-acm-sig-proceedings-template/bmvfhcdnxfty) (see [the instruction by KDD 2023](https://kdd.org/kdd2023/call-for-research-track-papers/)). 
The recommend setting for LaTex file manuscript is
```latex
\documentclass[sigconf, review]{acmart}
```
If your submission includes appendices, it should be included in the same file with the main manuscript.
- The submission is single-blinded for the ease of data and code sharing. The reviewers are anonymized but the authors do not need to be anonymized in the submission. 
- This workshop is *non-archival*. Relevant findings that have been recently published are also welcome. For already published submissions, the paper can be submitted in the original format. These submissions will be very lightly reviewed for their relevance to this workshop.
- Authors are *strongly encouraged* to include the corresponding datasets and code as supplementary materials in their submission. For large datasets or repositories, the authors can provide an external link through Github, Google drive, Dropbox, OneDrive, or Box. We limit the choice of storage platforms for security considerations. Please email the organizers if none of the listed platforms works for you.
We also encourage authors to contribute new datasets and tasks to our benchmark curation platform, [Graph Learning Indexer (GLI)](https://github.com/Graph-Learning-Benchmarks/gli). 
- If the data cannot be made publicly available, an extra section is required to illustrate how the results of the established benchmark may generalize to other graph data.