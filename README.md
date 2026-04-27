# Term Project Proposal: Deep Learning

- **Student Name:** ChoHyeongmin(조형)
- **Title:** Implementation of Natural Language-to-Motor Trajectory Mapping for Humanoid Robots using LLMs

### Summary
This project implements a Physical AI system that maps natural language commands to motor trajectories for a 19-degree-of-freedom (DoF) humanoid robot. While traditional robot control relies on complex inverse kinematics, this study explores the potential of Large Language Models (LLMs), specifically the Gemini API, to translate human intent directly into physical motion. By leveraging the sequence modeling capabilities discussed in the *Deep Learning* textbook (Goodfellow et al.), the system parses linguistic input and generates corresponding joint angles in a JSON format.

In the final report, I will detail the system architecture deployed on the Jetson AGX Orin and analyze how language embeddings are mapped onto the robot's action space (Representation Learning). Furthermore, I will conduct experiments to evaluate the trade-offs between the high-level intelligence of remote APIs and the latency requirements of real-time Human-Robot Interaction (HRI). This implementation aims to demonstrate a practical application of deep learning foundations in creating intuitive, embodied AI agents.
