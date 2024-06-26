# 23级培训计划

## 整体介绍
### 1.主要的任务
  - calibrate_task
  - CAN_receive
  - chassis_remote_control
  
## 学习任务
### 一、C语言学习内容

- 变量
  - 命名规范
  - 占用空间
  - 作用域
- 进制表示
- 位运算
- 结构体
- 共用体
- 枚举
- typedef关键字
- 指针
  - 取值符
  - 解引用
  - 定义指针时未分配空间
- 状态机
- 耦合问题

### 二、STM32内容学习

- GPIO点亮LED灯
- IIC、SPI、CAN、UART通信学习
- ADC、DMA外设学习
- 外部中断
- 定时器
- PWM
- 枚举
- FreeRTOS

### 三、控制算法内容学习

- PID算法，并用C语言结构体进行封装
- 控制系统中的一些基本概念，例如开环、闭环、干扰、反馈、校正、误差等，建议看自动控制原理
- PID的改进算法，例如分段PID、模糊PID、串级PID等等
- 麦克拉姆轮、运动学分解
- 卡尔曼滤波的学习
- 机械臂正运动学和逆运动学解算

### 四、相关工具的使用

- https://github.com/（github的使用）

- git的使用

- 更多的使用Google而不使用Baidu

- 使用StackOverflow、ask Ubuntu、nVidia社区等网站而不使用CSDN

- 养成翻官方文档的习惯[RoboMaster 2024机甲大师高校系列赛参赛资料包](https://www.robomaster.com/zh-CN/resource/pages/announcement/1655)，每一年的规则会有改变注意查看。

- 可以使用VSCODE上面的Embedded IDE插件进行开发

  

## 实践任务

1到2人组成一个组完成以下任务

 1、我们会提供已经写好的代码和一个基本工程，要求能够重写一遍一台机器人的代码(步兵、英雄、哨兵自选其一)，在阅读完代码后，按照自己的理解逐步往上面增添控制功能，顺序不定，但要求每增添一个功能的代码后，之前的功能和现在的功能能够兼容，不发生冲突。每个阶段要简单记录到报告中，如果在重写过程中实现了对控制的优化，将想法与实现的结果一并记录到报告中。可参考RoboMaster开发板C型嵌入式软件教程文档。

 2、熟悉一台机器人的连线，用简图的方式绘出机器人的连线，要求标出各个器件的名字和接线类型。

 3、提高任务(可选)

任务一：实现对六轴机械臂的控制，通过串口向机械臂发送一个世界坐标和位姿，机械臂在收到信息后末端执行器移动到对应的位置。

任务二：实现对舵轮步兵底盘的控制，实现遥控底盘的基本功能（各方向移动）和小陀螺功能。



## 学习参考

1. [51单片机入门学习](https://www.bilibili.com/video/BV1Mb411e7re/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click&vd_source=9805319fbcc667bd39b66994068b0d17)
2. [STM32学习开发](https://www.bilibili.com/video/BV1th411z7sn/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click)
3. [C语言从入门到精通](https://www.bilibili.com/video/BV1U44y1y7xN/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click)
4. [C语言参考网站](https://cplusplus.com/reference/)
5. 《C Primer Plus》
6. 《C和指针》
7. 《C++ Primer Plus》
8. [卡尔曼滤波讲解](https://www.bilibili.com/video/BV12D4y1S7fU/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click)
9. [自控原理学习](https://www.bilibili.com/video/BV1F34y1h7so/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click)

​	10.《机器人建模与控制》

