# Multi-Agent-Reasoning-System-for-Dynamic-Task-Planning-with-LLMs

# 🧠 Multi-Agent Reasoning System for Dynamic Task Planning with LLMs

This project implements a modular AI agent framework designed to autonomously decompose, execute, and validate multi-step tasks using large language models (LLMs). It showcases how a system composed of specialized roles—Planner, Reasoner, Executor, and Evaluator—can collaborate to solve complex queries in an iterative and interpretable manner.

## ✨ Key Features

- **Multi-agent architecture**: Clear role separation for planning, reasoning, action execution, and result evaluation.
- **LLM-based reasoning**: Uses GPT (via OpenAI API) to handle logic decomposition and code generation.
- **Autonomous execution**: Supports automatic task execution and self-reflection on intermediate results.
- **Shared memory**: Enables persistent task state across agents for coherent long-horizon workflows.
- **Error recovery**: Evaluator can detect faulty outputs and trigger re-planning or regeneration loops.

## 🧩 System Overview


## 🛠️ Tech Stack

- Python 3.10+
- OpenAI API (GPT-4 / GPT-3.5)
- Streamlit (optional UI)
- LangChain (optional, for memory/context management)

## 🚀 Getting Started

1. **Clone this repo**
   ```bash
   git clone https://github.com/lynlzh/Multi-Agent-Reasoning-System-for-Dynamic-Task-Planning-with-LLMs.git
   cd Multi-Agent-Reasoning-System-for-Dynamic-Task-Planning-with-LLMs
