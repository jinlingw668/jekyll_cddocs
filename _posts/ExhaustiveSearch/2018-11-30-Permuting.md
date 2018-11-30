---
layout: default
tags:
  - CD Demo
categories:
  - ExhaustiveSearch
permalink: /ExhaustiveSearch/Permuting
---
### 全排列遍历算法
1. 全排列算法，输出1~n的所有排列情况。
2. 全排列算法，关键的一点是：(s[i],s[j]) 第1次交换之后，需要再交换回来，以恢复到原始序列。参见代码行5和7。
3. Call Stack记录递归遍历中的父函数关键信息，以“No: (i,j)”或者“No: (i)”的形式 
- No: (i,j) - (s[i],s[j]) 相交换； 
- No: (i) - (s[i]) 到达尾端，输出排列；
4. Output 标识算法的中间输出，以"cnt：Perm"的形式 
- cnt - 排列计数，对应全局变量cnt； 
- Perm - 排列序列； 
5. 例如 n=4时 
- 10: (0,0);(1,1);(2,3); - 栈顶对应步骤No10，(s[2],s[3]) 相交换； 
- 12: (0,0);(1,1);(2,3);(3) - 栈顶对应步骤No12，(s[3]) 输出一个排列Output； 
- 12: (0,0);(1,1);(2,3); - 栈顶对应步骤No12，(s[2],s[3]) 交换回来；