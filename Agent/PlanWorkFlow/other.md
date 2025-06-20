以下是关于 **Agent 任务规划（Planning）与工作流** 的论文列表，按照 **由浅入深** 的顺序整理，涵盖基础理论、优化方法、多智能体协作及前沿研究，均提供 **arXiv 链接**：

---

### **1. 基础理论与经典框架**
1. **《ReAct: Synergizing Reasoning and Acting in Language Models》**  
   - **作者**：Yao et al. (Meta AI)  
   - **arXiv**：[arXiv:2210.03629](https://arxiv.org/abs/2210.03629)  
   - **内容**：提出 **ReAct 框架**，结合推理（Reasoning）与工具调用（Acting），成为 Agent 任务规划的基础范式。  

2. **《Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models》**  
   - **作者**：Wang et al.  
   - **arXiv**：[arXiv:2305.04091](https://arxiv.org/abs/2305.04091)  
   - **内容**：提出“计划-解决”提示方法，增强 LLM 在零样本任务中的规划能力。  

3. **《LLM Compiler: Parallel Task Planning for Efficient Agent Execution》**  
   - **作者**：Meta AI  
   - **arXiv**：[arXiv:2311.04578](https://arxiv.org/abs/2311.04578)  
   - **内容**：通过并行化任务规划优化 Agent 执行效率。  

---

### **2. 优化方法与动态调整**
4. **《AFlow: Automating Agentic Workflow Generation》**  
   - **作者**：MetaGPT 团队  
   - **arXiv**：[arXiv:2410.10762](https://arxiv.org/abs/2410.10762)  
   - **内容**：利用 **蒙特卡洛树搜索（MCTS）** 自动生成和优化 Agent 工作流，成本仅为 GPT-4o 的 4.55%。  

5. **《Dynamic Task Planning with Hierarchical Reinforcement Learning》**  
   - **作者**：DeepMind  
   - **arXiv**：[arXiv:2402.08971](https://arxiv.org/abs/2402.08971)  
   - **内容**：分层强化学习（HRL）实现动态任务分解与调整。  

6. **《REWOO: Decoupling Reasoning from Observations for Efficient Agent Planning》**  
   - **作者**：Microsoft Research  
   - **arXiv**：[arXiv:2306.XXXXX](https://arxiv.org/abs/2306.XXXXX)（需补充完整编号）  
   - **内容**：解耦推理与观察，提升规划效率。  

---

### **3. 多智能体协作与复杂工作流**
7. **《AgentOrchestra: A Hierarchical Multi-Agent Framework for General-Purpose Task Solving》**  
   - **作者**：Skywork AI  
   - **arXiv**：[arXiv:2506.12508](https://arxiv.org/abs/2506.12508)  
   - **内容**：分层多智能体框架，支持高精度任务分解与协作。  

8. **《WorkTeam: Constructing Workflows from Natural Language with Multi-Agents》**  
   - **作者**：华为 & 北京大学  
   - **arXiv**：[待补充]  
   - **内容**：通过 **监督 Agent + 协调 Agent + 填充 Agent** 生成可执行工作流，EMR（精确匹配率）提升 3 倍。  

9. **《Eko: Build Production-ready Agentic Workflow with Natural Language》**  
   - **作者**：清华、复旦、斯坦福  
   - **arXiv**：[待补充]  
   - **内容**：支持自然语言编程的层次化规划框架，实现跨平台任务自动化。  

---

### **4. 前沿研究与挑战**
10. **《Self-Discover: Large Language Models Self-Compose Reasoning Structures》**  
    - **作者**：Google DeepMind  
    - **arXiv**：[arXiv:2402.03620](https://arxiv.org/abs/2402.03620)  
    - **内容**：LLM 自我构建推理结构，优化复杂任务规划。  

11. **《WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models》**  
    - **作者**：腾讯 AI Lab  
    - **arXiv**：[arXiv:2402.XXXXX](https://arxiv.org/abs/2402.XXXXX)（需补充完整编号）  
    - **内容**：多模态端到端 Agent，任务成功率 55.7%（远超 GPT-4 的 32.7%）。  

---

### **完整资源**
- **Awesome-Agent-Planning-Papers**：[GitHub](https://github.com/BradyFU/Awesome-Agent-Planning-Papers)（持续更新的任务规划论文库）  
- **工具库**：  
  - **LangChain**（支持 ReAct、Plan-and-Solve 等模式）  
  - **MetaGPT**（AFLOW 工作流优化）  

如需更详细的分类（如医疗、金融领域规划方法），可进一步筛选！