# Notices

- Motions: H2 Dances (https://huggingface.co/datasets/Kyry10/h2-dances), derived from the AIST Dance Video Database / AIST++.
  Required citation: Tsuchida et al., AIST Dance Video Database, ISMIR 2019. Commercial use: AIST Dance DB Terms of Use.
  `motions/*.bin` are the same trajectories resampled to 30 fps (float32, T x 38 qpos) for the browser.
- Robot model: Unitree H2 MuJoCo model from unitreerobotics/unitree_mujoco (BSD-3-Clause). Meshes are decimated for the web (`robot.bin`).
- three.js (MIT), loaded from the jsDelivr CDN.
