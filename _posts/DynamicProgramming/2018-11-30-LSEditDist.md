---
layout: default
tags:
  - CD Demo
categories:
  - DynamicProgramming
permalink: /DynamicProgramming/LSEditDist
---
### Levenstein编辑距离
#### 演示说明
1. 使用ep标识距离和方向，其中p的值说明如下：
- U - 从上方计算来的e；
- L - 从左侧计算来的e；
- 0 - 从左上计算来的e，对应x[i]与y[j]字符相同的情况；
- 1 - 从左上计算来的e，对应x[i]与y[j]字符不同的情况；
2. 两个或三个方向上距离值相等时，计算次序为：U、L、0/1。
3. 交互时不需考虑上标，如“3U”可直接输入“3U”。
4. “ε”符号表示空串，借用自计算理论。
