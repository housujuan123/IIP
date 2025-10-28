# Intra-Inter Perspective: an Efficient Network for Logo Detection

## IIP(Intra-Inter Perspective)
<img width="1406" height="264" alt="image" src="https://github.com/user-attachments/assets/fd138235-ed1b-4089-ab91-425210971102" />
<p align="center">Fig. 1: Intra-Inter Class Enhancement (IICE).</p>
## The Description of IIP
Logo detection is crucial in various fields, including
advertising marketing, security monitoring, manufacturing and
brand protection. However, accurately detecting logos in complex environments presents significant challenges due to issues
such as widespread occlusion, rotation, and scale variations. To
tackle these issues, we developed an efficient network for logo
detection to enhance logo saliency in complex environments. Our
approach employs intra-inter class enforcement, which refines
the contrast between foreground and background by utilizing
image details and a learnable external guidance vector to generate
more effective feature proposals. Additionally, we decouple the
classification and regression tasks to minimize interference. In
the regression branch, we strategically adjust the weighting of
the Region of Interest (ROI) by focusing on both intra-ROI and
inter-ROI relationships, effectively emphasizing the regression
target. Extensive experiments conducted on three widely used
logo datasets demonstrate the effectiveness of our proposed
network.

## Intra-Inter Class Enhancement (IICE)
The Intra-Inter Class Enhancement (IICE) module  details how the combination of external and internal information achieves foreground-background separation.
<img width="1115" height="605" alt="image" src="https://github.com/user-attachments/assets/683c1c61-ed9e-4d5e-bd99-9204b6ff1eeb" />
<p align="center">Fig. 2: Intra-Inter Class Enhancement (IICE).</p>

## Intra-Inter ROI Weighted Decoupling (IIWD)
The Intra-Inter ROI Weighted Decoupling (IIWD) module separates the classification and regression tasks.This module leverages inter-ROI and intra-ROI relationships to weight ROI features, leading to a more robust and accurate regression.
<img width="1243" height="613" alt="image" src="https://github.com/user-attachments/assets/6949dc20-164a-4e89-bfd5-ae4f5f2d2a51" />
<p align="center">Fig. 3: Intra-Inter ROI Weighted Decoupling (IIWD).</p>

## Visualization Comparison
The visual comparison of IIP with other models is shown in the figure.
<img width="1340" height="827" alt="image" src="https://github.com/user-attachments/assets/9ad17c39-8e10-4184-84a9-9f6336c8fdd2" />
<p align="center">Fig. 4: Visualization of the proposed model. The category label and classification score are assigned to each bounding box.</p>

## Installation
We recommend that users follow best practices to install MMDetection.

## Getting Started

To train a model with "train.py", use<br>
```
python tools/train.py
```

To evaluate a model's performance, use<br>
```
python tools/test.py
```
