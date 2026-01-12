# UDH2026_robotics
Open repository for Advanced Sensing, Robotics and IoT Challenge for the Aramco Upstream Digital Hackathon 2026

## Aramco Digital Hackathon – Robotics Challenge: Autonomous AGV for Desert Seismic Exploration
The Robotics Challenge invites participants to design, simulate, and program an autonomous ground vehicle (AGV) capable of performing a realistic seismic exploration mission in a desert environment. Hosted as part of the KAUST Winter Enrichment Program, this two‑week hackathon blends robotics, autonomy, simulation engineering, and geophysical field operations into a single mission‑driven experience.

## Challenge Overview
Teams will work in NVIDIA Isaac Sim to develop a high‑fidelity simulation of a desert seismic operation. To ensure realism and consistency across teams, the organizers will provide a pre‑generated 3D desert terrain surface, representing dunes, rough topography, and natural obstacles.
Terrain download link:  https://drive.google.com/file/d/1HGYjwDokWN6SuNhYVApJAxalCgsNt4VX/view?usp=share_link

Participants will import this terrain into Isaac Sim and integrate an AGV capable of navigating the environment. The AGV must autonomously visit all assigned surveying points in the most efficient sequence and shortest possible time while:

* Handling uneven and unpredictable terrain
* Avoiding collisions with obstacles
* Maintaining stable and safe navigation
* Optimizing the mission path for speed and coverage

This challenge mirrors real‑world constraints in autonomous seismic acquisition, where efficiency, safety, and terrain adaptability are essential.

## Technical Requirements
Teams will use:
* Isaac Sim for world‑building, robot dynamics, and sensor simulation
* AGV autonomy stack for mapping, localization, path planning, and obstacle avoidance
* Mission‑level logic for waypoint sequencing and optimal route planning

To support development, participants may use NVIDIA’s official learning resources:
* Isaac Sim Documentation: https://docs.nvidia.com/isaacsim
* Isaac Sim Tutorials: https://developer.nvidia.com/isaac-sim/tutorials
* Omniverse Learning: https://docs.omniverse.nvidia.com (docs.omniverse.nvidia.com in Bing)
* Isaac SDK Examples: https://developer.nvidia.com/isaac-sdk

## Hackathon Milestones
### Milestone 1 — End of Week 1
* Import the organizer‑provided 3D desert terrain into Isaac Sim
* Add and configure the AGV model (sensors, physics, collision geometry)
* Demonstrate basic teleoperation or scripted movement

### Milestone 2 — Day 10
* Implement autonomous navigation, including:
  - Terrain‑aware path planning
  - Obstacle detection and avoidance
  - Waypoint following

Demonstrate partial autonomous traversal of the environment

### Milestone 3 — Final Day
* Execute the full seismic exploration mission:
  - Visit all survey points in optimal order
  - Complete the mission in minimal time
  - Avoid all collisions

* Deliver a final presentation summarizing:
  - Environment integration  
  - Autonomy architecture
  - Mission performance
  - Lessons learned and real‑world applicability
