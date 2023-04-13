---
permalink: /glb2023
title: "Workshop on Graph Learning Benchmarks <br>(GLB 2023)"
excerpt: Aug. 7, 2023 - Long Beach, CA, USA <br> Held in conjunction with <a href="https://kdd.org/kdd2023/">KDD 2023</a>
browser-title: "GLB 2023"
masthead-title: "GLB 2023"
masthead-subtitle: "@KDD 2023"
masthead-url: "/"
layout: splash
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/images/glb-bg.jpg
navigation:
  - title: "CfP"
    url: /glb2023#call-for-papers
  - title: "Important Dates"
    url: /glb2023#important-dates
  - title: "Submission"
    url: /glb2023#submission
  # - title: "Schedule"
  #   url: /glb2022#registration
  # - title: "Keynotes"
  #   url: /glb2022#keynote-speakers
  # - title: "Panelists"
  #   url: /glb2022#panelists
  # - title: "Accepted Papers"
  #   url: /glb2022#accepted-papers
  - title: "Organization"
    url: /glb2023#organizers
  - title: "Past Editions"
    url: /all-editions
---


<!-- <div class="notice--info">
  <!-- <h4 class="no_toc">Notice Headline:</h4> ~~>
  {{ notice-text | markdownify }}
</div> -->

<script>
if (!sessionStorage.getItem('timezone')) {
  var tz = jstz.determine() || 'UTC';
  sessionStorage.setItem('timezone', tz.name());
}
var currTz = sessionStorage.getItem('timezone');
var startTime = moment("2022-04-26T08:45:00Z");
var tzTime = startTime.tz(currTz)
</script>

# Overview

GLB 2023 is the third edition of the Workshop of the Graph Learning Benchmarks, encouraged by the success of [the previous editions](/all-editions). 
Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks,
we call for contributions that establish novel ML tasks on novel graph-structured data which have the potential to
(i) increase the diversity of graph learning benchmarks,
(ii) identify new demands of graph machine learning in general, and 
(iii) gain a better synergy of how concrete techniques perform on these benchmarks. 
We also welcome contributions on data-centric graph learning, such as novel approaches to collect, annotate, clean, augment, and sythesize graph-structured data.

GLB 2023 will be a **non-archival** workshop; we are excited to host this edition **in person** in conjunction with [**KDD 2023**](https://kdd.org/kdd2023/).

<!-- Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks, 
we call for contributions that introduce novel ML tasks or novel graph-structured data which have the potential to 
(i) help understand the performance and limitations of graph representation models on diverse sets of problems and 
(ii) support benchmark evaluations for various models. -->

<!-- Our previous call for papers can be found [here](/glb2023/call-for-papers).  -->

# Call for Papers

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
- **Submission deadline**: May 26, 2023 
- **Acceptance notification**: Jun. 13, 2023
- **Camera-ready version due**: Jun. 27, 2023
- **Workshop**: Aug. 7, 2023

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

<!-- # Keynote Speakers -->

<!-- # Accepted Papers
<ul>
{% for pubitem in site.data.papers2023 %}
    <li> {{ pubitem.title | markdownify | remove: '<p>' | remove: '</p>' | strip }} <br>
    <div class="small">
    <i> {{ pubitem.authors | markdownify | remove: '<p>' | remove: '</p>' | strip }} </i> 
    </div>
    {% if pubitem.abstract %} 
    <a class="btn btn--small btn--info collapsible">Abstract</a> 
    <div class="btn-content small">
        <b>Abstract</b>: {{ pubitem.abstract }}
    </div>
    {% endif %}
    {% if pubitem.PDF %} <a href="{{ pubitem.PDF }}" class="btn btn--small btn--info">PDF</a>{% endif %}
    {% if pubitem.code %} <a href="{{ pubitem.code }}" class="btn btn--small btn--info">
    {% if pubitem.new_dataset %} Code & Datasets {% else %} Code {% endif %} </a>{% endif %}
    </li>
{% endfor %}
</ul> -->

# Organizers
Please contact us through <a target="_blank" href="https://mailhide.io/e/5RV52Tlm">this email address</a> if you have any questions.

{% capture organizers %}
A list of organizers can also be found [here](https://airtable.com/shrwvG9wYqjrbXq0s/tblLXlCDQlpCBK6lR?backgroundColor=purple).
{% endcapture %}

<div class="small">
{{ organizers | markdownify }}
</div>

<style>
    #organizer-wrap { width: 100%; height: 750; padding: 0; overflow: hidden; }
    #organizer-frame { width: 107%; height: 750; background: transparent; border: 1px solid #ccc; }
    #organizer-frame {
        -ms-zoom: 0.93;
        -moz-transform: scale(0.93);
        -moz-transform-origin: 0 0;
        -o-transform: scale(0.93);
        -o-transform-origin: 0 0;
        -webkit-transform: scale(0.93);
        -webkit-transform-origin: 0 0;
    }
</style>
<div id="organizer-wrap">
<iframe id="organizer-frame" class="airtable-embed" src="https://airtable.com/embed/shrwvG9wYqjrbXq0s?backgroundColor=purple" frameborder="0" onmousewheel="" height="750" style="background: transparent; border: 1px solid #ccc;"></iframe>
</div>

<!-- <iframe class="airtable-embed" src="https://airtable.com/embed/shrwvG9wYqjrbXq0s?backgroundColor=purple" frameborder="0" onmousewheel="" width="106%" height="750" style="background: transparent; border: 1px solid #ccc;"></iframe> -->


<!-- # Program Committee
<div class="small row-two-columns">
<div class="column-half">
<ul>
{% for people in site.data.pc-members2022 limit:12 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
<div class="column-half">
<ul>
{% for people in site.data.pc-members2022 offset:12 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
</div>

<script>
    var coll = document.getElementsByClassName("collapsible");
    var i;

    for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
        content.style.display = "none";
        } else {
        content.style.display = "block";
        }
    });
    }
</script> -->
