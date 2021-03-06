
## 背包问题

### 代码

[背包问题代码](pack.cpp)

### 问题说明

有N件物品和一个容量为V的背包。

第i件物品的重量是w[i]，价值是v[i]。

求解将哪些物品装入背包可使这些物品的重量总和不超过背包容量，

且价值总和最大。

### 功能说明

本程序用动态规划的思想解决了背包问题，并用了两种算法：
迭代法、递归法。在迭代法中实现了打印背包问题的表格。

### 代码简述

通过用户输入数据，程序输入检测，动态分配空间，选择算法，
用动态规划的思想求解背包问题。

#### 迭代法：
通过遍历n行W列，迭代每行每列的值，并把最优解放到
n行（在数组中为第n+1行）W列（在数组中为第W+1列）中。

#### 递归法：
通过每次返回前i个物品和承重为j的最优解，
递归计算总背包问题的最优解。
