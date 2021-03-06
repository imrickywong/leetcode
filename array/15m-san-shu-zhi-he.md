# \#15M 三数之和

## 题目

给你一个包含 _n_ 个整数的数组 `nums`，判断 `nums` 中是否存在三个元素 _a，b，c ，_使得 _a + b + c =_ 0 ？请你找出所有满足条件且不重复的三元组。

**注意：**答案中不可以包含重复的三元组。

**示例：**

```text
给定数组 nums = [-1, 0, 1, 2, -1, -4]，

满足要求的三元组集合为：
[
  [-1, 0, 1],
  [-1, -1, 2]
]
```

## 解法一：无脑暴力循环

无脑搜索，三层循环，遍历所有的情况。需要注意的是，我们需要把重复的情况去掉，也就是 \[ 1, -1, 0 \] 和 \[ 0, -1, 1\] 是属于同一种情况的。

不过三层循环会达到 `O(n^3)` 的时间复杂度，所以会报超时错误，所以算法还需要优化。

## 解法二：数组排序+双指针





