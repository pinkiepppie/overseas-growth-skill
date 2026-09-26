# 海外增长智库 Overseas Growth Playbook (Claude Skill)

这个仓库包含一个 Claude Code / Claude skill:`overseas-growth-playbook`。

它把十位 AI / 科技公司增长与营销负责人的公开访谈、博客、播客内容,蒸馏成一套
可以直接用来诊断"海外市场营销增长"实际工作问题的知识库——例如新品上市该怎么
做传播、成熟期产品增长见顶了怎么找新增长点、PLG/病毒增长怎么设计、企业级出海
GTM 怎么打等等。

## 目录结构

```
overseas-growth-playbook/
├── SKILL.md                     # skill 入口:场景路由表 + 使用方法
└── references/
    ├── 01-krithika-shankarraman.md   # 前 OpenAI 首位营销负责人・前 Stripe 首位营销负责人
    ├── 02-elena-verna.md             # Lovable 增长负责人(10个月$200M ARR)
    ├── 03-albert-cheng.md            # Chess.com CGO,曾任 Duolingo / Grammarly 增长负责人
    ├── 04-michael-truell.md          # Cursor 联合创始人 & CEO
    ├── 05-jason-droege.md            # Scale AI CEO,前 Uber Eats 增长负责人
    ├── 06-grant-lee.md               # Gamma 联合创始人 & CEO
    ├── 07-paul-smith.md              # Anthropic 首席商务官 CCO
    ├── 08-kacie-jenkins.md           # Anthropic Claude Code 营销负责人
    ├── 09-camille-ricketts.md        # 前 Notion 首任营销负责人
    ├── 10-austin-lau.md              # Anthropic 增长营销(Claude Code 付费增长)
    └── scenarios.md                  # 按"新品上市 / 成熟期增长"整合的跨人物打法清单
```

## 如何使用

把 `overseas-growth-playbook/` 目录作为一个 skill 安装/引用给 Claude 即可。当你在做
海外营销增长工作、提出诸如"新品该怎么在海外做传播和上市""成熟期产品增长见顶了
怎么找新增长点"之类的问题时,Claude 会自动定位相关场景,调取对应人物的公开框架和
观点,并结合"出海"语境给出可执行建议。

每份人物文档里的观点都标注了出处链接;查不到公开依据的内容会被明确标注为
"推测归纳",不会假装是本人原话。

## 已安装的技能商店:小红书运营技能

仓库的 `.claude/settings.json` 已声明并启用
[vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills) 技能商店
(插件 `xiaohongshu-complete-skills`,144 个小红书运营技能,覆盖内容创作、账号运营、
互动运营、数据分析、电商转化、平台规则、工具生态、营销推广、增长策略)。
在本仓库打开 Claude Code 并信任该目录后会自动提示安装;也可以手动执行:

```bash
claude plugin marketplace add vivy-yi/xiaohongshu-skills
claude plugin install xiaohongshu-complete-skills@xiaohongshu-skills
```

## 已安装的项目级 Skill:吠陀占星 vedic-astro-skills

`.claude/skills/vedic-*` 是从 [CNWU16/vedic-astro-skills](https://github.com/CNWU16/vedic-astro-skills)
的 `claude-code/skills/` 复制来的 8 个 skill(排盘 calculator、星盘读取 reader、完整分析
core、事业 career、感情 love、合盘 synastry、校时 rectifier、卜卦 prashna)。在本仓库打开
Claude Code 即自动加载。排盘前需要 Python 3.8～3.13,首次使用运行
`python .claude/skills/vedic-calculator/scripts/setup_env.py` 安装 PyJHora 等依赖。
许可:AGPL-3.0 + 附加商业限制(仅限个人非商业使用),见 `.claude/skills/_vedic-astro-license/`。

## 已知的准确性修正

调研过程中发现两处需要注意的时效性/准确性问题(详见对应人物文档开头的说明):

- **Albert Cheng** 目前(2026)是 **Chess.com 首席增长官**,Duolingo / Grammarly 的增长
  职务都已是过去时。
- **Paul Smith**(Anthropic CCO)的职业履历是 微软 → Salesforce → ServiceNow → Anthropic,
  未找到任何证据显示他曾任职 Stripe。

## 局限性说明

本次调研环境的网页直接抓取(WebFetch)被网络代理整体拦截,所有内容基于搜索引擎
返回的摘要与多源交叉验证整理,而非对原始播客/文章的逐字核对。多数关键论断在
2-3 个独立信源中重复出现,可信度较高,但部分"金句"标注为"经转述"而非逐字引语。
如需正式对外引用,建议通过文档里列出的原始链接(Lenny's Podcast、Substack 等)
自行核实措辞。
