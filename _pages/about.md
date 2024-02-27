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

I am currently a second-year master student at Visual & Data Intelligence Center of ShanghaiTech University, supervised by [Prof. Lan Xu](https://www.xu-lan.com/). I am also fortunate to work closely with [Prof. Jingyi Yu](https://scholar.google.com/citations?user=R9L_AfQAAAAJ) and [Prof. Jingya Wang](https://faculty.sist.shanghaitech.edu.cn/faculty/wangjingya/). Before graduate study, I received my bachelor degree from ShanghaiTech.

My research interests include:
- 3D computer vision/graphics,
- Human-centric motion understanding,
- LLM-enhanced motion reasoning.

# 🔥 News

- *2024.02*: &nbsp;🎉🎉 3 papers accepted to CVPR 2024!
- *2023.01*: &nbsp;🎉🎉 1 paper accepted to TVCG 2023!
- *2022.11*: &nbsp;🎉🎉 1 paper accepted to AAAI 2023!

# 📝 Publications
<!-- CVPR2024 I'M HOI -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/imhoi.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://afterjourney00.github.io/IM-HOI.github.io/" style="text-decoration:none">**I'M HOI: Inertia-aware Monocular Capture of 3D Human-Object Interactions**<sup>🔗</sup></a>

*IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024.*

**Authors:** <ins>Chengfeng Zhao</ins>, Juze Zhang, Jiashen Du, Ziwei Shan, Junye Wang, Jingyi Yu, Jingya Wang, Lan Xu

**Abstract:** We present I'm-HOI, a monocular scheme to faithfully capture the 3D motions of both the human and object in a novel setting: using a minimal amount of RGB camera and object-mounted Inertial Measurement Unit (IMU).
  
</div>
</div>

<!-- CVPR2024 HOI-M3 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/hoim3.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- <a href="https://afterjourney00.github.io/IM-HOI.github.io/" style="text-decoration:none">**HOI-M$^3$: Capture Multiple Humans and Objects Interaction within Contextual Environment**<sup>🔗</sup></a> -->
**HOI-M$^3$: Capture Multiple Humans and Objects Interaction within Contextual Environment**

*IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024.*

**Authors:** Juze Zhang\*, Jingyan Zhang\*, Zining Song, Zhanhe Shi, <ins>Chengfeng Zhao</ins>, Ye Shi, Jingyi Yu, Lan Xu, Jingya Wang

**Abstract:** In this paper, we introduce HOI-M$^3$, a novel large-scale dataset for modeling the interactions of Multiple huMans and Multiple objects.
  
</div>
</div>

<!-- CVPR2024 LiveHPS -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/livehps.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- <a href="https://afterjourney00.github.io/IM-HOI.github.io/" style="text-decoration:none">**LiveHPS: LiDAR-based Scene-level Human Pose and Shape Estimation in Free Environment**<sup>🔗</sup></a> -->
**LiveHPS: LiDAR-based Scene-level Human Pose and Shape Estimation in Free Environment**

*IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024.*

**Authors:** Yiming Ren, Xiao Han, <ins>Chengfeng Zhao</ins>, Jingya Wang, Lan Xu, Jingyi Yu, Yuexin Ma 

**Abstract:** In this paper, we present LiveHPS, a novel single LiDAR-based approach for scene-level Human Pose and Shape estimation without any limitation of light conditions and wearable devices.
  
</div>
</div>

<!-- TVCG2023 LIP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2023</div><img src='images/lip.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://4dvlab.github.io/project_page/LIPD.html" style="text-decoration:none">**LiDAR-aid Inertial Poser: Large-scale Human Motion Capture by Sparse Inertial and LiDAR Sensors**<sup>🔗</sup></a>

*IEEE Transactions on Visualization and Computer Graphics (Proc. IEEE VR), 2023.*

**Authors:** Yiming Ren\*, <ins>Chengfeng Zhao</ins>\*, Yannan He, Peishan Cong, Han Liang, Jingyi Yu, Lan Xu, Yuexin Ma

- \* represents equal contribution.

**Abstract:** We propose a multi-sensor fusion method for capturing challenging 3D human motions using single LiDAR and 4 IMUs.
  
</div>
</div>

<!-- AAAI2023 HybridCap -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/hybridcap.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2203.09287" style="text-decoration:none">**HybridCap: Inertia-aid Monocular Capture of Challenging Human Motions**<sup>🔗</sup></a>

*The 37th AAAI Conference on Artificial Intelligence (AAAI), 2023.*

**Authors:** Han Liang, Yannan He, <ins>Chengfeng Zhao</ins>, Mutian Li, Jingya Wang, Jingyi Yu, Lan Xu

**Abstract:** We present a light-weight, hybrid mocap technique called HybridCap that augments the camera with only 4 Inertial Measurement Units (IMUs) in a learning-and-optimization framework.
  
</div>
</div>

# 🎖 Honors and Awards

- *2022.06* **"Outstanding Graduate of Shanghai"**, Undergraduate.
- *2022.06* **"Outstanding Graduate of ShanghaiTech University"**, Undergraduate.

# 💬 Teaching Assistants

- *2022 Fall & 2023 Fall*, **CS280: Deep Learning**, ShanghaiTech University.
- *2022 Spring*, **CS100: Introduction to Programming**, ShanghaiTech University.
- *2021 Fall*, **CS130: Operating Systems**, ShanghaiTech University.
- *2021 Spring*, **SI100B: Introduction to Information Science and Technology**, ShanghaiTech University.

# 💻 Internships

<div class='exp-box'> <div class='exp-box-image'><div><img src='images/SenseTime_logo.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[SenseTime](https://www.sensetime.com/en), Shanghai, China.

*2021.06 - 2021.09*

</div>
</div>

# 📖 Educations
<!-- master, shanghaitech -->
<div class='exp-box'> <div class='exp-box-image'><div><img src='images/shanghaitech.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

**Master**

[ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/), Shanghai, China.

*2022.09 - now*

</div>
</div>

<!-- bachelor, shanghaitech -->
<div class='exp-box'> <div class='exp-box-image'><div><img src='images/shanghaitech.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

**Bachelor**

[ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/), Shanghai, China.

*2018.09 - 2022.06*

</div>
</div>

<!-- bachelor, shanghaitech -->
<div class='exp-box'> <div class='exp-box-image'><div><img src='images/nsfz.jpg' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[High School Affiliated to Nanjing Normal University](https://www.nsfz.net/), Nanjing, China.

*2015.09 - 2018.06*

</div>
</div>