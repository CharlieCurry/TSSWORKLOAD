# TSS 1.0
## Tile Size Selection 
*Optimization of loop programs is an important topic in program optimization. As a typical technique of loop optimization, loop tiling has been widely studied and applied. The selection of tile size, which is complex and highly dependent on program and hardware, has a great impact on the performance of loops. Traditional approaches based on static analysis and heuristic experience search have high cost of labor and time, and lack generality and portability. Therefore, the neural network method, which is good at representing high-dimensional information, is considered to learn the hidden correlation between tiling size and program performance, which is a result of complex interaction between program and hardware.*

link:http://www.jsjkx.com/CN/10.11896/jsjkx.191200180

CHI Hao-yu, CHEN Chang-bo. Prediction of Loop Tiling Size Based on Neural Network[J]. Computer Science, 2020, 47(8): 62-70.

Related work:https://link.springer.com/chapter/10.1007/978-3-030-52200-1_28#citeas

中文摘要：
    循环程序的优化一直是程序优化的重点,循环分块作为一种典型的循环程序优化技术已被广泛地研究和应用.分块 大小的选择对循环程序的性能有着重要影响,分块大小的选择复杂多变且高度依赖程序和硬件.传统的静态分析和启发式经 验搜索的人工和时间成本过高,缺少通用性和可移植性.为此,考虑使用有良好高维表示特性的神经网络方法来学习程序与硬 件复杂交互过程中分块大小与程序性能的隐含关联.从问题规模、循环结构、循环内操作的局部性等方面抽取出一组新的２９ 维特征,对问题规模为１０２４~２０４８的随机大小的６类内核程序(３维循环、２维数据)的数十万行示例进行实验.串行模型 (TSSＧT６)相比 GCCＧO２默认优化实现了６．６４倍的平均加速比,相比穷尽搜索实现了９８．５％的平均最大可用性能,相比 Pluto 默认分块优化实现了平均９．９％的性能提升.并行模型(TSSPＧT６ＧSearch)相比 OpenMP默认优化实现了２．４１倍的平均加速 比,相比穷尽搜索实现了９１．７％的平均最大可用性能,同时与 Pluto默认分块并行优化相比得到了平均９％的性能提升. 关键词:编译优化;自动调优;循环程序分块;人工神经网络;缓存优化

