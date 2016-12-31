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
- Going forward, my research is focused on transfer learning and domain adaptation. I am looking to answer the question of how well we can learn policies on cheaper robots in simple environments, and adapt them for more expensive platforms operating in challenging environments.
{: .text-justify}

You can watch a video of the quadrotor in action below.
<iframe height="200" src="https://www.youtube.com/embed/OHvjQklxypU" frameborder="0" allowfullscreen></iframe>