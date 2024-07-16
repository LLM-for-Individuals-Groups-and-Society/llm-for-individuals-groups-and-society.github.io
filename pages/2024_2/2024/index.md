---
permalink: /2024_2
title: "2nd Workshop on Large Language Models for Individuals, Groups, and Society"
excerpt: Washington D.C., USA, July 18, 2024 <br> Held in conjunction with <a href="https://sigir-2024.github.io/">SIGIR 2024</a>
browser-title: "LLM for Individuals, Groups, and Society"
masthead-title: "LLM for Individuals, Groups, and Society"
masthead-subtitle: "@SIGIR 2024"
masthead-url: "/"
layout: splash
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.2"
    overlay_image: /assets/images/llm-bg2.jpg
navigation:
  - title: "Call for Papers"
    url: /2024_2/call-for-papers
  # - title: "Important Dates"
  #   url: /2024_2#important-dates
  # - title: "Submission"
  #   url: /2024_2#submission
  - title: "Schedule"
    url: /2024_2#schedule
  - title: "Keynotes"
    url: /2024_2#keynote-speakers
  - title: "Panelists"
    url: /2024_2#panelists
  # - title: "Accepted Papers"
  #   url: /2024_2#accepted-papers
  - title: "Organization"
    url: /2024_2#organizers
  # - title: "Past Editions"
  #   url: /all-editions

keynote:
    - image_path: assets/images/zhiyong_lu.png
      alt: "Zhiyong Lu"
      title: "Zhiyong Lu"
      excerpt: |
        **Senior Investigator, NIH/NLM**<br>
        **Deputy Director for Literature Search, NCBI**<br>
        **Professor of Computer Science (Adjunct), UIUC**

      abstract: >
        **Transforming Medicine with AI: from PubMed Search to TrialGPT**<br>
        The explosion of biomedical big data and information in the past decade or so has created new opportunities for discoveries to improve the treatment and prevention of human diseases. As such, the field of medicine is undergoing a paradigm shift driven by AI-powered analytical solutions. This talk explores the benefits (and risks) of AI and ChatGPT, highlighting their pivotal roles in revolutionizing biomedical discovery, patient care, diagnosis, treatment, and medical research. By demonstrating their uses in some real-world applications such as improving PubMed searches (Fiorini et al., Nature Biotechnology 2018), supporting precision medicine (LitVar, Allot et al., Nature Genetics 2023), and accelerating patient trial matching (TrialGPT), we underscore the potential of AI and ChatGPT in enhancing clinical decision-making, personalizing patient experiences, and accelerating knowledge discovery.


      bio: >
        Dr. Zhiyong Lu is a tenured Senior Investigator at the NIH/NLM IPR, leading research in biomedical text and image processing, information retrieval, and AI/machine learning. In his role as Deputy Director for Literature Search at NCBI, Dr. Lu oversees the overall R&D efforts to improve literature search and information access in resources like PubMed and LitCovid, which are used by millions worldwide each day. Additionally, Dr. Lu is Adjunct Professor of Computer Science at the University of Illinois Urbana-Champaign (UIUC). With over 350 peer-reviewed publications, Dr. Lu is a highly cited author, and a Fellow of the American College of Medical Informatics (ACMI) and the International Academy of Health Sciences Informatics (IAHSI).

      spaces: true

    - image_path: assets/images/hamed_zamani.jpg
      alt: "Hamed Zamani"
      title: "Hamed Zamani"
      excerpt: |
        **Associate Professor, UMass**

      abstract: >
        **Personalizing Large Language Models**<br>
        Many users these days rely on Large Language Models (LLMs) to learn about topics and find the answer to their questions. In this talk, I will discuss models and evaluation methodologies for generating personalized outputs, depending on the user's preferences, history, or background knowledge. In more detail, I will first introduce the Language Model Personalization (LaMP) benchmark (https://lamp-benchmark.github.io/) -- a large-scale benchmark for studying personalization for text classification and generation using LLMs. I will later draw connections between LLM personalization and retrieval-enhanced machine learning (REML) and introduce retrieval-augmented approaches for personalizing large language models.

      bio: >
        Hamed Zamani is an Associate Professor in the Manning College of Information and Computer Sciences at the University of Massachusetts Amherst (UMass), where he also serves as the Associate Director of the Center for Intelligent Information Retrieval (CIIR), one of the top academic research labs in Information Retrieval worldwide. Prior to UMass, he was a Researcher at Microsoft. His research focuses on designing and evaluating statistical and machine learning models with applications to (interactive) information access systems and retrieval-enhanced AI systems. His work has led to over 90 refereed publications in the field, in addition to a number of open-source research tools. His research has been recognized by a CAREER Award from NSF, Early Career Excellence in Research and Community Engagement awards from ACM SIGIR, multiple research awards from Adobe, Amazon, Google, and Microsoft, and multiple paper awards from SIGIR 2023, SIGIR 2022, CIKM 2020, and ICTIR 2019.

      spaces: true

invited:
    - image_path: assets/images/hongning_wang.jpg
      alt: "Hongning Wang"
      title: "Hongning Wang"
      excerpt: |
        **Copenhaver Associate Professor of Computer Science, University of Virginia** <br>

      abstract: >
        **Human vs. Generative AI in Content Creation Competition: Symbiosis or Conflict?**<br>
        The advent of generative AI technology produces transformative impact on the content creation landscape, offering alternative approaches to produce diverse, good-quality content across media, thereby reshaping the ecosystems of online content creation and publishing, but also raising concerns about market over-saturation and the potential marginalization of human creativity. Our recent work introduces a competition model generalized from the Tullock contest to analyze the tension between human creators and generative AI. Our theory and simulations suggest that despite challenges, a stable equilibrium between human and AI-generated content is possible. Our work contributes to understanding the competitive dynamics in the content creation industry, offering insights into the future interplay between human creativity and technological advancements in generative AI.

      bio: >
        Hongning Wang received his Ph.D. from the Department of Computer Science at University of Illinois at Champaign-Urbana in 2014, and joined University of Virginia as Assistant Professor since then. He is the recipient of National Science Foundation CAREER Award, 2014 Yahoo ACE (Academic Career Enhancement) Award, Google 2012 PhD Fellowship in Search and Information Retrieval, and 2012 Yahoo! Key Scientific Challenges in Web Information Management. He has served on program committees for several major conferences such as WWW, WSDM, ICML, ECML/PKDD, CIKM, and ECIR, and reviewed for multiple journals, including IEEE TKDE, ACM TOIS, Neurocomputing and BMC Bioinformatics.

      spaces: true
---


<!-- <div class="notice--info">
    <h4 class="no_toc">Notice Headline:</h4>
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

<!-- We have a full-day program from <u>8am to 5pm on Sunday (Aug. 6)</u> at ***Grand Ballroom B***. -->

| Time               | Agenda                                                                                                             |
|--------------------|--------------------------------------------------------------------------------------------------------------------|
| **9:00-9:10 AM**   | **Opening remarks**                                                                                                |
| **9:10-10:00 AM**  | **Keynote by Zhiyong Lu - Transforming Medicine with AI: from PubMed Search to TrialGPT**                          |
| **10:00-10:30 AM** | **Contributing Talk 1**                                                                                            |
| **10:30-11:00 AM** | **Break**                                                                                                          |
| **11:00-11:30 AM** | **Contributing Talk 2**                                                                                            |
| **1:30-2:00 PM**   | **Invited talk by Hongning Wang - Human vs. Generative AI in Content Creation Competition: Symbiosis or Conflict** |
| **2:00-3:00 PM**   | **Panel Discussion**                                                                                               |
| **3:00-3:30 PM**   | **Break**                                                                                                          |
| **3:30-4:20 PM**   | **Keynote by Hamed Zamani - Personalizing Large Language Models**                                                  |

<!--
{% capture schedule %}
Click [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) to view the detailed schedule in Google Sheets.
{% endcapture %}
<div class="small">
{{ schedule | markdownify }}
</div>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="600"></iframe> -->

# Keynote Speakers

{% include feature_row id="keynote" type="left" %}

# Invited Speakers

{% include feature_row id="invited" type="left"%}

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

# Accepted Papers

| Paper ID | Title                                                                            | Link                                      |
| -------- | -------------------------------------------------------------------------------- | ----------------------------------------- |
| 2        | Session Context Embedding for Intent Understanding in Product Search                                  | [arxiv](https://arxiv.org/abs/2406.01702) |
| 3        | Unlocking the 'Why' of Buying: Introducing a New Dataset and Benchmark for Purchase Reason and Post-Purchase Experience           | [arxiv](https://arxiv.org/abs/2402.13417) |

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

# Previous Editions

* [1st Workshop on Large Language Models for Individuals, Groups, and Society](/2024)

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
</div> -->

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
