以下是关于 **多智能体开发（Multi-Agent Development）** 的补充论文列表，涵盖 **协作优化、动态架构、具身智能** 等方向，均提供 **arXiv 链接**，并按 **由浅入深** 排序，避免与之前内容重复：

---

### **1. 协作优化与任务分解**
1. **《Xolver: Multi-Agent Reasoning with Holistic Experience Learning》**  
   - **作者**：Md Tanzib Hosain 等  
   - **arXiv**：[arXiv:2506.14234](https://arxiv.org/abs/2506.14234)  
   - **内容**：提出 **Xolver** 框架，通过 **经验记忆库**（策略/代码片段/推理模式）实现多智能体动态协作，在数学推理（GSM8K 98.1%）和编程（LiveCodeBench-V5 91.6%）任务中超越 GPT-4o 和 Gemini 2.5 Pro。  

2. **《PARCO: Learning Parallel Autoregressive Policies for Multi-Agent Combinatorial Optimization》**  
   - **作者**：Federico Berto 等  
   - **arXiv**：[arXiv:2409.05072](https://arxiv.org/abs/2409.05072)  
   - **内容**：通过 **并行自回归解码** 和 **多指针机制** 解决路由/调度等组合优化问题，支持冲突处理与动态通信。  

---

### **2. 动态架构与自适应协作**
3. **《MaAS: Multi-agent Architecture Search via Agentic Supernet》**  
   - **作者**：新加坡国立大学  
   - **arXiv**：[arXiv:2502.04180](https://arxiv.org/abs/2502.04180)  
   - **内容**：构建 **智能体超网**（Agentic Supernet），根据任务复杂度动态采样最优工作流（如简单任务用 ReAct+Early-Exit，复杂任务用 Debate+Refine），推理成本仅为 AFlow 的 25%。  

4. **《Workforce: Modular Multi-Agent Framework for Cross-Domain Task Automation》**  
   - **作者**：港大 & camel-ai  
   - **arXiv**：[arXiv:2505.23885](https://arxiv.org/abs/2505.23885)  
   - **内容**：提出 **解耦设计**（Planner/Coordinator/Worker Nodes），仅需替换工作节点即可跨领域迁移，在 GAIA 基准上准确率 69.7%（超越 OpenAI Deep Research）。  

---

### **3. 具身智能与视觉推理**
5. **《VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning》**  
   - **作者**：Li Kang 等  
   - **arXiv**：[arXiv:2506.09049](https://arxiv.org/abs/2506.09049)  
   - **内容**：结合 **视觉语言模型（VLM）** 与强化学习，在 VIKI-Bench（20k 多智能体任务）中优化 **Agent Activation**、**Task Planning** 和 **Trajectory Perception** 三层级协作。  

6. **《AgentVerse: Simulating Human Group Dynamics for Multi-Agent Collaboration》**  
   - **作者**：清华 & 腾讯  
   - **arXiv**：[arXiv:2308.10848](https://arxiv.org/abs/2308.10848)  
   - **内容**：仿人类群体动力学设计 **专家招募→协作决策→行动执行→评估** 四阶段框架，在 Minecraft 物品制作中涌现自适应协作行为。  

---

### **4. 前沿挑战与优化**
7. **《Advancing Multi-Agent Systems Through Model Context Protocol》**  
   - **作者**：Naveen Krishnan  
   - **arXiv**：[arXiv:2504.21030](https://arxiv.org/abs/2504.21030)  
   - **内容**：提出 **模型上下文协议（MCP）**，通过标准化上下文共享提升多智能体系统的可扩展性，应用于企业知识管理等领域。  

8. **《Emergence of Scale-Free Networks in LLM-Based Social Interactions》**  
   - **作者**：智源社区  
   - **arXiv**：[arXiv:2312.06619](https://arxiv.org/abs/2312.06619)  
   - **内容**：研究 LLM 智能体社交互动中 **无标度网络** 的涌现机制，揭示协作模式的底层动力学。  

---

### **完整资源**
- **Awesome-Multi-Agent-Papers**：[GitHub](https://github.com/FoundationAgents/awesome-foundation-agents)（持续更新的多智能体论文库）  
- **工具库**：  
  - **MaAS**：[代码](https://github.com/bingreeky/MaAS)（动态架构搜索）  
  - **Workforce**：[代码](https://github.com/camel-ai/owl)（模块化跨领域框架）  

如需更细分领域（如博弈论、分布式控制），可进一步筛选！