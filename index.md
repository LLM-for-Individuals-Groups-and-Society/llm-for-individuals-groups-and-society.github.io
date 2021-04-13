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
panelists:
    - image_path: assets/images/guennemann.jpg
      alt: "Stephan Günnemann"
      excerpt: >
        **Stephan Günnemann**<br>
        Technical University of Munich
    - image_path: assets/images/yizhou.jpg
      alt: "Yizhou Sun"
      excerpt: >
        **Yizhou Sun**<br>
        University of California, Los Angeles
    - image_path: assets/images/Jie.jpg
      alt: "Jie Tang"
      excerpt: >
        **Jie Tang**<br>
        Tsinghua University

keynote: # Not ready yet
    - image_path: /assets/images/jure.jpg
      alt: "Jure Leskovec"
      title: "Jure Leskovec"
      excerpt: >
        ***Stanford University***

        
        Talk title and abstract TBD. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>

invited-talk: 
    - image_path: /assets/images/leman.jpg
      alt: "Leman Akoglu"
      title: "Leman Akoglu"
      excerpt: >
        ***Carnegie Mellon University***


        **Issues with Propagation Based Models for Graph-Level Outlier Detection**


        **Abstract**: 
        Graph-Level Outlier Detection (GLOD) is the task of identifying unusual graphs within a graph database, 
        which received little attention compared to node-level detection in a single graph. As propagation based 
        graph embedding by GNNs and graph kernels achieved promising results on another graph-level task, i.e. 
        graph classification, we study applying those models to tackle GLOD. Instead of developing new models, 
        this paper identifies and delves into a fundamental and intriguing issue with applying propagation based 
        models to GLOD, with evaluation conducted on repurposed binary graph classification datasets where one class 
        is down-sampled as outlier. We find that ROC-AUC performance of the models changes significantly 
        (“flips” from high to low) depending on which class is down-sampled. Interestingly, ROC-AUCs on these two 
        variants approximately sum to 1 and their performance gap is amplified with increasing propagations. 
        We carefully study the graph embedding space produced by propagation based models and find two driving factors: 
        (1) disparity between within-class densities which is amplified by propagation, and 
        (2) overlapping support (mixing of embeddings) across classes. Our study sheds light onto the effects of using 
        graph propagation based models and classification datasets for outlier detection for the first time.
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

<script>
if (!sessionStorage.getItem('timezone')) {
  var tz = jstz.determine() || 'UTC';
  sessionStorage.setItem('timezone', tz.name());
}
var currTz = sessionStorage.getItem('timezone');
var startTime = moment("2021-04-16T13:00:00Z");
var tzTime = startTime.tz(currTz)
</script>

# Overview

Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks, 
we call for contributions that introduce novel ML tasks or novel graph-structured data which have the potential to 
(i) help understand the performance and limitations of graph representation models on diverse sets of problems and 
(ii) support benchmark evaluations for various models.

Our previous call for papers can be found [here](/call-for-papers). 

# Schedule

All the time listed below are in Ljubljana time (Central European Summer Time, UTC+2). The workshop will start at Apr 16, 2021 3:00pm CEST<span id="viewerTime"></span>.

| Time (UTC+2) | Agenda |
| ----------------- | ------------ |
| **3:00-3:10pm**    | **Opening remarks** |
| **3:10-3:30pm**    | **[Invited talk by Leman Akoglu](#Leman+Akoglu) (20 min)**: <br> Issues with Propagation Based Models for Graph-Level Outlier Detection |
| **3:30-4:00pm**    | **Contributed talks (12 min + 3-min Q&A for each):**<br>\- Reproducible Evaluations of Network Representation Learning Models Using EvalNE<br>\- Catastrophic Forgetting in Deep Graph Networks: an Introductory Benchmark for Graph Classification |
| **4:00-4:05pm**    | **Break (5 min)** |
| **4:05-4:40pm**    | **Spotlight talks (11 x 3 min)** |
| **4:40-5:30pm**    | **Interactive poster session & Break (50 min)** |
| **5:30-6:25pm**    | **[Panel discussion](#panelists) (55 min):<br>Stephan Günnemann, Yizhou Sun, Jie Tang**|
| **6:25-6:30pm**    | **Break (5 min)** |
| **6:30-7:10pm**    | **[Keynote by Jure Leskovec](#Jure+Leskovec) (40 min)** |
| **7:10-7:20pm**    | **Closing remarks** |

<script>
  document.getElementById("viewerTime").innerHTML = " (" + tzTime.format('MMM DD h:mma z') + ")"
</script>

# Invited Speakers
<!-- ![image-left](/assets/images/jure.jpg){: .align-left} -->

<!-- - Speaker: [Jure Leskovec](https://cs.stanford.edu/~jure/), Stanford University
- Title: Issues with Propagation Based Models for Graph-Level Outlier Detection
- Abstract: TBA -->
{% include feature_row id="keynote" type="left" %}
{% include feature_row id="invited-talk" type="left" %}

# Panelists
{% include feature_row id="panelists" %}

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
{% capture organizers %}
- **[Jiaqi Ma](http://www.jiaqima.com/)** (University of Michigan)
- **[Jiong Zhu](https://www.jiongzhu.net/)** (University of Michigan)
- **[Yuxiao Dong](https://ericdongyx.github.io/)** (Facebook AI)
- **[Danai Koutra](https://web.eecs.umich.edu/~dkoutra/)** (University of Michigan)
- **[Qiaozhu Mei](http://www-personal.umich.edu/~qmei/)** (University of Michigan)
{% endcapture %}

<div class="small">
{{ organizers | markdownify }}
</div>
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