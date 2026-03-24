---
layout: about
title: about
permalink: /
subtitle: Ph.D. in Engineering | Visiting Researcher at Kanagawa University

# 標準のプロフィール表示（自動浮き出し）をオフにして、手動で右カラムに入れます
profile:
  show: false 
  align: right
  image: prof_pic.jpg
  image_circular: false

social: false
news: false
selected_papers: false
last_posts: false
---

<div class="row">
  <div class="col-sm-8" markdown="1">

## Biography

I am an experimental researcher specializing in **Magnetic Resonance**, with a focus on **Electron Spin Resonance (ESR/EPR)**. Throughout my career, I have consistently utilized "spin" as a primary tool to characterize complex systems.

My academic journey began at **Akita University**, where I studied **Inorganic Chemistry and Metallurgy**. I then moved to **Yamagata University** for my graduate studies (M.S. and Ph.D. in Engineering). During this time, I developed analytical protocols for **Reactive Oxygen Species (ROS)**, aiming for **ISO/JIS standardization**. 

Following my doctoral work, I focused on **Condensed Matter Physics** at **Kobe University**, conducting ESR studies under extreme conditions. I also served as a NEDO project researcher at **Sophia University**, investigating fuel cell degradation.

In recent years, I have expanded my focus toward **Quantum Technology**, including research on **Diamond NV Centers** at **Science Tokyo** and **Quantum Internet** at **ICU**. Currently, I am exploring the integration of these fields with **Machine Learning**.

<hr>

## Research Interests
* **Magnetic Resonance:** Multi-frequency / High-field ESR, ROS analysis.
* **Condensed Matter Physics:** Material properties under extreme environments.
* **Quantum Technology:** Quantum sensing and Quantum Networking.

<hr>

## Selected Publications
{% include selected_papers.liquid %}

  </div>

  <div class="col-sm-4" markdown="1">

### Profile
<div class="profile float-none w-100">
  {% if page.profile.image %}
    {% assign profile_image_path = page.profile.image | prepend: 'assets/img/' %}
    {% include figure.liquid 
       path=profile_image_path 
       class="img-fluid z-depth-1 rounded" 
       alt=page.profile.image 
    %}
  {% endif %}
  <div class="more-info" style="font-size: 0.9rem;">
    <p>Visiting Researcher</p>
    <p>Kawai Group, Kanagawa University</p>
  </div>
</div>

<hr>

### News
{% include news.liquid %}

<hr>

### Latest Posts
{% include repository/repo_user.liquid %} 
{% dynamic_repository "latest_posts" %}

<hr>

### Hobbies
* ☕️ **Coffee**: Pour-over
* 🚗 **Driving**: My hometown and Yamagata
* 💻 **Mac and Open-source**: Apple Geek, Python

  </div>
</div>
