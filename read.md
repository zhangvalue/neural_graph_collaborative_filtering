# Neural Graph Collaborative Filtering
## 基于图神经网络的协同过滤算法
**基于图神经网络的协同过滤算法 NGCF，它可以显式地将 User-Item 的高阶交互编码进 Embedding 中来提升 Embedding 的表示能力进而提升整个推荐效果。
NGCF 的关键就在于 Embedding Propagation Layer 来学习 User 和 Item 的 Embedding，后面的预测部分只是简单的内积。
可以说，NGCF 较好地解决了协同过滤算法的第一个核心问题。
另外，本文的 Embedding Propagation 实际上没有考虑邻居的重要性，
如果可以像 Graph Attention Network 在传播聚合过程中考虑邻居重要性的差异，NGCF 的效果应该可以进一步提升。
**
