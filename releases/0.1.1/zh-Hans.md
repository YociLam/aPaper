# aPaper 0.1.1

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ko.md)


## 新功能
- 模型设置和对话输入框统一采用各模型的推理强度预设。
- 研究图表与交互视图采用统一样式，支持已核验的来源摘录和视图状态保存。
- 可直接从资料库右键菜单导入文献。

## 改进
- 提升会话列表、流式回答和知识图谱更新的响应表现。
- 查看结果可在卡片或图谱模式中定位本次操作的文献。
- 重启后接续符合条件的已保存沉淀任务；依赖恢复可用时自动重试可恢复的错误，保留处理设置和已有知识。

## 问题修复
- 防止多个 App 实例同时打开同一工作区，并保留 SQLite 事务锁。
- 为知识库启动瞬态失败提供有限恢复和清晰提示。
- 恢复失败或停止回答后的问题编辑与重试。
- 修正侧边栏悬停展开、整理弹窗、引导页导航和授权控件。
- 保留可用的 Dogzee 模型分组，避免可选的密钥名称更新失败导致分组消失。
- 改善研究助理的附件访问、项目资源操作和命令运行可靠性。
- 使用 Zotero 已有标识或标题整理元数据，并保留用户编辑。
- 移动到和复制到菜单按文件夹层级展开。
- 鼠标悬停灵动岛时，滚动保持在岛内，覆盖标题和边缘区域。

[完整更新日志](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)
