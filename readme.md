# 电赛前准备
**人员信息 分工 技术栈**
小组一共3人：唯凡 鸡哥 琦 均为电子信息工程专业 *第一人为队长*
1.唯凡：负责硬件兼电控 硬件可以画pcb板子，电控可以写基本程序 调试小车
2.鸡哥：硬件 可独自完成主控板的制作 一些降压模块（boost等） 组装小车
3.琦：硬件 可以画电源板 拓展板等板子 焊接pcb板子
## 方向
方向选择：嵌入式 控制方向
**题目：送药小车**
  分析 
传感器模块：循迹传感器*识别引导线*  距离传感器*避开障碍物* 视觉识别传感器*识别药品信息等***由于视觉刚开始接触所以视觉传感器装配周期较长**
控制模块：stm32
  电控：
路径算法：A*算法
电机控制：编写电机驱动程序 PWM技术控制电机
图像识别：Openmv等图像处理**提取特征和目标识别**
电机驱动：TB6612
蓝牙：CSM92F25
红外传感器
LED指示灯
锂电池12V
## 设备清单
**工具**
    热熔胶 万用表 黑胶带 电池（20块） 螺丝刀套装 焊膏 六角棱柱 
**硬件材料**
   电阻 电感 芯片 电容 开关 视觉模块 电阻丝 蜂鸣器
**软件工具链**
   文本编辑器 *VSC*  编译器 *将源代码编译成可执行文件*  嘉立创
eg：keil5
## 学习计划
  唯凡：学习stm32相关知识以及工作原理库函数的使用*周期：2周* 
  鸡哥：学习无线充电基本理论*两周*
  琦:学习PCB排线规则PCB板绘制要求*一周*电源板，电机驱动板工程制作及焊接*二周*两辆小车搭建，测试*三周*
  根据实验室安排 再规定时间内画好开源的板子，并对其进行焊接，
