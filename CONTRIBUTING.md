# 贡献指南

感谢您对「军师」技能的兴趣！欢迎提交 Issue 和 Pull Request。

## 如何贡献

### 报告问题

如果您发现了 bug 或有改进建议：

1. 先搜索现有 Issue，避免重复
2. 创建新 Issue，描述：
   - 问题现象
   - 复现步骤
   - 期望行为
   - 实际行为

### 提交新模块

军师支持模块化扩展，欢迎贡献新的谋略模块！

#### 模块规范

每个模块需要两个文件：

**1. modules/{module_id}.yaml**

```yaml
id: module_id           # 唯一标识，小写+下划线
name: 模块名称           # 中文显示名
version: "1.0.0"        # 版本号
source: "理论来源"       # 书名/作者
category: 分类           # 如：战略评估、风险评估
priority: 80            # 匹配优先级（1-100）

keywords:               # 触发关键词列表
  - 关键词1
  - 关键词2

input_prompts:          # 向用户追问的问题
  - 问题1
  - 问题2

analysis_logic:         # 分析逻辑定义
  dimensions:
    - 维度1
    - 维度2

output_template: module_id.md
```

**2. templates/{module_id}.md**

输出模板必须使用以下五个部分：

```markdown
【军师诊断】...理论来源引用...

【XX评估/分析】...维度分析...

【在下建议】...分层级建议...

【军师点睛】...一句名言...

【避坑指南】...常见误区...
```

变量使用 `{variable_name}` 格式。

#### 提交流程

1. Fork 本仓库
2. 创建分支：`git checkout -b add-module-{module_name}`
3. 添加模块文件（YAML + Markdown）
4. 更新 README.md 模块列表
5. 提交 PR，描述模块用途和理论来源

### 改进现有模块

- 优化追问问题的表述
- 完善分析维度的定义
- 改进输出模板的结构
- 补充理论来源的引用

## 代码规范

- YAML 使用 2 空格缩进
- 模块 ID 使用小写字母+下划线
- 中文标点使用全角符号
- 保持「在下/阁下」称谓一致性

## 审核流程

- 所有 PR 需要至少 1 个 Reviewer 批准
- 新模块需要说明理论来源的权威性
- 保持与现有模块的风格一致性

## 联系我们

- Issue: https://github.com/yourname/junshi-advisor/issues
- Discussion: 欢迎发起讨论分享使用心得

感谢您对「军师」的贡献！
