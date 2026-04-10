# SocialThinker-Skill 🧠

> **让历史上最伟大的社会学家、思想家和哲学家成为你的智囊团**
>
> AI Skills + Multi-Agent Analysis for Critical Thinking, Global Affairs & Intellectual Enlightenment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 简介 | Introduction

**SocialThinker-Skill** 是一套面向 CodeBuddy / AI 编程助手的 **Skill + Agent 集合**，将历史上最伟大的社会学家、经济学家、政治哲学家的**知识体系和思维方法**转化为可调用的 AI 技能和可并行执行的分析 Agent。

核心特色：

- 🧠 **10 位思想家 Skill** — 每位思想家的完整方法论框架、分析步骤、输出规范
- 🤖 **10 个专用分析 Agent** — 每个 Agent 模仿一位思想家，调用对应 Skill 独立分析
- 🔄 **多 Agent 并行分析** — 多个 Agent 同时启动，从不同视角分析同一问题，最后综合总结
- 📋 **4 大分析模板** — 世界新闻、经济形势、社会问题、未来走向的结构化分析流程
- 📚 **完整的参考资料** — 每位思想家的著作详解和学术脉络

---

## 🏛️ 思想家名录 | Thinker Roster

本项目收录了 **10 位** 横跨社会学、经济学、政治哲学和科学哲学的伟大思想家：

| # | 思想家 | Thinker | 领域 | 核心方法论 | Skill | Agent |
|---|--------|---------|------|-----------|-------|-------|
| 1 | 亚当·斯密 | Adam Smith (1723-1790) | 经济学 | 看不见的手、分工、道德情操 | ✅ | ✅ |
| 2 | 马克斯·韦伯 | Max Weber (1864-1920) | 社会学 | 理想类型、理性化、权威类型 | ✅ | ✅ |
| 3 | 埃米尔·涂尔干 | Émile Durkheim (1858-1917) | 社会学 | 社会事实、失范、社会团结 | ✅ | ✅ |
| 4 | 凯恩斯 | J.M. Keynes (1883-1946) | 经济学 | 总需求、动物精神、乘数效应 | ✅ | ✅ |
| 5 | 哈耶克 | F.A. Hayek (1899-1992) | 经济学 | 知识问题、自发秩序、自由 | ✅ | ✅ |
| 6 | 汉娜·阿伦特 | Hannah Arendt (1906-1975) | 政治哲学 | 极权主义、平庸之恶、公共领域 | ✅ | ✅ |
| 7 | 米歇尔·福柯 | Michel Foucault (1926-1984) | 哲学 | 权力/知识、话语分析、生命政治 | ✅ | ✅ |
| 8 | 马基雅维利 | N. Machiavelli (1469-1527) | 政治学 | 政治现实主义、能力与命运 | ✅ | ✅ |
| 9 | 雷·达里奥 | Ray Dalio (b. 1949) | 经济学 | 大周期、债务周期、五大力量 | ✅ | ✅ |
| 10 | 卡尔·波普尔 | Karl Popper (1902-1994) | 科学哲学 | 可证伪性、开放社会、批判理性 | ✅ | ✅ |

---

## 📂 项目结构 | Project Structure

```
SocialThinker-Skill/
├── README.md                          # 项目说明（本文件）
├── LICENSE                            # MIT 许可证
│
├── agents/                            # 🤖 Agent 定义文件
│   ├── social-thinker-analyst.md      # 主协调 Agent（多Agent并行分析）
│   └── thinkers/                      # 各思想家专用 Agent
│       ├── smith-analyst.md           # 亚当·斯密分析 Agent
│       ├── weber-analyst.md           # 韦伯分析 Agent
│       ├── durkheim-analyst.md        # 涂尔干分析 Agent
│       ├── keynes-analyst.md          # 凯恩斯分析 Agent
│       ├── hayek-analyst.md           # 哈耶克分析 Agent
│       ├── arendt-analyst.md          # 阿伦特分析 Agent
│       ├── foucault-analyst.md        # 福柯分析 Agent
│       ├── machiavelli-analyst.md     # 马基雅维利分析 Agent
│       ├── dalio-analyst.md           # 达里奥分析 Agent
│       └── popper-analyst.md          # 波普尔分析 Agent
│
├── docs/                              # 📄 分析报告存档
│   └── world-analysis-2026-04.md      # 示例：2026年4月世界形势分析
│
└── skills/                            # 🧠 Skill 文件
    ├── references/
    │   └── comprehensive-analysis-templates.md  # 综合分析模板（含Agent调用规范）
    │
    ├── adam-smith-亚当斯密/
    │   ├── SKILL.md
    │   └── references/
    │       └── adam-smith-works.md
    │
    ├── max-weber-马克斯韦伯/
    │   ├── SKILL.md
    │   └── references/
    │       └── max-weber-works.md
    │
    ├── emile-durkheim-埃米尔涂尔干/
    │   ├── SKILL.md
    │   └── references/
    │       └── emile-durkheim-works.md
    │
    ├── john-maynard-keynes-约翰梅纳德凯恩斯/
    │   ├── SKILL.md
    │   └── references/
    │       └── keynes-works.md
    │
    ├── friedrich-hayek-弗里德里希哈耶克/
    │   ├── SKILL.md
    │   └── references/
    │       └── hayek-works.md
    │
    ├── hannah-arendt-汉娜阿伦特/
    │   ├── SKILL.md
    │   └── references/
    │       └── hannah-arendt-works.md
    │
    ├── michel-foucault-米歇尔福柯/
    │   ├── SKILL.md
    │   └── references/
    │       └── michel-foucault-works.md
    │
    ├── niccolo-machiavelli-尼科洛马基雅维利/
    │   ├── SKILL.md
    │   └── references/
    │       └── machiavelli-works.md
    │
    ├── ray-dalio-雷达里奥/
    │   ├── SKILL.md
    │   └── references/
    │       └── ray-dalio-works.md
    │
    └── karl-popper-卡尔波普尔/
        ├── SKILL.md
        └── references/
            └── karl-popper-works.md
```

---

## 🚀 使用方式 | How to Use

### 方式一：单思想家视角分析

安装特定思想家的 Skill，以该思想家的视角分析问题：

1. 将对应思想家文件夹复制到 `~/.codebuddy/skills/` 或项目的 `.codebuddy/skills/` 目录
2. 在对话中使用触发词激活 Skill
3. AI 将以该思想家的完整方法论框架分析你提出的问题

**触发词示例：**

| 场景 | 触发词 | 调用 Skill |
|------|-------|-----------|
| 经济分析 | "用经济学视角分析..." | Adam Smith / Keynes / Hayek |
| 权力分析 | "分析这个权力结构..." | Foucault / Machiavelli / Arendt |
| 社会问题 | "这个社会现象的根源..." | Weber / Durkheim |
| 周期分析 | "当前经济周期在哪个阶段..." | Ray Dalio |
| 批判思考 | "这个说法是否站得住脚..." | Karl Popper |

### 方式二：多 Agent 并行分析（推荐 ⭐）

这是本项目最核心的使用方式：**启动多个 Agent，每个 Agent 模仿一位思想家，调用对应的 Skill 独立分析，最后综合总结。**

#### 工作流程

```
用户提出问题
    ↓
① 信息收集：web_search 搜索最新事实和数据
    ↓
② 选择思想家组合：根据问题类型选择 3-8 位思想家
    ↓
③ 并行启动 Agent：每位思想家 → 一个 Agent → 读取 Skill → 独立分析
    ↓
④ 综合总结：共识 · 分歧 · 预判 · 风险 · 希望
    ↓
⑤ 输出报告并保存到 docs/
```

#### Agent 启动方式

**Team 模式（推荐，并行执行）：**

```
1. team_create("analysis-team")        → 创建分析团队
2. task(name="weber", team_name=...)    → 启动韦伯 Agent（异步）
3. task(name="keynes", team_name=...)   → 启动凯恩斯 Agent（异步）
4. task(name="foucault", team_name=...) → 启动福柯 Agent（异步）
5. ... 更多 Agent 并行启动
6. send_message()                       → 收集各 Agent 结果
7. 综合总结
8. team_delete()                        → 清理团队
```

**每个 Agent 的核心行为：**

```python
# 1. 读取对应 Skill
read_file("skills/max-weber-马克斯韦伯/SKILL.md")

# 2. 严格使用该思想家的分析工具
#    - Core Intellectual Framework 中的每个概念
#    - Analytical Methodology 中的每个步骤
#    - Response Framework 中的输出格式

# 3. 独立分析（不参考其他思想家观点）

# 4. 返回结构化分析结果
```

#### 思想家组合推荐

| 问题类型 | 推荐思想家 | 核心维度 |
|---------|-----------|---------|
| 🌍 **世界形势/地缘政治** | 韦伯 + 马基雅维利 + 阿伦特 + 达里奥 + 福柯 | 权威·权力·秩序·周期·话语 |
| 📊 **经济形势/宏观分析** | 斯密 + 凯恩斯 + 哈耶克 + 达里奥 | 市场·需求·秩序·周期 |
| 🏘️ **社会问题/文化冲突** | 韦伯 + 涂尔干 + 福柯 + 阿伦特 + 波普尔 | 结构·团结·权力·公共·批判 |
| 💻 **技术与社会** | 福柯 + 韦伯 + 哈耶克 + 波普尔 + 达里奥 | 监控·理性·秩序·证伪·创新 |
| 📜 **政策评估** | 凯恩斯 + 哈耶克 + 斯密 + 波普尔 + 达里奥 | 干预·自由·市场·检验·周期 |
| 🔮 **未来预判** | 达里奥 + 波普尔 + 阿伦特 + 韦伯 + 哈耶克 | 周期·证伪·诞生·理性·演化 |

#### 完整示例：分析当前世界形势

```
用户: "分析当前世界形势"

AI 执行流程:
1. web_search → 收集最新世界新闻、经济数据、地缘政治动态
2. 选择思想家: 韦伯 + 凯恩斯 + 福柯 + 达里奥 + 哈耶克 + 斯密 + 阿伦特 + 马基雅维利
3. 并行启动 8 个 Agent:
   - weber-analyst:  读取 weber SKILL.md → 用理想类型/理性化/权威分析
   - keynes-analyst: 读取 keynes SKILL.md → 用总需求/动物精神/乘数分析
   - foucault-analyst: 读取 foucault SKILL.md → 用权力知识/话语/治理术分析
   - dalio-analyst:  读取 dalio SKILL.md → 用大周期/债务/五大力量分析
   - hayek-analyst:  读取 hayek SKILL.md → 用知识问题/自发秩序分析
   - smith-analyst:  读取 smith SKILL.md → 用看不见的手/分工分析
   - arendt-analyst: 读取 arendt SKILL.md → 用极权/平庸之恶/公共领域分析
   - machiavelli-analyst: 读取 machiavelli SKILL.md → 用现实主义/virtù分析
4. 综合总结:
   - 共识: 国际秩序崩解、安全话语压倒一切、全球化逆转、AI唯一正面变量
   - 分歧: 政府角色(凯恩斯vs哈耶克)、战争走向(达里奥vs阿伦特)
   - 最终判断: 短期/中期/长期预判
5. 保存报告到 docs/world-analysis-{日期}.md
```

### 方式三：使用综合分析模板

参考 `skills/references/comprehensive-analysis-templates.md` 中的结构化模板：

- **世界新闻分析模板** — 7步多维度深度解读（波普尔→福柯→斯密→韦伯→阿伦特→达里奥→综合）
- **经济形势分析模板** — 四大经济学家视角对照表 + 深度分析清单
- **社会问题分析模板** — 结构/行动/规范/变革四维分析
- **未来走向预判模板** — 概率性、多模型、情景分析

---

## 🎯 应用场景 | Use Cases

### 1. 世界新闻深度解读
> "帮我从多个思想家视角分析当前的中美贸易摩擦"

→ 启动 5 个 Agent：斯密(市场) × 凯恩斯(需求) × 达里奥(周期) × 马基雅维利(战略) × 福柯(话语)

### 2. 经济形势研判
> "当前全球通胀形势如何理解？"

→ 启动 4 个 Agent：凯恩斯(成本推动) × 哈耶克(信贷扩张) × 达里奥(债务周期) × 斯密(市场机制)

### 3. 社会现象分析
> "社交媒体对民主政治的影响"

→ 启动 5 个 Agent：阿伦特(公共领域) × 福柯(数字监控) × 涂尔干(社会团结) × 波普尔(开放社会) × 韦伯(理性化)

### 4. 政策评估
> "这个经济刺激方案是否合理？"

→ 启动 5 个 Agent：凯恩斯(乘数效应) × 哈耶克(知识问题) × 斯密(政府角色) × 达里奥(去杠杆) × 波普尔(可检验性)

### 5. 批判性思维训练
> "这篇分析报告的逻辑是否严谨？"

→ 启动 3 个 Agent：波普尔(可证伪性) × 福柯(话语权力) × 韦伯(事实与价值)

---

## 🔧 架构设计 | Architecture

### Skill → Agent → 协调 的三层架构

```
┌─────────────────────────────────────────────┐
│            social-thinker-analyst            │  ← 主协调 Agent
│         (问题分类 → 选择组合 → 综合总结)       │
├─────────────────────────────────────────────┤
│  weber   │ keynes │ foucault │ dalio │ ...  │  ← 10个思想家 Agent
│ analyst  │ analyst│ analyst  │analyst│      │     (模仿思维方式)
├─────────┼────────┼──────────┼───────┼──────┤
│  weber   │ keynes │ foucault │ dalio │ ...  │  ← 10个 Skill 文件
│ SKILL.md │SKILL.md│ SKILL.md │SKILL  │      │     (方法论框架)
└─────────┴────────┴──────────┴───────┴──────┘
```

**设计原则：**
- **Skill 是知识层**：定义思想家的完整方法论、分析步骤、输出格式
- **Agent 是执行层**：模仿思想家的思维方式，严格调用 Skill 中的分析工具
- **协调 Agent 是整合层**：负责问题分类、Agent 调度、结果综合

---

## 📋 信息来源与验证 | Information Sources & Verification

本项目中每位思想家的信息均经过多渠道交叉验证：

### 验证标准
- ✅ **生平信息**：基于 Stanford Encyclopedia of Philosophy、Britannica 等权威来源
- ✅ **核心理论**：基于原著文本和主流学术解读
- ✅ **著作列表**：基于标准学术目录和出版记录
- ✅ **影响关系**：基于学术共识和引用网络
- ✅ **现代应用**：基于当代学术研究和实践应用

### 信息来源
- Stanford Encyclopedia of Philosophy (plato.stanford.edu)
- Internet Encyclopedia of Philosophy (iep.utm.edu)
- Encyclopædia Britannica (britannica.com)
- 各思想家的原著和标准学术评注
- 主流学术期刊和学术出版社

---

## 📦 安装方法 | Installation

### 方法一：完整安装（Skill + Agent）

```bash
# 克隆仓库
git clone https://github.com/your-username/SocialThinker-Skill.git

# 复制 Skills
cp -r SocialThinker-Skill/skills/* ~/.codebuddy/skills/

# 复制 Agents
cp -r SocialThinker-Skill/agents/* ~/.codebuddy/agents/
```

### 方法二：仅安装 Skills

```bash
cp -r SocialThinker-Skill/skills/* ~/.codebuddy/skills/
```

### 方法三：选择性安装

```bash
# 只安装凯恩斯和达里奥
cp -r SocialThinker-Skill/skills/john-maynard-keynes-约翰梅纳德凯恩斯 ~/.codebuddy/skills/
cp -r SocialThinker-Skill/skills/ray-dalio-雷达里奥 ~/.codebuddy/skills/
cp -r SocialThinker-Skill/agents/thinkers/keynes-analyst.md ~/.codebuddy/agents/thinkers/
cp -r SocialThinker-Skill/agents/thinkers/dalio-analyst.md ~/.codebuddy/agents/thinkers/
# 建议同时安装综合分析模板和协调Agent
cp -r SocialThinker-Skill/skills/references ~/.codebuddy/skills/
cp SocialThinker-Skill/agents/social-thinker-analyst.md ~/.codebuddy/agents/
```

---

## 🏷️ Tags

`ai-skill` `ai-agent` `multi-agent` `llm` `social-thought` `critical-thinking` `global-affairs` `economic-analysis` `political-philosophy` `sociology` `economics` `philosophy` `codebuddy-skill` `codebuddy-agent`

---

## 📄 许可证 | License

本项目采用 [MIT License](LICENSE) 开源许可。

---

## 🤝 贡献 | Contributing

欢迎为本项目贡献更多思想家 Skill 和 Agent！贡献时请注意：

1. **Skill 规范**：遵循 CodeBuddy Skill 格式（YAML frontmatter + Markdown）
2. **Agent 规范**：每个 Agent 必须定义身份、核心分析方法、输出格式、风格要求
3. **中英文命名**：目录使用"英文名-中文名"格式
4. **参考资料**：每个 Skill 都应包含 `references/` 目录下的著作详解
5. **Agent-Skill 对应**：每个 Agent 必须明确指向对应的 Skill 文件路径

### 建议添加的思想家方向
- 东方哲学：孔子、老子、庄子
- 近现代社会学：布迪厄、哈贝马斯
- 博弈论与制度：纳什、奥斯特罗姆
- 行为经济学：卡尼曼、塔勒布
- 地缘政治：亨廷顿、沃勒斯坦

---

> *"实践中的人自以为不受任何学理影响，其实他们都是某个已故经济学家的奴隶。"*
> — 约翰·梅纳德·凯恩斯

> *"历史不重复自己，但会押韵。"*
> — 雷·达里奥
