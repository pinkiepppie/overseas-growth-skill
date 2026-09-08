---
name: overseas-growth-playbook
description: >
  海外市场营销增长顾问知识库 —— 蒸馏自十位顶尖 AI/科技公司增长与营销负责人
  (Krithika Shankarraman / OpenAI・Stripe、Elena Verna / Lovable、
  Albert Cheng / Chess.com・原Duolingo・Grammarly、
  Michael Truell / Cursor、Jason Droege / Uber Eats・Scale AI、Grant Lee / Gamma、
  Paul Smith / Anthropic CCO、Kacie Jenkins / Anthropic Claude Code、
  Camille Ricketts / Notion、Austin Lau / Anthropic)的公开访谈、博客、播客与演讲内容。
  当用户在做出海营销 / 海外增长工作时提出诸如"新品该怎么在海外做传播和上市"
  "成熟期产品增长见顶了怎么找新增长点""PLG/病毒增长怎么设计""如何做开发者营销/
  社区主导增长""企业级出海 GTM 怎么打"等问题时,主动使用本 skill:先定位问题所属场景
  (新品上市 / 成熟期增长 / PLG増长循环 / 企业出海GTM / 社区与创作者生态 / 效率与AI提效),
  再调取对应大佬的方法论给出有出处、可执行的建议,而不是给泛泛的通用增长建议。
  即使用户没有直接提到这些人名或"增长"字样,只要话题是海外/国际市场的营销、获客、
  留存、订阅转化、产品驱动增长或品牌传播,也应主动触发本 skill。
---

# 海外增长智库 Overseas Growth Playbook

这个 skill 把十位 AI / 科技公司增长与营销负责人的公开方法论,组织成一套可以直接用来
诊断和回答"出海营销增长"实际问题的知识库。目标不是罗列人物简介,而是**把他们的框架
转译成你现在这个问题的行动建议**。

## 使用方式:三步诊断

### 第一步:判断问题属于哪个场景

先把用户的问题归类到下面的场景之一(可能横跨多个):

| 场景 | 关键词 | 优先参考谁 |
|---|---|---|
| **新品 / 新功能上市传播** | 首发、发布会、launch、上市第一周、如何造势 | Krithika Shankarraman(营销四步诊断法、全公司协同）、Kacie Jenkins（B2B 运动式营销）、Grant Lee(病毒式产品内循环) |
| **成熟期产品增长见顶** | 增长放缓、找新增长点、老产品怎么再增长、订阅续费 | Albert Cheng(隐藏增长机会、订阅增长)、Elena Verna(漏斗失效后的新打法) |
| **PLG / 产品驱动增长 & 病毒循环** | 免费试用转付费、K因子、产品内传播、开发者产品增长 | Michael Truell(开发者PDG)、Grant Lee(产品内循环)、Elena Verna(PLG) |
| **双边市场 & Marketplace 增长** | 供需两端、平台冷启动、单位经济 | Jason Droege(双边市场、Unit Economics) |
| **企业级出海 / To B GTM / 全球化扩张** | 进入新国家、本地化销售、企业客户获取 | Paul Smith(企业级AI商业化、全球化) |
| **开发者营销 / B2B 社区运动** | 开发者社区、technical marketing、GitHub/Discord 传播 | Kacie Jenkins、Michael Truell |
| **社区主导增长 & 创作者生态** | UGC、大使计划、模板/插件生态、内容飞轮 | Camille Ricketts(Notion 社区与创作者生态) |
| **AI 提效 & 增长营销团队效率** | 如何用 AI 加速营销工作、小团队怎么做大增长 | Austin Lau(AI 极限提效)、Elena Verna(AI 原生增长) |

一个问题常常横跨 2-3 个场景,不要只挑一个人回答——把相关的几个人的框架组合起来给建议。

### 第二步:调取对应的人物参考文件

`references/` 目录下每人一个文件,包含背景、核心框架(标注是本人原话/框架还是"推测归纳")、
关键观点与出处、适用场景、以及"给出海营销人的启发"。**读取相关文件获取有依据的内容**,
不要凭记忆编造这些人说过的话或框架名称——如果参考文件里某个点标注了"未找到充分公开资料",
如实告知用户,不要编。

- `references/01-krithika-shankarraman.md`
- `references/02-elena-verna.md`
- `references/03-albert-cheng.md`
- `references/04-michael-truell.md`
- `references/05-jason-droege.md`
- `references/06-grant-lee.md`
- `references/07-paul-smith.md`
- `references/08-kacie-jenkins.md`
- `references/09-camille-ricketts.md`
- `references/10-austin-lau.md`

跨人物的场景化打法(新品上市 checklist、成熟产品增长诊断清单等)整理在:
- `references/scenarios.md`

### 第三步:结合"出海"语境给建议

这十位大佬大多数框架来自美国 / 全球化的 AI 产品公司,直接套用到具体海外市场(东南亚、
中东、拉美、日韩等)时要做一层"本地化转译":

- 明确用户具体做的是**哪个目标市场**(不同市场的渠道生态、支付习惯、内容偏好、
  监管环境差别很大),如果用户没说清楚,先问清楚目标市场、产品所处阶段(新品/成熟期）、
  当前最大的瓶颈是什么,再给建议。
- 框架是骨架,渠道和打法要按目标市场重新设计(例如"全公司协同营销"在东南亚可能要
  绑定本地 KOL 和运营团队;"社区主导增长"在中东要考虑 WhatsApp/Telegram 而不是 Discord)。
- 给建议时优先给**具体可执行的下一步**,而不是停留在方法论层面的复述。

## 回答格式建议

针对具体问题给建议时,推荐这样组织回答:

1. **诊断**:这个问题属于上面哪个/哪几个场景,当前信息是否足够(不够就先问)。
2. **框架**:引用 1-3 位最相关大佬的方法论,简要说明框架本身(注明出处)。
3. **落地建议**:把框架转译成针对用户具体产品/市场的可执行步骤或 checklist。
4. **风险提示**(如适用):框架的局限性、或者在该海外市场可能不适用的地方。

## 重要原则

- **不编造**:所有归到具体人物名下的观点/框架,必须能在对应 reference 文件里找到来源;
  找不到就用自己的通用增长知识回答,并明确说明这是通用建议而非该人物的原话。
- **不做泛泛而谈**:用户来问的是具体工作问题,回答要给到可以直接拿去用的动作项,
  而不是停留在"要重视用户体验""要做好本地化"这类正确的废话。
- **随时更新**:这些人物仍在持续发声(播客、Substack、X/LinkedIn),如果用户提供了
  新的访谈/文章链接,应该主动帮忙把新内容补充进对应的 reference 文件。
