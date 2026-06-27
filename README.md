 __  __ ___   ___ ___ 
|  \/  |   \ / __| __|
| |\/| | |) | (_ | _| 
|_|  |_|___/ \___|___|

# MiniDialogue
轻量级手机端 AI 对话引擎 · 基于 TinyTransformer 架构，无需网络，纯本地 CPU 运行。
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=flat-square)](https://github.com/wakcvjb/ai) [![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
项目简介：MiniDialogue 是一个专门为移动设备设计的轻量级对话模型。基于 TinyTransformer 架构，整个模型仅约 1 MB，可在手机端 CPU 上流畅运行，无需联网，无需 GPU。你可以在任何 Android 设备上，用它进行自然、流畅的英文对话。
核心特性：
模型架构：TinyTransformer (embed_dim=256, heads=4, layers=4)
模型大小：约 1 MB
运行方式：本地 CPU 推理，无需网络
交互方式：多轮对话，自然语言输入
训练数据：20 万字英文日常对话语料
生成速度：手机端毫秒级响应
温度采样：支持 0.8 温度控制，提升对话多样性
下载模型：你可以直接从 GitHub 仓库下载最新版模型文件：MiniDialogue_1782522799.pth
运行对话：将模型文件和对话脚本放在同一目录，执行：python chat
开始聊天：输入英文，模型会自动回复：你: How are you? MiniDialogue: I'm fine, thank you!
技术参数：
嵌入维度：256
注意力头数：4
Transformer 层数：4
参数量：约 3.4 M
训练数据量：20 万英文对话字符
损失函数：CrossEntropyLoss
优化器：AdamW
项目结构：
MiniDialogue/
├── MiniDialogue_1782522799.pth
├── README.md
└── LICENSE
开源协议：本项目采用 MIT 许可证。你可以自由下载、修改、商用，但需保留版权声明。
贡献：欢迎通过 GitHub Issues 或 Pull Requests 提出建议与优化。
链接：
官网：https://wakcvjb.github.io
GitHub：https://github.com/wakcvjb/ai
官方 Logo：🐱
