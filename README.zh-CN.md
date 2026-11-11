# write-skill：Claude Code 版

[双语说明](README.md)

## 用途

本公开仓库提供介绍。私有核心仓库提供可使用的技能。

## 能力

中英文申请文书。先核对规则和事实，再组织论证、起草或编辑。

## 双仓

[公开介绍](https://github.com/Shawn200212/write-skill_claude) · [私有核心](https://github.com/Shawn200212/write-skill_claude-core)

## 安装

使用有权限的账户拉取私有核心仓库。先预览安装，再应用更改。

```text
git clone https://github.com/Shawn200212/write-skill_claude-core.git
cd write-skill_claude-core
python install.py
python install.py --apply
```

## 调用

安装后，在 Claude Code 中调用 `/write-skill:write-skill`。检查安装输出中的未满足依赖。

## 依赖

包内含技能指令和必要的小型资源。外部应用、项目文件和论文库需要另行准备。

## 核查

本次发布记录结构检查、相关本地测试和有限写作试验。这些检查不能证明全部流程或模型均已通过。

## 边界

本技能不保证录用、作者身份判断或通用写作质量。实际应用操作需要满足依赖并另行验证。

## 插件

完成配置后，用 `claude --plugin-dir .` 加载此目录。
