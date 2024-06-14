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
    - image_path: assets/images/mark_najork.jpeg
      alt: "Mark Najork"
      title: "Mark Najork"
      excerpt: |
        **Google DeepMind, Mountain View** <br>
        **TBA**

      abstract: >
        TBA

      bio: >
        TBA

      spaces: true

    - image_path: assets/images/luna_dong.jpeg
      alt: "Xin Luna Dong"
      title: "Xin Luna Dong"
      excerpt: |
        **Meta, Seattle** <br>
        **TBA**

      abstract: >
        TBA

      bio: >
        TBA

      spaces: true

invited:
    - image_path: assets/images/derek.jpeg
      alt: "Derek Zhiyuan Cheng"
      title: "Derek Zhiyuan Cheng"
      excerpt: |
        **Google DeepMind, Mountain View** <br>
        **TBA**

      abstract: >
        TBA

      bio: >
        TBA

      spaces: true

    - image_path: assets/images/julian.jpeg
      alt: "Julian McAuley"
      title: "Julian McAuley"
      excerpt: |
        **UC San Diego, San Diego** <br>
        **TBA**

      abstract: >
        TBA

      bio: >
        TBA

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

<!-- | Time (CST)       | Agenda                                                                 |
|------------------|------------------------------------------------------------------------|
| **9:00-9:10 AM** | **Opening remarks**                                                    |
| **9:10-10:00 AM**| **Keynote by Marc Najork**                                             |
| **10:00-10:30 AM**| **Break**                                                              |
| **10:30-11:20 AM**| **Keynote by Luna Dong**                                               |
| **11:20-11:30 AM**| **Short Break**                                                        |
| **11:30 AM-12:15 PM**| **Panel discussion**                                                 |
| **2:00-2:40 PM** | **Invited Talk by Derek Cheng**                                        |
| **2:40-2:45 PM** | **Short Break**                                                        |
| **2:45-3:30 PM** | **Paper talk - LaMP: When Large Language Models Meet Personalization** |
| **3:00-3:15 PM** | **Paper talk - Teach LLMs to Personalize -- An Approach inspired by Writing Education** |
| **3:15-3:30 PM** | **Paper talk - Editable User Profiles for Controllable Text Recommendations** |
| **3:30-4:00 PM** | **Break**                                                              |
| **4:00-4:40 PM** | **Invited Talk by Julian McAuley (virtual talk)**                      |
| **4:40-4:45 PM** | **Short Break**                                                        |
| **4:45-5:00 PM** | **Paper talk - Language-Based User Profiles for Recommendation**       |
| **5:00-5:15 PM** | **Paper talk - Automated Evaluation of Personalized Text Generation using Large Language Models** |
| **5:15-5:30 PM** | **Paper talk - A Dialogue Generation Adapter for LLM over Domain Knowledge Gap** |
| **5:30-5:35 PM** | **Closing remarks**                                                    | -->

<!--
{% capture schedule %}
Click [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&single=true) to view the detailed schedule in Google Sheets.
{% endcapture %}
<div class="small">
{{ schedule | markdownify }}
</div>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTRMzc0vmmj11ItBZKcHgKIVed9VaePOYvUeueLsOZidKApQmheY0fFLptdCVNhWCQLXPCxfLRxThiA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="600"></iframe> -->

# Keynote Speakers
<!-- {% include feature_row id="keynote" type="left" %} -->

# Invited Speakers
<!-- {% include feature_row id="invited" type="left"%} -->

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