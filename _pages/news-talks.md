---
last_modified_at: 2026-10-24
title: "News & Talks"
permalink: /news-talks/
redirect_from:
  - /talks/
excerpt: "Research news, media coverage, invited talks, and recognition for Chau Tong and the CCT Lab."
author_profile: true
---

<div class="page-kicker">01 / News and public scholarship</div>

Publications, research coverage, talks, and group news.

## Recent updates

<div class="news-stream">
{% assign recent_news = site.data.news | sort: 'date' | reverse %}
{% for item in recent_news %}
  <article class="news-card"><time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.display_date }}</time><div class="module-kicker">{{ item.type }}</div><h3>{{ item.title }}</h3><p>{{ item.summary }}</p>{% if item.url %}<a href="{{ item.url }}">{{ item.link_label }} <span aria-hidden="true">{% if item.url contains site.url %}→{% elsif item.url contains "://" %}↗{% else %}→{% endif %}</span></a>{% endif %}</article>
{% endfor %}
</div>

## Building on this work

<div class="coverage-list">
  <article><div class="coverage-list__date">2024</div><div><h3><a href="https://journals.sagepub.com/doi/10.1177/00027642231174334">Credibility labels and judgments of false information</a></h3><p>Michael Hameleers’s “This is Clearly Fake!” in <em>American Behavioral Scientist</em> builds on our 2020 study and related research on “fake news” as a weaponized term. It examines how prior beliefs relate to judgments of information in the United States and the Netherlands.</p></div></article>
</div>

## Institutional research coverage

<div class="coverage-list">
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/07/how-your-words-shape-what-you-see-online/">How your words shape what you see online</a></h3><p><em>Missouri School of Journalism</em> · Coverage of my research as sole author on query wording and political Google results.</p></div></article>
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/04/the-surprising-truth-about-pink-slime-journalism/">The surprising truth about “pink slime” journalism</a></h3><p><em>Missouri School of Journalism / Reynolds Journalism Institute</em> · A feature on our analysis of networks of local news sites generated algorithmically.</p></div></article>
  <article><div class="coverage-list__date">2025</div><div><h3><a href="https://journalism.missouri.edu/2025/05/journalism-faculty-selected-for-prestigious-mizzou-fellows-programs/">Journalism faculty selected for Mizzou fellows programs</a></h3><p><em>Missouri School of Journalism</em> · Announcement of my selection for the 2025–2027 Arts &amp; Humanities Research and Creative Works Fellows Program.</p></div></article>
  <article><div class="coverage-list__date">2022</div><div><h3><a href="https://news.cornell.edu/stories/2022/09/new-technique-boosts-online-medical-search-results">New technique boosts online medical search results</a></h3><p><em>Cornell Chronicle</em> · Coverage of our method using word embeddings and networks for finding health videos that clinical search terms miss.</p></div></article>
</div>

## Talks and research presentations

<div class="talk-list">
  <article><span>2026</span><div><strong>When Google Answers Health Questions: Uncertainty, Guidance, and Safeguards in AI Overviews</strong><p>Invited internal colloquium · Missouri School of Journalism · October 16</p></div></article>
  <article><span>2026</span><div><strong>From concepts to classification: What new methods (MLs/LLMs) can and can’t do for social science measurement</strong><p>Invited internal seminar · J9000 Doctoral Theory Seminar · September 10</p></div></article>
  <article><span>2024</span><div><strong>Using Data Science Skills for Social Impact: Computational Social Science</strong><p>Data Science &amp; Analytics Executive Week · MU Institute for Data Science &amp; Informatics</p></div></article>
  <article><span>2022</span><div><strong>Leveraging Big Data and Analytics for Data-driven Discovery and Audience Insights in Communication Research</strong><p>Missouri School of Journalism and MU Institute for Data Science &amp; Informatics</p></div></article>
  <article><span>2022</span><div><strong>Dealing with Misinformation on COVID-19: Comparing the Use of Transparency and Accessibility in Fact-Checking Practices across 74 Countries</strong><p>Global Fact 9 · External conference presentation · Online</p></div></article>
  <article><span>2022</span><div><strong>Who Prefers Algorithmic Filtering of Political News?</strong><p>Cornell Alumni Research Poster Open House</p></div></article>
  <article><span>2021</span><div><strong>Bias by Design: Combining Old and New Methods to Contextualize Information Engagement, Exposure and Disparities in the Digital Media Environment</strong><p>Department of Communication · Cornell University</p></div></article>
</div>

## Service to the field

<dl class="collaboration-rows service-record">
  <div><dt>Professional service</dt><dd>ICA Computational Methods Division, Diversity, Equity and Inclusion Task Force, 2022–2026.</dd></div>
  <div><dt>Scholarly reviewing</dt><dd>Journal reviewing includes <em>International Journal of Public Opinion Research</em>, <em>Mass Communication and Society</em>, and <em>Harvard Kennedy School Misinformation Review</em>. Conference reviewing includes ICA, NCA, AEJMC, AAPOR, ICWSM, and the International Conference on Computational Social Science.</dd></div>
  <div><dt>External grant review</dt><dd>External reviewer for the Faculty Development Scheme, Research Grants Council of Hong Kong, 2022.</dd></div>
  <div><dt>Research community</dt><dd>Leading proposal development and team coordination for Missouri Journalism and RJI’s bid to host the 2027 C+J Symposium.</dd></div>
</dl>

<section class="recognition-band" markdown="1">
<div class="module-kicker">Selected recognition</div>

## Awards and fellowships

- **Arts & Humanities Research & Creative Works Fellow**, University of Missouri, 2025–2027
- **CTRSI Scholarship Award**, Cornell University, 2023

<details class="earlier-recognition" markdown="1">
<summary>Earlier paper awards</summary>

- **Top Student-led Paper**, AEJMC Political Communication Interest Group, 2019
- **Second-Top Student Paper**, ICA Ethnicity & Race Division, 2018
- **Top Four Paper Award**, ICA Health Communication Division, 2016

</details>

</section>

My research support includes service as key personnel on an NCI project on colorectal cancer information, 2021–2023 (R37CA259156), and current support as PI through Missouri’s Arts & Humanities Research & Creative Works Fellows Program, 2025–2027.

For the full scholarly record, including conference presentations and grants, see my [CV](/cv/).
