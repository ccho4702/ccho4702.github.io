---
layout: home
title: about
permalink: /
---

{% include site_style.liquid %}

<section class="home-card hero-card" aria-labelledby="home-name">
  <h1 id="home-name">Changho Choi</h1>
  <p class="home-subtitle">Ph.D. student, Electrical Engineering, KAIST · Visiting researcher at Carnegie Mellon University</p>

  <div class="hero-grid">
    <div class="hero-copy">
      <p>Hello! I am <strong>Changho Choi</strong>, a Ph.D. student in Electrical Engineering at <a href="https://www.kaist.ac.kr/en/">KAIST</a> advised by <a href="https://scholar.google.com/citations?user=GdQtWNQAAAAJ&amp;hl=en">Prof. Junmo Kim</a>. I am currently visiting Carnegie Mellon University through a fully funded Korean government exchange program.</p>

      <p>My research focuses on <strong>data-centric foundation models, audio-language models, and multimodal reasoning</strong>. I study how data and training decisions shape what models can do: which examples are useful, when they should be introduced, and how to evaluate their value before expensive full-scale training. I am also interested in LLM reasoning, agent learning, and benchmarks that reveal where models succeed or fail.</p>

      <p>Previously, I worked with the AI Foundation Model Team at <strong>KRAFTON</strong>, contributing to data pipelines for speech and text foundation models. My academic work includes <a href="https://arxiv.org/abs/2606.18273">Continuous Audio Thinking</a> for audio-language models and <a href="https://arxiv.org/abs/2508.05269">B4DL</a>, a benchmark for spatio-temporal reasoning over 4D LiDAR.</p>
    </div>

    <div class="hero-photo">
      <img src="{{ '/assets/img/self.png' | relative_url | bust_file_cache }}" alt="Portrait of Changho Choi" loading="eager">
    </div>
  </div>

  <div class="contact-row" aria-label="Contact and profile links">
    <a href="mailto:ccho4702@kaist.ac.kr" aria-label="Email ccho4702@kaist.ac.kr"><i class="fa-solid fa-envelope" aria-hidden="true"></i> ccho4702@kaist.ac.kr</a>
    <a href="https://scholar.google.com/citations?user=t7GLfp0AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar</a>
    <a href="https://github.com/ccho4702" target="_blank" rel="noopener noreferrer" aria-label="GitHub"><i class="fa-brands fa-github" aria-hidden="true"></i> GitHub</a>
    <a href="https://linkedin.com/in/changho-choi-075399331/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn"><i class="fa-brands fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
  </div>
</section>

<section class="home-card" aria-labelledby="research-interests">
  <h2 id="research-interests">Research Interests</h2>
  <ul>
    <li>Data selection and training strategies for foundation models</li>
    <li>Speech and audio-language models</li>
    <li>Multimodal reasoning and evaluation</li>
    <li>LLM reasoning and agents</li>
  </ul>
</section>

<section class="home-card" aria-labelledby="education">
  <h2 id="education">Education</h2>
  <div class="timeline-entry">
    <div><strong>KAIST</strong><br>Ph.D. in Electrical Engineering</div>
    <span class="timeline-date">Mar 2026 – Present</span>
  </div>
  <div class="timeline-entry">
    <div><strong>Carnegie Mellon University</strong><br>Visiting Scholar, Software and Societal Systems Department</div>
    <span class="timeline-date">Aug 2026 – Present</span>
  </div>
  <div class="timeline-entry">
    <div><strong>KAIST</strong><br>M.S. in Electrical Engineering</div>
    <span class="timeline-date">Mar 2024 – Feb 2026</span>
  </div>
  <div class="timeline-entry">
    <div><strong>Korea University</strong><br>B.S. in Cyber Defense</div>
    <span class="timeline-date">Mar 2020 – Feb 2024</span>
  </div>
</section>

<section class="home-card" aria-labelledby="internship">
  <h2 id="internship">Internship</h2>
  <div class="timeline-entry">
    <div><strong>KRAFTON · AI Foundation Model Team</strong><br>Machine Learning Engineer, Data Team</div>
    <span class="timeline-date">Jan 2026 – Aug 2026</span>
  </div>
  <ul>
    <li>Built and curated speech-text data through ASR/TTS pipelines, alignment, and quality filtering for Raon-Speech and its full-duplex extension.</li>
    <li>Prepared LLM pretraining data through web crawling, curation, deduplication, preprocessing, and quality filtering.</li>
  </ul>
</section>
