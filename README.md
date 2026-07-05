# Quadrotor Trajectory Tracking with Artificial Potential Fields

**A full 6-DOF quadrotor model with PD control tracks a dynamic target through APF-planned, obstacle-avoiding trajectories.**

▶ [**Watch the demo video**](./APF.mp4) · 📄 [**Project report (PDF)**](./Report.pdf) · 🎞 [**Slides (PDF)**](./PPT.pdf)

## Overview
This project closes the loop from planning to control: an **artificial potential field (APF)** generates a trajectory that follows a dynamic target while avoiding static obstacles, and a **6-DOF quadrotor model with a PD controller** tracks that trajectory in simulation.

## Method
- APF planner: attractive potential toward the moving target, repulsive potentials around static obstacles.
- Full 6-DOF quadrotor dynamics model with PD trajectory-tracking control.

## Context
Graduate research project, Robotics & Autonomous Systems, **IISc Bengaluru** (Aug–Dec 2021).
