---
term: AVG.回合时长

---
平均轮次持续时间是一个指标，用于根据网络难度和矿池哈希率估算矿池找到一个区块所需的时间。计算方法是将预期找到一个区块的份额数除以矿池的哈希率。例如，如果一个矿池有 200 个矿工，每个矿工平均每秒产生 4 个区块，那么矿池的总计算能力就是每秒 800 个区块：

```text
200 * 4 = 800
```

假设平均需要 100 万个份额才能找到一个有效区块，则池的 *Avg.回合持续时间*为 1,250 秒，约 21 分钟：

```text
1,000,000 / 800 = 1,250
```

实际上，这意味着矿池平均每 21 分钟左右就能找到一个区块。这一指标会随着矿池哈希率的变化而波动：哈希率的增加会缩短*平均回合持续时间*，而哈希率的减少则会延长*平均回合持续时间*。回合持续时间*，而减少则会延长。它还会随着比特币难度目标的定期调整（每 2016 个区块一次）而波动。该指标不考虑其他矿池发现的区块，只关注被研究矿池的内部性能。