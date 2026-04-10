# SocialThinker-Skill 🧠

> **让历史上最伟大的社会学家、思想家和哲学家成为你的智囊团**
>
> AI Skills for Critical Thinking, Global Affairs Analysis & Intellectual Enlightenment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 简介 | Introduction

**SocialThinker-Skill** 是一套面向 CodeBuddy / AI 编程助手的 **Skill 集合**，将历史上最伟大的社会学家、经济学家、政治哲学家的**知识体系和思维方法**转化为可调用的 AI 技能。

它的核心目标是帮助使用者：

- 🌍 **理解世界新闻**：从多个思想家视角深度解读全球重大事件
- 📊 **分析经济形势**：运用经济学大师的框架剖析宏观经济趋势
- 🔮 **研判未来走向**：基于历史周期和系统性分析预判发展方向
- 🤔 **深度批判思考**：用哲学家的逻辑框架审视社会问题
- 💬 **多元视角碰撞**：让不同思想传统的大师"对话"，获得综合性洞见

---

## 🏛️ 思想家名录 | Thinker Roster

本项目收录了 **10 位** 横跨社会学、经济学、政治哲学和科学哲学的伟大思想家：

| # | 思想家 | Thinker | 领域 | 核心方法论 |
|---|--------|---------|------|-----------|
| 1 | 亚当·斯密 | Adam Smith (1723-1790) | 经济学 | 看不见的手、分工理论、道德情操论 |
| 2 | 马克斯·韦伯 | Max Weber (1864-1920) | 社会学 | 理想类型、理性化、权威类型、理解社会学 |
| 3 | 埃米尔·涂尔干 | Émile Durkheim (1858-1917) | 社会学 | 社会事实、失范、机械/有机团结 |
| 4 | 约翰·梅纳德·凯恩斯 | J.M. Keynes (1883-1946) | 经济学 | 总需求、动物精神、乘数效应、流动性偏好 |
| 5 | 弗里德里希·哈耶克 | F.A. Hayek (1899-1992) | 经济学/政治哲学 | 知识问题、自发秩序、通往奴役之路 |
| 6 | 汉娜·阿伦特 | Hannah Arendt (1906-1975) | 政治哲学 | 极权主义、平庸之恶、公共领域、诞生性 |
| 7 | 米歇尔·福柯 | Michel Foucault (1926-1984) | 哲学/社会理论 | 权力/知识、话语分析、规训、生命政治 |
| 8 | 尼科洛·马基雅维利 | N. Machiavelli (1469-1527) | 政治学 | 政治现实主义、能力与命运、狮子与狐狸 |
| 9 | 雷·达里奥 | Ray Dalio (b. 1949) | 经济学/地缘政治 | 大周期、债务周期、五大力量、历史模式识别 |
| 10 | 卡尔·波普尔 | Karl Popper (1902-1994) | 科学哲学 | 可证伪性、开放社会、批判理性主义 |

---

## 📂 项目结构 | Project Structure

```
SocialThinker-Skill/
├── README.md                          # 项目说明（本文件）
├── LICENSE                            # MIT 许可证
└── skills/
    ├── references/
    │   └── comprehensive-analysis-templates.md  # 综合多视角分析模板
    │
    ├── adam-smith-亚当斯密/
    │   ├── SKILL.md                   # Skill 主文件
    │   └── references/
    │       └── adam-smith-works.md     # 主要著作详解
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

### 单个思想家视角分析

将特定思想家的 Skill 安装到你的 CodeBuddy 中：

1. 将对应思想家文件夹复制到 `~/.codebuddy/skills/` 或项目的 `.codebuddy/skills/` 目录
2. 在对话中触发 Skill（使用描述中的触发词）
3. AI 将以该思想家的视角分析你提出的问题

**示例触发词：**

| 场景 | 触发词 | 调用 Skill |
|------|-------|-----------|
| 经济分析 | "用经济学视角分析..." | Adam Smith / Keynes / Hayek |
| 权力分析 | "分析这个权力结构..." | Foucault / Machiavelli / Arendt |
| 社会问题 | "这个社会现象的根源..." | Weber / Durkheim |
| 周期分析 | "当前经济周期在哪个阶段..." | Ray Dalio |
| 批判思考 | "这个说法是否站得住脚..." | Karl Popper |

### 多思想家综合分析

使用 `references/comprehensive-analysis-templates.md` 提供的综合分析模板，从多个思想家视角同时分析同一问题：

- **世界新闻分析模板** — 7步多维度深度解读
- **经济形势分析模板** — 四大经济学家视角对照
- **社会问题分析模板** — 结构/行动/规范/变革四维分析
- **未来走向预判模板** — 概率性、多模型、情景分析

---

## 🎯 应用场景 | Use Cases

### 1. 世界新闻深度解读
> "帮我从多个思想家视角分析当前的中美贸易摩擦"

→ 斯密谈自由贸易 × 凯恩斯谈需求管理 × 达里奥谈大国周期 × 马基雅维利谈地缘战略

### 2. 经济形势研判
> "当前全球通胀形势如何理解？"

→ 凯恩斯谈成本推动 × 哈耶克谈信贷扩张 × 达里奥谈债务周期 × 斯密谈市场机制

### 3. 社会现象分析
> "社交媒体对民主政治的影响"

→ 阿伦特谈公共领域 × 福柯谈数字监控 × 涂尔干谈社会团结 × 波普尔谈开放社会

### 4. 政策评估
> "这个经济刺激方案是否合理？"

→ 凯恩斯谈乘数效应 × 哈耶克谈知识问题 × 斯密谈政府角色 × 达里奥谈去杠杆

### 5. 批判性思维训练
> "这篇分析报告的逻辑是否严谨？"

→ 波普尔检验可证伪性 × 福柯分析话语权力 × 韦伯区分事实与价值

---

## 📋 信息来源与验证 | Information Sources & Verification

本项目中每位思想家的信息均经过多渠道交叉验证：

### 验证标准
- ✅ **生平信息**：基于 Stanford Encyclopedia of Philosophy、Britannica、学术传记等权威来源
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

### 局限性说明
- 每位思想家的思想体系极为丰富，Skill 文件仅摘取了与"分析当代社会、经济、政治问题"最相关的部分
- 思想家之间的比较和对照基于学术共识，但不同学术传统可能有不同解读
- Ray Dalio 作为当代人物，其思想仍在发展中

---

## 📦 安装方法 | Installation

### 方法一：用户级安装（所有项目可用）

```bash
# 克隆仓库
git clone https://github.com/your-username/SocialThinker-Skill.git

# 复制到 CodeBuddy skills 目录
cp -r SocialThinker-Skill/skills/* ~/.codebuddy/skills/
```

### 方法二：项目级安装（仅当前项目可用）

```bash
# 在项目根目录
mkdir -p .codebuddy/skills
cp -r SocialThinker-Skill/skills/* .codebuddy/skills/
```

### 方法三：选择性安装

只安装你感兴趣的思想家：

```bash
# 例如只安装凯恩斯和达里奥
cp -r SocialThinker-Skill/skills/john-maynard-keynes-约翰梅纳德凯恩斯 ~/.codebuddy/skills/
cp -r SocialThinker-Skill/skills/ray-dalio-雷达里奥 ~/.codebuddy/skills/
# 建议同时安装综合分析模板
cp -r SocialThinker-Skill/skills/references ~/.codebuddy/skills/
```

---

## 🏷️ Tags

`ai-skill` `llm` `social-thought` `critical-thinking` `global-affairs` `economic-analysis` `intellectual-enlightenment` `political-philosophy` `sociology` `economics` `philosophy` `speech-writing` `world-news` `future-trends` `codebuddy-skill`

---

## 📄 许可证 | License

本项目采用 [MIT License](LICENSE) 开源许可。

---

## 🤝 贡献 | Contributing

欢迎为本项目贡献更多思想家 Skill！贡献时请注意：

1. **信息准确性**：所有思想家信息必须来自可靠学术来源并经过交叉验证
2. **Skill 规范**：遵循 CodeBuddy Skill 格式规范（YAML frontmatter + Markdown）
3. **中英文命名**：目录使用"英文名-中文名"格式
4. **参考资料**：每个 Skill 都应包含 `references/` 目录下的著作详解
5. **综合视角**：在每个 Skill 的"Integration with Other Thinkers"部分说明与其他思想家的关系

### 建议添加的思想家方向
- 东方哲学：孔子、老子、庄子
- 近现代社会学：布迪厄、哈贝马斯
- 博弈论与制度：纳什、奥斯特罗姆
- 行为经济学：卡尼曼、塔勒布

---

> *"实践中的人自以为不受任何学理影响，其实他们都是某个已故经济学家的奴隶。"*
> — 约翰·梅纳德·凯恩斯
