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

  .contact-header {
    background: linear-gradient(135deg, var(--brand-navy) 0%, #2c3e50 100%);
    color: white;
    padding: 40px;
    border-radius: 15px;
    margin-bottom: 30px;
    border-left: 8px solid var(--brand-orange);
  }

  .contact-card {
    background: #fff;
    border: none;
    border-radius: 12px;
    transition: 0.3s;
    height: 100%;
    border-bottom: 3px solid transparent;
  }

  .contact-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-bottom: 3px solid var(--brand-orange);
  }

  .icon-box {
    width: 50px;
    height: 50px;
    background: rgba(26, 42, 68, 0.1);
    color: var(--brand-navy);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    margin-bottom: 15px;
  }

  .contact-link {
    color: var(--brand-navy);
    font-weight: 700;
    text-decoration: none !important;
  }

  .contact-link:hover {
    color: var(--brand-orange);
  }

  .availability-badge {
    background: var(--brand-orange);
    color: white;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.8rem;
    font-weight: bold;
  }
</style>

<div class="contact-header shadow-lg">
  <h2 class="text-white">**Let's Work Together**</h2>
  <p class="mb-0">I am currently open to **Cybersecurity collaborations**, **AI Security consultations**, and **Data Science projects**. Reach out and let’s build something secure.</p>
</div>

<div class="row">
  <div class="col-md-4 mb-4">
    <div class="card contact-card shadow-sm p-4">
      <div class="icon-box"><i class="fas fa-envelope"></i></div>
      <h5>**Email**</h5>
      <p class="small text-muted">For formal inquiries and project proposals.</p>
      <a href="mailto:mishaelmorara@gmail.com" class="contact-link">mishaelmorara@gmail.com</a>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card contact-card shadow-sm p-4">
      <div class="icon-box"><i class="fab fa-linkedin"></i></div>
      <h5>**LinkedIn**</h5>
      <p class="small text-muted">For professional networking and industry updates.</p>
      <a href="https://www.linkedin.com/in/mishael-momanyi" target="_blank" class="contact-link">Connect with Me</a>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card contact-card shadow-sm p-4">
      <div class="icon-box"><i class="fab fa-github"></i></div>
      <h5>**GitHub**</h5>
      <p class="small text-muted">Explore my source code and technical repositories.</p>
      <a href="https://github.com/Mishhopkins" target="_blank" class="contact-link">View Projects</a>
    </div>
  </div>
</div>

<div class="row mt-2">
  <div class="col-md-6 mb-4">
    <div class="card contact-card shadow-sm p-4">
      <div class="d-flex justify-content-between">
        <div class="icon-box"><i class="fab fa-whatsapp"></i></div>
        <div><span class="availability-badge">ACTIVE</span></div>
      </div>
      <h5>**Phone & WhatsApp**</h5>
      <a href="tel:+254718045860" class="contact-link" style="font-size: 1.2rem;">+254 718 045 860</a>
    </div>
  </div>

  <div class="col-md-6 mb-4">
    <div class="card contact-card shadow-sm p-4">
      <div class="icon-box"><i class="fas fa-map-marker-alt"></i></div>
      <h5>**Location**</h5>
      <p class="contact-link mb-0">Nairobi, Kenya</p>
      <small class="text-muted">Available for remote work worldwide.</small>
    </div>
  </div>
</div>

> **Pro Tip:** When sending an email, please include **[Project Inquiry]** in the subject line for a faster response!
