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

Hello! I am Zhijin Rong (容志谨), an undergraduate student in Mathematics and Applied Mathematics at Ocean University of China. My research interests focus on **mathematical principles in machine learning (particularly domain shift problems), image processing and analysis, and biomedical data (computational biology and computational pathology)**. 

I have a strong background in mathematical modeling and scientific computing, having won awards such as the Meritorious Winner in the 2025 MCM/ICM and National Second Prize in the 2025 CUMCM. You can check my Google Scholar profile <a href='https://scholar.google.com/citations?user=qgcpKl4AAAAJ'>here <strong><span id='total_cit'></span></strong></a> (You can also view citation badge <a href='https://scholar.google.com/citations?user=qgcpKl4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2026.03*: &nbsp;🎉🎉 Our paper on "DARE: Domain-Aware Representation Enhancement for Data-Efficient Histopathological Tissue Classification" received a revision invitation from *Biomedical Signal Processing and Control* (BSPC, JCR Q1).
- *2025.11*: &nbsp;🎉🎉 Awarded National Second Prize in the 2025 National Undergraduate Mathematics Modeling Competition.
- *2025.04*: &nbsp;🎉🎉 Awarded Meritorious Winner (International First Prize) in the 2025 Mathematical Contest in Modeling (MCM/ICM).



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BSPC (Revise)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DARE: Domain-Aware Representation Enhancement for Data-Efficient Histopathological Tissue Classification](https://scholar.google.com/citations?user=qgcpKl4AAAAJ)

**Zhijin Rong**, Xueying Zeng\*, J. Zhang, Q. Zhang

*Biomedical Signal Processing and Control* (Under Revision, 2026)

[**Project**](https://github.com/AndyRong921/DARE) <strong><span class='show_paper_citations' data='qgcpKl4AAAAJ:ALROH1vI_8AC'></span></strong>

<p>
  <img src="https://img.shields.io/badge/Python-3.8%2B-green" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-2.0.0%2B-orange" alt="PyTorch">
  <a href="https://github.com/AndyRong921/DARE"><img src="https://img.shields.io/github/stars/AndyRong921/DARE?style=social" alt="GitHub stars"></a>
  <a href="https://github.com/AndyRong921/DARE"><img src="https://img.shields.io/github/forks/AndyRong921/DARE?style=social" alt="GitHub forks"></a>
</p>

- Introduced statistical sampling theory to construct a dual-enhancement framework (DARE) to address scarce annotations and high heterogeneity in medical images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Highl. Sci. Eng. Technol.</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Study on the Impact of Nuclear Pollution Discharge on the Seafood Industry in Coastal Cities Based on the DID-SARIMA Model](https://doi.org/10.54097/fy4z4r12)

Xuan Wang\*, **Zhijin Rong**\*, et al.

*Highlights in Science, Engineering and Technology*, 2025

[**Paper**](https://doi.org/10.54097/fy4z4r12)

<p>
  <img src="https://img.shields.io/badge/R-%26%20Python-blue" alt="Language">
  <img src="https://img.shields.io/badge/Method-DID%20%26%20SARIMA-lightgrey" alt="Method">
</p>

- Integrated Difference-in-Differences (DID) causal inference with SARIMA dynamic time-series forecasting to evaluate economic impacts.
</div>
</div>


# 🎖 Honors and Awards
- *2025.04* **Meritorious Winner (International First Prize)**, Mathematical Contest in Modeling (MCM/ICM)
- *2025.09* **National Second Prize**, National Undergraduate Mathematics Modeling Competition (CUMCM)
- *2024.10* **First-Class Comprehensive University Scholarship** & **Outstanding Student of the University** (2023-2024, 2024-2025)
- *2025.06* **Provincial Second Prize**, National Undergraduate Mathematics Modeling Competition (CUMCM, 2024)
- *2025.03* **Honorable Mention**, Mathematical Contest in Modeling (MCM, 2026)


# 📖 Education
- *2023.09 - Present*, **Ocean University of China (OUC)**, Qingdao, China.
  - Undergraduate student in Mathematics and Applied Mathematics.


# 💼 Academic Service
- *2025.03 - 2026.06*, **Teaching Assistant**, Undergraduate second-year courses, Numerical methods.
- *2025.09 - 2026.02*, **Outstanding Teaching Assistant**, Undergraduate second-year courses, Ordinary Differential Equation.



# 💻 Research Experience
- **Elimination of Batch Effects in Viral Abundance Quantification** | *Core Member* (2026 - Present)
  - Applying mathematical and statistical theories, specifically Bayesian estimation and robust regression modeling methodologies, to systematically eliminate batch effects in viral abundance across high-throughput sequencing datasets.
- **DARE: Domain-Aware Representation Enhancement for Data-Efficient Histopathological Tissue Classification** | *First Author* (2023.11 - Present)
  - Developed the DARE dual-enhancement framework using statistical sampling theory, combining image-space low-order statistic perturbation and feature-space pseudo-domain interpolation to resolve domain shift issues under few-shot scenarios. Resulted in a first-author paper currently under revision at *Biomedical Signal Processing and Control* (JCR Q1).
- **Research on the Economic Impact of Coastal Seafood Industry Based on DID-SARIMA Model** | *Co-First Author* (2023 - 2024)
  - Integrated the Difference-in-Differences (DID) method for policy impact causal inference and utilized the SARIMA model for seasonal time-series dynamic forecasting, quantitatively evaluating the long-term economic effects of nuclear wastewater discharge on the regional coastal seafood industry. Resulted in a co-first-author publication in *Highlights in Science, Engineering and Technology*.
