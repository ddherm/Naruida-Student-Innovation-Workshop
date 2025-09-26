预备知识：
连续时间系统和离散时间系统的时频域分析。
TI官方的授课ppt文件：Introduction to mmwave Sensing: FMCW Radars.pdf

这是一份有关FMCW雷达的Matlab仿真demo(Radar_Target_Generation_and_Detection.m)，
里面有chirp信号的生成，以及雷达参数的基础设定，
模拟接收信号的时延过程，以及接收信号和发射信号的混频过程，
最后通过2D-FFT得到RD图获得目标距离、速度定位，
并使用恒虚警率（Constant False Alarm Rate，CFAR）检测技术对探测目标进行判决。

请思考并尝试解决以下问题：
1、此代码为单一目标检测，如何加入多目标检测？不同目标间的最大可分辨距离或者速度是多少？
请从实验现象和原理上分别进行分析。
2、此代码的距离分辨力远高于速度分辨率，原因是什么？如何调节参数，增加速度分辨率？
3、对CFAR原理进行简单介绍。
4、能否使用多个阵元之间的相位差，实现对目标的方向估计。