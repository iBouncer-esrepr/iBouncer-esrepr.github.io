---
layout: about
title: about
permalink: /
subtitle: Ph.D. in Engineering | Visiting Researcher at Kanagawa University

profile:
  show: false # ここはfalseで正解です
  align: right
  image: prof_pic.jpg
  image_circular: false

social: false
news: true # news.liquidを動かすために一応true
selected_papers: false
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
<div class="my-profile" style="margin-bottom: 20px;">
  {% if page.profile.image %}
    {% assign profile_image_path = page.profile.image | prepend: 'assets/img/' %}
    <img src="{{ profile_image_path | relative_url }}" class="img-fluid z-depth-1 rounded" style="width: 100%; height: auto;">
  {% endif %}
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

  </div>
</div>
