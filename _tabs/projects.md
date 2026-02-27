---
layout: page
title: Projects
icon: fas fa-project-diagram
order: 3
---
<style>
  :root {
    --project-teal: #008080; /* Teal from your thumbnail */
    --project-orange: #ff8c00; /* Your brand orange */
    --project-navy: #1a2a44;
  }
  .project-card { border-radius: 15px; border: none; transition: 0.3s; background: #fff; }
  .project-card:hover { transform: translateY(-8px); box-shadow: 0 12px 24px rgba(0,0,0,0.15); }
  .img-container { position: relative; overflow: hidden; border-radius: 15px 15px 0 0; }
  .badge-category { background: var(--project-teal); color: white; font-weight: bold; }
  .text-brand-navy { color: var(--project-navy); font-weight: 800; }
  .btn-view { background: var(--project-orange); color: white; font-weight: bold; border-radius: 30px; border: none; transition: 0.3s; }
  .btn-view:hover { background: var(--project-navy); color: white; }

  .project-card {
    border: none;
    transition: transform 0.3s ease, shadow 0.3s ease;
    border-radius: 12px;
    overflow: hidden;
    background: #fff;
  }
  .project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
  }
  .project-category {
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 700;
    color: #ff8c00; /* Your Brand Orange */
  }
  .project-title {
    font-size: 1.4rem;
    font-weight: 800;
    color: #1a2a44; /* Your Brand Navy */
    margin-top: 5px;
  }
  .btn-project {
    background: #1a2a44;
    color: #fff;
    font-weight: 600;
    border-radius: 25px;
    padding: 8px 20px;
    font-size: 0.9rem;
  }
  .btn-project:hover {
    background: #ff8c00;
    color: #fff;
  }
</style>

<div class="d-flex flex-wrap mb-5">
  <span class="badge badge-pill badge-dark p-2 px-3 mr-2 mb-2">All</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Data Science</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Machine Learning</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Web Development</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Graphics Design</span>
</div>

<div class="row">

  <div class="col-md-6 mb-5">
    <div class="card project-card shadow-sm h-100">
      
      <div class="img-container">
        <img src="/assets/img/my_Thumbnail.jpg" class="card-img-top" alt="Netflix Data Wrangling">
        <div class="position-absolute" style="top: 15px; right: 15px;">
          <span class="badge badge-pill badge-category p-2 px-3 shadow">DATA SCIENCE</span>
        </div>
      </div>
      
      <div class="card-body p-4">
        <div class="d-flex justify-content-between align-items-center mb-2">
          <small class="text-muted"><i class="far fa-calendar-alt mr-1"></i> Jan 25, 2026</small>
        </div>
        
        <h3 class="text-brand-navy mb-3">NETFLIX DATA WRANGLING PROJECT</h3>
        
        <p class="card-text text-dark mb-4">
          **The Challenge:** Raw datasets from Netflix often contain significant noise, duplicates, and inconsistent formatting that prevent accurate analysis[cite: 1, 10, 11].
          <br><br>
          **The Solution:** I performed a full data lifecycle transformation:
          1. **Cleaning**: Eliminated errors, null values, and redundant duplicates.
          2. **Structuring**: Standardized formats and normalized data for consistency.
          3. **Validating**: Ensured high-quality, accurate data ready for advanced analytics.
        </p>
        
        <div class="mb-4">
          <span class="badge badge-light border text-navy">#Python</span>
          <span class="badge badge-light border text-navy">#Pandas</span>
          <span class="badge badge-light border text-navy">#Data_Cleaning</span>
          <span class="badge badge-light border text-navy">#Kaggle</span>
        </div>
        
        <a href="https://www.kaggle.com/code/mishaelmomanyi/mishael-morara-netflix-data-wrangling" target="_blank" class="btn btn-view btn-block p-2">
          <i class="fas fa-external-link-alt mr-2"></i> **EXPLORE ON KAGGLE**
        </a>
      </div>
    </div>
  </div>

  </div>
        </a>
      </div>
    </div>
  </div>
  </div>
