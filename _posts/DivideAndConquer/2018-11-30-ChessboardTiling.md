---
layout: default
tags:
  - CD Demo
categories:
  - DivideAndConquer
permalink: /DivideAndConquer/ChessboardTiling
---
### 棋盘覆盖算法
#### 演示说明
1.  Call Stack 记录算法运行中的栈信息，以“No: (#Loc, rcpqs, TileNo)”的形式记录
- No - 对应演示步骤No;
- \#Loc - 函数调用的return point 返回点，以便返回后继续执行；
  - Loc标识代码行
  - #Loc标识代码行地址；
- rcpqs - 函数调用的参数(r, c, p, q, s)取值；
- TileNo - 棋盘覆盖的L块计数；
2. 例如 n=2 (0,0)时
- 02:(#16,00004) 
  - 栈顶对应步骤No2
  - 函数ChessboardTiling(0,0,0,0,4)的返回点，是ChessBoardTilingCaller的#16代码行；
- 04:(#16,00002,1)(#15,00002) 
  - 栈顶对应步骤No4
  - 函数ChessboardTiling(0,0,0,0,2)的返回点，是父函数ChessboardTiling的#15代码行(递归)；

#### 问题描述
残缺棋盘：一个2k*2k的棋盘中，有一个残缺方格。

棋盘覆盖算法，要求使用L型骨牌，覆盖残缺方格外的所有方格，且骨牌不得重叠。