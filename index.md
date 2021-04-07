---
title: "Workshop on Graph Learning Benchmarks <br>(GLB 2021)"
browser-title: "Home"
layout: splash
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/images/glb-bg.jpg
organizers: # Not ready yet
    - image_path: /assets/images/danai.jpg
      alt: "Danai Koutra"
      excerpt: "**Danai Koutra**"
    - image_path: /assets/images/danai.jpg
      alt: "Danai Koutra"
      excerpt: "**Danai Koutra**"
    - image_path: /assets/images/danai.jpg
      alt: "Danai Koutra"
      excerpt: "**Danai Koutra**"
    - image_path: /assets/images/danai.jpg
      alt: "Danai Koutra"
      excerpt: "**Danai Koutra**"
    - image_path: /assets/images/danai.jpg
      alt: "Danai Koutra"
      excerpt: "**Danai Koutra**"
keynote: # Not ready yet
    - image_path: /assets/images/jure.jpg
      alt: "Jure Leskovec"
      excerpt: |
        - **Speaker**: Jure Leskovec <br>
        - **Title**: TBA
        - **Abstract**: TBA
---

<!-- {% capture notice-text %}
This is an example notice using Markdown.

* Bullet point 1
* Bullet point 2
{% endcapture %}

<div class="notice--info">
  <h4 class="no_toc">Notice Headline:</h4>
  {{ notice-text | markdownify }}
</div> -->


# Overview

Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks, 
we call for contributions that introduce novel ML tasks or novel graph-structured data which have the potential to 
(i) help understand the performance and limitations of graph representation models on diverse sets of problems and 
(ii) support benchmark evaluations for various models.

We especially (but not exclusively) call for submissions which will contribute to at least one of the following:

- **New Graph Datasets**: Novel graph-structured datasets—especially large-scale, application-oriented, and publicly accessible datasets. We also welcome methods and software packages that enable streamlined benchmarking of large-scale graph data, crawling or crowdsourcing for labeled graph data, and generation of realistic synthetic graphs.
- **New ML Tasks**: New ML tasks and applications on different types of graphs, at different levels (e.g., node, edge, subgraph or graph), with a special focus on real-world and industry-valued problems.
- **New Metrics**: New evaluation procedures and metrics of graph learning associated with the various tasks and datasets.
- **Benchmarking Studies**: Studies that benchmark multiple graph ML methods (especially graph neural networks) on non-trivial tasks and datasets. We explicitly encourage works that reveal limitations of existing models, optimize matches between model design and problems, and other novel findings about the behaviors of existing models on various tasks or datasets.

The acceptance of the contributed papers is decided on the meaningfulness of the established graph learning tasks/datasets and their potential of being formalized into new benchmarks, rather than the performance of ML models (old or new) on these tasks. We particularly welcome contributions of **negative results** of popular, state-of-the-art models on a new task/dataset, as these provide novel insights to the community’s understanding of the meta-knowledge of graph ML. 

Our previous call for papers can be found [here](/call-for-papers). 

# Keynote Speaker
<!-- ![image-left](/assets/images/jure.jpg){: .align-left} -->

- Speaker: [Jure Leskovec](https://cs.stanford.edu/~jure/), Stanford University
- Title: TBA
- Abstract: TBA

<!-- {% include feature_row id="keynote" type="left" %} -->

# Accepted Papers
<ul>
{% for pubitem in site.data.papers %}
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
</ul>

# Organizers
- [Jiaqi Ma](http://www.jiaqima.com/), University of Michigan
- [Jiong Zhu](https://www.jiongzhu.net/), University of Michigan
- [Yuxiao Dong](https://ericdongyx.github.io/), Facebook AI
- [Danai Koutra](https://web.eecs.umich.edu/~dkoutra/), University of Michigan
- [Qiaozhu Mei](http://www-personal.umich.edu/~qmei/), University of Michigan

<!-- {% include feature_row id="organizers" %} -->

# Program Committee
<div class="small row-two-columns">
<div class="column-half">
<ul>
{% for people in site.data.pc-members limit:10 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
<div class="column-half">
<ul>
{% for people in site.data.pc-members offset:10 %}
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
</script>