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
* Ph.D. Candidate in Computer Science and Technology, ShanghaiTech University / Chinese Academy of Sciences, 2021&nbsp;–&nbsp;present (expected Jul 2026)
* B.Eng. in Information Engineering, Zhejiang University, 2017&nbsp;–&nbsp;2021

Research & Engineering Experience
======
* 2021&nbsp;–&nbsp;present: Ph.D. Candidate, Brain-Computer Interface Lab, ShanghaiTech University (Shanghai, China)
  * Design binocular VR SSVEP paradigms that encode more targets with fewer frequencies to improve immersive BCI robustness and comfort.
  * Build Unity-based multi-scene EEG-BCI platforms, Hololens/Pico AR interactions, and FusionCA neural-fusion systems for closed-loop control.
  * Develop wearable wireless EEG hardware, FPGA-based scalable acquisition, and edge inference pipelines for multimodal sensing.

* 2022&nbsp;–&nbsp;2025: Lead engineer, SariBCI & Multimodal Sensing Projects
  * Delivered ADS1299-based high-resolution EEG modules with Wi-Fi streaming and synchronized multi-channel acquisition.
  * Integrated Zigbee peripherals and sensor fusion (EEG/ECG/EMG/IMU) with real-time neural decoding deployed on embedded platforms.
  
Skills
======
* Brain-computer interfaces: VR/AR SSVEP paradigms, neural decoding, EEG/EXG analytics, MATLAB, Python
* Embedded & hardware: FPGA prototyping, ESP32, nRF5340, wireless EEG system design, Zephyr RTOS
* Interactive systems: Unity/C#, Hololens and Pico VR development, 3D interface design, LabVIEW rapid prototyping

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
* National invention patents (2): SSVEP-ERP based visual paradigm generation; AR brain-feedback interface system
