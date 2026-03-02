---
layout: page
title: Projects
icon: fas fa-project-diagram
order: 3
---

<style>
  :root {
    --project-teal: #008080; 
    --project-orange: #ff8c00; 
    --project-navy: #1a2a44;
  }
  .project-card { border-radius: 15px; border: none; transition: 0.3s; background: #fff; position: relative; }
  .project-card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
  .img-container { position: relative; overflow: hidden; border-radius: 15px 15px 0 0; }
  .badge-category { background: var(--project-teal); color: white; font-weight: bold; font-size: 0.7rem; }
  .text-brand-navy { color: var(--project-navy); font-weight: 800; font-size: 1.25rem; }
  .btn-view { background: var(--project-orange); color: white; font-weight: bold; border-radius: 30px; transition: 0.3s; text-decoration: none !important; }
  .btn-view:hover { background: var(--project-navy); color: white; }
  
  /* Read More Styling */
  details summary {
    cursor: pointer;
    color: var(--project-teal);
    font-weight: 700;
    outline: none;
    margin-bottom: 10px;
    list-style: none;
  }
  details summary::-webkit-details-marker { display: none; }
  details[open] summary { color: var(--project-navy); margin-bottom: 15px; }
  .details-content { border-left: 3px solid var(--project-orange); padding-left: 15px; margin-top: 10px; }
</style>

<div class="d-flex flex-wrap mb-5">
  <span class="badge badge-pill badge-dark p-2 px-3 mr-2 mb-2">All</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Data Science</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Machine Learning</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Web Development</span>
  <span class="badge badge-pill badge-light border p-2 px-3 mr-2 mb-2">Graphics Design</span>
</div>

<div class="row">

  <div class="col-md-6 mb-4">
    <div class="card project-card shadow-sm h-100">
      <div class="img-container">
        <img src="/assets/img/my_Thumbnail.jpg" class="card-img-top" alt="Netflix Data Wrangling">
        <div class="position-absolute" style="top: 12px; right: 12px;">
          <span class="badge badge-pill badge-category p-2 px-3 shadow">DATA SCIENCE</span>
        </div>
      </div>
      <div class="card-body p-4 d-flex flex-column">
        <h3 class="text-brand-navy mb-3">NETFLIX DATA WRANGLING</h3>
        
        <details>
          <summary><i class="fas fa-plus-circle mr-2"></i>Read Project Details</summary>
          <div class="details-content">
            <p class="card-text text-dark small mb-3">
              **The Challenge:** Raw Netflix datasets contain noise and inconsistencies[cite: 10, 67].
              <br><br>
              **The Solution:** Executed a full lifecycle: Cleaning (removing duplicates/nulls), Structuring (standardizing formats), and Validating[cite: 67].
            </p>
            <div class="mb-2">
              <span class="badge badge-light border text-navy">#Python</span>
              <span class="badge badge-light border text-navy">#Pandas</span>
              <span class="badge badge-light border text-navy">#Data_Wrangling</span>
            </div>
          </div>
        </details>

        <div class="mt-auto">
          <a href="https://www.kaggle.com/code/mishaelmomanyi/mishael-morara-netflix-data-wrangling" target="_blank" class="btn btn-view btn-block p-2 mt-2">
            <i class="fas fa-external-link-alt mr-2"></i> **EXPLORE ON KAGGLE**
          </a>
        </div>
      </div>
    </div>
  </div>

  <div class="col-md-6 mb-4">
    <div class="card project-card shadow-sm h-100">
      <div class="img-container">
        <img src="/assets/img/my_Thumbnail2.jpg" class="card-img-top" alt="Web Scraping Python">
        <div class="position-absolute" style="top: 12px; right: 12px;">
          <span class="badge badge-pill badge-category p-2 px-3 shadow">DATA SCIENCE</span>
        </div>
      </div>
      <div class="card-body p-4 d-flex flex-column">
        <h3 class="text-brand-navy mb-3">WEB SCRAPING USING PYTHON</h3>
        
        <details>
          <summary><i class="fas fa-plus-circle mr-2"></i>Read Project Details</summary>
          <div class="details-content">
            <p class="card-text text-dark small mb-3">
              **Objective:** Automate data extraction using `BeautifulSoup` and `requests`[cite: 72].
              <br><br>
              **Outcome:** Processed raw HTML into a structured Pandas DataFrame and exported to .csv[cite: 67, 72].
            </p>
            <div class="mb-2">
              <span class="badge badge-light border text-navy">#Python</span>
              <span class="badge badge-light border text-navy">#BeautifulSoup</span>
              <span class="badge badge-light border text-navy">#Web_Scraping</span>
            </div>
          </div>
        </details>

        <div class="mt-auto">
          <a href="https://colab.research.google.com/drive/1uYArj-ycabLCc004sUyZ45bO13G03xqq?usp=sharing" target="_blank" class="btn btn-view btn-block p-2 mt-2">
            <i class="fas fa-external-link-alt mr-2"></i> **VIEW ON GOOGLE COLAB**
          </a>
        </div>
      </div>
    </div>
  </div>

</div>
