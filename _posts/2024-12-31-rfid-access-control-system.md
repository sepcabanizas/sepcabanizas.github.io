---
layout: single
title: "RFID Access Control System"
date: 2024-12-31
permalink: /projects/rfid-access-control-system/
author_profile: true
toc: true
toc_label: "Sections"
toc_icon: "key"
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
  <h1>RFID Access Control System</h1>
  <div class="project-meta">
    Oct 2024 – Dec 2024 &nbsp;·&nbsp; Electronics &nbsp;·&nbsp; Wayne State University
  </div>
  <div style="margin-top:0.5rem;">
    <span class="info-badge">👤 Individual Project</span>
    <span class="info-badge">🔌 Arduino / RC522</span>
    <span class="info-badge">🔒 Solenoid Lock Control</span>
  </div>
</div>

---

<div class="project-section">
<h2>Overview</h2>

<div class="entry">
  <p style="font-size:0.875rem; color:#333; line-height:1.7;">
    Designed and implemented an RFID-based electronic access control system that authenticates users using RFID tags and controls a 12V solenoid lock. The system provides real-time user feedback through an LCD, LEDs, and a buzzer, allowing secure and user-friendly entry verification.
  </p>
  <div class="tag-list">
    <span class="tag">Arduino</span>
    <span class="tag">RC522 RFID Module</span>
    <span class="tag">Solenoid Lock Control</span>
    <span class="tag">LCD Interface</span>
  </div>
</div>
</div>

---

<div class="project-section">
<h2>Technical Details</h2>

<div class="entry">
  <ul>
    <li>Integrated an RC522 RFID reader with an Arduino microcontroller to detect and read RFID tag identifiers, enabling secure user authentication. Programmed embedded logic to compare scanned tag IDs with authorized values stored in the system.</li>
    <li>Designed control circuitry to actuate a 12V solenoid lock using a transistor/relay driver when valid credentials were detected. Implemented a user feedback interface using an LCD, LEDs, and a buzzer to indicate successful or denied access attempts.</li>
  </ul>
</div>
</div>

---

<div class="project-section">
<h2>Key Results</h2>

<div class="entry">
  <ul>
    <li>Implemented an RFID-based authentication system using an Arduino and RC522 reader to detect and validate authorized RFID tags. The system controlled a 12V solenoid lock to allow secure electronic locking and unlocking.</li>
    <li>Provided real-time user feedback through an LCD, LEDs, and a buzzer to indicate successful or denied access attempts.</li>
  </ul>
</div>
</div>
