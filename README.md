# siemens-color-scheme

适用于 Qoder 的西门子品牌设计规范 Skill，在编写前端代码和设计印刷物料时自动应用西门子品牌设计标准。基于西门子企业设计规范（State: 2025-02-17）。

## 功能特性

- **完整配色体系** — 主色、辅助色、状态色、Deep Blue 灰度色阶，含 TailwindCSS Token 映射和 RGB 数值
- **配色语义规范** — 数字端与印刷端用色区分（Soft Green/Soft Blue 仅用于印刷），WCAG 2.1 对比度规则
- **企业渐变色** — Bold Dynamic Petrol（数字端）、Soft Dynamic Petrol（印刷端）、Deep Blue–Petrol
- **Key Visuals** — 品牌图形（变换∞、前进»、Xcelerator X、可持续○）、视觉矩阵、10个技术组合图标
- **易拉宝设计规范** — 三种布局模式（活动型、信息型、产品型）、Logo 位置、排版规则、内容分区指南
- **交互组件规范** — CTA 按钮、链接、焦点状态的 TailwindCSS 代码片段
- **规范禁忌** — 配色选择、背景、高亮文字、无障碍设计的 Dos & Don'ts

## 安装方式

### 方式一：手动安装（用户级，所有项目可用）

将本仓库克隆到 Qoder skills 目录：

```bash
git clone https://github.com/Polly1128/siemens-color-scheme.git ~/.qoder/skills/siemens-color-scheme
```

### 方式二：手动安装（项目级，仅当前项目）

克隆到项目的 `.qoder/skills/` 目录：

```bash
git clone https://github.com/Polly1128/siemens-color-scheme.git .qoder/skills/siemens-color-scheme
```

### 方式三：Skills CLI

```bash
npx skills add https://github.com/Polly1128/siemens-color-scheme -a qoder
```

## 文件结构

```
siemens-color-scheme/
├── SKILL.md           # 主文件（配色、渐变、Key Visuals 概要、交互规范、核心规则、易拉宝设计）
├── KEY_VISUALS.md     # 详细参考（品牌图形、视觉矩阵、技术图标、排版、易拉宝布局模式）
└── README.md          # 本文件
```

## 使用方法

当你在对话中提到以下关键词时，此 Skill 会自动激活：

- 西门子配色 / 西门子设计 / 西门子品牌 / 西门子风格
- Siemens UI / Siemens palette / Petrol
- Dayu UI / Siemens Xcelerator / Key visuals
- 易拉宝 / Roll-up banner / Banner design

示例提问：

```
按照西门子配色规范设计一个登录页面
用 Siemens style 做一个组件
设计一个西门子 AI Camp 的易拉宝
Create a dashboard using Siemens brand colors
```

## 配色速查表

| 角色 | Token | Hex | 用途 |
|------|-------|-----|------|
| 品牌主色 | `siemens-petrol` | `#009999` | Logo、按钮、链接 |
| 主色悬停 | `siemens-petrol-dark` | `#007a7a` | 悬停状态 |
| 深色背景 | `deep-blue` | `#000028` | 深色主题、易拉宝背景 |
| 浅色背景 | `light-sand` | `#f3f3f0` | 浅色主题背景 |
| 深色背景高亮 | `light-petrol` | `#00c1b6` | 深色背景上的强调色 |
| 数字端强调 | `bold-green` | `#00ffb9` | Key Visuals、CTA 渐变 |
| 印刷端强调 | `soft-green` | `#00d7a0` | 仅用于印刷、成功状态 |
| 错误 | `red` | `#ef0137` | 错误提示、危险操作 |
| Agent/AI | `dark-purple` | `#553ba3` | AI 指示器、Skill 标签 |

## 依赖要求

- [Qoder](https://qoder.com) IDE 或 CLI
- TailwindCSS（使用 Token 类名时需要）

## 许可声明

本 Skill 仅供开发参考，引用了西门子企业设计规范相关内容。西门子品牌资产及设计规范版权归西门子股份公司所有。
