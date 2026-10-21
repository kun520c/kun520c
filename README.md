# 刘坤炀 | Java Backend Developer

哈尔滨工业大学（深圳）计算机科学与技术专业本科生，主要学习和实践 Java 后端开发，关注数据库事务、并发控制、Redis 缓存与 RAG/LLM 应用工程。

目前正在寻找 Java 后端开发实习机会。

## 主要项目

### [AI Interview Studio · AI 模拟面试系统](https://github.com/kun520c/ai-interview-system)

基于 Java 21、Spring Boot、MySQL、Milvus 构建的 AI 模拟面试平台，涵盖题库管理、面试作答、RAG 检索、AI 评分与报告生成。

**工程重点：**

- 基于状态机管理面试流程，使用幂等机制与乐观锁控制并发提交。
- 使用 Milvus 实现 RAG 知识检索，结合评分点快照与 Java 侧结果校验。
- 设计异常恢复与超时接管机制，减少外部模型调用失败对业务状态的影响。

[查看项目源码、界面展示与技术文档 →](https://github.com/kun520c/ai-interview-system)

### [一方书室 · 图书管理系统](https://github.com/kun520c/library)

基于 Spring Boot、MyBatis、MySQL、Redis 的图书借阅管理系统，实现用户认证、图书管理、借阅归还和记录查询。

**工程重点：**

- 使用 MySQL 事务与条件更新处理并发借阅、库存扣减和重复归还。
- 使用 Redis Cache-Aside 缓存图书详情，处理缓存失效与故障回源。
- 提供自动化测试、CI 与本地运行指南。

[查看项目源码、界面展示与技术文档 →](https://github.com/kun520c/library)

### [Dual Agent Studio · 多 Agent 协作桌面工具](https://github.com/kun520c/dual-agent-studio)

基于 Python、PySide6、React 的 Windows 多 Agent Coding 桌面项目，探索 AI 编程任务编排、Git Worktree 隔离与可信验证。

当前为源码开发预览版本，部分自主编排功能仍处于实验与离线验证阶段。

[查看项目与开发状态 →](https://github.com/kun520c/dual-agent-studio)

## 技术方向

Java 21 · Spring Boot · MyBatis · MySQL · Redis · JWT · Milvus · RAG

[GitHub 主页](https://github.com/kun520c)
