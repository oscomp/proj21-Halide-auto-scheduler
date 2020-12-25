# proj21-Halide-auto-scheduler
### 项目名称
Halide auto-scheduler优化

### 项目描述

[Halide](https://halide-lang.org/)是一个算法和调度分离，基于C++的计算语言，主要面向图像和阵列信号处理。Halide auto scheduler可以帮助开发人员自动搜索适用于算法执行的最优调度策略，可以有效缩短手工算法实现优化的时间。

虽然Halide已经包括了auto scheduler的支持，但是针对auto scheduler的研究和实现才刚起步，针对DSP/FPGA/GPU等不同计算硬件的优化仍有很大提高空间。

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

**杨振西**

* github 

* email yangzx0409@thundersoft.com

### 难度

中等

### 特征

-   Halide​ Auto Scheduler原理分析

-   Auto Scheduler优化方向

-   针对图像处理场景，对CPU/DSP/GPU等不同硬件的Auto Scheduler优化方案

-   Auto Scheduler性能评估

### 文档

https://github.com/halide

### License

* [The MIT License](https://opensource.org/licenses/MIT)

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：典型图像处理算法的Halide auto scheduler加速性能评估

-   在基于ARMV8架构的嵌入式设备或手机上，评估常用图像处理滤波算法使用auto
    scheduler的加速效果。

-   评估算法范围包括OpenCV [Image
    Processing](https://docs.opencv.org/master/d7/dbd/group__imgproc.html)下常用的滤波和特征提取算法

### 第二题：简单Auto Scheduler的设计和实现

-   学习Halide内置的Auto Scheduler原理。

-   设计并实现一个简单的Auto Scheduler。

### 第三题：Auto Scheduler优化

-   基于​第一题的结果和第二题对Auto Scheduler的理解，分析现有auto
    scheduler的不足并提出改进方向

-   设计和实现一个优化的auto scheduler并比较与baseline的性能差异。