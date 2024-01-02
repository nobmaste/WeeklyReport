# 不定期周刊：002

 
> 作者：mlm
> 日期：2024年1月日
> ***
> 本杂志开源（GitHub:[nobmaste/WeeklyReport ](https://github.com/nobmaste/WeeklyReport)），欢迎提交 issue，投稿或推荐你的项目。
## 1.铁电材料模拟大脑结构
![截图1](https://github.com/nobmaste/WeeklyReport/blob/main/dcos/issue-002/img/shutu.jpg)
斯坦福大学研究团队提出了一种“纳米晶核”用于模拟神经元突触
该器件是一种改进过的晶体管，当脉冲以正确的顺序到达时会打开并允许电流通过。
优点是高效的**并行处理、更少的热量**。
基于铁电晶体管进行设计是因为铁*电晶体管曾被认为是在神经形态芯片中结合记忆和逻辑的一种方式*——铁电材料在其**极化中提供存储器**，当栅极接收到电压脉冲时，该极化翻转，然后它会保持这种极化，直到它接收到另一个脉冲。<br>
原文链接：https://spectrum.ieee.org/dendrites
## 2. 泰勒展开的工程应用
四轴小马哥的博文，内容很简单。在控制算法中需要运算反三角函数，一般依赖math库解决计算，但不同MCU的架构不同，所以有时候不想调库时，在误差允许范围内依靠泰勒展开来进行这些计算。<br>
链接：https://mp.weixin.qq.com/s/iaoWnK55VJp5-Bvl9GXpLA