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

# 👤 About Me
I am currently engaged in the field of Large Language Models (LLMs), specializing in applications within the realm of communication.

I graduated with a Bachelor's degree in June 2020 from the Department of Electronic Engineering and Information Science at the [University of Science and Technology of China](https://en.ustc.edu.cn/) (USTC). Building upon this foundation, I furthered my education at the Research Center for Intelligent Internet of Things at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/) (SJTU), where I earned my Master’s degree in March 2023 under the guidance of Professor [Dongyao Chen](https://chendy.tech/).

I won the honorary title of "outstanding graduate of Shanghai Jiao Tong University" in 2023.

My research interests include mobile sensing and wearable computing. I have published three papers at the top international computer conferences such as MobiCom and UbiComp.


<span class='anchor' id='publications'></span>

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UbiComp 2024</div><img src='images/magdot_2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MagDot: Drift-free, Wearable Joint Angle Tracking at Low Cost](https://dl.acm.org/doi/abs/10.1145/3631423)

Dongyao Chen, **Qing Luo**, Xiaomeng Chen, Xinbing Wang, Chenghu Zhou

[paper](files/MagDot.pdf)

MagDot introduces a magnetic-based, drift-free method for wearable joint angle tracking, achieving high accuracy in applications such as VR/AR, sports monitoring, and medical rehabilitation. Tested with a professional motion capture system, MagDot demonstrates precision of 2.72°, 4.14°, and 4.61° for elbow, knee, and shoulder, respectively, while consuming only 98mW, enabling all-day use with a small battery pack.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MobiCom 2022</div><img src='images/magic_2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automatic calibration of magnetic tracking](https://dl.acm.org/doi/abs/10.1145/3495243.3558760)

Mingke Wang<sup>*</sup>, **Qing Luo**<sup>*</sup>, Yasha Iravantchi, Xiaomeng Chen, Alanson Sample, Kang G Shin, Xiaohua Tian, Xinbing Wang, Dongyao Chen

[paper](files/MAGIC.pdf)

MAGIC is an automatic calibration system for MEMS magnetometers that addresses soft- and hard-iron disturbances without user intervention. It uses an auto-triggering mechanism to detect environmental changes and recalibrate, improving tracking accuracy efficiently. MAGIC outperforms traditional methods with minimal overhead and user involvement.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MobiCom 2021</div><img src='images/magx.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MagX: wearable, untethered hands tracking with passive magnets](https://dl.acm.org/doi/abs/10.1145/3447993.3483260)

Dongyao Chen, Mingke Wang, Chenxi He, **Qing Luo**, Yasha Iravantchi, Alanson Sample, Kang G Shin, Xinbing Wang

[paper](files/MagX.pdf)

MagX is a wearable, untethered hand tracking system using passive magnets for millimeter-accurate 5 DoF tracking. It offers low energy consumption, supporting all-day use. Applications include subconscious behavior monitoring, enhanced user interactions, and healthcare, such as face touching detection and endocapsule tracking.

</div>
</div>

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2020.09 - 2023.03*, Master, Shanghai Jiao Tong University 
- *2016.08 - 2020.06*, Undergraduate, University of Science and Technology of China

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2023.03* Outstanding Graduate of Shanghai Jiao Tong University 
- *2022.12* China COSCO Shipping Second-class Scholarship (Shanghai Jiao Tong University) 
- *2020.12* First-class Graduate Academic Scholarship (Shanghai Jiao Tong University) 
- *2018.10* First-class Prize in the 2018 RoboGame Competition (University of Science and Technology of China) 

<span class='anchor' id='cv'></span>

# 📜 CV
For a comprehensive overview of my experience and publications, please download my curriculum vitae here: [CV](files/Curriculum_Vitae.pdf)