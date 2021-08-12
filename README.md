# DatabaseAndAlgorithm（自己学习数据结构和算法）
## 数组
    数组基本操作
    稀疏数组
    将稀疏数组存入硬盘和读出
## 链表
### 单链表
    添加节点
    更改节点
    删除节点
    顺序添加节点
    获取单链表节点的个数
    查找链表中倒数第k个节点
    单链表的反转
    逆序打印单链表
    合并两个链表
### 双向链表
    添加节点
    更改节点
    删除节点
    顺序添加节点
### 栈
    数组模拟栈
    利用栈计算表达式
    中缀表达式转后缀表达式并进行表达式的计算
## 八大排序
### 冒泡排序
    内部排序法
    冒泡排序的实现与优化
    进行排序时间速度测试
### 选择排序
    内部排序法
    选择排序的实现与优化
    进行排序时间速度测试（优于冒泡排序）
### 插入排序
    插入排序的实现与优化
    插入排序的时间速度测试
### 希尔排序
    实现与优化
    1.利用交换法
    2.利用移动法（类似于插入排序）
    3.移动法速度快于交换法
### 快排排序
    快排的实现
    速度测试（速度对比前面最快）
    使用while循环与递归调用
### 归并排序
    归并排序的代码实现
    运用两个方法+递归+while
    时间复杂度低（速度测试），速度快。
### 基数排序
    基数排序的实现（理解较难）
    速度测试（目前最快）
    用到二维数组。
## 查找

### 线性查找
    for循环遍历ArrayList存取
### 二分查找（需要有序序列）
    1.二分查找的实现（递归），存在不能查找多个数据
    2.解决1中问题，可以查找多个数据
    3.用ArrayList存取（while循环）
### 插值查找
    实现：递归 + int mid = left + (right - left) * (findValue - arr[left]) / (arr[right] - arr[left]);
    适用于数据量大的查找方法，在一方面优于二分查找
### 斐波那契（黄金分割法）查找
    未实现
## 哈希表   
    暂未实现
## 树
### 二叉树
    创建节点，二叉树
    利用递归进行二叉树的 前 中 后序遍历，还有前 中 后序查找和删除
### 顺序存取二叉树
    创建一个数组，利用二叉树的性质遍历（前 中 后）
### 线索化二叉树
    概念与代码实现，运用递归
    运用中序遍历线索化二叉树
