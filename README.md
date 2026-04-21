s# Laboratory Demonstration of LiDAR-Based Docking and Refueling of a Spinning Spacecraft

This repository is a derivative of the [SPOT](https://github.com/Carleton-SRL/SPOT) project. Specifically, it is a snapshot of the project from the Capstone 2024-2025 academic year.

## Abstract
This research addresses the need to develop in-space refueling technologies by experimentally demonstrating an autonomous docking maneuver and fluid transfer operation between a servicer and uncooperative spinning client spacecraft. A novel computer vision algorithm estimates the relative pose of the client spacecraft in real-time using an on-board Light Detection and Ranging camera. An unscented Kalman filter refines the pose data before a model predictive controller generates a collision-free docking trajectory for the servicer spacecraft to follow. A custom-designed docking and refueling mechanism for fluid transfer performs magnetic soft docking and robotic arm capture to seal a probe-and-drogue connection and transfer fluid from the servicer to the client spacecraft. Planar experimental validation is conducted at Carleton University's Spacecraft Proximity Operations Testbed, demonstrating a complete autonomous docking and refueling operation.

---

## Citation

If you use this software for any research, please cite:

```bibtex
@inproceedings{peters2026lidar,
  author    = {Jeremy Peters, Dominika Folta, Thomas King, Brianna Hines, Brian Koren, Daan Singh, Kristian Delaney, Alexander Crain, and Steve Ulrich},
  title     = {Experimental Demonstration of LiDAR-Based Docking and Refueling of a Spinning Spacecraft},
  booktitle = {36th AIAA/AAS Space Flight Mechanics Meeting},
  address   = {Orlando, FL},
  month     = jan,
  year      = {2026},
  note      = {AIAA/AAS SFM 2026}
}
```
