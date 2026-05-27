# 🚀 XXXX 云平台 · 项目管理看板

> 科技感 3D 渲染风格项目管理仪表盘 | Tech-Style Project Management Dashboard

## 📋 当前项目清单

| 项目 | 状态 | 进度 | 当前阶段 |
|------|------|------|----------|
| [521ARC-product-analysis](projects/521ARC-product-analysis.md) | 🟢 active | 15% | Phase 1：产品分析 + Amazon Listing 优化 |
| [CC-pcba-order-website](projects/CC-pcba-order-website.md) | 🟢 active | 40% | Phase 3：三模式报价计算器完善中 |
| [pcbaforge-platform](projects/pcbaforge-platform.md) | ⬛ archived | 100% | 全部已完成，项目已迁移 |
| [pcb-order-website](projects/pcb-order-website.md) | ⬛ archived | 100% | 全部已完成，项目已迁移 |
| [mrocioa-seo](projects/mrocioa-seo.md) | 🟢 active | 5% | Phase 1：基础建设与数据监控 |
| [DCX-wastewater-process](projects/DCX-wastewater-process.md) | 🟢 active | 5% | 项目初始化 |
| [commercial-display-b2b](projects/commercial-display-b2b.md) | 🟢 active | 5% | v1.0 首页 + 产品页 + WhatsApp 对接 |
| [chinese-ceramic-art](projects/chinese-ceramic-art.md) | 🟢 active | 5% | v1.0 首页 + 藏品页 + 联系页 |
| [lidar-promo-website](projects/lidar-promo-website.md) | 🟢 active | 5% | 初始化，待开发 |
| [IDE-Migration](projects/IDE-Migration.md) | 🔵 planning | 0% | Phase 1：Mac 环境配置（未开始）|
| [website-optimization](projects/website-optimization.md) | ⬛ archived | 85% | 已归档 2026-05-24 |

## 🗂 仓库结构

```
project-management/
├── README.md              # 项目清单 + 规则总览
├── dashboard/
│   ├── index.html         # 看板模板（只生成一次，永不修改）
│   └── data.json          # 数据文件（每次同步只更新此文件）
├── projects/              # 各项目进度快照
│   ├── 521ARC-product-analysis.md
│   ├── pcbaforge-platform.md
│   ├── CC-pcba-order-website.md
│   ├── pcb-order-website.md
│   ├── mrocioa-seo.md
│   ├── DCX-wastewater-process.md
│   ├── commercial-display-b2b.md
│   ├── chinese-ceramic-art.md
│   ├── lidar-promo-website.md
│   ├── IDE-Migration.md
│   └── website-optimization.md
└── logs/                  # 同步记录
    └── 2026-05.md
```

## 预览

深蓝色科技主题，包含：
- 🌐 全球网络节点地球仪（动态光晕）
- 📊 项目分类饼图 + 进度条
- 📋 四栏任务看板（待办 / 进行中 / 评审中 / 已完成）
- 📈 周趋势折线图
- 🖥 系统资源状态监控
- 🔔 实时动态消息流
- 🕐 实时时钟

## 触发词速查

| 触发词 | 动作 |
|--------|------|
| 「同步进度」 | 读各仓库 → 只更新 data.json |
| 「本周计划」 | 按截止日期 + 重要性排序 |
| 「更新日历」 | 把里程碑写入 Google Calendar |
| 「加一个项目」 | 更新 README.md + 新建 projects/*.md |

## 技术栈

- 纯 HTML / CSS / JavaScript（零依赖）
- CSS Grid 布局 / SVG 图表 / CSS 动画

## GitHub Pages

Settings → Pages → Branch: main → 开启后可在线预览看板。

---
最后更新：2026-05-26 | Made with ⚡ by andrewljf001


规则说明：项目执行规则以  为唯一准则。
