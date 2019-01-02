# Leetcode-1.Two-Sum
主要思路有两个：
1.两遍循环，暴力方法解决，但是python超时了
2.一次遍历，得到target-当前遍历得到的值（nums[i]=tofind）
dict d 以原数组中的值为键，原数组中的下标为值
查找dict中是否有这个tofind
如果没有就添加到d中
