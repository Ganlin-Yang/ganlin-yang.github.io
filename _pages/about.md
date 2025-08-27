---
layout: archive
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Yuqiang Yang, a Research&Development Engineer at [Embodied AI Center](https://internrobotics.shlab.org.cn/), [Shanghai AI Laboratory](https://www.shlab.org.cn/). Working with [Dr. Tai Wang](https://tai-wang.github.io/) and [Dr. Jiangmiao Pang](https://oceanpang.github.io/), my research interests are to combine LLM with robotic model-based optimization to enable various robots, such as **mobile manipulator, autonomous car, humanoid and multicopter**, to perform tasks autonomously and efficiently in unstructured environment. 

Specifically, we study post-training the **VLM-based System2** model and **diffusion-based obstacle avoidance System1** model to enable different embodiments (Unitree G1, Go2, Turtlebot, Galaxea, etc) to finish VLN tasks efficently and smoothly. Besides, we have explored and realized the possibility of allowing the mobile manipulators to efficiently pick and place in a **wholebody** manner while avoidance collision smoothly **in cluttered dynamic environment** full of chairs, tables and shelves. I have full-stack technical expertise across core domains including high-quality data generation, efficient model evaluation, sim2real transfer, robust robotics localization, high-dimensional motion planning and high-precision optimal control. 

Our team is dedecated to building Embodied AGI systems and empowering academia and industry through open-source initiatives. We have contributed many works on [github](https://github.com/InternRobotics). If you are interested to join us, feel free to contact us.
## Education and Training


<div style="float:left; text-align:left; line-height: 1.8">
<i><b>South China University of Technology</b></i>
<br>Master, Robotics
<br>Supervisor: Prof. <a href="https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao">Chenguang Yang</a>
<br> GPA: 3.82/4.0 (ranked first)
</div>
<div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br/>
<br/> <br/>
<br/>

<div style="float:left; text-align:left; line-height: 1.8">
<i><b>South China University of Technology</b></i>
<br>Bachelor of Engineering, Automation
<br>School of Automation Science and Engineering
<br>GPA: 3.94/4.0 (ranked first)
</div> <div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div> <br/>

<br/>
<br/>
<br/>


<div style="float:left; text-align:left; line-height: 1.8">
<i><b> <a href="http://zju-fast.com/fei-gao">FastLab</a> of Zhejiang University</b></i>
<br>Visiting student
<br>Wholebody planning and  control for multicopter
<br>Supervisor: Prof. <a href="http://zju-fast.com/fei-gao">Fei Gao</a>
</div>
 <div style="float:right; text-align:right"><i>Oct. 2023 - Nov. 2023</i></div> <br/>
<br/>
<br/>


## Research Experiences
<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：2个小图在上、1个长图在下 -->
  <div style="flex: 1; min-width: 300px;">
    <!-- 上方：2个小图横向排列 -->
    <div style="display: flex; gap: 10px; margin-bottom: 10px;">
      <img src="../files/esdf.gif" alt="ESDF Map" style="width: 48%; height: auto; object-fit: contain;">
      <img src="../files/planning.gif" alt="Planning Trajectory" style="width: 48%; height: auto; object-fit: contain;">
    </div>
    <!-- 下方：1个长图全屏宽度 -->
    <img src="../files/realwolrd.gif" alt="Real-World Experiment" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、期刊、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">RAMPAGE: Towards Whole-body, Real-Time and Agile Motion Planning in Dynamic Cluttered Environments for Mobile Manipulators</h3>
    <p>[<a href="https://yuqiang-yang.github.io/publications#rampage">Video</a>, <a href="https://github.com/yuqiang-yang/TIE-Supplementary-video">PDF</a>]</p>
    <p>2024 IEEE Transaction on Industrial Electronics</p>
    <p>• Proposed a hierarchical topology-guided search and AL-DDP-based optimization to solve whole-body kinodynamic planning in dynamic environments.<br>
    • Achieved real-time planning (≈30ms) and ≈80% success rate with accurate collision detection via ESDF map and sphere decomposition.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/open_door.gif" alt="Door Opening Demo" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、会议、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Learn to Coordinate: a Whole-Body Learning from Demonstration Framework for Differential Drive Mobile Manipulators</h3>
    <p>[<a href="https://yuqiang-yang.github.io/publications#open_door">Video1</a>, <a href="https://yuqiang-yang.github.io/publications#learning">Video2</a>, <a href="https://ieeexplore.ieee.org/abstract/document/10394442">PDF</a>]</p>
    <p>2023 IEEE Conference on Systems, Man, and Cybernetics</p>
    <p>• Developed a Gaussian Process-based learning framework with WLN inverse kinematics for few-shot whole-body skill learning.<br>
    • Enabled coordinated door opening with disturbance rejection, simplifying human guidance via admittance control.</p>
  </div>
</div>

# Project Experiences
<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：4个图（原2x2排列，保持4图在左侧） -->
  <div style="flex: 1; min-width: 300px;">
    <div style="display: flex; flex-wrap: wrap; gap: 10px;">
      <img src="../files/h1-hosp.gif" alt="H1 in Hospital" style="width: 48%; height: auto; object-fit: contain;">
      <img src="../files/h1-office.gif" alt="H1 in Office" style="width: 48%; height: auto; object-fit: contain;">
      <img src="../files/h1-out.gif" alt="H1 Outdoors" style="width: 48%; height: auto; object-fit: contain;">
      <img src="../files/h1-stair.gif" alt="H1 on Stairs" style="width: 48%; height: auto; object-fit: contain;">
    </div>
  </div>
  <!-- 右侧：标题、链接、状态、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Locomotion in complex terrain through reinforcement learning in Isaac lab</h3>
    <p>[<a href="https://yuqiang-yang.github.io/cv#rl">Video</a>]</p>
    <p>• Used PPO algorithm with a fine-tuned reward function to train Unitree H1’s locomotion via curriculum learning.<br>
    • Realized robust Sim-to-Sim transfer of RL policies to diverse photo-realistic environments in Nvidia Isaac Sim.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：占位图（无原始图，保持左侧区域） -->
  <div style="flex: 1; min-width: 300px;">
    <div style="width: 100%; height: 300px; background: #f5f5f5; display: flex; align-items: center; justify-content: center; color: #666;">
      AVP Motion Planning Visualization (Image Placeholder)
    </div>
  </div>
  <!-- 右侧：标题、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Risk-aware contingency motion planning under uncertainties for Automated Valet Parking(AVP)</h3>
    <p>DJI Automotive</p>
    <p>• Proposed Voronoi-based safe corridors and SplineGrid optimization for lateral bypass, plus iLQR for risk-aware longitudinal speed.<br>
    • Handled prediction multimodality via tree-branch iLQR, ensuring safe trajectory under perception/prediction uncertainties.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/fly_forest.gif" alt="Multicopter in Forest" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Low-cost and efficient location, mapping, planning and control for multicopter in embedded system</h3>
    <p>[<a href="https://yuqiang-yang.github.io/talks#planning">Video1</a>, <a href="https://yuqiang-yang.github.io/talks#hover">Video2</a>, <a href="https://yuqiang-yang.github.io/talks#rcesdf">Video3</a>]</p>
    <p>Application Innovate Laboratory, Huawei; FastLab, Zhejiang University | <i>2023.2 - 2024.3</i></p>
    <p>• Enhanced VINS-Fusion with learning-based features and QR optimization for better accuracy/robustness on low-performance chips.<br>
    • Implemented fast OGM updating (incremental inflation) and robot-centric ESDF for efficient MPCC-based collision-aware control.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/se3.jpg" alt="SE3 Narrow Gap Crossing" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">SE3 planning and control for multicopter to cross narrow gap</h3>
    <p>[<a href="https://yuqiang-yang.github.io/talks#se3">Video</a>]</p>
    <p>FastLab, Zhejiang University | <i>2023.10 - 2023.12</i></p>
    <p>• Built safe flight corridors (SFC) and used MINCO for spatial-temporal trajectory optimization via L-BFGS.<br>
    • Achieved accurate narrow gap crossing by calibrating thrust mapping and tuning controllers for large-attitude tracking.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/follow.gif" alt="Pedestrian Following Demo" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Pedestrian following and collision avoidance with spatial-temporal optimization for differential car</h3>
    <p>[<a href="https://yuqiang-yang.github.io/teaching#follow">Video</a>]</p>
    <p>Application Innovate Laboratory, Huawei; FastLab, Zhejiang University | <i>2023.2 - 2023.11</i></p>
    <p>• Developed multi-level hybrid A* for EKF-predicted pedestrian following, plus MINCO optimization for smooth trajectories.<br>
    • Ensured collision avoidance via lidar filtering and MPC control, handling kinematic constraints and communication delay.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/racing.png" alt="Self-balanced Racing Car" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Self-balanced racing car with wireless charging capability</h3>
    <p>[<a href="https://yuqiang-yang.github.io/teaching#balance">Video</a>]</p>
    <p>School of Automation Science and Engineering, SCUT | <i>2020.01 - 2020.08</i></p>
    <p>• Designed adaptive PD wireless charging (≈30W) for super-capacitors and tuned cascade controllers for stable track navigation.<br>
    • Won 5th national place with a 23.8s race time, successfully passing circles, slopes, and crossroads.</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
  <!-- 左侧：1个图 -->
  <div style="flex: 1; min-width: 300px;">
    <img src="../files/pick_place.gif" alt="Wholebody Pick-and-Place" style="width: 100%; height: auto; object-fit: contain;">
  </div>
  <!-- 右侧：标题、链接、单位、年份、英文总结 -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="margin-top: 0;">Wholebody pick-and-place for mobile manipulator</h3>
    <p>[<a href="https://yuqiang-yang.github.io/talks#pick_and_place">Video</a>]</p>
    <p>Application Innovate Laboratory, Huawei | <i>2022.10 - 2022.11</i></p>
    <p>• Trained GGCNN for 6-D object perception and used OSQP to solve dynamic-weighted QP for whole-body coordination.<br>
    • Enabled smooth pick-and-place by balancing manipulability, energy, and trajectory tracking performance.</p>
  </div>
</div>

## Honor & Awards

<ul>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2021-10</i></div></li>

<li> <div style="float:left; text-align:left"> Scholarship of <a href="https://www.gac.com.cn/cn/" title="GuangQi">Guangzhou Automobile Group Co., Ltd</a></div> <div style="float:right; text-align:right"><i>2020-10</i></div></li>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2019-10</i></div></li>
<li> <div style="float:left; text-align:left">The first prize of the <a href="https://www.caa.org.cn/Content/260.html" title="zhinengche">National University Students Intelligent Car Race</a> </div> <div style="float:right; text-align:right"><i>2020-08</i></div></li>
<li> <div style="float:left; text-align:left">Meritorious Winner of  <a href="https://www.comap.com/contests/mcm-icm" title="zhinengche">Interdisciplinary Contest In Modeling (ICM)</a> </div> <div style="float:right; text-align:right"><i>2021-03</i></div> </li>
</ul>


## Internship

<div style="float:left; text-align:left; line-height: 1.8">
<i><b> Huawei Technologies Co.Ltd</b></i>
<br>Intern, Application Innovation Laboratorys
<br>Planning and Control for various robots
<br>Supervisor: Dr. Chen Chen, Dr. Zehui Meng
</div>
 <div style="float:right; text-align:right"><i>June. 2022 - now</i></div> <br/>
<br/>
<br/>
<br/>

<div style="float:left; text-align:left; line-height: 1.8">
<i><b>China-Singapore International Joint Research Institute</b></i>
<br>Intern, Robot Perception and Computer Vision Group
<br>Multi-sensor calibration and 3D detection
<br>Supervisor: Dr. Mingxing Wen
</div>
 <div style="float:right; text-align:right"><i>Jan. 2021 - Mar. 2021</i></div> <br/>
<br/>
<br/>



## Skills

**Programming:**
<p>Python, MATLAB, C/C++, PyTorch, Pybullet, Airsim, Embedded System</p>  

**Robotics:**
<p>Wholebody control, Peception and mapping, Convex Optimization, Admittance/Impedance Control, Gravity Compensation, teleoperation</p>

**Hardware Experience:**
<p>Multicopter, <a href="https://en.directdrive.com/">Diablo</a>, Franka, UR, Mobile Manipulator, Robotiq 2F85, Vicon, Touch X, ATI sensors, STM32</p>