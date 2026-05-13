---
layout: single
title: "Autonomous Soil Analysis Rover"
categories: Project
date: 2026-04-30
permalink: /projects/autonomous-soil-analysis-rover/
author_profile: true
toc: true
toc_label: "Sections"
toc_icon: "satellite"
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
  <h1>Autonomous Soil Analysis Rover</h1>
  <div class="project-meta">
    Jan 2026 – Apr 2026 &nbsp;·&nbsp; Capstone Senior Design &nbsp;·&nbsp; Wayne State University
  </div>
  <div style="margin-top:0.5rem;">
    <span class="info-badge">👥 Team of 4</span>
    <span class="info-badge">🤖 ESP32 / Raspberry Pi</span>
    <span class="info-badge">🌱 Soil Sensor Integration</span>
  </div>
</div>

---

<div class="project-section">
<h2>Overview</h2>

<div class="entry">
  <p style="font-size:0.875rem; color:#333; line-height:1.7;">
    Developed a rover platform for soil data collection and environmental monitoring as part of the Capstone Senior Design project. The system integrates embedded motor control, wireless communication, and soil sensing hardware to support mobile agricultural data acquisition.
  </p>
  <div class="tag-list">
    <span class="tag">ESP32</span>
    <span class="tag">Arduino</span>
    <span class="tag">Raspberry Pi</span>
    <span class="tag">PWM Motor Control</span>
    <span class="tag">DC Motors</span>
    <span class="tag">Embedded Systems</span>
  </div>
</div>
</div>

---

<div class="project-section">
<h2>Technical Details</h2>

<div class="entry">
  <ul>
    <li>Developed an ESP32-based autonomous rover with Bluetooth control and line-following navigation for soil data collection.</li>
    <li>Designed the embedded system architecture integrating ESP32, motor drivers, and sensors for autonomous rover operation.</li>
    <li>Implemented autonomous line-following using PWM differential steering for precise dual-motor control.</li>
    <li>Integrated an 8-parameter soil sensor and servo-actuated sampling arm for automated multi-depth soil data collection.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Current Progress</h2>

<div class="entry">
  <ul>
    <li>Successfully established Bluetooth communication between the controller and the ESP32 rover platform.</li>
    <li>Verified motor driver control and rover mobility using PWM differential steering.</li>
    <li>Confirmed operation of the multi-parameter soil sensor for environmental data collection.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Figures</h2>

<div class="entry">
  <ul>
    <li><strong>Fig 1:</strong> Chassis during assembly stage</li>
    <li><strong>Fig 2:</strong> Voltage Regulator Circuit</li>
    <li><strong>Fig 3:</strong> Circuit all connected without frying the ESP32</li>
    <li><strong>Fig 4:</strong> Snippet from video showing the Rover being controlled via Bluetooth controller</li>
    <li><strong>Fig 5:</strong> Circuit verifying Soil Probe works</li>
  </ul>
</div>
</div>
