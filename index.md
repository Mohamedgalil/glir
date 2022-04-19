---
layout: default
title:  GLIR
description: A Practical Global-local Integrated Reactive Planner towards Safe Human-Robot Collaboration
---

*Mohamed El-Shamouty, Julian Titze, Sitar Kortik, Werner Kraus and Marco F. Huber*

Submitted to the IEEE 27th International Conference on Emerging Technologies and Factory Automation (ETFA).

<p align="center">
  <iframe width="900" height="506" src="https://youtu.be/YkmY9KdU_cU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>


## Abstract
<div align="justify"> In manufacturing, there is a current trend-shift from mass-production to mass-personalization enabled, among others, by the emerging field of human-robot collaboration (HRC), in which humans collaborate or work in proximity with robots. In HRC-scenarios, robots need to exert a desired behaviour that maximizes utility without sacrificing safety and responsiveness. To maximize safety and utility in static environments, state-of-the-art offline motion-planners use computationally-heavy algorithms for approximating the collision-free robot reachability and accordingly generate (sub-) optimal robot trajectories. To enable real-time responsiveness, we propose an integrated global planner to generate sub-optimal trajectories. It relies on a closed-loop reactive controller for executing the global plan while ensuring safety with practical assumptions about the environment. We evaluated GLIR in simulation. In our experiments, our global planner operates at 25Hz and the local planner at 100Hz, enabling their execution in dynamic environments. In all experiments on static scenes with static and dynamic goals, GLIR achieves 100% positive clearance from obstacles.
</div>
