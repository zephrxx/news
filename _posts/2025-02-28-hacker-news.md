---
layout: page
title: 勒西科技日报 - 2025年02月28日
date: 2025-02-28 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 泽连斯基愤怒离开白宫会议；
1. Mozilla 删除了永不出售 Firefox 数据的承诺；
1. 如何在数亿人和热门应用上获得代码执行权限；
1. 暴力改变人类基因，影响几代人，研究人员发现；
1. GitHub诈骗调查：数千个“模组”和“破解”盗取数据；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 泽连斯基愤怒离开白宫会议 
<small>🔗 [bbc.com](https://www.bbc.com/news/live/c625ex282zzt): Zelensky leaves White House after angry meeting</small>


| 🔥🔥: 2239 \| 💬: [3285](https://news.ycombinator.com/item?id=43208973) \| 🗓️ 2025-02-28


<br />
泽连斯基与特朗普的会晤气氛截然不同，**白宫的紧张局势**让人震惊。此次会谈后，欧洲各国将更加关注如何应对**华盛顿与基辅关系的公开破裂**。即将召开的峰会将成为关键时刻，决定未来的外交策略。

---

## <a name="2"></a>2. Mozilla 删除了永不出售 Firefox 数据的承诺 
<small>🔗 [twitter.com](https://twitter.com/LundukeJournal/status/1895249805338886591): Mozilla deletes promise to never sell Firefox data</small>


| 🔥🔥: 838 \| 💬: [6](https://news.ycombinator.com/item?id=43203096) \| 🗓️ 2025-02-28


<br />
Mozilla 最近取消了其对用户数据隐私的承诺，表示将不再保证不会出售 Firefox 用户的数据。这一变化引发了用户对隐私保护的担忧，尤其是在当前数据安全问题日益严重的背景下。此举可能影响用户对 Firefox 的信任，促使他们重新考虑使用该浏览器的决定。

---

## <a name="3"></a>3. 如何在数亿人和热门应用上获得代码执行权限 
<small>🔗 [kibty.town](https://kibty.town/blog/todesktop/): How to gain code execution on hundreds of millions of people and popular apps</small>


| 🔥🔥: 559 \| 💬: [130](https://news.ycombinator.com/item?id=43210858) \| 🗓️ 2025-02-28


<br />
这篇文章讲述了作者在研究**Cursor**时发现的一个安全漏洞。通过**todesktop**的安装程序，作者进行了一系列的调查，发现了一个不安全的**Firebase**集合和一个**S3**上传漏洞。最终，作者成功利用这些漏洞在应用程序中植入了反向 shell，获取了**Firebase**管理员密钥，从而能够推送自动更新到使用todesktop的应用，如**ClickUp**和**Notion**，影响数亿用户。作者与todesktop的团队迅速沟通并修复了漏洞，展现了良好的安全响应。

---

## <a name="4"></a>4. 暴力改变人类基因，影响几代人，研究人员发现 
<small>🔗 [news.ufl.edu](https://news.ufl.edu/2025/02/syrian-violence-epigenetics/): Violence alters human genes for generations, researchers discover</small>


| 🔥🔥: 375 \| 💬: [222](https://news.ycombinator.com/item?id=43206722) \| 🗓️ 2025-02-28


<br />
研究表明，经历暴力的女性在怀孕期间会在其后代的基因中留下**表观遗传**的印记。这项研究揭示了**应激**如何通过母系传递影响未来几代人，强调了暴力对社会的深远影响。研究人员发现，经历过冲突的家庭的后代在基因中有14个区域发生了变化，显示出对暴力的共同反应。这些发现可能有助于理解**贫困**和**创伤**的代际循环，并呼吁对暴力问题的重视。

---

## <a name="5"></a>5. GitHub诈骗调查：数千个“模组”和“破解”盗取数据 
<small>🔗 [timsh.org](https://timsh.org/github-scam-investigation-thousands-of-mods-and-cracks-stealing-your-data/): Github scam investigation: Thousands of “mods” and “cracks” stealing data</small>


| 🔥🔥: 369 \| 💬: [154](https://news.ycombinator.com/item?id=43203158) \| 🗓️ 2025-02-28


<br />
在一个社交工程论坛上发现了一种新型诈骗，**成千上万的GitHub仓库**被创建，伪装成Roblox和Fortnite的模组或破解软件。一旦下载并运行，这些程序会收集用户的电脑数据并发送到Discord服务器，**寻找加密钱包私钥、银行账户和社交媒体凭证**。通过分析恶意代码，发现其为一种名为**Redox**的窃取器，能够在用户不知情的情况下收集敏感信息。

---

## <a name="6"></a>6. 3200% CPU 利用率 
<small>🔗 [josephmate.github.io](https://josephmate.github.io/2025-02-26-3200p-cpu-util/): 3,200% CPU Utilization</small>


| 🔥🔥: 368 \| 💬: [159](https://news.ycombinator.com/item?id=43207831) \| 🗓️ 2025-02-28


<br />
我的机器曾经出现了 **3200% 的 CPU 利用率**，所有 32 个核心都被完全占用。通过 Java 17 的线程转储，我发现多个线程在访问一个未加锁的 **TreeMap** 时出现了问题。代码中的一个逻辑错误导致了不必要的迭代，最终引发了性能问题。经过实验，我确认了并发访问未加锁的 **TreeMap** 可能导致 **无限循环**，从而造成 CPU 利用率飙升。这一发现不仅揭示了潜在的代码缺陷，还强调了在多线程环境中对数据结构的保护重要性。

---

## <a name="7"></a>7. 写作以逃离你的默认设置 
<small>🔗 [kupajo.com](https://kupajo.com/write-to-escape-your-default-setting/): Write to Escape Your Default Setting</small>


| 🔥🔥: 281 \| 💬: [71](https://news.ycombinator.com/item?id=43206174) \| 🗓️ 2025-02-28


<br />
对于思维能力平平的人来说，写作提供了**结构**和**清晰度**，帮助我们理清混乱的思绪。我们的思维常常处于“**持续近似模式**”，只是在脑海中反复琢磨，而非深入探索。写作能够揭示我们内心的盲点和假设，促使我们更有效地思考。通过写作，我们不仅能够更好地表达自己，还能发现潜在的偏见和误解。正如斯蒂芬·金所说，写作就像在清澈的河水中搅动泥沙，帮助我们清理心灵的混乱。

---

## <a name="8"></a>8. 鲍里斯·斯帕斯基：1937–2025 
<small>🔗 [en.chessbase.com](https://en.chessbase.com/post/boris-spassky-1937-2025): Boris Spassky: 1937–2025</small>


| 🔥🔥: 268 \| 💬: [48](https://news.ycombinator.com/item?id=43202982) \| 🗓️ 2025-02-28


<br />
鲍里斯·斯帕斯基，**第十任国际象棋世界冠军**，于2025年去世，享年88岁。他在18岁时成为**国际象棋特级大师**，并于1969年赢得世界冠军，直到1972年在著名的“世纪之战”中输给鲍比·菲舍尔。斯帕斯基与作者弗雷德里克·弗里德尔保持了数十年的友谊。

---

## <a name="9"></a>9. 关于Mozilla Firefox使用条款的更新 
<small>🔗 [blog.mozilla.org](https://blog.mozilla.org/en/products/firefox/update-on-terms-of-use/): An update on Mozilla's terms of use for Firefox</small>


| 🔥🔥: 255 \| 💬: [126](https://news.ycombinator.com/item?id=43213612) \| 🗓️ 2025-02-28


<br />
Mozilla于2025年2月28日宣布更新Firefox的使用条款和隐私声明，旨在更清晰地说明其与用户数据的互动。更新后的条款强调用户授予Mozilla必要的权利以操作Firefox，包括处理用户数据，但不意味着Mozilla拥有用户输入的内容。此外，Mozilla已删除了引起混淆的可接受使用政策的相关内容。关于隐私，Mozilla澄清其不以传统意义“出售”用户数据，并强调在某些地区法律对“销售”的定义较宽泛。Firefox通过内置的隐私和安全功能，确保用户数据的安全，并提供可调节的数据设置。

---

## <a name="10"></a>10. 继承的重要性日益上升，几乎与工作同等重要 
<small>🔗 [economist.com](https://www.economist.com/leaders/2025/02/27/inheriting-is-becoming-nearly-as-important-as-working): Inheriting is becoming nearly as important as working</small>


| 🔥🔥: 243 \| 💬: [319](https://news.ycombinator.com/item?id=43213143) \| 🗓️ 2025-02-28


<br />
在富裕国家，**继承财富**的影响力正在上升，这对**资本主义**和社会构成了威胁。过去，努力工作是成功的关键，但如今，越来越多的财富被传承给婴儿潮一代，改变了财富积累的游戏规则。这种趋势可能会导致社会的不平等加剧。

---

## <a name="11"></a>11. 通过iSCSI和iPXE网络启动Windows 11 
<small>🔗 [terinstock.com](https://terinstock.com/post/2025/02/Netboot-Windows-11-with-iSCSI-and-iPXE/): Netboot Windows 11 with iSCSI and iPXE</small>


| 🔥🔥: 173 \| 💬: [45](https://news.ycombinator.com/item?id=43204604) \| 🗓️ 2025-02-28


<br />
这篇文章探讨了如何在物理硬件上通过NAS导出磁盘来安装和启动Windows 11。作者主要使用Linux，但由于某些游戏仅支持Windows，决定将Windows安装转移到NAS上。使用**iPXE**和**iSCSI**，作者成功地从网络启动Windows 11，尽管遇到了一些驱动程序问题。通过创建包含网络驱动的**WinPE**映像，最终顺利安装Windows 11，并实现了良好的游戏体验。

---

## <a name="12"></a>12. 热议：GPT 4.5毫无实质意义 
<small>🔗 [garymarcus.substack.com](https://garymarcus.substack.com/p/hot-take-gpt-45-is-a-nothing-burger): Hot take: GPT 4.5 is a nothing burger</small>


| 🔥🔥: 165 \| 💬: [182](https://news.ycombinator.com/item?id=43203543) \| 🗓️ 2025-02-28


<br />
GPT 4.5被认为是一个**“毫无实质意义的产品”**，与之前的版本相比并没有显著改进。尽管投入了巨额资金，**纯粹的扩展**似乎已经遇到瓶颈，依然存在**幻觉和错误**。AI行业的乐观者们对其表现感到失望，甚至连OpenAI的CEO也未能如往常一样激动地谈论AGI。总的来看，GPT 4.5未能带来预期的突破，反映出当前AI发展的局限性。

---

## <a name="13"></a>13. 人工智能正在摧毁一些公司，而其他公司却在蓬勃发展——让我们看看数据 
<small>🔗 [elenaverna.com](https://www.elenaverna.com/p/ai-is-killing-some-companies-yet): AI is killing some companies, yet others are thriving – let's look at the data</small>


| 🔥🔥: 148 \| 💬: [146](https://news.ycombinator.com/item?id=43206491) \| 🗓️ 2025-02-28


<br />
人工智能正在改变主要内容网站的商业模式，像**WebMD**、**Quora**和**Chegg**等平台因AI搜索和聊天机器人而流失流量。用户不再需要点击页面，AI能迅速提供答案。尽管面临挑战，**Reddit**和**Wikipedia**等平台仍在增长，显示出用户对真实内容和社区的偏好。

---

## <a name="14"></a>14. 布赖恩·克雷布斯：这个政府完全被妥协 
<small>🔗 [infosec.exchange](https://infosec.exchange/@briankrebs/114083485241630234): Brian Krebs: This Administration Is Completely Compromised</small>


| 🔥🔥: 145 \| 💬: [35](https://news.ycombinator.com/item?id=43211506) \| 🗓️ 2025-02-28


<br />
布赖恩·克雷布斯在文章中指出，当前的**政府**已经完全被**妥协**，这对国家安全和公民自由构成了严重威胁。他强调，必须采取措施来恢复公众对政府的信任，并确保透明度和问责制，以防止未来的腐败和滥用权力。

---

## <a name="15"></a>15. 对Mozilla政策变更的评论 
<small>🔗 [waterfox.net](https://www.waterfox.net/blog/a-comment-on-mozilla-changes/): A Comment on Mozilla's Policy Changes</small>


| 🔥🔥: 136 \| 💬: [154](https://news.ycombinator.com/item?id=43204376) \| 🗓️ 2025-02-28


<br />
关于Mozilla最近的政策更新，社区反应不一，许多人对潜在的隐私影响表示担忧。Mozilla在公告中澄清，所需的许可证并不意味着对用户数据的所有权。此事件反映出Mozilla与用户之间的沟通不畅，缺乏必要的背景信息。相比之下，Waterfox在隐私政策上保持一致，强调透明度和用户控制。浏览器生态中存在不同的隐私策略，但缺乏正式治理结构的项目可能让用户面临风险。Waterfox通过明确的政策和法律框架，建立了用户信任，确保用户的隐私得到尊重。

---

## <a name="16"></a>16. Waterfox：快速且私密的网页浏览器 
<small>🔗 [waterfox.net](https://www.waterfox.net/): Waterfox: Fast and Private Web Browser</small>


| 🔥🔥: 130 \| 💬: [60](https://news.ycombinator.com/item?id=43205110) \| 🗓️ 2025-02-28


<br />
Waterfox 默认提供 **内置追踪保护**，并支持 **Oblivious DNS**，使您的在线活动更难被 ISP 跟踪。用户可以轻松使用 **私密标签**进行匿名浏览，而 **容器标签**则帮助组织不同类型的浏览。与其他浏览器不同，Waterfox 不会收集用户数据，确保您的隐私受到尊重。下载 Waterfox，享受安全的上网体验。

---

## <a name="17"></a>17. 为什么建造喷气发动机如此困难 
<small>🔗 [construction-physics.com](https://www.construction-physics.com/p/why-its-so-hard-to-build-a-jet-engine): Why it's so hard to build a jet engine</small>


| 🔥🔥: 128 \| 💬: [33](https://news.ycombinator.com/item?id=43212952) \| 🗓️ 2025-02-28


<br />
建造喷气发动机面临着**技术复杂性**和**经济压力**的双重挑战。为了实现高效能和低成本，工程师必须在材料、设计和制造工艺上不断创新。喷气发动机需要在极端条件下运行，要求其部件具备极高的强度和轻量化，这使得开发新发动机成为一项耗时且昂贵的任务。只有少数公司能够承担这样的技术挑战，且开发成本通常高达数十亿美元。

---

## <a name="18"></a>18. 住房理论的全能解答 
<small>🔗 [worksinprogress.co](https://worksinprogress.co/issue/the-housing-theory-of-everything/): The Housing Theory of Everything (2021)</small>


| 🔥🔥: 128 \| 💬: [95](https://news.ycombinator.com/item?id=43214263) \| 🗓️ 2025-02-28


<br />
当前西方世界面临许多问题，如**经济增长缓慢**、**气候变化**和**经济不平等**，而这些问题的根源在于住房短缺。住房价格高昂限制了人们的生活选择，影响了工作和家庭规模，导致生产力下降。解决住房问题不仅能改善生活质量，还能推动经济增长和创新，缩小社会不平等。

---

## <a name="19"></a>19. WebShield – Safari的全新广谱内容拦截器 
<small>🔗 [github.com](https://github.com/arjpar/WebShield): WebShield – A new wide-spectrum content blocker for Safari</small>


| 🔥🔥: 127 \| 💬: [66](https://news.ycombinator.com/item?id=43204406) \| 🗓️ 2025-02-28


<br />
WebShield是一款为Safari设计的高效内容拦截器，能够阻止广告、追踪器和Cookie通知。它支持自定义过滤列表，并利用Safari的内容拦截API。该项目目前处于测试阶段，依赖用户捐赠以维持独立性，确保无“可接受广告”政策。WebShield致力于为用户提供隐私保护和性能优化的浏览体验。

---

## <a name="20"></a>20. 梅尔狮：时间序列智能的机器学习框架 
<small>🔗 [github.com](https://github.com/salesforce/Merlion): Merlion: A Machine Learning Framework for Time Series Intelligence</small>


| 🔥🔥: 121 \| 💬: [19](https://news.ycombinator.com/item?id=43209064) \| 🗓️ 2025-02-28


<br />
梅尔狮是一个用于时间序列智能的**Python库**，提供了一个端到端的机器学习框架，支持**预测**、**异常检测**和变更点检测等多种任务。它的核心特点包括标准化的数据加载、丰富的模型库、自动化超参数调优和灵活的评估管道，旨在帮助工程师和研究人员快速开发和评估时间序列模型。通过可视化界面和分布式计算支持，梅尔狮能够高效处理工业规模的时间序列应用。

---

## <a name="21"></a>21. 自建 Firefox 同步服务器的指南 
<small>🔗 [blog.diego.dev](https://blog.diego.dev/posts/firefox-sync-server/): Self-Hosting a Firefox Sync Server</small>


| 🔥🔥: 118 \| 💬: [21](https://news.ycombinator.com/item?id=43214294) \| 🗓️ 2025-02-28


<br />
在从 Firefox 切换到 LibreWolf 后，作者决定自建一个 Firefox 同步服务器。经过一番探索，作者发现 Mozilla 的同步服务器仓库已不再维护，转而选择了基于 Rust 的 **syncstorage-rs**。尽管在使用 **Docker** 部署过程中遇到了一些文档混乱和配置挑战，最终通过社区提供的 **syncstorage-rs-docker** 解决方案成功搭建了服务器。设置过程中，作者强调了数据库持久性和存储空间的问题，并分享了自己的经验和建议，帮助其他用户避免类似的困难。

---

## <a name="22"></a>22. Starlink将接管24亿美元空中交通控制通信合同 
<small>🔗 [theverge.com](https://www.theverge.com/news/620777/starlink-verizon-contract-faa-communication-musk): Starlink to take over $2.4B contract to overhaul air traffic control comms</small>


| 🔥🔥: 115 \| 💬: [141](https://news.ycombinator.com/item?id=43205435) \| 🗓️ 2025-02-28


<br />
SpaceX旗下的Starlink可能会接管一项价值**24亿美元**的空中交通控制通信系统改造合同，该合同原本授予了Verizon。美国联邦航空局（FAA）的一支SpaceX团队正在推动这一变更，尽管此举引发了**偏袒**和**利益冲突**的指责。Elon Musk声称Verizon的系统存在严重问题，并表示Starlink将以“**零成本**”提供应急服务。FAA尚未正式决定如何处理这一合同变更，且内部官员对此表示反对。Musk的公司长期以来依赖政府合同和补贴，这一事件可能进一步加剧对其影响力的质疑。

---

## <a name="23"></a>23. 微软Skype将于5月5日正式关闭 
<small>🔗 [arstechnica.com](https://arstechnica.com/gadgets/2025/02/on-may-5-microsofts-skype-will-shut-down-for-good/): May 5, Microsoft's Skype will shut down for good</small>


| 🔥🔥: 108 \| 💬: [2](https://news.ycombinator.com/item?id=43205677) \| 🗓️ 2025-02-28


<br />
经过21年的发展，**Skype**将于2025年5月5日停止服务。微软确认，用户可通过Teams继续通话和聊天，且部分Skype用户将能使用Skype凭证登录Teams。现有的联系人和聊天记录将自动迁移，用户也可导出数据。Skype的付费用户将在关闭前继续享受服务，而Skype余额可通过Teams的网页界面使用。Skype的关闭标志着其在科技和通信历史中的重要一章的结束。

---

## <a name="24"></a>24. 美国政府终止所有结核病项目 
<small>🔗 [bsky.app](https://bsky.app/profile/johngreensbluesky.bsky.social/post/3lj6krxlhx22d): All Tuberculosis programs funded by the U.S. Gov were officially terminated</small>


| 🔥🔥: 102 \| 💬: [46](https://news.ycombinator.com/item?id=43203248) \| 🗓️ 2025-02-28


<br />
美国政府于昨晚正式终止了几乎所有的**结核病**（TB）项目，这一决定令人震惊。更令人担忧的是，这包括了全球药物设施（GDF），该机构负责协调全球大多数TB治疗和检测的采购。GDF的关闭将导致全球范围内的TB治疗中断，可能对公共健康造成严重影响。

---

## <a name="25"></a>25. AMD RDNA 4 – AMD Radeon RX 9000系列显卡发布 
<small>🔗 [amd.com](https://www.amd.com/en/newsroom/press-releases/2025-2-28-amd-unveils-next-generation-amd-rdna-4-architectu.html): AMD RDNA 4 – AMD Radeon RX 9000 Series Graphics Cards</small>


| 🔥🔥: 101 \| 💬: [178](https://news.ycombinator.com/item?id=43205196) \| 🗓️ 2025-02-28


<br />
AMD于2025年2月28日推出了新一代的**AMD RDNA™ 4架构**，并发布了**Radeon™ RX 9000系列显卡**，包括RX 9070 XT和RX 9070。这些显卡配备16GB内存，具备改进的光线追踪加速器和强大的AI加速器，旨在提供高质量的游戏体验。RX 9000系列显卡在1440p游戏中相比前代产品性能提升超过20%，并支持最新的显示技术，确保玩家在未来的游戏中也能享受卓越的性能和视觉效果。

---
