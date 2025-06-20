以下是关于 **参数高效微调（Parameter-Efficient Fine-Tuning, PEFT）** 的最新论文推荐，涵盖从基础方法到前沿优化的多个方向，按由浅入深的顺序排列，确保内容不重复：

---

### **1. 基础PEFT方法与理论**
- **《Prefix-Tuning+: Modernizing Prefix-Tuning through Attention Independent Prefix Data》**  
  提出改进版的Prefix-Tuning，通过将前缀模块移出注意力头，解决了传统Prefix-Tuning在现代LLMs上的性能瓶颈，实验表明其性能与LoRA相当。  
  **[arXiv:2506.13674](https://arxiv.org/abs/2506.13674)**   

- **《InfLoRA: Interference-Free Low-Rank Adaptation for Continual Learning》**  
  针对持续学习任务，提出InfLoRA方法，通过低秩自适应（LoRA）优化，减少新任务对旧任务的干扰，提升模型稳定性与可塑性。  
  **[arXiv:2404.02002](https://arxiv.org/abs/2404.02002)**   

- **《AFLoRA: Adaptive Freezing of Low Rank Adaptation》**  
  提出自适应冻结LoRA路径的方法，减少计算量并缓解过拟合，在GLUE基准上实现SOTA性能。  
  **[arXiv:2403.13269](https://arxiv.org/abs/2403.13269)**   

---

### **2. 新型PEFT架构与优化**
- **《Parameter-Efficient Fine-Tuning with Discrete Fourier Transform》**  
  提出傅立叶微调方法，利用频域稀疏性大幅减少可训练参数（仅为LoRA的1/10~1/1000），在NLP和CV任务上表现优异。  
  **[arXiv:2405.03003](https://arxiv.org/abs/2405.03003)**   

- **《PERU: Parameter-Efficient Reusing Fine-Tuned Models》**  
  提出训练无关的模型复用方法，通过稀疏任务向量（PERU-FFT）和低秩近似（PERU-LoRA）高效整合多个微调模型。  
  **[arXiv:2310.01886](https://arxiv.org/abs/2310.01886)**   

---

### **3. 领域特定PEFT应用**
- **《Delving into PEFT in Code Change Learning: An Empirical Study》**  
  实证研究PEFT在代码变更任务（如缺陷预测、提交信息生成）中的表现，发现Adapter Tuning和LoRA优于全参数微调。  
  **[arXiv:2402.06247](https://arxiv.org/abs/2402.06247)**   

- **《PEFT: Parameter-Efficient Fine-Tuning on Billion-Scale Models with Low-Resource Hardware》**  
  Hugging Face PEFT库的技术报告，展示如何在消费级GPU（如RTX 3080）上微调十亿级模型（如T5、OPT）。  
  **[Hugging Face Blog](https://hf.co/blog/peft)**   

---

### **4. 前沿综述与未来方向**
- **《面向基础模型的高效参数微调》综述**  
  全面梳理PEFT技术，涵盖LLM、VLM、VFM等基础模型，分析五大PEFT类别（选择性/加法/提示/重参数化/混合）及未来趋势。  
  **[GitHub资源库](https://github.com/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models)**   

---

### **推荐阅读顺序**  
1. **基础方法**（Prefix-Tuning+/InfLoRA）→ **架构创新**（傅立叶微调/PERU）→ **领域应用**（代码学习/低资源硬件）→ **综述展望**。  
2. 对持续学习感兴趣可重点阅读 **InfLoRA**，低资源场景参考 **Hugging Face PEFT库**。  

如需更细分方向（如 **多模态PEFT** 或 **动态稀疏化**），可进一步筛选。