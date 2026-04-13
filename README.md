# 军师 (Junshi Advisor) | Strategic Advisor

> 愿「军师.skill」助阁下决胜职场。
> May the Junshi Skill help you triumph in your career.

[![Qoder Skill](https://img.shields.io/badge/Qoder-Skill-blue)](https://qoder.com)
[![Version](https://img.shields.io/badge/version-2.0.0-green)](./config.yaml)
[![License](https://img.shields.io/badge/license-MIT-yellow)](./LICENSE)

**中文**: 军师是一个 [QoderWork](https://qoder.com) 智能体技能，将军事理论与管理智慧转化为可执行的职场决策建议。

**English**: Junshi (军师) is a [QoderWork](https://qoder.com) AI agent skill that transforms military strategy and management wisdom into actionable workplace decision-making advice.

---

## 核心特点 | Key Features

- **12大谋略模块** | **12 Strategic Modules**: 涵盖军事经典与商业管理理论 | Covering military classics and business management theories
- **模块化架构** | **Modular Architecture**: YAML 定义 + Markdown 模板，易于扩展 | YAML definitions + Markdown templates for easy extension
- **结构化输出** | **Structured Output**: 诊断 → 评估 → 建议 → 点睛 → 避坑 | Diagnosis → Assessment → Advice → Insight → Pitfall Avoidance
- **沉浸式体验** | **Immersive Experience**: 军师语气（在下/阁下），增强信任感与仪式感 | Advisor tone (humble servant / honored lord) enhances trust and ceremony

---

## 谋略模块一览 | Strategic Modules Overview

### 军事理论模块（六大经典）| Military Theory Modules (6 Classics)

| 模块 Module | 来源 Source | 适用场景 Use Cases |
|-------------|-------------|-------------------|
| **五事七计** Five Affairs & Seven Calculations | 《孙子兵法》The Art of War | 项目立项、可行性评估 Project initiation, feasibility assessment |
| **先为不可胜** Invincibility First | 《孙子兵法》The Art of War | 风险评估、止损决策 Risk assessment, stop-loss decisions |
| **重心打击** Center of Gravity Strike | 《战争论》On War | 优先级排序、资源聚焦 Priority sorting, resource focus |
| **阶段划分** Phase Division | 《论持久战》On Protracted War | 长期项目、坚持策略 Long-term projects, persistence strategies |
| **非对称作战** Asymmetric Warfare | 《超限战》Unrestricted Warfare | 以小博大、竞争策略 Competing against larger opponents |
| **摩擦预留** Friction Reserve | 《战争论》On War | 排期规划、缓冲管理 Scheduling, buffer management |

### 商业/管理理论模块（六大扩展）| Business/Management Modules (6 Extensions)

| 模块 Module | 来源 Source | 适用场景 Use Cases |
|-------------|-------------|-------------------|
| **跨越鸿沟** Crossing the Chasm | 《跨越鸿沟》Crossing the Chasm | 新产品上市、市场推广 New product launch, marketing |
| **创新者的窘境** Innovator's Dilemma | 《创新者的窘境》The Innovator's Dilemma | 内部创新、颠覆式创新 Internal innovation, disruptive innovation |
| **蓝海战略** Blue Ocean Strategy | 《蓝海战略》Blue Ocean Strategy | 差异化竞争、价值创新 Differentiation, value innovation |
| **黑天鹅** Black Swan | 《黑天鹅》The Black Swan | 危机应对、极端事件 Crisis response, extreme events |
| **影响力** Influence | 《影响力》Influence | 向上管理、跨部门沟通 Managing up, cross-department communication |
| **反脆弱** Antifragile | 《反脆弱》Antifragile | 职业风险配置、杠铃策略 Career risk allocation, barbell strategy |

---

## 安装使用 | Installation

### 方式一：QoderWork 技能市场（待上架）| Method 1: QoderWork Skill Marketplace (Coming Soon)

等待官方技能市场上架后，直接在 QoderWork 中搜索"军师"安装。

Once officially listed, search for "Junshi" or "军师" in QoderWork to install.

### 方式二：手动安装 | Method 2: Manual Installation

1. 克隆本仓库到本地 | Clone this repository:
```bash
git clone https://github.com/yourname/junshi-advisor.git
```

2. 复制到 QoderWork skills 目录 | Copy to QoderWork skills directory:
```bash
# macOS/Linux
cp -r junshi-advisor ~/.qoderwork/skills/

# Windows
xcopy /E /I junshi-advisor %USERPROFILE%\.qoderwork\skills\junshi-advisor
```

3. 重启 QoderWork 或开新对话，技能自动加载。

Restart QoderWork or start a new chat session. The skill will auto-load.

---

## 使用示例 | Usage Examples

### 示例 1：项目立项决策 | Example 1: Project Initiation Decision

**用户 User**: 老板让我牵头一个新项目，要不要接？My boss wants me to lead a new project. Should I take it?

**军师 Junshi**（触发「五事七计」Trigger: Five Affairs & Seven Calculations）：
> 【军师诊断】阁下正面临一次"庙算"问题...
> 【Strategic Diagnosis】You face a "temple calculation" challenge...
>
> 【五事评估】Five Affairs Assessment
> - 道（共识）Tao (Consensus): 团队内部是否达成共识？上级是否支持？Does the team have consensus? Does leadership support this?
> - 天（时机）Tian (Timing): 当前市场时机、政策环境如何？What's the current market timing and policy environment?
> ...

### 示例 2：风险评估 | Example 2: Risk Assessment

**用户 User**: 这个方案风险太大，我怕搞砸 This plan is too risky. I'm afraid I'll mess it up.

**军师 Junshi**（触发「先为不可胜」Trigger: Invincibility First）：
> 【军师诊断】阁下正面临一个"风险评估"问题...
> 【Strategic Diagnosis】You face a risk assessment challenge...
>
> 【风险评估】Risk Assessment
> - 最坏情况 Worst Case: {worst_loss}
> - 可承受性 Affordability: {can_afford}
> ...

### 示例 3：向上管理 | Example 3: Managing Up

**用户 User**: 如何推动领导层解决一线的问题？How can I push leadership to solve frontline problems?

**军师 Junshi**（触发「影响力」+「跨越鸿沟」Trigger: Influence + Crossing the Chasm）：
> 【军师诊断】阁下正面临"跨越鸿沟"的经典困境...
> 【Strategic Diagnosis】You face the classic "crossing the chasm" dilemma...
>
> 【六大影响力策略】Six Principles of Influence
> 1. 互惠 Reciprocity: 先给领导一份竞品情报...First give leadership competitive intelligence...
> 2. 社会认同 Social Proof: 展示同行成功案例...Show peer success cases...
> ...

---

## 工程结构 | Project Structure

```
junshi-advisor/
├── SKILL.md              # 主技能文件 | Main skill file
├── config.yaml           # 全局配置 | Global configuration
├── modules/              # 谋略模块（YAML，12个）| Strategy modules (12 YAML files)
│   ├── five_affairs.yaml
│   ├── invincible_first.yaml
│   ├── crossing_the_chasm.yaml
│   └── ...
└── templates/            # 输出模板（Markdown，12个）| Output templates (12 Markdown files)
    ├── five_affairs.md
    ├── invincible_first.md
    ├── crossing_the_chasm.md
    └── ...
```

---

## 扩展新模块 | Extending with New Modules

无需修改 SKILL.md，只需两步 | No need to modify SKILL.md, just two steps:

1. 在 `modules/` 下新建 `your_module.yaml` | Create `your_module.yaml` in `modules/`:
```yaml
id: your_module
name: 你的模块名 | Your Module Name
version: "1.0.0"
source: "理论来源 | Theory Source"
category: 分类 | Category
priority: 80
keywords:
  - 关键词1 | keyword1
  - 关键词2 | keyword2
input_prompts:
  - 追问问题1 | Follow-up question 1
  - 追问问题2 | Follow-up question 2
analysis_logic:
  dimensions:
    - 维度1 | Dimension 1
    - 维度2 | Dimension 2
output_template: your_module.md
```

2. 在 `templates/` 下新建 `your_module.md`，使用 `{variable}` 占位符。

Create `your_module.md` in `templates/` using `{variable}` placeholders.

重新加载即可生效。Reload to activate.

---

## 贡献指南 | Contributing

欢迎提交 Issue 和 PR！Issues and PRs welcome!

- 发现 bug？请提交 Issue，描述复现步骤 | Found a bug? Submit an issue with reproduction steps
- 想新增模块？参考现有模块格式，提交 PR | Want to add a module? Reference existing format and submit a PR
- 有改进建议？欢迎讨论 | Have suggestions? Join the discussion

---

## 许可证 | License

[MIT License](./LICENSE)

---

## 致谢 | Acknowledgments

- **军事理论 Military Theory**:《孙子兵法》The Art of War、克劳塞维茨《战争论》Clausewitz's On War、毛泽东《论持久战》Mao's On Protracted War、乔良/王湘穗《超限战》Qiao Liang/Wang Xiangsui's Unrestricted Warfare
- **管理理论 Management Theory**: 杰弗里·摩尔 Geoffrey Moore、克莱顿·克里斯坦森 Clayton Christensen、W·钱·金 W. Chan Kim、纳西姆·塔勒布 Nassim Taleb、罗伯特·西奥迪尼 Robert Cialdini
- **平台 Platform**: [QoderWork](https://qoder.com)

---

**愿「军师.skill」助阁下决胜职场。**
**May the Junshi Skill help you triumph in your career.**
