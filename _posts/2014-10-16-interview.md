---
layout: post
title: 面试
categories: 吐槽
tags: 面试
---

列一下最近面试遇到的编程类题目，不会的最好动手写写。

1. 描述一下堆排序的过程，写出建堆的函数。（其实就是 shift 过程，想明白原理就很 easy）
2. 描述快速排序过程，时间复杂度。如何改进（只要看过维斯的《数据结构域算法分析》就毫无压力）
3. 给一个数组，比如[9 10 10 11]，打印数字的全排列，同时找出最大的数字组合（本题为9111010）。(整个首先是全排列，然后考虑数组太大的话会破栈，更稳妥是保存状态)
4. 给一个数组，比如[1 2 2 3 3 3]，找出一种随机算法，使得随机的数字出现比例满足数字出现次数的比例（本题出现1、2、3的比例是1:2:3）。
5. 毕业论文如何判断是否为抄袭？（编辑距离）
6. 表达式求值（模拟栈操作，和括号匹配一样）
7. 如何寻找一个链表的倒数第十个节点（2个指针，1个出发10距离另一个出发）
8. 给你2G的整数，内存只有200M。排序还是啥的，我给忘了（编程珠玑经典题目，可以按照二进制位来搞，也可以多路归并）
9. 一个整数数组的某一个元素个数过半，如何找出这个数字（经典题目了，每次取2个元素，两个不同就随机删一个）
