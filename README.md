# CortexSpace


[English Introduction](#-english-introduction) | [简体中文介绍](#-简体中文介绍)

---

## English Introduction

CortexSpace is not just another note-taking app. It's a powerful, **local-first** knowledge workspace designed to transform your scattered ideas into structured insights and completed tasks. By seamlessly integrating with **your own AI model**, it becomes a dynamic partner in your thinking process, helping you explore, synthesize, and create.

### ✨ Core Philosophy

In an era of information overload, simply storing information isn't enough. The real value lies in connecting, understanding, and acting upon it. CortexSpace is built on this principle, evolving from a passive information container into an active **task completion engine**. Your data stays on your machine, and you bring your own AI, giving you full control and privacy.

### 🚀 Key Features

-   **🧠 AI-Powered Cognition**:
    -   **Deep Exploration**: Start a conversation with any knowledge card. Let the AI help you brainstorm, challenge assumptions, or dive deeper into a topic.
    -   **Intelligent Augmentation**: Instantly rewrite, expand, or summarize any card's content with a single click.
    -   **Knowledge Capture Loop**: Seamlessly save valuable insights from AI conversations back into your workspace as new, atomic knowledge cards.
    -   **Bulk Synthesis**: Select multiple chat messages and merge them into a single, cohesive new card.

-   **🛠️ Advanced Workflow & Task Completion**:
    -   **Outline-Driven Synthesis**: A powerful report generation engine! Build an outline, drag-and-drop reference cards into each section, and let the AI write a comprehensive, coherent document based on your framework.
    -   **Action Plan**: Set a high-level goal for your workspace using a Markdown task list to keep your objectives front and center.
    -   **Split View**: Pin up to two cards to the side for easy reference, comparison, or writing.
    -   **Whiteboard View**: Break free from the grid! Organize your cards spatially on an infinite canvas.

-   **⚙️ Modern & Efficient Interface**:
    -   **Local-First & Private**: All your data is stored securely in your browser's IndexedDB. No cloud, no tracking.
    -   **Command Palette**: Press `Ctrl/Cmd + K` to instantly access any command.
    -   **Data Portability**: Easily export/import your workspace as a `.zip` (including all chat logs) or a clean `.md` file.
    -   **Slick UI**: Enjoy a polished, responsive interface with light and dark themes.

### 🛠️ Getting Started

CortexSpace is a single-file web application. No installation needed!

1.  **Download**: Get the `index.html` file from this repository.
2.  **Open**: Open the file in a modern web browser (Chrome, Firefox, Edge).
3.  **Configure AI**:
    -   Click the **Settings** icon (⚙️).
    -   Enter your API details for an OpenAI-compatible service (e.g., OpenAI, Groq).
        -   **URL**: e.g., `https://api.openai.com/v1`
        -   **API Key**: Your `sk-...` key.
        -   **Model**: e.g., `gpt-4-turbo`
    -   Click "Save Settings".

### 💻 Tech Stack

-   **Core**: Vanilla JavaScript (ES6+), HTML5, CSS3
-   **Database**: IndexedDB
-   **Dependencies**: Marked.js, Highlight.js, Fuse.js, JSZip, FileSaver.js

---

## 🇨🇳 简体中文介绍

CortexSpace 是一个强大的、**本地优先**的知识工作空间，旨在将您零散的想法转化为结构化的洞见和已完成的任务。通过与**您自己的 AI 模型**无缝集成，它将成为您思考过程中的动态伙伴，助您探索、综合与创造。

### ✨ 核心理念

在信息过载的时代，仅仅存储信息是远远不够的。真正的价值在于连接、理解信息并采取行动。CortexSpace 正是基于这一原则构建的，它从一个被动的信息容器，进化为一个主动的**任务完成引擎**。您的数据保留在本地设备上，并由您自己的 AI 模型驱动，赋予您完全的控制权和隐私安全。

### 🚀 核心功能

-   **🧠 AI 驱动的认知**:
    -   **深度探索**: 围绕任何知识卡片开启对话。让 AI 助您进行头脑风暴、挑战既有假设或深入钻研特定主题。
    -   **智能增强**: 一键对卡片内容进行改写、扩写或缩写。
    -   **知识捕获闭环**: 将 AI 对话中的宝贵见解，无缝地创建为新的、原子化的知识卡片，沉淀到您的工作区。
    -   **批量合成**: 选中多条对话消息，将它们合并成一张逻辑连贯的新卡片。

-   **🛠️ 高级工作流与任务完成**:
    -   **大纲驱动合成**: 强大的报告生成引擎！构建报告大纲，将参考卡片拖拽至相应章节，然后让 AI 根据您的框架撰写一份内容详实、结构清晰的完整文档。
    -   **行动计划**: 使用 Markdown 任务列表为您的工作空间设定顶层目标，让您的核心任务始终明确，并跟踪进展。
    -   **分栏视图**: 将最多两张卡片钉在侧边，便于随时参考、对比内容或进行写作。
    -   **白板视图**: 打破网格束缚！在无限画布上自由地组织您的知识卡片，构建思维导图或可视化信息簇。

-   **⚙️ 现代化高效界面**:
    -   **本地优先与隐私安全**: 您的所有数据都安全地存储在浏览器的 IndexedDB 中。没有云端，没有追踪。
    -   **命令面板**: 使用 `Ctrl/Cmd + K` 快捷键，即时访问所有功能。
    -   **数据可移植性**: 轻松地将工作空间导出/导入为 `.zip` 压缩包（包含所有聊天记录）或干净的 `.md` 文件。
    -   **精美 UI**: 享受精致、响应式的用户界面，并支持明暗两种主题。

### 🛠️ 快速上手

CortexSpace 是一个单文件 Web 应用，无需安装！

1.  **下载**: 从本仓库获取 `index.html` 文件。
2.  **打开**: 在现代浏览器（如 Chrome, Firefox, Edge）中打开该文件。
3.  **配置 AI**:
    -   点击左下角的**设置**图标 (⚙️)。
    -   填入您的 AI 服务（兼容 OpenAI API）的配置信息。
        -   **URL**: 例如 `https://api.openai.com/v1`
        -   **API Key**: 您的 `sk-...` 密钥。
        -   **Model**: 例如 `gpt-4-turbo`
    -   点击“保存设置”。

### 💻 技术栈

-   **核心**: 原生 JavaScript (ES6+), HTML5, CSS3
-   **数据库**: IndexedDB
-   **依赖库**: Marked.js, Highlight.js, Fuse.js, JSZip, FileSaver.js
