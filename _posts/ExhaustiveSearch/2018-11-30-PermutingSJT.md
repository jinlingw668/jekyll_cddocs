---
layout: default
tags:
  - CD Demo
categories:
  - ExhaustiveSearch
permalink: /ExhaustiveSearch/PermutingSJT
---
### 全排列遍历-SJT算法
全排列-SJT算法的关键点是：找到最大的可移动项。

1. 使用“>”或“<”标识数字的可移动方向 
- < - 可向左移动； 
- \> - 可向右移动；
2. Output 标识算法的中间输出，以“cnt(No)Perm”的形式 
- cnt - 排列计数，对应全局变量cnt； 
- No - 对应演示步骤No； 
- Perm - 排列序列；