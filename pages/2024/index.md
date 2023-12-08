---
permalink: /2024
title: "Workshop on Large Language Models for Individuals, Groups, and Society"
excerpt: Merida, Yucatan, Mexico, March 8, 2024 <br> Held in conjunction with <a href="https://www.wsdm-conference.org/2024/">WSDM 2024</a>
browser-title: "LLM for Individuals, Groups, and Society"
masthead-title: "LLM for Individuals, Groups, and Society"
masthead-subtitle: "@WSDM 2024"
masthead-url: "/"
layout: splash
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/images/llm-bg.jpg
navigation:
  - title: "Call for Papers"
    url: /2024/call-for-papers
  # - title: "Important Dates"
  #   url: /2024#important-dates
  # - title: "Submission"
  #   url: /2024#submission
  - title: "Schedule"
    url: /2024#schedule
  - title: "Keynotes"
    url: /2024#keynote-speakers
  - title: "Panelists"
    url: /2024#panelists
  # - title: "Accepted Papers"
  #   url: /2024#accepted-papers
  - title: "Organization"
    url: /2024#organizers
  # - title: "Past Editions"
  #   url: /all-editions

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
        **Data, Benchmark and Models to Enable AI in Healthcare**

      abstract: >
        In this presentation, we address the key components for AI integration in healthcare: data, benchmarks, and models. Firstly, we examine a Hierarchical Autoregressive Language Model that generates high-dimensional Electronic Health Records, facilitating the development of healthcare AI models. Then, we assess the Hierarchical Interaction Network (HINT) paper's clinical trial outcome prediction as an open benchmark. Finally, we explore an evidence-based spatiotemporal model using Ising dynamics for COVID-19 hospitalization predictions, leveraging specialized graph regularization. This discussion exemplifies how AI, fueled by both synthetic and real data, is set to transform the biotech and healthcare sectors.

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

The recent advancements in large language models (LLMs), such as GPT, PaLM, and Llama, along with the generative AI capabilities they possess, have garnered significant attention within both the research community and the public sphere. Although these models are easily accessible to users and researchers through conventional prompting interfaces, API calls, or static snapshots, there is an increasing demand for these models to provide personalized and context-aware responses. This requirement arises from diverse application scenarios where assistive creation and tailored generation are essential for individual and groups/sub-populations of users with even more diverse backgrounds and preferences. Merely relying on generic responses is insufficient in addressing the specific needs and constraints of users in personal, group, or even societal contexts. Instead, such scenarios demand the models’ ability to consider and align their responses to the preferences and objectives of the users in these aforementioned contexts.

This workshop aims to create a collaborative and interdisciplinary platform that brings together creators, researchers, and practitioners of large language models. By fostering an open and forward-looking environment, the workshop seeks to facilitate discussions on the current landscape of personalizing LLMs, adapting LLMs to individual and group contexts, and aligning LLMs with the value and objectives of the society at large. It provides an opportunity for participants to share insights, exchange ideas, and explore innovative approaches in the field. The ultimate goal is to drive progress and shape the future of large language models for individuals, groups, and the society through collective expertise and collaboration.

Topics of the workshop will include but not limited to:
* Novel **models and algorithms** for adapting large language models to personal contexts.
* New developments in **aligning** large language models with the preferences and objectives of individuals, sub-populations, or the society at large.
* Theoretical and empirical results of applying **reinforcement learning from the feedback** of individuals and groups of human users to LLMs.
* **Evaluation of personalization and societal alignment** of LLMs, including datasets, metrics, and benchmarks.
* **Personalizing and aligning LLMs under resource constraints**. For example, deploying personalized LLMs on mobile devices or aligning the output of frozen LLMs through APIs.
* **Applications** of personalization and societal-alignment of LLMs, including but not limited to search engines, recommender systems, email/writing assistants, social networking, entertainment, education, healthcare, scientific discovery, and future of work.
* **Ethics** of personalizing LLMs, including but not limited to privacy, fairness, bias, transparency, diversity, and other potential impacts of LLMs to individuals, groups, and the society.
* **Equitable applications** of LLM to diverse user groups.

# Schedule

<!-- We have a full-day program from <u>8am to 5pm on Sunday (Aug. 6)</u> at ***Grand Ballroom B***.

| Time (PDT) | Agenda |
| ----------------- | ------------ |
| **8:00-8:10am**    | **Opening remarks** |
| **8:10-8:50am**    | **[Keynote by Yizhou Sun](#Yizhou+Sun) (40 min)**: <br> Graph Neural Networks: Trends and Open Problems |
| **8:50-9:30am**    | **[Keynote by Da Zheng](#Da+Zheng) (40 min)**: <br> Graph machine learning for industry applications with DGL and GraphStorm |
| **9:30-10:00am**    | **Coffee Break** |
| **10:00-10:40am**    | **[Keynote by Xavier Bresson](#Xavier+Bresson) (40 min)**: <br> A Generalization of Visual Transformers and MLP-Mixer to Graphs |
| **10:40-11:30am**    | **Contributed Talks - Session 1 (50 min)** [(Presentation Time)](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) <br> - A critical look at the evaluation of GNNs under heterophily: Are we really making progress? *(Outstanding Paper)*<br>- Examining the Effects of Degree Distribution and Homophily in Graph Learning Models<br>- Impact-Oriented Contextual Scholar Profiling using Self-Citation Graphs<br>- An Out-of-the-Box Application for Reproducible Graph Collaborative Filtering extending the Elliot Framework|
| **11:30-1:00pm**    | **Lunch Break (90 min)** |
| **1:00-1:40pm**    | **[Keynote by Atlas Wang](#Atlas+Wang) (40 min)**: <br> Unveiling the simplicity in Training Graph Neural Networks |
| **1:40-2:20pm**    | **[Keynote by Jimeng Sun](#Jimeng+Sun) (40 min)**: <br> Data, Benchmark and Models to Enable AI in Healthcare |
| **2:20-3:00pm**    | **Contributed Talks - Session 2 (40 min)** [(Presentation Time)](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) <br> - Graph Generative Model for Benchmarking Graph Neural Networks *(Outstanding Paper)*<br>- TpuGraphs: A Performance Prediction Dataset on Large Tensor Computational Graphs<br>- NeuroGraph: Benchmarks for Graph Machine Learning in Brain Connectomics |
| **3:00-3:30pm**    | **Coffee Break (30 min)**|
| **3:30-4:30pm**    | **[Panel Discussion](#panelists) (60 min)**<br>**Moderator**:Jingrui He<br>**Panelists**: Michael Galkin, Neil Shah, Yujun Yan|
| **4:30-4:50pm**    | **Contributed Talks - Session 3 (20 min)** [(Presentation Time)](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) <br> - A Metadata-Driven Approach to Understand Graph Neural Networks<br>- Web-Scale Academic Name Disambiguation: the WhoIsWho Benchmark, Leaderboard, and Toolkit |
| **4:50-5:00pm**    | **Closing Remarks** |

{% capture schedule %}
Click [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) to view the detailed schedule in Google Sheets.
{% endcapture %}
<div class="small">
{{ schedule | markdownify }}
</div>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="600"></iframe> -->

# Keynote Speakers
<!-- {% include feature_row id="keynote" type="left" %} -->

# Panelists
<!-- {% include feature_row id="panelists" %} -->

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
Please contact us through <a target="_blank" href="https://mailhide.io/e/sX9eL7uk">this email address</a> if you have any questions.

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
<iframe id="organizer-frame" class="airtable-embed" src="https://airtable.com/embed/appIcFI3A3qlZEXLn/shrEdMW17Ryg0T1Ns?backgroundColor=orange&viewControls=on" frameborder="0" onmousewheel="" height="950" style="background: transparent; border: 1px solid #ccc;"></iframe>
</div>

<!-- <iframe class="airtable-embed" src="https://airtable.com/embed/shrwvG9wYqjrbXq0s?backgroundColor=purple" frameborder="0" onmousewheel="" width="106%" height="750" style="background: transparent; border: 1px solid #ccc;"></iframe>


<!-- # Program Committee
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
</script> -->