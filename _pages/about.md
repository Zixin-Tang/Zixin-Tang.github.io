---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently a research assistant at Shanghai AI Laboratory, where I am fortunate to work under the mentorship of Prof. [Xuelong Li](https://iopen.nwpu.edu.cn/info/1329/1171.htm). Before this, I obtained my M.S. degree from [National University of Defense Technology (NUDT)](https://www.nudt.edu.cn) in June 2023, advised by Prof. [Xin Xu](https://xueshu.baidu.com/scholarID/CN-B7736SUJ), and my bachelor's degree in Computer Science and Technology from [Sichuan University](https://www.scu.edu.cn).
    


Research Topics
------  
I am interested in <b>Embodied AI: Robotics, Deep Reinforcement Learning, and Computer Vision</b>.
Recently, my research mainly focuses on leveraging LLMs to tackle long-horizon manipulation challenges in robotics:
+ Embodied planning via LLMs: Heterogeneous Multi-agent Task Planning.
I am working on setting up heterogeneous multi-robot benchmark in simulation and contributing to our task planning method. (Below is a demo video to demonstrate the key point of our tasks.)


<p align="center">
  <a href="https://www.youtube.com/watch?v=GZIk6S_AlUc">
    <img src="https://github.com/Zixin-Tang/Zixin-Tang.github.io/blob/master/images/HADemoCover.png?raw=true" width="600" height="350" alt="Embodied Planning Demo">
  </a>
</p>

+ Embodied control via LLMs: Long-horizon Bimanual Manipulation.
I am working on designed a LLM-based control algorithm for long-horizon bimanual manipulation. The bimanual platform used is [ALOHA](https://tonyzhaozh.github.io/aloha/) designed by Stanford. (Below is a demo video to show a long-horizon task and its corresponding substeps)


<p align="center">
  <a href="https://www.youtube.com/watch?v=VmRhUqRFp-4">
    <img src="https://github.com/Zixin-Tang/Zixin-Tang.github.io/blob/master/images/ALOHACover.png?raw=true" width="600" height="350" alt="Embodied Control Demo">
  </a>
</p>



Publications
------
For a quick overview, please check this [summary file](https://Zixin-Tang.github.io/assets/pub/Online_Summary_material.pdf).

<b>[CSGP: Closed-loop Safe Grasp Planning via Attention-based Deep Reinforcement Learning from Demonstrations](https://ieeexplore.ieee.org/document/10059127)</b>

**IEEE Robotics and Automation Letters (RA-L 2023).**

<table border="0">
  <tr>
    <td>
      <img src="https://github.com/Zixin-Tang/Zixin-Tang.github.io/blob/master/images/HADemoCover.png?raw=true" width="250" height="110" alt="Video Title">
    </td>
    <td>
      <li>The first closed-loop planning method to achieve safe grasping in stacked scenarios</li>
      <li>Propose a Next-Best-Region (NBR) attention module to intrinsically identify safe regions</li>
      <li>Present a reinforcement learning from demonstrations algorithm for stable fine-tuning</li>
      <li>Experiments on 1000 stacked scenes demonstrate the state-of-the-art performance</li>
    </td>
  </tr>
</table>

<b>[SymmetryGrasp: Symmetry-Aware Antipodal Grasp Detection From Single-View 
RGB-D Images](https://ieeexplore.ieee.org/document/9919329)</b>

**IEEE Robotics and Automation Letters (RA-L 2022), also selected by ICRA 2023 for oral presentation.**

<table border="0">
  <tr>
    <td>
      <img src="https://github.com/Zixin-Tang/Zixin-Tang.github.io/blob/master/images/HADemoCover.png?raw=true" width="250" height="110" alt="Video Title">
    </td>
    <td>
      <li>The first symmetry-aware 7-DoF antipodal grasp detection method</li>
      <li>Propose a Principal-directional scale-Invariant Feature Transformer (PIFT) to improve grasping ability on novel objects</li>
      <li>Experiments on GraspNet-1Billion demonstrate the state-of-the-art performance for robust grasping synthesis</li>
    </td>
  </tr>
</table>

- The first symmetry-aware 7-DoF antipodal grasp detection method
- Propose a Principal-directional scale-Invariant Feature Transformer (PIFT) to improve grasping ability on novel objects
- Experiments on GraspNet-1Billion demonstrate the state-of-the-art performance for robust grasping synthesis

<b>[A deep Koopman Operator-based Modeling Approach for Long-term Prediction of 
Dynamics with Pixel-level Measurements](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12149)</b> 

**CAAI Transactions on Intelligence Technology (CAAI 2023).**
- Learning Koopman Operator-based latent dynamics model from raw pixels
- Achieve long-term prediction over 100 steps in latent space and reconstruction space
- Experiments in OpenAI Gym and MuJoCo demonstrate excellent performance in terms of high precision and fast inference

<b>[Efficient Reinforcement Learning with Least-squares Soft Bellman Residual for Robotic Grasping](https://www.sciencedirect.com/science/article/pii/S0921889023000246)</b> 

**Robotics and Autonomous Systems (RAS 2023).**
- A novel Actor-Critic algorithm based on least-squares soft Bellman residual
- Construct sparse kernel-based feature representations to improve sample efficiency and generalization ability
- Experiments compared with typical RL algorithms, e.g. SAC, DDPG, TD3, demonstrate better performance 

<b>[Grasp Planning Based on Deep Reinforcement Learning: A Brief Survey](https://ieeexplore.ieee.org/document/9727526)</b>

**China Automation Congress (CAC 2021).**



For more info
------
Please feel free to contact me at **email zixintangzx[at]gmail[dot]com**.
