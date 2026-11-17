---
# ═══════════ RESOURCES ═══════════
# Pages live in static/demos/ and static/tutorials/; card images sit next to this file.
title: 资源
type: resources
eyebrow: 研究资源
lead: 课题组的交互演示、课程材料、虚拟实验室和学习笔记。
chips:
- name: 交互演示
  url: '#demos'
- name: 物理光学课程
  url: '#course'
- name: 虚拟实验室与搭建指南
  url: '#labs'
- name: 笔记与手册
  url: '#notes'
- name: 代码与数据
  url: '#software'
sections:
- id: demos
  title: 交互演示
  label: 交互演示
  columns: 3
  text: 在浏览器里探索论文背后的光学原理：拖动旋转、逐步查看采集过程、调整参数。
  items:
  - title: 贝塞尔光束拍频层析
    subtitle: SRST · PS-OB³ TPFT
    image: bessel-beating-tomography.jpg
    text: 两束贝塞尔光的光学拍频如何把深度信息编码到空间频率中，以及如何通过逆傅里叶变换在不做 z 扫描的情况下恢复深度分布。
    links:
    - name: 打开演示
      url: demos/bessel-beating-tomography.html
    - name: 论文（2024）
      url: publication/2024-ps-ob3-tpft/
    - name: 论文（2021）
      url: publication/2021-srs-tomography/
  - title: 贝塞尔光弹 · B²-SRS
    subtitle: 飞行时间光学切片
    image: bessel-light-bullet-b2srs.jpg
    text: 群速度可调的泵浦光与斯托克斯贝塞尔光弹在样品中相向传播、相遇，延时决定成像深度。
    links:
    - name: 打开演示
      url: demos/bessel-light-bullet-b2srs.html
    - name: 论文
      url: publication/2024-bessel-light-bullet-srs/
  - title: PHYSIQ-SRS 光路
    subtitle: 物理配对 I/Q 探测
    image: physiq-optical-path.jpg
    text: 逐站漫游 PHYSIQ-SRS 系统的三维光路，从激光器到双相位锁相探测。
    links:
    - name: 打开演示
      url: demos/physiq-optical-path.html
    - name: 论文
      url: publication/2026-physiq-srs/
- id: course
  title: 物理光学课程
  label: 课程
  columns: 2
  text: 交互式物理光学系列：每一集都包含三维场景、二维场截面和对应公式，滑块直接驱动仿真。
  items:
  - title: EP01 · 从电磁波到波前
    subtitle: 波动方程 · 平面波与球面波 · 干涉
    image: tut-physical-optics-ep01.jpg
    text: 从真空中的波动方程出发，逐步建立波前与干涉图样。
    links:
    - name: 打开
      url: tutorials/physical-optics-ep01.html
  - title: EP02 · 计算全息与结构光
    subtitle: 全息 · SLM 相位图 · 结构光束
    image: tut-physical-optics-ep02.jpg
    text: 从底片记录光强，到计算全息图、用相位掩模塑造结构光。
    links:
    - name: 打开
      url: tutorials/physical-optics-ep02.html
  - title: EP03 · 超快光与时空光场
    subtitle: 脉冲 · 色散 · 时空耦合
    image: tut-physical-optics-ep03.jpg
    text: 脉冲是频率分量的相干叠加；当空间与时间耦合时会发生什么。
    links:
    - name: 打开
      url: tutorials/physical-optics-ep03.html
  - title: EP04 · 非线性光学与相干拉曼成像
    subtitle: 非谐振子 · 二次谐波 · CARS / SRS
    image: tut-physical-optics-ep04.jpg
    text: 从带非谐项的洛伦兹振子，到二次谐波产生与相干拉曼散射显微成像。
    links:
    - name: 打开
      url: tutorials/physical-optics-ep04.html
- id: labs
  title: 虚拟实验室与搭建指南
  label: 虚拟实验室
  columns: 3
  text: 通过交互式仪器了解系统如何搭建、如何调节，以及每个部件的作用。
  items:
  - title: 多模态显微镜虚拟实验室
    subtitle: 同一台显微镜上的 TPF · SHG · SRS
    image: tut-multimodal-microscopy-virtual-lab.jpg
    text: 把部件从光路中拔掉，观察信号、噪声谱和重建图像如何变化。包含引导教学和自由探索两种模式。
    links:
    - name: 打开
      url: tutorials/multimodal-microscopy-virtual-lab.html
  - title: DIY 双光子扫描显微镜（3D）
    subtitle: 正置 · 共振-振镜扫描 · 非退扫探测
    image: tut-diy-two-photon-microscope-3d.jpg
    text: 自搭双光子显微镜的三维模型，含 32 个带标注的部件、光路和扫描动画。
    links:
    - name: 打开
      url: tutorials/diy-two-photon-microscope-3d.html
  - title: D-FFOCT 从零搭建与装调
    subtitle: 动态全场 OCT · Linnik 干涉仪
    image: dffoct-build-alignment.jpg
    text: 一步步搭建并调节动态全场 OCT 显微镜的三维指南。
    links:
    - name: 打开
      url: demos/dffoct-build-alignment.html
  - title: TGV 三维光场加工系统
    subtitle: 玻璃通孔 · 轴向可编程光场
    image: tut-tgv-3d-light-field-fabrication.jpg
    text: 实验系统与原理：轴向可编程针状光场、沉积驱动的逆设计以及 z 向周期光场。
    links:
    - name: 打开
      url: tutorials/tgv-3d-light-field-fabrication.html
  - title: 双轴锥镜光路 · 3D 交互台
    subtitle: 环形光与贝塞尔光束的产生
    image: axicon-pair-3d-lab.jpg
    text: 调整两个轴锥镜的锥角、间距和失调量，观察对应的光强分布。
    links:
    - name: 打开
      url: demos/axicon-pair-3d-lab.html
- id: notes
  title: 笔记与手册
  label: 笔记
  columns: 2
  text: 带交互图示的阅读图谱与学习笔记。
  items:
  - title: 超分辨成像手册
    subtitle: 衍射极限 · SIM · STED · 单分子定位
    image: tut-super-resolution-imaging-handbook.jpg
    text: 荧光超分辨成像的交互式学习手册，含方法对比、实践要点和自测。
    links:
    - name: 打开
      url: tutorials/super-resolution-imaging-handbook.html
  - title: 超分辨前沿详解
    subtitle: 前沿专题，2017–2026
    image: tut-super-resolution-frontiers.jpg
    text: 分子尺度定位、膨胀显微、活细胞 SIM，以及单帧、无标记和计算方法，附横向对比与来源。
    links:
    - name: 打开
      url: tutorials/super-resolution-frontiers.html
  - title: 光计算讲义
    subtitle: 4f 系统 · MZI 网格 · 衍射网络
    image: tut-optical-computing-notes.jpg
    text: 为什么用光来计算，以及透镜、干涉仪网格、波长复用和衍射网络各自如何实现计算。
    links:
    - name: 打开
      url: tutorials/optical-computing-notes.html
  - title: OCT 学习图谱
    subtitle: 光学相干层析成像 · 84 章
    image: tut-oct-learning-map.jpg
    text: 按 Drexler 与 Fujimoto 主编的《Optical Coherence Tomography》（第 2 版，Springer，2015）逐章整理的学习图谱，可记录学习进度。
    links:
    - name: 打开
      url: tutorials/oct-learning-map.html
- id: software
  title: 代码与数据
  label: 代码与数据
  text: 随论文发布的代码和数据集将在这里列出。
  items: []
next:
- title: 发表论文
  text: 这些资源对应的论文。
  url: publication/
- title: 研究方向
  text: 资源背后的研究问题。
  url: research/
- title: 加入我们
  text: 咨询使用或扩展某项资源。
  url: contact/
---
