# Publications

## UAV Localization

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICoSR2022</div><img src='images/icosr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Deep learning based cross-view image matching for UAV geo-localization. \\
**Xubo Luo**, Yaolin Tian, Xue Wan, Jinzhong Xu, Tao Ke

- Due to the large scale and illumination difference between aerial and satellite images, it is challenging that most existing cross-view image matching algorithms fail to localize the UAV robustly and accurately. To solve the above problem, a novel UAV localization framework containing three-stage coarse-to-fine image matching is proposed.
- [Paper](https://ieeexplore.ieee.org/abstract/document/10137193) [Project](/projects/icosr2022.html)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS2024</div><img src='images/iros2024/pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

JointLoc: A Real-time Visual Localization Framework for Planetary UAVs Based on Joint Relative and Absolute Pose Estimation. (Under Review) \\
**Xubo Luo**, Xue Wan, Yixing Gao, Yaolin Tian, Wei Zhang, Leizheng Shu

- Unmanned aerial vehicles (UAVs) visual localization in planetary aims to estimate the absolute pose of the UAV in the world coordinate system through satellite maps and images captured by on-board cameras. However, since planetary scenes often lack significant landmarks and there are modal differences between satellite maps and UAV images, the accuracy and real-time performance of UAV positioning will be reduced. In order to accurately determine the position of the UAV in a planetary scene in the absence of the global navigation satellite system (GNSS), this paper proposes JointLoc, which estimates the real-time UAV position in the world coordinate system by adaptively fusing the absolute 2-degree-of-freedom (2-DoF) pose and the relative 6-degree-of-freedom (6-DoF) pose. Extensive comparative experiments were conducted on a proposed planetary UAV image cross-modal localization dataset, which contains three types of typical Martian topography generated via a simulation engine as well as real Martian UAV images from the Ingenuity helicopter. JointLoc achieved a root-mean-square error of 0.237m in the trajectories of up to 1,000m, compared to 0.594m and 0.557m for ORB-SLAM2 and ORB-SLAM3 respectively. The source code will be available at this https URL.
- [Paper](https://arxiv.org/abs/2405.07429) [Project](/projects/iros2024.html)

</div>
</div>

## Image Fusion

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVIU</div><img src='images/cviu/pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

HBANet: A hybrid boundary-aware attention network for infrared and visible image fusion. (Under Review) \\
**Xubo Luo**, Liping Wang, Jinshuo Zhang, Dongmei Niu

- Infrared and visible image fusion is an extensively investigated problem in infrared image processing, aiming to extract useful information from source images. However, the automatic fusion of these images presents a significant challenge due to the large domain difference and ambiguous boundaries. In this article, we propose a novel image fusion approach based on hybrid boundary-aware attention, termed HBANet, which models global dependencies across the image and leverages boundary-wise prior knowledge to supplement local details. Specifically, we design a novel mixed boundary-aware attention module that is capable of leveraging spatial information to the fullest extent and integrating long dependencies across different domains. To preserve the integrity of texture and structural information, we introduced a sophisticated loss function that comprises structure, intensity, and variation losses. Our method has been demonstrated to outperform state-of-the-art methods in terms of both visual and quantitative metrics, in our experiments on public datasets. Furthermore, our approach also exhibits great generalization capability, achieving satisfactory results in CT and MRI image fusion tasks.
- [Paper]() [Project]()

</div>
</div>
