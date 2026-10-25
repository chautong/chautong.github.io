---
last_modified_at: "2026-10-25T05:09:01+00:00"
permalink: /
title: "Chau Tong"
excerpt: "Computational communication research on information access, credibility, and inequality in health and politics."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="visibility-hero">
  <div class="visibility-hero__copy">
    <div class="page-kicker">Computational communication</div>
    <h2>What becomes<br>visible?</h2>
    <p>People. Platforms. Public information.</p>
  </div>
  <img class="visibility-hero__art" src="/images/research/visibility-field.svg" alt="" aria-hidden="true">
  <div class="visibility-hero__footer"><span>Chau Tong</span><span>CCT Lab · University of Missouri</span></div>
</section>

<p class="positioning-statement">I study how search, social platforms, and generative AI shape the information people find and the claims they trust. At Missouri, I lead the Computational Communication Technology Lab, where we examine information access, credibility, and inequality in health and politics.</p>

<section class="brief-bio" markdown="1">
I am an assistant professor of Strategic Communication, jointly appointed in the [Missouri School of Journalism](https://journalism.missouri.edu/people/chau-tong/) and the [Institute for Data Science & Informatics](https://muidsi.missouri.edu/person/chau-tong/). Originally from Hanoi, I earned my M.A. at Ewha Womans University and my Ph.D. at the University of Wisconsin–Madison, advised by Dr. Hernando Rojas. At Cornell, my postdoctoral mentors were Drs. Jeff Niederdeppe and Drew Margolin.
</section>

<nav class="page-actions lead-actions" aria-label="Explore my work">
  <a href="/research/">Explore my research <span aria-hidden="true">→</span></a>
  <a href="/lab/">Work with me <span aria-hidden="true">→</span></a>
</nav>

<section class="current-agenda" aria-labelledby="current-focus">
  <div class="module-kicker">Current work</div>
  <h2 id="current-focus">AI and public information</h2>
  <p>My group is auditing Google AI Overviews across languages and over time. We examine how answers and sources change, how health guidance communicates uncertainty, and what these answers offer people seeking help.</p>
  <a class="text-link-arrow" href="/research/#research-across-fields">Research program and collaborations <span aria-hidden="true">→</span></a>
</section>

<section class="research-atlas" aria-labelledby="selected-work">
  <div class="page-kicker">01 / Selected research</div>
  <h2 id="selected-work">Making information visible</h2>
  <div class="atlas-summary">
    <p>My retrieval method recovered health videos that clinical search terms missed. Combining word embeddings, recommendation networks, and human review helps researchers examine the language people use online.</p>
    <a class="text-link-arrow" href="/publications/#health-information-retrieval">Read the study <span aria-hidden="true">→</span></a>
  </div>
  <div class="contribution-pair">
    <article><div class="module-kicker">Algorithmic gatekeeping</div><h3><a href="/publications/#political-search">The query matters.</a></h3><p>Across three political topics, query wording was the primary source of differences in Google results. My audit separates query choices from variation associated with users’ political identities, changing how we interpret apparent search bias.</p><span class="study-source">Sole author · ACM WebSci · 2025</span></article>
    <article class="contribution-pair__accent"><div class="module-kicker">Credibility and public discourse</div><h3><a href="/publications/#credibility">When “fake news” becomes an accusation</a></h3><p>Accusations of “fake news” against political opponents were associated with affective polarization. I distinguish these uses from descriptions of false content, examining credibility labels as acts of political communication.</p><span class="study-source">First author · Mass Communication and Society · 2020</span></article>
  </div>
</section>


<section class="home-news" aria-labelledby="news-updates">
  <div class="page-kicker">02 / News &amp; updates</div>
  <h2 id="news-updates">Recently</h2>
  <div class="update-list">
  {% assign recent_news = site.data.news | sort: 'date' | reverse %}
  {% for item in recent_news limit:3 %}
    <article><time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.display_date }}</time><div>{% if item.url %}<a href="{{ item.url }}">{{ item.title }}</a>{% else %}<span>{{ item.title }}</span>{% endif %}</div></article>
  {% endfor %}
  </div>
  <a class="text-link-arrow" href="/news-talks/">All news and talks <span aria-hidden="true">→</span></a>
</section>
