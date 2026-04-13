# GitHub 发布指南

## 前置要求

- 已安装 Git：https://git-scm.com/downloads
- 已有 GitHub 账号：powerzl725-ztreez
- 已登录 GitHub 网页版

## 发布步骤

### 第一步：初始化 Git 仓库

打开命令提示符（CMD）或 PowerShell，执行：

```bash
cd "E:\AgentOutcomes\codebuddy\军师\junshi-advisor-github"
git init
```

### 第二步：配置 Git 用户信息（如未配置过）

```bash
git config user.name "powerzl725-ztreez"
git config user.email "你的邮箱@example.com"
```

### 第三步：添加文件并提交

```bash
git add .
git commit -m "Initial commit: Junshi Advisor Skill v2.0.0

- 12个谋略模块（6个军事理论 + 6个商业管理）
- 模块化架构：YAML配置 + Markdown模板
- 支持动态加载和版本管理
- 完整文档和贡献指南"
```

### 第四步：在 GitHub 创建仓库

1. 打开 https://github.com/new
2. Repository name 填写：`junshi-advisor`
3. Description 填写：职场军师决策辅助技能 - 将军事理论与管理智慧转化为可执行的职场决策建议
4. 选择 **Public**（公开）
5. 不要勾选 "Initialize this repository with a README"（因为我们已经有 README 了）
6. 点击 **Create repository**

### 第五步：关联远程仓库并推送

```bash
git remote add origin https://github.com/powerzl725-ztreez/junshi-advisor.git
git branch -M main
git push -u origin main
```

### 第六步：验证发布

1. 打开 https://github.com/powerzl725-ztreez/junshi-advisor
2. 确认所有文件都已上传
3. 检查 README 是否正常显示

## 可选：添加话题标签（Topics）

在 GitHub 仓库页面，点击右侧 "About" 旁边的齿轮，添加话题：

- qoder
- qoder-skill
- ai-agent
- career-advice
- decision-making
- sunzi
- military-strategy

## 可选：创建 Release

1. 在 GitHub 仓库页面，点击右侧 "Releases"
2. 点击 "Create a new release"
3. Tag version: `v2.0.0`
4. Release title: `军师 Skill v2.0.0 - 十二谋略模块`
5. 描述可以复制 README 的简介部分
6. 点击 "Publish release"

## 完成！

发布后仓库地址：https://github.com/powerzl725-ztreez/junshi-advisor

可以分享给他人使用，也可以向 Qoder 官方申请上架技能市场。
