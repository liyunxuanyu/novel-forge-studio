# Novel Forge Studio

这是 Novel Forge 的综合项目，统一存放 AI 小说生产工程与后续小说创作资料。

## 目录约定

- `lib/`、`test/`、`skills/`、`scripts/`：Novel Forge AI 工程源码、技能和测试。
- `docs/`：AI 工程设计、参考项目和 DSH 集成说明。
- `novels/门世界/拆文库/`：门世界项目的拆文资料。每个作品保持一个独立目录，原始文件层级不改写，便于追溯来源。
- `novels/`：后续小说创作区。新作品使用“系列或世界观/作品名/”三级归档；正文、设定、拆文、草稿和定稿由作品目录自行管理。

## Git 历史与分支

本项目从原 `novel-forge` 仓库完整克隆，保留原有提交历史、提交对象和分支引用。

- `master`：原始基线。
- `gpt`：只允许通过 Codex 修改。
- `zcode`：只允许通过 zcode 修改。
- `harness`：只允许通过 DeepSeek Harness 修改。

根目录 `AGENTS.md` 是当前分支的协作约束。它是代理行为规则；Git 本身不能识别编辑客户端，因此不能替代权限控制。

## 合并原则

AI 工程改动与小说内容改动都必须通过 Git 提交。小说资料默认先进入对应作品目录，再由工具生成或更新书仓真源；不要把个人草稿散落在项目根目录。

三个参考项目的能力边界仍保持为：Biz 负责角色推动，Scriptor 负责机制分析，oh-story 负责结构与章节组织。它们是设计来源，不代表直接复制代码或文本。

## 来源记录

- AI 工程来源：原目录 `D:\workspace\Agent WorkSpace\novel-forge`
- 拆文资料来源：`D:\workspace\小说\门世界\拆文库`
- 本综合项目：`D:\workspace\Agent WorkSpace\novel-forge-studio`
