﻿# Algorithm optimization 优化一些常见的OpenCV算法

- speed_filter2d_in_gray_image.cpp 使用OpenBLAS和OpenMP优化对灰度图的卷积算法(filter2D)
- speed_filter2d_in_rgb_image.cpp 使用OpenBLAS和OpenMP优化对RGB图的卷积算法(filter2D)
- speed_meanFilter_in_gray_image.cpp 使用x86循环展开，openmp优化均值滤波算法
- speed_medianFilter_in_gray_image.cpp AVX和Openmp，优化中值滤波算法
- speed_twoVector_distance.cpp AVX和x86循环展开，优化计算两个向量距离算法
- Huang_Fast_MedianBlur.cpp 利用直方图实现快速中值滤波算法，算法原理：https://blog.csdn.net/just_sort/article/details/87994573