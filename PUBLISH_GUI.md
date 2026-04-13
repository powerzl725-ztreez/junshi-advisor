# GitHub 网页版发布指南（纯点击操作）

## 第一步：在 GitHub 上创建仓库

1. 打开 https://github.com/new

2. 填写信息：
   - **Repository name**: `junshi-advisor`
   - **Description**: 职场军师决策辅助技能 - 将军事理论与管理智慧转化为可执行的职场决策建议
   - 选择 **Public**（公开）
   - ✅ 勾选 **"Add a README file"**（先让GitHub创建一个空的）

3. 点击 **Create repository**

## 第二步：上传文件到 GitHub

创建完仓库后，你会看到仓库页面。

### 方法A：直接拖拽上传（最简单）

1. 在你的电脑上，打开文件夹：`E:\AgentOutcomes\codebuddy\军师\junshi-advisor-github`

2. 选中所有文件和文件夹（Ctrl+A），压缩成一个 zip 文件：
   - 右键 → "发送到" → "压缩(zipped)文件夹"
   - 或者右键 → "7-Zip" → "添加到 junshi-advisor.zip"

3. 回到 GitHub 网页，点击 **"Add file"** → **"Upload files"**

4. 把 zip 文件拖进去，或者点击 "choose your files" 选择 zip

5. 等待上传完成，点击 **"Commit changes"**

6. 上传后点击 zip 文件，然后点击 **"Delete"** 删除 zip（因为我们只需要里面的内容）

### 方法B：逐个文件上传

1. 在 GitHub 仓库页面，点击 **"Add file"** → **"Create new file"**

2. 文件名输入：`SKILL.md`

3. 内容把我给你的 SKILL.md 内容复制粘贴进去

4. 点击 **"Commit new file"**

5. 重复上述步骤，逐个创建：
   - `config.yaml`
   - `README.md`
   - `LICENSE`
   - `CONTRIBUTING.md`
   - `.gitignore`

6. 创建文件夹：
   - 点击 **"Add file"** → **"Create new file"**
   - 文件名输入：`modules/five_affairs.yaml`（斜杠会自动创建文件夹）
   - 粘贴对应文件内容
   - 点击 Commit

## 第三步：验证发布

1. 打开 `https://github.com/powerzl725-ztreez/junshi-advisor`

2. 确认能看到：
   - README.md 内容正常显示
   - modules 文件夹里有 12 个 yaml 文件
   - templates 文件夹里有 12 个 md 文件

## 完成！

发布后仓库地址：https://github.com/powerzl725-ztreez/junshi-advisor

---

## 推荐：使用 GitHub Desktop（图形化工具）

如果文件太多，网页一个个上传太麻烦，可以下载 GitHub Desktop：

1. 下载：https://desktop.github.com/

2. 安装后登录你的 GitHub 账号

3. 点击 **"File"** → **"Add local repository"**

4. 选择文件夹：`E:\AgentOutcomes\codebuddy\军师\junshi-advisor-github`

5. 点击 **"Publish repository"**

6. 填写仓库名 `junshi-advisor`，选择 Public，点击发布

这样所有文件就一次性上传了。
