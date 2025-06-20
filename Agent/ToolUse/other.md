以下是关于 **Agent 工具调用（Tool Use）** 的论文列表，按照 **由浅入深** 的顺序整理，涵盖基础理论、优化方法、多工具集成及前沿研究，均提供 **arXiv 链接**：

---

### **1. 基础理论与经典框架**
1. **《ReAct: Synergizing Reasoning and Acting in Language Models》**  
   - **作者**：Yao et al. (Meta AI)  
   - **arXiv**：[arXiv:2210.03629](https://arxiv.org/abs/2210.03629)  
   - **内容**：提出 **ReAct 框架**，结合推理（Reasoning）与工具调用（Acting），成为 Agent 工具调用的基础范式。

2. **《Toolformer: Language Models Can Teach Themselves to Use Tools》**  
   - **作者**：Meta AI  
   - **arXiv**：[arXiv:2302.04761](https://arxiv.org/abs/2302.04761)  
   - **内容**：让 LLM 自动学习工具调用，无需人工标注数据。

3. **《Gorilla: Large Language Model Connected with Massive APIs》**  
   - **作者**：UC Berkeley  
   - **arXiv**：[arXiv:2305.15334](https://arxiv.org/abs/2305.15334)  
   - **内容**：支持 LLM 调用海量 API，解决工具幻觉问题。

---

### **2. 检索增强与多工具集成**
4. **《Corrective-RAG: Self-Refining Retrieval-Augmented Generation》**  
   - **arXiv**：[arXiv:2401.15884](https://arxiv.org/abs/2401.15884)  
   - **内容**：通过自纠正机制优化工具调用与检索的协同。

5. **《DoTA-RAG: Dynamic of Thought Aggregation RAG》**  
   - **arXiv**：[arXiv:2406.12571](https://arxiv.org/abs/2406.12571)  
   - **内容**：动态路由检索，提升多工具调用的效率。

6. **《HiPerRAG: High-Performance Retrieval Augmented Generation for Scientific Insights》**  
   - **arXiv**：[arXiv:2505.04846](https://arxiv.org/abs/2505.04846)  
   - **内容**：面向科学文献的百万级文档 RAG，优化工具调用准确性。

---

### **3. 多模态与复杂任务规划**
7. **《AR-RAG: Autoregressive Retrieval Augmentation for Image Generation》**  
   - **arXiv**：[arXiv:2506.06962](https://arxiv.org/abs/2506.06962)  
   - **内容**：图像生成的动态块级检索增强，扩展工具调用至多模态领域。

8. **《AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation》**  
   - **arXiv**：[arXiv:2408.00764](https://arxiv.org/abs/2408.00764)  
   - **内容**：通过自动生成任务提升 Agent 的规划与工具调用能力。

---

### **4. 前沿优化与挑战**
9. **《Self-Rewarding RAG: Autonomous Fine-Tuning via Reinforcement Learning》**  
   - **arXiv**：[arXiv:2401.10020](https://arxiv.org/abs/2401.10020)  
   - **内容**：通过强化学习自我优化工具调用策略。

10. **《AFlow: Automating Agentic Workflow Generation》**  
    - **arXiv**：[arXiv:2410.10762](https://arxiv.org/abs/2410.10762)  
    - **内容**：利用蒙特卡洛树搜索（MCTS）自动生成工具调用工作流。

---

### **完整资源**
- **Awesome-Tool-Use-Papers**：[GitHub](https://github.com/BradyFU/Awesome-MultiTool-Agent-Papers)（持续更新的工具调用论文列表）  
- **LangChain Tools 文档**：[官方指南](https://python.langchain.com/docs/modules/agents/tools/)（实战工具集成方法）  

如需更详细的分类（如医疗、金融领域工具调用），可进一步筛选！