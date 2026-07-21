# TB Skills

个人 Codex 技能集合，汇集了日常开发中常用的自定义 Agent 技能。

## 技能列表

### 🛠️ RTK CLI Agent
一个 CLI 代理，可减少常见开发命令中 60-90% 的 LLM 令牌消耗。单个 Rust 二进制文件，零依赖。

**仓库：** [rtk-ai/rtk](https://github.com/rtk-ai/rtk.git)

### 📱 App Store Opportunity Research
全流程 App Store 机会研究。发现未充分服务的细分市场，分析竞争对手的差距，编写 MVP 产品需求文档，并在 Rork 上构建原型。

**仓库：** [froessell/app-store-opportunity-research](https://github.com/froessell/app-store-opportunity-research.git)

### 🎨 Agnes AI Generation
Agnes AI 在文本、图像和视频生成方面的各项能力。

**仓库：** [Yacey/agnes-ai-generation-skill](https://github.com/Yacey/agnes-ai-generation-skill.git)

### 🦴 Caveman
通过"原始人式"压缩表达，将输出 Token 数量减少 65%，同时保持完整的技术准确性。支持多种强度级别：lite、full、ultra、文言模式。

**仓库：** [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman.git)

## 使用方式

每个技能通过对应的 `SKILL.md` 文件定义，将技能目录放置于 Codex 的 skills 路径下即可使用。

```bash
# 技能安装路径
~/.codex/skills/<skill-name>/
```
