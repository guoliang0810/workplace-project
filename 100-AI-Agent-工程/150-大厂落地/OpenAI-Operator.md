# OpenAI "Operator" 与 Assistants API 演进

## OpenAI Operator (电脑操作员)
> 2025年发布的里程碑式产品（代号），能够直接接管用户电脑完成复杂任务。

- **核心能力**:
    - **Computer Use**: 能够看懂屏幕，控制鼠标键盘。
    - **跨应用工作流**: 比如 "帮我查一下去巴黎的机票，对比三家网站，把结果做成 Excel 发给我"。
    - **浏览器沙箱**: 在安全的环境中执行网页操作。

## Assistants API v3 (2026)
- **状态管理**: 更加成熟的 Thread 管理，支持分支对话。
- **File Search (RAG)**: 性能大幅提升，支持混合检索 (Hybrid Search)。
- **Code Interpreter**: 支持更多 Python 库，甚至支持部分网络访问（受控白名单）。

## Swarm Framework
- 虽然 OpenAI 官方称其为 "实验性/教育性" 框架，但在 2025 年被广泛模仿。
- 核心思想：**Routines** (程序) 和 **Handoffs** (交接)。
- 这种模式非常适合客服场景：前台 Agent 分类意图 -> 转接给 售后 Agent / 销售 Agent。
