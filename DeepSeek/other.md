以下是截至2025年5月的 **DeepSeek系列** 主要论文及其对应链接，涵盖基础架构、训练优化、推理增强等多个方向：  

### **一、基础架构与训练优化**  
1. **DeepSeek LLM**  
   - 标题：*DeepSeek LLM: Scaling Open-Source Language Models with Longtermism*  
   - 时间：2024年1月  
   - 链接：[arXiv:2401.02954](https://arxiv.org/abs/2401.02954)  
   - 突破：提出分组查询注意力（GQA）降低推理成本，优化学习率调度器提升训练效率。  

2. **DeepSeekMoE**  
   - 标题：*DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models*  
   - 时间：2024年1月  
   - 链接：[arXiv:2401.06066](https://arxiv.org/abs/2401.06066)  
   - 突破：细粒度专家分割与共享策略，MoE架构性能提升30%。  

3. **DeepSeek Math**  
   - 标题：*DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models*  
   - 时间：2024年2月  
   - 链接：[arXiv:2402.03300](https://arxiv.org/abs/2402.03300)  
   - 突破：提出组相对策略优化（GRPO），强化数学推理能力。  

4. **DeepSeek-V2**  
   - 标题：*DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model*  
   - 时间：2024年5月  
   - 链接：[arXiv:2405.04434](https://arxiv.org/abs/2405.04434)  
   - 突破：引入多头潜在注意力（MLA），KV缓存减少40%，训练成本降低50%。  

5. **DeepSeek-V3**  
   - 标题：*DeepSeek-V3 Technical Report*  
   - 时间：2024年12月（v1），2025年2月（v2）  
   - 链接：[arXiv:2412.19437](https://arxiv.org/abs/2412.19437)  
   - 突破：671B参数MoE模型，FP8混合精度训练，显存占用降低60%。  

---  

### **二、推理能力与强化学习**  
6. **DeepSeek-R1**  
   - 标题：*DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning*  
   - 时间：2025年1月  
   - 链接：[arXiv:2501.12948](https://arxiv.org/abs/2501.12948)  
   - 突破：多阶段强化学习增强逻辑推理能力，支持思维链（CoT）。  

7. **DeepSeek-R1 蒸馏模型**  
   - 标题：*Distilling Reasoning Capabilities from DeepSeek-R1 to Smaller Models*  
   - 时间：2025年1月  
   - 链接：[GitHub项目页](https://github.com/deepseek-ai/DeepSeek-R1)  
   - 突破：将R1推理能力迁移至轻量模型，数学推理准确率提升25%。  

8. **DeepSeek-Prover-V2**  
   - 标题：*DeepSeek-Prover-V2: Recursive Theorem Proving via Reinforcement Learning*  
   - 时间：2025年5月  
   - 链接：[GitHub](https://github.com/deepseek-ai/DeepSeek-Prover-V2) | [论文](https://github.com/deepseek-ai/DeepSeek-Prover-V2/blob/main/DeepSeek_Prover_V2.pdf)  
   - 突破：数学定理证明SOTA，MiniF2F-test通过率88.9%。  

---  

### **三、前沿探索与技术创新**  
9. **CODEI/O**  
   - 标题：*CODEI/O: Enhancing General Reasoning via Code Input/Output Prediction*  
   - 时间：2025年  
   - 链接：[GitHub](https://github.com/hkust-nlp/CodeIO)  
   - 突破：通过代码输入/输出预测增强通用推理能力。  

10. **DeepSeek-V3 软硬协同训练**  
   - 标题：*Insights into DeepSeek-V3: Challenges of Scale and Reflections on AI Architecture Hardware*  
   - 时间：2025年5月  
   - 链接：[arXiv:2505.09343](https://arxiv.org/abs/2505.09343)  
   - 突破：FP8训练、MLA优化、多平面网络架构，降低训练成本。  

---  

### **完整论文列表与开源资源**  
- **DeepSeek官方GitHub**：[https://github.com/deepseek-ai](https://github.com/deepseek-ai)  
- **DeepSeek系列论文汇总**：[CSDN博客](https://blog.csdn.net/weixin_44986037/article/details/148040771)  

如需更详细的论文内容或特定研究方向，可访问上述链接或DeepSeek的官方发布渠道。