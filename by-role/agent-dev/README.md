# Agent 开发面经合集

> LLM Agent 开发面试经验整理，涵盖 Agent 架构、RAG、工具调用、多 Agent 系统等方向。

## 岗位方向细分

| 方向 | 高频考点 | 代表公司 |
| :--- | :--- | :--- |
| Agent 架构 | ReAct、Plan-Execute、Multi-Agent | 阿里巴巴、字节跳动、智谱 |
| RAG 系统 | Embedding、检索、重排、Chunk 策略 | 阿里巴巴、腾讯、百度 |
| 工具调用 | Function Calling、Tool Registry | 阿里巴巴、MiniMax |
| LLM 应用 | Prompt Engineering、LLM Ops | 月之暗面、零一万物 |

## 面经列表

| 公司 | 方向 | 轮次 | 亮点 | 链接 |
| :--- | :--- | :--- | :--- | :--- |
| 阿里巴巴 | Agent 架构 | 4轮技术+HR | RAG 优化+系统设计 | [查看](../../by-company/alibaba/agent-dev/) |
| 字节跳动 Agentkit | Agent Infra / Agent Runtime（27 秋招） | 技术面（轮次序号未提供） | Agent Loop / Harness / Memory / MCP / Sandbox + MySQL + LRU | [查看](../../by-company/bytedance/agent-dev/bytedance-agentkit-agent-engineer-27autumn.md) |

## 高频面试问题清单

### Agent 架构
- [ ] ReAct vs Function Calling
- [ ] Plan-and-Execute 范式
- [ ] Multi-Agent 通信机制
- [ ] Agent 记忆系统设计
- [ ] Agent 执行容错（超时、重试、降级）

### RAG 系统
- [ ] Chunk 策略选择（固定 vs 语义 vs 结构）
- [ ] Embedding 模型选型
- [ ] 混合检索（BM25 + 向量）
- [ ] Reranker 重排序
- [ ] 召回率优化案例
- [ ] GraphRAG / 多跳检索

### 工具调用
- [ ] Function Calling API 设计
- [ ] Tool Registry 架构
- [ ] 工具沙箱安全执行
- [ ] 参数提取与校验
- [ ] 工具编排（串行/并行/DAG）

### LLM 应用
- [ ] Prompt Engineering 最佳实践
- [ ] Few-shot vs Zero-shot
- [ ] CoT（Chain-of-Thought）
- [ ] LLM 评估方法
- [ ] 成本优化（模型路由、缓存）

### 生产部署
- [ ] 流式输出实现
- [ ] 多租户隔离
- [ ] 限流与背压
- [ ] 审计日志
- [ ] P99 延迟优化

---

> 📌 欢迎投稿你的 Agent 开发面经！请使用 [面经模板](../../templates/interview-template.md) 提交 PR。
