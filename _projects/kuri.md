---
layout: page
title: Brown HCRI
description: Implemented a our group's previous paper on a real-world agent (Kuri).
img: assets/img/kuri.jpg
importance: 3
category: Research
---
Keywords: reinforcement learning, curriculum learning, natural language processing, ROS, planning, control.

From Jun 2019 - September 2020, I researched under the supervision 
of Professor [Micahel Littman](https://www.littmania.com/) at Brown 
[Human-Centered Robotics Initiative](https://hcri.brown.edu/) and implemented our research group's paper 
[Teaching a Robot Tasks of Arbitrary Complexity via Human Feedback](https://dl.acm.org/doi/abs/10.1145/3319502.3374824)
on a real-world robotic agent, [Kuri](https://www.heykuri.com/explore-kuri/). 
Our agent can learn tasks of arbitrary complexity via natural language feedback only:
```
This paper addresses the problem of training a robot to carry out temporal tasks of arbitrary 
complexity via evaluative human feedback that can be inaccurate. A key idea explored in our 
work is a kind of curriculum learning---training the robot to master simple tasks and then 
building up to more complex tasks. We show how a training procedure, using knowledge of the 
formal task representation, can decompose and train any task efficiently in the size of its 
representation. We further provide a set of experiments that support the claim that non-expert 
human trainers can decompose tasks in a way that is consistent with our theoretical results, 
with more than half of participants successfully training all of our experimental missions. 
We compared our algorithm with existing approaches and our experimental results suggest that 
our method outperforms alternatives, especially when feedback contains mistakes.
```
We did a lot of hacking with ROS, Kuri's sensor/actuator hardware, and ran initial experiments. 
The experiments, which required human subjects, were interrupted by COVID-19 and 
the work remained unpublished.

Experiment setup:  

<img src="https://yxie20.github.io/assets/img/kuri_lab.png" width="300">

Kuri's world (SLAM):

<img src="https://yxie20.github.io/assets/img/kuri_map.jpg" width="300">
