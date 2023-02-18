# GANet

# GANet: Goal Area Network for Motion Forecasting

This repo is for our ICRA 2023 paper `"GANet: Goal Area Network for Motion Forecasting"` for motion prediction in autonomous driving scenarios, and its variant also won the Motion Forecasting Challenge of Argoverse Challenge 2022. 


**Authors**: Mingkun Wang, Xinge Zhu, Changqian Yu, Wei Li, Yuexin Ma, Ruochun Jin, Xiaoguang Ren, Dongchun Ren, Mingxu Wang and Wenjing Yang∗

[[arXiv]](https://arxiv.org/abs/2209.09723)

## Abstract
Predicting the future motion of road participants is crucial for autonomous driving but is extremely challenging due to staggering motion uncertainty.
Recently, most motion forecasting methods resort to the goal-based strategy, i.e., predicting endpoints of motion trajectories as conditions to regress the entire trajectories, so that the search space of solution can be reduced.
However, accurate goal coordinates are hard to predict and evaluate.
In addition, the point representation of the destination limits the utilization of a rich road context, leading to inaccurate prediction results in many cases. Goal area, i.e., the possible destination area, rather than goal coordinate, could provide a more soft constraint for searching potential trajectories by involving more tolerance and guidance.  
In view of this, we propose a new goal area-based framework, named Goal Area Network (GANet), for motion forecasting, which models goal areas as preconditions for trajectory prediction, performing more robustly and accurately.
Specifically, we propose a GoICrop (Goal Area of Interest) operator to effectively extract semantic lane features in goal areas and model actors' future interactions, which benefits a lot for future trajectory estimations.
GANet ranks the \textbf{1st} on the leaderboard of Argoverse Challenge among all public literature (till the paper submission).
Code will be available at https://github.com/kingwmk/GANet.

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
