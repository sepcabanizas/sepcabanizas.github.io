---
layout: single
title: "Multi-Cycle MIPS Processor"
categories: Project
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
  @media (max-width: 600px) {
    .entry-header { flex-direction: column; }
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

<div class="entry">
  <ul>
    <li><strong>Fig 1:</strong> Sample Summary of Test Results (from Project Report)</li>
    <li><strong>Fig 2:</strong> Verilog Control Logic for instruction execution stage</li>
  </ul>
</div>
</div>
