---
permalink: /
title: "Yan Zhang's Homepage"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 1. 全局样式：基础规整+移动端适配 */
body {
  line-height: 1.7;
  margin: 0 auto;
  max-width: 1200px;
  padding: 20px; /* 移动端减少左右内边距 */
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #333;
}

/* 2. 模块标题：强化识别度+统一间距 */
h2 {
  color: #2c3e50;
  border-bottom: 2px solid #3498db;
  padding-bottom: 10px;
  margin: 50px 0 25px;
  font-size: 1.4rem;
}

/* 3. 个人信息模块：突出关键成就 */
.profile-intro {
  margin-bottom: 30px;
}
.profile-intro strong {
  color: #2980b9; /* 高亮关键信息：如项目、奖项 */
}

/* 4. 论文卡片：优化图片排版+响应式适配（核心优化部分） */
.paper-box {
  display: flex;
  gap: 25px; /* 增加图片与文字间距，避免拥挤 */
  padding: 25px;
  margin: 0 auto 35px; /* 水平居中，增加底部间距 */
  max-width: 1100px; /* 限制卡片最大宽度，避免过宽 */
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06); /* 微调阴影，更显质感 */
  align-items: center; /* 图片与文字垂直居中对齐，更协调 */
}
/* 移动端：卡片改为垂直布局，图片居中 */
@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
    padding: 20px;
    gap: 20px;
  }
  .paper-box-image {
    flex: 0 0 auto !important; /* 取消固定宽度 */
    width: 100% !important; /* 图片占满容器 */
    max-width: 350px !important; /* 限制移动端图片最大宽度，避免过大 */
    margin: 0 auto 15px !important; /* 图片居中 */
  }
}
.paper-box-image {
  flex: 0 0 240px; /* 适度加宽图片区域，提升视觉占比 */
  margin: 5px 0; /* 上下微留间距，避免贴边 */
}
.paper-box-image img {
  border-radius: 8px; /* 增加圆角，更显柔和 */
  object-fit: cover; /* 保持图片比例，避免拉伸变形 */
  width: 100%;
  height: 180px; /* 适度提高图片高度，增强视觉效果 */
  border: 1px solid #f0f0f0; /* 增加细边框，区分图片与背景 */
}
.paper-box-text {
  flex: 1;
  font-size: 15px;
  color: #34495e;
  padding: 5px 0; /* 上下微留间距，避免文字贴边 */
}

/* 5. 成果列表：优化间距+层级 */
#Achievements {
  padding-left: 20px; /* 列表整体右移，避免贴边 */
}
#Achievements li {
  margin-bottom: 30px; /* 增加成果项间距，避免拥挤 */
  padding-left: 12px;
  border-left: 3px solid #3498db;
}
#Achievements li strong {
  color: #2980b9;
  font-size: 16px;
}

/* 6. 发表论文：规整格式+高亮期刊 */
.articles-list {
  padding-left: 20px;
  list-style-type: decimal; /* 有序列表，对应论文序号 */
}
.articles-list li {
  margin-bottom: 20px;
  padding-right: 10px;
  font-size: 15px;
}
.articles-list li em {
  color: #e74c3c; /* 高亮SCI/Q1信息，突出学术价值 */
  font-style: normal;
  font-weight: bold;
}
.articles-list li a {
  color: #3498db; /* 链接蓝色，提升辨识度 */
  text-decoration: none;
}
.articles-list li a:hover {
  text-decoration: underline; /*  hover时显示下划线，提示可点击 */
}

/* 7. 标签样式：优化视觉 */
.badge {
  display: inline-block;
  padding: 4px 10px;
  margin-bottom: 10px;
  background: #3498db;
  color: #fff;
  font-size: 13px;
  border-radius: 6px;
  font-weight: bold;
}

/* 8. 谷歌学术统计：居中显示+间距（已保留原样式，若后续启用可直接用） */
.gs-stats {
  text-align: center;
  margin: 40px 0;
}
.gs-stats img {
  margin: 0 15px; /* 多个统计图标之间加间距 */
  vertical-align: middle;
}
</style>

<span class='anchor' id='about-me'></span>

## About Me: Yan Zhang
<div class="profile-intro">
I am a "Distinguished Hundred Talents" postdoctoral fellow at Beihang University. My research focuses on key issues in respiratory exoskeleton robots, including bionic mechanisms, variable-stiffness and variable-configuration design, and human-in-the-loop control.<br>
I have published 4 SCI papers as the first author or corresponding author, including high-level papers in <em>IEEE Transactions on Biomedical Engineering</em> (IEEE TBME, a Q1 journal in the biomedical engineering field) and <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em> (IEEE TNSRE, a Q1 journal in the rehabilitation field). My doctoral dissertation was awarded the 2025 Doctoral Dissertation Incentive Program by the Technical Committee on Intelligent Robots of the China Computer Federation. Relevant achievements were invited for a presentation at the Youth Forum of the 2025 China Haptic Technology and Application Conference (ranked <strong>3rd out of 80 participants</strong>).
</div>


## Co-Supervisor: Yubo Fan
<div class="profile-intro">
Professor Fan Yubo is a recipient of the National Distinguished Young Scientist Fund. He currently serves as Dean of the Interdisciplinary Innovation Institute of Medical and Engineering, Dean of the School of Medical Science and Engineering, and Dean of the School of Biological and Medical Engineering at Beihang University.<br>
He also holds the positions of Director of the National Medical Research and Development Industry-Education Integration Platform (Medical-Engineering Integration), Director of the Beijing Advanced Innovation Center for Biomedical Engineering, and Director of the Key Laboratory of Biomechanics and Mechanobiology of the Ministry of Education.<br>
Professor Fan is a Changjiang Scholar Distinguished Professor, leader of the Innovation Group of the National Natural Science Foundation of China, and leader of the Innovation Team in Key Fields of the Ministry of Science and Technology. He is a recipient of the Special Government Allowance of the State Council. Additionally, he is a Fellow of the American Institute for Medical and Biological Engineering (AIMBE), International Academy for Medical and Biological Engineering (IAMBE), International Union for Physical and Engineering Sciences in Medicine (IUPESM), and Federation of the International Societies for Biomaterials Science and Engineering (FBSE).
</div>


## Doctoral Supervisor: Dangxiao Wang
<div class="profile-intro">
Professor Wang Dangxiao is a doctoral supervisor at Beihang University and Deputy Director of the State Key Laboratory of Virtual Reality Technology and Systems. He is also the Chief Scientist of a National Key Research and Development Program project.<br>
He has previously served as Chair of the IEEE Technical Committee on Haptics, Chair of AsiaHaptics 2022, and Associate Editor of <em>IEEE Transactions on Haptics</em> (IEEE TOH). His research areas include medical rehabilitation robots, haptic human-computer interaction, and brain-computer interface technology.<br>
Professor Wang has published more than 50 papers in IEEE Transactions journals as the first or corresponding author, including 25 papers in <em>IEEE Transactions on Haptics</em> (a top journal in the haptics field) as the first/corresponding author (ranked <strong>5th globally</strong> in terms of author order in the Web of Science database).
</div>


## News
<!-- 图片优化：移除原400%宽度错误设置，依赖CSS控制尺寸 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">中国康复医学报告2022</div>
      <img src='images/pic1(1).png' alt="中国康复医学报告2022相关图片">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
As shown in the picture, the research group to which Homo sapiens belongs applied to serve as the lead unit for the National Key R&D Program "Wearable Machine for Cardiopulmonary Assistance Integrating Homo sapiens," with Homo sapiens applying to participate as a core member of the project team. This involvement includes five research projects, such as the General Program of the National Natural Science Foundation of China and collaborative projects with Huawei. The related achievements have undergone effectiveness validation in over 200 applications and have been included as an additional technology in the "China Rehabilitation Medicine Report 2022" (the only selected technology in the respiratory machine Homo sapiens category), edited by Academician Wang Chen.
  </div>
</div>

## Achievements 
<ul id="Achievements">
  <li>
    <strong>Development of respiratory exoskeleton prototypes</strong><br>
    To address the issue that clinical positive pressure ventilators do not fully align with physiological breathing mechanisms and are prone to causing lung injuries and alveolar collapse, we proposed a soft wearable robotic device that simulates human physiological breathing. Three types of respiratory assist robotic devices were developed, and their efficacy was validated in five categories of patients with typical respiratory disorders (motor neuron injury, chronic obstructive pulmonary disease, cervical spinal cord injury, stroke, and traumatic respiratory failure). This research provides a hardware foundation and clinical experience for personalized optimization strategies involving human-in-the-loop for patients with various respiratory diseases. Professor Roche Ellen from the Department of Mechanical Engineering and Medical Engineering at MIT commented that the cardiopulmonary function assistive technology based on soft robots is promising to overcome the limitations of traditional ventilators.
  </li>
  <li>
    <strong>Bionic muscle-driven variable-stiffness design based on Broussonetia papyrifera origami</strong><br>
    The research team conducted preliminary studies on key technologies of respiratory assist devices, designing a variable-stiffness negative-pressure shell based on the layer-blocking variable-stiffness actuation principle, which can switch between rigid and soft states. In the rigid state, the shell can apply negative pressure ranging from 0 to -50 cmH₂O to the chest wall, meeting the pressure and volume requirements for inspiratory assistance. Additionally, the team achieved a breakthrough in fiber-reinforced double-layer casting technology and developed a high-output-force, high-folding-ratio soft actuator based on the Yoshimura tubular origami structure of Broussonetia papyrifera for expiratory assistance. The designed personalized portable exoskeleton system can effectively provide respiratory assistance to wearers in daily life scenarios and support the exploration of exoskeleton-assisted strategies during routine movements.
  </li>
  <li>
    <strong>Research on human-in-the-loop control strategies</strong><br>
    A closed-loop control system for respiratory assist devices was established, and a model-based proportional controller was designed to achieve personalized parameter adjustment and closed-loop tracking of complex breathing signals. By integrating a dual-chamber respiratory mechanics model with backstepping control, a biphasic control strategy for respiratory assist devices was proposed, enabling precise regulation of lung volume. Through flexible force tactile sensors and human-device interactive force compliance control, patient-ventilator asynchrony was effectively reduced. The previously developed exoskeleton testing platform allows rapid configuration of assistive modes and has high-precision control performance, providing technical support for real-time performance optimization and assistive mode efficacy evaluation of closed-loop exoskeleton systems.
  </li>
  <li>
    <strong>Multimodal respiratory intention perception</strong><br>
    A multimodal intention decoding framework was proposed based on the respiratory nerve-muscle-skeleton-airflow conduction mechanism. An IMU-based motion artifact removal method and a dynamic respiratory feature recognition algorithm were developed, achieving millisecond-level respiratory status monitoring and patient-ventilator synchrony triggering. Using diaphragm ultrasound for noninvasive monitoring of deep respiratory muscles, results showed that machine-assisted intervention significantly improved diaphragm mobility. Cortical EEG analysis revealed that during active respiratory control, the 0–2 Hz EEG power in the frontal and right parietal regions exhibited significantly enhanced phase-locking values with respiratory signals, enabling neural decoding of respiratory engagement. These findings provide a solid foundation for personalized respiratory profiling, respiratory status assessment, and real-time clinical efficacy evaluation across diverse diseases and individuals.
  </li>
</ul>


## Published Essays
<!-- 优化：改为有序列表，高亮SCI/Q1，规整作者与期刊格式 -->
<ol class="articles-list">
  <li><strong>Yan Zhang</strong>, Qinggang Ge, Zongyu Wang, Yuxing Qin, Yixing Wu, Mingjing Wang, Mai Shi, Lei Xue, Weidong Guo, Yuru Zhang, Guangyu Wang, and Dangxiao Wang. Extracorporeal closed-loop respiratory regulation for patients with respiratory difficulty using a soft bionic robot [J]. <em>IEEE Transactions on Biomedical Engineering</em>, 2024. <em>(SCI, Q1)</em> (First Author)</li>
  <li><strong>Yan Zhang</strong>, Danye Li, Fengyao Zhang, Zongyu Wang, Lei Xue, Xiaolu Nan, Nianming Li, Xilai Tan, Weidong Guo, Yuru Zhang, Hongmei Zhao, Qinggang Ge, Dangxiao Wang. Evaluation and modeling of diaphragm displacement using ultrasound imaging for wearable respiratory assistive robot [J]. <em>Frontiers in Bioengineering and Biotechnology</em>. <em>(SCI, Q1)</em> (First Author)</li>
  <li><strong>Yan Zhang</strong>,Ziqi Wang,Qinggang Ge, Zongyu Wang, Xiangjie Zhou, Shaohang Han,Yuru Zhang, Dangxiao Wang. Soft exoskeleton mimics human cough for assisting the expectoration capability of SCI patients [J]. <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em>, 2022. <em>(SCI, Q1)</em> (Co-First Author)</li>
  <li>Wenzhuo Zhi, Wei Zhao, <strong>Yan Zhang</strong>, Enming Shi, Yangfan Zhou, Bi Zhang. Thoraco-abdominal biomechanical model and dual-layer control method for soft robotic system with application to respiratory assistance [J]. <em>Frontiers in Bioengineering and Biotechnology</em>. <em>(SCI, Q1)</em> (Co-Corresponding Author)</li>
  <li>Yue Wang, <strong>Yan Zhang</strong>, Qinggang Ge, Yaoxi Zhang, Zongyu Wang, Weidong Guo, Yuru Zhang, Yuhui Wang, and Dangxiao Wang. Voluntary respiration control: signature analysis by EEG [J]. <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em>, 2023. <em>(SCI, Q1)</em> (Second Author)</li>
</ol>