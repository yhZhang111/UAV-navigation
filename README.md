# UAV navigation in view changing and occlusion, method and dataset

ReMemGeo studies language-guided UAV navigation when the view changes or a target becomes occluded. The tasks require precise flight control and the ability to use earlier observations during multistage maneuvers and return flights.

**Method.** ReMemGeo-Nav combines visual and geometric features in fixed-size recurrent memory to predict continuous flight actions.

**Dataset.** ReMemGeo-Bench covers six task categories with 3,190 training trajectories and 244 test trajectories. It pairs depth and continuous action supervision with task-specific evaluation.

- [Paper](main.pdf)
- [Supplementary video](rememgeo_full_text_cover_updated_v2.mp4)
