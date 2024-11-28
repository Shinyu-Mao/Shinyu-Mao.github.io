---
permalink: /
title: "Xinyu Mao@UQ"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm a third-year PhD student from [IELab](https://ielab.io/) at the University of Queensland (UQ), supervised by [Professor. Guido Zuccon](https://researchers.uq.edu.au/researcher/22857), [A.Professor. Bevan Koopman](https://bevankoopman.github.io/), and [Dr. Harrisen Scells](https://scells.me/).

I received a Master of Data Science from the University of Queensland in 2021. Before that, I obtained a Bachelor of Engineering and a Bachelor of Arts from Shanghai Ocean University in 2019.

My research focuses on Information Retrieval (IR), and my PhD topic is domain-specific: **Automation of Medical Systematic Review**. I have been working on Screening Prioritisation, and currently focus on Boolean Query Performance Prediction. I'm also interested in general IR topics, such as Ranker Robustness. Prior to my PhD, I had research experience in Cybersecurity, investigating the application of Homomorphic Encryption.

I tutor at UQ for **DATA7001: Introduction to Data Science** (2023) and **INFS7410: Information Retrieval and Web Search** (2023, 2024).

## News
<ul>
{% include news.html %}
<a href="/news/" class="read-more-link">Read all news</a>
</ul>

## Services

I serve as a reviewer/PC member for the following conferences:

- ACM ICTIR 2023


## Publications

<ul>
{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for post in sorted_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>