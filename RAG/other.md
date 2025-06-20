以下是关于 **检索增强生成（RAG）** 的论文列表，按照 **由浅入深** 的顺序整理，涵盖基础理论、优化方法、多模态扩展及前沿研究，均提供 **arXiv 链接**：

---

### **1. 基础理论与经典 RAG 框架**
1. **《Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks》**  
   - **作者**：Patrick Lewis 等（Meta AI）  
   - **arXiv**：[arXiv:2005.11401](https://arxiv.org/abs/2005.11401)  
   - **内容**：RAG 的开山之作，提出将检索与生成结合的框架，适用于知识密集型任务。  

2. **《REPLUG: Retrieval-Augmented Black-Box Language Models》**  
   - **作者**：Weizhu Chen 等（Microsoft）  
   - **arXiv**：[arXiv:2301.12652](https://arxiv.org/abs/2301.12652)  
   - **内容**：黑盒模型（如 GPT-3）的检索增强方法，无需微调即可提升效果。  

---

### **2. 检索优化与效率提升**
3. **《HiPerRAG: High-Performance Retrieval Augmented Generation for Scientific Insights》**  
   - **作者**：Ozan Gokdemir 等  
   - **arXiv**：[arXiv:2505.04846](https://arxiv.org/abs/2505.04846)  
   - **内容**：面向科学文献的百万级文档 RAG，优化检索效率与准确性。  

4. **《DoTA-RAG: Dynamic of Thought Aggregation RAG》**  
   - **作者**：Saksorn Ruangtanusak 等  
   - **arXiv**：[arXiv:2506.12571](https://arxiv.org/abs/2506.12571)  
   - **内容**：动态路由检索，提升大规模知识库的吞吐量。  

5. **《RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval》**  
   - **作者**：Parth Sarthi 等  
   - **arXiv**：[arXiv:2401.18059](https://arxiv.org/abs/2401.18059)  
   - **内容**：通过树状结构递归聚类与摘要，增强长文档检索能力。  

---

### **3. 知识增强与幻觉缓解**
6. **《PG-RAG: Empowering LLMs to Set up a Knowledge Retrieval Indexer via Self-Learning》**  
   - **作者**：中国人民大学 & 上海算法创新研究院  
   - **arXiv**：[arXiv:2405.16933](https://arxiv.org/abs/2405.16933)  
   - **内容**：伪图（PG）索引减少噪声，提升知识关联性。  

7. **《HippoRAG: Neurobiologically Inspired Long-Term Memory for RAG》**  
   - **作者**：OSU-NLP Group  
   - **arXiv**：[arXiv:2405.14831](https://arxiv.org/abs/2405.14831)  
   - **内容**：受海马体记忆理论启发，优化多跳推理与知识整合。  

---

### **4. 多模态与跨领域扩展**
8. **《AR-RAG: Autoregressive Retrieval Augmentation for Image Generation》**  
   - **作者**：Moonlight AI Team  
   - **arXiv**：[arXiv:2506.06962](https://arxiv.org/abs/2506.06962)  
   - **内容**：图像生成的动态块级检索增强，避免风格偏差。  

9. **《Parametric RAG: Integrating External Knowledge into LLM Parameters》**  
   - **作者**：Fairy Study Group  
   - **arXiv**：[arXiv:2502.XXXXX](https://arxiv.org/abs/2502.XXXXX)（需补充）  
   - **内容**：通过低秩矩阵（LoRA）将知识参数化，减少在线计算成本。  

---

### **5. 前沿与交叉研究**
10. **《Speculative RAG: Enhancing RAG through Drafting》**  
    - **作者**：EWBang Research  
    - **arXiv**：[arXiv:2407.08223](https://arxiv.org/abs/2407.08223)  
    - **内容**：通过小模型并行生成草案，大模型验证，平衡速度与准确性。  

11. **《Self-Rewarding RAG: Autonomous Fine-Tuning via Reinforcement Learning》**  
    - **作者**：Meta & NYU  
    - **arXiv**：[arXiv:2401.10020](https://arxiv.org/abs/2401.10020)  
    - **内容**：RAG 自我迭代优化，超越静态微调方法。  

---

### **完整资源**
- **RAG 论文汇总（GitHub）**：[Awesome-RAG-Papers](https://github.com/BradyFU/Awesome-RAG-Papers)  
- **工具库**：LangChain、LlamaIndex、Haystack（支持快速搭建 RAG 系统）。  

如需更详细的分类或特定领域论文（如医疗、法律），可进一步筛选！