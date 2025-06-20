以下是关于模型训练的最新arXiv论文推荐，涵盖从基础优化方法到前沿训练范式的多个方向，按由浅入深顺序排列，确保内容不重复：

---

### 1. **基础训练优化技术**
- **《Training Transformers with 4-bit Integers》**  
  提出INT4量化训练方法，通过Hadamard量化器和梯度稀疏化技术，在保持精度的同时实现比FP16快2.2倍的训练速度。适合资源受限场景。  
  [arXiv:2306.11987](https://arxiv.org/abs/2306.11987)

- **《Stretching Each Dollar: Diffusion Training from Scratch on a Micro-Budget》**  
  索尼AI团队开发低成本扩散模型训练方法，通过延迟掩蔽（Deferred Masking）和轻量级Patch-Mixer，仅用1890美元训练11.6亿参数模型。  
  [arXiv:2407.15811](https://arxiv.org/abs/2407.15811)

---

### 2. **高效架构与分布式训练**
- **《NoLoCo: No All-Reduce Low Communication Training for Large Language Models》**  
  Gensyn公司提出的分布式训练框架，通过随机局部通信替代全局同步，减少高速网络依赖，适合跨数据中心训练。  
  [arXiv:2506.10911](https://arxiv.org/abs/2506.10911)

- **《nGPT: Normalized Transformer on Hyperspheres》**  
  英伟达团队的超球面归一化Transformer，通过向量单位化简化计算，在8K上下文下训练速度提升20倍，且精度无损。  
  [arXiv:2410.01131](https://arxiv.org/abs/2410.01131)

---

### 3. **数据优化与预训练革新**
- **《Rewriting Pre-Training Data Boosts LLM Performance in Math and Code》**  
  提出数据重写技术，通过语法修正和风格转换增强代码与数学数据质量，使Llama-3.1-8B在HumanEval上提升17分。  
  [arXiv:2505.02881](https://arxiv.org/abs/2505.02881)

- **《Model Merging in Pre-training of Large Language Models》**  
  字节Seed团队的预训练模型合并（PMA）技术，通过检查点权重平均提升13%性能，并减少训练周期。  
  [arXiv:2505.12082](https://arxiv.org/abs/2505.12082)

---

### 4. **强化学习与推理优化**
- **《Magistral: Pure RL Training for Reasoning》**  
  Mistral AI的纯强化学习框架GRPO，通过自对比答案优化推理路径，在AIME数学竞赛中性能提升50%。  
  [arXiv:2506.10910](https://arxiv.org/abs/2506.10910)

- **《Self-Training LLMs with Confident Reasoning》**  
  提出CORE-PO方法，基于推理路径置信度（而非答案正确性）筛选伪标签，提升分布外泛化能力。  
  [arXiv:2505.17454](https://arxiv.org/abs/2505.17454)

---

### 5. **多模态与低成本训练**
- **《LMM-R1: RL Framework for Vision-Language Models》**  
  东南大学开源的多模态强化学习框架，3B小模型通过规则化奖励函数超越100B+商业模型，训练成本仅百元级GPU。  
  [GitHub链接](https://github.com/PALM-ECNU/LMM-R1)（论文暂未公开）

- **《An Empirical Study on Eliciting R1-like Reasoning Models》**  
  九章云极团队复现R1推理模型，结合代码工具增强推理，AIME准确率达81.7%。  
  [arXiv:2503.04548](https://arxiv.org/abs/2503.04548)

---

### 其他推荐方向
- **《Scaling Laws for Neural Language Models》**（经典文献）  
  分析模型规模与性能的关系，指导训练资源配置[citation:无，可补充]。  
  [arXiv:2001.08361](https://arxiv.org/abs/2001.08361)

如需更细分领域（如稀疏训练、MoE架构）或具体论文解读，可进一步筛选。