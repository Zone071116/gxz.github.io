---
permalink: /
title: "Kailun Mai's Homepage"
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
  padding: 20px;
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
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.2s;
}
.profile-intro strong {
  color: #2980b9;
}

/* 4. 论文卡片：优化图片排版+响应式适配+动画 */
.paper-box {
  display: flex;
  gap: 25px;
  padding: 25px;
  margin: 0 auto 35px;
  max-width: 1100px;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
  align-items: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.4s;
}
.paper-box:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
}
/* 移动端：卡片改为垂直布局，图片居中 */
@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
    padding: 20px;
    gap: 20px;
  }
  .paper-box-image {
    flex: 0 0 auto !important;
    width: 100% !important;
    max-width: 400px !important;
    margin: 0 auto 15px !important;
  }
  .paper-box-image img {
    height: auto !important;
    min-height: 180px !important;
  }
}
.paper-box-image {
  flex: 0 0 300px;
  margin: 5px 0;
  overflow: hidden;
  border-radius: 8px;
}
.paper-box-image img {
  border-radius: 8px;
  object-fit: cover;
  width: 100%;
  height: 220px;
  border: 1px solid #f0f0f0;
  transition: transform 0.5s ease;
}
.paper-box-image img:hover {
  transform: scale(1.05);
}
.paper-box-text {
  flex: 1;
  font-size: 15px;
  color: #34495e;
  padding: 5px 0;
}

/* 5. 成果列表：优化间距+层级+动画 */
#Achievements {
  padding-left: 20px;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.6s;
}
#Achievements li {
  margin-bottom: 30px;
  padding-left: 12px;
  border-left: 3px solid #3498db;
  transition: border-color 0.3s ease, background-color 0.3s ease;
}
#Achievements li:hover {
  border-left-color: #2980b9;
  background-color: rgba(52, 152, 219, 0.03);
}
#Achievements li strong {
  color: #2980b9;
  font-size: 16px;
}

/* 6. 发表论文：规整格式+高亮期刊+动画 */
.articles-list {
  padding-left: 20px;
  list-style-type: decimal;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.8s;
}
.articles-list li {
  margin-bottom: 20px;
  padding-right: 10px;
  font-size: 15px;
}
.articles-list li em {
  color: #e74c3c;
  font-style: normal;
  font-weight: bold;
}
.articles-list li a {
  color: #3498db;
  text-decoration: none;
  position: relative;
  transition: color 0.3s ease;
}
.articles-list li a::after {
  content: "";
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 0;
  height: 2px;
  background-color: #2980b9;
  transition: width 0.3s ease;
}
.articles-list li a:hover {
  color: #2980b9;
}
.articles-list li a:hover::after {
  width: 100%;
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

/* 8. 谷歌学术统计：居中显示+间距 */
.gs-stats {
  text-align: center;
  margin: 40px 0;
}
.gs-stats img {
  margin: 0 15px;
  vertical-align: middle;
}

/* 9. 动画关键帧定义 */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<span class='anchor' id='about-me'></span>

## About Me
<div class="profile-intro">
I strictly adhere to school and class regulations, respect teachers, and unite with classmates; actively participate in volunteer services (such as tree-planting activities on Arbor Day and serving as a referee for the Freshmen Cup table tennis competition), assist in cleaning the Shahe Town Service Center, serve as a dormitory leader to help maintain the cleanliness of the dormitory floors, and fully uphold collective honor. I study diligently, maintaining the habit of "previewing before class, focusing during class, and reviewing after class," with academic performance consistently ranking at the top of the class. I actively participate in competitions and scientific research activities, including the Beihang AERO Racing Team competition, and have been awarded honors such as Outstanding Science and Technology Camp Participant by the school. In my spare time, I expand my knowledge through popular science books like "Global Science" to enhance my academic literacy. I maintain a daily exercise routine, actively participate in table tennis (Fengyun Cup) and volleyball competitions; join the school's volleyball and billiards clubs, and take part in their regular activities. (ranked <strong>3rd out of 80 participants</strong>).
</div>

## News
<!-- 图片优化：移除原400%宽度错误设置，依赖CSS控制尺寸 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">中国康复医学报告2022</div>
      <img src='images/pic-m.png' alt="中国康复医学报告2022相关图片">
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