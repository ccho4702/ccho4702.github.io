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
      <p>Hello! I am <strong>Changho Choi</strong>, a Ph.D. student in Electrical Engineering at <a href="https://www.kaist.ac.kr/en/">KAIST</a> advised by <a href="https://scholar.google.com/citations?user=GdQtWNQAAAAJ&amp;hl=en">Prof. Junmo Kim</a>. I am currently visiting Carnegie Mellon University through a fully funded Korean government exchange program. I also work remotely as an intern at <a href="https://pyler.tech/">PYLER</a> on agent-based multimodal video retrieval. Previously, I was a Machine Learning Engineer intern with the AI Foundation Model Team at <strong>KRAFTON</strong>, contributing to pretraining data pipelines for <a href="https://huggingface.co/KRAFTON/Raon-1-mini-preview">Raon-1-mini</a> and <a href="https://huggingface.co/KRAFTON/Raon-Speech-9B">Raon-Speech-9B</a>.</p>

      <p>My research focuses on <strong>data-centric foundation models, audio-language models, and multimodal reasoning</strong>. I study how data and training decisions shape what models can do: which examples are useful, when they should be introduced, and how to evaluate their value before expensive full-scale training. I am also interested in LLM reasoning, agent learning, and benchmarks that reveal where models succeed or fail.</p>
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
    <li>Multimodal large language models</li>
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

<section class="home-card" aria-labelledby="experience">
  <h2 id="experience">Industry Experience</h2>
  <div class="timeline-entry">
    <div><strong><a href="https://pyler.tech/">PYLER</a></strong><br>Remote Intern</div>
    <span class="timeline-date">Oct 2026 – Present</span>
  </div>
  <ul>
    <li>Built a multimodal video retrieval pipeline combining embedding-based search, multimodal LLM verification, and web-search agents to return timestamped moments from natural-language queries.</li>
  </ul>

  <div class="timeline-entry experience-entry">
    <div><strong>KRAFTON · AI Foundation Model Team</strong><br>Machine Learning Engineer, Data Team Intern</div>
    <span class="timeline-date">Jan 2026 – Aug 2026</span>
  </div>
  <ul>
    <li>Contributed to pretraining data pipelines for <a href="https://huggingface.co/KRAFTON/Raon-1-mini-preview">Raon-1-mini</a> (30B-A4B MoE LLM) and <a href="https://huggingface.co/KRAFTON/Raon-Speech-9B">Raon-Speech-9B</a> (9B Speech LLM).</li>
    <li>Built and evaluated large-scale datasets for ASR, TTS, and full-duplex speech modeling. Scaled processing across a large B300 GPU cluster using vLLM and Slurm, and used proxy models to assess model performance and training data quality.</li>
    <li>Prepared text pretraining corpora through synthesis, web crawling, curation, deduplication, preprocessing, and quality filtering.</li>
  </ul>
</section>
