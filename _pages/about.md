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
JiaXu Li is a lecture of School of Information Engineering, China University of Geosciences Beijing.
She earned her master and Ph.D. degree in Computer Science from the University of Macau in 2024,
supervised by Prof. Yicong Zhou from Vision and Image Processing Lab. 
Her research interest lies in theoretical and applied research on image processing, 
remote sensing data, and machine learning. 



# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 
**2025**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/TGRS2025_SASP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Seam-Adaptive Structure-Preserving Image Stitching for Drone Images](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10793400)

**Jiaxue Li** and Yicong Zhou

- Taking advantages of the quaternion representation
of the color image, this paper proposes a quaternion perceptual seamline detection model to generate the seamline in
the quaternion domain. It considers seamline detection as a
quaternion-domain color image labeling problem and minimizes
the local-area quaternion perceptual difference cost to obtain
the optimal seamline. To assess seamline quality effectively,
we develop a quaternion perceptual seamline quality measure.
Based on the proposed quaternion perceptual seamline detection
model and quality measure, we further propose a general framework for automatic quaternion-domain color image stitching
(AQCIS). To the best of our knowledge, this is the first attempt
to perform color image stitching completely in the quaternion
domain. Meanwhile, AQCIS introduces the joint optimization
strategy of local alignment and seamline in an iterative fashion.
Extensive experiments on challenging datasets demonstrate that
our AQCIS achieves superior performance for color image
stitching in comparison with state-of-the-art methods.
</div>
</div>

**2024**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2024</div><img src='images/TIP2024_AQCIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automatic Quaternion-Domain Color Image Stitching](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10430121)

**Jiaxue Li** and Yicong Zhou

- Drones have been widely used for remote sensing
applications. To perform high-quality drone image stitching, this
article first proposes a local and global structure-preserving
alignment (LGSPA) method that aligns drone images from local
dual feature-based and global pixel-based alignment perspectives,
while maintaining local linear and global collinear image structures. To enable an optimal image stitching performance, we then
propose a seam-adaptive weighting (SAW) scheme to enhance
the local alignment accuracy under the guidance of a seam
prior. On the ground of LGSPA and SAW, we further develop
a seam-adaptive structure-preserving (SASP) image stitching
framework to generate the final stitched drone images. Both
qualitative and quantitative experimental results demonstrate
that LGSPA and SASP are capable of generating higher quality
alignment and stitching results than several state-of-the-art
methods over multiple challenging aerial scenarios, including low
textures, repetitive textures, large parallax, wide baseline, and
occlusions.
</div>
</div>

**2022**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/CVPR2022_QR1A.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automatic Color Image Stitching Using Quaternion Rank-1 Alignment](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Automatic_Color_Image_Stitching_Using_Quaternion_Rank-1_Alignment_CVPR_2022_paper.pdf)

**Jiaxue Li** and Yicong Zhou

- Color image stitching is a challenging task in real-world
applications. This paper first proposes a quaternion rank1 alignment (QR1A) model for high-precision color image
alignment. To solve the optimization problem of QR1A, we
develop a nested iterative algorithm under the framework of
complex-valued alternating direction method of multipliers.
To quantitatively evaluate image stitching performance, we
propose a perceptual seam quality (PSQ) measure to calculate misalignments of local regions along the seamline. Using QR1A and PSQ, we further propose an automatic color
image stitching (ACIS-QR1A) framework. In this framework, the automatic strategy and iterative learning strategy
are developed to simultaneously learn the optimal seamline
and local alignment. Extensive experiments on challenging
datasets demonstrate that the proposed ACIS-QR1A is able
to obtain high-quality stitched images under several difficult scenarios including large parallax, low textures, moving objects, large occlusions or/and their combinations.
</div>
</div>
