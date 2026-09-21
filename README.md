# 张维 · AI 教育应用作品集

个人展示站点：介绍、能力清单与项目作品集。

**在线地址**：<https://aiedu.readthedocs.io/>

---

## 技术栈

- [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- 托管于 [Read the Docs](https://readthedocs.org/)，push 后自动构建

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve          # 打开 http://127.0.0.1:8000
```

构建静态产物：

```bash
mkdocs build          # 输出到 site/
```

## 目录结构

```
.
├── mkdocs.yml            # 站点配置（导航、主题、扩展）
├── requirements.txt      # Python 依赖
├── .readthedocs.yaml     # Read the Docs 构建配置
└── docs/
    ├── index.md          # 首页
    ├── about.md          # 关于我
    ├── capabilities.md   # 能力清单
    ├── stack.md          # 技术栈
    ├── changelog.md      # 更新记录
    ├── stylesheets/
    │   └── extra.css     # 自定义样式
    ├── assets/
    │   └── covers/       # 项目封面图
    └── works/
        ├── index.md      # 作品总览
        ├── quickclass.md
        ├── quickform.md
        ├── quickembed.md
        ├── ai-town.md
        └── huaxuezhong.md
```

## 怎么新增一个项目

1. 封面图放进 `docs/assets/covers/`（建议宽 900px、JPEG，控制在 150KB 以内）
2. `docs/works/index.md` 复制一张卡片，改文案与链接
3. `docs/index.md` 的「全部作品」表格补一行
4. 重点项目另建 `docs/works/<项目名>.md`，并在 `mkdocs.yml` 的 `nav` 里登记
5. `docs/changelog.md` 顶部加一条记录
6. commit + push，Read the Docs 自动重建

## 说明

站点内容与平台代码解耦——**更新文档不需要重新部署任何应用**。
