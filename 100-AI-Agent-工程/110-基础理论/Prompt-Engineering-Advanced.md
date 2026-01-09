# Prompt Engineering 高级技巧

## 1. CoT (Chain of Thought)
让模型“一步步思考”。
> Prompt: "Let's think step by step."
> 进阶: "Please break down the problem into sub-tasks, solve each one, and then combine the results."

## 2. ReAct (Reason + Act)
Agent 的核心循环。
- **Thought**: 我需要做什么？（比如：查天气）
- **Action**: 调用天气 API。
- **Observation**: API 返回“北京，晴，25度”。
- **Thought**: 我现在知道了天气，可以回答用户了。
- **Action**: 回答“北京今天天气不错...”

## 3. Few-Shot Prompting (少样本提示)
不要只给指令，给几个示例 (Examples)。
- 示例是告诉 LLM “输出格式”和“推理风格”的最有效方式。

## 4. DSPy (Declarative Self-improving Language Programs)
- 2025 年的趋势是 **Prompting 编程化**。
- 不再手动微调 Prompt 里的词语，而是定义 Metrics (评估标准) 和 Dataset，让 DSPy 自动优化 Prompt。
- *观点*: "Prompt Engineering is dead. Long live DSPy."
