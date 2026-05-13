---
layout: single
title: "Pendulum Tracking and Modeling System"
categories: Project
date: 2024-12-31
permalink: /projects/pendulum-tracking-modeling-system/
author_profile: true
toc: true
toc_label: "Sections"
toc_icon: "wave-square"
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
  <h1>Pendulum Tracking and Modeling System</h1>
  <div class="project-meta">
    Aug 2024 – Dec 2024 &nbsp;·&nbsp; Numerical Methods &nbsp;·&nbsp; Wayne State University
  </div>
  <div style="margin-top:0.5rem;">
    <span class="info-badge">👥 Team of 3</span>
    <span class="info-badge">🔌 Arduino / HC-SR04</span>
    <span class="info-badge">📊 MATLAB AppDesigner</span>
  </div>
</div>

---

<div class="project-section">
<h2>Overview</h2>

<div class="entry">
  <p style="font-size:0.875rem; color:#333; line-height:1.7;">
    Developed a system to measure and model the motion of a swinging pendulum using an ultrasonic distance sensor and Arduino. Experimental data were collected in real time and analyzed using a MATLAB AppDesigner GUI to calculate oscillation periods and compare theoretical predictions with measured motion.
  </p>
  <div class="tag-list">
    <span class="tag">Arduino</span>
    <span class="tag">HC-SR04 Ultrasonic Sensor</span>
    <span class="tag">MATLAB</span>
    <span class="tag">MATLAB AppDesigner</span>
  </div>
</div>
</div>

---

<div class="project-section">
<h2>Technical Details</h2>

<div class="entry">
  <ul>
    <li>Built a hardware data acquisition system using an HC-SR04 ultrasonic sensor and Arduino to measure pendulum displacement and collect time-series motion data.</li>
    <li>Developed a MATLAB AppDesigner GUI to visualize oscillation behavior, compute pendulum periods, and compare experimental results with Euler's method simulations and polynomial regression models.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Key Results</h2>

<div class="entry">
  <ul>
    <li>Successfully collected time-series motion data for pendulums with varying string lengths.</li>
    <li>Computed pendulum oscillation periods using zero-crossing detection and numerical interpolation methods.</li>
    <li>Compared experimental motion data with Euler's method simulations and regression models, achieving an average error of approximately 15.6%.</li>
  </ul>
</div>
</div>
