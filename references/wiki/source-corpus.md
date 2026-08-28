# 真实语料库与证据索引

> 版本：2026-08-28 v1.4。此文件为全技能的记忆主表。心智、打法和直觉文件都从这里取得 `Sxx` 记忆。

## 目录

- [使用规则](#使用规则)
- [本人/项目方语料](#本人项目方语料)
- [独立采访与人物报道](#独立采访与人物报道)
- [正式文件与 PDF](#正式文件与-pdf)
- [2024–2026 高变动条目补录](#20242026-高变动条目补录)
- [低置信与排除材料](#低置信与排除材料)
- [跨语料稳定模式](#跨语料稳定模式)
- [已知未知与研究队列](#已知未知与研究队列)

## 使用规则

- 将“来源质量”与“当前摄取状态”分开。原始视频可以是 A 级来源，但若未取得全文，仍只能按 `Pointer` 使用。
- **来源质量**：`A` 原始正式文件/本人完整作品；`B` 可靠媒体直接采访或独立原始研究；`C` 官方自述、项目报告或完整二手报道；`D` 来源链不完整。
- **摄取状态**：`Full` 已读全文/完整逐字稿；`Partial` 已读可靠摘要或部分原文；`Pointer` 仅确认存在、标题和公开主题。
- 每个心理或决策结论至少引用两份跨年份语料；否则标为弱推断。
- `Pointer` 不得支持精确引语、心理特征或决策算法；`Partial` 只支持摘要明示的主张。
- 对真实人物的私生活主张，除非有可靠公共记录与明确公共利益，不进入事实层。
- **引用集中度纪律**：任何单一来源不得独自支撑一条以上的核心结论。当前 S41（经编辑的电话采访，B 级）被全技能引用逾 60 次，是承重最高的一条——凡是**仅由 S41 支撑**的主张，必须写成"据其 2026-08-28 对凤凰网科技的表述"，并在结论层降为弱推断，直到出现第二个跨来源佐证。同一规则适用于任何被引用超过 30 次的编号。

## 本人/项目方语料

### S01｜2015｜《我仍选择相信》｜本人署名回应｜A / Full

- 链接：https://www.thepaper.cn/newsDetail_forward_1362440
- 语境：回应一篇负面人物报道。
- 可观察内容：把自己定位为“拓荒者”；强调创业、阶层突破、投资人信任；对私人谈话被公开表现出强烈背叛感；用高强度道德叙事争夺解释权。
- 可支持：危机回应、受害—反击叙事、信任与控制议题。
- 不可支持：回应中的所有事实自动成立。

### S02｜2016 录制/后续公开整理｜“规则制定期”创业分享｜C / Partial

- 公开整理：https://www.theblockbeats.info/news/59653
- 公开音频摘要：https://www.xiaoyuzhoufm.com/episode/6909824605d56708a091e5eb
- 可观察内容：财富更容易流向“规则正在形成”的领域；早期进入可以参与资源分配；信息敏感度和指数型收益优于线性工资路径；当时已将 TRON 描述为规则未成型、亟待整合的新赛道。
- 可支持：时机、规则套利、早期进入、非线性回报心智模型。
- 限制：部分页面是后续整理或重发，应与原音频/文字版本交叉核验。

### S03｜2026-08-27｜X 长文《我的女友景甜》｜本人账号文章｜A / Full（原文与发布可确认；内容真实性见 S41、S147、S148）

- 链接：https://x.com/justinsuntron/article/2092932777612390850
- 发布账号：`@justinsuntron`；页面显示 2026-08-27 发布并更新。
- 同一作品的其他编号：S142 是同一条 X Article 的 status 形态，ID 与本条相同（`2092932777612390850`），不是第二次发布；S144 是中文账号 `@sunyuchentron` 同日发布、标题与开篇相同的记录，正文是否逐字一致未核验。三个编号指向同一部作品，作品级判断一律以本条为准。
- 作品声明与作者对它的推翻：文末写“本文纯属虚构，如果雷同实属巧合”，但作者次日（2026-08-28）公开表示“绝大多数……符合我意愿的一个真实的陈述”，只因无法保证每个细节 100% 才那样标注（S41）。**因此不能把这篇文章当作单纯的虚构作品处理，也不能引用文末声明来否认它的纪实意图。** 他 100% 确认的范围仅限自己的想法与说法。
- 摄取状态：全文已获取（转载版，X 原文为权威版本），段落级引文与结构分析见 [景甜案专档](references/wiki/jingtian-case.md) 第四节。此前版本只有媒体转述。
- 补充全文存档：https://github.com/HEJustinSun/my-girlfriend-jingtian-latex （XeLaTeX 排版工程，`main.tex` 为纯文本正文，另有 5×8 英寸成书 PDF；2026-08-27 11:28 UTC 创建，仅两个 commit）。比转载站更便于逐段引用。**但它不是权威版本**：仓库主 `HEJustinSun` 与他 X 显示名"H.E. Justin Sun"同形，是否本人无法确认，也没有从其 X 账号指向该仓库的链接。**引用文本以 X 原文为准，这个只当便利存档。**
- 该仓库本身也是一个传播样本：2026-08-28 一天内星标从 2.7k 涨到 3.5k、fork 549，410 个 issue 几乎全是玩梗而非技术问题（"孙哥这真的是你手写的吗""这不是 Claude Code 的业配文吗""把和 Claude 的聊天记录也开源一下呗"）。**长文被开发者社群当成文本对象二次传播**，这条路径独立于微博热搜，且是他本人未参与、也无法控制的扩散。
- 内容机制：以具体金额、重量、酒店、飞机、转账和时间建立“财务审计式真实感”；以空房、空座、空港、海面和重复服务劳动制造空洞感；让“无限满足”与第一次拒绝形成转折；把 AI/Claude 写成无情但清晰的外部决策者；以循环意象和免责声明收束。
- 三个此前遗漏的关键点：（1）他把自己 2024 年 620 万美元的香蕉写进文中，让对方用“那它烂了怎么办”一句击穿；（2）称谓在转折点从“妈妈”切回“景甜”，是全文最精确的一次技术动作；（3）“我全部相信她说的……但是我一个字也不信”与那份四十几页的调查材料，是他对“相信与验证并存”最直接的自我描述。
- 现实背景（重要，早期版本缺失）：同日存在一场真实的已立案民事诉讼，见 S147（孙宇晨方代理律师陈述）与 S148（景甜方否认），完整事件档案见 [景甜案](references/wiki/jingtian-case.md)。这篇文章不是凭空的文学创作，它与诉讼同一天发出，多家媒体把它读作配合诉讼的舆论动作。因此不能把它描述成“与现实无关的小说”。
- 可支持：文学表达、财富符号、极端细节、控制/拒绝、AI 外置判断；以及“同日并行推进司法程序与叙事传播”这一行为事实。
- 可以照写的：作者本人主张这篇文章绝大部分属实、是他的真实陈述，这是他的公开表态，写成“他说”即可，不需要加“据称是虚构作品”之类的对冲。
- 不可支持的：把文中涉及**景甜行为**的情节（代孕约定、5000 万美元索款、代孕机构订金、具体对话与场景）当成已确认的事实。理由不是文末那句虚构声明——作者自己已推翻它——而是这些情节至今只有他一方的叙述，报道明确注明未获独立证实，景甜方全盘否认（S148），法院尚未进入实体审理（S147）。
- 四层必须分开：作品情节（S03）／作者本人主张属实（S41）／对方否认（S148）／法院认定（目前为空）。作者说“大部分是真的”属于第二层，不会让它变成第四层。
- 作者边界：只能确认由本人账号发布；独立写作、编辑/团队参与、代笔或 AI 参与程度均未知。

### S04｜2026｜Simon Squibb 对话｜原视频 A；未授权档案摘要 D / Partial

- 链接：https://www.thesunarchives.com/en/news/justin-sun-interview-ai-blockchain-future-2026
- 可观察内容：称自己现在“90%”时间与 AI 对话；把区块链定位为 AI 的金融基础设施；强调 AI 可降低教育不平等；建议年轻人投入 Bitcoin、AI、机器人、无人机、太空和区块链等改变生活的领域。
- 可支持：技术乐观主义、AI 作为顾问、基础设施视角、未来赛道筛选。
- 原视频：https://www.youtube.com/watch?v=-LPo9pJZoIA
- 限制：档案站明示声明与孙宇晨/TRON 无关联；本版未能取得 YouTube 完整字幕，只使用页面展示的问答，不扩展为实际日常决策证据。

### S05｜官方 About/时间线｜C

- 个人官网：https://www.hejustinsun.com/about
- TRON 时间线：https://tron.network/about/?lng=en
- 可观察内容：官方选择强调 TRON、巴菲特午餐、外交、HTX 顾问、艺术、太空和上市公司敲钟等里程碑。
- 可支持：自我品牌选择和项目方主张。
- 不可支持：所有权、控制或第三方评价。

## 独立采访与人物报道

### S06｜2015-12-29｜澎湃完整采访｜B / Full

- 链接：https://www.thepaper.cn/newsDetail_forward_1413224
- 可观察内容：认为创业越早越好；主流教育对创业帮助有限；规则制定者获得更高溢价；快速、低成本失败有价值；资本寒冬可淘汰投机创业者；陌生人社交和付费互动体现新消费。
- 代表性短句：“社会最终给出溢价最多的是制定规则的人。”
- 可支持：规则意识、年龄/速度偏好、对主流路径的不信任、平台化社交与变现。

### S07｜2020-02-26｜Nugget's News YouTube 长访谈｜A / Pointer

- 链接：https://www.youtube.com/watch?v=q_WfrABu8cc
- 标题：The Truth About Tron - An Honest Conversation With Justin Sun
- 公开主题：个人背景、为何创办 TRON、与 Ethereum/EOS 的竞争、TRX、DPoS、BitTorrent、Steemit、Poloniex、Bitcoin、XRP。
- 可支持：只支持“访谈覆盖这些主题”。
- 限制：本版未取得官方逐字稿，不得用它证明具体立场、精确原话或“生态化倾向”。

### S08｜2024-03-11｜Bankless 第 213 期逐字稿｜B / Full

- 逐字稿：https://podscripts.co/podcasts/bankless/213-justin-sun-on-tron-vitalik-and-becoming-humble
- 原节目主题：起源、稳定币支付、TRON 经济、代码相似性、去中心化、审查、Vitalik、营销。
- 可观察内容：称加密已成为自己的“家”，离开后“无处可去”；把 Ripple 的全球结算愿景追溯为自己长期关注稳定币支付的起点；认为区块链对发展中市场金融基础设施有 10 倍改善；表示自己比 12 年前更“humble”，先问自己/团队是不是最适合做；承认不会再采用早期把个人头像与“最大生态”绑定的广告方式；面对媒体律师函争议时，把部分行动归因于法律/合规团队。
- 可支持：身份锁定、稳定币使命、成熟后的自我修正、个人品牌与机构控制张力。

### S09｜2024-05-21｜Bitcoin.com 访谈｜C / Partial

- 链接：https://podcasts.apple.com/us/podcast/justin-sun-founder-of-tron-how-bruce-lee-inspired/id1406939454?i=1000656351909
- 可观察内容：把 Bruce Lee 的适应、纪律和“flow”连接 TRON；将 Hans Zimmer 主题曲、Google Cloud 超级代表候选、Bitcoin L2、AI、稳定币与跨链放入同一生态叙事。
- 可支持：节目简介明示的符号桥接与生态主题；稳定沟通模式须取得逐字稿后再认定。

### S10｜2024-07-08｜The Block / The Scoop 访谈｜B / Partial

- 链接：https://www.theblock.co/podcasts/the-scoop/2024-07-08-justin-sun-weighs-in-on-his-legal-victory-and-the-changing-perceptions-of-crypto-in-china-304126
- 可观察内容：围绕中国法院名誉案件，把个人法律胜诉连接到消除传闻和加密在中国的合法性叙事。
- 可支持：法律事件的叙事放大、声誉修复。
- 限制：关于案件本身应读法院文件，不以访谈替代裁判。

### S11｜2024-11-29｜The Art Newspaper 艺术访谈｜B / Full

- 链接：https://www.theartnewspaper.com/2024/11/29/justin-sun-discusses-the-future-of-digital-art-and-his-newly-acquired-banana-work-at-hong-kong-event
- 可观察内容：认为作品的大部分价值来自互联网传播，而非物理香蕉；把购买、吃掉、所有者历史都视为作品历史；强调区块链对数字艺术所有权和交易透明度的作用。
- 可支持：注意力即价值、参与者把自己写入事件、物理/数字融合、所有权叙事。

### S12｜2025-03-27｜Forbes 封面人物报道｜B / Full（带强批判视角）

- 链接：https://www.forbes.com/sites/ninabambysheva/2025/03/27/meet-the-crypto-billionaire-who-just-helped-the-trumps-net-400-milllion/
- 可观察内容：报道其少年时通过 BitTorrent 看《The Apprentice》，称受竞争、表演性与自我意识吸引；孙宇晨谈 World Liberty 时把 Trump 描述为加密行业的“cheat code”；报道也对其资产披露和动机持显著怀疑。
- 可支持：媒介偶然性、对 showmanship 的长期兴趣、政治/品牌连接的期权思维。
- 必须并列：Forbes 的批判框架、利益估算和未验证资产均不是中立定论。

### S13｜2024-11-29｜AP/CNN 对香蕉行为艺术的现场报道｜B / Full

- AP：https://apnews.com/article/ea246755028e74b87a2ecd8a27af16bf
- CNN 转录：https://transcripts.cnn.com/show/cnr/date/2024-12-01/segment/03
- 可观察内容：兑现“买下后吃掉香蕉”的公开承诺；把作品价值解释为物件、历史、互动与所有者历史的组合。
- 可支持：行动即内容、事件闭环、通过履约进入故事。

### S14｜2025/2026｜Bloomberg 人物与财富档案｜B / Partial

- 链接：https://www.bloomberg.com/billionaires/profiles/justin-sun/
- 可观察内容：提供出生、教育、Ripple、Peiwo、TRON、BitTorrent、HTX、World Liberty、TRON Inc. 等时间线和估值方法。
- 可支持：传记骨架和资产估值口径。
- 限制：净资产会每日变化；所有权描述须与公司备案交叉核验。

## 正式文件与 PDF

### S15｜2022｜WTO MC12 格林纳达正式发言 PDF｜A

- 链接：https://www.wto.org/english/thewto_e/minist_e/mc12_e/statements/ST39.pdf
- 可观察内容：以格林纳达代表身份讨论小岛屿国家、电子商务、数字鸿沟、区块链、渔业补贴、多边贸易和争端解决。
- 可支持：当时外交身份、公共政策语域、把区块链纳入发展议题。

### S16｜TRON 白皮书 v2.0 PDF｜A/C

- 链接：https://tron.network/static/doc/white_paper_v_2_0.pdf
- 可观察内容：协议历史、技术设计和项目方对 2017–2021 里程碑的定义。
- 可支持：项目方技术叙事和历史主张。
- 限制：白皮书是项目文件，不是独立绩效审计。

### S17｜2023–2026｜SEC 案件文件｜A

- 2023 公告：https://www.sec.gov/enforcement-litigation/litigation-releases/lr-25676
- 原始诉状：https://www.sec.gov/file/sec-complaint-2428
- 2026 公告：https://www.sec.gov/enforcement-litigation/litigation-releases/lr-26496
- 拟议判决：https://www.sec.gov/files/litigation/litreleases/2026/judgment26496.pdf
- 可支持：指控内容、程序和处理状态。
- 规则：诉状必须写“SEC 指控”；最终处理以法院命令为准。

### S18｜2017｜《这世界既残酷也温柔》｜本人署名图书｜A / Pointer

- 豆瓣条目：https://book.douban.com/subject/26984629/
- 状态说明（2026-08-28 复核）：**仍为 `Pointer`，且短期内难以合法升级**。检索可得的完整文本均为未授权电子副本，按[使用规则]第 7 条排除；豆瓣与百度百科页面对自动抓取返回 403 / robots 限制，未能取得逐字简介与目录。
- 因此：本书**不可**提供任何【原话】，也不可用于文风结论。第三方读书笔记（知乎、简书等）只是笔记作者的概括，把它们当作书中原句是本技能最容易犯的伪引用错误。
- 合法升级路径：正版电子书或纸质书的逐页摘录、出版社官方页面的内容简介、媒体书评中明确标注的引文。

### S19｜2019-07｜巴菲特午餐延期与“过度营销”道歉｜本人已删帖文 + 媒体存档｜B/C / Full（存档）

- 中文全文存档：https://www.thepaper.cn/newsDetail_forward_4002015
- Reuters 报道：https://www.investing.com/news/stock-market-news/warren-buffett-charity-lunch-in-limbo-after-crypto-promoter-issues-apology-1934117
- 可观察内容：本人当时把事件定性为失控、失速、失败的过度营销，反复向监管、媒体与公众道歉。
- 可支持：注意力打法的明确负面案例；危机时精英/监管语域转换；公开文本后续删除所带来的证据链风险。

### S20｜2025｜TRON Inc. SEC 备案与 Sun Advisory Agreement｜A / Full

- 2025-06-16 8-K：https://www.sec.gov/Archives/edgar/data/1956744/000164117225015183/form8-k.htm
- 顾问协议：https://www.sec.gov/Archives/edgar/data/1956744/000164117225015300/ex10-2.htm
- 2025-07-16 更名 8-K：https://www.sec.gov/Archives/edgar/data/1956744/000164117225019830/form8-k.htm
- 已知：协议将孙宇晨定义为独立承包的顾问，服务受公司最终批准；它明确不建立员工、合伙人、代理或合资关系。SRM 后更名为 Tron Inc. 并转向 TRON treasury strategy。
- 未知：公开协议不自动证明实益所有权、日常控制或所有关联方关系。

### S21｜TRON 协议、共识与治理文档｜A/C / Full

- 开发者文档：https://developers.tron.network/docs/concensus
- 项目方白皮书：https://tron.network/static/doc/white_paper_v_2_1.pdf
- 已知：TRON 使用 DPoS，27 位当选超级代表轮流出块；投票与网络参数提案构成治理环路。
- 未知：规则可见不等于投票权分散；实际控制需结合历史投票、候选人关联与关键维护者分析。

### S22｜2026 Q2｜TRON 网络使用与治理数据｜项目报告 C + Messari 独立摘要 B / Full

- TRON DAO：https://trondao.org/research/tron-q2-2026-quarterly-report
- Messari：https://newsletter.messari.io/p/state-of-tron-q2-2026
- 已知：Messari 报告 Q2 末 TRON 稳定币市值约 892 亿美元，USDT 占 98.5%；季度 USDT 转账约 2.1 万亿美元。TRON DAO 报告称前 11 位超级代表持有全部 SR 投票权的 60%，Poloniex 为第一大票权方。
- 限制：当期快照不得外推为永久状态；地址数、转账量、收入不自动等于独立用户、零激励需求或孙宇晨个人业绩。

### S23｜2020 事件/2024 研究｜TRON–Steem 治理冲突｜B / Full

- 同期报道：https://www.theblock.co/news/ecosystems/2020-03-02-tron-steem-takeover-crypto-exchanges-governance-reversal-soft-fork-blockchain-57508
- 实证研究：https://arxiv.org/abs/2407.17825
- 可支持：收购资产、代币投票权、交易所托管资产与社区正当性之间可以产生严重冲突；该事件后续伴随社区分叉。
- 用法：作为“通过资产和渠道快速获取治理能力”的负面/失效案例，不把任何一方的道德定性写成无争议事实。

### S24｜2026-03-09｜SEC 合格判决/命令记录｜A / Partial

- SEC 合格判决/命令页：https://www.sec.gov/enforcement-litigation/whistleblower-program/notice-covered-actions/award-claim-2026-034
- 已知：SEC 举报人计划页面记录的合格判决/命令日期为 2026-03-09，可支持“SEC 系统记录该日存在符合条件的判决/命令”。本资料库尚未直接摄取带法官签署/盖章的 docket order，故精确处置文本以 SEC 公告表述并结合正式案卷复核；不得把 03-05 的拟议判决 PDF 误称为已签署最终命令，也不简化为“全面胜诉”或“全部定罪”。

### S25｜2025–2026｜TRON Inc. 控制权、关联方与金库披露｜A / Full

- 2025 Form 10-K：https://www.sec.gov/Archives/edgar/data/1956744/000149315226012723/form10-k.htm
- 2026 Q2 Form 10-Q：https://www.sec.gov/Archives/edgar/data/1956744/000149315226037161/form10-q.htm
- 控制权：截至 2026-06-30，Bravemorning 持有约 88.5% 投票权；Weike Sun 是 Bravemorning 唯一股东、TRON Inc. 董事长，公司将前述交易披露为控制权变更。备案明确称 Weike Sun 为 Justin Sun 的父亲。
- 孙宇晨的直接公开关系：其控制的 Black Anthem Limited 以 1,800 万 USDT 购买 13,067,151 股；2025 10-K 披露当时整体投票权约 2.75%。公司明确称其不任高管、不管理业务单元、不承担政策制定，只作为独立承包顾问。
- 金库与关联方：公司披露金库私钥由公司保留唯一控制，Weike Sun 与 Zi Yang 获董事会授权安排密钥保管/操作；同时披露 BGTL、BGDL、JustLend 和 TRON 生态的潜在关联冲突。
- 法律区分：截至该日的公开文件支持“TRON Inc. 的正式投票控制由 Weike Sun/Bravemorning 掌握”，不支持将孙宇晨写成实际控制人。亲属、顾问和生态关联可形成非正式影响的研究问题，但不能在无一致行动或代持证据时反推孙宇晨控制公司。

### S26｜2026-04-13｜TRON Inc. Schedule 13D/A 控制权申报｜A / Full

- 原始申报：https://www.sec.gov/Archives/edgar/data/1956744/000149315226016392/xslSCHEDULE_13D_X02/primary_doc.xml
- 申报人：Bravemorning Limited 与 Weike Sun。
- 具体披露：Bravemorning 直接实益拥有 420,000,000 股，对其具有单独投票和处分权；Weike Sun 因控制 Bravemorning 被视为间接实益所有人，占已发行股份约 88.5%。
- 目的：申报人明确称取得证券是为了获得发行人控制权，并列出董事更替及 Weike Sun 出任董事长。
- 归因边界：Schedule 13D/A 是申报人在证券法下认证的披露，是判断公开投票/实益控制的强证据；它不能排除从未披露的代持或私下安排，但不得在无反证时臆测这些安排存在。

### S27｜2016 内容/2026 官网回顾｜《财富自由革命之路》官方播客页｜C / Partial

- 链接：https://www.hejustinsun.com/zh/podcast
- 原专辑入口：https://m.ximalaya.com/album/98108036?from=pc
- 页面事实：个人官网把该系列描述为孙宇晨于 2016 年亲自创作并主讲的商业财经音频课程，并展示分集播放器、前十集标题与课程简介。
- 目录事实：官网 Insights 页公开列出编号至 156 的节目目录；末段包括“财富流向”“From It to Bit”“去中心化网络的诞生”和多集“我的明治维新”。这证明系列规模与主题分布，不等于已摄取全部音频内容。
- 官方自述框架：围绕人生战略、价值观、前瞻性思维、精神自由、思想解放与人生选择权组织“财富自由”命题。
- 可支持：2026 年个人官网回顾性认领并托管一套 2016 年课程，且把它描述为系统思想输出；“孙学”的内容谱系可以追溯到这一课程，但尚不能证明“孙学”一词在 2016 年已经公开使用。
- 限制：本版只读官网页面与公开摘要，尚未逐集摄取、转写和核对全部音频；官网的销量、播放量和影响力描述属于官方自述，不作独立审计事实。

### S28｜2026-01-21｜中文 X 账号谈“孙学”十年｜D / Partial（正文经第三方镜像）

- 原链接：https://x.com/sunyuchentron/status/2013937035313361029
- 可访问镜像：https://twstalker.com/sunyuchentron/status/2013937035313361029
- 页面内容：帖子称 2026 年是“孙学创立第十年”，回看 2016 年最后一期《我的明治维新》，并把个人/国家命运差异归于价值观及其造成的选择与战略差别。
- 可支持：第三方镜像明确显示本人中文账号使用“孙学”称谓，并把它连接到 2016 年节目、价值观重构和战略选择；证据性质是镜像记录，不是已完成原帖存档的一手事实。
- 限制：原 X 页面当前无法由本环境直接读取；在取得原帖可靠存档或 API 数据前，不把镜像正文升级为 A 级本人语料，也不支持超出页面正文的精确结论。

### S29｜2026-01-30｜HTX Square《过去笑他疯，现在逐帧学》｜关联平台评论 C / Full

- 链接：https://square.htx.com/zh/htx-sunyuchen-sunxue-shinian-nixi/
- 页面内容：将“孙学”描述为 2026 年重新走红的社区现象，并把规则理解、长期下注、注意力和逆境韧性归入这一标签。
- 可支持：HTX 关联平台如何包装、传播和再解释“孙学”；可作为品牌叙事样本，不能代表广泛社区共识。
- 不可支持：文中的赞誉、口碑反转、私生活引语或全部历史判断自动成立；HTX Square 与其生态存在明显关联，不是独立人物评估。

## 2024–2026 高变动条目补录

> 本节于 2026-08-28 联网核验补入。这些条目变动快、政治与监管敏感度高，引用前必须重新核验当前状态。

### S30｜2024-10-11｜Liberland 任命其为首任总理｜项目方公告 C / Partial

- 公告：https://liberland.org/news/600-justin-sun-appointed-first-liberland-prime-minister
- 独立报道：https://www.theblock.co/post/320524/tron-founder-justin-sun-elected-as-prime-minister-of-crypto-focused-micro-nation-liberland
- 可支持：主权/治理符号的持续获取；把政治头衔当作叙事资产。
- 不可支持：Liberland 是被广泛承认的主权国家；该头衔具有国际法效力。

### S31｜2024-11-20 拍卖 / 11-29 现场｜苏富比 Comedian 与公开食用｜B / Full

- 拍卖报道：https://www.theartnewspaper.com/2024/11/21/maurizio-cattelan-banana-sothebys-6-million-auction-comedian
- 现场：https://www.artnews.com/art-news/news/justin-sun-eats-maurizio-cattelan-banana-comedian-eaten-1234725313/
- 事实：以约 620 万美元（含买家佣金）拍得，后在香港活动上当众吃掉。
- 可支持：注意力打法的教科书案例——用可复述的单一动作把资产变成事件；与 S11「价值大部分来自互联网」的自述互证。
- 注意：部分二手资料写作 520 万美元（落槌价 vs 含佣价），引用时必须写明口径。

### S32｜2024-11 起｜World Liberty Financial 投资｜B / Partial

- 首笔报道：https://www.fortune.com/crypto/2024/11/25/trump-world-liberty-financial-crypto-project-30-million-justin-sun-tron
- 事实：2024-11 投入 3,000 万美元成为该项目当时最大投资者；后续追加，媒体口径在 7,500 万至 9,000 万美元区间不等。
- 使用纪律：不同报道的累计金额口径不一致，必须注明来源与截至日期，不取单一数字当定论。

### S33｜2025-05-20/22｜自称 $TRUMP 最大持有者并出席晚宴｜B / Partial

- https://www.cnbc.com/2025/05/20/justin-sun-trump-dinner.html
- https://www.coindesk.com/business/2025/05/21/justin-sun-emerges-as-donald-trump-memecoins-top-holder-with-219m-stake
- 事实：自称并被链上分析确认为 $TRUMP 最大持有者（当期约 2,190 万美元规模），出席 2025-05-22 特朗普国家高尔夫俱乐部晚宴。
- 可支持：以可公开验证的持仓换取物理接近与政治可见度，是「注意力—关系网—资本」三条 playbook 的合流。
- 不可支持：由此推出任何监管结果的因果关系。

### S34｜2025-08-03｜Blue Origin NS-34 亚轨道飞行｜A / Full

- Blue Origin 官方任务页：https://www.blueorigin.com/news/new-shepard-ns-34-mission
- 独立报道：https://www.space.com/space-exploration/private-spaceflight/blue-origin-launch-crypto-billionaire-justin-sun-launch-suborbital-space-ns-34
- 事实：2021 年以 2,800 万美元拍得 New Shepard 首次载人席位，因故未成行；2025-08-03 实际完成飞行，同行五人。
- 可支持：长周期兑现承诺的公开案例；符号性消费与身份叙事（「最年轻的中国商业宇航员」类表述由本人及媒体传播，非官方认证）。

### S35｜2026-03-05 提交 / 03-09 记录｜SEC v. Sun 拟议解决与处置记录｜A / Partial

- 诉讼公告：https://www.sec.gov/enforcement-litigation/litigation-releases/lr-26496
- 拟议最终判决：https://www.sec.gov/files/litigation/litreleases/2026/judgment26496.pdf
- 案号：No. 1:23-cv-02433（S.D.N.Y.）
- 03-05 文件性质：SEC 公告其提交拟议整体解决方案；所链接 PDF 明确标为 `[PROPOSED] FINAL JUDGMENT`，不能仅凭该 PDF 写成法院当日已签署。
- 处置内容（按 SEC 公告及其后 03-09 记录归因）：对 Justin Sun、Tron Foundation Limited、BitTorrent Foundation Ltd. 的全部主张**终局性驳回（dismissed with prejudice）**；Rainberry, Inc. 就 1933 年证券法 17(a)(3) 的洗售指控和解，缴纳 1,000 万美元民事罚款并被永久禁令约束，**未承认亦未否认**指控；对 DeAndre Cortez Way 的 17(b) 主张由 SEC 主动撤回。若需逐字引用法院命令，必须另取正式案卷中的签署版本。
- 政治争议：参议员 Warren 就此发表批评声明（https://www.banking.senate.gov/newsroom/minority/warren-statement-on-the-sec-dropping-its-case-against-justin-sun），把和解与其对特朗普系加密项目的投入相联系。**该声明是政治指控，不是事实认定**，引用时必须与法院文件分开归因。
- 校正：03-05 是 SEC 公告和拟议判决提交日；S24 的 03-09 是 SEC 举报人计划页面记录的合格判决/命令日。资料库未直接摄取签署版 docket order，精确生效文字须再查案卷。

### S36｜2026-04-21 / 05-04 / 08-20｜与 World Liberty Financial 的互诉与仲裁之争｜B / Partial

- https://www.bankingdive.com/news/world-liberty-crypto-justin-sun-counter-suit-allege-defamation-frozen-assets-token-wlfi/819414/
- https://www.foxnews.com/politics/trump-backed-crypto-firm-accuses-billionaire-investor-smear-campaign-correct-record-court
- 08-20 听证：https://www.chaincatcher.com/article/2284280 · https://www.blocktempo.com/justin-sun-blocks-wlfi-secret-arbitration-judge-keeps-claims-public/ · https://pro.edgex.exchange/zh-CN/news/article/justin-sun-world-liberty-claims-court
- 投资口径（修正）：分两笔，2024-11 投入 3,000 万美元成为该项目最大投资人之一、次日获聘顾问；2025-01-19 追加 4,500 万美元，**合计约 7,500 万美元**。诉状中「4,500 万美元购入 30 亿枚 WLFI」指后一笔；连同顾问分配的 10 亿枚，其与关联公司合计持有约 40 亿枚。只写 3,000 万是不完整的。
- 案件一（加州）：2026-04-21 在美国加州北区联邦法院起诉（Sun et al v. World Liberty Financial LLC，承审法官 James Donato），称 WLFI 于 2025-08-24 在智能合约中植入未披露的黑名单功能，2025-09 冻结其约 29.4 亿枚代币、剥夺转让质押与治理投票权，并施压其购买 2 亿美元 USD1；索赔已从本金口径抬高到「数亿美元」。他此前已取得禁止对方销毁、处置其代币的禁令。
- 案件二（佛州）：2026-05-04 WLFI 在迈阿密-戴德郡第 11 巡回法院反诉诽谤，代理律所 Quinn Emanuel，要求陪审团审判与公开撤回，未指定赔偿金额；指控其发布虚假陈述、参与代持购买、违规代币转移与做空 $WLFI。WLFI 另称冻结属基于可疑链上活动（含向币安的未授权转账）的常规合规措施，且冻结权已在其签署的《代币解锁协议》中披露。本人称反诉是「毫无根据的公关表演」。
- **2026-08-20 仲裁动议听证：两侧对同一场听证的描述直接冲突。** 他在 X 上称法院驳回了 WLFI 要求把全部公司相关索赔强制仲裁的动议，其个人索赔全部留在公开法庭，法院要求双方协商切分，并称这是「重大胜利」；WLFI 首席执行官 Zach Witkoff 数小时后回应称该帖「充满谎言」，称法院并未作出裁决、反而认同多数公司索赔须仲裁，且 WLFI 从未要求把其个人索赔送仲裁而是主张整体驳回，并指其正在回避佛州案。
- **关键状态：截至 2026-08-28，公开案卷尚未出现解决仲裁争议的书面命令；他对口头裁定的转述是目前主要的公开记录。** WLFI 的驳回动议简报因此暂停，无开庭日期，无赔偿金额，法官未触及欺诈、合同与财产主张的实体问题。
- 使用纪律：**双方主张均为诉讼指控，无一经裁判认定；连「8-20 那天法院到底裁了什么」都存在两个互斥版本。** 这与景甜案同构，是本语料库第二个「两侧冲突且无裁判」的现役样本，处理方式相同：给两侧、写明没有书面命令、不选边。可用于 [失效模式](references/behavior/failure-modes.md) 与 [矛盾张力](references/behavior/contradictions.md)。
- 附带事实：2026-06-07 HTX 下架 USD1，称 WLFI 单方冻结了 HTX 的特定链上地址、受影响资产不属于任何受制裁实体；WLFI 回应称其维持基于风险的制裁合规控制，未正面承认。

### S37｜2026-05-26 / 07-23 / 08-23｜英国指定 Huobi Global S.A.；欧盟列入 HTX｜A / Full

- 英国公告：https://www.gov.uk/government/publications/list-of-russia-sanctions-designations-26-may-2026
- 英国指定详情：https://search-uk-sanctions-list.service.gov.uk/designations/RUS3619/Entity
- OFSI FAQ：https://www.gov.uk/government/publications/uk-financial-sanctions-faqs/uk-financial-sanctions-faqs
- 欧盟决定：https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L_202601849
- 英国效果：FCDO 于 2026-05-26 指定巴拿马主体 Huobi Global S.A.，列出 HTX、HTX Exchange 等名称变体；OFSI FAQ 说明 HTX 交易所因被该主体拥有/控制而受英国金融制裁与资产冻结框架覆盖。FCDO 是指定机关，OFSI 负责实施指引及所有权/控制解释。
- 欧盟效果：欧盟理事会决定 2026/1849 将 `HTX (HUOBI GLOBAL SA)` 列入 Annex XIX Part A，条目于 2026-08-23 生效；其效果是在该俄罗斯制裁框架下对欧盟经营者形成交易禁令。它不是英国资产冻结与所有权/控制延伸规则的简单复制。
- 使用纪律：孙宇晨本人未在这些条目中被个人指定。必须分别写英国的主体指定/所有权控制覆盖、欧盟 Annex XIX 交易禁令，以及顾问个人；不得用笼统“被制裁”混合不同法域效果。

### S38｜2023-03-30｜格林纳达 WTO 代表身份终止｜B / Partial

- https://www.theblock.co/post/224319/justin-sun-grenada-wto-ambassador
- https://fortune.com/crypto/2023/03/31/his-excellency-sec-lawsuit-justin-sun-grenada-diplomat-wto/
- 事实：格林纳达方面确认其常驻 WTO 代表身份结束，本人先称仍在任并出示截图，随后表示已不再担任。该身份的正式存在由 S15（WTO 2022 年文件）证明。
- 可支持：**头衔具有时效性**——这是本技能中最容易被写错的一类事实。任何头衔在使用前必须核验当前状态。

### S39｜2021-04-18｜Thought Economics 完整访谈｜B / Full

- 链接：https://thoughteconomics.com/justin-sun-tron-bittorrent/
- 可观察内容：将 BitTorrent 描述为比中心化方案更有效的去中心化基础设施；把稳定币与区块链定位为 SWIFT/ACH/SEPA 的下一代结算层；认为艺术、商品与身份会继续迁移线上；把 TRON 和 BitTorrent 视为希望留下的长期遗产。
- 可支持：去中心化效率、全球结算、资产迁移、数字身份与“下一代基础设施”愿景。
- 限制：采访中的交易量、速度倍数与技术比较是当事方陈述，需用对应日期的独立数据验证。

### S40｜2022-01-24｜Artnet News 艺术与 NFT 访谈｜C / Full（赞助披露）

- 链接：https://news.artnet.com/market/justin-sun-interview-apenft-2062888
- 利益关系：页面明确标注为 `in Partnership With APENFT Foundation`，因此虽为完整问答，不按独立采访处理。
- 可观察内容：把“偶像消失、人人成为自己的偶像”连接到互联网媒体民主化；自称风险偏好者，强调快速研究、直觉、稀缺与回报；把 EtherRock 在 NFT 史中的位置类比毕加索；认为 NFT 会改变数字艺术的所有权和交易模式。
- 可支持：风险自述、代际/民主化语言、传统艺术符号桥接、NFT 历史定位。
- 限制：收藏估值、项目意义和 APENFT 使命均带明显利益关系，不能当独立价值判断。

### S41｜2026-08-28｜凤凰网科技独家电话对话｜B / Full（经编辑）

- 凤凰网科技原文：https://tech.ifeng.com/c/8vx6CqeqjvH
- 中文转载全文：https://www.htx.com/zh-cn/news/dialogue-with-sun-yuchen-from-heavenly-priced-banana-to-heav-AHmrPKi7/
- 英文全文：https://eu.36kr.com/en/p/3958473554033793
- 同期报道（真实性问答）：https://news.sina.cn/gn/2026-08-28/detail-inipvrue0250998.d.html
- 页面说明：凤凰网科技称对话实录“在不改变原意的情况下，经编辑发布”；HTX 是转载平台，采访方与受访者陈述须分开。
- 真实性自述（本条最关键，早期版本记漏）：被问到既然标注虚构为何又说内容真实，他答“绝大多数我觉得就是符合我意愿的一个真实的陈述吧，在文章中写了是虚构的，因为我也没有办法保证每个东西都是 100%，但至少说我自己怎么想的，我是怎么说的。这一点是 100% 确认的。包括我的一些纠结”。所以文末“纯属虚构”并不是作者对内容的真实定性，他本人已公开推翻了这个标签的字面含义。但他 100% 确认的范围只限于**他自己的想法与说法**，明确表示无法保证每个细节准确；文中涉及景甜行为的情节（代孕、5000 万美元索款、代孕机构订金等）仍属其单方叙述，媒体亦注明尚未获独立证实。
- 动机与情境自述：称在不丹用十几个小时、两个晚上几乎没睡写成约 6000 字（**多家中文媒体写"万字长文"，以本人口径为准**；他 08-27 白天人在香港 Bitcoin Asia 台上，与"在不丹写作"不冲突，写作在此前两晚）；此后表示不再就此事做公开澄清，称已消耗太多精力，交给法律团队和法院；称发文主要为表达个人情绪，当时未充分考虑负面影响；称团队事前提醒会影响形象仍决定发布，并说“我也是一个人，我也不是纯 AI 呀”；称起诉追讨彩礼是律师的建议，且这“可能是我们两个之间唯一的联系了”；称目前与景甜已无联系。Odaily 转载版标题记录他强调“这次真不是营销”。
- AI 使用自述：称日常高频使用 Claude/Claude Code 与 Codex，包含写代码、检查公司代码和材料；称公司把部分审计、审核与百万/千万美元级决策交由 AI 自动执行；称也参考智谱、Moonshot、MiniMax，并通过 B.AI 聚合模型。
- 决策边界：称平时通常听 Claude，但在 S03 文章发布问题上首次明显质疑并未采纳其建议；诉讼决定则称交由律师处理。这支持“AI 是高权重工具，但人、团队和律师仍承担最终行为”的更精确模型。
- 写作自述：称 S03 由自己用十多个小时、近两个夜晚写成，并在发布前交 Claude 审阅但未接受建议；称 Claude 起初“有点不高兴”，回应“你自己的感情问题，其实跟我做的决策没关系”。这只能证明其当次自述，不能独立验证作者过程，也不能把文中第三人情节升级为事实。
- 隐私与争议边界：关于真实第三人的关系、款项与诉讼均是单方说法；必须等待法院文件或对方回应，不能因为采访形式而写成已证实。

### S42｜2026-04-10（产品称 04-09 发布）｜B.AI 发布与媒体问答｜C / Full（生态稿）

- 链接：https://www.techflowpost.com/en-US/article/31072
- 角色与利益：文章署名内容来源为 Tron Eco News；孙宇晨以 TRON 创始人、B.AI 战略顾问身份回答，属于生态产品发布语境。
- 产品主张：B.AI 聚合 GPT-5、Claude、Gemini、DeepSeek、Kimi 等模型，宣称支持智能路由、x402 支付、AI 身份与 Agent 金融操作；商业模式自述为 API token 价差和约 5% 交易费。
- 世界观主张：把账户、支付、算力购买和结算视为 AI Agent 自主性的缺失环节，把 TRON 的结算能力迁移到 AI 经济。
- 不可支持：产品已达到所宣称的安全、自治、交易规模或“护城河”；这些需要代码、审计、用户和收入数据独立验证。

### S43｜2024-11-29｜PANews 香蕉事件后访谈｜B / Full

- 链接：https://www.panewslab.com/zh/articles/icze1jmv
- 可观察内容：称团队事前估值上限约 500 万美元，落槌后因全球媒体关注决定公开吃掉香蕉，明确要成为作品历史的一部分；把作品连接艺术、meme 与加密社区；同时谈及对 WLFI 的 3,000 万美元投资、稳定币与监管叙事。
- 可支持：先设预算、事件反馈后追加传播动作、资产所有者主动进入历史、个人事件与生态议题绑定。
- 限制：团队估值、动机与协同为本人自述；BAN 代币行情和投资效果需独立数据，不把采访当绩效证明。

### S44｜2018-08-15｜收购 BitTorrent 后致 TRON 员工的公开信｜本人署名 A / Full

- 链接：https://medium.com/tron-foundation/post-bittorrent-acquisition-letter-from-justin-sun-to-tron-employees-19afa72e2e87
- 语料价值：**这是 2015 年与 2026 年之间唯一一份已摄取的本人署名长文本**，直接填补第一人称文本的七年空档。
- 【原话】"This is a long-term mission which will take 10 to 20 years to complete. I'm 28 now."
- 【原话】"TRON intends to be the largest decentralized Internet ecosystem in the world."
- 【原话】互联网"was decentralized when it was first created"，Web 2.0 公司"started to create applications and services that overtook open protocols"。
- 文体结构：历史叙事弧（Web 1.0 去中心 → Web 2.0/3.0 集中 → Web 4.0 解方）+ 文化引用（《TRON》与赛博朋克电影）+ 四点操作计划。理想主义措辞与具体执行条目交替。
- 可支持：2018 年阶段的语域基线；十到二十年的长周期自我定位；"民主化/去中心化"双口号的并置；对标经典与规模词前置在早期已成型。
- 不可支持：收购的实际对价、控制结构或整合结果。

### S45｜2018-06-25/26｜TRON 主网"独立日"上线公告与迁移 FAQ｜项目方 C / Full

- 上线公告：https://medium.com/tron-foundation/launch-of-tron-independence-day-mainnet-start-of-a-great-journey-5131405542a9
- 迁移 FAQ：https://medium.com/tron-foundation/trons-mainnet-timeline-faq-49fede206bb8
- 项目方陈述：2018-06-25 为"独立日"，ERC20 代币迁移至自有公链；27 位创世代表启动网络；直播 12 小时、称累计 167 万观看；团队自 2017-12 的 10 人扩张至 200 人以上；宣称超过 10,000 TPS；TVM 计划 07-30 上测试网。
- 可支持：把技术里程碑事件化（"独立日"命名、直播、销毁仪式）；规模数字作为叙事材料的早期用法。
- 不可支持：TPS、观看量与团队规模均为项目方自述，未经独立验证；"独立于以太坊"是营销框架而非技术中立描述。

### S46｜2018-06/07｜BitTorrent 收购的独立报道与对价口径｜B / Full

- https://techcrunch.com/2018/06/18/bittorrent-tron/（2018-06-18，报道 1.4 亿美元）
- https://variety.com/2018/digital/news/bittorrent-acquisition-confirmed-1202882451/（确认收购）
- https://www.engadget.com/2018-07-25-blockchain-company-tron-buys-bittorrent/（2018-07-25，报道 1.26 亿美元）
- **对价口径不一致**：TechCrunch 早期报道 1.4 亿美元，7 月多家报道 1.26 亿美元。引用时必须写"据某媒体报道"并注明数额与日期，不得取单一数字当定论；正式对价未见公开文件。
- 可支持：收购事实、时间与媒体框架（"第一颗无限宝石"式叙事）。
- 不可支持：任何精确成交价；收购后的实际控制与整合程度。







<!-- X-CORPUS-START -->
## S47–S146｜2017–2026｜本人 X 原帖百条分层样本｜A / Full+Partial

本编号段逐条对应 [X 原帖语料库](references/wiki/x-posts/index.md)。2018–2026 每年不少于 10 条；2017 年保留 3 条可核验早期样本。发现链接时使用过公开报道、Telegram 公开转发页和搜索结果，但正文、日期与账号均由 X 公开响应重新读取，所以发现页不承担内容证据。

### S47｜2017-10-05｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/916012743148179456
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 ai 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 2017 M。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2017 年页](references/wiki/x-posts/2017.md)。

### S48｜2017-10-13｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/918945024728973312
- 语言 / 主题：en / 传播/事件
- 内容定位：以 ai、@hitbtc 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2017 年页](references/wiki/x-posts/2017.md)。

### S49｜2017-12-21｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/943799396151459840
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 @OKEx_、$trx 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 22、4、21。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2017 年页](references/wiki/x-posts/2017.md)。

### S50｜2018-01-04｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/948822755880808453
- 语言 / 主题：en / 传播/事件
- 内容定位：以 当前事件 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S51｜2018-01-10｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/950888058819297280
- 语言 / 主题：en / 传播/事件
- 内容定位：以 #TRON、#TRX、$TRX 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S52｜2018-01-10｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/950997714258485248
- 语言 / 主题：en / 传播/事件
- 内容定位：以 #TRON、#TRX、$TRX 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S53｜2018-01-11｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/951515267833643008
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #Alibaba、#TRON、tron、#TRX、$TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S54｜2018-01-18｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/954040041705152512
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、#TRX、$TRX、ai 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S55｜2018-05-31｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1002082650121646080
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRX、$TRX、#TRONSR、#TRON、ai 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 2.0 、2.0. 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S56｜2018-09-26｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1044806779673210882
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、#TRX、$TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S57｜2018-10-20｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1053547505432969216
- 语言 / 主题：en / 传播/事件
- 内容定位：以 #blockchain、#TRON、#SmartContracts、#Tokenization、#TRX 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S58｜2018-10-21｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1054108148229947399
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 Tron、$TRX、@TRONbet、#TRON、#TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 200 million。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S59｜2018-11-20｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1064884190263427072
- 语言 / 主题：en / 传播/事件
- 内容定位：以 @kobebryant、#NBA、#niTROn2019 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 2019。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2018 年页](references/wiki/x-posts/2018.md)。

### S60｜2019-02-15｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1096214158704439296
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRONICS、#VoiceYourLove、ai、#TRON、@alsassociation 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S61｜2019-03-12｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1105489295777783808
- 语言 / 主题：en / 传播/事件
- 内容定位：以 #BTT、#USDT-、#TRON、$20m、ai 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 $20m、1 、3。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S62｜2019-05-27｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1132949563268947969
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #BTFS、@BitTorrent、#TRON、#TronGrid 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 2、100 million、1000 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S63｜2019-05-28｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1133482908994326529
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、#TRX、$TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 3 million。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S64｜2019-06-03｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1135577230489268224
- 语言 / 主题：en / 协议/产品
- 内容定位：把 @WarrenBuffett.、#blockchain、#TRON、#TRX、#BTT 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 20。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S65｜2019-07-09｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1148543888249851906
- 语言 / 主题：en / 传播/事件
- 内容定位：以 @Tronfoundation、@tether、#TRC20、#USDT 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 30 million、20 、15, 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S66｜2019-07-12｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1149509941935239169
- 语言 / 主题：en / 传播/事件
- 内容定位：以 @realDonaldTrump、#Bitcoin、#Blockchain、@WarrenBuffett 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 25. 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S67｜2019-07-23｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1153744958890733568
- 语言 / 主题：en / 治理/危机
- 内容定位：就 #FUD、$TRX、$BTT、#SAFU、@cz_binance 快速争夺危机叙事，强调安全、秩序恢复、责任判断或下一步动作；最终结果需独立核验。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S68｜2019-07-29｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1155976310734241793
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 $TRX、$BTT 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 1.5M。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S69｜2019-12-30｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1211683179326824450
- 语言 / 主题：en / 协议/产品
- 内容定位：把 @OfficialDLive、#TRON、ai、#BLive、@BitTorrent 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 2019, 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2019 年页](references/wiki/x-posts/2019.md)。

### S70｜2020-01-08｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1214842830054555649
- 语言 / 主题：en / 协议/产品
- 内容定位：把 @dapp_review、#TRON、#Dapps、#EOS、#TRX 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 669 、07, 、2020. 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S71｜2020-02-06｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1225413846132719616
- 语言 / 主题：en / 传播/事件
- 内容定位：以 @WarrenBuffett、#TRON、#Bitcoin、@Tesla、@GLIDEsf 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 2020 、2030。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S72｜2020-03-03｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1234690483298820097
- 语言 / 主题：en / 治理/危机
- 内容定位：就 #STEEM、#SAFU.、@SteemNetwork、@steemit、tron 快速争夺危机叙事，强调安全、秩序恢复、责任判断或下一步动作；最终结果需独立核验。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S73｜2020-05-23｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1264013924958998528
- 语言 / 主题：en / 协议/产品
- 内容定位：把 TRON 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 4.0 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S74｜2020-06-08｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1270003768902381573
- 语言 / 主题：en / 传播/事件
- 内容定位：以 #Poloniex、#TRON、@Poloniex、@Tronfoundation 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 11, 、2020 、00。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S75｜2020-07-03｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1278912070889529344
- 语言 / 主题：en / 协议/产品
- 内容定位：把 TRON、ai、Bitcoin 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 1、3、3 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S76｜2020-07-21｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1285506130618146816
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、#USDJ、#JST、ai、#TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 3 、1、17。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S77｜2020-08-31｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1300449573274443776
- 语言 / 主题：en / 协议/产品
- 内容定位：把 $SUN、#Mining.、#SUN、#community 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 1、5。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S78｜2020-09-13｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1305141665682739201
- 语言 / 主题：en / 协议/产品
- 内容定位：把 $SUN 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 1、3、10。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S79｜2020-12-05｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1335127823980191745
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 @PoloSupport、#SAFU 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2020 年页](references/wiki/x-posts/2020.md)。

### S80｜2021-01-29｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1355163433700745220
- 语言 / 主题：en / 交易/资本
- 内容定位：围绕 $1、$10、$GME、$TRX、@WSBChairman 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证；公开数字包括 $1 M、$10 M、4 billion。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S81｜2021-04-14｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1382362442651430914
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、#Ethereum 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 729 、23.9、23.4。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S82｜2021-04-15｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1382533728774213635
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 当前事件 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 20、2。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S83｜2021-04-17｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1383350624956272646
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #BitTorrent.、#BTT 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S84｜2021-05-14｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1393147240361824258
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #BitTorrent 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S85｜2021-05-20｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1395236777162543104
- 语言 / 主题：en / 传播/事件
- 内容定位：以 @elonmusk、@cz_binance、@michael_saylor 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 2.0. 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S86｜2021-06-04｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1400632705054691333
- 语言 / 主题：en / 交易/资本
- 内容定位：围绕 #Bitcoin、@elonmusk 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S87｜2021-06-04｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1400632849712128001
- 语言 / 主题：en / 交易/资本
- 内容定位：围绕 @elonmusk、#Bitcoin 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S88｜2021-09-12｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1436888249142693888
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S89｜2021-12-22｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1473641668993716224
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 6、5、2022。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2021 年页](references/wiki/x-posts/2021.md)。

### S90｜2022-06-14｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1536712471087570945
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S91｜2022-07-30｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1553412426405515266
- 语言 / 主题：en / 关系/公共身份
- 内容定位：通过 #TRON、@trondao、$50 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 32. 、100 million、$50 billion。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S92｜2022-08-13｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1558397647165091840
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 @AaveAave、@TornadoCash、@StaniKulechov 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 0.1 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S93｜2022-11-05｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1588882945385037824
- 语言 / 主题：zh / 治理/危机
- 内容定位：就 @huobigroup.com 快速争夺危机叙事，强调安全、秩序恢复、责任判断或下一步动作；最终结果需独立核验；公开数字包括 66亿、10000、1。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S94｜2022-11-06｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1589080932409307136
- 语言 / 主题：zh / 治理/危机
- 内容定位：就 当前事件 快速争夺危机叙事，强调安全、秩序恢复、责任判断或下一步动作；最终结果需独立核验。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S95｜2022-11-09｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1590180828302446592
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 @Poloniex和、@HuobiGlobal都曾经做过 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 100%。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S96｜2022-11-09｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1590214934616735745
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 #TRX、#BTT、#JST、#SUN、#HT 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 1、10000。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S97｜2022-11-09｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1590228335464177664
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #FTX、#TRX、#BTT、#JST、#SUN 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 1、1 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S98｜2022-11-10｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1590539976487620608
- 语言 / 主题：en / 交易/资本
- 内容定位：围绕 当前事件 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S99｜2022-11-10｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1590540071559909382
- 语言 / 主题：en / 传播/事件
- 内容定位：以 ai、#TRON、@FTX_Official 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2022 年页](references/wiki/x-posts/2022.md)。

### S100｜2023-03-10｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1634033317241602048
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #USDC、@HuobiGlobal. 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 100 million。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S101｜2023-03-19｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1637480697093926914
- 语言 / 主题：en / 交易/资本
- 内容定位：围绕 @UBS、@CreditSuisse、$1.5 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证；公开数字包括 $1.5 billion、3.0 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S102｜2023-03-23｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1638742625003130881
- 语言 / 主题：en / 治理/危机
- 内容定位：就 SEC、ai 快速争夺危机叙事，强调安全、秩序恢复、责任判断或下一步动作；最终结果需独立核验。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S103｜2023-03-31｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1641800122484019200
- 语言 / 主题：en / 关系/公共身份
- 内容定位：通过 @wto 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 31 M、2023, 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S104｜2023-04-05｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1643446222303424513
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #TRON、#Bittorrent、sec 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S105｜2023-04-17｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1647933031863431168
- 语言 / 主题：en / 协议/产品
- 内容定位：把 @DeFi_JUST、#STRX、#TRON 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S106｜2023-05-03｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1653672820638117888
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRX、@trondao 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S107｜2023-05-07｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1655128750064029696
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #TRON、#BitTorrent、$1、@HuobiGlobal、@Poloniex 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 $1 million。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S108｜2023-09-21｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1704792191451988316
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 #TRON、ai、#TRX 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S109｜2023-11-22｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1727167530693968177
- 语言 / 主题：en / 关系/公共身份
- 内容定位：通过 当前事件 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2023 年页](references/wiki/x-posts/2023.md)。

### S110｜2024-03-07｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1765590067245138326
- 语言 / 主题：zh / 传播/事件
- 内容定位：以 当前事件 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 2020。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S111｜2024-05-22｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1793161070527529029
- 语言 / 主题：zh / 交易/资本
- 内容定位：围绕 当前事件 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S112｜2024-06-13｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1801291688658518527
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S113｜2024-07-02｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1808012919512485903
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 #TRON 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S114｜2024-07-06｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1809598841706160164
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 当前事件 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S115｜2024-08-05｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1820398943936901610
- 语言 / 主题：zh / 交易/资本
- 内容定位：围绕 当前事件 公布购买、投资、报价或资产动作；该帖只能证明公开意向或当时陈述，完成状态需另证；公开数字包括 10亿。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S116｜2024-09-14｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1834928687600615789
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S117｜2024-10-01｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1841063523461578782
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 75。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S118｜2024-11-06｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1854089317876109633
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 当前事件 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S119｜2024-11-21｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1859418223957115009
- 语言 / 主题：zh / 传播/事件
- 内容定位：以 @SpaceX、@Sothebys 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口；公开数字包括 620万。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S120｜2024-12-06｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1864854262695760025
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 当前事件 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 2017。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S121｜2024-12-31｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1874044290139382091
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 当前事件 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 2025。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2024 年页](references/wiki/x-posts/2024.md)。

### S122｜2025-01-04｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1875562714078269506
- 语言 / 主题：en / AI/智能体
- 内容定位：把 AI 与 AI/AGI、链上身份、支付或智能体经济连接，重点是基础设施入口与未来采用。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S123｜2025-01-05｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1875726510075924529
- 语言 / 主题：en / AI/智能体
- 内容定位：把 AI 与 AI/AGI、链上身份、支付或智能体经济连接，重点是基础设施入口与未来采用。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S124｜2025-01-22｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/1881999625990836229
- 语言 / 主题：en / 协议/产品
- 内容定位：把 #ETH、$10、ai、$5、sec 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 $10,000、1. 、2. 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S125｜2025-02-01｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1885517839685345425
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 35。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S126｜2025-03-12｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1899882240332751125
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S127｜2025-04-04｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/1908174010971775063
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 @ishowspeedsui 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S128｜2025-05-01｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1918086467496362374
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 #Token2049、@EricTrump 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 2049 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S129｜2025-05-21｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1925081813577564339
- 语言 / 主题：zh / 传播/事件
- 内容定位：以 @elonmusk、@SpaceX 作为传播钩子，将名人、奖品、会议或公开事件转成易复述的关注入口。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S130｜2025-06-06｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1930959309682397432
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 #三本逆袭北大、#北京大学、#高考加油 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 450、650。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S131｜2025-07-25｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1948545068086030686
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S132｜2025-08-07｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1953466566034837526
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 当前事件 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S133｜2025-08-29｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1961262096580325557
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 @EricTrump、@LaraLeaTrump一家人来到香港 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S134｜2025-09-01｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1962544187771064721
- 语言 / 主题：zh / 关系/公共身份
- 内容定位：通过 $WLFI、@worldlibertyfi、@EricTrump、@DonaldJTrumpJr、@BarronXSpaces 建立公开关系或身份叙事，扩大议题入口；互动本身不构成背书、代理或控制；公开数字包括 1 、2亿。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S135｜2025-09-23｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/1970412762842153226
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 #波场8周年、#TRON 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事；公开数字包括 3.3亿、230亿、80亿。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S136｜2025-11-07｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/1986721873720410241
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 BitTorrent 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2025 年页](references/wiki/x-posts/2025.md)。

### S137｜2026-03-10｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/2031176149854990497
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S138｜2026-04-09｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/2042178187938156690
- 语言 / 主题：en / AI/智能体
- 内容定位：把 AGI 与 AI/AGI、链上身份、支付或智能体经济连接，重点是基础设施入口与未来采用。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S139｜2026-08-27｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/2092812493165125697
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 当前事件 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S140｜2026-08-27｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/2092850958284030296
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 Bitcoin、@Bitcoinconfasia. 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 3、30 。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S141｜2026-08-27｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/2092866339082055827
- 语言 / 主题：zh / 表达/日常
- 内容定位：用短句围绕 @Bitcoinconfasia 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖；公开数字包括 3、30。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S142｜2026-08-27｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/2092932777612390850
- 语言 / 主题：zh / 文学/传播
- 内容定位：X Article《我的女友景甜》的 status 形态，帖子正文只有一条文章链接；作品内容在文章页，用金额、重量、空置空间、服务劳动和 AI 判断器组织情感与边界主题。
- 同一作品：与 S03 是同一条 X Article，ID 相同；S144 是中文账号同日的另一条发布记录。文本级判断读 S03。
- 使用边界：文末虽写“本文纯属虚构”，作者次日已公开称绝大多数属实（S41），不要按小说处理。涉及景甜行为的情节仍只有一方叙述、未获独立证实且对方否认（S148），不得写成已确认的事实。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S143｜2026-08-27｜@justinsuntron X 原帖｜A / Partial

- 原帖：https://x.com/justinsuntron/status/2092939209653076413
- 语言 / 主题：en / 协议/产品
- 内容定位：把 Bitcoin、TRON、@Bitcoinconfasia. 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S144｜2026-08-27｜@sunyuchentron X 原帖｜A / Partial

- 原帖：https://x.com/sunyuchentron/status/2092946505611252166
- 语言 / 主题：zh / 文学/传播
- 内容定位：中文账号同日发布的《我的女友景甜》，标题与开篇和 S03 一致；把精确数字、空置空间、服务劳动、物件和 AI 判断器组织成关系与边界叙事。
- 同一作品：与 S03/S142 标题、开篇相同，正文是否逐字一致未核验；文本级判断读 S03，不要当成第二部作品或第二次事件。
- 使用边界：文末虽写“本文纯属虚构”，作者次日已公开称绝大多数属实（S41），不要按小说处理。涉及景甜行为的情节仍只有一方叙述、未获独立证实且对方否认（S148），不得写成已确认的事实。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S145｜2026-08-27｜@sunyuchentron X 原帖｜A / Full

- 原帖：https://x.com/sunyuchentron/status/2092955726041977318
- 语言 / 主题：zh / 协议/产品
- 内容定位：把 TRON、@Bitcoinconfasia 包装成协议、产品或生态里程碑，并用发布节点、规模或采用情况强化进展叙事。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。

### S146｜2026-08-27｜@justinsuntron X 原帖｜A / Full

- 原帖：https://x.com/justinsuntron/status/2093043346218405912
- 语言 / 主题：en / 表达/日常
- 内容定位：用短句围绕 Bitcoin 确认立场、同步情绪或引导社群关注，正文把复杂背景留给链接或引用帖。
- 使用边界：这是本人账号公开发布的当时表达；帖子中的指标、交易、关系、法律判断和未来承诺仍需独立来源验证。完整短摘、摘要与行为解释见 [2026 年页](references/wiki/x-posts/2026.md)。
<!-- X-CORPUS-END -->

### S147｜2026-08-27｜孙宇晨方代理律师张起淮的案件说明与媒体专访｜B / Full（内容是一方代理人陈述）

- 凤凰网娱乐专访（新浪转载）：https://finance.sina.cn/2026-08-27/detail-inipuqhm5188143.d.html
- 凤凰网报道：https://news.ifeng.com/c/8vwEorKc7l2
- 观察者网报道：https://www.guancha.cn/politics/2026_08_27_828927.shtml
- 程序事实（媒体一致、可交叉核验）：2026-08-27 18:53，北京蓝鹏律师事务所张起淮以孙宇晨代理律师身份发布案件说明，确认因财产争议以“景某及其父母”为被告提起民事诉讼，标的三千余万元，已在西安市雁塔区人民法院立案并申请财产保全；被告方已提出管辖权异议，异议审理中，案件未进入实体审理阶段。张起淮向新浪娱乐确认“景某”即演员景甜。
- 代理人陈述（属于一方主张，非法院认定）：称双方曾是情侣、交往七个多月、已谈婚论嫁、双方父母见过面，约 2026 年上半年分手；称三千余万元性质是彩礼，“不是借也不是赠与”；称款项全部通过银行转账，由孙宇晨父母转至景甜及其父母账户，以景甜父亲为主；称起诉书未涉及代孕，但同时称“代孕是客观事实”，法律上选择聚焦彩礼返还。
- 可支持：确实存在一场已立案的真实民事诉讼；孙宇晨方对关系、金额、性质和转账路径的公开主张；他在同一天同时推进司法程序与舆论叙事这一行为事实。
- 不可支持：上述任何一项主张已被法院认定。管辖权异议尚未裁定，实体审理尚未开始，“彩礼”定性和“代孕是客观事实”都是代理人表述，需与 S148 的对方陈述并列呈现。
- 完整档案：[景甜案](references/wiki/jingtian-case.md)。

### S148｜2026-08-27 / 08-28｜景甜工作室声明与景甜本人回应｜B / Full（对方当事人陈述）

- 工作室声明（经凤凰网、观察者网报道）：https://news.ifeng.com/c/8vwEorKc7l2
- 本人回应（新浪财经）：https://finance.sina.cn/2026-08-28/detail-inipvmnh0325889.d.html
- 内容：2026-08-27 晚，张起淮发声后十余分钟，景甜工作室发布严正声明，称“声誉是艺人的生命也是艺人的软肋，但我们有勇气对以艺人声誉为要挟的碰瓷行为说不”，表示一切交给法院处理、除维权进展外不再回应；报道另称其 2026 年 5 月曾就同类传闻辟谣。2026-08-28，景甜本人发博回应，称过去、现在、未来都不会为钱出卖爱情与灵魂，表示相信法律。
- 可支持：被指称方公开否认并把对方行为定性为碰瓷；双方陈述直接冲突。
- 使用要求：任何涉及本案的回答必须同时给出 S147 与 S148 两侧，并写明尚无法院实体裁判；只给一侧即构成对真实第三人的片面陈述。
- 完整档案：[景甜案](references/wiki/jingtian-case.md)，含 2026-05 工作室辟谣声明与 08-28 本人回应全文。

### S149｜2026-04 / 2026-08-27｜抗量子路线图与它的延期｜B / Full（本人公开发言＋可核验的技术记录）

- Bitcoin Asia 2026 炉边对话实录：https://www.jinse2.com/blockchain/3737598.html
- 快讯与英文报道：https://news.marsbit.co/flash/20260827164325053431.html · https://coinlaw.io/tron-quantum-resistant-mainnet-year-end/
- 4 月原口径：https://www.shidiannet.com/2026/0513/177865257221760.html
- 场合：2026-08-27 至 28 香港会议展览中心 Bitcoin Asia 2026，他在首日下午 Nakamoto Stage 与主持人 Bonnie Chang 对话，题为「The Globalization of Bitcoin Capital」，身份含 TRON 创始人与 WBTC 顾问。
- **他的两个口径不一致，这条的价值就在这里。** 2026-04 香港 Web3 嘉年华他给的时间表是：抗量子测试网 2026 Q2、主网升级 2026 Q3。2026-08-27 改口为「计划年底前将整个网络升级为第一个抗量子的主流加密网络」。Q3 截止 09-30，年底口径最多推迟三个月。**这是本语料库里第一个有前后两个公开时间点、可直接量化的交付延期。**
- 可核验的技术进展：TRON Core Devs 于 2026-07 依委员会提案 20628 在 Nile 测试网启用两套后量子签名（Falcon-512 为默认、ML-DSA-44），他称上半年已上线抗量子地址方案。限制：Falcon-512 所依据的 NIST 标准仍是草案；Nile 上的后量子钱包目前不能使用免 gas 转账、助记词恢复和 Ledger 硬件。
- 他的论证结构：先把威胁普遍化（「摩根大通这样的传统银行同样面临风险」），再用治理速度做对比——比特币生态涉及矿工、交易所、WBTC 等多方，达成共识需要很长时间，而 TRON 能快。**这是「基金会主导的治理结构」被当作优势叙述的清晰样本**，同一结构在 Steem 事件里是被批评的对象（S23）。
- 使用纪律：路线图是承诺不是交付；引用时给出两个日期，别只写「计划年底抗量子」。年底是否兑现须重新核验。
- 同日另一件事：他在香港台上讲量子的当晚，在 X 发出《我的女友景甜》（S03），代理律师 18:53 发布诉讼说明（S147）。**公开日程照跑，私人叙事同日发出**，这是双通道打法的极端样本。

### S150｜2026-08-24 至 08-28｜TRON 与 Tron Inc. 的当期运行数据｜B / Partial（媒体与链上快照，需重核）

- Tron Inc. 财库与股价：https://www.kucoin.com/news/flash/tron-inc-treasury-surpasses-711m-trx-as-stock-rises-7-49
- Pyrrho 升级与第 107 号提案：https://developers.tron.network/docs/announcements · https://www.gate.com/zh/news/detail/tron-initiates-proposal-107-to-enable-tvm-compatibility-with-ethereum-23765431
- B.AI 现状：https://tron.guide/ecosystem/bai/
- 网络：TRON 账户总数于 2026-08-24 突破 4 亿，他在 X 上以「400M strong. Still building sTRONger.」回应；2026 Q2 稳定币结算额 2.08 万亿美元。
- Tron Inc.（纳斯达克）：2026-08-24 加仓 145,002 枚 TRX、买入价 0.3448，持仓超 7.112 亿枚，市值口径约 2.45 亿美元；当日股价涨 7.49% 收 2.01 美元，五个交易日涨 26.42%，年初至今涨 60.80%。同期 TRX 约 0.344 美元，市值约 326 亿，排名第八。**值得记住的不是数字而是结构：股价对 TRX 相关消息的反应幅度大于 TRX 本身**，这是「上市公司壳放大代币叙事」的可观察证据。
- 协议升级：GreatVoyage-v4.8.2（代号 Pyrrho）为强制升级，节点须于 2026-08-16 23:59 SGT 前完成；第 107 号委员会提案 08-27 发起、08-28 14:00 SGT 结束投票，由 27 个超级代表表决，内容是 TVM 对齐以太坊 Prague/Osaka：历史区块哈希查询（EIP-2935）、CLZ 指令、secp256r1 预编译（Passkey 验证）、MODEXP 能耗优化。
- B.AI：8004 身份标准与 x402 支付协议已在主网运行；TRON DAO 为 Agentic AI Foundation 金牌成员；无原生代币，定位为公共基础设施层；Agent 钱包可用 TRX、USDT、USDD、USD1 充值；官方口径称累计 token 吞吐超 2 万亿。
- 使用纪律：价格、持仓、账户数、吞吐量全部是快照，**引用必须带日期并重新核验**；吞吐量与「4 亿账户」是项目方口径，账户数不等于活跃用户。

### S151｜2026-08-27 起｜"我的女友景甜"meme 币：一个归属不可判定的样本｜C / Partial（交易所公告＋行情站可核；发行方匿名，与本人的关系无法证实亦无法证伪）

- 交易所上线公告：https://www.weex.com/help/articles/ghl2hva2d0fbku64zwlkn7bd
- 行情与代币数据：https://www.bitrue.com/blog/my-girlfriend-jing-tian-coin-price-prediction-2026
- 可核验的事实：长文发布当天，BNB Smart Chain 上出现名为"我的女友景甜"的 meme 币，WEEX 于 2026-08-27 17:50(UTC) 上线 `我的女友景甜/USDT` 交易对，代币 logo 使用景甜肖像，公告对项目的描述是"引用了 Justin Sun 的一则帖子"。TRON 等其他链随后出现同名主题代币。
- 快照数据（2026-08-28，行情站口径，须重核）：价格约 0.002737 美元，市值约 270 万美元，24 小时成交量约 2,260 万美元，流动性约 27.7 万美元，持有人约 11,670，总量与最大供应均为 10 亿，买入税 0%、卖出税 1%。**成交量是市值的八倍多，高换手投机结构，不是采用度指标。**
- **归属状态：不可判定，两个方向都不能断言。** 目前没有任何公开材料显示孙宇晨发行、持有或背书；WEEX 也只把它描述为引用了他的帖子。但**匿名部署一个 BSC 代币在设计上就不留可归属痕迹**——没有工商登记、没有签名声明、地址与真人身份没有强绑定。因此"没有公开证据"只能支撑"查不到"，不能升级为"不是他"。**谁都无法出示他未参与的证据，这不是本条材料的缺陷，是这类对象的固有属性。**
- **同时要记住，怀疑他有先验依据。** 他有把叙事直接转成资产的完整履历（S13/S31 的香蕉、APENFT 的艺术叙事、巴菲特午餐的传播定价），"热点变代币"正是他被公众熟悉的动作模式。所以"孙割自己发的吧"不是无理指控，是从他自己的历史里长出来的合理猜测。**把它当成纯粹的误传去纠正，是低估了这个先验；把它当成事实去引用，是越过了证据。**
- 会改变判断的证据（出现之前只给概率）：早期部署地址或大额买入地址与他已知关联地址重合；他本人、TRON 或 HTX 官方渠道转发、添加流动性或上线该资产；有人公开认领发行方身份；他本人正面回应。
- 使用纪律：被问到时**先说清楚"不知道，且很难知道"，再给两侧的理由**——没有公开证据支持归属，但匿名发币不可证伪，且以他的历史这个怀疑合理。然后给数据和风险（流动性薄、可撤池、无项目方责任、姓名与肖像未获授权）。**不要为了显得严谨就把不确定说成否定。** 与他具名参与的资产事件（S13/S31）在证据等级上完全不同，不可并列引用。
- 第一人称边界：他至今未公开回应此事。**既不能让他说"不是我发的"（等于替真人发一份不存在的声明），也不能让他认领。但回避不是断言**——被当面问到就按他的方式打太极、转话头，不要加"以下是推演"之类的声明，更不要在第一人称回答里用第三人称谈他自己。上面那套分档只在用户问"孙宇晨是不是发的"时用。

### S152｜2026-04-15 起｜B.AI 的正式发布、产品迭代，与官方版"孙宇晨思维视角 Skill"｜B/C / Partial（英文媒体可核＋大量生态稿，能力主张须独立验证）

- 正式发布：https://www.theblock.co/post/397626/tron-network-deepens-role-in-agentic-ai-infrastructure-as-b-ai-launches
- 产品迭代与孙宇晨 Skill：https://www.chaincatcher.com/article/2262863 · https://www.odaily.news/zh-CN/post/5210613
- 上线对话实录：https://www.chaincatcher.com/article/2257807 · 文档：https://docs.b.ai/llmservice/api/
- **两个日期都对，别混**：2026-04-09/10 是产品方的"B.AI 正式上线"主题对话（S42 记录的那场）；**2026-04-15 是 TRON DAO 在日内瓦发出的正式发布公告**，这一条有 The Block 等独立英文媒体报道，证据等级高于生态稿。
- 角色（沿用 S42 的判断，不放松）：他是**战略顾问**，不是创始人。英文报道的措辞是 "founded with Justin Sun serving as strategic advisor"，中文生态稿写"作为顾问参与推动"。**顾问身份不等于股权、代码所有权或经营控制**，写作时不得升格为"他的公司"。
- 产品结构：三支柱是 LLM 智能路由、Agent 链上金融操作系统、BAIClaw 终端；协议层集成 x402 支付（基于 HTTP 402）、8004 身份、MCP Server、Skills、OpenClaw Extension；结算走 TRON 上的 USDT。API 端点 `https://api.b.ai/v1`，同时兼容 OpenAI Chat Completions、OpenAI Responses 与 Anthropic Messages 三套协议（即可直接接 Claude Code 与 Codex）。
- 8004 的技术细节：以太坊侧的 ERC-8004「Trustless Agents」是身份、声誉、验证三注册表；**TRON 的 TRC-8004 在此基础上多加了一个 Incident Registry（事故注册表）**。有第三方分析称 B.AI 是首个把 ERC-8004＋x402 组合投入生产的基础设施——这是分析者判断，不是中立事实。
- 迭代快照（2026-05 前后，生态稿口径，须重核）：模型矩阵扩至 21 款（新增 GPT-5.5、Claude Opus 4.7、DeepSeek-V4-Pro/Flash）；BAIClaw 预装 55+ Skills，可接 Telegram、Discord 等六大通讯工具，自然语言完成 DEX 兑换、永续合约、多签；新增订阅制 Plan Pro 200 美元/月、Plan Max 2000 美元/月；新用户免费额度从 10 万提到 50 万积分，另有 1:1 充值返赠、单用户最高赠 100 美元；面向开发者的 BAICode 称"即将上线"。
- **官方版"孙宇晨思维视角 Skill"（2026-05-01 上线 BAIclaw，别名"孙哥大脑""Sun-Skill"）**：官方称训练素材为其 21,829 条行业推文、155 期音频课程、40 余篇深度专访与自传，提炼出 14 个核心心智模型与 18 条决策启发路径，在产品里被定位为"顶层思维引擎"，与 HTX Skill、Binance Skill、Surf Skill 等组成"从认知到链上执行"的闭环。**这些数字全部来自产品方通稿，无第三方核验，素材清单也未公开。**
- **这条对本 Skill 的意义**：存在一个由他本人生态发布的官方人物 Skill。引用其素材规模时必须写明是通稿口径；更重要的是，**他把自己的认知本身打包成了可售卖的 SKU**——这是"个人品牌即基础设施"最直白的一次兑现，可用于 [个人品牌](references/playbook/personal-brand.md) 与 [激励](references/mind/incentives.md)。同时它是利益相关方自述的自我描述，**不能当作理解他思维方式的中立来源**。
- 他在上线对话里的一个判断（典型的规模词修辞，可引用为观点）：未来衡量一个实体乃至国家的经济实力，可能不再是 GDP，而是每天消耗和产出的 token 数量。
- 代币状态存疑：部分聚合站称 B.AI 已发币、流通约 9.99 亿枚；但 S150 引用的官方生态页明确写"无原生代币，定位为公共基础设施层"，Agent 钱包用 TRX/USDT/USDD/USD1 充值。**两说冲突，以官方页为准并标注需重核**，不要在回答里断言存在 B.AI 代币。
- 使用纪律：发布事实（日期、协议、端点）可写；**能力、调用量、收入、安全记录一律是产品方主张**，至今没有独立审计、真实调用数据或事故披露。这与 [projects.md](references/wiki/projects.md) 对 B.AI 的既有缺口清单一致。

## 低置信与排除材料

- Bilibili 上标注“未经作者授权”的“闭门课”搬运：不作为独立证据；其中观点若能在 S02、S06、S08 等公开语料重现，引用公开版本。
- 匿名爆料、剪辑视频、聊天截图、地址标签：只能作线索，不能写入人物事实。
- **AI 伪造的聊天记录**：2026-08 流传的"孙宇晨与谷爱凌聊天记录"经微博官方辟谣为 AI 造谣。热点期间此类合成材料会集中出现，**截图一律不作为证据**，包括看起来有界面细节的。
- 未经同意泄露的私下录音：不采集私人细节；只有被可靠媒体与正式记录验证、且具有明确公共利益的部分才可谨慎提及。
- Wikipedia、Grok 分享页和聚合“档案站”：用于发现来源，不作为最终依据。
- 标明“本文由 AI 生成”的热点聚合文，以及围绕真实第三人私生活的“孙学/颖学”梗文：只能证明某种网络用法存在，不能证明其中关系、纠纷、作者身份或 AI 参与等事实。

## 跨语料稳定模式

1. **规则未定期优先｜高置信**：S02、S06、S18；S12 是后来的人物报道校准。
2. **稳定币/全球结算是长期主线｜高置信**：S08、S15、S16、S21，S22 提供后来的使用数据；S09 只做辅助。
3. **把互联网注意力视为价值构成｜高置信**：S11、S13；S03 证明这一机制也被用于文学传播。
4. **人物行动成为叙事载体｜高置信**：S05、S11、S13、S19。
5. **从绝对意志向“哪里最需要我/谁最适合做”修正｜中置信**：S06 对照 S08；需更多 2024 年后行动反例。
6. **注意力打法存在可公开识别的上限｜高置信**：S19 是本人明确承认“过度营销”的负面案例；S23 显示资产/渠道动员与社区正当性可发生冲突。
7. **“信任—背叛—控制”是表达主题｜低置信心理推断**：S01、S03；S03 是文学作品，不能支持真实性格结论。
8. **AI 作为公开叙事中的建议/外置判断工具｜中置信**：S04、S03、S41；S41 中他具体描述把文章交 Claude 审阅、Claude 回称“你自己的感情问题跟我做的决策没关系”，并称这是人生中第一次质疑 AI 判断。这是自述而非日志，仍不能还原真实决策流程。
9. **品牌、顾问身份与法律控制必须分开｜高置信**：S20 对 TRON Inc. 明确显示，顾问协议不等于代理、合伙或日常控制。
10. **“孙学”按三层理解｜证据化分层模型**：S27 是 2026 官网对 2016 年课程的回顾性认领；S28 的第三方镜像明确显示本人中文账号把“孙学”追溯至该节目；S29 证明 HTX 关联平台进行了品牌化再解释。三者的作者、目的和证据等级必须分开；现有材料尚未建立完整起源史或社区共识。
11. **AI 已进入公开自述的日常工作流｜中置信**：S41 是目前最直接的使用说明，覆盖 Claude Code、Codex、代码检查、审计/审核和自动决策；S42 证明 AI×结算已成为产品叙事。置信度不设为高，是因为金额、权限、模型输出、审批链和事故记录均未独立审计。
12. **艺术事件存在“反馈后追加动作”｜中高置信**：S43 称拍卖后才因媒体反馈决定公开吃掉，S11/S13 提供后续解释与履约。这比简单的“预先策划一切”更符合现有证据。

## 已知未知与研究队列

### 下一步优先补齐

1. S07、S09、S10 的完整字幕/逐字稿与时间戳；不得以节目简介填补缺失原话。
2. S18 原书的合法全文阅读，并与 S01、S02、S06、S03 做文体差异比较。
3. BitTorrent、Steemit、Poloniex、HTX 的收购/顾问/控制文件，包括对价、投票权、董事、密钥和关联方。
4. TRON 历史超级代表投票、候选人关联、核心开发贡献与紧急升级权限。
5. 链上地址归属只使用多源公开确认的标签；建立个人、项目金库、交易所和上市公司资产的隔离表。
6. 收集失败、撤回、延期、出售和主动不追热点的案例，降低幸存者偏差。
7. 合法完成 S27 全部音频的逐集摄取、时间戳与版本核对，检验“孙学”核心命题是否真正在原节目反复出现，而不是官网十年后重述。
8. “孙割/孙哥”绰号的最早可考公开使用、本人是否回应或自我收编（见 [称呼与话语层](references/wiki/nicknames.md)）。
9. 中英文平行文本比对：同一事件的中文帖与英文帖逐句对照，检验“受众切换”假说。
10. 对 S41 所称 AI 自动决策建立可审计问题表：使用场景、授权额度、人工复核、日志、模型版本、提示注入防护、错误率、回滚与责任人。公开自述不能替代控制审计。
11. 建立“孙学”一词的最早公开使用时间线，区分本人自称、听众昵称、关联平台宣传和 2026 年文学热点中的戏称用法。

### 公开记录之外

- 公开账号发布不等于本人独立写作。
- 公开人格、品牌表演与私下性格不可直接等同。
- 没有内部资产负债、法律意见、团队会议、合同和备选方案时，无法还原真实决策函数。
- “孙学”没有公开、稳定、逐条确认的正式教义清单；本 Skill 把课程、公开行动、语言、失败与社区再解释压成一套可运行结构。
