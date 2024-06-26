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
    overlay_filter: "0.2"
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
  - title: "Invited Speakers"
    url: /2024#invited-speakers
  - title: "Accepted Papers"
    url: /2024#accepted-papers
  - title: "Organizers"
    url: /2024#organizers
  # - title: "Past Editions"
  #   url: /all-editions

keynote:
    - image_path: assets/images/mark_najork.jpeg
      alt: "Mark Najork"
      title: "Mark Najork"
      excerpt: |
        **Google DeepMind, Mountain View**

      abstract: >
        Recently, the coming-of-age of deep neural networks has dramatically improved the capabilities of large language models (LLMs). Trained on a large corpus of documents, these models not only memorize the vocabulary, morphology and syntax of human languages, but have shown to be able to memorize facts and relations. Generative language models, when provided with a prompt, will extend the prompt with likely completions – an ability that can be used to extract answers to questions from the model. The keynote will summarize the short history of these generative information retrieval systems, and focus on the many open challenges in this emerging field: ensuring that answers are grounded, attributing answer passages to a primary source, providing nuanced answers to non-factoid-seeking questions, avoiding bias, and going beyond simple regurgitation of memorized facts. It will also touch on the changing nature of the content ecosystem. LLMs are starting to be used to generate web content. Should search engines treat such derived content equal to human-authored content? Is it possible to distinguish generated from original content? How should we view hybrid authorship where humans contribute ideas and LLMs shape these ideas into prose? And how will this parallel technical evolution of search engines and content ecosystems affect their respective business models?

      bio: >
        Marc Najork is a Distinguished Research Scientist in Google DeepMind, working on new techniques to make it easier for people to obtain relevant and useful information when and where they need it. Marc is interested in using generative language models to answer questions directly, rather than referring users to relevant sources.  Direct answers represent a major paradigm shift in Information Retrieval, affecting the user experience, the fundamental architecture of the retrieval system, and the economic foundation of commercial web search and the entire web content ecosystem.  Prior to joining Google, Marc was a Principal Researcher at Microsoft Research, and a Research Scientist at Digital Equipment Corporation.  He is an ACM Fellow, IEEE Fellow, and a SIGIR Academy member.

      spaces: true

    - image_path: assets/images/luna_dong.jpeg
      alt: "Xin Luna Dong"
      title: "Xin Luna Dong"
      excerpt: |
        **Meta, Seattle**

      abstract: >
        An intelligent assistant shall be an agent that knows you and the world, can receive your requests or predict your needs, and provide you the right services at the right time with your permission. As smart devices such as Amazon Alexa, Google Home, Ray-ban Meta get popular, Intelligent Assistants are gradually playing an important role in people's lives. The Emergence of wearable devices brings more opportunities and calls for the next generation of Intelligent Assistants. In this talk, we discuss the many challenges and opportunities we face to grow intelligent assistants from voice-only to multi-modal, from context-agnostic to context-aware, from listening to the users' requests to predicting the user's needs, and from server-side to on-device. We discuss our solutions toward multi-modality, contextualization, personalization, and retrieval-augmentation. We expect these new challenges to open doors to new research areas and start a new chapter for providing personal assistance services.

      bio: >
        Xin Luna Dong is a Principal Scientist at Meta Reality Labs, leading the ML efforts in building an intelligent personal assistant. She has spent more than a decade building knowledge graphs, such as the Amazon Product Graph and the Google Knowledge Graph. She has co-authored books "Machine Knowledge: Creation and Curation of Comprehensive Knowledge Bases" and “Big Data Integration”. She was named an ACM Fellow and an IEEE Fellow for "significant contributions to knowledge graph construction and data integration", awarded the VLDB Women in Database Research Award and VLDB Early Career Research Contribution Award. She serves in the PVLDB advisory committee, was a member of the VLDB endowment, a PC co-chair for KDD’2022 ADS track, WSDM’2022, VLDB’2021, and Sigmod’2018.

      spaces: true

invited:
    - image_path: assets/images/jianmo.jpeg
      alt: "Jianmo Ni"
      title: "Jianmo Ni"
      excerpt: |
        **Google DeepMind, Mountain View**

      abstract: >
        With the recent advances of large language models, there have been growing opportunities to improve recommender systems by using LLM's extraordinary capabilities as language understanding, reasoning and generation. In this talk, we will introduce and discuss recent works on building better personalized recommender systems with LLMs, from the perspective of user reference prediction, content understanding, personalized generation, tool-use, data efficiency and privacy.

      bio: >
        Jianmo Ni is a senior software engineer at Google DeepMind, where he worked on the intersection of natural language understanding and recommender systems. He has developed Sentence T5, Promptagator, Differentiable Search Index and SWIM-IR to improve retrieval systems by bridging embedding models with large language models (LLMs). Prior to Google, he obtained his Ph.D. from University of California San Diego, where his research focused on personalized machine learning.

      spaces: true

    - image_path: assets/images/julian.jpeg
      alt: "Julian McAuley"
      title: "Julian McAuley"
      excerpt: |
        **UC San Diego, San Diego**

      abstract: >
        In this talk we'll explore the current landscape of conversational recommendation in light of new developments on Large Language Models. While LLMs offer a surprisingly effective "off-the-shelf" solution to conversational recommendation, they also have various limitations. We'll discuss limitations from the perspective of datasets, methodology, and evaluation, and discuss possible future directions.

      bio: >
        Julian McAuley is a Professor at UC San Diego, where he works on applications of machine learning to problems involving personalization, and teaches classes on personalized recommendation. He likes bicycling and baroque keyboard.

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


| Time (CST)            | Agenda                                                                                            |
| --------------------- | ------------------------------------------------------------------------------------------------- |
| **9:00-9:10 AM**      | **Opening remarks**                                                                               |
| **9:10-10:00 AM**     | **Keynote by Marc Najork**                                                                        |
| **10:00-10:30 AM**    | **Break**                                                                                         |
| **10:30-11:20 AM**    | **Keynote by Luna Dong**                                                                          |
| **11:20-11:30 AM**    | **Short Break**                                                                                   |
| **11:30 AM-12:15 PM** | **Panel discussion**                                                                              |
| **2:00-2:40 PM**      | **Invited Talk by Jianmo Ni**                                                                     |
| **2:40-2:45 PM**      | **Short Break**                                                                                   |
| **2:45-3:30 PM**      | **Paper talk - LaMP: When Large Language Models Meet Personalization**                            |
| **3:00-3:15 PM**      | **Paper talk - Teach LLMs to Personalize -- An Approach inspired by Writing Education**           |
| **3:15-3:30 PM**      | **Paper talk - Editable User Profiles for Controllable Text Recommendations**                     |
| **3:30-4:00 PM**      | **Break**                                                                                         |
| **4:00-4:40 PM**      | **Invited Talk by Julian McAuley (virtual talk)**                                                 |
| **4:40-4:45 PM**      | **Short Break**                                                                                   |
| **4:45-5:00 PM**      | **Paper talk - Language-Based User Profiles for Recommendation**                                  |
| **5:00-5:15 PM**      | **Paper talk - Automated Evaluation of Personalized Text Generation using Large Language Models** |
| **5:15-5:30 PM**      | **Paper talk**                                                                                    |
| **5:30-5:35 PM**      | **Closing remarks**                                                                               |


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
{% include feature_row id="invited" type="left" %}

# Accepted Papers

| Paper ID | Title                                                                            | Link                                      |
| -------- | -------------------------------------------------------------------------------- | ----------------------------------------- |
| 3        | Language-Based User Profiles for Recommendation                                  | [arxiv](https://arxiv.org/abs/2402.15623) |
| 4        | Teach LLMs to Personalize -- An Approach inspired by Writing Education           | [arxiv](https://arxiv.org/abs/2308.07968) |
| 5        | Editable User Profiles for Controllable Text Recommendation                      | [arxiv](https://arxiv.org/abs/2304.04250) |
| 6        | LaMP: When Large Language Models Meet Personalization                            | [arxiv](https://arxiv.org/abs/2304.11406) |
| 7        | Automated Evaluation of Personalized Text Generation using Large Language Models | [arxiv](https://arxiv.org/abs/2310.11593) |

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
-->

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