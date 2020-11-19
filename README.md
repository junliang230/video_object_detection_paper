# video object detection paper
record some video object detection papers and dataset (视频目标检测论文整理)
### some notes about papers:
* [[视频目标检测(video object detection)简单综述](https://blog.csdn.net/breeze_blows/article/details/105323491)] 
* [[视频目标检测论文](https://blog.csdn.net/breeze_blows/category_9757142.html)]

<br>

#### note: If the image does not display, please check [[link](https://blog.csdn.net/breeze_blows/article/details/105323491)] or download the 'fig/' folder

#### state-of-the-art video object detectors performance comparison without post-processing methods.
![video_object_detectors_performance_without_post_process](https://github.com/breezelj/video_object_detection_paper/raw/master/fig/video_object_detectors_performance_without_post_process.JPG)


<br>

#### state-of-the-art video object detectors performance comparison with post-processing methods. ∗ indicates use of video-level post-processing methods (e.g Seq-NMS, tubelet rescoring, BLR), △ indicates using data augmentation
![video_object_detectors_performance_with_post_process](https://github.com/breezelj/video_object_detection_paper/raw/master/fig/video_object_detectors_performance_with_post_process.JPG)

<br>
<br>

### Dataset
* **ImageNet**: Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang, Andrej Karpathy,Aditya Khosla, Michael Bernstein, Alexander C. Berg, and Li Fei-Fei. "ImageNet Large Scale Visual Recognition Challenge". IJCV(2015).[[paper](https://arxiv.org/abs/1409.0575)] [[download link](http://image-net.org/challenges/LSVRC/2015/downloads)]
* **Epic Kitchen**: Dima Damen, Hazel Doughty, Giovanni Maria Farinella,Sanja Fidler, Antonino Furnari, Evangelos Kazakos, Davide Moltisanti, Jonathan Munro, Toby Perrett, Will Price, et al. "Scaling egocentric vision: The epic-kitchens dataset". ECCV(2018).[[paper](https://arxiv.org/pdf/1804.02748.pdf)] [[download link](https://epic-kitchens.github.io/2020-100)]

<br>

### ACM MM 2020
* **DSFNet**: Lijian Lin, Haosheng Chen, Honglun Zhang, Jun Liang, Yu Li, Ying Shan, Hanzi Wang. "Dual Semantic Fusion Network for Video Object Detection". ACM MM(2020).  [[paper](https://arxiv.org/pdf/2009.07498.pdf)]
* **EBFA**: Liang Han, Pichao Wang, Zhaozheng Yin, Fan Wang, Hao Li. "Exploiting Better Feature Aggregation for Video Object Detection.". ACM MM(2020).  [[paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413927)]

<br>

### ECCV 2020
* **LSTS**: Jiang, Zhengkai and Liu, Yu and Yang, Ceyuan and Liu, Jihao and Gao, Peng and Zhang, Qian and Xiang, Shiming and Pan, Chunhong. "Learning Where to Focus for Efficient Video Object Detection". ECCV(2020).  [[paper](https://arxiv.org/pdf/1911.05253.pdf)] [[code](https://github.com/jiangzhengkai/LSTS)]
* **OLTA**: Chun-Han Yao, Chen Fang, Xiaohui Shen, Yangyue Wan, Ming-Hsuan Yang. "Video Object Detection via Object-level Temporal Aggregation". ECCV(2020). [[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590154.pdf)]
* **HVRNet**: Mingfei Han, Yali Wang, Xiaojun Chang, and Yu Qiao Mining. "Mining Inter-Video Proposal Relations for Video Object Detection". ECCV(2020). [[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660426.pdf)] [[code](https://github.com/youthHan/HVRNet)]
* **CHP**: Zhujun Xu, Emir Hrustic, and DamienVivet. "CenterNet Heatmap Propagation for Real-time Video Object Detection". ECCV(2020). [[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700222.pdf)]

<br>

### CVPR 2020
* **MEGA**: Yihong Chen, Yue Cao, Han Hu, Liwei Wang. "Memory Enhanced Global-Local Aggregation for Video Object Detection". CVPR(2020).[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Memory_Enhanced_Global-Local_Aggregation_for_Video_Object_Detection_CVPR_2020_paper.pdf)] [[code](https://github.com/Scalsol/mega.pytorch)]

<br>

### AAAI 2020
* **TCENet**: Fei He, Naiyu Gao, Qiaozhe Li, Senyao Du, Xin Zhao, Kaiqi Huang. "Temporal Context Enhanced Feature Aggregation for Video Object Detection". AAAI(2020).[[paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/6727)]

<br>

### ICCV 2019
* **RDN**: Jiajun Deng, Yingwei Pan, Ting Yao, Wengang Zhou, Houqiang Li, and Tao Mei. "Relation Distillation Networks for Video Object Detection". ICCV(2019).[[paper](https://arxiv.org/pdf/1908.09511v1.pdf)]
* **SELSA**: Haiping Wu, Yuntao Chen, Naiyan Wang, Zhaoxiang Zhang. "Sequence Level Semantics Aggregation for Video Object Detection". ICCV(2019).[[paper](https://arxiv.org/abs/1907.06390v2)] [[code](https://github.com/happywu/Sequence-Level-Semantics-Aggregation)]
* **LLTR**: Mykhailo Shvets, Wei Liu, Alexander C. Berg. "Leveraging Long-Range Temporal Relationships Between Proposals for Video
Object Detection". ICCV(2019).[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Shvets_Leveraging_Long-Range_Temporal_Relationships_Between_Proposals_for_Video_Object_Detection_ICCV_2019_paper.pdf)]
* **OGEMN**: Hanming Deng, Yang Hua, Tao Song, Zongpu Zhang, Zhengui Xue, Ruhui Ma, Neil Robertson, and Haibing Guan. "Object Guided External Memory Network for Video Object Detection". ICCV(2019).[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Object_Guided_External_Memory_Network_for_Video_Object_Detection_ICCV_2019_paper.pdf)]
* **PSLA**: Chaoxu Guo, Bin Fan1, Jie Gu, Qian Zhang, Shiming Xiang, Veronique Prinet, Chunhong Pan1. "Progressive Sparse Local Attention for Video Object Detection". ICCV(2019).[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Guo_Progressive_Sparse_Local_Attention_for_Video_Object_Detection_ICCV_2019_paper.pdf)]
* **A Delay Metric for Video Object Detection: What Average Precision Fails to Tell**: Huizi Mao, Xiaodong Yang, William J. Dally. "A Delay Metric for Video Object Detection: What Average Precision Fails to Tell". ICCV(2019).[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_A_Delay_Metric_for_Video_Object_Detection_What_Average_Precision_ICCV_2019_paper.pdf)]

<br>

### AAAI 2019
* **LWDN**: Zhengkai Jiang, Peng Gao, Chaoxu Guo, Qian Zhang, Shiming Xiang, Chunhong Pan. "Video Object Detection with Locally-Weighted Deformable Neighbors". AAAI(2019).[[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4871)]
* **DorT**: Hao Luo, Wenxuan Xie, Xinggang Wang, Wenjun Zeng. "Detect or Track: Towards Cost-Effective Video Object Detection/Tracking". AAAI(2019).[[paper](https://arxiv.org/abs/1811.05340)]

<br>

### CVPR 2018
* **THP**:  Xizhou Zhu, Jifeng Dai, Lu Yuan, Yichen Wei. "Towards High Performance Video Object Detection". CVPR(2018).[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhu_Towards_High_Performance_CVPR_2018_paper.pdf)]
* **LSTM-SSD**:  Mason Liu, Menglong Zhu. "Mobile Video Object Detection with Temporally-Aware Feature Maps". CVPR(2018).[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Mobile_Video_Object_CVPR_2018_paper.pdf)]
* **ST-Lattice**:  Kai Chen, Jiaqi Wang, Shuo Yang, Xingcheng Zhang, Yuanjun Xiong, Chen Chang Loy, Dahua Lin. "Optimizing Video Object Detection via a Scale-Time Lattice". CVPR(2018).[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Optimizing_Video_Object_CVPR_2018_paper.pdf)]

<br>

### ECCV 2018
* **STSN**:  Gedas Bertasius, Lorenzo Torresani, ianbo Shi. "Object Detection in Video with Spatiotemporal Sampling Networks". ECCV(2018).[[paper](https://arxiv.org/pdf/1803.05549v2.pdf)]
* **STMM**:  Fanyi Xiao, Yong Jae Lee. "Video Object Detection with an Aligned Spatial-Temporal Memory". ECCV(2018).[[paper](https://arxiv.org/pdf/1712.06317v3.pdf)] [[code](http://fanyix.cs.ucdavis.edu/project/stmn/project.html)]
* **MANet**:  Shiyao Wang, Yucong Zhou, Junjie Yan, Zhidong Deng. "Fully Motion-Aware Network for Video Object Detection". ECCV(2018).[[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Shiyao_Wang_Fully_Motion-Aware_Network_ECCV_2018_paper.pdf)]

<br>

### CVPR 2017
* **DFF**:  Xizhou Zhu, Yuwen Xiong, Jifeng Dai, Lu Yuan, Yichen Wei. "Deep Feature Flow for Video Recognition". CVPR(2017).[[paper](https://arxiv.org/pdf/1611.07715.pdf)] [[code](https://github.com/msracver/Deep-Feature-Flow)]

<br>

### ICCV 2017
* **FGFA**:  Xizhou Zhu, Yujie Wang, Jifeng Dai, Lu Yuan, Yichen Wei. "Flow-Guided Feature Aggregation for Video Object Detection". ICCV(2017).[[paper](https://arxiv.org/abs/1703.10025v2)] [[code](https://github.com/msracver/Flow-Guided-Feature-Aggregation)]
* **D&T**:  Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman. "Detect to Track and Track to Detect". ICCV(2017).[[paper](https://arxiv.org/pdf/1710.03958v2.pdf)] [[code](https://github.com/feichtenhofer/detect-track)]

<br>

### Papers before 2017
* **T-cnn**:  Kai Kang, Hongsheng Li, Junjie Yan, Xingyu Zeng, Bin Yang, Tong Xiao, Cong Zhang, Zhe Wang, Ruohui Wang, Xiaogang Wang, Wanli Ouyang. " T-cnn:
Tubelets with convolutional neural networks for object detection from videos". IEEE Transactions on Circuits and Systems for Video Technology(2017).[[paper](https://arxiv.org/abs/1604.02532)] [[code](https://github.com/myfavouritekk/T-CNN)]
* **Object detection from video tubelets with convolutional neural networks**:  Kai Kang, Wanli Ouyang, Hongsheng Li, Xiaogang Wang. "Object detection
from video tubelets with convolutional neural networks". CVPR(2016).[[paper](https://arxiv.org/pdf/1604.04053.pdf)] [[code](https://github.com/myfavouritekk/vdetlib)]
* **Seq-NMS**:  Wei Han, Pooya Khorrami, Tom Le Paine, Prajit Ramachandran, Mohammad Babaeizadeh, Honghui Shi, Jianan Li, Shuicheng Yan, Thomas S. Huang. "Seq-NMS for Video Object Detection". ArXiv(2016).[[paper](https://arxiv.org/pdf/1602.08465v2.pdf)]
