---
title: BIRD
redirect_from: /Research/BIRD/
permalink: /research/bird/
---
As part of the *Provably-Stable Vision-Based Control of High-Speed Flight through Forests and Urban Environments* ONR MURI grant, the goal of the BIRD project is to achieve robust autonomous flight through dense, cluttered environments like forests.
{: .text-justify}

My work on the project includes:

- Improve trajectory selection of the receding horizon planner by introducing a notion of hysteresis into the planner. The planner takes into account the past trajectories it has selected so as not to cause sudden deviations in its heading directions, and also follow the desired goal heading.
- Associate failures of the perception system with recovery maneuvers most likely to recover from those failures. Perception failures might be cause by a wide variety of factors - over exposure, strong shadows, large rotations etc. We learn from experience to execute simple recovery maneuvers that help mitigate these failures. The first page of the paper submitted to ICRA 2017 can be found <a href="/docs/ICRA_page_1.pdf" target="_blank">here</a>.
- I also did some work on using reinforcement learning to blend different robot behaviours - *go-to-goal* and *avoid-obstacles* - in simulation. The first page of the paper submitted to ICAPS 2017 can be found <a href="/docs/ICAPS_page_1.pdf" target="_blank">here</a>. As an extension, I want to see if the unified learned policy is transferrable to new domains.
- Going forward, part of my research is focused on transfer learning and domain adaptation. I want to answer the question of how well we can learn policies on cheaper robots in simple environments, and adapt them for more expensive platforms operating in challenging environments. I will also be working on a contextual multi-armed bandit formulation of the my ICRA paper work on learning failure recovery maneuvers.
{: .text-justify}

You can watch a video of the quadrotor in action below.
<iframe height="200" src="https://www.youtube.com/embed/OHvjQklxypU" frameborder="0" allowfullscreen></iframe>