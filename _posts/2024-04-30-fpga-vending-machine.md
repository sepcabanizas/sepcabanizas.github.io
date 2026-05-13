---
layout: single
title: "FPGA Vending Machine Controller"
categories: 
  - Project
date: 2024-04-30
permalink: /projects/fpga-vending-machine/
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
  <h1>FPGA Vending Machine Controller</h1>
  <div class="project-meta">
    Feb 2024 – Apr 2024 &nbsp;·&nbsp; Digital Logic &nbsp;·&nbsp; Wayne State University
  </div>
  <div style="margin-top:0.5rem;">
    <span class="info-badge">👥 Team of 3</span>
    <span class="info-badge">🔲 Nexys4 FPGA</span>
    <span class="info-badge">⚙️ Verilog / Vivado</span>
  </div>
</div>

---

<div class="project-section">
<h2>Overview</h2>

<div class="entry">
  <p style="font-size:0.875rem; color:#333; line-height:1.7;">
    Designed and simulated a vending machine controller using Verilog on a Nexys4 FPGA board. The system models coin insertion, product selection, and dispensing logic using a finite-state machine architecture.
  </p>
  <div class="tag-list">
    <span class="tag">Verilog</span>
    <span class="tag">Nexys4 FPGA</span>
    <span class="tag">Vivado</span>
    <span class="tag">Finite State Machines</span>
  </div>
</div>
</div>

---

<div class="project-section">
<h2>Technical Details</h2>

<div class="entry">
  <ul>
    <li>Implemented a finite-state machine (FSM) to manage system states, including idle, coin input, product selection, and dispense operations.</li>
    <li>Developed modular Verilog components, including a counter-based clock divider, FSM control logic, and a seven-segment display driver.</li>
    <li>Used switch inputs on the Nexys4 board to simulate coin insertion and product selection, with LEDs and seven-segment displays representing system outputs.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Key Results</h2>

<div class="entry">
  <ul>
    <li>Successfully demonstrated correct state transitions and vending logic behavior for candy and soda selections.</li>
    <li>Verified system functionality through simulation and FPGA testing, confirming proper coin handling and output responses.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Figures</h2>

<div class="entry">
  <ul>
    <li><strong>Fig 1:</strong> Top-Level Schematic of the Vending Machine</li>
    <li><strong>Fig 2:</strong> State Diagram of the Vending Machine</li>
    <li><strong>Fig 3:</strong> Two Coin Input with Candy Assertion (2 switches ON = Displays Proper Output)</li>
  </ul>
</div>
</div>
