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
network.
