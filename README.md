# Intra-Inter Perspective: an Efficient Network for Logo Detection

## IIP(Intra-Inter Perspective)
<img width="1406" height="264" alt="image" src="https://github.com/user-attachments/assets/fd138235-ed1b-4089-ab91-425210971102" />

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

## Visualization Comparison
The visual comparison of IIP with other models is shown in the figure.
<img width="1276" height="461" alt="image" src="https://github.com/user-attachments/assets/9d54d683-7417-48a8-9c1c-cd8ede35d3f1" />

## Getting Started

To train a model with "train.py", use<br>
```
python tools/train.py
```

To evaluate a model's performance, use<br>
```
python tools/test.py
```
