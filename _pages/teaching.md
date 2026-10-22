---
title: "Teaching"
permalink: /teaching/
---

<style>
  .teaching-lead { font-size: 1.08rem; line-height: 1.7; max-width: 52rem; }
  .teaching-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem; margin: 1.25rem 0 2rem; }
  .course-card, .teaching-exhibit { border: 1px solid #d7dce2; border-radius: 4px; padding: 1.1rem 1.2rem; background: #fff; }
  .course-card h3, .teaching-exhibit h3 { margin-top: 0; margin-bottom: .25rem; }
  .course-meta { color: #59636e; font-size: .9rem; margin-bottom: .7rem; }
  .course-tags { color: #45515c; font-size: .82rem; letter-spacing: .01em; }
  .principle { border-left: 3px solid #4b6577; padding-left: 1rem; margin: 1.25rem 0; }
  .principle h3 { margin-bottom: .25rem; }
  .process { display: flex; align-items: stretch; gap: .45rem; margin: 1rem 0; }
  .process-step { flex: 1; border-top: 3px solid #4b6577; background: #f3f5f6; padding: .75rem; min-width: 0; }
  .process-step strong { display: block; margin-bottom: .3rem; }
  .process-arrow { display: flex; align-items: center; color: #68737e; font-weight: 700; }
  .split-paths { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem; }
  .path { background: #f3f5f6; padding: .9rem 1rem; }
  .path h4 { margin-top: 0; }
  .path ol { margin-bottom: 0; }
  .curriculum-map { width: 100%; border-collapse: collapse; font-size: .9rem; }
  .curriculum-map th { background: #eef1f3; text-align: left; }
  .curriculum-map th, .curriculum-map td { border: 1px solid #d7dce2; padding: .65rem; vertical-align: top; }
  .earlier-teaching { background: #f6f7f8; padding: 1rem 1.2rem; }
  @media (max-width: 760px) {
    .teaching-grid, .split-paths { grid-template-columns: 1fr; }
    .process { flex-direction: column; }
    .process-arrow { justify-content: center; transform: rotate(90deg); }
    .curriculum-map { font-size: .82rem; }
    .curriculum-map th, .curriculum-map td { padding: .45rem; }
  }
</style>

<p class="teaching-lead">I teach students to investigate communication in rapidly changing technological environments. Across journalism and data science, my courses connect theory, research design, and computational methods while asking students to examine what evidence can—and cannot—establish.</p>

<p class="teaching-lead">My courses serve students with different disciplinary backgrounds and levels of technical preparation. I use scaffolded projects, applied exercises, coding labs, case discussions, and peer feedback to help students move from concepts to defensible research decisions. Whether students are designing a survey, analyzing language or networks, or evaluating a generative-AI system, I want them to develop the judgment to use emerging methods responsibly and explain their limitations clearly.</p>

## Courses at Missouri

<div class="teaching-grid">
  <section class="course-card">
    <h3>Emerging Technologies</h3>
    <div class="course-meta">JOURN 7462 · Missouri School of Journalism · 2023–2026</div>
    <p>I rebuilt this eight-week course around generative-AI literacy and the changing role of technological systems in journalism. Students examine AI and machine learning in relation to credibility, ethics, professional responsibility, platform governance, and media organizations. The course combines critical reading with documented experimentation: students maintain a weekly AI prompt-and-outcome log while developing an independent, publication-oriented research proposal.</p>
    <div class="course-tags">Generative AI · Journalism · Technology ethics · Online learning</div>
  </section>

  <section class="course-card">
    <h3>Strategic Communication Research Methods</h3>
    <div class="course-meta">JOURN 4952 · Missouri School of Journalism · 2025–2026</div>
    <p>Students learn to use research to make defensible strategic-communication decisions. Working in teams, they progress from secondary research to survey design, in-depth interviews, data interpretation, and an evidence-based client report. Individual artifacts and peer accountability preserve each student's responsibility within the collaborative process.</p>
    <div class="course-tags">Research design · Surveys · Interviews · Evidence-based decisions</div>
  </section>

  <section class="course-card">
    <h3>Introduction to Natural Language Processing with Generative AI</h3>
    <div class="course-meta">DATA_SCI 8001 · Institute for Data Science and Informatics · 2024</div>
    <p>This graduate course introduces natural language processing for computational social science. Students work with social-media, political, and news texts; learn preprocessing, dictionary methods, embeddings, machine learning, information extraction, and large language models; and examine the epistemic, legal, and ethical questions these methods raise. A scaffolded research project moves from a 300-word idea pitch to a proposal draft and a completed paper or study proposal.</p>
    <div class="course-tags">NLP · Text analysis · Machine learning · LLMs</div>
  </section>

  <section class="course-card">
    <h3>Communication Network Analytics</h3>
    <div class="course-meta">DATA_SCI 8220 · Institute for Data Science and Informatics · 2025–2026</div>
    <p>This graduate course connects network theory to computational analysis of communication systems. Students construct and visualize networks, assess centrality and connectivity, compare network models, identify communities, examine link prediction and diffusion, and apply these techniques to digital-trace data. The course culminates in an independently designed network-analysis project in a reproducible computational environment.</p>
    <div class="course-tags">Network analysis · Communication systems · Python · Digital platforms</div>
  </section>
</div>

## How I teach

<section class="principle">
  <h3>From concepts to evidence</h3>
  <p>Students should understand the relationship among a theoretical concept, its operationalization, the data used to represent it, and the claim produced by an analysis. I ask students to explain methodological choices and limitations rather than treating a technically successful output as sufficient evidence.</p>
</section>

<section class="principle">
  <h3>Learning through structured practice</h3>
  <p>I sequence lower-stakes exercises into larger research tasks: question development, method selection, data collection, analysis, validation, interpretation, and communication. Coding labs, survey exercises, case analysis, structured peer feedback, and project checkpoints give students repeated opportunities to apply ideas and receive guidance.</p>
</section>

<section class="principle">
  <h3>Responsible engagement with AI</h3>
  <p>Students need both practical fluency with generative AI and the ability to recognize when its use weakens independent reasoning or evidentiary quality. My courses combine guided experimentation, disclosure and reflection, model-output evaluation, and selected assignments completed without generative AI. The goal is informed judgment rather than uncritical adoption or blanket rejection.</p>
</section>

## Teaching design in practice

<section class="teaching-exhibit">
  <h3>1. From a communication problem to an evidence-based recommendation</h3>
  <p>In Strategic Communication Research Methods, student teams move through a complete applied-research cycle.</p>
  <div class="process" role="img" aria-label="A four-stage process: understand the problem, identify evidence gaps, generate primary evidence, and translate evidence into decisions.">
    <div class="process-step"><strong>Understand the problem</strong>Research the client, audience, market, competition, and existing evidence.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Identify evidence gaps</strong>Turn what remains unknown into focused research questions.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Generate primary evidence</strong>Design and conduct surveys and in-depth interviews.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Translate evidence into decisions</strong>Integrate findings into an evidence-based client report.</div>
  </div>
</section>

<section class="teaching-exhibit">
  <h3>2. Responsible AI learning cycle</h3>
  <p>In authorized Emerging Technologies activities, students document how they use an AI system and evaluate the resulting output before deciding whether it is usable.</p>
  <div class="process" role="img" aria-label="A five-stage process: choose a task, document the source and prompt, evaluate output, identify limitations and risks, and decide whether and how the output can be used.">
    <div class="process-step"><strong>Choose a real task</strong>Work from an authentic information need and, when required, a public source.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Document the interaction</strong>Record the source, model, prompt, timing, and retained output.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Evaluate the output</strong>Assess usefulness, complexity, accuracy, and fit for the task.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Identify limitations</strong>Examine uncertainty, error, legal concerns, and ethical risk.</div>
    <div class="process-arrow" aria-hidden="true">→</div>
    <div class="process-step"><strong>Make a judgment</strong>Decide whether and how the output can responsibly be used.</div>
  </div>
</section>

<section class="teaching-exhibit">
  <h3>3. Two pathways from data to social-scientific evidence</h3>
  <div class="split-paths">
    <div class="path">
      <h4>Natural-language processing</h4>
      <ol>
        <li>Frame a communication question</li>
        <li>Select and prepare text data</li>
        <li>Choose and justify an NLP method</li>
        <li>Validate and interpret the output</li>
        <li>Develop a research paper or proposal</li>
      </ol>
    </div>
    <div class="path">
      <h4>Communication-network analysis</h4>
      <ol>
        <li>Frame a relational question</li>
        <li>Construct and describe a network</li>
        <li>Analyze structure, communities, and dynamics</li>
        <li>Visualize and interpret the results</li>
        <li>Complete an independent network study</li>
      </ol>
    </div>
  </div>
</section>

<section class="teaching-exhibit">
  <h3>4. Curriculum map</h3>
  <div style="overflow-x:auto;">
    <table class="curriculum-map">
      <thead>
        <tr><th>Course</th><th>Intellectual contribution</th><th>Methods and practices</th><th>Culminating work</th></tr>
      </thead>
      <tbody>
        <tr><td><strong>Emerging Technologies</strong></td><td>Critical evaluation of AI and technological change</td><td>AI-output documentation, ethical analysis, research design</td><td>Publication-oriented proposal</td></tr>
        <tr><td><strong>Strategic Communication Research Methods</strong></td><td>Evidence-based communication decisions</td><td>Secondary research, surveys, interviews, mixed evidence</td><td>Client research report</td></tr>
        <tr><td><strong>Introduction to NLP</strong></td><td>Text as social-scientific evidence</td><td>Preprocessing, embeddings, machine learning, LLMs</td><td>Research paper or proposal</td></tr>
        <tr><td><strong>Communication Network Analytics</strong></td><td>Relational structure and information flow</td><td>Network construction, centrality, communities, dynamics</td><td>Independent network analysis</td></tr>
      </tbody>
    </table>
  </div>
</section>

## Earlier teaching and invited instruction

<div class="earlier-teaching">
  <p>Before joining Missouri, I taught discussion sections in Introduction to Mass Communication and Mass Media in Multicultural America at the University of Wisconsin–Madison. I have also delivered invited methods instruction on social-media data collection, computational text analysis, topic modeling, and word embeddings at Cornell University and the University of Missouri.</p>
</div>

[Lab](/lab/)
