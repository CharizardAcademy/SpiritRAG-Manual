---
icon: '1'
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/yE16Xb3IemPxJWydtPOj/getting-started/publish-your-docs
---

# Motivation

SpiritRAG was created to address a fundamental challenge in the study of religion and spirituality: concepts such as _spirituality_, _faith_, or _religion_ can carry different meanings depending on the context in which they are used.&#x20;

Traditional search tools often therefore often produce false negatives when searching these terms. We call this "information noise". For example, when searching the official archive of the United Nations General Assembly,

* searching for "spirit\*" may turn up matches for "in the spirit of",
* searching for "faith" results for "good faith" (in the legal sense of the word),&#x20;
* and "religion" often turns up lists in which religion is mentioned but not discussed in detail (e.g. "discrimination based on ethnicity, religion or gender").

Our motivation was to build a system that allows the user to search large volumes of (largely) irrelevant documents for such highly context-sensitive terms. For this purpose, we built SpiritRAG, an interactive Question Answering (Q\&A) system based on Retrieval-Augmented Generation (RAG).&#x20;

SpiritRAG is currently based on 7,500 United Nations (UN) resolution documents related to religion and spirituality in the domains of health and education.

{% hint style="info" %}
Although SpiritRAG was developed using for this purpose, it is highly flexible and can be easily adapted to different domains and datasets.
{% endhint %}

Ultimately, SpiritRAG aims to offer a scalable and customizable tool for digital-humanities research, enabling users to apply RAG-technology to search vast troves of archival data which would take years to search using traditional search tools.&#x20;

### Background

The project emerged from an interdisciplinary collaboration across computer science, social anthropology, computational linguistics, and education science.

Our team brings together four postdoctoral researchers whose expertise spans several academic disciplines:

* **Linguistic Research Infrastructure** (Dr. Yingqiang Gao\*), leading the technical implementation of the project, including corpus construction, system architecture, platform deployment and maintenance, and comprehensive system testing.
* **URPP Digital Religion(s)** (Dr. Fabian Winiger\*), contributing deep expertise in religion and spirituality, offering contextual understanding of their cultural, historical, and interpretive evaluation dimensions.
* **Department of Computational Linguistics** (Dr. Anastasia Shaitarova), providing expertise in corpus analysis, data visualization, linguistic insights, and the development of illustrative case studies.
* **Institute of Education** (Dr. Patrick Montjourides), bringsing perspectives on policy, international frameworks, and the role of social and institutional context in education and health.

<sub>\*indicates main contributors</sub>

&#x20;For its unique interdisciplinary approach, SpiritRAG won the 2025 UZH Postdoc Team Award.
