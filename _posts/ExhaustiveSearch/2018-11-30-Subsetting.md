---
layout: default
tags:
  - CD Demo
categories:
  - ExhaustiveSearch
permalink: /ExhaustiveSearch/Subsetting
---
### 子集遍历算法
1. Call Stack记录递归调用过程中的父函数信息，以“No：(#Loc,n)”的形式 
- No - 对应演示步骤No； 
- \#Loc - 函数调用的return point 返回点，以便返回后继续执行；Loc标识代码行（#Loc标识代码行地址）； 
- n - 函数调用的参数值； 
2. 例如 n = 4 时 
- 02: (#11,3) - 栈顶对应步骤No2，函数Subsetting(3)的返回点，是其#11代码行； 
- 08: (#11,3)(#11,2)(#11,1)(#11,0) - 栈顶对应步骤No8，Subsetting(0) 输出一个子集； 
- 14: (#11,3)(#11,2)(#14,1) - 栈顶对应步骤No14，函数Subsetting(1)的返回点，是其#14代码行；