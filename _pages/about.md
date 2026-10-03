---
layout: about
title: About
permalink: /
news: false
selected_papers: false
social: false
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-label="Introduction">
    <div class="portfolio-hero-copy">
      <p class="portfolio-eyebrow">M.S. Robotics · Carnegie Mellon University</p>
      <p class="portfolio-lead">I build learning systems for robots that move, perceive, and adapt.</p>
      <p>I’m a Master of Science in Robotics student at CMU’s Robotics Institute, working with <a href="https://www.ri.cmu.edu/ri-faculty/deva-kannan-ramanan/">Prof. Deva Ramanan</a> on robot learning. My recent work, <a href="https://luckykantnayak.github.io/mimic-agent/">MimicAgent</a>, turns natural-language prompts into reference motions for dynamic quadruped skills.</p>
      <p>Previously, I was a research assistant in <a href="https://rislab.org/">RISLab</a> with <a href="https://www.ri.cmu.edu/ri-faculty/wennie-tabib/">Dr. Wennie Tabib</a> and a research intern in the <a href="https://www.stochlab.com/">STOCH Lab</a> at IISc Bangalore with <a href="https://www.shishirny.com/">Dr. Shishir N. Y. Kolathaya</a>. I hold B.Tech and M.Tech degrees in Aerospace Engineering from IIT Kanpur, where I worked on multi-UAV mapping with <a href="https://cse.iitk.ac.in/users/isaha/">Dr. Indranil Saha</a>.</p>
      <div class="portfolio-hero-actions">
        <a class="portfolio-button portfolio-button-primary" href="#projects">Explore projects <span aria-hidden="true">↘</span></a>
        <a class="portfolio-button portfolio-button-secondary" href="mailto:nayakluckykant01@gmail.com">Get in touch <span aria-hidden="true">↗</span></a>
      </div>
      <div class="portfolio-social" aria-label="Social links">
        <a href="https://github.com/Luckykantnayak">GitHub <span aria-hidden="true">↗</span></a>
        <a href="https://www.linkedin.com/in/lucky-kant-nayak-798827171/">LinkedIn <span aria-hidden="true">↗</span></a>
      </div>
    </div>
    <figure class="portfolio-portrait">
      <img src="{{ '/assets/img/Lucky_Google.jpg' | relative_url }}" alt="Lucky Kant Nayak" width="480" height="600">
      <figcaption><span class="portfolio-portrait-dot" aria-hidden="true"></span> Robotics Institute · Pittsburgh, PA</figcaption>
    </figure>
  </section>

  <section id="projects" class="portfolio-projects" aria-labelledby="projects-heading">
    <div class="portfolio-section-heading">
      <div>
        <p class="portfolio-eyebrow">Research &amp; selected work</p>
        <h2 id="projects-heading">Projects</h2>
      </div>
      <p>Robot learning, human-centered autonomy, and 3D vision.</p>
    </div>

    <div class="portfolio-grid">
      <article class="portfolio-card portfolio-card-featured">
        <div class="portfolio-card-top">
          <span class="portfolio-kicker">Featured research · 2026</span>
          <span class="portfolio-status">ICRA 2027 submitted</span>
        </div>
        <h3>MimicAgent</h3>
        <p class="portfolio-card-subtitle">Quadruped Skills via Prompt-to-Trajectory Generation</p>
        <p>MimicAgent uses coding agents to turn a natural-language skill prompt into a coarse reference trajectory. Example-guided reinforcement learning then trains a dynamic quadruped policy that can run in simulation and on a real robot.</p>
        <p class="portfolio-card-note">Spotlight at the <a href="https://www.ai-meets-autonomy.com/">IROS 2026 AI Meets Autonomy workshop</a> · Published at the <a href="https://openreview.net/forum?id=1iAEFtFQ9M">ICLR 2026 Workshop on Recursive Self-Improvement</a></p>
        <div class="portfolio-card-links">
          <a href="https://luckykantnayak.github.io/mimic-agent/">Project website <span aria-hidden="true">↗</span></a>
          <a href="https://arxiv.org/pdf/2609.24145">arXiv paper (PDF) <span aria-hidden="true">↗</span></a>
        </div>
      </article>

      <article class="portfolio-card">
        <span class="portfolio-kicker">Human-robot interaction · Report</span>
        <h3>VIP: VLM-Guided Interactive Policy Steering</h3>
        <p class="portfolio-card-subtitle">Test-Time Preference Alignment</p>
        <p>A vision-language model compares candidate robot trajectories against a person’s preferences and asks a visually grounded question when uncertain. In the report, natural-language feedback improves alignment with fewer interruptions than manual trajectory selection, while conversation history reduces repeated questions.</p>
        <p class="portfolio-card-note">With Shikun Ban, Shohei Nagai, and Zixi Song.</p>
        <div class="portfolio-card-links">
          <a href="{{ '/assets/pdf/vip-vlm-guided-interactive-policy-steering.pdf' | relative_url }}">Read report (PDF) <span aria-hidden="true">↗</span></a>
        </div>
      </article>

      <article class="portfolio-card">
        <span class="portfolio-kicker">3D vision · Course project</span>
        <h3>Geometry-Aware Multi-View Diffusion</h3>
        <p class="portfolio-card-subtitle">Enhancing Multi-View Diffusion with Geometry-Aware Positional Encoding</p>
        <p>We add RayRoPE to EscherNet’s diffusion model for novel-view generation. The geometry-aware encoding improves image quality over camera-only encoding on DL3DV. We also study whether learned uncertainty tracks generation error, view visibility, and depth error.</p>
        <p class="portfolio-card-note">With Minsik Jeon and Chaneui Song.</p>
        <div class="portfolio-card-links">
          <a href="{{ '/assets/pdf/geometry-aware-multi-view-diffusion.pdf' | relative_url }}">Read report (PDF) <span aria-hidden="true">↗</span></a>
        </div>
      </article>

      <article class="portfolio-card portfolio-card-media">
        <span class="portfolio-kicker">Legged robotics · IISc Bangalore</span>
        <h3>Quadruped Locomotion Control</h3>
        <p>Developed a hierarchical reinforcement learning controller for quadruped locomotion across slopes and varied surfaces. Contributed to a ROS 2 controller stack designed to work across robots and controllers.</p>
        <div class="portfolio-media-grid">
          <img src="{{ '/assets/img/Quad_Slope.gif' | relative_url }}" alt="Quadruped walking on a slope" loading="lazy">
          <img src="{{ '/assets/img/Quad_Ramp.gif' | relative_url }}" alt="Quadruped walking on a ramp" loading="lazy">
          <img src="{{ '/assets/img/media3.gif' | relative_url }}" alt="Quadruped locomotion experiment" loading="lazy">
        </div>
      </article>

      <article class="portfolio-card portfolio-card-media">
        <span class="portfolio-kicker">Aerial robotics · IIT Kanpur</span>
        <h3>Aerial Mapping with Multi-UAV Systems</h3>
        <p>Developed multi-UAV coverage path planning for large-area mapping and adapted a mesh-optimization image-stitching method to produce natural-looking maps with low shape distortion.</p>
        <div class="portfolio-media-grid portfolio-media-grid-two">
          <img src="{{ '/assets/img/Alt18_70_8x8-Border.png' | relative_url }}" alt="Aerial mapping coverage plan" loading="lazy">
          <img src="{{ '/assets/img/Alt18_70_8x8.png' | relative_url }}" alt="Stitched aerial map" loading="lazy">
        </div>
      </article>
    </div>
  </section>
</div>
