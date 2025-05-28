# Datasets for Robotic Multimodal Model Training


Below is a curated selection of the most-used & recent **robot-centric data sets that power generative-AI research in robotics**.  The table lists each data set’s year, scope and scale, and—crucially—the licence that governs redistribution or commercial use.  This should let you pick a corpus whose terms match your project (e.g., Apache 2.0 or CC-BY for commercial reuse vs. “research-only” agreements).

## Embodied & manipulation-focused data sets

| Dataset                                                             | Year | Task(s)                               | Scale                                                                  | Licence                                                       |
| ------------------------------------------------------------------- | ---- | ------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------- |
| [RT-1](https://robotics-transformer1.github.io/)                    | 2022 | Multi-task real-world manipulation    | ≈ 130 k episodes, 700 tasks ([robotics-transformer1.github.io][1])     | Apache 2.0 ([GitHub][2])                                      |
| [DROID](https://droid-dataset.github.io/)                           | 2024 | In-the-wild manipulation              | 76 k trajectories, 564 scenes, 86 tasks ([droid-dataset.github.io][3]) | MIT ([GitHub][4])                                             |
| [VIMA](https://vimalabs.github.io/)                                 | 2023 | Simulated multimodal manipulation     | ≈ 650 k trajectories ([Hugging Face][5])                               | CC-BY 4.0 ([Hugging Face][5])                                 |
| [BC-Z](https://sites.google.com/view/bc-z/home)                     | 2021 | Diverse manipulation                  | ≈ 39 k trajectories, 100 + tasks                                       | CC-BY 4.0 ([Kaggle][6])                                       |
| [RoboTurk](https://roboturk.stanford.edu/)                          | 2019 | Crowd-sourced manipulation demos      | 2 144 demonstrations (3 tasks) ([roboturk.stanford.edu][7])            | MIT ([GitHub][8])                                             |
| [Language Table](https://github.com/google-research/language-table) | 2023 | Table-top rearrangement via language  | ≈ 600 k labelled trajectories                                          | Apache 2.0 ([GitHub][9])                                      |
| [RoboSet](https://robopen.github.io/roboset/)                       | 2023 | Household kitchen manipulation        | 30 050 trajectories, 38 tasks                                          | MIT ([GitHub][10])                                            |
| [FMB](https://functional-manipulation-benchmark.github.io/)         | 2024 | Functional, long-horizon manipulation | 22 550 expert trajectories                                             | CC-BY 4.0 ([functional-manipulation-benchmark.github.io][11]) |
| [Mobile ALOHA](https://mobile-aloha.github.io/)                     | 2024 | Bimanual mobile manipulation          | ≈ 50 demonstrations / task (5 + tasks)                                 | MIT ([GitHub][12])                                            |

## Navigation & embodied-vision data sets

| Dataset                                          | Year    | Domain                                    | Scale                   | Licence                                                                     |
| ------------------------------------------------ | ------- | ----------------------------------------- | ----------------------- | --------------------------------------------------------------------------- |
| [HM3D](https://aihabitat.org/datasets/hm3d/)     | 2021    | 3-D indoor navigation                     | 1 000 scanned buildings | MIT ([GitHub][13])                                                          |
| [Gibson](https://gibsonenv.stanford.edu/)        | 2018    | Real-scan navigation                      | 572 scenes              | MIT code / custom research-only data ([GitHub][14], [svl.stanford.edu][15]) |
| [Room-to-Room (R2R)](https://bringmeaspoon.org/) | 2018    | Vision-language navigation                | 22 k human instructions | Custom research-only                                                        |
| [AI2-THOR](https://ai2thor.allenai.org/)         | 2017-24 | Interactive scenes for nav + manipulation | 200 + synthetic rooms   | Apache 2.0 ([GitHub][16])                                                   |
| [RoboTHOR](https://ai2thor.allenai.org/robothor) | 2020    | Sim-to-real navigation                    | 89 apartments           | Apache 2.0 ([GitHub][17])                                                   |

---

### Reading the licences

* **Apache 2.0 / MIT** – permissive; redistribution (even commercial) is fine with attribution.
* **CC-BY 4.0** – also permissive but requires explicit attribution for any reuse, including derivatives.
* **Custom / research-only** – typically bars commercial use and redistribution without permission; check each EULA carefully.



[1]: https://robotics-transformer1.github.io/ "RT-1: Robotics Transformer"
[2]: https://github.com/hyy02/RT-1?utm_source=chatgpt.com "hyy02/RT-1 - GitHub"
[3]: https://droid-dataset.github.io/ "DROID: A Large-Scale In-the-Wild Robot Manipulation Dataset"
[4]: https://github.com/droid-dataset/droid_policy_learning/blob/master/LICENSE?utm_source=chatgpt.com "MIT license - droid-dataset/droid_policy_learning - GitHub"
[5]: https://huggingface.co/datasets/VIMA/VIMA-Data?utm_source=chatgpt.com "VIMA/VIMA-Data · Datasets at Hugging Face"
[6]: https://www.kaggle.com/datasets/google/bc-z-robot?utm_source=chatgpt.com "bc z robot - Kaggle"
[7]: https://roboturk.stanford.edu/dataset_real.html?utm_source=chatgpt.com "The RoboTurk Real Robot Dataset"
[8]: https://github.com/RoboTurk-Platform/roboturk_real_dataset/blob/master/LICENSE?utm_source=chatgpt.com "MIT license - RoboTurk-Platform/roboturk_real_dataset - GitHub"
[9]: https://github.com/google-research/language-table?utm_source=chatgpt.com "google-research/language-table - GitHub"
[10]: https://github.com/robopen/roboagent?utm_source=chatgpt.com "robopen/roboagent: Repository to train and evaluate ... - GitHub"
[11]: https://functional-manipulation-benchmark.github.io/?utm_source=chatgpt.com "FMB: A Functional Manipulation Benchmark for Generalizable ..."
[12]: https://github.com/MarkFzp/mobile-aloha/blob/main/LICENSE?utm_source=chatgpt.com "MIT license - MarkFzp/mobile-aloha - GitHub"
[13]: https://github.com/facebookresearch/habitat-matterport3d-dataset?utm_source=chatgpt.com "facebookresearch/habitat-matterport3d-dataset - GitHub"
[14]: https://github.com/StanfordVL/GibsonEnv/blob/master/LICENSE?utm_source=chatgpt.com "GibsonEnv/LICENSE at master - GitHub"
[15]: https://svl.stanford.edu/gibson2/assets/GDS_agreement.pdf?utm_source=chatgpt.com "[PDF] Agreement GDS 06-04-18.pages"
[16]: https://github.com/allenai/ai2thor/blob/main/LICENSE?utm_source=chatgpt.com "License - allenai/ai2thor - GitHub"




| Name | Task | Scenes | Sensors | Platform | Year |
| --- | --- | --- | --- | --- | --- |
| [SDF-Sim](https://arxiv.org/abs/2405.14045) | Action, Navigation | – | RGB | – | 2024 |
| [TRUMANS](https://arxiv.org/abs/2403.08629) | Action, Navigation | 100 interior scenes (dining room, living room, bedroom, kitchen, etc.) | VICON, RGB-D, IMU | A800 GPU | 2024 |
| [WonderWorld](https://github.com/KovenYu/WonderWorld)  | Action, Navigation | – | – | A6000 GPU, AR, VR | 2024 |
| [GenZI](https://craigleili.github.io/projects/genzi/)  | Action, Navigation | – | – | A100 GPU | 2024 |
| [iGibson2.0](http://svl.stanford.edu/igibson/) | Action, Navigation | 15 complete interactive scenes (108 rooms: kitchen, bathroom, living room, etc.) | RGB, Depth, LiDAR | Intel 5930k CPU, Nvidia GTX 1080 Ti, HTC Vive (Pro Eye), Oculus Rift S, Quest, Fetch robot, Humanoid robot | 2021 |
| [Habitat-Sim](https://github.com/facebookresearch/habitat-sim)  | Action, Navigation | – | RGB, Depth, GPS, Compass, Contact | Intel Xeon E5-2690 v4 CPU, Nvidia Titan Xp GPU, VR, Robot | 2019 |
| [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) | all | all | – | – | 2024 |
| [Matterport3D Simulator](https://github.com/peteanderson80/Matterport3DSimulator)  | Navigation | 90 architectural-scale scenes (homes, offices, churches) | RGB-D, Panoramic | Intel Xeon E5-2690 v4 CPU, Nvidia Titan Xp GPU, Robot | 2017 |
| [SoundSpaces](https://soundspaces.org/)  | Navigation | 103 scenes, 102 copyright-free sounds | RGB-D, Microphone | – | 2020 |
| [SoundSpaces v2](https://github.com/facebookresearch/sound-spaces)  | Navigation | – | RGB-D, Microphone | – | 2022 |
