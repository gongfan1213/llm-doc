以下是关于 **混合专家模型（Mixture of Experts, MoE）** 的最新论文推荐，涵盖从基础架构到前沿优化的多个方向，按由浅入深的顺序排列，确保内容不重复：

---

### **1. 基础架构与路由机制**
- **《OLMoE: Open Mixture-of-Experts Language Models》**  
  首个100%开源的MoE大模型，7B参数但仅激活1B参数，推理成本与1B密集模型相当，采用细粒度路由（64专家选8个）。  
  **[arXiv:2409.02060](https://arxiv.org/abs/2409.02060)**   

- **《DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models》**  
  提出专家拆分（增加专家数量）和共享专家（必选+可选）策略，1.89B参数性能媲美全参数密集模型。  
  **[arXiv:2401.06066](https://arxiv.org/abs/2401.06066)**   

- **《XMoE: Sparse Models with Fine-grained and Adaptive Expert Selection》**  
  结合细粒度专家拆分与动态阈值路由，优化计算效率，在相同计算量下性能提升显著。  
  **[arXiv:2403.18926](https://arxiv.org/abs/2403.18926)**   

---

### **2. 动态路由与自适应计算**
- **《Harder Tasks Need More Experts: Dynamic Routing in MoE Models》**  
  提出基于任务复杂度的动态路由，简单任务选1专家，复杂任务选多专家，提升效率。  
  **[arXiv:2403.07652](https://arxiv.org/abs/2403.07652)**   

- **《HyperMoE: Towards Better Mixture of Experts via Transferring Among Experts》**  
  利用未激活专家辅助激活专家，增强知识迁移，适用于异构任务分布。  
  **[arXiv:2402.12656](https://arxiv.org/abs/2402.12656)**   

---

### **3. 多模态与稀疏训练**
- **《MoE-LLaVA: Mixture of Experts for Large Vision-Language Models》**  
  首个稀疏多模态MoE架构，3B激活参数媲美LLaVA-7B，在物体幻觉基准超越LLaVA-13B。  
  **[arXiv:2401.15947](https://arxiv.org/abs/2401.15947)**   

- **《Awaker2.5-VL: Efficient Multi-Task MoE for Vision-Language Models》**  
  智子引擎开源的多模态MoE，采用LoRA-MoE架构缓解“多任务冲突”，在MME评测中领先。  
  **[arXiv:2411.10669](https://arxiv.org/abs/2411.10669)**   

---

### **4. 可微训练与高效预训练**
- **《Lory: Fully Differentiable MoE for Autoregressive Language Models》**  
  普林斯顿&Meta提出因果分段路由（Causal Segment Routing）和相似性批处理，训练效率提升2.5倍。  
  **[arXiv:2405.03133](https://arxiv.org/abs/2405.03133)**   

- **《Faster MoE LLM Inference for Extremely Large Models》**  
  分析细粒度MoE（如DeepSeek）的推理优化，探讨减少激活专家数对效率-性能的影响。  
  **[arXiv:2505.03531](https://arxiv.org/abs/2505.03531)**   

---

### **5. 强化学习与新兴应用**
- **《Mixture-of-Experts Meets In-Context Reinforcement Learning》**  
  提出T2MIR框架，结合Token-wise和Task-wise MoE，增强多模态RL任务的上下文学习能力。  
  **[arXiv:2506.05426](https://arxiv.org/abs/2506.05426)**   

---

### **经典奠基论文**
- **《Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer》**  
  Google Brain 2017年MoE奠基作，首次实现千倍模型容量提升，应用于LSTM语言模型。  
  **[arXiv:1701.06538](https://arxiv.org/abs/1701.06538)**   

---

### **推荐阅读顺序**  
1. 先读 **Google Brain奠基论文** → **OLMoE/DeepSeekMoE**（现代改进）→ **Lory/XMoE**（可微/动态路由）→ **MoE-LLaVA/Awaker2.5-VL**（多模态应用）。  
2. 对推理优化感兴趣可重点阅读 **Faster MoE LLM Inference**，强化学习方向参考 **T2MIR**。  

如需更细分方向（如 **专家剪枝、层级MoE**）或某篇论文的详细解读，可进一步筛选。