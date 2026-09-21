# 作品集

全部已上线的项目。每个都能直接打开体验——不是在跑 Demo，是真的部署在公网上的应用。

!!! info "关于这里的内容"
    这些应用部署在**魔搭创空间**（ModelScope Studio）。首次访问时容器可能处于冷启动状态，等待几秒即可正常加载。

---

## AI 教育应用

<div class="grid cards" markdown>

-   ![QuickClass](../assets/covers/quickclass.jpg)

    ---

    **QuickClass Agent · AI 智能体学习平台**

    AI 驱动的课堂教学辅助平台，区分教师端与学生端。老师可以快速搭建包含 AI 对话活动、HTML 互动探究、课堂作业、学生作品提交的完整教学单元；系统采集学生对话、答题、探究操作等全流程数据，自动生成个人与班级学情分析报告，并基于课堂原始数据一键生成教研论文。

    `Next.js` `TypeScript` `Prisma` `SQLite` `LLM`

    [访问站点](https://modeai-quickclass.ms.show) · [项目详情](quickclass.md)

-   ![QuickForm](../assets/covers/quickform.jpg)

    ---

    **QuickForm · 轻量级表单数据回收**

    面向教研与课堂场景的轻量数据收集平台。**核心差异是开放提交接口**——传统表单只能在自家页面填写，QuickForm 可以把提交接口接入任意网页、AI 生成页面或第三方课程活动页，数据自动汇总回后台统一管理，并配 AI 辅助分析。

    `Docker` `开放 API` `数据大屏`

    [访问站点](https://modeai-quickform.ms.show) · [项目详情](quickform.md)

-   ![画中学](../assets/covers/huaxuezhong.jpg)

    ---

    **盛通教育 · 画中学**

    基于开源 Excalidraw 打造的手绘风 K12 学习白板。依托原生手绘笔触与无限画布，支持学生创作连环画、梳理思维导图、搭建解题四步学习框架；内置每日挑战练习模块与教学贴纸库，配套个人作品集管理，把抽象知识转化为可视化手绘作品。

    `Excalidraw` `静态托管` `K12`

    [访问站点](https://modeai-huaxuezhong.ms.show) · [项目详情](huaxuezhong.md)

-   ![语音聊天屋](../assets/covers/chatforme.jpg)

    ---

    **语音聊天屋**

    专为 3–12 岁儿童打造的网页端 AI 语音聊天玩伴。无需打字，直接语音对话；内置 47 款童声音色一键切换，基于 DeepSeek 优化儿童专属对话逻辑，内容纯净易懂，可陪孩子聊天、讲故事、解答科普问题。

    `Gradio` `DeepSeek` `TTS` `MCP`

    [访问站点](https://modeai-chatforme.ms.show)

-   ![QuickEmbed](../assets/covers/embedding.jpg)

    ---

    **QuickEmbed · 文本向量化服务**

    自建文本向量化引擎：Ollama + `qwen3-embedding:0.6B` 模型，对外提供 OpenAI 兼容接口。支持单条与批量嵌入，模型与用量数据持久化，重启不丢失。

    `Ollama` `Flask` `向量检索`

    [访问站点](https://modeai-embedding.ms.show) · [项目详情](quickembed.md)

-   ![QuickEmbed 网关](../assets/covers/embedding-gw.jpg)

    ---

    **QuickEmbed · 统一网关**

    向量化服务的统一对外入口。所有应用与老师只需对接这一个地址，网关负责代理上游引擎、鉴权、限流与用量统计（配套监控大屏）。与引擎解耦，可在不影响调用方的情况下独立升级。

    `Flask` `限流` `用量统计大屏`

    [访问站点](https://modeai-embedding-gw.ms.show) · [项目详情](quickembed.md)

</div>

## 探索与实验项目

<div class="grid cards" markdown>

-   ![AI Town](../assets/covers/ai-town.jpg)

    ---

    **AI Town 小镇**

    8 位会自己走路、可点击对话的 AI 居民，世界在浏览器里持续推进。对话由自部署 Ollama（Qwen2.5-1.5B）实时生成——**三端解耦架构**：前端是哑终端，NPC 行为逻辑在云端服务，模型端独立部署，改 AI 不用动前端。

    `React` `PixiJS` `Convex` `Ollama`

    [访问站点](https://modeai-ai-town.ms.show) · [项目详情](ai-town.md)

-   ![AI Town 大脑](../assets/covers/ai-town-ollama.jpg)

    ---

    **AI Town · 小镇大脑**

    小镇的模型端。Ollama + Qwen2.5 对话模型 + bge-m3 嵌入模型，权重直接烘焙进镜像。2 核纯 CPU 环境下的调优实践：上下文长度是延迟主导因素，需要在 `num_ctx` / `num_predict` / 并发数之间做取舍。

    `Ollama` `Qwen2.5` `bge-m3` `CPU 推理`

    [访问站点](https://modeai-ai-town-ollama.ms.show) · [项目详情](ai-town.md)

-   ![上帝视角](../assets/covers/godseye.jpg)

    ---

    **上帝视角 · 世界隐秘档案**

    浏览器端实景 3D 全球态势观测终端。汇聚航班、船舶、卫星、火情、地震等公开实时数据，支持 AI 语音操控目标追踪、驾驶舱视角与多类传感器滤镜，用沉浸式方式观察真实世界动态。

    `WebGL` `实时公开数据` `AI 语音`

    [访问站点](https://modeai-godseye-secrets.ms.show)

-   ![PDF 工具](../assets/covers/stirlingpdf.jpg)

    ---

    **PDF 在线编辑阅读工具**

    开源 Stirling-PDF 的本地化部署。50+ 种 PDF 处理能力：合并拆分、页面旋转裁剪、格式互转（Word / PPT / 图片 / HTML / Markdown）、加解密与权限、水印、电子签名、OCR 识别、压缩、文档对比与修复。**所有文件处理在本地完成，不外传，任务结束自动清理。**

    `Stirling-PDF` `Docker` `隐私优先`

    [访问站点](https://modeai-stirlingpdf.ms.show)

</div>

---

## 速查表

| 项目 | 类型 | 关键技术 | 入口 |
| --- | --- | --- | --- |
| QuickClass Agent | AI 教育平台 | Next.js · Prisma · LLM | [访问](https://modeai-quickclass.ms.show) |
| QuickForm | 数据收集 | Docker · 开放 API | [访问](https://modeai-quickform.ms.show) |
| 盛通教育 · 画中学 | K12 学习工具 | Excalidraw · 静态托管 | [访问](https://modeai-huaxuezhong.ms.show) |
| 语音聊天屋 | 儿童语音对话 | Gradio · DeepSeek · TTS | [访问](https://modeai-chatforme.ms.show) |
| QuickEmbed 向量化服务 | AI 基础设施 | Ollama · qwen3-embedding | [访问](https://modeai-embedding.ms.show) |
| QuickEmbed 统一网关 | AI 基础设施 | Flask · 限流 · 监控大屏 | [访问](https://modeai-embedding-gw.ms.show) |
| AI Town 小镇 | 智能体沙盒 | React · PixiJS · Convex | [访问](https://modeai-ai-town.ms.show) |
| AI Town 大脑 | 模型服务 | Ollama · Qwen2.5 | [访问](https://modeai-ai-town-ollama.ms.show) |
| 上帝视角 | 数据可视化 | WebGL · 实时数据 | [访问](https://modeai-godseye-secrets.ms.show) |
| PDF 在线工具 | 效率工具 | Stirling-PDF · Docker | [访问](https://modeai-stirlingpdf.ms.show) |
