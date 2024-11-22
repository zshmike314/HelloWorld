$$
L(\theta) = \sum_{i=1}^{n} w_i \cdot L_i(\theta)
$$
其中，$\theta$ 是全局模型的参数，$L_i(\theta)$ 是客户端 $i$ 的局部损失函数，$w_i$ 是客户端 $i$ 的权重，反映了客户端 $i$ 的重要性或数据量，且 $\sum_{i=1}^{n} w_i = 1$。
