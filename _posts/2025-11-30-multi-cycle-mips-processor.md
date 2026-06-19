---
layout: single
title: "Multi-Cycle MIPS Processor"
categories:
  - Project
tags:
  - School Project
  - Verilog
header:
  teaser: /assets/images/mips/datapath-diagram.jpg
date: 2025-11-30
permalink: /projects/multi-cycle-mips-processor/
author_profile: true
toc: true
toc_label: "Sections"
toc_icon: "microchip"
classes: wide
---

<style>
  .project-header {
    text-align: center;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 2px solid #1D9E75;
  }
  .project-header h1 {
    font-size: 2rem;
    margin-bottom: 0.25rem;
    letter-spacing: 0.05em;
  }
  .project-meta {
    font-size: 0.85rem;
    color: #555;
    margin-top: 0.5rem;
  }
  .project-section {
    margin-bottom: 2rem;
  }
  .project-section h2 {
    font-size: 1rem;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: #1D9E75;
    border-bottom: 1px solid #e0e0e0;
    padding-bottom: 0.3rem;
    margin-bottom: 1rem;
  }
  .entry {
    margin-bottom: 1.25rem;
  }
  .entry-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.25rem;
  }
  .entry-title {
    font-weight: 700;
    font-size: 0.95rem;
  }
  .entry-meta {
    font-size: 0.8rem;
    color: #777;
    font-style: italic;
  }
  .entry ul {
    margin: 0.25rem 0 0 1.25rem;
    padding: 0;
  }
  .entry ul li {
    font-size: 0.875rem;
    line-height: 1.65;
    color: #333;
    margin-bottom: 0.2rem;
  }
  .tag-list {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-top: 0.4rem;
    margin-bottom: 0.6rem;
  }
  .tag {
    background: #E1F5EE;
    color: #0F6E56;
    font-size: 0.75rem;
    padding: 2px 10px;
    border-radius: 100px;
    font-family: monospace;
  }
  .info-badge {
    display: inline-block;
    background: #FFF8E1;
    color: #856404;
    font-size: 0.75rem;
    padding: 2px 10px;
    border-radius: 100px;
    margin-right: 6px;
    margin-top: 4px;
  }

  /* ---- Slideshow gallery ---- */
  .gallery {
    max-width: 760px;
    margin: 0 auto;
  }
  .gallery-stage {
    position: relative;
    border-radius: 10px;
    overflow: hidden;
    background: #f2f4f3;
  }
  .gallery-slide {
    display: none;
  }
  .gallery-slide.is-active {
    display: block;
  }
  .gallery-slide img {
    width: 100%;
    display: block;
    aspect-ratio: 4 / 3;
    object-fit: cover;
  }
  .gallery-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 42px;
    height: 42px;
    border: none;
    border-radius: 50%;
    background: rgba(15, 110, 86, 0.82);
    color: #fff;
    font-size: 1.1rem;
    line-height: 1;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.2s ease;
    z-index: 2;
  }
  .gallery-btn:hover {
    background: #0F6E56;
  }
  .gallery-btn.prev { left: 10px; }
  .gallery-btn.next { right: 10px; }
  .gallery-caption {
    text-align: center;
    font-size: 0.85rem;
    color: #555;
    line-height: 1.5;
    margin-top: 0.7rem;
    min-height: 1.4em;
  }
  .gallery-dots {
    display: flex;
    justify-content: center;
    gap: 8px;
    margin-top: 0.6rem;
  }
  .gallery-dot {
    width: 10px;
    height: 10px;
    padding: 0;
    border: none;
    border-radius: 50%;
    background: #cfe7df;
    cursor: pointer;
    transition: background 0.2s ease, transform 0.2s ease;
  }
  .gallery-dot.is-active {
    background: #1D9E75;
    transform: scale(1.25);
  }
  .gallery-counter {
    text-align: center;
    font-size: 0.75rem;
    color: #999;
    margin-top: 0.35rem;
  }

  @media (max-width: 600px) {
    .entry-header { flex-direction: column; }
    .gallery-btn { width: 36px; height: 36px; font-size: 1rem; }
  }
</style>

<div class="project-header">
  <h1>Multi-Cycle MIPS Processor</h1>
  <div class="project-meta">
    Aug 2025 – Nov 2025 &nbsp;·&nbsp; Computer Architecture &nbsp;·&nbsp; Wayne State University
  </div>
  <div style="margin-top:0.5rem;">
    <span class="info-badge">👥 Team of 3</span>
    <span class="info-badge">🖥️ Verilog / Cadence</span>
    <span class="info-badge">⚙️ 32-bit MIPS CPU</span>
  </div>
</div>

---

<div class="project-section">
<h2>Overview</h2>

<div class="entry">
  <p style="font-size:0.875rem; color:#333; line-height:1.7;">
    Designed and implemented a 32-bit multi-cycle MIPS processor in Verilog using a Mealy finite-state machine (FSM) control unit. Verified correctness through Cadence simulation using instruction-level test programs and waveform analysis.
  </p>
  <div class="tag-list">
    <span class="tag">Verilog</span>
    <span class="tag">Cadence Simulation</span>
    <span class="tag">Mealy FSM Control</span>
    <span class="tag">Multi-Cycle CPU Datapath</span>
  </div>
</div>
</div>

---

<div class="project-section">
<h2>Technical Details</h2>

<div class="entry">
  <ul>
    <li>Implemented a multi-cycle datapath (fetch, decode, execute, memory, write-back) coordinated by a Mealy FSM control unit.</li>
    <li>Developed Verilog modules for key processor components including control, ALU control/ops, register writes, memory reads/writes, and PC update/branch logic.</li>
    <li>Verified control signals and datapath behavior using Cadence waveforms and expected register/memory outcomes.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Key Results</h2>

<div class="entry">
  <ul>
    <li>Successfully executed R-type, I-type, and branch instructions (add, sub, addi, nor, lw, sw, beq, bne) on a 32-bit multi-cycle MIPS processor.</li>
    <li>Verified correct ALU operations, register updates, memory reads/writes, and program counter control using Cadence waveform simulations.</li>
    <li>Validated processor functionality using an instruction-level test program, including behavior equivalent to a custom load-with-increment (LWI) instruction.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Figures</h2>

<div class="gallery" id="mipsGallery">
  <div class="gallery-stage">
    <button class="gallery-btn prev" onclick="moveGallery(-1)" aria-label="Previous figure">&#10094;</button>

    <div class="gallery-slide is-active" data-caption="Fig 1: Multi-Cycle Datapath Diagram">
      <img src="{{ '/assets/images/mips/datapath-diagram.jpg' | relative_url }}" alt="Multi-Cycle MIPS Datapath Diagram" loading="lazy">
    </div>
    <div class="gallery-slide" data-caption="Fig 2: Cadence Waveform Simulation">
      <img src="{{ '/assets/images/mips/cadence-waveform.jpg' | relative_url }}" alt="Cadence waveform simulation output" loading="lazy">
    </div>
    <div class="gallery-slide" data-caption="Fig 3: Sample Summary of Test Results">
      <img src="{{ '/assets/images/mips/test-results-table.jpg' | relative_url }}" alt="Test results table from project report" loading="lazy">
    </div>
    <div class="gallery-slide" data-caption="Fig 4: Verilog Control Logic for Instruction Execution Stage">
      <img src="{{ '/assets/images/mips/verilog-code.jpg' | relative_url }}" alt="Verilog control logic code" loading="lazy">
    </div>

    <button class="gallery-btn next" onclick="moveGallery(1)" aria-label="Next figure">&#10095;</button>
  </div>

  <div class="gallery-caption">Fig 1: Multi-Cycle Datapath Diagram</div>

  <div class="gallery-dots">
    <button class="gallery-dot is-active" onclick="jumpGallery(0)" aria-label="Go to figure 1"></button>
    <button class="gallery-dot" onclick="jumpGallery(1)" aria-label="Go to figure 2"></button>
    <button class="gallery-dot" onclick="jumpGallery(2)" aria-label="Go to figure 3"></button>
    <button class="gallery-dot" onclick="jumpGallery(3)" aria-label="Go to figure 4"></button>
  </div>

  <div class="gallery-counter">1 / 4</div>
</div>
</div>

<script>
(function () {
  var gallery = document.getElementById('mipsGallery');
  if (!gallery) return;

  var slides  = gallery.querySelectorAll('.gallery-slide');
  var dots    = gallery.querySelectorAll('.gallery-dot');
  var caption = gallery.querySelector('.gallery-caption');
  var counter = gallery.querySelector('.gallery-counter');
  var current = 0;

  function render() {
    for (var i = 0; i < slides.length; i++) {
      var active = (i === current);
      slides[i].classList.toggle('is-active', active);
      dots[i].classList.toggle('is-active', active);
    }
    caption.textContent = slides[current].getAttribute('data-caption');
    counter.textContent = (current + 1) + ' / ' + slides.length;
  }

  window.moveGallery = function (dir) {
    current = (current + dir + slides.length) % slides.length;
    render();
  };

  window.jumpGallery = function (n) {
    current = n;
    render();
  };

  document.addEventListener('keydown', function (e) {
    if (e.key === 'ArrowLeft')  window.moveGallery(-1);
    if (e.key === 'ArrowRight') window.moveGallery(1);
  });

  render();
})();
</script>
