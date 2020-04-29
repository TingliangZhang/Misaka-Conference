# Misaka-Conference

编译命令：

```
pdflatex Misaka.tex
```

用latexmk -xelatex会缺字体

用latexmk 图片会报错

# 大纲   Outline

Misaka: A Visualized Swarm Testbed for Smart Grid Algorithm Evaluation

介绍和背景 INTRODUCTION

- 

定位： an open-source open-hardware swarm interfaces for Smart Grid Algorithm.

a Visualized Testbed for Smart Grid Algorithm Evaluation



In this article, we present Misaka, a visualized swarm testbed for smart grid algorithm evaluation, also an extendable open-source open-hardware platform for developing tabletop swarm interfaces.

The platform consists of a collection of custom-designed 3-onmi-wheeled robots each 10 cm in diameter, high accuracy localization through a microdot pattern overlaid on top of the activity sheets, and a software framework for application development and control, while remaining affordable (per unit cost about 30 USD at the prototype stage). We illustrate the potential of tabletop swarm user interfaces through a set of smart grid algorithm development application scenarios developed with Misaka.

In summary, our contributions are:

- The first open-source hardware/software platform for smart grid algorithm evaluation with tabletop swarm user interfaces
- Redefinition for Algorithm Visualization with several implemented examples
- A set of scenarios to illustrate the unprecedented possibilities offered by Misaka swarm and by tabletop swarm user interfaces in general
- A common platform for any algorithm visualization, and other interactive swarm user interfaces

Furthermore, as benefits, Misaka:

- are modular each unit, can be extended with powerful platform, such as NVIDIA Jetson NANO.
- can simulate real smart grid communication scenarios with Zigbee modular on board
- can interact with user moving and turning the robot or using the illuminated capacitive touch keys on the robot 
- can be manipulated either individually or collectively
- are small enough to also act as “pixels” of a physical display
- can coexist in large numbers
- are lightweight, can operate on any horizontal surface, and relatively cost-effective: about 30 USD each now, down to
$15 if mass manufactured.

测试算法解释 Test Algorithm

UI EXAMPLES WITH MISAKA : 

- 动态迭代过程
- 信息传输流（带小屏显示帧数据）
- 时间轴尺度操纵



软硬件架构 HARDWARE AND SOFTWARE DESIGN

LIMITATIONS AND FUTURE WORK

CONCLUSION