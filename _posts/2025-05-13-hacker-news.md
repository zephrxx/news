---
layout: page
title: 勒西科技日报 - 2025年05月13日
date: 2025-05-13 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 若优先优化软件，旧硬件也能满足全球需求；
1. GNU Screen 存在多个安全漏洞；
1. 分支特权注入：利用分支预测器竞态条件的新漏洞；
1. 高压职场中，人际关系优先；
1. Nextcloud控诉谷歌Play Store下架其应用涉嫌打压竞争；

以上是今天的前五条黑科技新闻标题。

总共24条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 若优先优化软件，旧硬件也能满足全球需求 
<small>🔗 [twitter.com](https://twitter.com/ID_AA_Carmack/status/1922100771392520710): The world could run on older hardware if software optimization was a priority</small>


| 🔥🔥: 527 \| 💬: [518](https://news.ycombinator.com/item?id=43971464) \| 🗓️ 2025-05-13


<br />
检测到浏览器**禁用JavaScript**，需启用或更换支持的浏览器才能继续使用x.com。隐私扩展可能导致问题，建议禁用后重试。文中强调**软件优化**可延长硬件生命周期，但当前生态更依赖硬件升级而非代码效率提升。底部包含帮助中心链接及公司版权信息。

---

## <a name="2"></a>2. GNU Screen 存在多个安全漏洞 
<small>🔗 [openwall.com](https://www.openwall.com/lists/oss-security/2025/05/12/1): Multiple security issues in GNU Screen</small>


| 🔥🔥: 324 \| 💬: [189](https://news.ycombinator.com/item?id=43971716) \| 🗓️ 2025-05-13


<br />
2025年5月12日，Matthias Gerstner披露了GNU Screen（终端复用工具）中的多个安全问题，主要影响**5.0.0版本**及**setuid-root安装配置**的系统。其中最严重的漏洞（CVE-2025-23395）允许本地用户通过`logfile_reopen()`函数以root权限任意创建或修改文件，可能导致**本地提权**。另一漏洞（CVE-2025-46802）在连接多用户会话时临时将终端权限改为全局可读写，存在**数据截获与注入风险**。受影响的系统包括Arch Linux、NetBSD及启用`multiuser`标志的Gentoo Linux。建议用户及时应用补丁或降级至4.9.1版本。

---

## <a name="3"></a>3. 分支特权注入：利用分支预测器竞态条件的新漏洞 
<small>🔗 [comsec.ethz.ch](https://comsec.ethz.ch/research/microarch/branch-privilege-injection/): Branch Privilege Injection: Exploiting branch predictor race conditions</small>


| 🔥🔥: 297 \| 💬: [109](https://news.ycombinator.com/item?id=43974891) \| 🗓️ 2025-05-13


<br />
苏黎世联邦理工学院研究人员发现**英特尔处理器**存在新型安全漏洞，该漏洞属于**分支预测器竞态条件（BPRC）**攻击类别。通过精心设计的指令序列，攻击者可利用处理器**推测执行技术**的时序漏洞，绕过权限检查，逐步读取其他用户的缓存和内存数据（速度超5000字节/秒）。所有2018年后的英特尔处理器（包括PC和服务器）均受影响，云环境多租户场景风险尤为突出。该漏洞反映了**推测执行架构**的根本性缺陷，英特尔已发布微码更新修复。

---

## <a name="4"></a>4. 高压职场中，人际关系优先 
<small>🔗 [wqtz.bearblog.dev](https://wqtz.bearblog.dev/high-stress-job-relationships/): In a high-stress work environment, prioritize relationships</small>


| 🔥🔥: 270 \| 💬: [173](https://news.ycombinator.com/item?id=43972535) \| 🗓️ 2025-05-13


<br />
在高压工作环境中，每个人都濒临崩溃，甚至幻想辞职。但**现实是职场关系至关重要**——离职后仍需推荐信，冲动言行会留下永久负面印象。**无论多忙，请以人为先**：将同事视为有情感需求的个体，而非任务工具。职业环境不应磨灭人性化沟通。

---

## <a name="5"></a>5. Nextcloud控诉谷歌Play Store下架其应用涉嫌打压竞争 
<small>🔗 [theregister.com](https://www.theregister.com/2025/05/13/nextcloud_play_store_complaint/): Nextcloud cries foul over Google Play Store app rejection</small>


| 🔥🔥: 243 \| 💬: [153](https://news.ycombinator.com/item?id=43970959) \| 🗓️ 2025-05-13


<br />
欧洲云服务商Nextcloud指责谷歌故意限制其Android文件同步应用功能，该应用拥有超82万用户。问题源于谷歌撤销了**"所有文件访问"权限**，导致应用无法正常运行。Nextcloud表示，谷歌推荐的替代方案**SAF框架**和**MediaStore API**无法满足需求，并质疑此举是变相排挤竞争对手。尽管多次申诉，谷歌仅回复政策条款。Nextcloud批评监管行动迟缓，称"大科技公司害怕小企业颠覆市场"。目前完整功能版仍可通过F-Droid获取。

---

## <a name="6"></a>6. 我为何辞去美国国家科学基金会职务 
<small>🔗 [time.com](https://time.com/7285045/resigning-national-science-foundation-library-congress/): Why I'm resigning from the National Science Foundation</small>


| 🔥🔥: 214 \| 💬: [243](https://news.ycombinator.com/item?id=43973210) \| 🗓️ 2025-05-13


<br />
作者因**白宫威胁宪政民主**、削减科研经费，以及**联邦机构诚信受损**而辞职。文中指出，国家科学基金会（NSF）和国会图书馆的咨询职能已被架空，**科学自由受政治干预**，例如未经审查否决拨款、解雇倡导多元化的官员。辞职是对**知识管控**和**体制空洞化**的抗议，强调顾问角色需真正影响决策，而非沦为形式。作者引用赫希曼的“退出与发声”理论，表明离开是为更自由地批判现状，坚守机构初心。

---

## <a name="7"></a>7. PDF文本提取：一个看似简单却极具挑战的技术难题 
<small>🔗 [marginalia.nu](https://www.marginalia.nu/log/a_119_pdf/): PDF to Text, a challenging problem</small>


| 🔥🔥: 204 \| 💬: [110](https://news.ycombinator.com/item?id=43973721) \| 🗓️ 2025-05-13


<br />
PDF本质是**图形格式**而非文本格式，其文字以**字形坐标映射**形式存储，导致提取时面临旋转、重叠、无序排列等难题。搜索引擎需要结构化HTML，但传统工具如PDFBox仅能提取原始文本，忽略**标题语义**等关键信息。改进方案通过统计每页字体大小（如正文中位值的120%识别标题）和行距分布优化段落划分，虽非完美但显著提升处理效果。学术论文等复杂排版仍存在多行标题合并等未解难题，但已能满足搜索引擎对核心内容抓取的需求。

---

## <a name="8"></a>8. 2025年了，银行为何还在用落后的身份验证？ 
<small>🔗 [jamal.haba.sh](https://jamal.haba.sh/its-2025-why-are-banks-still-getting-authentication-so-wrong/): Why are banks still getting authentication so wrong?</small>


| 🔥🔥: 199 \| 💬: [260](https://news.ycombinator.com/item?id=43976359) \| 🗓️ 2025-05-13


<br />
作者因国际旅行时无法接收加拿大短信，被TD银行**SMS双因素认证（2FA）**系统锁死账户，即便安装了专用验证应用仍陷入死循环。文章批评银行依赖**不安全的短信验证**（易受SIM卡劫持和钓鱼攻击），却拒绝支持**TOTP标准**或通行密钥（Passkeys）等现代方案。安全性与用户体验本可兼顾，但银行固守陈旧技术，甚至三年后仍未改进。关键问题在于：**安全设计应以用户为中心**，而非制造障碍。

---

## <a name="9"></a>9. 奥丁：为我量身打造的高效编程语言 
<small>🔗 [zylinski.se](https://zylinski.se/posts/a-programming-language-for-me/): Odin: A programming language made for me</small>


| 🔥🔥: 162 \| 💬: [175](https://news.ycombinator.com/item?id=43970800) \| 🗓️ 2025-05-13


<br />
作者Karl Zylinski分享了他对**奥丁语言**的喜爱，认为它完美融合了C语言的高效实践与现代特性。文中重点介绍了**自定义分配器**（如临时分配器、追踪分配器）、**零值初始化**（ZII）和**缓存友好编程**（如#soa数组布局）等核心设计，这些特性直接内置于语言基础库，简化了内存管理并提升性能。奥丁保持了C的简洁性，同时引入泛型等现代功能，适合游戏开发等场景。作者强调，奥丁的易用性源于其与自身C编程经验的契合，但也推荐新手通过他的书籍系统学习。

---

## <a name="10"></a>10. 暮光操作系统：为文明崩溃设计的极简计算系统 
<small>🔗 [duskos.org](https://duskos.org/): Dusk OS</small>


| 🔥🔥: 156 \| 💬: [97](https://news.ycombinator.com/item?id=43976862) \| 🗓️ 2025-05-13


<br />
**暮光操作系统（Dusk OS）** 是一款32位Forth系统，专为**文明崩溃初期**设计，目标是在无法生产现代计算机时仍能利用现有设备。其核心设计理念是**极简主义**，通过牺牲传统约束实现高“功率密度”，并内置**类C编译器**以复用UNIX代码。支持多种硬件架构（如i386、ARM、RISC-V），仅需6000行代码即可实现自举，包含编辑器、汇编器等工具。系统强调**操作者控制权**，无并发设计允许直接硬件操控，挑战现代软件堆栈的复杂性。

---

## <a name="11"></a>11. 谷歌秘密开发安卓桌面模式，挑战三星DeX 
<small>🔗 [androidauthority.com](https://www.androidauthority.com/android-desktop-mode-leak-3550321/): Google is building its own DeX: First look at Android's Desktop Mode</small>


| 🔥🔥: 154 \| 💬: [143](https://news.ycombinator.com/item?id=43973395) \| 🗓️ 2025-05-13


<br />
谷歌正在测试名为**“Desktop View”**的新功能，可将安卓手机连接外接显示器后切换为PC界面，支持**任务栏**、**可调整窗口**及**拖拽多任务**操作。目前该功能仍隐藏在开发者选项中，但进展迅速，未来可能让所有安卓设备具备类似三星DeX的桌面体验。此举旨在打破三星在移动桌面领域的垄断，推动安卓向全功能操作系统进化。

---

## <a name="12"></a>12. 微软将裁员3%以优化管理层结构 
<small>🔗 [cnbc.com](https://www.cnbc.com/2025/05/13/microsoft-is-cutting-3percent-of-workers-across-the-software-company.html): Microsoft is Cutting 3% of All Workers</small>


| 🔥🔥: 113 \| 💬: [23](https://news.ycombinator.com/item?id=43973399) \| 🗓️ 2025-05-13


<br />
微软宣布将在全球范围内裁员**3%**，涉及所有层级和地区。截至去年6月，该公司拥有22.8万名员工，此次裁员将影响数千人。此举旨在**减少管理层级**，以适应市场变化。尽管微软近期财报表现强劲（季度净利润258亿美元），但这是继2023年裁员1万人后的又一次大规模调整。发言人强调，此次裁员与绩效无关，而是**组织优化**的一部分。同时，微软Azure云业务因AI驱动增长超预期，股价近期创下年内新高。

---

## <a name="13"></a>13. 实验在等待：当诗歌与科学碰撞的奇迹 
<small>🔗 [rifters.com](https://www.rifters.com/crawl/?p=11511): It Awaits Your Experiments</small>


| 🔥🔥: 112 \| 💬: [34](https://news.ycombinator.com/item?id=43974005) \| 🗓️ 2025-05-13


<br />
这篇文章讲述了诗人**Christian Bök**历时二十余年的**《异种文本实验》**，将诗歌编码进**耐辐射奇球菌**（Deinococcus radiodurans）的DNA中。这种微生物堪称“细菌界的终结者”，能在极端环境中存活，甚至可能比人类文明更长久。Bök的诗歌不仅是一段文字，还与生成的蛋白质形成“奥菲斯与欧律狄刻”般的对话，并发出荧光。尽管科学界曾质疑其可行性，Bök最终在2025年成功，让艺术驱动了科学。这部作品不仅是诗歌，更是**跨越时空的生命艺术**，或将成为人类留给外星文明的遗产。

---

## <a name="14"></a>14. 反人类计算（2023） 
<small>🔗 [erratique.ch](https://erratique.ch/writings/anti-personnel-computing): Anti-Personnel Computing (2023)</small>


| 🔥🔥: 111 \| 💬: [50](https://news.ycombinator.com/item?id=43970637) \| 🗓️ 2025-05-13


<br />
该文提出新词“**反人类计算**”，指21世纪初主流计算设备**牺牲用户利益**、为第三方谋利的现象。相关术语“**反人类计算机**”指主要服务于第三方而非用户的设备。词源结合了“反人员地雷”与“个人计算/电脑”，尖锐揭示科技异化问题。核心矛盾在于**设备所有权与受益权分离**，用户沦为数据剥削对象。

---

## <a name="15"></a>15. 美国漏洞追踪体系失灵，欧盟推出自主安全漏洞数据库 
<small>🔗 [theregister.com](https://www.theregister.com/2025/05/13/eu_security_bug_database/): As US vuln-tracking falters, EU enters with its own security bug database</small>


| 🔥🔥: 106 \| 💬: [39](https://news.ycombinator.com/item?id=43972438) \| 🗓️ 2025-05-13


<br />
欧盟漏洞数据库（**EUVD**）正式上线，提供实时监控**关键漏洞**和**活跃攻击漏洞**的平台，以应对美国CVE项目因预算削减、披露延迟等问题导致的混乱。该数据库由欧盟网络安全局（**ENISA**）开发，整合多方数据源，界面简洁高效。与此同时，美国CISA削减网络安全预算并停止公开漏洞警报，引发行业担忧。EUVD的推出标志着全球漏洞追踪体系的分化趋势。

---

## <a name="16"></a>16. 共和党将十年AI监管禁令塞入预算法案 
<small>🔗 [arstechnica.com](https://arstechnica.com/ai/2025/05/gop-sneaks-decade-long-ai-regulation-ban-into-spending-bill/): GOP sneaks decade-long AI regulation ban into spending bill</small>


| 🔥: 100 \| 💬: [105](https://news.ycombinator.com/item?id=43975254) \| 🗓️ 2025-05-13


<br />
美国众议院共和党人近日在预算法案中新增条款，**禁止各州及地方政府在未来10年内监管人工智能**。该提案由肯塔基州众议员Brett Guthrie提出，措辞宽泛，可能导致加州、纽约等地现有及拟议的AI保护法规失效，例如医疗AI披露义务和招聘算法偏见审计。法案还限制各州分配联邦AI资金的方式，削弱地方与白宫技术政策的差异。批评者称此举是**"给科技巨头的礼物"**，将放任深度伪造和算法偏见等风险。特朗普政府与AI行业关系密切，多名科技高管担任顾问，进一步推动去监管化。

---

## <a name="17"></a>17. HelixDB：专为AI应用打造的开源图向量数据库（Rust） 
<small>🔗 [github.com](https://github.com/HelixDB/helix-db/): Show HN: HelixDB – Open-source vector-graph database for AI applications (Rust)</small>


| 🔥: 97 \| 💬: [49](https://news.ycombinator.com/item?id=43975423) \| 🗓️ 2025-05-13


<br />
HelixDB是一款基于**Rust**开发的高性能**图向量数据库**，专为**RAG（检索增强生成）**和AI应用设计。它结合了图数据库的关系处理能力与向量数据库的相似性搜索功能，并采用LMDB作为存储引擎，确保**ACID兼容**与高效持久化。性能表现卓越（比Neo4j快1000倍，与Qdrant向量搜索相当），提供CLI工具和多种语言SDK（如TypeScript/Python），支持快速部署查询。开源协议为AGPL-3.0，同时提供商业托管服务。

---

## <a name="18"></a>18. OpenAI"星际之门"项目因关税问题陷入停滞 
<small>🔗 [techcrunch.com](https://techcrunch.com/2025/05/12/openais-stargate-project-reportedly-struggling-to-get-off-the-ground-thanks-to-tariffs/): OpenAI's Stargate project struggling to get off the ground, due to tariffs</small>


| 🔥: 91 \| 💬: [160](https://news.ycombinator.com/item?id=43974268) \| 🗓️ 2025-05-13


<br />
OpenAI耗资5亿美元的**"星际之门"**数据中心项目因关税导致的经济不确定性而进展受阻。据彭博社报道，市场波动加剧及AI服务成本下降使银行、私募投资者态度谨慎，主要支持方软银尚未启动详细融资讨论。分析指出，**关税可能使建设成本增加5%-15%**，加之微软等科技巨头收缩数据中心投资，加剧了投资者对产能过剩的担忧。

---

## <a name="19"></a>19. 太空数据中心Starcloud：用轨道算力训练下一代AI 
<small>🔗 [ycombinator.com](https://www.ycombinator.com/companies/starcloud): Starcloud</small>


| 🔥: 88 \| 💬: [154](https://news.ycombinator.com/item?id=43977188) \| 🗓️ 2025-05-13


<br />
Starcloud（前身为Lumen Orbit）计划在太空部署**兆瓦级数据中心网络**，未来可扩展至千兆瓦规模，旨在利用**太空太阳能**和**被动冷却**优势，解决地球算力扩张对能源与环境的压力。其首颗演示卫星将于2025年7月发射，搭载比现有太空GPU强**100倍**的算力，并与英伟达合作。团队由航天与AI专家组成，已获千万美元融资，目标为GPT6等大模型提供可持续的轨道训练环境。

---

## <a name="20"></a>20. AI就像个不靠谱的顾问 
<small>🔗 [lukekanies.com](https://lukekanies.com/writing/ai-is-like-a-crappy-consultant/): AI Is Like a Crappy Consultant</small>


| 🔥: 86 \| 💬: [98](https://news.ycombinator.com/item?id=43972088) \| 🗓️ 2025-05-13


<br />
作者通过尝试用AI辅助Swift编程发现，**AI适合处理基础工作**（如快速定位语法错误），但无法胜任架构设计等复杂任务。它常给出**糟糕的解决方案**（如盲目捕获错误而非重构），且缺乏真正的思考能力。关键在于**严格控制AI的参与度**——像带实习生一样，只委托机械性工作并严格审查输出。最终结论：AI是高效的工具，但绝不能替代人类决策。

---

## <a name="21"></a>21. 别再用unwrap处理Option了：这里有更好的方法（2024） 
<small>🔗 [corrode.dev](https://corrode.dev/blog/rust-option-handling-best-practices/): Don't unwrap options: There are better ways (2024)</small>


| 🔥: 82 \| 💬: [48](https://news.ycombinator.com/item?id=43975785) \| 🗓️ 2025-05-13


<br />
本文探讨了Rust中处理`Option`类型时避免使用`unwrap()`的更好实践。当函数返回`Result`时，直接对`Option`使用`?`运算符会报错，常见解法包括：**`ok_or`转换**、**`match`匹配**和**`let-else`语法**。其中，**`let-else`**因其简洁性和可读性成为首选方案，能清晰区分正常流程与错误处理。作者强调生产代码中应避免滥用`unwrap`，推荐使用标准库方案提升代码健壮性。

---

## <a name="22"></a>22. 高效生活的101条法则 
<small>🔗 [mitchhorowitz.substack.com](https://mitchhorowitz.substack.com/p/101-rules-of-effective-living): One hundred and one rules of effective living</small>


| 🔥: 81 \| 💬: [76](https://news.ycombinator.com/item?id=43971791) \| 🗓️ 2025-05-13


<br />
作者Mitch Horowitz基于三十年的经验，总结了**诚实守信、专注执行、人际智慧**三大核心原则。包括：准时完成工作、直面失败、减少抱怨、远离恶人、重视实践而非空谈、尊重他人、保持好奇心等。强调**道德自省**（如"道德评判他人，伦理约束自我"）和**危机意识**（"自然灾难时，生存是唯一法则"）。最后提醒：过度关注厌恶你的人，只会放大自我投射的不安。

---

## <a name="23"></a>23. 全球等面积毫米级地理空间索引系统A5 
<small>🔗 [github.com](https://github.com/felixpalmer/a5): Show HN: A5</small>


| 🔥: 79 \| 💬: [26](https://news.ycombinator.com/item?id=43971314) \| 🗓️ 2025-05-13


<br />
A5是一种基于**五边形网格**的全球地理空间索引系统（DGGS），提供32级分辨率，最大单元覆盖全球，最小单元面积小于30mm²且**等面积误差控制在2%以内**。该系统可将空间数据转换为网格集合，便于分析（如海拔与作物产量相关性）或点数据聚合（如城市民宿分布密度）。A5采用**十二面体五边形镶嵌**技术，相比其他DGGS（如H3的六边形），能最小化投影变形。开源库基于TypeScript，Apache-2.0许可。

---

## <a name="24"></a>24. 美国如何放弃科学霸主地位 
<small>🔗 [steveblank.com](https://steveblank.com/2025/05/13/how-the-united-states-became-a-science-superpower-and-how-quickly-it-could-crumble/): How the United States Gave Up Being a Science Superpower</small>


| 🔥: 73 \| 💬: [34](https://news.ycombinator.com/item?id=43972493) \| 🗓️ 2025-05-13


<br />
本文探讨了美国科学领导力的衰落根源。**二战后**，美国通过政府、高校与企业的独特合作模式成为科学超级大国，**联邦资助**推动基础研究并催生硅谷等产业。然而，特朗普政府大幅削减科研预算（如将高校间接成本报销从50%砍至15%），并针对气候、多样性等领域，动摇了这一创新生态的核心。**间接成本体系**本是维持实验室运转的关键，如今被政治短视破坏，威胁到每年1100家科技初创的诞生。作者警告，美国正重蹈英国战后科学衰落的覆辙。

---
