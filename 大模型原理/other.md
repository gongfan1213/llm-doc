以下是从最新研究中筛选出的关于大模型原理的arXiv论文链接，涵盖从基础架构到前沿理论的多个层面，按由浅入深的顺序排列，并确保与历史内容不重复：

### 1. **基础架构与注意力机制**
- **《Training Dynamics of Multi-Head Softmax Attention for In-Context Learning: Emergence, Convergence, and Optimality》**  
  耶鲁大学团队分析单层多头自注意力模型的训练动态，揭示上下文学习的收敛性和任务分配机制。  
  [arXiv:2403.00993](https://arxiv.org/abs/2403.00993)

- **《Theoretical Analysis of Positional Encodings in Transformer Models》**  
  系统分析位置编码（如正弦、ALiBi）对模型表达能力和泛化性的影响，提出基于正交函数的新编码方法。  
  [arXiv:2506.06398](https://arxiv.org/abs/2506.06398)

### 2. **模型优化与训练方法**
- **《PENCIL: Long Thoughts with Short Memory》**  
  ICML 2025论文，提出交替“生成-擦除”的推理范式，解决传统思维链（CoT）的上下文爆炸问题，理论证明其图灵完备性。  
  [arXiv:2503.14337](https://arxiv.org/abs/2503.14337)

- **《Knowledge Circuits in Pretrained Transformers》**  
  NeurIPS 2024论文，提出“知识回路”假说，通过稀疏子图解释大模型的知识存储与处理机制。  
  [arXiv:2405.17969](https://arxiv.org/abs/2405.17969)

### 3. **长序列处理与新型架构**
- **《Titans: Neural Long-Term Memory for Sequential Modeling》**  
  谷歌团队提出支持200K上下文窗口的新架构，整合短期/长期记忆模块，优化长序列处理效率。  
  [arXiv:2501.00663](https://arxiv.org/abs/2501.00663)

- **《APAR: LLMs Can Do Auto-Parallel Auto-Regressive Decoding》**  
  清华大学提出自动并行自回归解码，通过层次化结构微调实现4倍速度提升，减少KV缓存消耗。  
  [arXiv:2401.06761](https://arxiv.org/abs/2401.06761)

### 4. **理论分析与扩展能力**
- **《Deep Residual Learning with Product Units》**  
  提出乘积单元残差网络（PURe），通过乘法交互提升表达效率，在ImageNet等任务中超越传统ResNet。  
  [arXiv:2505.04397](https://arxiv.org/abs/2505.04397)

- **《From Reasoning to Learning: A Survey on Hypothesis Discovery and Rule Learning with LLMs》**  
  综述大模型的溯因、演绎与归纳推理能力，探讨其从“信息执行器”到“创新引擎”的潜力（未提供arXiv链接，但可参考摘要内容）。

### 5. **前沿探索与多模态**
- **《Scaling Laws and Emergent Abilities in Large Language Models》**  
  分析模型规模与涌现能力的关系（如上下文学习、指令跟随），讨论Chinchilla等模型的优化策略。  
  （综述类内容，具体论文可延伸阅读《Scaling Laws for Neural Language Models》等）

### 其他推荐方向
- **《Transformers as Algorithms: Generalization and Implicit Bias》**  
  理论分析Transformer的算法化泛化行为（未在搜索结果中，但属经典方向补充）。

如需更具体的领域（如知识编辑、多模态推理）或某篇论文的详细解读，可进一步筛选。