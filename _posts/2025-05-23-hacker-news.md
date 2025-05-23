---
layout: page
title: 勒西科技日报 - 2025年05月23日
date: 2025-05-23 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. VS Code 全新 PostgreSQL 集成开发环境发布；
1. 找到你的同路人；
1. 为什么我的HTTPS网站不再使用传统证书；
1. OpenAI如何用PostgreSQL支撑亿级用户；
1. MCP：Web 2.0精神的复兴；

以上是今天的前五条黑科技新闻标题。

总共22条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. VS Code 全新 PostgreSQL 集成开发环境发布 
<small>🔗 [techcommunity.microsoft.com](https://techcommunity.microsoft.com/blog/adforpostgresql/announcing-a-new-ide-for-postgresql-in-vs-code-from-microsoft/4414648): Postgres IDE in VS Code</small>


| 🔥🔥: 589 \| 💬: [257](https://news.ycombinator.com/item?id=44073588) \| 🗓️ 2025-05-23


<br />
微软推出 **PostgreSQL 扩展** 预览版，深度整合 **GitHub Copilot** 智能代理 `@pgsql`，支持数据库管理、模式可视化、自然语言交互及 **Entra ID 无密码认证**。该工具显著提升开发效率，减少上下文切换，提供实时性能优化建议，并支持本地与云端 PostgreSQL 实例无缝连接。现可通过 VS Code 扩展市场安装体验。

---

## <a name="2"></a>2. 找到你的同路人 
<small>🔗 [foundersatwork.posthaven.com](https://foundersatwork.posthaven.com/find-your-people): Find Your People</small>


| 🔥🔥: 315 \| 💬: [140](https://news.ycombinator.com/item?id=44074017) \| 🗓️ 2025-05-23


<br />
演讲者回顾自己迷茫的毕业经历，提醒毕业生**人生轨道在此终结**，必须主动选择方向。他建议通过**接触有趣的人**发现兴趣点，并强调**拒绝被否定**的重要性——多数雄心勃勃的想法最初都看似荒谬。关键在于摆脱随波逐流，重新定义自我，像他最终通过创业圈找到热情所在。

---

## <a name="3"></a>3. 为什么我的HTTPS网站不再使用传统证书 
<small>🔗 [rachelbythebay.com](https://rachelbythebay.com/w/2025/05/22/ssl/): Why I no longer have an old-school cert on my HTTPS site</small>


| 🔥🔥: 215 \| 💬: [215](https://news.ycombinator.com/item?id=44071690) \| 🗓️ 2025-05-23


<br />
作者曾因对**ACME协议**的复杂性和现有客户端代码的不可靠性感到厌恶，长期坚持使用传统SSL证书。但随着注册商Gandi服务质量下降，他被迫转向ACME，通过自研工具逐步实现协议流程，最终成功为网站[rachelbythebay.com]部署Let's Encrypt证书。文中详述了破解**JSON编码**、**RSA密钥处理**等难题的过程，并讽刺协议设计的冗余。这一转变体现了技术迭代中开发者对安全与效率的权衡。

---

## <a name="4"></a>4. OpenAI如何用PostgreSQL支撑亿级用户 
<small>🔗 [pixelstech.net](https://www.pixelstech.net/article/1747708863-openai%3a-scaling-postgresql-to-the-next-level): OpenAI: Scaling PostgreSQL to the Next Level</small>


| 🔥🔥: 172 \| 💬: [118](https://news.ycombinator.com/item?id=44071418) \| 🗓️ 2025-05-23


<br />
OpenAI在PGConf.dev 2025上分享了其**非分片架构**的PostgreSQL实践：单主库+40+只读副本支撑5亿用户，读写峰值超百万QPS。**主库写入瓶颈**通过写操作卸载、查询优化和轻量级Schema变更缓解，同时利用跨地域副本降低延迟。案例显示，即使顶级硬件和Azure托管服务仍需应对WAL复制延迟、索引膨胀等问题。OpenAI呼吁社区改进索引禁用、监控指标和Schema变更历史功能。评论指出，单机PostgreSQL的扩展性再次验证“分布式数据库是伪需求”的观点。

---

## <a name="5"></a>5. MCP：Web 2.0精神的复兴 
<small>🔗 [anildash.com](https://www.anildash.com//2025/05/20/mcp-web20-20/): MCP is the coming of Web 2.0 2.0</small>


| 🔥🔥: 166 \| 💬: [139](https://news.ycombinator.com/item?id=44073785) \| 🗓️ 2025-05-23


<br />
**MCP（模型上下文协议）**由Anthropic提出，现被OpenAI等广泛采纳，成为AI与外部系统交互的开放标准。尽管协议本身设计松散，但其快速普及重现了**Web 2.0时代**的开放精神——强调**互操作性**和开发者协作，而非封闭平台垄断。作者指出，Facebook等巨头曾扼杀这一愿景，而MCP的兴起可能推动AI生态回归开放协议，赋予用户和开发者更多控制权。然而，协议仍存在**数据透明度**与安全风险，需社区持续监督。

---

## <a name="6"></a>6. 我是如何成为也门航空飞行员并活下来的 
<small>🔗 [pprune.org](https://www.pprune.org/terms-endearment/653181-yemenia-expat-contract-full-info.html): How I ended up flying for Yemen's national airline – and survived</small>


| 🔥🔥: 152 \| 💬: [26](https://news.ycombinator.com/item?id=44072971) \| 🗓️ 2025-05-23


<br />
作者分享了在**也门航空**担任飞行员的惊险经历。面对**战乱**和落后的航空基础设施，他克服了重重困难，包括飞机维护不足、空域管制混乱等问题。文章揭示了在极端环境下飞行的**职业挑战**与生存智慧，展现了航空业不为人知的一面。

---

## <a name="7"></a>7. 在美国如何靠每月432美元生活 
<small>🔗 [shagbark.substack.com](https://shagbark.substack.com/p/how-to-live-on-432-a-month-in-america): How to live on $432 a month in America</small>


| 🔥🔥: 127 \| 💬: [235](https://news.ycombinator.com/item?id=44074340) \| 🗓️ 2025-05-23


<br />
作者以纽约州北部小镇**马塞纳**为例，提出一种**极简生活方式**：购买2.9万美元的小屋，利用廉价水电、公共交通和本地资源（如狩猎、垂钓），将月开销控制在432美元。关键在于放弃都市繁华，接受偏远地区的低消费生活，并通过零工或副业（如季节性工作、手工艺品销售）补充收入。文章强调，这种回归祖辈生活模式的选择，能摆脱债务压力，获得更多自由时间，同时为衰落社区注入活力。

---

## <a name="8"></a>8. 凯撒的最后一口气 
<small>🔗 [charliesabino.com](https://charliesabino.com/caesars-last-breath/): Caesar's Last Breath</small>


| 🔥🔥: 118 \| 💬: [48](https://news.ycombinator.com/item?id=44073185) \| 🗓️ 2025-05-23


<br />
每次呼吸时，我们大约会吸入**1个分子**来自凯撒临终前的最后一口气。这一惊人结论源自**费米估算**，通过简化计算得出：地球大气体积与单次呼吸体积之比约为1/10²²，而每次呼吸包含约10²²个分子。由此推断，我们吸入的空气可能混合了历史上所有人的气息，包括苏格拉底、爱因斯坦等。**估算技巧**和**数量级思维**是这一有趣推理的核心，展示了科学直觉的魅力。

---

## <a name="9"></a>9. HN时间线视图：hcker.news——更符合人体工学的Hacker News前端 
<small>🔗 [hcker.news](https://hcker.news): Show HN: hcker.news – an ergonomic, timeline-based Hacker News front page</small>


| 🔥🔥: 109 \| 💬: [52](https://news.ycombinator.com/item?id=44075353) \| 🗓️ 2025-05-23


<br />
hcker.news是一个**Hacker News的替代界面**，主打**时间线浏览模式**，支持自定义筛选（如按投票数、关键词、内容类型）。用户可调整布局、主题和字体，并利用**高级过滤功能**（如排除特定关键词或仅显示个人博客等**Small Web内容**）。该工具还集成hackerweb.app，优化评论页面的浏览体验。

---

## <a name="10"></a>10. 超越语义：无意义中间标记的惊人有效性 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2505.13775): Beyond Semantics: Unreasonable Effectiveness of Reasonless Intermediate Tokens</small>


| 🔥: 89 \| 💬: [45](https://news.ycombinator.com/item?id=44074111) \| 🗓️ 2025-05-23


<br />
这篇论文挑战了当前对**思维链（CoT）**的普遍认知，认为中间标记的语义准确性并非模型性能的关键。研究者通过训练模型使用形式化验证的推理轨迹（如A*搜索算法），发现即使中间步骤错误，模型仍能输出正确答案。更惊人的是，使用**随机噪声替换正确中间标记**后，模型性能不仅未下降，有时甚至表现更好。这一结果表明，语言模型的“推理行为”可能被过度拟人化解读，**中间标记的实际作用可能与其表面语义无关**。研究呼吁谨慎对待CoT的解释性，避免将其等同于人类或算法的真实推理过程。

---

## <a name="11"></a>11. 注意力机制并非万能：现代Transformer技术演进 
<small>🔗 [stephendiehl.com](https://www.stephendiehl.com/posts/post_transformers/): Attention Wasn't All We Needed</small>


| 🔥: 89 \| 💬: [14](https://news.ycombinator.com/item?id=44075105) \| 🗓️ 2025-05-23


<br />
本文探讨了自《Attention Is All You Need》论文发表以来的多项重要技术改进，重点介绍了**分组查询注意力(GQA)**和**多头潜在注意力**两大核心优化。**GQA**通过共享键值头显著降低推理时的内存占用，而**潜在注意力**则引入可学习的中间向量，将计算复杂度从O(L²)降至O(L·N)。这些技术平衡了模型性能与计算效率，使Transformer能处理更长序列。文章还提供了PyTorch实现代码片段，展示关键技术细节。

---

## <a name="12"></a>12. 大语言模型判读不可靠：位置偏好、顺序效应与提示词敏感性问题 
<small>🔗 [cip.org](https://www.cip.org/blog/llm-judges-are-unreliable): Positional preferences, order effects, prompt sensitivity undermine AI judgments</small>


| 🔥: 87 \| 💬: [51](https://news.ycombinator.com/item?id=44074668) \| 🗓️ 2025-05-23


<br />
研究表明，**大语言模型（LLM）**在敏感领域（如招聘、法律）的决策中存在系统性偏差。**位置偏好**（选项B被选概率高达61%）、**顺序效应**（评分标准顺序影响结果）和**提示词敏感性**（细微改动导致输出大幅波动）严重削弱其可靠性。模型还表现出类似人类的认知偏差（如锚定效应），且不同模型偏差模式各异。解决方案包括使用中性标签、多模型验证及严格测试提示词组件，但根本问题源于LLM架构本身的不可预测性。开发者需警惕高风险场景的应用，并借助工具量化这些偏差。

---

## <a name="13"></a>13. 2030年的清晨日常 
<small>🔗 [marginalia.nu](https://www.marginalia.nu/log/a_120_morning_routine_2030/): A 2030 Morning Routine</small>


| 🔥: 82 \| 💬: [30](https://news.ycombinator.com/item?id=44072110) \| 🗓️ 2025-05-23


<br />
你被全息助手**Kyle**叫醒，随后被**AI咖啡机Evan**、智能鞋带**George**等喋喋不休的AI包围。合成咖啡代替了昂贵的真咖啡，健身房因API故障无人值守，但**储物柜**仍要求繁琐的身份验证。通勤时，车载AI**Ulysses**一路推销功能。最终你瘫在工位，戴上耳机重复着Evan的台词——这注定是漫长的一天。

---

## <a name="14"></a>14. 遗传算法驱动的群体模拟系统 
<small>🔗 [attentionmech.github.io](https://attentionmech.github.io/genetic-boids/): Show HN: Genetic Boids Web Simulation</small>


| 🔥: 82 \| 💬: [20](https://news.ycombinator.com/item?id=44075911) \| 🗓️ 2025-05-23


<br />
该模拟程序通过**遗传算法**控制虚拟鸟群（Boids）的群体行为，用户可调节种群数量（1000只）、运动参数（最大速度2.5、作用力0.1）及**三种关键行为规则**：对齐（权重1.0）、分离（1.5）和聚合（1.0）。支持基因信号传递（概率0.002、范围50），并实时显示帧率、信号活跃度等数据。提供"平静""混乱""密集"等预设模式，底层采用网格优化（单元格50）保障性能。

---

## <a name="15"></a>15. 米制的起源：从法国大革命到现代科学 
<small>🔗 [abc.net.au](https://www.abc.net.au/news/science/2025-05-20/metre-treaty-anniversary-metric-system-measurement-metrology/105302024): The metre originated in the French Revolution</small>


| 🔥: 69 \| 💬: [127](https://news.ycombinator.com/item?id=44073867) \| 🗓️ 2025-05-23


<br />
米制诞生于**法国大革命**时期，最初定义为地球北极到赤道距离的千万分之一。1875年《米制公约》签署后，国际度量衡局成立，推动全球统一测量标准。随着科技进步，米制定义历经变革：1960年改用**氪86原子波长**，1983年最终以**光速**和原子钟重新定义。尽管澳大利亚等国家逐步采用公制，美国仍保留英制单位。如今，米制已成为科学和贸易的基石，甚至用于测量地月距离。

---

## <a name="16"></a>16. Samchika：Java高性能多线程文件处理库 
<small>🔗 [github.com](https://github.com/MayankPratap/Samchika): Show HN: Samchika – A Java Library for Fast, Multithreaded File Processing</small>


| 🔥: 56 \| 💬: [43](https://news.ycombinator.com/item?id=44072788) \| 🗓️ 2025-05-23


<br />
Samchika（梵语“文件”之意）是一个**轻量级**、**多线程**的Java文件处理库，专为高效处理大文件设计。它通过**并行处理**显著提升性能（实测70%以上速度提升），支持日志分析、ETL操作等场景。提供简洁API，可实时统计运行指标，内存占用低（16GB文件仅需约800MB）。采用MIT开源协议，支持Maven/Gradle一键集成。

---

## <a name="17"></a>17. 加拿大阿尔伯塔省分离主义运动再起波澜 
<small>🔗 [nytimes.com](https://www.nytimes.com/2025/05/22/world/canada/alberta-separatism-referendum.html): Alberta separatism push roils Canada</small>


| 🔥: 52 \| 💬: [209](https://news.ycombinator.com/item?id=44074684) \| 🗓️ 2025-05-23


<br />
尽管**阿尔伯塔省脱离加拿大的可能性极低**（需修改宪法等障碍），但该省正推动公投，以表决是否支持独立。作为**加拿大保守派重镇**和石油资源中心，当地长期不满联邦政策对能源开发的限制，部分居民甚至倾向加入美国。分离主义声音因特朗普的"吞并加拿大"言论及联邦自由党连任被放大，但魁北克独立运动近年已式微。

---

## <a name="18"></a>18. 风洞的秘密世界 
<small>🔗 [jordanwtaylor2.substack.com](https://jordanwtaylor2.substack.com/p/into-the-tunnel): Into The Tunnel: The secret life of wind tunnels</small>


| 🔥: 47 \| 💬: [5](https://news.ycombinator.com/item?id=44074637) \| 🗓️ 2025-05-23


<br />
风洞是模拟气流环境的实验设备，从**NASA艾姆斯低速风洞**（全球最大，功率达104兆瓦）到法国超音速风洞和德国低温氮气风洞，形态多样。它们用于测试飞机、赛车甚至城市风场，通过**雷诺数**和**马赫数**等参数确保实验准确性。尽管计算机模拟兴起，风洞仍是验证复杂气动现象（如激波、颤振）的关键工具，结合荧光涂料、激光测速等技术获取数据。其独特价值在于平衡成本与安全性，填补理论与实景测试的鸿沟。

---

## <a name="19"></a>19. 瑞昱10美元微型万兆网卡即将登陆主板 
<small>🔗 [tomshardware.com](https://www.tomshardware.com/networking/realteks-usd10-tiny-10gbe-network-adapter-is-coming-to-motherboards-later-this-year): Realtek's $10 tiny 10GbE NIC will hit motherboards soon</small>


| 🔥: 46 \| 💬: [41](https://news.ycombinator.com/item?id=44071701) \| 🗓️ 2025-05-23


<br />
瑞昱（Realtek）在Computex 2025展会上展示了**RTL8127**微型万兆网卡控制器，尺寸仅9mm x 9mm，支持2.5G/5G/10G多种速率，功耗低至1.95W，并集成**硬件级纠错（ECC）**和自检功能。该芯片售价约10美元，预计2025年底量产，将推动万兆网络在主流主板和笔记本中的普及。不过，当前**10GBase-T交换机**和CAT6A线缆的高成本仍是普及障碍，但随着需求增长，价格有望下降。

---

## <a name="20"></a>20. 用Emacs的dired-mode替代文件管理器 
<small>🔗 [lynn.sh](https://lynn.sh/guix-emacs-file-manager.html): Emacs dired-mode as a file manager</small>


| 🔥: 46 \| 💬: [26](https://news.ycombinator.com/item?id=44075388) \| 🗓️ 2025-05-23


<br />
作者分享如何通过**Emacs**的**dired-mode**替代传统文件管理器（如Nautilus或Dolphin），并解决Linux系统中目录默认打开方式的问题。通过配置**xdg-mime**，将`inode/directory`类型关联到Emacs，实现直接以dired模式打开文件夹。文中提供了Guix系统的具体配置代码，并建议扩展其他MIME类型（如图片、文本）以实现更统一的文件管理。最后推荐了Guix配置框架rde，帮助用户构建可复现的系统。

---

## <a name="21"></a>21. 谷歌AI模式被出版商指责为"盗窃行为" 
<small>🔗 [9to5google.com](https://9to5google.com/2025/05/22/google-ai-mode-theft-publisher-opt-out-controls/): Google's AI Mode is 'the definition of theft,' publishers say</small>


| 🔥: 43 \| 💬: [42](https://news.ycombinator.com/item?id=44075346) \| 🗓️ 2025-05-23


<br />
2025年5月23日，Abner Li报道称，出版商集体批评**谷歌的AI摘要功能**未经许可抓取内容，称其**"本质上是盗窃"**。该争议源于Android 16 QPR1 Beta 1测试版中新增的AI功能，可自动生成网页内容摘要，但未向原创者提供补偿或流量回馈。出版商强调，此举将**破坏内容生态**，威胁行业可持续发展。

---

## <a name="22"></a>22. 破折号的逆袭：人类专属标点符号「Am Dash」诞生 
<small>🔗 [theamdash.com](https://www.theamdash.com): Amdash – Human only punctuation mark</small>


| 🔥: 40 \| 💬: [34](https://news.ycombinator.com/item?id=44072922) \| 🗓️ 2025-05-23


<br />
在AI泛滥的时代，**破折号（em dash）**因被算法文本滥用而失去人类书写的神韵。为此，设计师推出**「Am Dash」**——一个象征真实思考与创作的新标点，仅限人类使用。配套字体Times New Human和Areal可通过输入"am-"自动生成该符号。ChatGPT评价其是**「对AI空洞文本的文化修正」**，像指纹般标记人类思想的独特性。这一设计既是对AI的幽默反击，也是对文学灵魂的捍卫。

---
