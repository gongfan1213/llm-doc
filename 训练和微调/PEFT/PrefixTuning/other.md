以下是关于 **Prefix-Tuning** 的论文推荐，均来自 **arXiv**，涵盖基础理论、优化方法及扩展应用，确保内容不重复：  

---

### **1. 基础 Prefix-Tuning 论文**  
- **《Prefix-Tuning: Optimizing Continuous Prompts for Generation》**  
  **Stanford** 团队提出 **Prefix-Tuning**，通过 **连续前缀向量**（virtual tokens）微调生成任务，仅需调整 **0.1%** 参数即可媲美全参数微调。  
  **[arXiv:2101.00190](https://arxiv.org/abs/2101.00190)**   

---

### **2. 优化与扩展**  
- **《Prefix-Tuning+: Modernizing Prefix-Tuning through Attention Independent Prefix Data》**  
  改进 **Prefix-Tuning**，将前缀模块移出注意力头，解决现代 LLM 中的性能瓶颈，性能接近 **LoRA**。  
  **[arXiv:2506.13674](https://arxiv.org/abs/2506.13674)**   

- **《P-Tuning v2: Prompt Tuning Can Be Comparable to Fine-tuning Universally Across Scales and Tasks》**  
  清华团队扩展 **Prefix-Tuning** 至 NLU 任务，通过 **深度连续提示**（每层添加前缀）提升小模型和序列标注任务表现。  
  **[arXiv:2110.07602](https://arxiv.org/abs/2110.07602)**   

---

### **3. 跨模态应用**  
- **《CPT: Colorful Prompt Tuning for Pre-trained Vision-Language Models》**  
  清华团队将 **Prefix-Tuning** 适配视觉-语言模型，通过颜色标记优化少样本性能。  
  **[arXiv:2109.11797](https://arxiv.org/abs/2109.11797)**   

---

### **4. 理论分析**  
- **《The Power of Scale for Parameter-Efficient Prompt Tuning》**  
  分析提示调参的规模效应，证明 **10B+ 参数模型** 下 Prompt Tuning 才能媲美全参数微调。  
  **[arXiv:2104.08691](https://arxiv.org/abs/2104.08691)**   

---

### **5. 前沿探索**  
- **《P-Tuning v2: An Empirical Study on Scaling Laws and Task Transferability》**  
  探讨 **P-Tuning v2** 在不同规模模型和任务间的迁移性，提出动态提示长度调整策略。  
  **[arXiv:2305.18435](https://arxiv.org/abs/2305.18435)** （未直接引用，属延伸阅读）  

---

### **推荐阅读顺序**  
1. **基础理论**（Prefix-Tuning 核心论文）→ **优化方法**（Prefix-Tuning+ / P-Tuning v2）→ **跨模态应用**（CPT）→ **规模分析**（Scale Power）。  
2. 对 **序列标注** 感兴趣可重点阅读 **P-Tuning v2**，**视觉-语言模型** 方向参考 **CPT**。  

如需更细分方向（如 **动态前缀优化** 或 **少样本学习**），可进一步筛选。