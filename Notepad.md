
# 阵麦算法

| 算法 | CH1 侧 | CH4 侧 |
|---|---:|---:|
| AuxIVA（上次结果的基线） | +6.27 dB | +6.26 dB |
| ILRMA | +6.38 dB | +7.03 dB |
| 空间掩膜 + MVDR 波束形成 | +8.81 dB | +10.62 dB |
| **空间维纳滤波** | **+9.02 dB** | **+10.80 dB** |



# 
## Moshi
[https://github.com/kyutai-labs/moshi](https://github.com/kyutai-labs/moshi)

## Sophon-Realtime 4B／32B
[https://github.com/adventists-ai](https://github.com/adventists-ai)


# Duplex 

# AI 领域的 Plural Intelligence / 复数智能

AI 领域里的 **Plural Intelligence / 复数智能**，可以理解为：不再追求“一个超级模型解决所有问题”，而是让**多个不同规模、不同专长、能持续自我改进的智能系统协同工作**。

---

## 一、技术架构：从“单模型”到“智能生态”

可以把 Plural Intelligence 拆成五层来看：

| 层级 | 作用 | 关键能力 |
| --- | --- | --- |
| 智能体层 | 多个专业 Agent | 规划、执行、评审、路由、安全审计等角色分工 |
| 协作层 | 智能体之间通信与分工 | 消息传递、黑板共享、A2A / MCP 等互操作协议 |
| 编排层 | 任务拆解与调度 | 将目标拆成子任务，路由给最合适模型或工具 |
| 自进化层 | 在生产环境中持续改进 | 从任务结果、失败、纠正中学习，优化指令、工具、模型选择 |
| 治理层 | 安全、权限、审计 | 身份认证、工具访问控制、审批流、可观测性 |

它的核心逻辑是：**不同任务用不同模型，不同角色由不同智能体承担，复杂流程由编排层调度，系统还能在真实工作中自我优化。**

---

## 二、代表架构模式

| 架构模式 | 特点 | 代表 |
| --- | --- | --- |
| 指挥官-工人 | 一个主智能体拆解任务，多个专业智能体执行 | LangGraph、CrewAI、Anthropic Subagent |
| 对话协作 | 多个智能体通过对话协商、纠错 | Microsoft AutoGen |
| 工作流 / 图式编排 | 用状态图定义任务流转，可分支、循环、重试 | LangGraph |
| 混合专家聚合 | 多个 Agent 并行生成，再由聚合器融合结果 | Mixture-of-Agents |
| 因子化智能体 | 把记忆、规划、工具调用、反思拆成独立模块 | Factored Agents |
| 跨系统互操作 | 不同平台、不同供应商的 Agent 互相协作 | Google A2A、Anthropic MCP |

---

## 三、代表项目与模型

| 代表项目 | 定位 | 与 Plural Intelligence 的关系 |
| --- | --- | --- |
| Noeri | 2026 年 11 月发布的 AI 实验室 | 明确提出 Plural Intelligence，主张企业用自身数据构建可自改进的专属 AI |
| Microsoft AutoGen | 多智能体协作框架 | 多个 LLM 智能体通过对话协作完成任务 |
| LangGraph / LangChain | 智能体工作流编排 | 把多智能体协作做成可控、可调试的生产级流程 |
| Anthropic Claude Subagent | 主智能体调度子智能体 | 典型指挥官-工人模式 |
| Google A2A | 智能体互操作协议 | 让不同平台的智能体跨系统通信 |
| Mixture-of-Agents | 多模型并行 + 结果聚合 | 通过群体协作提升单模型能力上限 |

---

## 四、和加德纳“多元智能”的区别

- **Multiple Intelligences / 多元智能**：讲人的能力类型，如语言、音乐、逻辑、人际等。
- **Plural Intelligence / 复数智能**：讲 AI 系统形态，强调智能应由多个模型、多个智能体、多种工具共同构成。

---
