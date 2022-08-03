# GIAOTracker
**GIAOTracker: A comprehensive framework for MCMOT with global information and optimizing strategies in VisDrone 2021**

## Important

Hi, considering someone emails me to ask about the codes and details of GIAOTracker, I create this repo.
I'm sorry but we don't plan to release the codes of GIAOTracker. However, if you have some questions about it, you can submit issues in this repo or [StrongSORT](https://github.com/dyhBUPT/StrongSORT).
Best wishes.

## Abstract

In recent years, algorithms for multiple object tracking tasks have benefited from great progresses in deep models and video quality. However, in challenging scenarios like drone videos, they still suffer from problems, such as small objects, camera movements and view changes. In this paper, we propose a new multiple object tracker, which employs Global Information And some Optimizing strategies, named GIAOTracker. It consists of three stages, i.e., online tracking, global link and post-processing. Given detections in every frame, the first stage generates reliable tracklets using information of camera motion, object motion and object appearance. Then they are associated into trajectories by exploiting global clues and refined through four post-processing methods. With the effectiveness of the three stages, GIAOTracker achieves state-of-the-art performance on the VisDrone MOT dataset and wins the 2nd place in the VisDrone2021 MOT Challenge.

## Methods

![GIAOTracker_Framework](https://user-images.githubusercontent.com/99722489/182517178-7207278e-51ce-4ed5-8480-7fea0debbf8d.jpg)

![online](https://user-images.githubusercontent.com/99722489/182517321-71f04435-3a95-40d5-a69e-aaf7d9710b91.jpg)

![GIModel](https://user-images.githubusercontent.com/99722489/182517458-ef8d6534-9431-4605-82c6-cecc84d4d2b9.png)

![NSAKalman](https://user-images.githubusercontent.com/99722489/182517555-c3451965-59df-449e-b149-63a8671098e9.jpg)


## Citation

```
@InProceedings{Du_2021_ICCV,
    author    = {Du, Yunhao and Wan, Junfeng and Zhao, Yanyun and Zhang, Binyu and Tong, Zhihang and Dong, Junhao},
    title     = {GIAOTracker: A Comprehensive Framework for MCMOT With Global Information and Optimizing Strategies in VisDrone 2021},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops},
    month     = {October},
    year      = {2021},
    pages     = {2809-2819}
}
```
