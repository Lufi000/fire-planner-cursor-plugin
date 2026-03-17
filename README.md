# FIRE 路径规划顾问 · Cursor Plugin

在 Cursor 里通过对话帮你发现「领域 × 杠杆」方向，并规划财务自由（FIRE）路径。

## 功能

- **用户画像**：通过聊天收集你的背景、技能、资源、目标与风险偏好  
- **方向推荐**：基于画像推荐 2–3 个「领域 × 杠杆」组合（代码/内容/资本/人力）  
- **路径规划**：FIRE 数字、里程碑、第一周/第一个月行动清单  

## 如何使用

安装本插件后，在 Cursor 对话里输入例如：

- 「开始规划」
- 「FIRE 规划」
- 「我想做副业 / 想创业」
- 「职业规划」「领域杠杆」

Agent 会按 skill 引导你完成画像 → 方向推荐 → 路径规划，并把结果写入当前项目下的 `users/{你的名字}/画像.md` 和 `规划.md`。

## 安装方式

### 从 Cursor Marketplace（若已上架）

在 Cursor 内打开 Marketplace，搜索「FIRE」或「fire-planner」，点击安装。

### 从本仓库（手动 / Team Marketplace）

1. **手动安装为 Skill**  
   - 克隆或下载本仓库，将 `skills/fire-planner/` 整个文件夹复制到：  
     - 用户级：`~/.cursor/skills/fire-planner/`  
     - 或项目级：你的项目根目录下的 `.cursor/skills/fire-planner/`  
   - 重启或重新加载 Cursor。

2. **Team / Enterprise 团队仓库**  
   - 在 Cursor Dashboard → Settings → Plugins → Team Marketplaces 中添加本仓库 URL，团队成员即可从 Marketplace 面板安装。

## 不用 Cursor，只用 Claude？

见 **`claude/`** 目录：内有可直接粘贴到 Claude「自定义说明」或第一条消息的 **FIRE 规划顾问系统说明**，以及可选上传的画像/规划模板。详见 [claude/README.md](claude/README.md)。

## 许可

MIT（若仓库中未单独声明，可自行添加 LICENSE 文件）。
