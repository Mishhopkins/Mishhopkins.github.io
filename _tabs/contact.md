---
layout: page  
title: My Contacts
permalink: /contacts/
icon: fas fa-paper-plane
order: 4
---

<style>
  :root {
    --brand-orange: #ff8c00;
    --brand-navy: #1a2a44;
  }

  /* Adaptive Text Color for the Header Title */
  .contact-title {
    color: var(--brand-orange) !important;
    font-weight: 900;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  .contact-header {
    background: rgba(26, 42, 68, 0.05); /* Very light navy tint */
    padding: 30px;
    border-radius: 15px;
    margin-bottom: 30px;
    border: 1px solid rgba(255, 140, 0, 0.3); /* Subtle orange border */
    border-left: 8px solid var(--brand-orange);
  }

  .contact-card {
    background: transparent; /* Allows theme to handle light/dark mode */
    border: 1.5px solid rgba(108, 117, 125, 0.2); /* Subtle adaptive border */
    border-radius: 12px;
    transition: 0.3s ease-in-out;
    height: 100%;
  }

  .contact-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(255, 140, 0, 0.15);
    border-color: var(--brand-orange); /* Border glows orange on hover */
  }

  .icon-box {
    width: 45px;
    height: 45px;
    background: var(--brand-navy);
    color: var(--brand-orange); /* Orange icon on Navy background */
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.3rem;
    margin-bottom: 15px;
  }

  .contact-link {
    color: var(--brand-orange);
    font-weight: 700;
    text-decoration: none !important;
    word-break: break-word;
  }

  .contact-link:hover {
    text-decoration: underline !important;
    filter: brightness(1.2);
  }

  .availability-badge {
    background: var(--brand-orange);
    color: white;
    padding: 3px 12px;
    border-radius: 20px;
    font-size: 0.75rem;
    font-weight: bold;
  }
</style>

<div class="contact-header">
  <h2 class="contact-title">Let's Work Together</h2>
  <p class="mb-0">I am currently open to **Cybersecurity collaborations**, **AI Security consultations**, and **Data Science projects**. Reach out and let’s build something secure.</p>
</div>

<div class="row">
  <div class="col-md-4 mb-4">
    <div class="card contact-card p-4">
      <div class="icon-box"><i class="fas fa-envelope"></i></div>
      <h5 class="font-weight-bold">Email</h5>
      <p class="small text-muted">For formal inquiries and proposals.</p>
      <a href="mailto:mishaelmorara@gmail.com" class="contact-link">mishaelmorara@gmail.com</a>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card contact-card p-4">
      <div class="icon-box"><i class="fab fa-linkedin"></i></div>
      <h5 class="font-weight-bold">LinkedIn</h5>
      <p class="small text-muted">Professional networking and updates.</p>
      <a href="https://www.linkedin.com/in/mishael-momanyi" target="_blank" class="contact-link">Connect with Me</a>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card contact-card p-4">
      <div class="icon-box"><i class="fab fa-github"></i></div>
      <h5 class="font-weight-bold">GitHub</h5>
      <p class="small text-muted">Explore my technical repositories.</p>
      <a href="https://github.com/Mishhopkins" target="_blank" class="contact-link">View Projects</a>
    </div>
  </div>
</div>

<div class="row mt-2">
  <div class="col-md-6 mb-4">
    <div class="card contact-card p-4">
      <div class="d-flex justify-content-between">
        <div class="icon-box"><i class="fab fa-whatsapp"></i></div>
        <div><span class="availability-badge">ACTIVE</span></div>
      </div>
      <h5 class="font-weight-bold">Phone & WhatsApp</h5>
      <a href="tel:+254718045860" class="contact-link" style="font-size: 1.2rem;">+254 718 045 860</a>
    </div>
  </div>

  <div class="col-md-6 mb-4">
    <div class="card contact-card p-4">
      <div class="icon-box"><i class="fas fa-map-marker-alt"></i></div>
      <h5 class="font-weight-bold">Location</h5>
      <p class="mb-0">**Nairobi, Kenya**</p>
      <small class="text-muted">Available for remote work worldwide.</small>
    </div>
  </div>
</div>

> **Note:** For a faster response, please include **[Project Inquiry]** in the subject line!
