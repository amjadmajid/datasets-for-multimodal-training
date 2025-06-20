# Datasets and Simulators for Training Robotic Multimodal Models


Below is a curated selection of the most-used & recent **robot-centric data sets that power generative-AI research in robotics**.  The table lists each data set’s year, scope and scale, and—crucially—the licence that governs redistribution or commercial use.  This should let you pick a corpus whose terms match your project (e.g., Apache 2.0 or CC-BY for commercial reuse vs. “research-only” agreements).

## Embodied & manipulation-focused data sets

| Dataset | Year | Task(s) | Scale | Licence |
| --- | --- | --- | --- | --- |
| <a href="https://robotics-transformer1.github.io/" target="_blank" rel="noopener noreferrer">RT-1</a> | 2022 | Multi-task real-world manipulation | ≈ 130 k episodes · 700 tasks | <a href="https://github.com/google-research/robotics_transformer/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://droid-dataset.github.io/" target="_blank" rel="noopener noreferrer">DROID</a> | 2024 | In-the-wild manipulation | 76 k trajectories · 564 scenes · 86 tasks | <a href="https://github.com/droid-dataset/droid_policy_learning/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://vimalabs.github.io/" target="_blank" rel="noopener noreferrer">VIMA</a> | 2023 | Simulated multimodal manipulation | ≈ 650 k trajectories | <a href="https://huggingface.co/datasets/VIMA/VIMA-Data" target="_blank" rel="noopener noreferrer">CC-BY 4.0</a> |
| <a href="https://sites.google.com/view/bc-z/home" target="_blank" rel="noopener noreferrer">BC-Z</a> | 2021 | Diverse manipulation | ≈ 39 k trajectories · 100 + tasks | <a href="https://www.kaggle.com/datasets/google/bc-z-robot" target="_blank" rel="noopener noreferrer">CC-BY 4.0</a> |
| <a href="https://roboturk.stanford.edu/" target="_blank" rel="noopener noreferrer">RoboTurk</a> | 2019 | Crowd-sourced manipulation demos | 2 144 demonstrations · 3 tasks | <a href="https://github.com/RoboTurk-Platform/roboturk_real_dataset/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/google-research/language-table" target="_blank" rel="noopener noreferrer">Language Table</a> | 2023 | Table-top rearrangement via language | ≈ 600 k labelled trajectories | <a href="https://github.com/google-research/language-table/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://robopen.github.io/roboset/" target="_blank" rel="noopener noreferrer">RoboSet</a> | 2023 | Household kitchen manipulation | 30 050 trajectories · 38 tasks | <a href="https://github.com/robopen/roboagent/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://functional-manipulation-benchmark.github.io/" target="_blank" rel="noopener noreferrer">FMB</a> | 2024 | Functional, long-horizon manipulation | 22 550 expert trajectories | <a href="https://functional-manipulation-benchmark.github.io/" target="_blank" rel="noopener noreferrer">CC-BY 4.0</a> |
| <a href="https://mobile-aloha.github.io/" target="_blank" rel="noopener noreferrer">Mobile ALOHA</a> | 2024 | Bimanual mobile manipulation | ≈ 50 demos / task (5 + tasks) | <a href="https://github.com/MarkFzp/mobile-aloha/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://robotics-transformer-x.github.io/" target="_blank" rel="noopener noreferrer">RT-X / Open X-Embodiment</a> | 2023 | Multi-embodiment, multi-task manipulation | ≈ 1 M+ trajectories · 160 k tasks · 22 robot types | <a href="https://github.com/google-deepmind/open_x_embodiment/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://huggingface.co/blog/lerobot-datasets" target="_blank" rel="noopener noreferrer">LeRobot Community</a> | 2025 | Community-contributed multimodal robot data (arms, mobile, driving) | 487 datasets · ≈ 10 M frames | Varied (mostly Apache 2.0) |


## Navigation & embodied-vision data sets

| Dataset | Year | Domain | Scale | Licence |
| --- | --- | --- | --- | --- |
| <a href="https://aihabitat.org/datasets/hm3d/" target="_blank" rel="noopener noreferrer">HM3D</a> | 2021 | 3-D indoor navigation | 1 000 scanned buildings | <a href="https://github.com/facebookresearch/habitat-matterport3d-dataset/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://gibsonenv.stanford.edu/" target="_blank" rel="noopener noreferrer">Gibson</a> | 2018 | Real-scan navigation | 572 scenes | <a href="https://github.com/StanfordVL/GibsonEnv/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://bringmeaspoon.org/" target="_blank" rel="noopener noreferrer">Room-to-Room (R2R)</a> | 2018 | Vision-language navigation | 22 k human instructions | Research-only (custom) |
| <a href="https://ai2thor.allenai.org/" target="_blank" rel="noopener noreferrer">AI2-THOR</a> | 2017-24 | Interactive nav + manipulation | 200 + synthetic rooms | <a href="https://github.com/allenai/ai2thor/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://ai2thor.allenai.org/robothor" target="_blank" rel="noopener noreferrer">RoboTHOR</a> | 2020 | Sim-to-real navigation | 89 apartments | <a href="https://github.com/allenai/ai2thor/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |

---

## Simulators for embodied multimodal models

| Name | Task | Scenes | Sensors | Platform | Year | Licence |
| --- | --- | --- | --- | --- | --- | --- |
| <a href="https://arxiv.org/abs/2405.14045" target="_blank" rel="noopener noreferrer">SDF-Sim</a> | Action, Navigation | – | RGB | – | 2024 | TBD — no public repo yet |
| <a href="https://arxiv.org/abs/2403.08629" target="_blank" rel="noopener noreferrer">TRUMANS</a> | Action, Navigation | 100 indoor scenes | VICON · RGB-D · IMU | A800 GPU | 2024 | <a href="https://github.com/cornellsml/truman/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/KovenYu/WonderWorld" target="_blank" rel="noopener noreferrer">WonderWorld</a> | Action, Navigation | – | – | A6000 GPU · AR/VR | 2024 | TBD — licence not yet posted |
| <a href="https://craigleili.github.io/projects/genzi/" target="_blank" rel="noopener noreferrer">GenZI</a> | Action, Navigation | – | – | A100 GPU | 2024 | TBD — code forthcoming |
| <a href="http://svl.stanford.edu/igibson/" target="_blank" rel="noopener noreferrer">iGibson 2.0</a> | Action, Navigation | 15 scenes (108 rooms) | RGB · Depth · LiDAR | GTX 1080 Ti · VR HMDs · Fetch | 2021 | <a href="https://github.com/StanfordVL/iGibson/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/facebookresearch/habitat-sim" target="_blank" rel="noopener noreferrer">Habitat-Sim</a> | Action, Navigation | – | RGB · Depth · GPS · Compass · Contact | Titan Xp · VR | 2019 | <a href="https://github.com/facebookresearch/habitat-sim/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/Genesis-Embodied-AI/Genesis" target="_blank" rel="noopener noreferrer">Genesis</a> | All | All | – | – | 2024 | <a href="https://github.com/Genesis-Embodied-AI/Genesis/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://github.com/peteanderson80/Matterport3DSimulator" target="_blank" rel="noopener noreferrer">Matterport3D Sim</a> | Navigation | 90 buildings | RGB-D · Panoramic | Titan Xp | 2017 | <a href="https://github.com/peteanderson80/Matterport3DSimulator/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://soundspaces.org/" target="_blank" rel="noopener noreferrer">SoundSpaces</a> | Navigation | 103 scenes · 102 sounds | RGB-D · Mic | – | 2020 | <a href="https://github.com/facebookresearch/soundspaces-challenge/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/facebookresearch/sound-spaces" target="_blank" rel="noopener noreferrer">SoundSpaces v2</a> | Navigation | – | RGB-D · Mic | – | 2022 | MIT (same repo) |
| <a href="https://ai2thor.allenai.org/" target="_blank" rel="noopener noreferrer">AI2-THOR</a> | Action, Navigation, Manipulation | 120 synthetic rooms | RGB · Depth · Semantic | Unity-based | 2017 | <a href="https://github.com/allenai/ai2thor/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://github.com/ARISE-Initiative/robosuite" target="_blank" rel="noopener noreferrer">RoboSuite</a> | Robotic manipulation | 25 MuJoCo tasks | RGB · Depth | GPU (MuJoCo) | 2020 | <a href="https://github.com/ARISE-Initiative/robosuite/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://gazebosim.org/libs/sim/" target="_blank" rel="noopener noreferrer">Gazebo Sim (gz-sim)</a> | Manipulation, Navigation, Multi-robot | User-defined | Any Gazebo sensor | CPU/GPU | 2023 | <a href="https://github.com/gazebosim/gz-sim/blob/gz-sim9/LICENSE" target="_blank" rel="noopener noreferrer">Apache 2.0</a> |
| <a href="https://pybullet.org/" target="_blank" rel="noopener noreferrer">PyBullet</a> | Physics, Manipulation | User-defined | OpenGL · Force/Torque | CPU/GPU | 2017 | <a href="https://github.com/bulletphysics/bullet3/blob/master/LICENSE.txt" target="_blank" rel="noopener noreferrer">zlib/libpng</a> |
| <a href="https://carla.org/" target="_blank" rel="noopener noreferrer">CARLA</a> | Autonomous driving | 20 + urban maps | RGB · LiDAR · RADAR | GPU (UE 4) | 2017 | <a href="https://github.com/carla-simulator/carla/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT</a> |
| <a href="https://github.com/threedworld-mit/tdw" target="_blank" rel="noopener noreferrer">ThreeDWorld (TDW)</a> | Multi-modal physics, Embodied AI | 1000s objects / layouts | RGB-D · Audio · Force | GPU (Unity) | 2021 | <a href="https://github.com/threedworld-mit/tdw/blob/master/LICENSE.txt" target="_blank" rel="noopener noreferrer">BSD-2-Clause</a> |
| <a href="https://developer.nvidia.com/isaac/sim" target="_blank" rel="noopener noreferrer">Isaac Sim</a> | Action, Navigation, Manipulation, Synthetic-data | Pre-built + custom USD worlds | RGB · Depth (LiDAR/Radar) · IMU · Contact | RTX-class GPU · Omniverse | 2021 | <a href="https://docs.omniverse.nvidia.com/isaacsim/latest/common/NVIDIA_Omniverse_License_Agreement.html" target="_blank" rel="noopener noreferrer">NVIDIA Omniverse EULA</a> |

### Reading the licences

* **Apache 2.0 / MIT** – permissive; redistribution (even commercial) is fine with attribution.
* **CC-BY 4.0** – also permissive but requires explicit attribution for any reuse, including derivatives.
* **Custom / research-only** – typically bars commercial use and redistribution without permission; check each EULA carefully.
