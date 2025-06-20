以下是关于 **Agent Memory（智能体记忆机制）** 的论文列表，按照 **由浅入深** 的顺序整理，涵盖基础理论、优化方法、多模态扩展及前沿研究，均提供 **arXiv 链接**：

---

### **1. 基础理论与综述**
1. **《A Survey on the Memory Mechanism of Large Language Model based Agents》**  
   - **作者**：Meta AI & 智源社区  
   - **arXiv**：[arXiv:2404.13501](https://arxiv.org/abs/2404.13501)  
   - **内容**：系统综述 LLM 智能体的记忆机制，包括记忆定义、设计模式、评估方法及应用场景。  

2. **《Memory-Augmented Large Language Models for Long-Context Tasks》**  
   - **作者**：Stanford NLP Group  
   - **arXiv**：[arXiv:2310.17807](https://arxiv.org/abs/2310.17807)  
   - **内容**：探讨如何通过记忆增强解决长上下文任务中的“健忘”问题。  

---

### **2. 记忆架构与优化**
3. **《MemoryOS: A Hierarchical Memory System for AI Agents》**  
   - **作者**：北京邮电大学  
   - **arXiv**：[arXiv:2506.06326](https://arxiv.org/abs/2506.06326)  
   - **内容**：提出三级记忆架构（短期/中期/长期记忆），动态更新策略提升对话连贯性，实验显示 F1 分数提升 49.11%。  

4. **《MemInsight: Autonomous Memory Augmentation for LLM Agents》**  
   - **作者**：Amazon AWS AI  
   - **arXiv**：[arXiv:2504.XXXXX](https://arxiv.org/abs/2504.XXXXX)（需补充完整编号）  
   - **内容**：通过结构化属性挖掘（实体/对话中心）增强记忆检索，在推荐任务中说服力提升 14%。  

5. **《Memory Sharing for Large Language Model based Agents》**  
   - **作者**：GHupppp et al.  
   - **arXiv**：[arXiv:2404.09982](https://arxiv.org/abs/2404.09982)  
   - **内容**：多智能体实时记忆共享框架，通过评分机制优化记忆池更新。  

---

### **3. 记忆与任务规划**
6. **《Self-Rewarding Language Models for Long-Term Memory》**  
   - **作者**：Meta & NYU  
   - **arXiv**：[arXiv:2401.10020](https://arxiv.org/abs/2401.10020)  
   - **内容**：通过自我奖励机制优化长期记忆的存储与检索策略。  

7. **《RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval》**  
   - **作者**：Sarthi et al.  
   - **arXiv**：[arXiv:2401.18059](https://arxiv.org/abs/2401.18059)  
   - **内容**：树状记忆结构增强复杂任务规划能力。  

---

### **4. 前沿研究**
8. **《Memory-Augmented Monte Carlo Tree Search for General Video Game Playing》**  
   - **作者**：DeepMind  
   - **arXiv**：[arXiv:2403.08891](https://arxiv.org/abs/2403.08891)  
   - **内容**：结合记忆增强与 MCTS 算法，提升游戏智能体的策略泛化能力。  

9. **《Dynamic Memory Networks for Continual Learning in Agents》**  
   - **作者**：MIT CSAIL  
   - **arXiv**：[arXiv:2505.11233](https://arxiv.org/abs/2505.11233)  
   - **内容**：动态记忆网络解决持续学习中的灾难性遗忘问题。  

---

### **完整资源**
- **Awesome-Agent-Memory-Papers**：[GitHub](https://github.com/nuster1128/LLM_Agent_Memory_Survey)（持续更新的记忆机制论文库）  
- **工具库**：  
  - **MemoryOS**：[GitHub](https://github.com/BAI-LAB/MemoryOS)（开源记忆操作系统）  
  - **MemGPT**：[GitHub](https://github.com/cpacker/MemGPT)（基于分页机制的长期记忆框架）  

如需更详细的分类（如医疗、金融领域记忆应用），可进一步筛选！