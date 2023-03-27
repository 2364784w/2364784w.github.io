---
layout: post
title: 2D Kinetic Theory of Gases Model
---

A 2D Kinetic Theory of Gases Model was developed as an approximation of the kinetic theory of gases model. A simulation involving 75 particles, with box width 75, initial particle energy 10, and particle radius 2 was run for 200 steps. The resulting dynamics and speed distribution of this model are visualised below:

<img src="/2D_Gas_Joint_Animation_Updated.gif" alt="GIF of 2D Gas Visualisation and Velocity Distribution of particles"   width = '100%'  height = 'auto'>

(LHS) Animation visualising movement of particles within 2D Kinetic Theory of Gases Model. Particles have colour based on their speed. (RHS) Parallel visualisation of velocity distribution of particles synchronised to the visualisation in the LHS. Depicts relaxation from initially equal velocity of all agents to a Maxwell-Boltzmann distribution, indicated by the distribution in orange. Note that the MB distribution was fitted to an averaged final velocity distribution.

#### Understanding 2D Collision dynamics

The 2D collision dynamics of this model are explained in the below diagram. The key aspect being rotating the frame of reference to separate the independent components of the velocities of the particles from the components involved in the collision. For further details, consult the thesis:

<img src="/Elastic_Collision_Explanation.png" alt="Diagram explaining the calculation of 2D elastic collision dynamics">
