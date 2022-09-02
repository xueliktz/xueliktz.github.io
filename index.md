---
title: Home
---

# Your Lab Slogan


{%
  include card.html
  image="images/home.svg"
  link="https://xueliktz.github.io/research/"
  title="基础研究与应用方向"
  description="雪梨课题组的基础研究主要集中在：1）信号处理：图像处理、阵列信号处理、目标检测与识别、人工智能等；2）集成电路设计：低功耗、高能效、高算力等构架与电路设计。
主要应用方向包括：1）先进医疗：面向医学临床需求，提供医护人员更好的诊疗手段和工具，实现重大疾病的精准诊断与治疗。重点研究消化道微成像系统、高精度肺部穿刺手术导航系统。2）海洋探索：旨在解决水下空间、能量受限条件下如何“看得清、认得准”等问题。重点研究水下可重构声纳阵列信号处理、水下光学图像处理、面向水下无人平台的智能芯片系统设计等。3）便携式人机交互：旨在解决“无处不在”的人机自然交互问题，实现随时随地、舒适、方便的口袋式或穿戴式自然交互，满足人们对高品质生活的不断追求。重点研究基于图像传感器结合微型投影的便携式人机交互方法与微系统设计、面向第一人称的双视人机交互方法与微系统设计。"
  tooltip="A cool tooltip"
  tags="先进医疗, 海洋探索, 人机交互"
%}


{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
