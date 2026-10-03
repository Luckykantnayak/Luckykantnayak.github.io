---
layout: page
title: Projects
permalink: /projects/
description: Research projects and reports in robot learning, human-robot interaction, and 3D vision.
nav: true
nav_order: 2
---

<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">
          <h2 class="card-title">MimicAgent: Quadruped Skills via Prompt-to-Trajectory Generation</h2>
          <p class="card-text">MimicAgent turns natural-language skill prompts into coarse quadruped reference trajectories with coding agents. Example-guided reinforcement learning uses those trajectories to train dynamic skills that transfer from simulation to real robots.</p>
          <p class="card-text"><strong>Status:</strong> Submitted to ICRA 2027; spotlight at the IROS 2026 AI Meets Autonomy workshop; published at the ICLR 2026 Workshop on Recursive Self-Improvement.</p>
          <p class="card-text"><a href="https://luckykantnayak.github.io/mimic-agent/">Project website</a> · <a href="https://arxiv.org/pdf/2609.24145">arXiv paper (PDF)</a> · <a href="https://www.ai-meets-autonomy.com/">IROS workshop</a> · <a href="https://openreview.net/forum?id=1iAEFtFQ9M">ICLR workshop paper</a></p>
        </div>
      </div>
    </div>
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">
          <h2 class="card-title">VIP: VLM-Guided Interactive Policy Steering for Test-Time Preference Alignment</h2>
          <p class="card-text">This project uses a vision-language model to compare candidate robot trajectories against a person's preferences. When the model is uncertain, it asks a visually grounded clarification question. The report finds that natural-language answers improve alignment with fewer interruptions than manual trajectory selection, while interaction history reduces repeated questions.</p>
          <p class="card-text">With Shikun Ban, Shohei Nagai, and Zixi Song.</p>
          <p class="card-text"><a href="{{ '/assets/pdf/vip-vlm-guided-interactive-policy-steering.pdf' | relative_url }}">Read the report (PDF)</a></p>
        </div>
      </div>
    </div>
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">
          <h2 class="card-title">Enhancing Multi-View Diffusion with Geometry-Aware Positional Encoding</h2>
          <p class="card-text">This course project adds RayRoPE, a geometry-aware positional encoding, to EscherNet's diffusion model for novel-view generation. It improves image quality over camera-only encoding on DL3DV and studies whether the model's learned uncertainty tracks generation error, view visibility, and depth error.</p>
          <p class="card-text">With Minsik Jeon and Chaneui Song.</p>
          <p class="card-text"><a href="{{ '/assets/pdf/geometry-aware-multi-view-diffusion.pdf' | relative_url }}">Read the report (PDF)</a></p>
        </div>
      </div>
    </div>
  </div>
</div>
