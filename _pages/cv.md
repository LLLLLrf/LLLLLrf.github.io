---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in China, Peking University, 2025
* B.S. in China, South China Normal University, 2021

Work experience
======
* Summer 2024: AI Algorithm Engineer & Full Stack Developer
  * Tencent
  * Duties includes: Develop algorithm in Image Super Resolution / Video Segmentation / Mobile Agent

Professional Experience
======
* Segmentation of polyp medical images based on computer vision						      2023.11-2024.5
  * Work as an intern in a research team from Peking University, studied the segmentation of polyp medical images.
  * First apply Vision-Mamba architecture to polyp segmentation and first to utilize prompt technology in a polyp segmentation model.
  * Published research paper “ProMamba: Prompt-Mamba for polyp segmentation” on arXiv in Mar 2024. (arXiv: 2403.13660)
* Developed motion data evaluation and visualization techniques using human pose recognition and neural rendering																			  2023.02-present
  * Using PoseFormerV2 framework that based on transformer achieve 2D-to-3D pose detection.
  * Based on quaternion, put forward a new method to evaluate similarity between two poses.
  * Developed fitness app “BodyBuddy” based on this pose recognition and evaluation technology for personalized workout tracking and guidance. Registered as the First Copyright Holder, Application Number: 2024R11L0492032.
* Planning and guidance system for study aboard											  2022.04-2023.10
  * Developed a website based on Vue3, comprises three distinct systems: the Student Portal, Teacher Portal, and Administrator Portal, each tailored with unique functionalities and permissions.
  * Inventor of a pending national patent application for a method and system for recommending study abroad applications based on natural language processing and neural networks, Application Number: 2023113068213.
* Learning situation collection and analysis system based on visual emotion recognition		  2021.12-2023.04
  * Built emotion recognition CNN network and trained on Fer 2013 datasets.
  * Developed a desktop application by PyQt5 for data visualization and more user-friendly.

Skills
======
* CET4: 626, CET6: 592
* Machine Learning
  * Computer Vision
  * LLM
* Software Development
  * Android
  * Web
 
      

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
