# Bolt
quadruped locomotion using Reinforcement learning 

I developed a robotic dog project using reinforcement learning to teach the robot to walk autonomously. The project leverages PyBullet for simulation and the Proximal Policy Optimization (PPO) algorithm from the Stable Baselines library. The initial focus was on optimizing the robot's movements by designing a reward function centered around energy efficiency.

Throughout the project, I experimented with both position control and torque control to find the most effective approach for improving the robot's learning process. Additionally, I refined the observation space by incorporating key factors such as joint positions, velocities, and base orientation, which allowed the robot to better interpret its environment and respond accordingly.

To improve stability, I adjusted the joint limits, ensuring that the robot could stand up after falling. Monitoring the training progress was essential, so I visualized various metrics such as average reward, KL divergence, and explained variance to assess the model’s performance.

Through continuous tuning of the reward function and action limits, I successfully trained the robotic dog to achieve stable walking behavior, showing significant improvement in its movement and control.
