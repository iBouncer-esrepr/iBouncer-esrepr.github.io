---
layout: about
title: about
permalink: /
subtitle: Ph.D. in Engineering | Visiting Researcher at Kanagawa University

profile:
  show: false # ここはfalseで正解です
  # align: right
  # image: prof_pic.jpg
  # image_circular: false

social: false
news: true # news.liquidを動かすために一応true
selected_papers: false
---

<div class="row">
  <div class="col-sm-8" markdown="1">

## Biography
I am an experimental researcher specializing in **Magnetic Resonance**, with a focus on **Electron Spin Resonance (ESR/EPR)**. Throughout my career, I have consistently utilized “spin” as a primary tool to characterize complex systems, spanning from metallurgy and organic chemistry to condensed matter physics and quantum information science.

My academic journey began at **Akita University**, where I studied **Inorganic Chemistry and Metallurgy**. I then moved to **Yamagata University** for my graduate studies (M.S. and Ph.D. in Engineering under Prof. Tateaki Ogata and Assoc. Prof. Tatsuro Kijima). During this time, I pivoted to **Organic Chemistry** and developed analytical protocols for **Reactive Oxygen Species (ROS)**, aiming for **ISO/JIS standardization**.

Following my doctoral work, I focused on **Condensed Matter Physics** at **Kobe University** (Extreme Conditions Physics Group, under Prof. Ohta, Assoc. Prof. Okubo, Assoc. Prof. Ohmichi, Assist. Prof. Sakurai and Assist. Prof. Takahashi), conducting ESR studies under ultra-low temperatures, high frequencies, and high pressures. I also served as a NEDO project researcher at **Sophia University** under Prof. Fujita, Prof. Takeoka, and Prof. Rikukawa, investigating the degradation mechanisms of **Solid Polymer Fuel Cells (PEFCs)**.

In recent years, I have expanded my focus toward the **quantum frontier**. This includes research on **Quantum Sensing with Diamond NV Centers** at **Tokyo Institute of Technology (now Institute of Science Tokyo)** under Assoc. Prof. Keigo Arai, and **Quantum Internet/Computing** using Lithium Niobate (LN) thin films at **International Christian University (ICU)** under Assoc. Prof. Rekishu Yamazaki.

Currently, I am exploring the integration of these multidisciplinary fields with **Machine Learning** to develop next-generation sensing and material characterization techniques.

<hr>

## Research Interests
* **Magnetic Resonance:** Multi-frequency / High-field ESR, ROS analysis, and protocol standardization (ISO/JIS).
* **Condensed Matter Physics:** Material properties under extreme environments (Low Temp, High Mag, High Pressure).
* **Quantum Technology:** Quantum sensing (NV centers) and Quantum Networking (LN-based).
* **Informatics:** Integrating ESR spectroscopy with **Machine Learning** for predictive modeling.

<hr>

## Education
* **Ph.D. in Engineering** | Yamagata University
* **M.S. in Engineering** | Yamagata University
* **B.S. in Engineering** | Akita University

<hr>

## Professional Experience

* **Visiting Researcher** | Kanagawa University (Kawai Group)
* **Postdoctoral Researcher** | International Christian University (ICU, Shu Lab)
* **Postdoctoral Researcher** | Tokyo Institute of Technology (Science Tokyo, Arai Lab.)
* **NEDO Project Researcher** | Sophia University (Polymer Science Lab.)
* **Lecturer (Research Fellow) / Research Support Specialist** | Kobe University (Kyokugen)

<hr>

## Technical Skills

<div class="skills">
  <strong>Experimental:</strong> ESR, High-field Magnetometry, Diamond NV Sensing, LN Thin-film devices, Cryogenics.<br>
  <strong>Computation/Workflow:</strong> Python, Machine Learning, LaTeX, Obsidian, Igor, MATLAB.<br>
  <strong>Standards:</strong> Development of ISO/JIS Analytical Protocols.
</div>

<hr>


## Selected Publications
{% include selected_papers.liquid %}

  </div>

<div class="col-sm-4" markdown="1">

### Profile
<div class="my-profile" style="margin-bottom: 20px;">
  <img src="{{ 'assets/img/prof_pic.jpg' | relative_url }}" class="img-fluid z-depth-1 rounded" style="width: 100%; height: auto;">
  
  <div class="info" style="font-size: 0.85rem; margin-top: 10px; line-height: 1.4;">
    <strong>Visiting Researcher</strong><br>
    Kawai Group, Kanagawa University
  </div>
</div>

<hr>

### News
{% include news.liquid %}

<hr>

### Latest Posts
<div class="news">
  {% if site.posts.size > 0 %}
    <div class="table-responsive">
      <table class="table table-sm table-borderless">
      {% assign latest_posts = site.posts | sort: 'date' | reverse %}
      {% for post in latest_posts limit: 3 %}
        <tr>
          <td>
            <a href="{{ post.url | relative_url }}" style="color: var(--global-theme-color); font-weight: bold;">{{ post.title }}</a>
          </td>
        </tr>
      {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No posts yet.</p>
  {% endif %}
</div>

<hr>

### Hobbies
* ☕️ **Coffee**: Pour-over
* 🚗 **Driving**: Hometown (Okitama) & Yamagata
* 💻 **Mac & Open-source**: Apple Geek, Python

<hr>

### Social & Contact
<div class="social-sidebar" style="font-size: 1.4rem; letter-spacing: 8px;">
  <a href="mailto:y-saito@kanagawa-u.ac.jp" title="Email"><i class="fa-solid fa-envelope"></i></a>
  
  <a href="https://scholar.google.com/citations?user=ecXGuwMAAAAJ" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  
  <a href="https://orcid.org/0000-0002-9108-4697" title="ORCID"><i class="ai ai-orcid"></i></a>
  
  <a href="https://www.researchgate.net/profile/Yu-Saito" title="ResearchGate"><i class="ai ai-researchgate"></i></a>
  
  <a href="https://www.linkedin.com/in/yu-saito-b537a588" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
  
  <a href="https://github.com/ibouncer-esrepr" title="GitHub"><i class="fa-brands fa-github"></i></a>
  
  <a href="https://x.com/Y_Saito_Bouncer" title="X"><i class="fa-brands fa-x-twitter"></i></a>
  
  <a href="{{ '/feed.xml' | relative_url }}" title="RSS Feed"><i class="fa-solid fa-rss"></i></a>

  <div class="contact-note" style="font-size: 0.75rem; margin-top: 12px; line-height: 1.4; letter-spacing: normal;">
    <strong>Academic:</strong> y-saito [at] kanagawa-u.ac.jp<br>
    <strong>General:</strong> y.saito.epr [at] gmail.com

  </div>
</div>
