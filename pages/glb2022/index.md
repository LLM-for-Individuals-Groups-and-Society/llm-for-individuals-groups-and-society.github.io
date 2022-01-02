---
permalink: /glb2022
title: "Workshop on Graph Learning Benchmarks <br>(GLB 2022)"
browser-title: "Home"
masthead-title: "GLB 2022"
masthead-subtitle: "@TheWebConf 2022"
masthead-url: "/"
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


        **Open Graph Benchmark Large-Scale Challenge**
        
        
        We first present the [Open Graph Benchmark (OGB)](https://ogb.stanford.edu), a diverse set of challenging and realistic benchmark datasets to facilitate scalable, robust, and reproducible graph machine learning (ML) research. OGB datasets are larger than existing graph benchmarks, encompass multiple important graph ML tasks, and cover a diverse range of domains. We then present OGB’s new initiative on a Large-Scale Challenge ([OGB-LSC](https://ogb.stanford.edu/kddcup2021)) at the KDD Cup 2021. OGB-LSC provides datasets that represent modern industrial-scale large graphs. We provide dedicated baseline experiments, scaling up expressive graph ML models to the massive datasets. We show that the expressive models significantly outperform simple scalable baselines, indicating an opportunity for dedicated efforts to further improve graph ML at scale.

invited-talk: 
    - image_path: /assets/images/leman.jpg
      alt: "Leman Akoglu"
      title: "Leman Akoglu"
      excerpt: >
        ***Carnegie Mellon University***


        **On Using Classification Datasets to Evaluate Graph Outlier Detection: Peculiar Observations and New Insights**


        **Abstract**: 
        It is common practice of the outlier mining community to repurpose classification datasets toward evaluating various detection models. To that end, often a binary classification dataset is used, where samples from (typically, the larger) one of the classes are designated as the ‘inlier’ samples, and the other class is substantially down-sampled to create the (ground-truth) ‘outlier’ samples. In this study, we identify an intriguing issue with repurposing graph classification datasets for graph outlier detection in this manner. Surprisingly, the detection performance of outlier models depends significantly on which class is down-sampled; put differently, accuracy often “flips” from high to low depending on which of the classes is down-sampled to represent the outlier samples. The problem is notably exacerbated particularly for a certain family of propagation based outlier detection models. Through careful analysis, we show that this issue mainly stems from disparate within-class sample similarity – which is amplified by various propagation based models – that impacts key characteristics of inlier/outlier distributions and indirectly, the difficulty of the outlier detection task and hence performance outcomes. With this study, we aim to draw attention to this (to our knowledge) previously-unnoticed issue, as it has implications for fair and effective evaluation of detection models, and hope that it will motivate the design of better evaluation benchmarks for outlier detection. Finally, we discuss the possibly overarching implications of using propagation based models on datasets with disparate within-class sample similarity beyond outlier detection, specifically for graph classification and graph-level clustering tasks. 
---

{% capture notice-text %}
**To join our workshop on live**: visit our room at the [MiTeam Platform](https://theweb.miteam.eu/asset/9Ffmuifa4MAzKPa6o) at TheWebConf 2021!
{% endcapture %}

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
var startTime = moment("2021-04-16T13:00:00Z");
var tzTime = startTime.tz(currTz)
</script>

# Call for Papers

GLB 2022 is the second edition of the Workshop of the Graph Learning Benchmarks, encouraged by the success of [GLB 2021](/glb2021). 
Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks,
we propose call for contributions that establish novel ML tasks on novel graph-structured data which have the potential to 
(i) identifying systematic failure modes of existing GNNs and providing new technical challenges for the development of new models which highlight diverse future directions, 
(ii) raising the attention of the synergy of graph learning, and
(iii) crowdsourcing benchmark datasets for various tasks of graph ML.

<!-- Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks, 
we call for contributions that introduce novel ML tasks or novel graph-structured data which have the potential to 
(i) help understand the performance and limitations of graph representation models on diverse sets of problems and 
(ii) support benchmark evaluations for various models. -->

We especially (but not exclusively) call for submissions which will contribute to at least one of the following:

- **Real-World Datasets**: Novel real-world graph-structured datasets---especially large-scale, application-oriented, and publicly accessible datasets. 
- **Synthetic Datasets** (*New*): Synthetic graph-structured datasets that are well-supported by graph theory, network science, or empirical studies, and can be used to reveal limitations of existing graph learning methods.
- **Software Packages**: Software packages which enable streamlined benchmarking large-scale online graphs, crawling or crowdsourcing of graph data, and generation of realistic synthetic graphs. 
- **Tasks**: New learning tasks and applications on different types of graphs, at different levels (e.g., node, edge, and (sub)graph), with a special focus on real-world and industry-oriented problems.
- **Metrics**: New evaluation procedures and metrics of graph learning associated with the various tasks and datasets. 
- **Benchmarks**: Works benchmarking multiple existing GNNs on non-trivial tasks and datasets. We explicitly encourage works that reveal limitations of existing models or optimize matches between network designs and problems. 
- **Task Taxonomy** (*New*): Discussions towards a more comprehensive and fine-grained taxonomy of graph learning tasks.

The acceptance of the contributed papers will be decided on the meaningfulness of the established graph learning tasks or datasets and their potential of being formalized into new benchmarks, rather than the performance of ML models (old or new) on these tasks. We particularly welcome contributions of **negative results** of popular, state-of-the-art models on a new task or dataset, as these provide novel insights to the community’s understanding of the meta-knowledge of graph ML. 

*We will provide more updates on the submission deadlines and instructions.*

<!-- Our previous call for papers can be found [here](/call-for-papers).  -->

<!-- # Schedule

All the time listed below are in Ljubljana time (Central European Summer Time, UTC+2). The workshop will start at Apr 16, 2021 3:00pm CEST<span id="viewerTime"></span>.

| Time (UTC+2) | Agenda |
| ----------------- | ------------ |
| **3:00-3:10pm**    | **Opening remarks** |
| **3:10-3:30pm**    | **[Invited talk by Leman Akoglu](#Leman+Akoglu) (20 min)**: <br> On Using Classification Datasets to Evaluate Graph Outlier Detection: Peculiar Observations and New Insights |
| **3:30-4:00pm**    | **Contributed talks (12 min + 3-min Q&A for each):**<br>\- Reproducible Evaluations of Network Representation Learning Models Using EvalNE<br>\- Catastrophic Forgetting in Deep Graph Networks: an Introductory Benchmark for Graph Classification |
| **4:00-4:05pm**    | **Break (5 min)** |
| **4:05-4:40pm**    | **Spotlight talks (11 x 3 min)** |
| **4:40-5:30pm**    | **Interactive poster session & Break (50 min)** |
| **5:30-6:25pm**    | **[Panel discussion](#panelists) (55 min):<br>Stephan Günnemann, Yizhou Sun, Jie Tang**|
| **6:25-6:30pm**    | **Break (5 min)** |
| **6:30-7:10pm**    | **[Keynote by Jure Leskovec](#Jure+Leskovec) (40 min)**: <br> Open Graph Benchmark Large-Scale Challenge |
| **7:10-7:20pm**    | **Closing remarks** | -->

<script>
  document.getElementById("viewerTime").innerHTML = " (" + tzTime.format('MMM DD h:mma z') + ")"
</script>

<!-- # Invited Speakers

{% include feature_row id="keynote" type="left" %}
{% include feature_row id="invited-talk" type="left" %} -->

<!-- # Panelists
{% include feature_row id="panelists" %} -->

<!-- # Accepted Papers
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
</ul> -->

# Organizers
{% capture organizers %}
- **[Jiaqi Ma](http://www.jiaqima.com/)** (University of Michigan)
- **[Jiong Zhu](https://www.jiongzhu.net/)** (University of Michigan)
- **[Anton Tsitsulin](http://tsitsul.in/)** (Google Research)
- **[Marinka Zitnik](https://zitniklab.hms.harvard.edu/bio/)** (Harvard University)
{% endcapture %}

<div class="small">
{{ organizers | markdownify }}
</div>
<!-- {% include feature_row id="organizers" %} -->

# Advisory Board
{% capture advisory-board %}
- **[Yuxiao Dong](https://ericdongyx.github.io/)** (Facebook AI)
- **[Danai Koutra](https://web.eecs.umich.edu/~dkoutra/)** (University of Michigan)
- **[Qiaozhu Mei](http://www-personal.umich.edu/~qmei/)** (University of Michigan)
{% endcapture %}

<div class="small">
{{ advisory-board | markdownify }}
</div>

<!-- # Program Committee
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
</script> -->
