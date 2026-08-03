# TB Skills

个人 Codex 技能集合，汇集了日常开发中常用的自定义 Agent 技能。

## 技能列表

### 🍎 Apple 开发

#### 🧠 Apple Full-Stack Genius
资深 Apple 全栈工程师 + 设计专家：使用 Swift 6、SwiftUI、iOS 26 Liquid Glass 构建 A 级 iOS/macOS/watchOS/tvOS/visionOS 应用，支持 AI 生成应用图标、启动图和 Logo，执行全代码审计（零警告、零死代码、零废弃 API）。

**仓库：** [Jonnycatx/apple-full-stack-genius-skill](https://github.com/Jonnycatx/apple-full-stack-genius-skill.git)

#### 🦾 Swift Development
全面 Swift 开发支持：SPM / Xcode 命令行构建、XCTest / Swift Testing 测试、simctl 模拟器管理、代码签名与分发、SwiftFormat / SwiftLint、Swift 6 并发模式、SwiftUI MVVM 架构、Core Data / SwiftData 持久化。

#### ⚡ Swift Concurrency Expert
Swift 6.2+ 并发审查与修复：Sendable 一致性、@MainActor、actor 隔离、数据竞争诊断、回调迁移 async/await。

#### 💧 SwiftUI Liquid Glass
采用、重构或审查 SwiftUI iOS 26+ Liquid Glass 界面，确保正确性、性能与设计一致性。

#### 📐 SwiftUI UI Patterns
SwiftUI 视图与组件最佳实践：导航层级、自定义 view modifier、响应式布局（stacks/grids）、TabView 架构、@State / @Binding 管理。

#### 🧹 SwiftUI View Refactor
SwiftUI 视图重构与审查：拆分为小型专用子视图、MV-over-MVVM 数据流、稳定视图树、显式依赖注入、正确使用 @Observable。

#### 🚀 SwiftUI Performance Audit
SwiftUI 运行时性能审计：慢渲染、滚动卡顿、高 CPU/内存、视图过度更新、布局抖动，并提供 Instruments 分析指导。

#### 💎 Liquid Glass
iOS 26 Liquid Glass 设计系统专家：glassEffect 实现、GlassEffectContainer、iOS 17/18 迁移、形态动画、HIG 合规、无障碍与性能优化。

**仓库：** [2dubu/liquid-glass](https://github.com/2dubu/liquid-glass.git)

#### 🍎 Apple Skills（技能包）
Apple 生态技能包，包含 30+ 个 API 参考与实战指南：SwiftUI、UIKit、StoreKit、WidgetKit、HealthKit、SwiftData、Combine、MapKit、App Intents、XCUITest、Swift Testing、HIG 等。

**仓库：** [Prisma-Labs-Dev/apple-skills](https://github.com/Prisma-Labs-Dev/apple-skills.git)

#### 🧪 iOS Agentic Skills（技能包）
iOS 质量审计技能包，包含 12 个子技能：无障碍、崩溃安全、数据建模与同步、错误信息与空状态、触觉设计、本地化、营销文案、性能、隐私、测试策略、视觉设计与对比度、watchOS 电池优化。

**仓库：** [mwd1234/ios-agentic-skills](https://github.com/mwd1234/ios-agentic-skills.git)

#### 🐞 iOS Debugger Agent
通过 XcodeBuildMCP 构建、运行、启动和调试模拟器上的 iOS 项目，检查界面状态、捕获日志、诊断运行时行为。

#### 🖥️ macOS Menubar Tuist App
构建、重构或审查基于 Tuist + SwiftUI 的 macOS 菜单栏应用（LSUIElement），包括 Tuist 目标定义、model-client-store-view 架构、脚本化启动流程。

#### 📦 macOS SwiftPM App Packaging
无 Xcode 项目的 SwiftPM macOS 应用开发：目录结构、目标与资源、自定义 .app 打包脚本、签名/公证/appcast 流程。

### 📱 App Store & 上架

#### 📝 App Store Changelog
基于 git tag 自动收集用户可见变更，生成 App Store 发布说明（What's New）。

#### ✅ App Store Review
对照 Apple App Store 审核指南检查项目合规性，支持原生（Swift/Obj-C）、Flutter、React Native、Expo、Kotlin Multiplatform、.NET MAUI 等项目。

#### 📸 ASO App Store Screenshots
分析应用代码库、提炼核心卖点，使用 Nano Banana Pro 生成高转化的 App Store 截图。

### 🔍 代码审查 & 重构

#### 👥 Review Swarm
并行只读多智能体 diff 审查：发现行为回归、安全/隐私风险、性能/可靠性问题、测试覆盖缺口，并给出优先级修复路径。

#### ✂️ Review and Simplify Changes
审查 git diff 或指定文件的复用性、代码质量、效率与规范问题，并可安全地应用修复。

#### 🐛 Bug Hunt Swarm
并行只读多智能体根因调查：定位崩溃、回归、卡顿、异常失败，输出带最快验证路径的排序诊断，不直接修改代码。

#### 🔀 Orchestrate Batch Refactor
大型重构/重写编排：并行多智能体分析、拆分工作流、明确所有权与依赖感知执行。

#### 📊 Project Skill Audit
分析项目历史 Codex 会话、记忆文件与现有技能，推荐高价值的新技能或更新建议。

#### ⚛️ React Component Performance
React 组件性能分析与优化：慢渲染、重复渲染、长列表卡顿、昂贵计算。

### 🐙 GitHub

#### 🐙 GitHub
通过 `gh` CLI 操作 GitHub：issue、PR、CI 状态、workflow 与 API 查询。

### 🛠️ 效率工具

#### 🛠️ RTK CLI Agent
一个 CLI 代理，可减少常见开发命令中 60-90% 的 LLM 令牌消耗。单个 Rust 二进制文件，零依赖。

**仓库：** [rtk-ai/rtk](https://github.com/rtk-ai/rtk.git)

#### 🎨 Agnes AI Generation
Agnes AI 在文本、图像和视频生成方面的各项能力。

**仓库：** [Yacey/agnes-ai-generation-skill](https://github.com/Yacey/agnes-ai-generation-skill.git)

#### 🦴 Caveman
通过"原始人式"压缩表达，将输出 Token 数量减少 65%，同时保持完整的技术准确性。支持多种强度级别：lite、full、ultra、文言模式。

**仓库：** [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman.git)

#### 🎨 UI/UX Pro Max
全平台专业 UI/UX 智能设计支持，覆盖品牌设计、设计系统、组件规范、动效设计等多维度能力。

**仓库：** [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git)

#### 📱 App Store Opportunity Research
全流程 App Store 机会研究。发现未充分服务的细分市场，分析竞争对手的差距，编写 MVP 产品需求文档，并在 Rork 上构建原型。

**仓库：** [froessell/app-store-opportunity-research](https://github.com/froessell/app-store-opportunity-research.git)

## 使用方式

每个技能通过对应的 `SKILL.md` 文件定义，将技能目录放置于 Codex 的 skills 路径下即可使用。

```bash
# 技能安装路径
~/.codex/skills/<skill-name>/
```
