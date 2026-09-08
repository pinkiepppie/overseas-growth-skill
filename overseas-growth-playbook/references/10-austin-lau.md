# Austin Lau — Anthropic 首位增长营销负责人，"一人抵一个营销团队"的 AI 极限提效实践者

## 背景 Snapshot

Austin Lau 是 Anthropic（Claude 母公司）的首位增长营销（Growth Marketing）雇员，2024 年加入，此前曾在 Notion 从事近四年的增长工作，并在 Dropbox（自助/企业增长）、Webflow、Modern Treasury（创始增长团队成员）等公司积累了增长营销经验，本科毕业于 UC Riverside 市场营销专业。2025 年 Claude Code 发布时他还是一名完全不会写代码的营销人（第一次用时要 Google "如何打开终端"），此后约十个月里他借助 Claude Code / Claude Cowork 独立扛起了 Anthropic 全部效果营销渠道（付费搜索、付费社交、应用商店、邮件、SEO 等），这段经历因"一人撑起本应由 15-20 人团队负责的增长营销工作"而在营销圈广泛流传。目前他仍在 Anthropic 从事增长营销工作，并对外担任 Canva、Scale AI、Hex、Webflow、Neighbor 等公司的增长营销顾问。

## 核心方法论与框架 Core Frameworks

- **"Blast Radius" Test（"爆炸半径"测试，他本人使用的说法）**：在让 AI Agent 接触任何"活的"（live）营销活动/预算/受众之前,先评估这个操作一旦出错会波及多大范围——即这次自动化任务的潜在影响半径有多大。半径小（如生成文案草稿、内部仪表盘查询）可以放手让 Agent 自动化甚至自主运行；半径大（如直接修改上线中的广告出价、发送给全量用户的邮件）则必须保留人工审核关卡。这是他在多个访谈中反复强调的、决定"什么可以自动化、什么必须人工把关"的判断标准。
- **Cowork vs. Claude Code 的场景划分**：他会区分什么任务适合用 Claude Cowork（更适合非工程背景、协作型、探索型的营销任务），什么任务适合直接用 Claude Code（需要构建可复用工具/脚本/工作流的场景），并据此规划自己和团队的工作方式。
- **把"部落知识"（Tribal Knowledge）编码为可复用的 Agent Skills**：他提出团队应当把只有少数专家掌握的经验（品牌语气、产品准确性要求、投放最佳实践等）显式地写成可被 AI 复用的"技能"（Agent Skills / Slash Commands），例如他为 Google Ads 文案生成搭建的自定义命令 `/rsa`，会自动比对品牌语气、产品准确性、Google Ads 最佳实践等规则集。他认为这是让 AI 从"一次性帮忙"升级为"可规模化能力"的关键——知识从"少数人的经验"变成"团队共享、可重复调用的资产"。
- **从"手动执行者"到"工具构建者"的角色转变（Marketing Engineer）**：他的核心实践路径是——遇到重复性、有明确规则的营销任务，不满足于让 AI 帮自己做一次，而是用 Claude Code 把这个任务"产品化"成一个可反复调用的工具（Figma 插件、仪表盘、Slash Command、自我迭代的 A/B 测试追踪系统等），从而实现从"人力线性投入"到"一次搭建、持续复用"的杠杆效应。这也是他所参与播客《The Marketing Engineer》命名理念的体现。
- **增长的"大赌注 + 渐进改进"组合（Big Bets + Incremental Improvements，推测归纳）**：在 Passionfroot 的 AMA 中，他谈到增长工作是"big bets and incremental improvements"的组合，建议先与团队对齐未来 30/60/90 天的业务优先级，明确 3-6 个月要达成的目标并拆解为可执行步骤，再判断哪些是值得投入的"大赌注"、哪些是持续优化的日常动作。此处标注"推测归纳"，因为这是对他在该次 AMA 谈话内容的概括提炼，未见他将其命名为正式框架。

## 关键观点与金句 Key Quotes & Insights

- "Growth involves a mix of big bets and incremental improvements. It's essential to focus on what you want to invest your time and effort in over the next 30, 60, or 90 days."（增长是"大赌注"与"渐进改进"的组合，关键是想清楚接下来 30/60/90 天要把时间精力投在哪里。）[Source: Passionfroot Blog, Passionfroot AMA: Anthropic's Austin Lau on Building your Growth Engine, https://www.passionfroot.me/blog/anthropics-austin-lau-on-building-your-growth-engine]
- 在开始行动前，他建议先与团队沟通、理解当下最紧迫的业务优先级，明确 3-6 个月目标并拆解为可执行步骤，同时思考哪些"大赌注"既有显著影响力又具备可行性和可扩展性。[Source: Passionfroot Blog, https://www.passionfroot.me/blog/anthropics-austin-lau-on-building-your-growth-engine]
- 他把用于生产广告文案的自定义 Claude Code 命令 `/rsa` 描述为会自动接入一套围绕"Anthropic 品牌语气、产品准确性、Google Ads 最佳实践"搭建的 Agent Skills 集合，用来生成、检验 Google 响应式搜索广告（RSA）文案。[Source: 综合报道, https://sapt.ai/insights/one-man-marketing-team-anthropic-austin-lau, https://peerlist.io/saxenashikhil/articles/how-anthropics-growth-marketing-team-cut-ad-creation-time-fr]
- 用 Claude Code 搭建的 Figma 插件可以一键从 Google Sheet 中的一批标题批量生成最多 100 个广告变体，把过去团队每条广告要花 30 分钟的流程缩短到 30 秒。[Source: WOLF (X/Twitter), https://x.com/WOLF_Financial/status/2031880265312977148; 综合报道 The One Man Marketing Team, https://sapt.ai/insights/one-man-marketing-team-anthropic-austin-lau]
- 十个月内，他独自负责 Anthropic 全部六大增长营销渠道（付费搜索、付费社交、应用商店、邮件、SEO 等），而行业惯例做这些渠道通常需要 15-20 人团队、300 万至 500 万美元年度人力预算。[Source: 综合报道, https://sapt.ai/insights/one-man-marketing-team-anthropic-austin-lau]
- 他强调团队需要把"少数人掌握的部落知识"转变为可分享、可重复使用的资产，尤其是领域专家的经验应该更容易传递给其他团队；构建可复用的 Skills 才是让 AI 应用真正规模化、而非停留在一次性零散请求的关键。[Source: Chief Marketer, 8 Ways to Use AI in Marketing, According to Anthropic's Austin Lau, https://www.chiefmarketer.com/8-ways-to-use-ai-in-marketing-according-to-anthropics-austin-lau/]
- 在《The Marketing Engineer》播客访谈中，他讨论了 AI 如何让营销人变成"建造者"（builder），何时该用 Claude Cowork、何时该用 Claude Code，以及在让 Agent 触碰任何上线中的营销活动之前会做的"blast radius"测试。[Source: The Marketing Engineer 播客, How Anthropic's First Growth Marketer Builds with Claude, https://open.spotify.com/episode/5PcwDbC8lK080wcaYtYyrW; https://www.tryprofound.com/podcasts/every-marketer-can-become-an-engineer-here-s-how-or-austin-lau]
- 他最初对 Claude Code 的反应是"完全不知道这个产品是给谁用的"（作为营销人看不出使用场景），在一位 Anthropic 同事的指导下才开始尝试，一周内就做出了第一个提效工具。[Source: 综合报道, https://sapt.ai/insights/one-man-marketing-team-anthropic-austin-lau]

> 说明：本次研究环境的网页直接抓取（WebFetch）被网络出口代理整体屏蔽，无法逐字核实原始播客文字稿或原文全文，以上信息主要基于 WebSearch 返回的多方转述与二次报道（Sapt.ai、TechFlow、Chief Marketer、Passionfroot、Peerlist 等）交叉印证得出，个别引述文字为多篇报道转述的近似表达而非确认的逐字速记。建议在正式引用金句前，通过 Spotify/Apple Podcasts 上的《The Marketing Engineer》节目及 Passionfroot AMA 原文自行核实措辞。此外，Austin Lau 目前公开可查的一手内容（本人撰写的长文、公开演讲全文）相对有限，多数信息来自第三方报道和转述，这点也如实说明。

## 适用场景 When To Apply

- **新品上市 New product launch**：产品/功能刚上线、团队人力有限时，可参考他"先手动做几次、发现重复模式后立刻工具化"的路径——不必等团队扩编，而是用 AI 把创始营销人自己的重复劳动（文案生成、素材批量产出、数据查询）快速产品化，用最小团队跑通冷启动阶段的多渠道投放。
- **成熟期产品增长 Mature product growth**：当增长渠道已经稳定运转（付费搜索、社交、邮件等）但团队规模受限时，可用"blast radius"思路划分自动化边界——把风险低、重复度高的环节（报表生成、创意变体扩充、日常监控简报）交给 Agent 全自动运行，把风险高、影响面广的环节（预算调整、面向全量用户的发送）保留人工审核，逐步扩大自动化覆盖面而不失控。
- **其他 Other relevant scenarios**：
  - *AI 辅助营销运营（AI-assisted marketing ops）*：把团队里专家的经验（品牌语气、合规红线、渠道最佳实践）显式写成可复用的 Agent Skills/Slash Commands，而不是让这些知识只存在于个别人的脑子里，这样新成员或 AI Agent 都能直接复用。
  - *小团队/单人营销团队（lean growth team）*：验证了"一人+AI"可以承担传统上需要一个中型团队才能覆盖的效果营销范围，为资源有限的团队（如出海初创公司的海外分部）提供了可参考的组织形态。
  - *工具化思维培养*：鼓励营销人主动学习用 AI 编程工具（哪怕零代码基础）把重复性工作变成自己可以随时调用的"产品"，而不仅仅是被动使用 AI 聊天助手。

## 给出海营销人的启发 Takeaways for overseas/international marketers

- **用"blast radius"思路给多市场自动化分级授权**：出海营销往往需要同时管理多个国家/语言市场的投放，可借鉴他的判断标准——先把各市场的日常任务（关键词研究、创意变体生成、多语言文案初稿、数据周报）按"出错影响范围"分级，低风险、高重复度的任务优先交给 AI 自动化，涉及实际预算调整或大规模用户触达的操作保留人工审核，尤其是对不熟悉的新市场应更保守。
- **把"总部专家经验"编码成可复用的 Skills，赋能海外本地团队**：跨国团队常见的问题是品牌语气、合规要求、渠道打法等"部落知识"集中在总部少数人手里，海外分支/本地代理商难以复制。可参考他把 Google Ads 最佳实践写成 `/rsa` 这类命令的做法，把总部沉淀的打法、品牌规范、合规红线固化成 Agent Skills，让海外团队或本地化 Agent 在生成当地语言素材时自动遵循统一标准，同时保留本地化调整空间。
- **用 AI 批量生成本地化广告创意变体，验证多市场素材效果**：他用 Figma 插件把广告变体生成从 30 分钟压缩到 30 秒的做法，特别适合出海场景下"同一素材需要适配多语言、多文化语境"的批量需求——可以搭建类似工具，让一份核心创意快速衍生出各市场语言版本的多个变体，用于快速 A/B 测试筛选。
- **小语种/长尾市场也能用"一人+AI"模式先跑通**：对于预算和人力都难以覆盖的长尾海外市场，可参考他"一人扛起本需 15-20 人团队"的经验，先用极简人力配合 AI 工具跑通该市场的基础增长动作（搜索广告、落地页本地化、基础 SEO），验证市场潜力后再决定是否加大投入，避免在验证前过度投入本地团队。
- **重复性国际化运营任务优先工具化，而非依赖人工重复劳动**：多市场营销中大量存在结构相似、仅语言/参数不同的重复工作（如各国 Google Ads 文案审核、各市场邮件模板本地化、多语言落地页数据监控），应优先识别这类任务并用 Claude Code 等工具搭建一次性可复用的工作流，而不是让团队成员在每个新市场重复手动操作。
- **保持对"最初看不懂用途"的开放心态**：他坦言最初完全不理解 Claude Code 对营销人的价值，是在同事引导下才开始尝试并快速见效。出海营销人在引入新 AI 工具时也应有类似耐心——先小范围试用一个具体重复任务，而不是因为"看不出直接用途"就放弃探索。

## 来源 Sources

- https://sapt.ai/insights/one-man-marketing-team-anthropic-austin-lau
- https://www.techflowpost.com/en-US/article/30652
- https://m.techflowpost.com/article/30652
- https://impactainews.com/anthropics-entire-growth-marketing-team-was-just-one-man/
- https://www.mejba.me/blog/one-person-marketing-team-claude-code
- https://www.luminarylane.app/blog/anthropic-marketing-team-claude-copilot-ceiling/
- https://claude.com/blog/how-anthropic-uses-claude-marketing
- https://peerlist.io/saxenashikhil/articles/how-anthropics-growth-marketing-team-cut-ad-creation-time-fr
- https://www.tryprofound.com/podcasts/every-marketer-can-become-an-engineer-here-s-how-or-austin-lau
- https://open.spotify.com/episode/5PcwDbC8lK080wcaYtYyrW
- https://www.passionfroot.me/blog/anthropics-austin-lau-on-building-your-growth-engine
- https://www.chiefmarketer.com/8-ways-to-use-ai-in-marketing-according-to-anthropics-austin-lau/
- https://x.com/WOLF_Financial/status/2031880265312977148
- https://x.com/verbove/status/2033184560754614577
- https://alessiobiancheri.substack.com/p/one-person-ran-anthropics-marketing
- https://getmarketingwithai.substack.com/p/the-marketers-guide-to-claude-code
- https://www.gate.com/post/status/19412116
- https://www.growthtalent.org/talent/austin-lau
- https://www.linkedin.com/in/austinlau1/
