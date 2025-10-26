# Intra-Inter Perspective: an Efficient Network for Logo Detection

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
network.Fig. 1 provides an overview of the comprehensive framework of the proposed network.
<img width="1406" height="264" alt="image" src="https://github.com/user-attachments/assets/fd138235-ed1b-4089-ab91-425210971102" />
We further conducted a visual analysis against several representative methods, including FSAF [41], GFL [42], LiteYOLO [46], TOOD [43], YOLOv10 [45], YOLOv12 [51], and the
Baseline [17], as illustrated in Fig. 2.
<img width="1276" height="461" alt="image" src="https://github.com/user-attachments/assets/9d54d683-7417-48a8-9c1c-cd8ede35d3f1" />

# Getting Started

To train a model with "train.py", use
python tools/train.py

To evaluate a model's performance, use
python tools/test.py
