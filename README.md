# slam_homework

从零开始学习SLAM笔记
# 01HW
 题目：我们知道SLAM是处理序列图像的，有时候需要格式化的图像名字用作输入。前面提到的TUM的RGB-D数据集中图像是根据时间命名的，请从下面链接下载数据集fr1/desk
 https://vision.in.tum.de/data/datasets/rgbd-dataset/download# 并解压。请编程实现将文件夹/rgb下以时间命名的序列图片重新命名为0000-9999的格式。

 本程序学习目标： 熟悉cmake的使用、OpenCV读写操作、C++的string操作 作者：公众号：计算机视觉life。发布于公众号旗下知识星球：从零开始学习SLAM
 ```shell
 mkdir build
cd build
cmake ..
make
 ./homework01 /home/hao/bags/tum/rgbd_dataset_freiburg1_desk/rgb
 ```
