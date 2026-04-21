# Leetcode算法与常见LLM模型组件代码

本仓库收集了常见的 LeetCode hot 100 算法题解以及常见LLM手撕核心组件的手写实现，旨在帮助开发者巩固基础，深入理解算法与模型原理。

## 目录

- [LeetCode 算法题解](./Code/Leetcode.md)
- [经典深度学习手撕实现](./Code/经典手撕.md)

---

## 主要内容

### 1. LeetCode 算法题解
包含了 LeetCode Hot 100 的 Python 实现，各题解思路都是我认为最适合初学者理解的算法题解。按题型进行分类：
- **基础数据结构**：哈希表、链表、二叉树、栈、堆。
- **常用算法技巧**：双指针、滑动窗口、子串处理。
- **高级算法**：回溯、二分查找、动态规划、贪心算法、图论。

查看详情：[Leetcode.md](./Code/Leetcode.md)

### 2. 经典深度学习手撕实现
包含了大模型（LLM）及深度学习中常用的核心组件与损失函数的手写实现（基于 PyTorch）：
- **模型架构**：LoRA、MoE (Mixture of Experts)、Self-Attention、MHA (Multi-Head Attention)、GQA (Grouped Query Attention) 等。
- **归一化与激活函数**：LayerNorm、RMSNorm、Sigmoid、ReLU、SwiGLU 等。
- **损失函数与强化学习**：Cross Entropy、KL Divergence、PPO Loss、DPO Loss、GRPO Loss 等。

查看详情：[经典手撕.md](./Code/经典手撕.md)

---

## 使用建议
建议先理解原理，再参考代码进行练习，重点关注代码中的关键逻辑与边界条件处理。
