---
permalink: /glb2023
title: "Workshop on Graph Learning Benchmarks <br>(GLB 2023)"
excerpt: Aug. 6, 2023 - Long Beach, CA, USA <br> Held in conjunction with <a href="https://kdd.org/kdd2023/">KDD 2023</a>
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
    url: /glb2023/call-for-papers
  # - title: "Important Dates"
  #   url: /glb2023#important-dates
  # - title: "Submission"
  #   url: /glb2023#submission
  - title: "Schedule"
    url: /glb2023#schedule
  - title: "Keynotes"
    url: /glb2023#keynote-speakers
  - title: "Panelists"
    url: /glb2023#panelists
  # - title: "Accepted Papers"
  #   url: /glb2022#accepted-papers
  - title: "Organization"
    url: /glb2023#organizers
  - title: "Past Editions"
    url: /all-editions

keynote: 
    - image_path: /assets/images/glb2023/YSun.jpg
      alt: "Yizhou Sun"
      title: "Yizhou Sun"
      excerpt: |
        ***University of California, Los Angeles*** <br>
        **A Graph Benchmark Dataset for Hardware Design Automation**

      abstract: >
        In recent decades, the demand for specialized computing systems tailored to specific applications has significantly increased. This has led to the emergence of domain-specific accelerators (DSAs) implemented in either application-specific integrated circuits (ASICs) or field-programmable gate arrays (FPGAs).  High-level synthesis (HLS) aims to raise the abstraction layer in hardware design, enabling the design of domain-specific accelerators (DSAs) using C/C++ instead of hardware description languages (HDLs). Compiler directives in the form of pragmas play a crucial role in modifying the microarchitecture within the HLS framework. However, the space of possible microarchitectures grows exponentially with the number of pragmas. Moreover, the evaluation of each candidate design using the HLS tool consumes significant time, ranging from minutes to hours, leading to a time-consuming optimization process. To accelerate this process, machine learning models have been used to predict design quality in milliseconds. However, existing open-source datasets for training such models are limited in terms of design complexity and available optimizations. In this talk, we present the first benchmark dataset that addresses these limitations. In this dataset, each program is represented in the form of both control data flow graph (CDFG) and source code. For each program, we provide labels for 5 performance related metrics (e.g., latency) for each design point (pragma configuration). The benchmark consists of 42 unique programs/kernels, resulting in over 42,000 labeled designs. It contains more complex programs with a wider range of optimization pragmas, making it a comprehensive dataset for training and evaluating design quality prediction models. We conduct an extensive comparison of state-of-the-art baselines to assess their effectiveness in predicting design quality. As an ongoing project, we anticipate expanding the benchmark in terms of both quantity and variety of programs to further support the development of this field.
      
      bio: >
        Yizhou Sun is an associate professor at the department of computer science of UCLA. She received her Ph.D. in Computer Science from the University of Illinois at Urbana-Champaign in 2012. Her principal research interest is on mining graphs/networks, and more generally in data mining, machine learning, and network science, with a focus on modeling novel problems and proposing scalable algorithms for large-scale, real-world applications. She is a pioneer researcher in mining heterogeneous information network, with a recent focus on deep learning on graphs/networks. Yizhou has over 180 publications in books, journals, and major conferences. Tutorials of her research have been given in many premier conferences. She is a recipient of multiple best paper awards, ACM SIGKDD Doctoral Dissertation Award, Yahoo ACE (Academic Career Enhancement) Award, NSF CAREER Award, CS@ILLINOIS Distinguished Educator Award, Amazon Research Awards (twice), Okawa Foundation Research Award, VLDB Test of Time Award, ACM Distinguished Member, IEEE AI 10-to-Watch Award, and SDM/IBM Faculty Award.

      spaces: true

    - image_path: /assets/images/glb2023/DZheng.jpeg
      alt: "Da Zheng"
      title: "Da Zheng"
      excerpt: |
        ***Amazon*** <br>
        **Graph machine learning for industry applications with DGL and GraphStorm**

      abstract: >
        Graph machine learning (GML) is a powerful tool to model data with relations. However, there are multiple challenges when we apply GML to industry use cases. This includes 1) how to scale to graphs with billions of nodes efficiently and in a cost-effective way, 2) how to process and model complex graphs, such as heterogeneous graphs with rich text features, 3) how to make GML techniques accessible to everyone, even non-GML experts. We develop DGL/DistDGL to scale GML training efficiently. On top of DGL/DistDGL, we develop GraphStorm, an enterprise GML framework, to make large-scale GML training easy. GraphStorm provides a collection of GML model implementations and training methods to handle different types of graph data commonly encountered in the industry use cases. GraphStorm provides no-code/low-code interface so that even non-GML experts can use it easily.
      
      bio: >
        Da Zheng is a senior applied scientist at AWS AI. At AWS AI, he is building frameworks and algorithms to bring graph ML technologies into production. This includes DGL for graph neural networks (GNN), DGL-KE for knowledge graph embeddings, DistDGL for scaling GNN training to billion-scale graphs, and TGL for temporal graph neural networks. His research interest covers a wide range of areas, including high-performance computing, large-scale data analysis systems, data mining, and machine learning. Da obtained a PhD from the department of computer science at the Johns Hopkins University. During his PhD, he worked on FlashGraph and FlashR, frameworks for large-scale graph analysis and data analysis on solid-state drives (SSDs).

      spaces: true

    - image_path: /assets/images/glb2023/Bresson.jpg
      alt: "Xavier Bresson"
      title: "Xavier Bresson"
      excerpt: |
        ***National University of Singapore*** <br>
        **A Generalization of Visual Transformers and MLP-Mixer to Graphs**
      
      abstract: >
        Graph Neural Networks (GNNs) have shown great potential in the field of graph representation learning. Standard GNNs define a local message-passing mechanism which propagates information over the whole graph domain by stacking multiple layers. This paradigm suffers from two major limitations, over-squashing and poor long-range dependencies, that can be solved using global attention but significantly increases the computational cost to quadratic complexity. In this work, we propose an alternative approach to overcome these structural limitations by leveraging the ViT/MLP-Mixer architectures introduced in computer vision. We introduce a new class of GNNs, called Graph MLP-Mixer, that holds three key properties. First, they capture long-range dependency as demonstrated on the long-range LRGB datasets and mitigate the over-squashing issue on the TreeNeighbour dataset. Second, they offer memory and speed efficiency, surpassing related techniques. Third, they show high expressivity in terms of graph isomorphism as they can distinguish at least 3-WL isomorphic graphs. As a result, this novel architecture provides significantly better results over standard message-passing GNNs for molecular datasets.
      
      bio: >
        Xavier Bresson (PhD 2005, EPFL, Switzerland) is Associate Professor in Computer Science at NUS, Singapore. He is a leading researcher in the field of Graph Deep Learning, a new framework that combines graph theory and deep learning techniques to tackle complex data domains in natural language processing, computer vision, combinatorial optimization, quantum chemistry, physics, neuroscience, genetics and social networks. In 2016, he received the highly competitive Singaporean NRF Fellowship of $2.5M to develop these deep learning techniques. He was also awarded several research grants in the U.S. and Hong Kong. As a leading researcher in the field, he has published more than 60 peer-reviewed papers in the leading journals and conference proceedings in machine learning, including articles in NeurIPS, ICML, ICLR, CVPR, JMLR. He has organized several international workshops and tutorials on AI and deep learning in collaboration with Facebook, NYU and Imperial such as the 2019 and 2018 UCLA workshops, the 2017 CVPR tutorial and the 2017 NeurIPS tutorial. He has been teaching undergraduate, graduate and industrial courses in AI and deep learning since 2014 at EPFL (Switzerland), NTU (Singapore) and UCLA (U.S.).
      
      spaces: true

    - image_path: /assets/images/glb2023/AWang.jpg
      alt: "Atlas Wang"
      title: "Atlas Wang"
      excerpt: |
        ***The University of Texas at Austin*** <br>
        **Unveiling the simplicity in Training Graph Neural Networks**

      abstract: >
        Scaling up the training of Graph Neural Networks (GNNs) has been perceived as more challenging than scaling vision or NLP models, primarily due to well-known obstacles such as over-smoothing, over-squashing,  and complexities in distributed training. Yet in this talk, we will unveil some surprising simplicity that we have discovered through our experiments with GNNs. Firstly, we will present a fresh perspective on gradient flow to comprehend the underwhelming performance of deep GCNs. By introducing GNN-customized initialization and implementing gradient-guided dynamic rewiring, we demonstrate how these techniques effectively facilitate healthy gradient flow and substantially enhance GNN trainability. Secondly, we embark on an unprecedented exploration by identifying matching untrained GNNs. Leveraging sparsity as a core tool, we can discover untrained sparse subnetworks during initialization that achieve performance on par with fully trained dense GNNs. Lastly, we explore a data-centric approach to tackle ginormous graph data by creating independently and parallelly trained multiple comparatively weaker models, without any intermediate communication. These models are subsequently merged using greedy interpolation, resulting in state-of-the-art performance.
      
      bio: >
        Professor Zhangyang “Atlas” Wang is currently the Jack Kilby/Texas Instruments Endowed Assistant Professor in the Chandra Family Department of Electrical and Computer Engineering at The University of Texas at Austin. He received the Ph.D. degree from the University of Illinois at Urbana–Champaign, under the supervision of Prof. Thomas Huang. He was an Assistant Professor at Texas A&M University from 2017 to 2020. His research interests include machine learning, computer vision, optimization, and their interdisciplinary applications. Most recently, he studies automated machine learning (AutoML), learning to optimize (L2O), robust learning, efficient learning, and graph neural networks.

      spaces: true

    - image_path: assets/images/glb2023/Sun.jpg
      alt: "Jimeng Sun"
      title: "Jimeng Sun"
      excerpt: |
        ***University of Illinois, Urbana-Champaign*** <br>

      # abstract: >
      #   (TBD)
      
      bio: >
        Jimeng Sun is the Health Innovation Professor at Computer Science Department and Carle's Illinois College of Medicine at University of Illinois, Urbana-Champaign. Previously, he was with the College of Computing, Georgia Institute of Technology. His research interest include artificial intelligence for healthcare, deep learning for drug discovery, clinical trial optimization, computational phenotyping, clinical predictive modeling, treatment recommendation, and health monitoring.
      
      spaces: true


panelists:
    - image_path: /assets/images/glb2023/MGalkin.jpg
      alt: "Michael Galkin"
      excerpt: >
        **Michael Galkin**<br>
        Intel Labs
      bio: >
        Michael Galkin is a Research Scientist at Intel AI Labs working on Graph Machine Learning and Geometric Deep Learning. Previously, Michael was a postdoc at Mila - Quebec AI Institute, working with Will Hamilton, Jian Tang, and Reihaneh Rabbany on various graph learning tasks ranging from reasoning and knowledge graphs to molecular representation learning.
    
    - image_path: /assets/images/glb2023/NShah.jpg
      alt: "Neil Shah"
      excerpt: >
        **Neil Shah**<br>
        Snap Research
      bio: >
        Neil Shah is a Lead Research Scientist and Manager at Snap Research, working on machine learning algorithms and applications on large-scale graph data. His work has resulted in 55+ conference and journal publications, in top venues such as ICLR, NeurIPS, KDD, WSDM, WWW, AAAI and more, including several best-paper awards. He has also served as an organizer, chair and senior program committee member at a number of these. He has had previous research experiences at Lawrence Livermore National Laboratory, Microsoft Research, and Twitch. He earned a PhD in Computer Science in 2017 from Carnegie Mellon University’s Computer Science Department, funded partially by the NSF Graduate Research Fellowship.
      
    - image_path: /assets/images/glb2023/YYan.jpg
      alt: "Yujun Yan"
      excerpt: >
        **Yujun Yan**<br>
        Dartmouth College
      bio: >
        Yujun Yan is an Assistant Professor from the Computer Science Department at Dartmouth College. She obtained her PhD from the University of Michigan, Ann Arbor, in 2022. Her area of specialization is graph-based machine learning, with a particular focus on generalizing graph neural networks to graphs with diverse properties, such as varying levels of heterophily and sizes. Her research on heterophily graphs has received widespread recognition and hundreds of citations. Yujun has published multiple papers at top machine learning and data mining conferences, including NeurIPS, KDD, and the WebConf. Her works have been integrated into the curricula of esteemed institutions such as Stanford University and Northeastern University. During her Ph.D., She completed internships at Microsoft Research in 2018 and 2021, as well as at Google Research in 2019 and 2020. She holds a pending patent with Google.
      
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

GLB 2023 will be a **non-archival** workshop; we are excited to host this edition **in person** in conjunction with [**KDD 2023**](https://kdd.org/kdd2023/). Please click [here](https://web.cvent.com/event/d8874717-951f-4368-b286-40f3f31cdbc3/summary) for KDD 2023 registration.

<!-- Inspired by the conference tracks in the computer vision and natural language processing communities that are dedicated to establishing new benchmark datasets and tasks, 
we call for contributions that introduce novel ML tasks or novel graph-structured data which have the potential to 
(i) help understand the performance and limitations of graph representation models on diverse sets of problems and 
(ii) support benchmark evaluations for various models. -->

Our previous call for papers can be found [here](/glb2023/call-for-papers).

# Schedule

{% capture schedule %}
Click [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) to view the schedule in Google Sheets.
{% endcapture %}

<div class="small">
{{ schedule | markdownify }}
</div>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="600"></iframe>

# Keynote Speakers
{% include feature_row id="keynote" type="left" %}

# Panelists
{% include feature_row id="panelists" %}

# Accepted Papers
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
</ul>

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


# Program Committee
<div class="small row-two-columns">
<div class="column-half">
<ul>
{% for people in site.data.pc-members2023 limit:11 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
<div class="column-half">
<ul>
{% for people in site.data.pc-members2023 offset:11 %}
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