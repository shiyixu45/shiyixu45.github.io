---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



<span class='anchor' id='about-me'></span>

<div class="profile-container" style="display: flex; align-items: flex-start; margin-bottom: 40px;">   <div class="profile-content" style="flex: 1;">     <h1 style="margin-top: 0;">Shiyi Xu | 徐十一</h1>     <p style="font-size: 1.2em; color: #555; margin-bottom: 15px;">Artificial Intelligence Undergraduate</p>     <p>I am an undergraduate student at the Gaoling School of Artificial Intelligence, Renmin University of China, where I conducted research under the supervision of Professor Wayne Xin Zhao in the <a href="http://aibox.ruc.edu.cn/" target="_blank">RUC AI Box</a> lab. My primary research focus on the <strong>pre-training, complex reasoning and evaluation of large language models</strong>.</p>     <p>If you want to discuss or collaborate with me, please feel free to contact me anytime in any way.</p>


<div style="margin-top: 20px;">
  <h3 style="margin-bottom: 10px;">Contact Information</h3>
  <ul style="list-style-type: none; padding-left: 0; margin-top: 0;">
    <li><i class="fas fa-envelope" style="margin-right: 8px; color: #0066cc;"></i><strong>Email:</strong> shiyixu45@gmail.com</li>
    <li><i class="fab fa-github" style="margin-right: 8px; color: #0066cc;"></i><strong>Github:</strong> shiyixu45</li>
  </ul>
</div>


  </div>  <div class="profile-image" style="flex: 0 0 200px; margin-left: 40px;">    <!-- Profile photo placeholder -->    <!-- <img src="images/profile.jpg" alt="Shiyi Xu" style="width: 100%; border-radius: 50%; border: 3px solid #0066cc;"> -->  </div> </div> <div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='education'></span>
## 🎓 Education



<div class="education-container">
  <div class="education-item" style="display: flex; margin-bottom: 30px; border-left: 4px solid #0066cc; padding-left: 15px;">
    <div style="flex: 1; margin-right: 20px;">
      <p style="font-weight: bold; color: #888;">2022 - Present</p>
    </div>
    <div style="flex: 3;">
      <h3 style="margin-top: 0;">Undergraduate, Gaoling School of Artificial Intelligence, Renmin University of China</h3>
    </div>
  </div>
  <div class="education-item" style="display: flex; margin-bottom: 30px; border-left: 4px solid #888; padding-left: 15px;">
    <div style="flex: 1; margin-right: 20px;">
      <p style="font-weight: bold; color: #888;">2019 - 2022</p>
    </div>
    <div style="flex: 3;">
      <h3 style="margin-top: 0;">Huaiyin High School</h3>
    </div>
  </div>
</div>
<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='papers'></span>
## 🔬 Papers

<div class="research-container">

  <!-- Current Research -->
  <!-- <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <span style="position: absolute; top: 15px; right: 15px; background-color: #ff6b6b; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Current Research</span>
      <h3>AMS Data Synthesis Technology Based on Autoregressive Architecture</h3>
      <p style="color: #666;"><strong>2025.04 - Present</strong></p>
      <div style="display: flex; flex-wrap: wrap; margin-top: 15px; align-items: center;">
        <div style="flex: 1; min-width: 200px; margin-right: 20px; margin-bottom: 15px;">
          <img src="images/autoregressive.png" alt="Autoregressive graph generation" style="width: 100%; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
        </div>
        <div style="flex: 2; min-width: 300px;">
          <ul style="padding-left: 20px; margin-top: 0;">
            <li>Researching autoregressive architecture-based circuit graph generation methods to address AMS circuit data scarcity</li>
            <li>Developing techniques to automatically generate circuit topologies that comply with design specifications</li>
            <li>Applied for Beijing Natural Science Foundation (Undergraduate "Qiyan" Program)</li>
          </ul>
        </div>
      </div>
    </div>
  </div> -->

  <!-- Ongoing Research -->
  <!-- <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <span style="position: absolute; top: 15px; right: 15px; background-color: #4dabf7; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Ongoing Research</span>
      <h3>Transferable Parasitic Estimation via Graph Contrastive Learning and Label Rebalancing in AMS Circuits</h3>
      <p style="color: #666;"><strong>2025.01 - 2025.04</strong></p>
      <div style="display: flex; flex-wrap: wrap; margin-top: 15px; align-items: center;">
        <div style="flex: 1; min-width: 200px; margin-right: 20px; margin-bottom: 15px;">
          <img src="images/fig-workflow.png" alt="Circuit GCL" style="width: 100%; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
        </div>
        <div style="flex: 2; min-width: 300px;">
          <ul style="padding-left: 20px; margin-top: 0;">
            <li>Researched parasitic parameter extraction algorithms for analog/mixed-signal circuits</li>
            <li>Explored knowledge transfer challenges across different circuit types using graph contrastive learning and balanced loss functions</li>
            <li>Submitted research as first student author to ICCAD 2025</li>
            <li><a href="https://github.com/ShenShan123/CircuitGCL" style="color: #0066cc;">GitHub: ShenShan123/CircuitGCL - Initial version of CircuitGCL</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div> -->

  <!-- International Exchange -->
  <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <span style="position: absolute; top: 15px; right: 15px; background-color:rgb(207, 81, 186); color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Finished Research</span>
      <h3>ICPC-Eval: Probing the Frontiers of LLM Reasoning with Competitive Programming Contests</h3>
      <p style="color: #666;"><strong>Shiyi Xu*</strong>, Yiwen Hu*, Yingqian Min, Zhipeng Chen, Wayne Xin Zhao, Ji-Rong Wen</p>
      <p style="color: #666;"><strong>Submitted to NeurIPS D&B 2025 | First Author</strong></p>
      <div style="display: flex; flex-wrap: wrap; margin-top: 15px; align-items: center;">
        <div style="flex: 1; min-width: 200px; margin-right: 20px; margin-bottom: 15px;">
          <img src="images\ICPC-Eval.png" alt="ICPC-Eval" style="width: 100%; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
        </div>
        <div style="flex: 2; min-width: 300px;">
          <ul style="padding-left: 20px; margin-top: 0;">
            <li>A new benchmark of 118 ICPC problems for evaluating LLM reasoning in competitive coding, featuring realistic ICPC competition scenario, robust local evaluation, and a iterative repair metrics Refine@K.</li>
            <!-- <li>Proposed a novel evaluation metric, <strong>Refine@K</strong>, to measure a model's ability to iteratively repair code based on execution feedback, better simulating realistic problem-solving scenarios.</li>
            <li>Designed a robust pipeline that leverages LLMs to automatically synthesize diverse and challenging test cases, enabling efficient and accessible local evaluation.</li> -->
            <li><a href="https://github.com/RUCAIBox/ICPC-Eval" style="color: #0066cc;">GitHub: RUCAIBox/ICPC-Eval - ICPC-Eval: LLM Evaluation Framework for Competitive Programming</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Open Source -->
  <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <!-- <span style="position: absolute; top: 15px; right: 15px; background-color: #fcc419; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Open Source</span> -->
      <span style="position: absolute; top: 15px; right: 15px; background-color: rgb(207, 81, 186); color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Finished Research</span>
      <h3>LLMBox: A Comprehensive Library for Large Language Models</h3>
      <p style="color: #666;">Tianyi Tang, Yiwen Hu, Bingqian Li, Wenyang Luo, Zijing Qin, Haoxiang Sun, Jiapeng Wang, <strong>Shiyi Xu</strong>, Xiaoxue Cheng, Geyang Guo, Han Peng, Bowen Zheng, Yiru Tang, Yingqian Min, Yushuo Chen, Jie Chen, Yuanqian Zhao, Luran Ding, Yuhao Wang, Zican Dong, Chunxuan Xia, Junyi Li, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen</p>
      <p style="color: #666;"><strong>Accepted by ACL 2024 Demo</strong></p>
      <div style="display: flex; flex-wrap: wrap; margin-top: 15px; align-items: center;">
        <div style="flex: 1; min-width: 200px; margin-right: 20px; margin-bottom: 15px;">
          <img src="images/LLMBox.png" alt="LLMBox" style="width: 100%; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
        </div>
        <div style="flex: 2; min-width: 300px;">
          <ul style="padding-left: 20px; margin-top: 0;">
            <li>A comprehensive library for implementing LLMs, including a unified training pipeline and comprehensive model evaluation.</li>
            <li><a href="https://github.com/RUCAIBox/LLMBox" style="color: #0066cc;">GitHub: RUCAIBox/LLMBox - LLMBox: A Comprehensive Library for Large Language Models</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>

</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='projects'></span>
## 🛰️ Projects

<div class="projects-container" style="display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 20px; margin-bottom: 30px;">
    <!-- Project 1 -->
    <div class="project-card" style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%; display: flex; flex-direction: column;">
        <div style="height: 160px; overflow: hidden;">
            <img src="images/Depression.png" alt="Depression" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 15px; flex-grow: 1; display: flex; flex-direction: column;">
            <div>
                <span style="background-color: rgb(207, 81, 186); color: white; padding: 3px 8px; border-radius: 12px; font-size: 0.75em;">Finished Project</span>
                <h4>Detection of Student Depression Issues Based on Machine Learning Algorithms</h4>
                <p style="color: #666; font-size: 0.9em;"><strong>2023 - 2024</strong></p>
            </div>
            <ul style="font-size: 0.9em; padding-left: 20px; margin-top: auto;">
                <li>University Student Innovation Program of Beijing</li>
                <li>Use Bert, SKEP, and GPT models to automatically identify and assess students' emotional states by training these models with Weibo text data.</li>
            </ul>
        </div>
    </div>
    <!-- Project 2 -->
    <!-- <div class="project-card" style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%; display: flex; flex-direction: column;">
        <div style="height: 160px; overflow: hidden;">
            <img src="images/rsop.png" alt="Optical" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 15px; flex-grow: 1; display: flex; flex-direction: column;">
            <div>
                <span style="background-color: #339af0; color: white; padding: 3px 8px; border-radius: 12px; font-size: 0.75em;">Optical Communications</span>
                <h4>Characterization of Polarization Damage in Optical Fiber Communication Systems</h4>
                <p style="color: #666; font-size: 0.9em;"><strong>2023.10 - 2024.03</strong></p>
            </div>
            <ul style="font-size: 0.9em; padding-left: 20px; margin-top: auto;">
                <li>Proposed 3D Stokes space method for polarization compensation</li>
                <li>Improved OSNR margin through novel coding techniques</li>
                <li>Developed three-parameter RSOP equalization method</li>
            </ul>
        </div>
    </div> -->
    <!-- Project 3 -->
    <!-- <div class="project-card" style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%; display: flex; flex-direction: column;">
        <div style="height: 160px; overflow: hidden;">
            <img src="images/IIOT.png" alt="Industrial IoT" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 15px; flex-grow: 1; display: flex; flex-direction: column;">
            <div>
                <span style="background-color: #8e44ad; color: white; padding: 3px 8px; border-radius: 12px; font-size: 0.75em;">Industrial IoT</span>
                <h4>Confidence Reachable Set Estimation in Industrial IoT</h4>
                <p style="color: #666; font-size: 0.9em;"><strong>2023.06 - 2023.09</strong></p>
            </div>
            <ul style="font-size: 0.9em; padding-left: 20px; margin-top: auto;">
                <li>Participated in National Youth Science Foundation project</li>
                <li>Designed water quality prediction algorithms</li>
                <li>Implemented Set-Propagation strategies</li>
            </ul>
        </div>
    </div> -->
</div>
<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<!-- <span class='anchor' id='publications'></span> -->
📝 Publications

<div class="publications-container">   <div class="publication-item" style="padding: 20px; margin-bottom: 20px; border-left: 4px solid #0066cc; background-color: #f8f9fa; border-radius: 0 4px 4px 0; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">     <h4 style="margin-top: 0;">Transferable Parasitic Estimation via Graph Contrastive Learning and Label Rebalancing in AMS Circuits</h4>     <p style="margin-bottom: 0;"><em>Under review at ICCAD 2025</em> | <strong>First Student Author</strong></p>   </div> </div> <div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='awards'></span>
## 🏆 Selected Awards

<div class="awards-container" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-bottom: 30px;">
  <div class="awards-card" style="background-color: #f8f9fa; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%;">
    <h4 style="color: #0066cc; margin-top: 0; border-bottom: 2px solid #0066cc; padding-bottom: 10px;">Competitions</h4>
    <ul style="padding-left: 20px;">
    <li> 2023 <strong>Second Prize</strong> in Mathematics competition of Chinese College Students, Chinese Mathematical Society</li>
    <li> 2023 <strong>Third Prize</strong> in the National Finals of the Lanqiao Cup, Talent exchange center of Ministry of industry and information technology</li>
    <li> 2021 <strong>First Prize</strong> in Chinese Physics Olympiad in Provinces, Chinese Physical Society</li>
    <li> 2020 <strong>Third Prize</strong> in Chinese High School Mathematics League, Chinese Mathematical Society</li>
    <li>2019 <strong>First Prize</strong> in China National Olympiad in Informatics in Provinces (NOIP), China Computer Federation (CCF)</li>
      <!-- <li>National College Student Mathematics Competition</li>
      <li>National Electronic Design Competition</li>
      <li>National College English Competition</li> -->
    </ul>
  </div>
  <!-- <div class="awards-card" style="background-color: #f8f9fa; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%;">
    <h4 style="color: #0066cc; margin-top: 0; border-bottom: 2px solid #0066cc; padding-bottom: 10px;">Scholarships & Honors</h4>
    <ul style="padding-left: 20px;">
      <li><strong style="color: red;">Beijing Natural Science Foundation Recipient</strong><br>("Qiyan" Program for Undergraduates)</li>
      <li>Industrial and Commercial Bank of China Scholarship</li>
      <li>University Scholarships</li>
      <li>Outstanding Student Award</li>
    </ul>
  </div> -->
</div>
<div style="text-align: center; margin-top: 40px; margin-bottom: 30px; padding: 20px; background-color: #f8f9fa; border-radius: 8px;">
  <p style="margin-bottom: 0; color: #666;">Last updated: May 2025 | <a href="assets/downloads/ShiyiXu_CV.pdf" style="color: #0066cc; text-decoration: none; font-weight: bold;">Download CV</a></p>
</div>

