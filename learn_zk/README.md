# 零知识证明相关理论

## 逻辑框架

![](/Users/confucian/TaiDi-Tech/github-repo/ZK-Learn/img/zk_framework.png)

## 常见的算法

> 区块链领域中所用到或者提到的 “zk” 通常不是真正的零知识证明, 而经常是 Validity Proof

![](../img/zkp.png)

### zk-SNARK

#### 概念

**z**ero-**k**nowledge **S**uccint **N**on-interactive **AR**guments of **K**nowledge

- **S**uccinct：证明的数据量比较小
- **N**on-interactive：没有或者只有很少交互
- **AR**guments：验证者只对计算能力有限的证明者有效。拥有足够计算能力的证明者可以伪造证明。这也叫“计算可靠性"（相对的还有”完美可靠性"）
- of **K**nowledge：对于证明者来说在不知道证据（**Witness**，比如一个哈希函数的输入或者一个确定 Merkle-tree 节点的路径）的情况下，构造出一组参数和证明是不可能的

### Zk-STARK