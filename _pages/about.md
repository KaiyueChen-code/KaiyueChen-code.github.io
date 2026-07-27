---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 👋 About Me

Hi 👋! I am **Kaiyue Chen**, an undergraduate student in **Mechatronics and Robotic Systems** at [**Xi'an Jiaotong-Liverpool University**](https://www.xjtlu.edu.cn/en) (**XJTLU**) in Suzhou, China. My research focuses on **tactile-guided Vision-Language-Action (VLA)**, embodied manipulation.

I am currently a research intern at **Sudo Robotics**, advised by [**Prof. Rui Chen**](https://callmeray.github.io/homepage/), where I develop tactile-guided VLA systems for contact-rich bimanual manipulation. My work includes vision-based tactile sensing, a dual-arm **SmolVLA** pipeline, tactile video encoding, and **Flow Reversal Steering** for action correction.

Previously, I co-organized the **ManiSkill-ViTac Challenge 2026** at the CVPR 2026 Embodied AI Workshop and developed its tactile-VLA baseline. I am also a co-first author of **3WD-VLA**, a three-way decision framework for safer robotic grasping under ambiguity.

# 🔥 News
- *2026.03*: &nbsp;🤖 Joined **Sudo Robotics** as a research intern working on tactile-guided VLA for contact-rich manipulation.
- *2026.06*: &nbsp;🥳 **ManiSkill-ViTac Challenge 2026 was successfully completed.**
- *2026*: &nbsp;📝 Submitted two papers on **Three-Way Decision VLA** and **real-time robotic grasp detection**.
- *2025.08*: &nbsp;🏆 **National Finals**, *The 27th China Robot and Artificial Intelligence Competition* — **Baidu Service Robot** track, coached by Prof. Eng Gee Lim (**IEEE Fellow**).
- *2024.09*: &nbsp;📚 Started **BEng Mechatronics and Robotic Systems** at **XJTLU** (expected **2028**).

# 📝 Publications

<sup>&#42;</sup> Equal contribution.

- Yan Zhu<sup>&#42;</sup>, <strong>Kaiyue Chen<sup>&#42;</sup></strong>, Lingyu Li, Xiaohui Zhu, and Xinheng Wang. **“3WD-VLA: Hierarchical Three-Way Decision for Collaborative Dual-View Robotic Grasping.”** Submitted to the *22nd EAI International Conference on Collaborative Computing: Networking, Applications and Worksharing (EAI CollaborateCom 2026)*.

- Xiaoyu Xia, Chengcheng Hu, Leyi Liu, Junyan He, **Kaiyue Chen**, Yuhao Jin, Yong Yue, and Xiaohui Zhu. **“Real-Time 3-DoF Robotic Grasp Detection via Keypoint Regression.”** Submitted to the *31st International Conference on Automation and Computing (ICAC 2026)*.

# 💬 Research Experience
- *2026.06 - Present*, **Research Intern**, *Tactile-Guided VLA for Contact-Rich Robotic Manipulation*, Sudo Robotics (Advisor: [**Prof. Rui Chen**](https://callmeray.github.io/homepage/)).
  - Designed and deployed vision-based tactile sensors on bimanual grippers to mitigate partial observability caused by occlusion and limited visual feedback.
  - Built a dual-arm tactile-VLA pipeline based on **SmolVLA (0.7B)** and am developing a tactile video encoder for contact geometry, shear deformation, and slip-related dynamics.
  - Explored **Flow Reversal Steering** to map tactile-guided coarse action corrections into the latent noise space of pretrained VLA policies.

- *2026.03 - 2026.06*, **Student Organizer**, *ManiSkill-ViTac Challenge 2026*, CVPR 2026 Embodied AI Workshop.
  - Built an end-to-end VLA pipeline around UMI-based data collection, covering hardware maintenance, data processing and filtering, model training, and real-robot deployment.
  - Integrated **AnyTouch** tactile representations into a **π0.5-based VLA** using modality-weighted training to establish the competition baseline.
  - Designed two long-horizon, contact-rich tasks and co-organized the challenge and accompanying technical report.

- *2026.01 - 2026.05*, **Co-first Author**, *Three-Way Decision VLA*, Xi’an Jiaotong-Liverpool University (Advisor: [**Prof. Xinheng Wang**](https://scholar.google.com/citations?user=TeoBMbgAAAAJ&hl=en&oi=ao)).
  - Developed a collaborative robotic grasping framework that defers action when direct execution is unsafe or unreliable, including ambiguous commands, target absence, human-hand intrusion, occlusion, and stacked objects.
  - Built a teleoperation data-collection pipeline for the **SO-100** robot arm and trained **ACT**, **π0.5**, and **SmolVLA** models.
  - Improved performance by **27.5 percentage points** over a matched SmolVLA baseline without 3WD and demonstrated clearer behavior under ambiguity, occlusion, and object stacking.

<span class='anchor' id='-internships'></span>

# 💼 Internships

<div class="project-list">
  <div class="project-card project-card--logo">
    <img src="/assets/images/internships/sudo-ai.png" alt="Sudo Robotics logo">
    <div>
      <h3>Sudo Robotics</h3>
      <div class="project-meta">2026.06 - Present · Research Intern</div>
      <span class="project-tag">Tactile Sensing</span>
      <span class="project-tag">VLA</span>
      <span class="project-tag">Bimanual Manipulation</span>
    </div>
  </div>
</div>

<span class='anchor' id='projects'></span>

# 🧩 Projects

<style>
.project-list {
  display: flex;
  flex-direction: column;
  gap: 1.6rem;
  margin-top: 1rem;
}

.project-card {
  display: grid;
  grid-template-columns: 220px 1fr;
  gap: 1.4rem;
  align-items: center;
}

.project-card img {
  width: 100%;
  border-radius: 8px;
  object-fit: cover;
}

.project-card--logo {
  grid-template-columns: 100px 1fr;
}

.project-card--logo img {
  width: 80px;
  max-width: 80px;
  height: auto;
  object-fit: contain;
  background: #fff;
  padding: 0.5rem;
  border: 1px solid #e8e8e8;
  border-radius: 8px;
}

.project-card h3 {
  margin: 0 0 0.35rem;
  font-size: 1.15rem;
}

.project-meta {
  margin-bottom: 0.55rem;
  color: #6f777d;
  font-weight: 600;
}

.project-tag {
  display: inline-block;
  margin: 0 0.35rem 0.55rem 0;
  padding: 0.2rem 0.55rem;
  border-radius: 6px;
  background: #e8f1ff;
  color: #2f5f9f;
  font-weight: 700;
  font-size: 0.8rem;
}

.project-links a {
  display: inline-block;
  margin: 0.15rem 0.35rem 0.15rem 0;
  padding: 0.25rem 0.7rem;
  border: 1px solid #d0d7de;
  border-radius: 5px;
  color: #3d4144;
  font-weight: 700;
  text-decoration: none;
}

@media (max-width: 600px) {
  .project-card {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="project-list">
  <div class="project-card">
    <img src="/assets/images/projects/maniskill-vitac-2026.png" alt="ManiSkill-ViTac Challenge 2026 project preview">
    <div>
      <h3>ManiSkill-ViTac Challenge 2026: Real-world Language-guided Bimanual Vision-Tactile Manipulation</h3>
      <div class="project-meta">CVPR 2026 Embodied AI Workshop · Student Organizer</div>
      <span class="project-tag">CVPR 2026</span>
      <span class="project-tag">VLA</span>
      <span class="project-tag">Tactile</span>
      <div class="project-links">
        <a href="https://callmeray.github.io/Mani_ViTac_Challenge_2026_page/">Project Page</a>
      </div>
    </div>
  </div>
</div>


# 💻 Competitions
- *2025.08*, **National Finals Team Member, Baidu Service Robot Competition**, *The 27th China Robot and Artificial Intelligence Competition*, Suzhou; coached by [**Prof. Eng Gee Lim**](https://scholar.google.com/citations?user=zHw8eegAAAAJ&hl=en) (**IEEE Fellow**).
  - Developed a ROS-based autonomous restaurant-service robot with order-driven task coordination, integrating touchscreen interaction, multi-point navigation, food pickup, delivery, and checkout.

# 📖 Education
- *2024.09 - 2028.07 (expected)*, **BEng Mechatronics and Robotic Systems**, Xi’an Jiaotong-Liverpool University, Suzhou, China. GPA (Years 1-2): **3.83/4.0**. Core coursework: Linear Algebra (**4.0**), Calculus (**4.0**), and C Programming (**4.0**).

# 🛠 Technical Skills
- **Robotics:** PyTorch, deep reinforcement learning, ROS1/2, Gazebo, Isaac Sim, ManiSkill.
- **Programming:** Python, C, C++.
- **Design and tools:** SolidWorks, Autodesk Fusion 360.
