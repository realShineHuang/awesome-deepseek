# Awesome DeepSeek [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Check Markdown Links](https://github.com/realShineHuang/awesome-deepseek/actions/workflows/check-links.yml/badge.svg?branch=main)](https://github.com/realShineHuang/awesome-deepseek/actions/workflows/check-links.yml)

[English](README.md) | 简体中文

> DeepSeek 资源精选列表，包括前沿 AI 模型、开发者工具、研究论文和社区项目。由社区维护，服务社区。

## 目录

- [官方资源](#官方资源)
- [模型](#模型)
- [技术报告](#技术报告)
- [工具和应用](#工具和应用)
- [提示词](#提示词)
- [教程和文档](#教程和文档)
- [社区项目](#社区项目)
- [其他精选列表](#其他精选列表)
- [如何贡献](#如何贡献)
- [许可证](#许可证)
- [致谢](#致谢)

---

## 官方资源

- [🌐 DeepSeek 官网](https://deepseek.com/) - 产品更新和研究的官方门户
- [💻 DeepSeek GitHub](https://github.com/deepseek-ai) - 官方代码仓库
- [🤖 DeepSeek Chat](https://chat.deepseek.com/) - 对话 AI 在线演示
- [📱 DeepSeek App](https://download.deepseek.com/app/) - iOS 和 Android 移动应用
- [📄 API 文档](https://api-docs.deepseek.com/) - 官方 API 参考
- [💰 API 定价](https://api-docs.deepseek.com/quick_start/pricing) - API 使用的详细定价信息
- [📊 服务状态](https://status.deepseek.com/) - 实时服务状态监控

---

## 模型

### 基础模型
- [🧠 DeepSeek-LLM](https://github.com/deepseek-ai/DeepSeek-LLM) - 7B/67B 参数通用大语言模型
- [🚀 DeepSeek-V2](https://github.com/deepseek-ai/DeepSeek-V2) - MoE 模型，总参数 236B（激活 21B），128k 上下文
- [⚡ DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) - MoE 模型，总参数 671B（激活 37B），128k 上下文
- [🔬 DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) - 强化学习增强模型，MATH 基准 60.9%，128k 上下文

### 代码模型
- [💻 DeepSeek-Coder：让代码自己写](https://arxiv.org/abs/2401.14196) - 介绍 DeepSeek Coder 模型的第一个版本
- [🔧 DeepSeek-Coder-V2：打破代码智能闭源模型的壁垒](https://arxiv.org/abs/2406.11931) - 开源 MoE 代码语言模型
- [🛠️ DeepSeek-MoE](https://github.com/deepseek-ai/DeepSeek-MoE) - 在专家混合语言模型中实现终极专家专业化

### 多模态模型
- [🖼️ DeepSeek-VL](https://github.com/deepseek-ai/DeepSeek-VL) - 视觉语言模型，用于现实世界理解（1.3B/7B），4096 上下文长度
- [🎨 Janus](https://github.com/deepseek-ai/Janus) - 统一的多模态理解和生成模型
- [🌌 DreamCraft3D](https://github.com/deepseek-ai/DreamCraft3D) - DreamCraft3D 的官方实现：使用 Bootstrapped Diffusion Prior 的分层 3D 生成

### 数学模型
- [🧮 DeepSeekMath：推动开放语言模型数学推理的极限](https://arxiv.org/abs/2402.03300) - 介绍 7B 数学专家模型，在 MATH 基准上达到 51.7%

### 微调和优化
- [⚙️ ESFT](https://github.com/deepseek-ai/ESFT) - 专家专门化微调

### 集成和工具
- [🔗 awesome-deepseek-integration](https://github.com/deepseek-ai/awesome-deepseek-integration) - DeepSeek 集成资源精选列表
- [🛠️ awesome-deepseek-coder](https://github.com/deepseek-ai/awesome-deepseek-coder) - DeepSeek Coder 相关开源项目精选列表

---

## 技术报告

### 基础模型
- [📜 DeepSeek LLM：用长期主义扩展开源语言模型](https://arxiv.org/abs/2401.02954) - 介绍 DeepSeek 基础模型的训练方法和创新
- [🚀 DeepSeek-V2：强大、经济和高效的混合专家语言模型](https://arxiv.org/abs/2405.04434) - 介绍 DeepSeek-V2 的架构和训练策略
- [⚡ DeepSeek-V3 技术报告](https://arxiv.org/abs/2412.19437) - 详细介绍总参数量 671B 的 MoE 架构
- [🔬 DeepSeek-R1：通过强化学习激励 LLM 的推理能力](https://arxiv.org/abs/2501.12948) - 介绍用于推理能力的强化学习方法

### 代码模型
- [💻 DeepSeek-Coder：当大语言模型遇到编程](https://arxiv.org/abs/2401.14196) - 深入探讨 DeepSeek Coder 的技术细节和性能
- [🔧 DeepSeek-Coder-V2：打破代码智能闭源模型的壁垒](https://arxiv.org/abs/2406.11931) - 介绍开源 MoE 代码语言模型

### 数学模型
- [🧮 DeepSeekMath：推动开放语言模型数学推理的极限](https://arxiv.org/abs/2402.03300) - 介绍 7B 数学专家模型，在 MATH 基准上达到 51.7%

### 使用指南
- [📚 DeepSeek 提示词库](https://api-docs.deepseek.com/prompt-library) - 精选提示词和示例集合

---

## 工具和应用

### 开发工具
- [⚡ API 快速入门](https://api-docs.deepseek.com/) - 5 分钟入门

### 集成
- [🤗 Hugging Face 模型](https://huggingface.co/deepseek-ai) - 模型中心集成

### 实验场
- [🧪 Colab 笔记本](https://colab.research.google.com/github/deepseek-ai) - 免费实验

---

## 提示词

- [📚 官方提示词库](https://api-docs.deepseek.com/prompt-library) - 精选提示词和示例集合

---

## 教程和文档

- [🚀 快速入门指南](https://api-docs.deepseek.com/) - DeepSeek 入门第一步
- [📚 完整文档](https://api-docs.deepseek.com/) - 全面的技术参考

---

## 社区项目

### 开源
- [🤗 Hugging Face 模型](https://huggingface.co/deepseek-ai) - 模型文档和演示

---

## 其他精选列表

- [🌟 Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) - 大语言模型资源
- [🔓 Awesome Open LLM](https://github.com/eugeneyan/open-llms) - 开源大语言模型
- [🌟 Awesome-Chinese-LLM](https://github.com/HqWu-HITCS/Awesome-Chinese-LLM) - 中文大语言模型资源
- [🛡️ Awesome LLM Security](https://github.com/corca-ai/awesome-llm-security) - 安全最佳实践

---

## 如何贡献

欢迎你的贡献！请：
1. 阅读我们的[贡献指南](CONTRIBUTING_zh-CN.md)
2. 确保链接相关且可用
3. 添加简洁的描述（50-150字符）
4. 遵守[行为准则](CODE_OF_CONDUCT_zh-CN.md)

---

## 许可证

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

---

## 致谢

特别感谢：
- DeepSeek 工程团队的开源贡献
- [@realShineHuang](https://github.com/realShineHuang) 维护此列表
- 所有[贡献者](CONTRIBUTORS_zh-CN.md)（查看完整列表） 