# classical-SLAM
一些经典的SLAM算法学习并注释的版本


## ORB-SLAM 框架

- ORB-SLAM

- ORB-SLAM2
> [ORB-SLAM2代码](https://github.com/raulmur/ORB_SLAM2)  
>特点： tracking, local mapping, loop closing 三线程  

- ORB-SLAM2with_pointcloud_map
> [ORB-SLAM2with_pointcloud_map代码](https://github.com/gaoxiang12/ORBSLAM2_with_pointcloud_map)  
>特点： 在tracking, local mapping, loop closing 三线程的基础上,增加了semantic segmentation, dense mapping threads.  



- DS-SLAM(A Semantic Visual SLAM towards Dynamic Environments)  
>[论文](https://arxiv.org/abs/1809.08379v1) 
[代码](https://github.com/ivipsourcecode/DS-SLAM)  
>特点：在ORB-SLAM2with_pointcloud_map的基础上，增加了SegNet(pixel-wise semantic segmentation based on caffe in real-time)
