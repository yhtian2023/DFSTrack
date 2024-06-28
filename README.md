# DFSTrack
Human pose tracking is a challenging task that involves estimating the human pose and tracking it across multiple frames in a video sequence. In recent years, deep learning-based methods have made significant progress in this field, achieving state-of-the-art performance. However, due to complex background and occlusion among people missed detection and incorrect association matching are still the challenging problems. To address these issues, we adopt a top-down framework to perform human pose tracking in the paper.

![image](https://github.com/yhtian2023/DFSTrack/blob/main/img-folder/dfstrack.jpg)<br />

Our main contributions are summarized as follows:
* We propose a **HDP module** to recover missed human targets from the detector in the detection stage. And we propose a **DFSTrack** to handle incorrect association matches among human poses across frames.
* In order to enable the DFSTrack to capture both temporal and spatial feature information of human poses, we propose a **RGCN block** and the **DST Transformer**.
* DFSTrack achieves good performance on the human pose tracking datasets. Our method achieves a MOTA score of 69.0. Compared with LightTrack [​14​] and CorrTrack [​17​], which also use Siamese network for human tracking, the MOTA scores of our method are improved by 4.1 and 0.2, respectively.
  
[paper](https://doi.org/10.1016/j.imavis.2024.105117)

# Visualization
![image](https://github.com/yhtian2023/DFSTrack/blob/main/img-folder/dfstrack.jpg)<br />
# Acknowledgements
Great thanks for these papers and their open-source codes：[HRNet](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch), [DarkPose](https://github.com/ilovepose/DarkPose)
