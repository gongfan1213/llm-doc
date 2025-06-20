以下是关于 **Agent 相关研究** 的补充论文列表，涵盖 **多智能体协作、任务规划、记忆机制、工具调用** 等方向，均提供 **arXiv 链接**，并按 **由浅入深** 排序，避免与之前内容重复：

---

### **1. 多智能体协作与优化**
1. **《AgentSynth: Scalable Task Generation for Generalist Computer-Use Agents》**  
   - **作者**：Jingxu Xie 等  
   - **arXiv**：[arXiv:2506.14205](https://arxiv.org/abs/2506.14205)  
   - **内容**：提出自动化合成复杂任务的流水线，通过子任务组合控制难度，生成 6,000+ 多样化任务，成本仅 0.6 美元/轨迹。  

2. **《Mass: Multi-Agent System Search via Optimized Prompts and Topologies》**  
   - **作者**：Google & 剑桥大学  
   - **arXiv**：[arXiv:2502.02533](https://arxiv.org/abs/2502.02533)  
   - **内容**：通过 **提示优化** 和 **拓扑优化** 提升多智能体系统性能，平均提升 10% 以上。  

3. **《Emergence of Scale-Free Networks in Social Interactions among Large Language Models》**  
   - **作者**：智源社区  
   - **arXiv**：[arXiv:2312.06619](https://arxiv.org/abs/2312.06619)  
   - **内容**：研究 LLM Agent 社交互动中 **无标度网络** 的涌现机制。  

---

### **2. 任务规划与工作流**
4. **《AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation》**  
   - **作者**：港大 & 微软  
   - **arXiv**：[arXiv:2408.00764](https://arxiv.org/abs/2408.00764)  
   - **内容**：通过 **自动生成多样化环境与任务** 提升 LLM 规划能力，8B 模型接近 GPT-4 水平。  

5. **《WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models》**  
   - **作者**：腾讯 AI Lab  
   - **arXiv**：[arXiv:2402.XXXXX](https://arxiv.org/abs/2402.XXXXX)（需补充完整编号）  
   - **内容**：多模态端到端 Agent，任务成功率 55.7%（远超 GPT-4 的 32.7%）。  

---

### **3. 记忆与知识增强**
6. **《AgentDistill: Training-Free Agent Distillation with Generalizable MCP Boxes》**  
   - **作者**：Jiahao Qiu 等  
   - **arXiv**：[arXiv:2506.14728](https://arxiv.org/abs/2506.14728)  
   - **内容**：通过 **可复用的任务解决模块（MCPs）** 实现无训练蒸馏，小模型性能媲美 GPT-4o。  

7. **《Advances and Challenges in Foundation Agents》**  
   - **作者**：MetaGPT & Mila 等 47 位学者  
   - **arXiv**：[arXiv:2504.01990](https://arxiv.org/abs/2504.01990)  
   - **内容**：264 页综述，定义 **基础智能体（Foundation Agent）** 的认知架构与自进化机制。  

---

### **4. 工具调用与执行**
8. **《AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation》**  
   - **作者**：微软研究院  
   - **arXiv**：[arXiv:2308.08155](https://arxiv.org/abs/2308.08155)  
   - **内容**：开源多 Agent 对话框架，支持工具调用、人工干预与动态工作流。  

---

### **完整资源**
- **Awesome-Agent-Papers**：[GitHub](https://github.com/FoundationAgents/awesome-foundation-agents)（持续更新的 Agent 论文库）  
- **工具库**：  
  - **AutoGen**：[GitHub](https://github.com/microsoft/autogen)（多 Agent 协作）  
  - **AgentSynth**：[代码库](https://github.com/simular-ai/Agent-S)（任务生成）  

如需更细分领域（如机器人控制、具身智能），可进一步筛选！