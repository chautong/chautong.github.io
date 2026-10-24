---
title: "News & Talks"
permalink: /news-talks/
excerpt: "Research news, media coverage, invited talks, and recognition for Chau Tong and the CCT Lab."
author_profile: true
---

<div class="page-kicker">01 / News and public scholarship</div>

Publications, research coverage, talks, and group news.

## Recent updates

<div class="news-stream">
{% assign recent_news = site.data.news | sort: 'date' | reverse %}
{% for item in recent_news %}
  <article class="news-card"><time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.display_date }}</time><div class="module-kicker">{{ item.type }}</div><h3>{{ item.title }}</h3><p>{{ item.summary }}</p>{% if item.url %}<a href="{{ item.url }}">{{ item.link_label }} <span aria-hidden="true">↗</span></a>{% endif %}</article>
{% endfor %}
</div>

## Media coverage

<div class="coverage-list">
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/07/how-your-words-shape-what-you-see-online/">How your words shape what you see online</a></h3><p><em>Missouri School of Journalism</em> · Coverage of my sole-authored research on query wording and political Google results.</p></div></article>
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/04/the-surprising-truth-about-pink-slime-journalism/">The surprising truth about “pink slime” journalism</a></h3><p><em>Missouri School of Journalism / Reynolds Journalism Institute</em> · A feature on our large-scale analysis of algorithmically generated local-news networks.</p></div></article>
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/05/journalism-faculty-selected-for-prestigious-mizzou-fellows-programs/">Journalism faculty selected for Mizzou fellows programs</a></h3><p><em>Missouri School of Journalism</em> · Announcement of my selection for the 2025–2027 Arts &amp; Humanities Research and Creative Works Fellows Program.</p></div></article>
  <article><div class="coverage-list__date">2022</div><div><h3><a href="https://news.cornell.edu/stories/2022/09/new-technique-boosts-online-medical-search-results">New technique boosts online medical search results</a></h3><p><em>Cornell Chronicle</em> · Coverage of our word-embedding and network method for finding health videos that clinical search terms miss.</p></div></article>
</div>

## Talks and research presentations

<div class="talk-list">
  <article><span>2026</span><div><strong>When Google Answers Health Questions: Uncertainty, Guidance, and Safeguards in AI Overviews</strong><p>Invited internal colloquium · Missouri School of Journalism · October 16</p></div></article>
  <article><span>2026</span><div><strong>From concepts to classification: What new methods (MLs/LLMs) can and can’t do for social science measurement</strong><p>Invited internal seminar · Invited internal seminar · J9000 Doctoral Theory Seminar · September 10</p></div></article>
  <article><span>2024</span><div><strong>Using Data Science Skills for Social Impact: Computational Social Science</strong><p>Data Science &amp; Analytics Executive Week · MU Institute for Data Science &amp; Informatics</p></div></article>
  <article><span>2022</span><div><strong>Leveraging Big Data and Analytics for Data-driven Discovery and Audience Insights in Communication Research</strong><p>Missouri School of Journalism and MU Institute for Data Science &amp; Informatics</p></div></article>
  <article><span>2022</span><div><strong>Dealing with Misinformation on COVID-19: Comparing the Use of Transparency and Accessibility in Fact-Checking Practices across 74 Countries</strong><p>Global Fact 9 Conference · Online</p></div></article>
  <article><span>2022</span><div><strong>Who Prefers Algorithmic Filtering of Political News?</strong><p>Cornell Alumni Research Poster Open House</p></div></article>
  <article><span>2021</span><div><strong>Bias by Design: Combining Old and New Methods to Contextualize Information Engagement, Exposure and Disparities in the Digital Media Environment</strong><p>Department of Communication · Cornell University</p></div></article>
</div>

<section class="recognition-band" markdown="1">
<div class="module-kicker">Selected recognition</div>

## Awards and fellowships

- **Arts & Humanities Research & Creative Works Fellow**, University of Missouri, 2025–2027
- **CTRSI Scholarship Award**, Cornell University, 2023
- **Top Student-led Paper**, AEJMC Political Communication Interest Group, 2019
- **Second-Top Student Paper**, ICA Ethnicity & Race Division, 2018
- **Top Four Paper Award**, ICA Health Communication Division, 2016

</section>

For the full scholarly record, including conference presentations and grants, see my [CV](/cv/).
