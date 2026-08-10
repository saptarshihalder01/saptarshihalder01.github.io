---
layout: default
title: Home
---

<!-- FontAwesome Icons for Social Media & Education -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
  .profile-container {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    margin-top: 25px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }
  
  .sidebar {
    flex: 1;
    min-width: 220px;
    max-width: 260px;
    text-align: center;
  }

  .profile-img {
    width: 190px;
    height: 190px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 15px;
  }

  .name {
    font-size: 26px;
    font-weight: 600;
    color: #222;
    margin: 5px 0;
  }

  .role {
    font-size: 14px;
    color: #666;
    margin-bottom: 6px;
    line-height: 1.3;
  }

  .affiliation {
    font-size: 14px;
    color: #2b6cb0;
    text-decoration: none;
    display: block;
    margin-bottom: 18px;
  }

  .affiliation:hover {
    text-decoration: underline;
  }

  .social-icons {
    display: flex;
    justify-content: center;
    gap: 14px;
    font-size: 22px;
  }

  .social-icons a {
    color: #2b6cb0;
    transition: color 0.2s ease;
  }

  .social-icons a:hover {
    color: #1a4971;
  }

  .main-content {
    flex: 2;
    min-width: 300px;
  }

  .main-content h2 {
    font-size: 30px;
    font-weight: 400;
    color: #333;
    margin-top: 0;
    margin-bottom: 20px;
    border: none;
  }

  .main-content p {
    line-height: 1.65;
    color: #444;
    font-size: 15px;
    margin-bottom: 16px;
  }

  .info-grid {
    display: flex;
    gap: 40px;
    margin-top: 35px;
    flex-wrap: wrap;
  }

  .info-column {
    flex: 1;
    min-width: 200px;
  }

  .info-column h3 {
    font-size: 18px;
    font-weight: 600;
    color: #222;
    margin-bottom: 12px;
    border: none;
  }

  .info-column ul {
    padding-left: 20px;
    margin: 0;
  }

  .info-column li {
    margin-bottom: 8px;
    color: #555;
    font-size: 14px;
  }

  .education-item {
    display: flex;
    gap: 12px;
    align-items: flex-start;
  }

  .education-item i {
    font-size: 16px;
    color: #333;
    margin-top: 3px;
  }

  .degree {
    font-weight: 600;
    font-size: 14px;
    color: #333;
  }

  .institution {
    font-size: 13px;
    color: #777;
    margin-top: 2px;
  }
</style>

<div class="profile-container">
  
  <div class="sidebar">
    <img src="DSC_5929.jpg" alt="Saptarshi Halder" class="profile-img">
    <div class="name">Saptarshi Halder</div>
    <div class="role">Researcher in Mathematics & Geometric Analysis</div>
    <a href="#" class="affiliation">Department of Mathematics</a>
    
    <div class="social-icons">
      <a href="mailto:your.email@institution.edu" title="Email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://x.com" title="Twitter/X"><i class="fa-brands fa-x-twitter"></i></a>
      <a href="https://scholar.google.com" title="Google Scholar"><i class="fa-solid fa-graduation-cap"></i></a>
      <a href="https://linkedin.com" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
    </div>
  </div>

  <div class="main-content">
    <h2>About me</h2>
    
    <p>
      I am a researcher in mathematics specializing in <strong>Complex Geometry</strong>, 
      <strong>Differential Geometry</strong>, and <strong>Geometric Analysis</strong>. My work focuses on 
      geometric operators, Ricci curvature tensors, Bochner-type formulas, and heat kernels on Riemannian manifolds.
    </p>

    <div class="info-grid">
      
      <div class="info-column">
        <h3>Interests</h3>
        <ul>
          <li>Complex Geometry</li>
          <li>Differential Geometry</li>
          <li>Functional Analysis</li>
          <li>Abstract Algebra</li>
        </ul>
      </div>

      <div class="info-column">
        <h3>Education</h3>
        <div class="education-item">
          <i class="fa-solid fa-graduation-cap"></i>
          <div>
            <div class="degree">Ph.D. in Mathematics</div>
            <div class="institution">Your University / Institution</div>
          </div>
        </div>
      </div>

    </div>

  </div>

</div>
