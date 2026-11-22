# 青铜纹样产品设计

[English](README.md)

一个中英双语 Codex Skill，把中国古代青铜器纹样用在实用产品上。重点是把**贴近来源的重绘**和**面向工艺的应用稿**分开：保留有辨识度的结构，不让装饰占用产品的功能区。

| 任务 | 可辅助完成 |
|---|---|
| 纹样识读 | 名称、可见特征、不确定点、图源记录 |
| 近源重绘 | 原图对照；按需另做可编辑的应用矢量 |
| 产品设计 | 纹样位置、功能留空区、材料和打样检查 |
| 展板打印 | 产品主视觉、来源说明、单色打印 PDF |

## 安装

克隆或下载此仓库。把完整的 [`skills/bronze-pattern-design`](skills/bronze-pattern-design) 文件夹复制到用户目录下的 `~/.agents/skills/`，或复制到目标项目的 `.agents/skills/`。发现规则和调用方式参见 [Codex Skills 官方文档](https://developers.openai.com/codex/skills)。

## 示例

附上展板照片或馆藏链接，然后输入：

> 用 $bronze-pattern-design 根据展签辨识这些纹样。用 ImageGen 贴近原纹重绘龙纹和凤鸟纹，设计一支笔和一本笔记本。别占用握位和书写区。交付 A4 横向黑白展板：左边产品，右上重绘，右下来源，不标图号。

除非用户指定，否则可按任务选用 ImageGen 或其他绘制工具。这是指令型 Skill，本身不需要 API 密钥、脚本或额外服务，不用于文物鉴定，也不代表博物馆授权或联名。仓库不包含原始展板照片。

## 文件

- [Skill 主说明](skills/bronze-pattern-design/SKILL.md)
- [中英纹样识读](skills/bronze-pattern-design/references/motif-field-guide.md)
- [产品转译与展板流程](skills/bronze-pattern-design/references/product-and-board.md)
