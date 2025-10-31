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