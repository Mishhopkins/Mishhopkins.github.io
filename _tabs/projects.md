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
  .project-card { border-radius: 15px; border: none; transition: 0.3s; background: #fff; }
  .project-card:hover { transform: translateY(-8px); box-shadow: 0 12px 24px rgba(0,0,0,0.15); }
  .img-container { position: relative; overflow: hidden; border-radius: 15px 15px 0 0; }
  .badge-category { background: var(--project-teal); color: white; font-weight: bold; }
  .text-brand-navy { color: var(--project-navy); font-weight: 800; }
  .btn-view { background: var(--project-orange); color: white; font-weight: bold; border-radius: 30px; border: none; transition: 0.3s; }
  .btn-view:hover { background: var(--project-navy); color: white; text-decoration: none; }
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
        <h3 class="text-brand-navy mb-3 text-uppercase">Netflix Data Wrangling</h3>
        <p class="card-text text-dark mb-4 small">
          **The Challenge:** Transform raw Netflix Movies and TV Shows datasets into high-quality, actionable data.
          <br><br>
          **The Solution:** Executed a full data lifecycle:
          1. **Cleaning**: Removed duplicates, null values, and formatting errors.
          2. **Structuring**: Normalized and standardized formats for consistency.
          3. **Validating**: Verified accuracy and quality for reliable downstream analytics.
        </p>
        <div class="mb-4">
          <span class="badge badge-light border text-navy">#Python</span>
          <span class="badge badge-light border text-navy">#Pandas</span>
          <span class="badge badge-light border text-navy">#Data_Cleaning</span>
        </div>
        <a href="https://www.kaggle.com/code/mishaelmomanyi/mishael-morara-netflix-data-wrangling" target="_blank" class="btn btn-view btn-block p-2">
          <i class="fas fa-external-link-alt mr-2"></i> **EXPLORE ON KAGGLE**
        </a>
      </div>
    </div>
  </div>
<!-- ....................................... Project 2.................................................. -->
  <div class="col-md-6 mb-5">
    <div class="card project-card shadow-sm h-100">
      <div class="img-container">
        <img src="/assets/img/my_Thumbnail2.png" class="card-img-top" alt="Web Scraping Python">
        <div class="position-absolute" style="top: 15px; right: 15px;">
          <span class="badge badge-pill badge-category p-2 px-3 shadow">DATA SCIENCE</span>
        </div>
      </div>
      <div class="card-body p-4">
        <div class="d-flex justify-content-between align-items-center mb-2">
          <small class="text-muted"><i class="far fa-calendar-alt mr-1"></i> Jan 17, 2026</small>
        </div>
        <h3 class="text-brand-navy mb-3 text-uppercase">Web Scraping using Python</h3>
        <p class="card-text text-dark mb-4 small">
          **The Challenge:** Extracting specific information from web pages and converting it into structured formats for analysis.
          <br><br>
          **The Objectives:** 1. **Automated Extraction**: Used `requests` and `BeautifulSoup` to pull data from web pages.
          2. **Data Parsing**: Cleaned and structured the raw HTML output.
          3. **Storage**: Integrated the data into a **Pandas DataFrame** and exported to **.csv** for portability.
        </p>
        <div class="mb-4">
          <span class="badge badge-light border text-navy">#Python</span>
          <span class="badge badge-light border text-navy">#BeautifulSoup</span>
          <span class="badge badge-light border text-navy">#Data_Extraction</span>
          <span class="badge badge-light border text-navy">#Colab</span>
        </div>
        <a href="https://colab.research.google.com/drive/1uYArj-ycabLCc004sUyZ45bO13G03xqq?usp=sharing" target="_blank" class="btn btn-view btn-block p-2">
          <i class="fas fa-external-link-alt mr-2"></i> **VIEW ON GOOGLE COLAB**
        </a>
      </div>
    </div>
  </div>

</div>
