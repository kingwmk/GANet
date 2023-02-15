# GANet

# GANet: Goal Area Network for Motion Forecasting

This repo is for our ICRA 2023 paper `"GANet: Goal Area Network for Motion Forecasting"` for motion prediction in autonomous driving scenarios, and its variant also won the Motion Forecasting Challenge of Argoverse Challenge 2022. 


**Authors**: Mingkun Wang, Xinge Zhu, Changqian Yu, Wei Li, Yuexin Ma, Ruochun Jin, Xiaoguang Ren, Dongchun Ren, Mingxu Wang and Wenjing Yang∗

[[arXiv]](https://arxiv.org/abs/2209.09723)

## Abstract
Predicting multimodal future behavior of traffic participants is essential for robotic vehicles to make safe decisions. Existing works explore to directly predict future trajectories based on latent features or utilize dense goal candidates to identify agent's destinations, where the former strategy converges slowly since all motion modes are derived from the same feature while the latter strategy has efficiency issue since its performance highly relies on the density of goal candidates. In this paper, we propose the Motion TRansformer (MTR) framework that models motion prediction as the joint optimization of global intention localization and local movement refinement. Instead of using goal candidates, MTR incorporates spatial intention priors by adopting a small set of learnable motion query pairs. Each motion query pair takes charge of trajectory prediction and refinement for a specific motion mode, which stabilizes the training process and facilitates better multimodal predictions. Experiments show that MTR achieves state-of-the-art performance on both the marginal and joint motion prediction challenges, ranking $1^{st}$ on the leaderbaords of Waymo Open Motion Dataset.

## Code 
Code will be released soon. 

## Citation
If you find this work useful in your research, please consider cite:
```
@article{wang2022ganet,
  title={Ganet: Goal area network for motion forecasting},
  author={Wang, Mingkun and Zhu, Xinge and Yu, Changqian and Li, Wei and Ma, Yuexin and Jin, Ruochun and Ren, Xiaoguang and Ren, Dongchun and Wang, Mingxu and Yang, Wenjing},
  journal={IEEE International Conference on Robotics and Automation (ICRA)},
  year={2023}
}

```
Please also consider cite:
```
@inproceedings{liang2020learning,
  title={Learning lane graph representations for motion forecasting},
  author={Liang, Ming and Yang, Bin and Hu, Rui and Chen, Yun and Liao, Renjie and Feng, Song and Urtasun, Raquel},
  booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part II 16},
  pages={541--556},
  year={2020},
  organization={Springer}
}
```
