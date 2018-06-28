### 题目描述

输入三个数组 `a` `b` 和 `c`，保证每个数组已按升序排序。

另外输入一个 `k`，你需要返回所有数组中的元素的第 `k` 小值。

参考：[【UR #4】元旦激光炮](http://uoj.ac/problem/52)
### 接口

`int query_kth(const int *a, int n_a, const int *b, int n_b, const int *c, int n_c, int k)`

### 数据范围

`n_a` `n_b` 和 `n_c` 均等于 10,000,000。数组中的每个元素均为不超过 1,000,000,000 的正整数。`k` 为不超过 30,000,000 的正整数。

函数 `query_kth` 会被调用 100 次，但多次调用时，仅 `k` 发生变化。

### 注意事项

本题的 `a` `b` 和 `c` 数组不计入空间限制，但你不能修改其中的内容。

交互库会占用 4 KB 的内存。