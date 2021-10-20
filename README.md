# Face Dataset

This repo aims to collect face related CV tasks datasets. Any contribution to this repo is highly welcomed. 
# Contents  
- [Action Units ](#action-units--facial-expression)  
- [Engagement Prediction](#engagement-prediction)  
- [Face Alignment](#head-pose--face-alignment)
- [Facial Expression](#action-units--facial-expression)  
- [Head Pose Estiamation](#head-pose--face-alignment)


### Action Units & Facial Expression


| Name       | Features                                                     | Links                                                        |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| SAMM       | ` 159 spontaneous micro-facial movements  `, ` 32 participants `, ` 13 different ethnicities `, ` ages between 19 and 57 `,  `17 male and 16 female` | [Homepage](https://personalpages.manchester.ac.uk/staff/adrian.davison/SAMM.html) [Paper](https://ieeexplore.ieee.org/abstract/document/7492264) |
| oulu-CASIA | `NIR&VIS`,  `  80 subjects `, ` three different illumination conditions `,  ` Label: 6 typical expressions `, `neutral to peek video`, ` Raw `, ` 65,000 images` | [Homepage](https://www.oulu.fi/cmvs/node/41316) [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0262885611000515) |
| VGAF       | `Label:Pos/Neu/Neg`, `Video level Group AFfect (VGAF) Database` | [Homepage](https://sites.google.com/view/emotiw2020)  [Paper](https://dl.acm.org/doi/10.1145/3382507.3417973) |

### Engagement Prediction
| Name   | Features                                                     | Links                                                        |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| DAiSEE | `725,000 frames or 9 hours`, `102 videos`, `75 subjects`, `in the wild`, `label: 0 to 3 engagement intensity`, `labeled by vote`, `Indian`, `EmotiW contest` | [Homepage](https://iith.ac.in/~daisee-dataset/) [Paper](https://arxiv.org/abs/1609.01885) |

### Head Pose & Face Alignment

| Name              | Features                                                     | Links                                                        |
| ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| BIWI              | `Kinect RGBD`, `24 sequences`, `6 women and 14 men`, `3D head template provided`, `calibration information provided`, `background removed`, `label: 3x3 rotation matrix, head location` | [Download](http://data.vision.ee.ethz.ch/cvl/gfanelli/kinect_head_pose_db.tgz) [Paper](https://link.springer.com/content/pdf/10.1007/s11263-012-0549-0.pdf) |
| AFLW2000-3D       | `label: 68-point 3D facial landmarks`, `2000 images`, `in the wild`, `tfds available` | [Homepage](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/main.htm) [Paper]() |
| lidf (BCMI, SJTU) | `Kinect One Depth & Infrared`, `918 indoor images`, `17 subjects * 9 poses * 6 expressions`,  `15 2D landmarks `, `aligned`, `Chinese` | [Homepage](https://bcmi.sjtu.edu.cn/resource.html)           |

