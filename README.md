# CrossTraj Trajectory Dataset

**CrossTraj** is a high-resolution urban trajectory dataset collected at a midblock crosswalk in the City of Milwaukee, Wisconsin. The dataset was extracted from two distinct one-hour video recordings obtained
during winter and summer, capturing seasonal and traffic dynamics. Data was collected using synchronized panoramic roadside cameras covering approximately 200 meters of road, enabling the extraction of extended trajectories rather than short-duration motion clips.

This dataset is designed to support benchmarking in computer vision and behavior modeling tasks such as:

- Object detection
- Multi-object tracking
- Trajectory prediction
- Pedestrian-vehicle interaction analysis

Dataset available at: [CrossTraj-DataSet](https://panthers-my.sharepoint.com/:f:/g/personal/muhamm72_uwm_edu/EtMlMxW-TLtGomVDfiTQBL4BVgBp_GGgCOhUZzYqztvWFA?e=sPi3LP)
---
If you have questions, you can contact the ACEMS lab at the University of Wisconsin-Milwaukee at tomshi@uwm.edu (Prof. Tom Shi) and muhamm72@uwm.edu (Muhammad Fahad).
## Contents

The dataset contains the following folders:

- **Summer Dataset**  
  Two preprocessed videos recorded under summer conditions.

- **Winter Dataset**  
  Two preprocessed videos recorded under winter conditions.

- **Training Dataset**  
  Includes raw videos and annotated datasets prepared for model training and evaluation.

---

## Citation

If you use this dataset in your work, please cite the corresponding papers once it is officially published.

```bibtex
@article{
@conference{fahad_2025_crosstraj,
  author    = {Muhammad Fahad, Anisha Tasnim, Tianyang Xiong, Agam Damaraju, Tian Zhao, Xiao Qin, Xiaowei Shi*},
  title     = {A Trajectory Dataset of Pedestrian–Vehicle Interactions at Crosswalks via Deep Learning and Roadside Cameras},
  year      = {2025},
  publisher = {Transportation Research Board (TRB) 103rd Annual Meeting, Submitted for Review}
}

@conference{fahad_2025_framework,
  author    = {Muhammad Fahad, Anisha Tasnim, Tianyang Xiong, Agam Damaraju, Tian Zhao, Xiao Qin, Xiaowei Shi*},
  title     = {A Comprehensive Evaluation Framework for Roadside Perception Systems},
  year      = {2025},
  publisher = {Transportation Research Board (TRB) 103rd Annual Meeting, Submitted for Review}
}
