---
layout: default
tags:
  - CD Demo
categories:
  - Sorting/HeapSortNode
permalink: /Sorting/MergeSortNode/MergeSort
---
### 归并排序算法
1. 归并排序的实现，有递归和迭代两种，此处是自上而下的递归式。
2. 使用Op标识演示状态： 
- B - Begin，开始； 
- D - Divide，划分； 
- M - Merge，归并； 
- F - Final step in dividing，划分至最后一步，即单个元素时；
3. 归并排序是稳定的排序算法，但需要O(n)的额外空间。