# roadmap · Java 程序员 AI 转型路线图

> 配套文章：篇1《干了 13 年 Java，AI 时代我不是被淘汰，而是被重新定价》
>
> 🎉 **「Java AI 实战派」系列 10 篇已全部完结**（2026-09），8 个配套开源仓库已上线，系列导航见文末。
>
> 这是一份**可执行**的路线图，不是鸡汤——每个阶段都有明确的「产出物」和「自检标准」。

---

## 一、你是谁，从哪里开始

| 画像 | 推荐方向 | 建议路径 |
|---|---|---|
| 1–5 年 Java 后端 | 方向 1（Spring AI 应用开发） | 90 天标准路径 |
| 5–10 年 Java 老兵 / Leader | 方向 4（AI 平台架构） | 侧重选型 + 架构 + 成本 |
| 想做副业的 Javaer | 方向 6（AI 副业） | 主业先行，先攒作品集 |
| 应届毕业生 | 方向 1 或 2 | 用 AI 项目做简历差异化 |
| 对安全感兴趣 | 方向 5（AI 安全） | 稀缺赛道，竞争少 |

---

## 二、六大转型方向

### 方向 1：Spring AI 应用开发工程师

- **目标岗位**：Java AI 应用开发 / AI 业务后端
- **核心技能**：Spring AI 2.0、ChatClient、ChatMemory、Function Calling、MCP
- **学习路径**：官方 quickstart → 企业级 ChatClient → 多模型接入 → 生产三件套（埋点/限流/安全）
- **产出物**：一个能跑的企业级 AI 服务（含 SSE 流式 + 多模型切换 + 限流降级）
- **薪资预期**：base +20%~40%

### 方向 2：RAG 工程师

- **目标岗位**：知识库 / 企业搜索方向 AI 工程师
- **核心技能**：文档解析、切片策略、Embedding 选型、混合检索、Rerank、评估体系
- **学习路径**：pgvector / Milvus → 切片与召回 → 混合检索 → Rerank → 用测试集量化效果
- **产出物**：一个准确率可量化的知识库问答系统（带评估脚本）
- **薪资预期**：base +25%~45%

### 方向 3：Agent 工程师

- **目标岗位**：Agent 平台开发 / 智能体工程师
- **核心技能**：ReAct / Plan-and-Execute、Multi-Agent 编排、MCP、A2A
- **学习路径**：单 Agent → 工具编排 → 多 Agent 协同 → 生产级稳定性（断点续跑/上下文管理）
- **产出物**：一个 4 Agent 协同的业务 Agent（Planner / Executor / Reviewer / Summarizer）
- **薪资预期**：base +30%~50%

### 方向 4：AI 平台架构师

- **目标岗位**：AI 中台 / AI 平台架构
- **核心技能**：多模型路由、AI 网关、可观测体系、Token FinOps、降级容灾
- **学习路径**：网关选型 → 路由策略 → 可观测（Trace/成本看板） → 成本优化
- **产出物**：一份 AI 平台架构方案 + 可用的多模型路由 Demo
- **薪资预期**：base +35%~60%

### 方向 5：AI 安全工程师

- **目标岗位**：AI 应用安全 / 合规
- **核心技能**：Prompt 注入防护、工具越权防护、内容审核、数据合规
- **学习路径**：攻击面分析 → 四层防御体系 → 红蓝对抗 → 合规审计
- **产出物**：30 条 AI 应用安全自查清单 + 一个防御中间件
- **薪资预期**：base +25%~50%（稀缺方向，企业刚需）

### 方向 6：AI 副业 / 独立开发者

- **目标**：副业月入 1w–4w（第 4 个月起）
- **路径**：作品集（GitHub + 公众号）→ 接外包 → 咨询 / 内训 → 课程 / 社群
- **产出物**：6 个开源项目 + 10 篇技术文章 + 第一单
- **时间投入**：主业为主，每周 10–15 小时
- **预期管理**：前 3 个月基本无收入是正常现象

---

## 三、90 天行动计划

### Day 1–30：打基础（每天 1–2 小时）

- [ ] 跑通 Spring AI 官方全部 quickstart
- [ ] 读完篇 1–篇 3 文章 + 对应仓库代码（framework-compare）
- [ ] 完成一个「多轮对话 + 工具调用」Demo
- [ ] 在 GitHub 开出自己的 AI 仓库（哪怕只有 README）

> **30 天自检**：你能向别人讲清楚 ChatClient / ChatMemory / Tool 是什么吗？

### Day 31–60：做项目（每天 2–3 小时）

- [ ] 选定 1 个方向，做一个完整项目（客服 / RAG / Agent 任选）
- [ ] 项目带 docker-compose 一键启动 + 中英双语 README
- [ ] 写 2–3 篇实践文章（公众号 / 掘金 / CSDN 同步分发）
- [ ] 把简历改造成「Java AI 应用开发工程师」

> **60 天自检**：你有 1 个拿得出手的项目 + 2 篇文章了吗？

### Day 61–90：变现 / 求职（每天 2–3 小时）

- [ ] 面试 3–5 家，检验市场反馈（别怕挂，面经就是情报）
- [ ] 或：接第一个外包 / 咨询（哪怕不赚钱，跑通流程）
- [ ] 持续输出：每周 1 篇文章
- [ ] 复盘：哪条路走通了就加深，没走通就换

> **90 天自检**：你拿到 offer 或第一笔副业收入了吗？

---

## 四、每月自检清单

- [ ] 我能 10 分钟内说清楚一个 AI 技术概念吗
- [ ] 我的项目别人 clone 下来能一键跑起来吗
- [ ] 我这个月产出了文章 / 代码吗
- [ ] 我和 3 个以上同行深聊过 AI 落地吗
- [ ] 我的简历 / GitHub 主页，HR 10 秒内能看出「Java + AI」吗

> 5 项里 ≥4 项打勾 = 节奏正常；≤2 项 = 该调整计划了。

---

## 五、资源清单

### 官方文档

| 资源 | 链接 |
|---|---|
| Spring AI | https://docs.spring.io/spring-ai/reference/ |
| LangChain4j | https://docs.langchain4j.dev/ |
| Spring AI Alibaba | https://sca.aliyun.com/ai/guide/getting-started/ |
| MCP 协议 | https://modelcontextprotocol.io/ |

### 本系列仓库

| 仓库 | 用途 |
|---|---|
| [framework-compare](../framework-compare) | 三框架对比（篇 2 / 篇 3 配套） |
| 后续每篇一个仓库 | 见[组织主页](https://github.com/java-ai-in-action) |

### 工具

- **Docker + docker-compose**（必备）
- **IDE**：IntelliJ IDEA / VSCode + AI 插件
- **模型**：DeepSeek（便宜）/ 通义（国内合规）/ OpenAI（效果标杆）

### 社区

- Spring AI GitHub Discussions
- 阿里云开发者社区 SCA 专栏
- 公众号「**Java程序员面试宝典**」（不定时更新）

---

## 六、FAQ

**Q：要不要学 Python？**
A：应用层不需要。模型训练 / 算法岗另说。Java + Spring AI 足够覆盖企业级 AI 应用开发 80% 的场景。

**Q：没 GPU 能学吗？**
A：能。调 API 完全不需要 GPU。本地部署（Ollama）是进阶选项，不是门槛。

**Q：多久能上手？**
A：30 天能做 Demo，90 天能做项目，6 个月能拿 offer（按每天投入 2 小时算）。

**Q：35 岁转来得及吗？**
A：Java AI 应用开发的壁垒是「工程能力 + 业务理解」——这两样正是老 Java 的优势。慌的应该是算法岗，不是你。

**Q：三个框架到底学哪个？**
A：看[篇 2 选型指南](../framework-compare)。默认建议：先 Spring AI（企业主流），再按需看 SAA 或 LangChain4j。

---

## 七、系列导航

| 篇序 | 文章 | 配套仓库 |
|---|---|---|
| 篇1 | 干了 13 年 Java，AI 时代我不是被淘汰，而是被重新定价 | 本仓库 |
| 篇2 | Spring AI vs LangChain4j vs Spring AI Alibaba：2026 终极选型指南 | [framework-compare](../framework-compare) |
| 篇3 | Spring AI 2.0 GA 实战：从 0 到 1 搭建企业级 ChatClient | [framework-compare](../framework-compare) |
| 篇4 | RAG 准确率从 32% 干到 89% | [framework-compare/benchmarks/rag](../framework-compare/tree/main/benchmarks/rag) |
| 篇5 | 把 @Tool 一键暴露成 MCP Server | [mcp-in-action](../mcp-in-action) |
| 篇6 | 企业级 Multi-Agent 实战 | [multi-agent-in-action](../multi-agent-in-action) |
| 篇7 | 多模型路由与故障转移 | [model-router-in-action](../model-router-in-action) |
| 篇8 | AI Agent 可观测 + Token FinOps | [ai-observability-in-action](../ai-observability-in-action) |
| 篇9 | Prompt Injection 真实复盘 | [ai-security-in-action](../ai-security-in-action) |
| 篇10 | 33 岁 Java 后端转 AI 的真实账单 | 本仓库（更新） |

---

## License

MIT

---

## 📮 关注公众号「Java程序员面试宝典」

<img src="docs/wechat-qrcode.png" width="720" alt="扫码关注公众号：Java程序员面试宝典" />

**微信搜一搜「Java程序员面试宝典」**，或直接扫码关注。

- 📖 **「Java AI 实战派」系列 10 篇长文** —— 公众号首发，不定时更新
- 🧰 每篇都配**可运行的开源仓库**（这套系列一共 8 个仓库）
- 🕳️ 只讲**踩过的坑**，不讲空概念

> 这个仓库帮到你了吗？点个 ⭐ **Star** 支持一下，再去公众号坐坐 👆
