---
layout: page
title: About Me
icon: fas fa-info-circle
order: 1
---

<style>
  :root {
    --brand-orange: #ff8c00;
    --brand-navy: #1a2a44;
    --glass-bg: rgba(26, 42, 68, 0.03);
  }

  /* Hero Section */
  .hero-banner {
    background: linear-gradient(135deg, var(--brand-navy) 0%, #2c3e50 100%);
    color: white;
    padding: 40px;
    border-radius: 20px;
    border-left: 10px solid var(--brand-orange);
    margin-bottom: 40px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.2);
  }

  .hero-title {
    font-weight: 900;
    font-size: 2.2rem;
    color: var(--brand-orange);
    margin-bottom: 10px;
  }

  /* Pillar Cards */
  .pillar-card {
    background: transparent;
    border: 1px solid rgba(108, 117, 125, 0.2);
    border-radius: 15px;
    transition: 0.3s ease;
    height: 100%;
  }

  .pillar-card:hover {
    border-color: var(--brand-orange);
    transform: translateY(-5px);
    background: var(--glass-bg);
  }

  .pillar-icon {
    font-size: 2rem;
    color: var(--brand-orange);
    margin-bottom: 15px;
  }

  /* Quick Navigation Buttons */
  .nav-btn {
    border: 2px solid var(--brand-navy);
    color: var(--brand-navy);
    font-weight: 700;
    border-radius: 30px;
    padding: 10px 25px;
    transition: 0.3s;
    text-decoration: none !important;
    display: inline-block;
    margin: 5px;
  }

  .nav-btn:hover {
    background: var(--brand-navy);
    color: white;
    transform: scale(1.05);
  }

  .nav-btn.active-btn {
    background: var(--brand-orange);
    border-color: var(--brand-orange);
    color: white;
  }

  .highlight-text {
    color: var(--brand-orange);
    font-weight: 700;
  }
</style>

<div class="hero-banner">
  <small class="text-uppercase" style="letter-spacing: 2px; opacity: 0.8;">Securing the Intelligence Era</small>
  <h1 class="hero-title">I'm Mishael Morara</h1>
  <p style="font-size: 1.15rem; line-height: 1.6; opacity: 0.9;">
    An <span class="highlight-text">AI Security Guardian</span> dedicated to securing the next generation of intelligent systems. I specialize in the design of autonomous <span class="highlight-text">'Zero Trust’</span> frameworks where AI monitors and protects AI.
  </p>
</div>

<div class="row mb-5">
  <div class="col-md-4 mb-4">
    <div class="card pillar-card p-4">
      <div class="pillar-icon"><i class="fas fa-shield-alt"></i></div>
      <h5 class="font-weight-bold">AI Guardrails</h5>
      <p class="small text-muted">Building robust security layers to ensure organizations scale AI power without compromising data integrity.</p>
    </div>
  </div>
  <div class="col-md-4 mb-4">
    <div class="card pillar-card p-4">
      <div class="pillar-icon"><i class="fas fa-microchip"></i></div>
      <h5 class="font-weight-bold">Zero Trust Architecture</h5>
      <p class="small text-muted">Implementing foundational security where every AI interaction is verified, monitored, and protected.</p>
    </div>
  </div>
  <div class="col-md-4 mb-4">
    <div class="card pillar-card p-4">
      <div class="pillar-icon"><i class="fas fa-user-lock"></i></div>
      <h5 class="font-weight-bold">Stakeholder Trust</h5>
      <p class="small text-muted">Ensuring that innovation remains a foundational feature of the business, never an afterthought.</p>
    </div>
  </div>
</div>

<div class="text-center mt-5">
  <h4 class="font-weight-bold mb-4">Explore My Work</h4>
  <div class="d-flex justify-content-center flex-wrap">
    <a href="/projects/" class="nav-btn active-btn shadow-sm">
      <i class="fas fa-code mr-2"></i> View Projects
    </a>
    <a href="/resume/" class="nav-btn">
      <i class="fas fa-file-alt mr-2"></i> Read Resume
    </a>
    <a href="/contacts/" class="nav-btn">
      <i class="fas fa-paper-plane mr-2"></i> Get In Touch
    </a>
  </div>
</div>

---

### My Philosophy
> "As organizations scale their AI power, they must do so without compromising the integrity of their data or the trust of their stakeholders. I build the systems that make that possible."
