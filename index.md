---
layout: default
---		

- [图片显示示例](./Classical/image-example.html)  
### 经典算法
- [洗牌算法](./Classical/Shuffle.html)
- [EuclidGCD算法](./Classical/EuclidGCD.html)

### 基于比较的排序算法
- [选择排序算法](./Sorting/SelectSort.html)
- [冒泡排序算法](./Sorting/BubbleSort.html)
- [插入排序算法](./Sorting/InsertSort.html)
- [快速排序算法](./Sorting/QuickSort.html)
- 归并排序
  - [二路归并算法](./Sorting/MergeSortNode/TwoWayMerge.html)
  - [归并排序算法](./Sorting/MergeSortNode/MergeSort.html)
- 堆算法
  - [建堆算法](./Sorting/HeapSortNode/Heapifying.html)
  - [堆排序算法](./Sorting/HeapSortNode/HeapSort.html)
 
### 穷举法
- [线性搜索算法](./ExhaustiveSearch/LinearSearch.html)
- [子集遍历算法](./ExhaustiveSearch/Subsetting.html)	
- [全排列遍历算法](./ExhaustiveSearch/Permuting.html)
- [全排列遍历-SJT算法](./ExhaustiveSearch/PermutingSJT.html)		  

### 分治法
- [二分搜索算法](./DivideAndConquer/BinarySearch.html)
- [棋盘覆盖算法](./DivideAndConquer/ChessboardTiling.html)	

### 动态规划方法
- [Levenstein编辑距离](./DynamicProgramming/LSEditDist.html)
- [0-1背包问题](./DynamicProgramming/DP0_1Knapsack.html)	

### 图算法
- [广度优先搜索算法](./GraphAlgorithms/GraphBFS.html)
- [深度优先搜索算法](./GraphAlgorithms/GraphDFS.html)	

　　　　{% for post in site.categories.sorting %} 
            <li>post.title</li>　　　　　　
　　　　{% endfor %}
