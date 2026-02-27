---
layout: page
title: Projects
icon: fas fa-project-diagram
order: 3
---

<style>
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

  <div class="col-md-6 mb-4">
    <div class="card project-card shadow-sm h-100">
      <img src="https://via.placeholder.com/600x350" class="card-img-top" alt="Project Thumbnail">
      
      <div class="card-body">
        <div class="project-category">Machine Learning • 2024</div>
        <h4 class="project-title">PROJECT NAME HERE</h4>
        
        <p class="card-text text-muted small mt-2">
          **Problem Solved:** Describe the challenge this project addresses.
          <br>
          **Solution:** Explain how your code or design solved it effectively.
        </p>
        
        <div class="mb-3">
          <span class="badge badge-light border">#Python</span>
          <span class="badge badge-light border">#AI</span>
        </div>
        
        <a href="#" class="btn btn-project btn-sm shadow-sm">
          <i class="fas fa-external-link-alt mr-1"></i> VIEW PROJECT
        </a>
      </div>
    </div>
  </div>
  </div>
