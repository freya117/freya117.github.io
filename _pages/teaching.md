---
title: "Teaching"
permalink: /teaching/
layout: single
author_profile: true
header:
  overlay_color: "#ffffff"
---

<style>
  /* Make all content smaller */
  .page__content {
    font-size: 0.7em;
    padding-top: 0;
  }
  
  /* Style the page title to align with content */
  .page__title {
    color: #0033A0 !important;
    font-size: 1.8em !important;
    font-weight: bold !important;
    margin-bottom: 1em !important;
    margin-top: 0 !important;
    text-decoration: none !important;
    border-bottom: none !important;
    max-width: 1024px !important;
    margin-left: auto !important;
    margin-right: auto !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
  
  /* Remove any border/underline from title links */
  .page__title a {
    text-decoration: none !important;
    border-bottom: none !important;
  }
  
  /* Make header much more compact */
  .page__hero-caption {
    text-align: left !important;
  }
  
  .teaching-item {
    display: flex;
    margin-bottom: 1.5em;
    padding-bottom: 0.7em;
    border-bottom: 1px solid #f2f3f3;
    gap: 1em;
  }
  
  .teaching-item:last-child {
    margin-bottom: 0.5em;
  }
  
  .teaching-image {
    flex: 0 0 140px;
    width: 140px;
    height: 105px;
    
    a {
      display: block;
      width: 100%;
      height: 100%;
      text-decoration: none;
      
      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 4px;
        transition: transform 0.2s ease, opacity 0.2s ease;
      }
      
      &:hover {
        img {
          transform: scale(1.02);
          opacity: 0.9;
        }
      }
    }
  }
  
  .teaching-content {
    flex: 1;
    
    h4 {
      font-size: 0.9em;
      font-weight: bold;
      margin-bottom: 0.3em;
      margin-top: 0;
      
      a {
        color: #2c3e50 !important;
        text-decoration: none !important;
        font-size: 1em !important;
        font-weight: 600 !important;
        line-height: 1.3 !important;
        display: block;
        
        &:hover {
          color: #1a252f !important;
          text-decoration: none !important;
        }
        
        &:visited {
          color: #2c3e50 !important;
        }
        
        &:focus {
          color: #2c3e50 !important;
          outline: none;
        }
      }
    }
  }
  
  .teaching-role {
    font-size: 0.8em;
    margin-bottom: 0.3em;
    color: #666;
  }
  
  .teaching-period {
    font-style: italic;
    font-size: 0.75em;
    margin-bottom: 0.4em;
    color: #888;
  }
  
  .teaching-description {
    font-size: 0.75em;
    margin-top: 0.4em;
    color: #555;
    line-height: 1.3;
  }
  
  .teaching-description ul {
    margin-top: 0.3em;
    margin-bottom: 0;
    padding-left: 1.5em;
  }
  
  .teaching-description li {
    margin-bottom: 0.3em;
  }
  
  .teaching-year {
    font-weight: bold;
    font-size: 1.2em;
    color: #0033A0;
    margin-top: 1.3em;
    margin-bottom: 0.7em;
    padding-bottom: 0.3em;
    border-bottom: 2px solid #f2f3f3;
  }
  
  // Mobile responsive adjustments
  @media (max-width: 768px) {
    .teaching-item {
      flex-direction: column;
      gap: 0.5em;
      
      .teaching-image {
        flex: none;
        width: 100%;
        height: 175px;
        
        a {
          &:hover {
            img {
              transform: none;
              opacity: 1;
            }
          }
        }
      }
      
      .teaching-content {
        h4 {
          a {
            &:hover {
              color: #2c3e50 !important;
            }
          }
        }
      }
    }
  }
</style>

<div class="teaching-year">2025 - Present</div>

<div class="teaching-item">
  <div class="teaching-image">
    <a href="/courses/ai-urban-energy/" target="_blank">
      <img src="/assets/images/teaching/kaufman-certificate.jpg" alt="Kaufman Teaching Certificate Program">
    </a>
  </div>
  <div class="teaching-content">
    <h4>
      <a href="/courses/ai-urban-energy/" target="_blank">
        Kaufman Teaching Certificate Program @ MIT Teaching and Learning Lab
      </a>
    </h4>
    <div class="teaching-role">
      Cohort participant (Spring 2025)
    </div>
    <div class="teaching-period">
      Sep 2025 - Present
    </div>
    <div class="teaching-description">
      <ul>
        <li>Developed <em>AI for Sustainable Urban Energy Systems</em> as a complete course package, including course description, week-by-week syllabus, unit-level ILOs, formative & summative assessments, rubrics, and active-learning lesson plans.</li>
        <li>Completed 8 workshops and delivered 2 microteaching sessions, applied assessment alignment, scaffolding, inclusive teaching practices, and structured feedback to iterate materials based on peer and instructor review.</li>
      </ul>
    </div>
  </div>
</div>

<div class="teaching-item">
  <div class="teaching-image">
    <img src="/assets/images/teaching/cybersecurity-clinic.jpg" alt="Cybersecurity Clinic">
  </div>
  <div class="teaching-content">
    <h4>
      Teaching Assistant @ MIT
    </h4>
    <div class="teaching-role">
      11.074/274 Cybersecurity Clinic | Supervisor: Lawrence Susskind & Jungwoo Chun
    </div>
    <div class="teaching-period">
      Fall 2025 & Spring 2026 | Sep 2025 - Present
    </div>
    <div class="teaching-description">
      <ul>
        <li>Supported teams in data-driven cybersecurity assessments for public agencies and hospitals, coached analysis workflows, reviewed technical deliverables, and ensured alignment with NIST standards.</li>
        <li>Lead 2 weekly lab sessions with prepared labs and supplementary materials; emphasized problem framing and evidence collection.</li>
      </ul>
    </div>
  </div>
</div>

<div class="teaching-item">
  <div class="teaching-image">
    <img src="/assets/images/teaching/pedestrian-modeling.jpg" alt="Modeling Pedestrian Activity">
  </div>
  <div class="teaching-content">
    <h4>
      Teaching Assistant @ MIT
    </h4>
    <div class="teaching-role">
      11.024/324 Modeling Pedestrian Activity in Cities | Supervisor: Andres Sevtsuk
    </div>
    <div class="teaching-period">
      Spring 2025 | Jan 2025 - May 2025
    </div>
    <div class="teaching-description">
      <ul>
        <li>Guided students in applying coding packages and spatial analysis techniques to model and predict pedestrian flows, enhancing real-world mobility understanding.</li>
      </ul>
    </div>
  </div>
</div>

