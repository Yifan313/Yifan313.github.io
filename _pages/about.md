---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
.experience-card {
    display: flex;
    align-items: center;
    background: #ffffff;
    border-radius: 12px;
    padding: 16px;
    margin-bottom: 0px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    transition: transform 0.3s, box-shadow 0.3s;
}
.experience-card:hover {
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}
.experience-logo {
    width: 60px;
    height: 60px;
    margin-right: 20px;
    border-radius: 8px;
    object-fit: contain;
}
.experience-info {
    font-family: "Segoe UI", sans-serif;
}
.experience-info strong {
    font-size: 1.1em;
}
</style>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I'm **Yifan** 😊. I am now a Research Associate 🧱 at the School of Airspace Science and Engineering, Shandong University.

I was sponsored by the China Scholarship Council (CSC) and obtained my Ph.D. degree at the 🏛️ School of Creative Technologies, University of Portsmouth, in Sept. 2021. Before that, I earned my master’s degree at the 🏛️ School of Computer Science and Technology, Ocean University of China, in June 2017. 

I currently serve as a reviewer 👨‍💻 for several journals, such as IEEE Transactions on Human-Machine Systems, IEEE Journal of Biomedical and Health Informatics, IEEE/CAA Journal of Automatica Sinica, and Neurocomputing.

My research interests 🎯 focus on **Visual Computing and Pattern Recognition**. I am a recipient of the 🏅 Second Prize in Natural Science of the 2025 Shandong Provincial Science and Technology Award. I have published numerous papers with a total of <a href='https://scholar.google.com/citations?user=_NIufakAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. If you are seeking any form of cooperation 🙋, please feel free 🌈 to email me at 📩 **xiayifan@sdu.edu.cn**.

# 🔥 News
- *2026.01*: &nbsp;Happy New Year!!!🎉🎉🎉 
- *2024.10*: &nbsp;A webpage was released for the **AFLFP** database. Welcome to [**download**](https://github.com/Yifan313/AFLFP)!
- *2024.08*: &nbsp;One paper on facial palsy evaluation was accepted by **IEEE TNSRE**!🎉🎉🎉

# 💻 Experience
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/sddx.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Research Associate**
- School of Airspace Science and Engineering, Shandong University, Weihai, China.
- 2021.12 - Present.
  
</div>
</div>-->
<div class="experience-card">
      <img src="images/sddx_logo.png" alt="sddx_logo" class="experience-logo">
      <div class="experience-info">
          <strong>Shandong University</strong><br>
          <em>2021.12 - Present.</em><br>
          Research Associate at the School of Airspace Science and Engineering
      </div>
  </div>

# 📝 Selected Publications

**\* means corresponding author. Please find my full paper list at my [[Google Scholar]](https://scholar.google.com/citations?user=_NIufakAAAAJ).**
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNSRE</div><img src='images/image1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Artificial Intelligence-based Facial Palsy Evaluation: A Survey](https://ieeexplore.ieee.org/document/10643562)

Y. Zhang, W. Gao, H. Yu, J. Dong and **Y. Xia***.

[[Paper@List]](https://github.com/Yifan313)
- **IEEE Transactions on Neural Systems and Rehabilitation Engineering**, vol. 32, pp. 3116-3134, 2024.
- This work reviews the recent development of artificial intelligence-based facial palsy evaluation, discusses the existing research challenges, and provides some guidelines about future directions for researchers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TAFFC</div><img src='images/image3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MGEED: A Multimodal Genuine Emotion and Expression Detection Database](https://ieeexplore.ieee.org/abstract/document/10153641)

Y. Wang, H. Yu, W. Gao, **Y. Xia** and C. Nduka.

[[Data@Download]](https://github.com/YMPort/MGEED) 
- **IEEE Transactions on Affective Computing**, vol. 15, no. 2, pp. 606-619, 2024.
- This work presents a facial emotional database, which consists of facial image sequences, depth maps, electroencephalography (EEG), optomyography (OMG) and electrocardiography (ECG) signals. Each facial image is annotated by the 9-level valence, arousal and the 6 basic emotions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSS</div><img src='images/image2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AFLFP: A Database with Annotated Facial Landmarks for Facial Palsy](https://ieeexplore.ieee.org/document/9831121)

**Y. Xia**, C. Nduka, R. Yap Kannan, E. Pescarini, J. Enrique Berner and H. Yu.

[[Data@Download]](https://github.com/Yifan313/AFLFP)
- **IEEE Transactions on Computational Social Systems**, vol. 10, no. 4, pp. 1975-1985, 2023.
- This work presents a diverse and reliable facial palsy database that contains facial images with 16-class asymmetric facial expressions. Each facial image is independently and manually annotated with 68 facial landmarks.
</div>
</div>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• S. Liu, <strong>Y. Xia</strong>, Y. Liu, Z. Shi, H. Yu, Z. Li and J. Lin, "Tool Path Planning of Consecutive Free-Form Sheet Metal Stamping with Deep Learning," <strong>Journal of Materials Processing Technology</strong>, vol. 303, pp. 1-15, 2022. <a href="https://www.sciencedirect.com/science/article/pii/S0924013622000425">[Paper]</a>
</p>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• <strong>Y. Xia</strong>, W. Zheng, Y. Wang, H. Yu, J. Dong and F. -Y. Wang, "Local and Global Perception Generative Adversarial Network for Facial Expression Synthesis," <strong>IEEE Transactions on Circuits and Systems for Video Technology</strong>, vol. 32, no. 3, pp. 1443-1452, 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9406832">[Paper]</a>
</p>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• <strong>Y. Xia</strong>, H. Yu, X. Wang, M. Jian and F. -Y. Wang, "Relation-Aware Facial Expression Recognition," <strong>IEEE Transactions on Cognitive and Developmental Systems</strong>, vol. 14, no. 3, pp. 1143-1154, 2022. <a href="https://ieeexplore.ieee.org/document/9496600">[Paper]</a>
</p>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• S. Liu, <strong>Y. Xia</strong>, Z. Shi, H. Yu, Z. Li and J. Lin, "Deep Learning in Sheet Metal Bending with a Novel Theory-Guided Deep Neural Network," <strong>IEEE/CAA Journal of Automatica Sinica</strong>, vol. 8, no. 3, pp. 565-581, 2021. <a href="https://ieeexplore.ieee.org/abstract/document/9346099">[Paper]</a>
</p>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• X. Liu, <strong>Y. Xia</strong>, H. Yu, J. Dong, M. Jian and T. D. Pham, "Region Based Parallel Hierarchy Convolutional Neural Network for Automatic Facial Nerve Paralysis Evaluation," <strong>IEEE Transactions on Neural Systems and Rehabilitation Engineering</strong>, vol. 28, no. 10, pp. 2325-2332, 2020. <a href="https://ieeexplore.ieee.org/abstract/document/9186079">[Paper]</a>
</p>

<p style="text-align: justify; text-justify: inter-ideograph; margin: 0.5em 0;">
• <strong>Y. Xia</strong>, H. Yu and F. -Y. Wang, "Accurate and Robust Eye Center Localization via Fully Convolutional Networks," <strong>IEEE/CAA Journal of Automatica Sinica</strong>, vol. 6, no. 5, pp. 1127-1138, 2019. <a href="https://ieeexplore.ieee.org/abstract/document/8823575">[Paper]</a>
</p>


# 🎖 Research Grants
- *2026 - 2028*: Young Scientists Fund of the National Natural Science Foundation of China, PI.
- *2025 - 2027*: Young Scientists Fund of Shandong Provincial Natural Science Foundation, PI.

# 📖 Education
- *2018.02 - 2021.09*, Ph.D., University of Portsmouth, UK.
- *2014.09 - 2017.06*, Master, Ocean University of China, China.
- *2010.09 - 2014.06*, Bachelor, Yantai University, China.
  

# 💬 Teaching
- C Programming (Undergraduate), @Shandong University.
- Robot Operating System (Undergraduate), @Shandong University.


