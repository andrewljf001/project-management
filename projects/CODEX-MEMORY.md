# Codex Sync Memory (Project Rules)

Last updated: 2026-05-27

1. 当你说“同步进度”时，必须只用 GitHub 在线同步（纯 API），不做本地仓库克隆或长期保存。
2. 本地仅允许必要的临时文件缓存（例如 `/private/tmp` 中的 API 响应），任务完成后必须清理。
3. 主查看入口是：`https://andrewljf001.github.io/project-management/dashboard/`。
4. `dashboard-CODEX` 是测试/验证入口：`https://andrewljf001.github.io/project-management/dashboard-CODEX/`。
5. 同步时要读取 GitHub 全部仓库状态，再更新看板数据（至少 `dashboard/data.json` 与 `dashboard-CODEX/data.json`）。
6. 项目已迁移/结束时，要在对应项目进度文件标记“全部已完成，项目已迁移”，并同步看板状态。
7. 未经明确要求，不额外改页面风格、结构和非必要文件。
8. 用户让改再改；先确认目标，再执行。
