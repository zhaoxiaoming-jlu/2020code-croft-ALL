# 2020code-croft-ALL
2020华为软件精英赛从热身赛到决赛代码，战队macrecry。

热身赛 31名，使用平均逻辑回归做二分类，使用mmap多线程读入，neon加速计算。0.0316s。

初赛西北赛区13名 使用for循环展开dfs和反向剪枝，进行3-7环的循环转账搜索，多线程mmap写入。0.21s 。

复赛西北赛区第3名，反向4层dfs剪枝，正向8层dfs查找，3-8环搜索。11.00s。

全国总决赛第24名，分别使用优先队列和手写更新堆，进行dijk搜索，使用前向星保存图，多线程原子锁进行任务分配。983s。
