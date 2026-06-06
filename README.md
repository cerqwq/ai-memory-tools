# 🧠 AI Memory Tools

AI记忆工具，支持记忆管理、检索、整合。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 记忆系统设计
- 💻 记忆代码生成
- 🔍 检索策略设计
- 🔄 记忆整合设计
- 🪟 上下文窗口生成
- 📊 记忆使用分析

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_memory_tools import create_tools

tools = create_tools()

# 记忆系统设计
memory = tools.design_memory_system("个人助手")

# 记忆代码
code = tools.generate_memory_code("语义", "ChromaDB")

# 检索策略
retrieval = tools.design_retrieval_strategy("客服")

# 记忆整合
consolidation = tools.design_consolidation(["短期", "长期"])

# 上下文窗口
context = tools.generate_context_window(memories, query, 4000)

# 使用分析
analysis = tools.analyze_memory_usage(usage_stats)
```

## 📁 项目结构

```
ai-memory-tools/
├── tools.py       # 记忆工具核心
└── README.md
```

## 📄 许可证

MIT License
