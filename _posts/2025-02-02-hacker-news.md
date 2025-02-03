---
layout: page
title: 勒西科技日报 - 2025年02月02日
date: 2025-02-02 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 你的位置无所遁形：通过应用内广告追踪自己的经历；
1. 生活不止是一个工程问题；
1. Waydroid——Linux 容器中的安卓系统；
1. Show HN: Lume - 专为Apple Silicon设计的轻量级macOS/Linux虚拟机CLI工具；
1. SanDisk High Endurance microSDXC 存储卡逆向工程与分析（2020）；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 你的位置无所遁形：通过应用内广告追踪自己的经历 
<small>🔗 [timsh.org](https://timsh.org/tracking-myself-down-through-in-app-ads/): Everyone knows your location: tracking myself down through in-app ads</small>


| 🔥🔥: 1129 \| 💬: [379](https://news.ycombinator.com/item?id=42909921) \| 🗓️ 2025-02-02


<br />
作者通过实验发现，**广告SDK（如Unity Ads）** 即使在关闭位置权限时仍会收集精确地理坐标、IP及设备信息，并通过实时竞价协议（OpenRTB）流向广告交易平台。数据经纪公司（如Redmob）以高价出售含**IDFA**等标识符的定位数据库，结合个人身份信息（PII）可精准追踪个体轨迹。欧盟用户数据最贵，而**用户选择“禁止追踪”仅屏蔽跨应用ID，无法阻止基础数据泄露**。

---

## <a name="2"></a>2. 生活不止是一个工程问题 
<small>🔗 [lareviewofbooks.org](https://lareviewofbooks.org/article/life-is-more-than-an-engineering-problem/): Life is more than an engineering problem</small>


| 🔥🔥: 338 \| 💬: [209](https://news.ycombinator.com/item?id=42907268) \| 🗓️ 2025-02-02


<br />
Ted Chiang 在与 Julien Crockett 的对话中探讨了人工智能、语言哲学与科技未来。他批判当前大型语言模型（**LLMs**）仅是“网络信息的模糊JPEG”，缺乏真实理解与推理能力，强调**人类主义**在技术变革中的核心地位。Chiang 认为，语言与数学无法完全替代人类复杂交流，而历史上对**完美语言**的追求本质是徒劳的。他通过科幻故事揭示哲学问题，主张科技应服务于人性，而非将其简化为工程难题。面对AI热潮，他呼吁警惕技术乌托邦叙事，重视现实中的伦理与情感维度。

---

## <a name="3"></a>3. Waydroid——Linux 容器中的安卓系统 
<small>🔗 [waydro.id](https://waydro.id/): Waydroid – Android in a Linux container</small>


| 🔥🔥: 272 \| 💬: [59](https://news.ycombinator.com/item?id=42911042) \| 🗓️ 2025-02-02


<br />
通过 **Linux 命名空间**技术，在基于 Wayland 的 GNU/Linux 桌面环境中运行完整安卓系统，实现**原生级性能**与硬件直通。支持多架构（ARM/x86）及主流 GPU，提供多窗口模式、全屏应用集成，并深度整合安卓应用至 Linux 程序目录。项目基于 LineageOS 定制安卓 11 镜像，开源社区驱动，含详细安装指南及定制化发行版（如 Ubuntu/Debian），需注意 NVIDIA GPU 需使用软件渲染。

---

## <a name="4"></a>4. Show HN: Lume - 专为Apple Silicon设计的轻量级macOS/Linux虚拟机CLI工具 
<small>🔗 [github.com](https://github.com/trycua/lume): Show HN: Lume – OS lightweight CLI for MacOS and Linux VMs on Apple Silicon</small>


| 🔥🔥: 261 \| 💬: [66](https://news.ycombinator.com/item?id=42908061) \| 🗓️ 2025-02-02


<br />
Lume 是一款基于 **Apple Virtualization.Framework** 的轻量级命令行工具，支持在Apple Silicon设备上快速创建、运行和管理macOS与Linux虚拟机。核心功能包括一键启动预构建镜像（如macOS Sonoma 15.2和Ubuntu 24.04）、动态调整CPU/内存/磁盘配置，以及通过本地API服务器实现自动化管理。通过 **ghcr.io/trycua** 提供优化镜像，支持SSH和共享目录，并采用MIT开源协议，支持Homebrew安装及社区贡献。

---

## <a name="5"></a>5. SanDisk High Endurance microSDXC 存储卡逆向工程与分析（2020） 
<small>🔗 [ripitapart.com](https://ripitapart.com/2020/07/16/reverse-engineering-and-analysis-of-sandisk-high-endurance-microsdxc-card/): Reverse-engineering and analysis of SanDisk High Endurance microSDXC card (2020)</small>


| 🔥🔥: 236 \| 💬: [103](https://news.ycombinator.com/item?id=42907766) \| 🗓️ 2025-02-02


<br />
作者通过逆向工程拆解 SanDisk 高耐久度存储卡，发现其采用 **3D TLC 闪存**，而 MAX Endurance 系列则通过 **pMLC 模式**提升耐用性。面对官方技术支持信息缺失，作者通过物理暴露测试点、自制转接板及逻辑分析仪追踪信号，最终解析出闪存 ID 并确认芯片规格。研究揭示了 SanDisk 对内部技术细节的严格保密，以及存储卡控制器与闪存总线间的复杂交互机制，为同类设备逆向工程提供了参考路径。

---

## <a name="6"></a>6. 深入解析高性能缓存库Caffeine的代码架构 
<small>🔗 [adriacabeza.github.io](https://adriacabeza.github.io/2024/07/12/caffeine-cache.html): Analyzing the codebase of Caffeine, a high performance caching library</small>


| 🔥🔥: 217 \| 💬: [41](https://news.ycombinator.com/item?id=42907488) \| 🗓️ 2025-02-02


<br />
本文探讨了Caffeine缓存库的核心机制，重点分析其**Window TinyLFU驱逐策略**：通过准入窗口筛选新条目，结合**频率草图（CountMinSketch）**估算访问频率，并采用分段LRU优化热点数据留存。同时，库内通过无哨兵节点的双链表队列和分层时间轮实现高效过期管理。这些设计以O(1)时间复杂度保障高命中率与低内存开销，支撑了Kafka、Cassandra等大型系统的缓存需求。

---

## <a name="7"></a>7. Sniffnet：网络流量监控工具 
<small>🔗 [github.com](https://github.com/GyulyVGC/sniffnet): Sniffnet – monitor your Internet traffic</small>


| 🔥🔥: 207 \| 💬: [78](https://news.ycombinator.com/item?id=42909530) \| 🗓️ 2025-02-02


<br />
一款**跨平台应用**，可直观监测互联网流量，支持实时流量图表、自定义通知及深度数据包分析。提供多语言界面，支持 Windows/macOS/Linux 系统，可通过 Homebrew、Cargo 等多种方式安装。内置**6000+协议识别**功能，支持 IP 地理定位、本地网络连接检测及 PCAP 报告导出。完全免费开源（Apache-2.0/MIT 双许可），需注意系统依赖项安装，并提供故障排查指南与用户手册。

---

## <a name="8"></a>8. 哥斯达黎加超市赢得与任天堂商标诉讼案 
<small>🔗 [ticotimes.net](https://ticotimes.net/2025/01/30/david-vs-goliath-costa-rican-super-mario-defeats-nintendo-in-court): Costa Rican supermarket wins trademark battle against Nintendo</small>


| 🔥🔥: 182 \| 💬: [61](https://news.ycombinator.com/item?id=42911842) \| 🗓️ 2025-02-02


<br />
哥斯达黎加圣拉蒙的**“Super Mario”超市**在商标注册纠纷中击败任天堂。店主申请注册**国际分类35类**（基础食品供应服务）时，任天堂以拥有“Super Mario”商标权为由上诉，但因其注册类别未涵盖食品供应，法院最终驳回诉求。律师指出任天堂虽注册45类商标，但未涉足**基本食品供应服务**。小企业主坚持维权，成功捍卫名称使用权，任天堂暂未回应。

---

## <a name="9"></a>9. 间隔重复法可实现无限记忆（2022年） 
<small>🔗 [efavdb.com](https://www.efavdb.com/memory%20recall): Spaced repetition can allow for infinite recall (2022)</small>


| 🔥🔥: 163 \| 💬: [166](https://news.ycombinator.com/item?id=42908041) \| 🗓️ 2025-02-02


<br />
通过**间隔重复**记忆法，新知识需高频复习巩固，但随着复习次数增加，保留时间呈**幂律增长**（T(s)∼s^γ）。研究表明，若按特定规则筛选记忆内容（N(t)∼t^{-[1/(γ+1)+ε]}），每日有限复习时间可覆盖无限增长的知识库。数学推导证明，当γ>0时，总记忆量随时间呈t^{γ/(γ+1)}增长，最终实现**无限记忆**。核心在于动态调整旧知识复习频率，确保系统可持续扩展。

---

## <a name="10"></a>10. 别拿著名作家丹·布朗开涮（2013） 
<small>🔗 [onehundredpages.wordpress.com](https://onehundredpages.wordpress.com/2013/06/12/dont-make-fun-of-renowned-dan-brown/): Don't make fun of renowned author Dan Brown (2013)</small>


| 🔥🔥: 150 \| 💬: [124](https://news.ycombinator.com/item?id=42912133) \| 🗓️ 2025-02-02


<br />
尽管新书《地狱》即将上市，**屡遭文评家嘲讽**的丹·布朗仍焦虑不已。批评者指其文风**重复累赘**、比喻荒诞，甚至调侃“鲨鱼般发白的眼睛”等句子。然而，经纪人提醒他：数百万读者与商业成功才是硬道理——从奥巴马到英国女王皆为其粉丝，梵高画作与莎士比亚珍本更彰显其财富。最终，布朗重拾信心，继续用“但丁密码”式配方书写畅销神话，并幻想受妻子启发转向浪漫诗歌。

---

## <a name="11"></a>11. 阿尔茨海默病科学中的谎言遗产 
<small>🔗 [nytimes.com](https://www.nytimes.com/2025/01/24/opinion/alzheimers-fraud-cure.html): The legacy of lies in Alzheimer's science</small>


| 🔥🔥: 146 \| 💬: [85](https://news.ycombinator.com/item?id=42910829) \| 🗓️ 2025-02-02


<br />
尽管癌症与心脏病治疗取得突破，**阿尔茨海默病死亡率却持续攀升**，全美近700万人受其折磨。数十年研究未产生有效疗法，除大脑复杂性外，**学术欺诈**成关键阻碍。知名神经科学家埃利泽·马斯利亚被曝长期篡改脑组织图像及蛋白质检测数据，其研究影响深远且获数十亿资金支持，凸显领域内**竞争压力与道德失范**。这一系统性造假严重误导疗法开发，加剧全球老龄化下的公共卫生危机。

---

## <a name="12"></a>12. Garmin数据库工具 
<small>🔗 [github.com](https://github.com/tcgoetz/GarminDB): GarminDB</small>


| 🔥🔥: 119 \| 💬: [17](https://news.ycombinator.com/item?id=42912515) \| 🗓️ 2025-02-02


<br />
开源Python工具可将**Garmin/FitBit/MS Health健康数据**自动下载解析至**SQLite数据库**，并通过**Jupyter Notebook**进行可视化分析。支持心率、运动记录、睡眠等多维度数据存储，提供命令行批量下载、增量更新及数据备份功能，内置统计视图与插件扩展机制，适配macOS并支持跨平台调试。需配置账户信息后通过`pip`安装或源码编译，含错误报告与社区贡献指南。

---

## <a name="13"></a>13. Shein/Temu利用免税漏洞向美国发货面临审查 
<small>🔗 [businessinsider.com](https://www.businessinsider.com/shein-temu-de-minimis-tax-loophole-scrutiny-2024-1): A loophole used by Shein/Temu to ship packages to US tax-free (2024)</small>


| 🔥🔥: 114 \| 💬: [88](https://news.ycombinator.com/item?id=42911511) \| 🗓️ 2025-02-02


<br />
美国**de minimis条款**允许价值低于800美元的进口包裹免税且免详细申报，快时尚平台Shein与Temu借此每日运送超百万包裹，引发监管质疑。反对者称该政策助长不公平竞争，且可能规避新疆棉禁令。美国国会提出两改革法案，但通过概率分别为30%与极低。两家企业表态支持**公平改革**，强调其低价源于供应链效率。传统零售商则面临"打不过就加入"的转型压力。

---

## <a name="14"></a>14. 修复文法中的左递归与相互递归问题 
<small>🔗 [brightprogrammer.in](https://brightprogrammer.in/posts/fixing-recursions-in-grammar/): Fixing left and mutual recursions in grammars</small>


| 🔥🔥: 102 \| 💬: [28](https://news.ycombinator.com/item?id=42907139) \| 🗓️ 2025-02-02


<br />
在上下文无关文法（CFG）中，**左递归**会导致自上而下解析算法陷入无限循环。例如，形如 `⟨S⟩ ::= ⟨S⟩ a | b` 的规则可通过转换为**右递归**解决：引入辅助符号 `⟨S’⟩` 改写为 `⟨S⟩ ::= b⟨S’⟩` 和 `⟨S’⟩ ::= a⟨S’⟩ | ε`。对于**相互递归**（如规则A→B、B→A），需重构语法树使其仅含右递归。作者以C++ demangler重构为例，展示了如何通过拆分规则、引入中间符号（如 `prefix_X`、`template_prefix_S2`）消除复杂递归，避免堆栈溢出。核心思路是将递归转移至右侧，确保解析器能有限步数内终止。

---

## <a name="15"></a>15. 马斯克“政府效率部”背后的年轻工程师：资历浅，权限大 
<small>🔗 [wired.com](https://www.wired.com/story/elon-musk-government-young-engineers/): The Young, Inexperienced Engineers Aiding Elon Musk’s Government Takeover</small>


| 🔥: 99 \| 💬: [46](https://news.ycombinator.com/item?id=42910910) \| 🗓️ 2025-02-02


<br />
**年轻且缺乏经验的工程师团队**（19-24岁）正协助马斯克通过“政府效率部”（DOGE）项目接管联邦机构，多数与马斯克或彼得·蒂尔有关联。他们已控制人事管理办公室（OPM）和总务署（GSA），并获准访问财政部支付系统，**可能获取数千万公民敏感数据**。部分成员被曝试图越权访问机密信息，引发专家对“私营势力操控政府”的质疑。  

团队成员包括SpaceX前实习生、Palantir关联者及OpenAI资助的创业者，**多人无政府工作经验却拥有高级安全权限**。学者警告此举或构成“全球首富对政府机器的敌意接管”，存在监管缺失与公共利益风险。

---

## <a name="16"></a>16. C++26 的 F-strings 提案 [PDF] 
<small>🔗 [open-std.org](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2024/p3412r0.pdf): F-strings for C++26 proposal [pdf]</small>


| 🔥: 98 \| 💬: [42](https://news.ycombinator.com/item?id=42912438) \| 🗓️ 2025-02-02


<br />
该提案主张为 C++26 引入**类似 Python 的格式化字符串语法**（f-strings），通过编译时解析实现类型安全的高效字符串插值。核心思路是允许在字符串字面量中**直接嵌入表达式**，并利用现有机制（如 `std::format`）进行类型校验与优化。争议点可能涉及语法冲突、编译器实现复杂度及与现有标准库的兼容性平衡。

---

## <a name="17"></a>17. 英国博彩巨头非法营销致赌徒深陷泥潭 
<small>🔗 [theguardian.com](https://www.theguardian.com/society/2025/feb/01/i-lost-10-years-of-my-life-how-uk-betting-giants-unlawful-marketing-kept-suicidal-gambler-hooked): UK betting giant's unlawful marketing kept suicidal gambler hooked</small>


| 🔥: 78 \| 💬: [70](https://news.ycombinator.com/item?id=42910983) \| 🗓️ 2025-02-02


<br />
英国高等法院裁定**Sky Bet**对一名有自杀倾向的成瘾赌徒实施非法定向营销。该赌徒（化名Sam）在2017-2019年间被标记为**“高价值客户”**，公司通过分析其2.4万份数据（包括消费习惯与游戏时间）发送1389封促销邮件，成功率高达98%。法官认定，Sam因赌博成瘾丧失自主决策能力，企业利用其脆弱心理进行数据追踪与精准推送的行为违法。尽管Sky Bet辩称已改进风控并考虑上诉，此案或引发行业对**数据滥用与成瘾营销**的全面审查。

---

## <a name="18"></a>18. 马斯克称狗狗币导致美财政部暂停向承包商付款 
<small>🔗 [fortune.com](https://fortune.com/2025/02/02/musk-doge-treasury-payments-system-halt-us-govenment-contractors-lutheran-charity/): Musk says DOGE is halting Treasury payments to US contractors</small>


| 🔥: 74 \| 💬: [44](https://news.ycombinator.com/item?id=42914425) \| 🗓️ 2025-02-02


<br />
埃隆·马斯克公开表示，**狗狗币（DOGE）**相关活动已迫使**美国财政部**暂停向国内承包商支付款项。该声明发表于其近期参与的就职活动期间，但未提供具体细节或证据。彭博社报道指出，此言论引发市场对加密货币政策影响的关注，但财政部尚未正式回应这一指控。

---

## <a name="19"></a>19. 强化学习：综述 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2412.05265): Reinforcement Learning: An Overview</small>


| 🔥: 73 \| 💬: [11](https://news.ycombinator.com/item?id=42910028) \| 🗓️ 2025-02-02


<br />
本文全面概述了（深度）强化学习与序列决策领域的最新进展，涵盖**基于价值的强化学习**、**策略梯度方法**、**基于模型的方法**等核心方向，并简要探讨了强化学习与大语言模型（LLMs）的结合。作者Kevin Murphy系统梳理了相关技术脉络与未来趋势。

---

## <a name="20"></a>20. ScatterBrain：揭秘PoisonPlug混淆器的隐匿威胁 
<small>🔗 [cloud.google.com](https://cloud.google.com/blog/topics/threat-intelligence/scatterbrain-unmasking-poisonplug-obfuscator): ScatterBrain: Unmasking the shadow of PoisonPlug's obfuscator</small>


| 🔥: 66 \| 💬: [7](https://news.ycombinator.com/item?id=42911162) \| 🗓️ 2025-02-02


<br />
Google威胁情报小组（GTIG）追踪到中国关联组织使用**POISONPLUG.SHADOW**（又名ShadowPad）模块化后门，结合**ScatterBrain混淆编译器**对欧洲及亚太目标发起攻击。该混淆器通过控制流混淆、指令变异及导入表保护机制，极大增加分析与检测难度，且持续演化升级。GTIG与FLARE团队合作开发独立反混淆工具，揭示其三种操作模式（选择性、完全及“无头”模式），并针对APT41关联攻击链提供深度解析，以应对这一国家级威胁。

---

## <a name="21"></a>21. Show HN: Modest —— Lua 的音乐和声库 
<small>🔗 [github.com](https://github.com/esbudylin/modest): Show HN: Modest – musical harmony library for Lua</small>


| 🔥: 65 \| 💬: [7](https://news.ycombinator.com/item?id=42907765) \| 🗓️ 2025-02-02


<br />
该库提供**和弦、音符与音程对象**的解析与操作，支持复杂和弦识别（含爵士和弦）、升降记号转换、音高推算及跨八度计算。通过 LPeg 实现灵活弦式解析，兼容 Unicode 符号与 ASCII 字符两种记谱方式，可生成乐理数字表示。采用 Fennel 编写，支持 Lua 5.4/LuaJIT，提供 LuaRocks 安装与手动编译方案，**强调不可变对象设计**。命名致敬作曲家穆索尔斯基，适用于音乐分析、自动伴奏等场景，功能对标 Python 的 Mingus 与 JS 的 Tonal 库。

---

## <a name="22"></a>22. Show HN: 土拨鼠AI春日API 
<small>🔗 [groundhog-day.com](https://groundhog-day.com/api): Show HN: Groundhog AI Spring API</small>


| 🔥: 51 \| 💬: [19](https://news.ycombinator.com/item?id=42910105) \| 🗓️ 2025-02-02


<br />
该API提供北美地区所有**气象预测动物**及其年度天气预测数据，支持通过三个**GET请求端点**获取全部/单个土拨鼠信息或指定年份预测结果。数据更新需通过官网提交，不开放API修改。包含OpenAPI架构，适用于构建**GaaP（土拨鼠即平台）**等企业级应用，为商业项目提供基础数据支持。

---

## <a name="23"></a>23. 马斯克获美财政部支付系统权限后承诺终止资助计划 
<small>🔗 [ft.com](https://www.ft.com/content/27ba0a6a-0d9b-4e08-8329-730b581c0481): Musk vows to cancel grants after gaining access to US Treasury payment system</small>


| 🔥: 51 \| 💬: [14](https://news.ycombinator.com/item?id=42910345) \| 🗓️ 2025-02-02


<br />
埃隆·马斯克在获得**美国财政部支付系统访问权限**后，宣布将取消现有资助项目。这一决定可能涉及对政府补贴或公共资金的调整，具体细节尚未披露。分析认为，此举或与其旗下企业（如SpaceX、特斯拉）的财务策略相关，但**资金来源变更**和**政策合规性**问题已引发外界关注。

---

## <a name="24"></a>24. 19岁DOGE员工“大球”获美财政部无限制访问权限 
<small>🔗 [bsky.app](https://bsky.app/profile/jsweetli.bsky.social/post/3lh5hr3hsc22k): 19 y/o DOGE employee "Big Balls" given unfettered access to Treasury Department</small>


| 🔥: 50 \| 💬: [3](https://news.ycombinator.com/item?id=42913801) \| 🗓️ 2025-02-02


<br />
一名自称**“大球”**的19岁DOGE雇员，此前履历仅为夏令营辅导员，其领英资料显示争议性昵称且已删除。报道质疑其**未经严格背景审查**即获取联邦支付系统权限，尤其亲属涉俄罗斯籍等敏感信息未被核查。事件暴露**系统权限管理漏洞**，引发公众对财政安全的担忧。

---

## <a name="25"></a>25. 为何AI生成内容读起来令人不适？ 
<small>🔗 [seangoedecke.com](https://www.seangoedecke.com/on-slop/): Why does AI slop feel so bad to read?</small>


| 🔥: 46 \| 💬: [27](https://news.ycombinator.com/item?id=42909042) \| 🗓️ 2025-02-02


<br />
当**AI垃圾内容**伪装成人类创作（如社交媒体推文）时，会触发**恐怖谷效应**——读者从“人际互动”模式被迫切换至“人机互动”，产生被欺骗感。这种不适源于AI内容的三大缺陷：内容中庸、套话冗余、缺乏作者人格一致性。相比之下，明确标注AI身份（如ChatGPT）或非深度阅读场景（如图像浏览）则无此困扰。解决前两点或许能改善体验，但人格化仍是核心难题。

---
