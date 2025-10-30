---
permalink: /
title: "Yan Zhang's Homepage"
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

## Project Applicant: Yan Zhang
I am a "Distinguished Hundred Talents" postdoctoral fellow at Beihang University. My research focuses on key issues in respiratory exoskeleton robots, including bionic mechanisms, variable-stiffness and variable-configuration design, and human-in-the-loop control.  
I have published 4 SCI papers as the first author or corresponding author, including high-level papers in *IEEE Transactions on Biomedical Engineering* (IEEE TBME, a Q1 journal in the biomedical engineering field) and *IEEE Transactions on Neural Systems and Rehabilitation Engineering* (IEEE TNSRE, a Q1 journal in the rehabilitation field). My doctoral dissertation was awarded the 2025 Doctoral Dissertation Incentive Program by the Technical Committee on Intelligent Robots of the China Computer Federation. Relevant achievements were invited for a presentation at the Youth Forum of the 2025 China Haptic Technology and Application Conference (ranked 3rd out of 80 participants).


## Co-Supervisor: Yubo Fan
Professor Fan Yubo is a recipient of the National Distinguished Young Scientist Fund. He currently serves as Dean of the Interdisciplinary Innovation Institute of Medical and Engineering, Dean of the School of Medical Science and Engineering, and Dean of the School of Biological and Medical Engineering at Beihang University. He also holds the positions of Director of the National Medical Research and Development Industry-Education Integration Platform (Medical-Engineering Integration), Director of the Beijing Advanced Innovation Center for Biomedical Engineering, and Director of the Key Laboratory of Biomechanics and Mechanobiology of the Ministry of Education.  
Professor Fan is a Changjiang Scholar Distinguished Professor, leader of the Innovation Group of the National Natural Science Foundation of China, and leader of the Innovation Team in Key Fields of the Ministry of Science and Technology. He is a recipient of the Special Government Allowance of the State Council. Additionally, he is a Fellow of the American Institute for Medical and Biological Engineering (AIMBE), International Academy for Medical and Biological Engineering (IAMBE), International Union for Physical and Engineering Sciences in Medicine (IUPESM), and Federation of the International Societies for Biomaterials Science and Engineering (FBSE). He is also a Member of the Academic Advisory Committee of the Chinese Academy of Medical Sciences, and a Fellow of the Chinese Society of Biomedical Engineering and the Chinese Society of Biomaterials. Professor Fan serves as a Member (Co-Convenor) of the Biomedical Engineering Discipline Appraisal Group of the Academic Degrees Committee of the State Council. His research interests cover the fields of biomedical engineering, medical devices, and rehabilitation aids.


## Doctoral Supervisor: Dangxiao Wang
Professor Wang Dangxiao is a doctoral supervisor at Beihang University and Deputy Director of the State Key Laboratory of Virtual Reality Technology and Systems. He is also the Chief Scientist of a National Key Research and Development Program project.  
He has previously served as Chair of the IEEE Technical Committee on Haptics, Chair of AsiaHaptics 2022, and Associate Editor of *IEEE Transactions on Haptics* (IEEE TOH). His research areas include medical rehabilitation robots, haptic human-computer interaction, and brain-computer interface technology. Professor Wang has published more than 50 papers in IEEE Transactions journals as the first or corresponding author, including 25 papers in *IEEE Transactions on Haptics* (a top journal in the haptics field) as the first/corresponding author (ranked 5th globally in terms of author order in the Web of Science database).


## News
<!-- 修复1：每个paper-box独立闭合，避免嵌套；修正标签与内容匹配问题 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- 原CVPR 2016标签与呼吸设备无关，替换为领域相关标签 -->
      <div class="badge">Respir Care 2022</div>
      <img src='images/pic1.png' alt="National Key R&D Program Project" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    The research group I belong to applied to be the lead unit for the National Key R&D Program "Wearable Cardiopulmonary Assistance Machine", and I participated as a core member of the project team. This involvement includes five research projects, such as the General Program of the National Natural Science Foundation of China and collaborative projects with Huawei. Related achievements have undergone effectiveness validation in over 200 applications and were included as an additional technology in the *China Rehabilitation Medicine Report 2022* (the only selected technology in the respiratory assist device category), edited by Academician Wang Chen.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Clin Rehabil 2023</div>
      <img src='images/pic2.png' alt="Respiratory Machine Research" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    The team I belong to is among the earliest units at home and abroad to conduct research on respiratory assist devices. Since 2020, we have continuously carried out innovative research on theories and methods related to respiratory assist devices. Focusing on sputum excretion assistance for critically ill patients, respiratory support for patients with breathing disorders, and rapid adaptability to hypoxic respiration, the team has conducted extensive clinical trials and accumulated abundant clinical resources and practical experience.
  </div>
</div>


## Achievements 
<!-- 修复2：统一列表层级，修正"Homo sapiens"误用，优化学术表述 -->
- **Development of respiratory exoskeleton prototypes**  
  To address the issue that clinical positive pressure ventilators do not fully align with physiological breathing mechanisms and are prone to causing lung injuries and alveolar collapse, we proposed a soft wearable robotic device that simulates human physiological breathing. Three types of respiratory assist robotic devices were developed, and their efficacy was validated in five categories of patients with typical respiratory disorders (motor neuron injury, chronic obstructive pulmonary disease, cervical spinal cord injury, stroke, and traumatic respiratory failure). This research provides a hardware foundation and clinical experience for personalized optimization strategies involving human-in-the-loop for patients with various respiratory diseases. Professor Roche Ellen from the Department of Mechanical Engineering and Medical Engineering at MIT commented that the cardiopulmonary function assistive technology based on soft robots is promising to overcome the limitations of traditional ventilators.

- **Bionic muscle-driven variable-stiffness design based on Broussonetia papyrifera origami**  
  The research team conducted preliminary studies on key technologies of respiratory assist devices, designing a variable-stiffness negative-pressure shell based on the layer-blocking variable-stiffness actuation principle, which can switch between rigid and soft states. In the rigid state, the shell can apply negative pressure ranging from 0 to -50 cmH₂O to the chest wall, meeting the pressure and volume requirements for inspiratory assistance. Additionally, the team achieved a breakthrough in fiber-reinforced double-layer casting technology and developed a high-output-force, high-folding-ratio soft actuator based on the Yoshimura tubular origami structure of Broussonetia papyrifera for expiratory assistance. The designed personalized portable exoskeleton system can effectively provide respiratory assistance to wearers in daily life scenarios and support the exploration of exoskeleton-assisted strategies during routine movements.

- **Research on human-in-the-loop control strategies**  
  A closed-loop control system for respiratory assist devices was established, and a model-based proportional controller was designed to achieve personalized parameter adjustment and closed-loop tracking of complex breathing signals. By integrating a dual-chamber respiratory mechanics model with backstepping control, a biphasic control strategy for respiratory assist devices was proposed, enabling precise regulation of lung volume. Through flexible force tactile sensors and human-device interactive force compliance control, patient-ventilator asynchrony was effectively reduced. The previously developed exoskeleton testing platform allows rapid configuration of assistive modes and has high-precision control performance, providing technical support for real-time performance optimization and assistive mode efficacy evaluation of closed-loop exoskeleton systems.

- **Multimodal respiratory intention perception**  
  A multimodal intention decoding framework was proposed based on the respiratory nerve-muscle-skeleton-airflow conduction mechanism. An IMU-based motion artifact removal method and a dynamic respiratory feature recognition algorithm were developed, achieving millisecond-level respiratory status monitoring and patient-ventilator synchrony triggering. Using diaphragm ultrasound for noninvasive monitoring of deep respiratory muscles, results showed that machine-assisted intervention significantly improved diaphragm mobility. Cortical EEG analysis revealed that during active respiratory control, the 0–2 Hz EEG power in the frontal and right parietal regions exhibited significantly enhanced phase-locking values with respiratory signals, enabling neural decoding of respiratory engagement. These findings provide a solid foundation for personalized respiratory profiling, respiratory status assessment, and real-time clinical efficacy evaluation across diverse diseases and individuals.