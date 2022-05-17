# 覆盖率

## 什么是覆盖率

>
>
>覆盖率是度量测试完整性的一个手段，是测试有效性的一个度量。通过已执行代码表示，用于可靠性、稳定性以及性能的评测 [`百度百科`](https://baike.baidu.com/item/%E8%A6%86%E7%9B%96%E7%8E%87)



它有四个测量维度。

- **行覆盖率**（line coverage）：是否每一行都执行了？
- **函数覆盖率**（function coverage）：是否每个函数都调用了？
- **分支覆盖率**（branch coverage）：是否每个if代码块都执行了？
- **语句覆盖率**（statement coverage）：是否每个语句都执行了？

## 代码插桩

在保证被测程序原有逻辑完整性的基础上在程序中插入一些探针（又称为“探测仪”，本质上就是进行信息采集的代码段，
可以是赋值语句或采集覆盖信息的函数调用）

## 覆盖率的意义

1.覆盖率是测试同学非常关注且直观的指标。

2.代码覆盖率是查找代码库中未测试部分的有用工具，然而它作为一个数字说明你的测试有多好用处不大。

3.覆盖率低很大程度上代码质量会有问题。