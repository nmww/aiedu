# 技能作品（SkillHub）

日常工作中反复出现的流程，我不会每次重做一遍——而是把它固化成一个可复用、可分发的 **Skill**，发布到 [SkillHub](https://skillhub.cn/) 上开放给其他人安装使用。

这些技能不是玩具：每一个都来自真实的工作场景（教研日报、视频配音、腾讯文档读写、服务器运维、数据收集……），跑通之后才整理成标准包发布。

<div class="ad-stats">
<div class="ad-stat"><span class="ad-stat__num">20</span><span class="ad-stat__label">已发布技能</span></div>
<div class="ad-stat"><span class="ad-stat__num">8</span><span class="ad-stat__label">覆盖分类</span></div>
<div class="ad-stat"><span class="ad-stat__num">1.2万+</span><span class="ad-stat__label">累计下载</span></div>
<div class="ad-stat"><span class="ad-stat__num">107</span><span class="ad-stat__label">累计安装</span></div>
</div>

!!! tip "关于 Skill"
    Skill 是给 AI 智能体用的「能力包」——把一套确定的操作流程、接口调用方式和边界条件写清楚，智能体装上就能按标准执行，不用每次重新描述需求。相当于把人的经验沉淀成可复用的工具。

---

## AI 智能体

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [🦞 龙虾记忆备份同步](https://skillhub.cn/skills/memory-backup-skill) | 把对话中的重要内容自动写入记忆文件，跨渠道同步，并通过 Git 推送到远程仓库备份；支持从备份恢复 | 1.0.3 | 808 | 18 |
| [灵芯派记忆守护者](https://skillhub.cn/skills/opencode-lingxin-memory) | 为 OpenCode 助手提供记忆持久化，专为灵芯派低资源 ARM64 环境设计，支持 Gitee 云端同步 | 1.0.0 | 544 | — |
| [灵芯派记忆守护者（轻量版）](https://skillhub.cn/skills/opencode-lingxin-memory1) | 同上场景的轻量实现：Git 版本控制 + Gitee 云同步，占用更小 | 1.0.0 | 614 | 13 |
| [AI 小镇访客居民接入](https://skillhub.cn/skills/ai-town-guest-agent) | 让任意智能体注册为 AI 小镇的访客居民：持续心跳在线、批量或定时说话、按语料自主聊天、状态查询与离线退出 | 1.1.0 | 15 | — |

## 办公效率

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [腾讯文档编辑技能](https://skillhub.cn/skills/tencent-works) | 腾讯文档（docs.qq.com）的完整操作能力：创建编辑文档 / 表格 / 幻灯片 / 思维导图 / 智能表格，管理知识库空间与文件结构 | 1.0.1 | 1509 | — |
| [腾讯文档技能](https://skillhub.cn/skills/tencentdoc) | 腾讯在线文档的创建、编辑、管理能力封装，覆盖多类文档形态 | 1.0.0 | 1002 | 14 |
| [龙虾教研日报助手](https://skillhub.cn/skills/daily-report-assistant) | 通过对话记录每日工作，自动写入腾讯文档智能表格；一键生成月度汇总 | 1.0.1 | 705 | 16 |
| [飞书消息按钮（feishubutton）](https://skillhub.cn/skills/feishubutton) | 飞书消息卡片按钮与审批交互能力封装 | 1.0.1 | 726 | — |

## 设计媒体

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [MiniMax 媒体生成](https://skillhub.cn/skills/minimax-skill) | 统一媒体生成入口：文本转语音、文生图、文生视频三类能力收口为一个命令，配置自己的 API Key 即可调用 | 1.0.0 | 1385 | 30 |
| [教学视频配音字幕合成](https://skillhub.cn/skills/video-tutorial-v2-publish) | 教学视频自动配音 + 字幕合成：环境自动检测 → 音色选择 → 一键执行 → 容错续跑，讯飞超拟人为主、edge 备用 | 1.0.20 | 1313 | — |
| [灵声工坊视频配音](https://skillhub.cn/skills/smart-dubbing-studio) | 智能视频配音与字幕同步：TTS 语音生成、语速自适应、自动识别填充静音段、逐句精校字幕，一键输出成品视频 | 1.0.7 | 940 | — |
| [字幕编辑器（subtitle-editor）](https://skillhub.cn/skills/subtitle-editor-pro) | 字幕文件的解析、编辑与导出工具链 | 1.0.2 | 708 | — |
| [MiMo V2.5 TTS 语音合成](https://skillhub.cn/skills/mimo-v2-5-tts) | 小米 MiMo V2.5 TTS 系列模型接入：预置音色、音色设计、音色克隆三种模式，支持自然语言控制与风格标签 | 1.0.0 | 446 | — |

## 开发编程

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [精准编程四大原则](https://skillhub.cn/skills/precise-coding-principles) | 源自 Andrej Karpathy 总结的 LLM 编程四大通病与核心原则，写代码 / 评审 / 重构时自动加载 | 1.0.0 | 768 | 16 |
| [Gitee 发布助手](https://skillhub.cn/skills/gitee-publish) | 把本地项目发布 / 维护到 Gitee 的标准流程，账号无关、一键 OAuth 授权、发布前自动脱敏 | 1.0.0 | 64 | — |
| [QuickForm 网页发布与数据收集](https://skillhub.cn/skills/quickform) | 把 AI 生成的单页 HTML 发布到 quickform.cn 并接上数据收集：建任务 → 注入提交逻辑 → 上传成公网链接 → 拿后台数据页 | 1.1.1 | 34 | — |

## 运维安全

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [腾讯云 Lighthouse 直连运维通道](https://skillhub.cn/skills/lighthouse-mcporter) | 通过 mcporter CLI + 腾讯云 API 密钥直连轻量应用服务器，覆盖实例查询、TAT 远程命令、防火墙、监控、快照等 60 项运维操作 | 1.0.0 | 32 | — |

## 数据分析

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [一句话数据收集器](https://skillhub.cn/skills/quickform-datacollect) | 一句话生成「数据收集网页 + 实时数据大屏 + 云端任务」，任务记本地台账，后续按名字维护、数据不丢 | 1.3.0 | 43 | — |

## 内容创作

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [博客园 cnblogs 文章发布](https://skillhub.cn/skills/cnblogs-metaweblog) | 通过 MetaWeblog XML-RPC 接口管理博客园博客：发布 / 编辑 / 删除文章、上传图片、拉取文章列表 | 1.0.0 | 19 | — |

## 生活服务

| 技能 | 说明 | 版本 | 下载 | 安装 |
| --- | --- | --- | ---: | ---: |
| [旅游规划](https://skillhub.cn/skills/aitravel) | 行程规划专家：逐日 itinerary、酒店 / 机票 / 火车推荐、预算估算、本地贴士与省钱建议 | 1.0.0 | 291 | — |

---

## 我怎么做一个 Skill

一个技能从想法到上架，大致四步：

1. **踩到痛点** —— 同一件事做了三遍以上，就该固化了。
2. **先跑通再封装** —— 在真实任务里把流程跑通、把坑踩完，确认稳定可用，才开始写包。
3. **写清边界** —— 触发条件、前置依赖、需要什么密钥、失败怎么降级，全部写进 `SKILL.md`。给别人用的东西，含糊就是坑。
4. **发布与迭代** —— 上架后有真实反馈再改版本；涉及密钥的一律走用户自己的凭据，技能包里不留任何 secret。

这套做法同样用在本站的 [QuickClass](works/quickclass.md) 等产品上——能沉淀成工具的流程，就不要重复手工做。

---

<p class="ad-tip">
技能数据来自 <a href="https://skillhub.cn/" target="_blank" rel="noopener">SkillHub</a> 平台，统计于 2026-09-21，随发布持续更新。完整列表见 <a href="https://skillhub.cn/user/user_a5827f21" target="_blank" rel="noopener">我的 SkillHub 主页</a>。
</p>
