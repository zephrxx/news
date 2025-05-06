---
layout: page
title: 勒西科技日报 - 2025年05月05日
date: 2025-05-05 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 白日梦的消亡：智能手机如何扼杀我们的无聊与创造力；
1. Daft Punk的声码效果解析；
1. 法官裁定Meta非法使用书籍构建AI模型；
1. 作为资深LLM用户，我为何不常使用生成式大模型；
1. 将文件系统变为向量数据库：VectorVFS轻量级工具；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 白日梦的消亡：智能手机如何扼杀我们的无聊与创造力 
<small>🔗 [afterbabel.com](https://www.afterbabel.com/p/on-the-death-of-daydreaming): The Death of Daydreaming</small>


| 🔥🔥: 518 \| 💬: [207](https://news.ycombinator.com/item?id=43894305) \| 🗓️ 2025-05-05


<br />
本文探讨了智能手机如何剥夺人类**无聊间隙**的价值，导致**白日梦**和创造力的衰退。作者指出，过去人们通过发呆、闲聊或观察周围来填充碎片时间，这些时刻孕育了反思与灵感。如今，手机以即时刺激填满所有空白，削弱了我们的耐心、同理心和情感调节能力。研究显示，过度依赖屏幕不仅加剧社交孤立，还让各年龄段陷入**注意力碎片化**的困境。文章呼吁重新珍视“闲置时间”，认为它是保持人性与民主社会健康的关键。

---

## <a name="2"></a>2. Daft Punk的声码效果解析 
<small>🔗 [bjango.com](https://bjango.com/articles/daftpunkvocaleffects/): The vocal effects of Daft Punk</small>


| 🔥🔥: 347 \| 💬: [76](https://news.ycombinator.com/item?id=43893601) \| 🗓️ 2025-05-05


<br />
Daft Punk在其作品中广泛运用了**声码器**、**Talk Box**和**和声处理器**三种技术。他们使用过Roland SVC-350、Auto-Tune和DigiTech Vocalist等设备，并在《Random Access Memories》中租用了稀有的Sennheiser VSM201声码器。**Talk Box**通过管道将声音传入嘴部塑造效果，而**声码器**则通过合成器与声音的频段混合实现机器人声效。和声处理器（如Auto-Tune）则直接改变音高，创造出《One More Time》等经典效果。文章还探讨了不同设备的音色差异及历史背景。

---

## <a name="3"></a>3. 法官裁定Meta非法使用书籍构建AI模型 
<small>🔗 [wired.com](https://www.wired.com/story/meta-lawsuit-copyright-hearing-artificial-intelligence/): Judge said Meta illegally used books to build its AI</small>


| 🔥🔥: 332 \| 💬: [294](https://news.ycombinator.com/item?id=43893762) \| 🗓️ 2025-05-05


<br />
Meta与包括Sarah Silverman、Ta-Nehisi Coates在内的作家团体陷入版权纠纷，争议焦点在于其AI工具是否生成**蚕食原作销量**的内容。法官Vince Chhabria质疑Meta以**合理使用**为由未经授权使用书籍（通过LibGen等影子图书馆获取）的合法性，强调若AI作品**摧毁原作市场**则难称合理。双方就是否影响作家收入激烈辩论，但法官对原告能否举证MetaAI导致经济损失表示怀疑。此案结果或为生成式AI版权争议树立重要先例，影响硅谷战略。

---

## <a name="4"></a>4. 作为资深LLM用户，我为何不常使用生成式大模型 
<small>🔗 [minimaxir.com](https://minimaxir.com/2025/05/llm-use/): As an experienced LLM user, I don't use generative LLMs often</small>


| 🔥🔥: 245 \| 💬: [142](https://news.ycombinator.com/item?id=43897320) \| 🗓️ 2025-05-05


<br />
作者作为BuzzFeed高级数据科学家，拥有十年文本生成工具开发经验，却**罕见地少用生成式LLM**。他通过**API直接调用**（如Claude Sonnet）而非普通前端，利用**系统提示词**和低温参数（temperature=0.0）提升输出精准度。工作中用LLM快速解决文章分类、语义聚类标签生成等任务，但强调需人工验证**幻觉问题**；编码时仅辅助处理正则表达式等特定场景，避免复杂逻辑依赖。个人写作则拒绝代笔，仅用LLM模拟Hacker News评论来优化论点。

---

## <a name="5"></a>5. 将文件系统变为向量数据库：VectorVFS轻量级工具 
<small>🔗 [vectorvfs.readthedocs.io](https://vectorvfs.readthedocs.io/en/latest/): Show HN: VectorVFS, your filesystem as a vector database</small>


| 🔥🔥: 197 \| 💬: [95](https://news.ycombinator.com/item?id=43896011) \| 🗓️ 2025-05-05


<br />
VectorVFS是一款**Python工具包**，通过Linux的**虚拟文件系统（VFS）扩展属性**，将本地文件系统直接转化为**向量数据库**。它无需额外索引或外部数据库，而是将向量嵌入数据存储在文件的原生属性中，支持基于语义的高效搜索。当前版本集成Meta的Perception Encoders（PE），在零样本图像任务中表现优异，支持CPU/GPU计算，但首次处理大量图像时可能耗时较长。其核心优势包括零开销索引、无缝检索和轻量化设计，完全依赖Linux原生功能，无需后台服务。目前仅支持PE模型和图像类型，未来将扩展更多数据类型。

---

## <a name="6"></a>6. 特朗普宣布对"外国制作"电影征收100%关税 
<small>🔗 [theguardian.com](https://www.theguardian.com/us-news/2025/may/04/trump-tariffs-foreign-movies): Trump announces 100% tariffs on movies ‘produced in foreign lands’</small>


| 🔥🔥: 196 \| 💬: [440](https://news.ycombinator.com/item?id=43893310) \| 🗓️ 2025-05-05


<br />
美国前总统特朗普在社交媒体Truth Social上宣布，将对所有**"外国制作"电影**征收100%关税，称此举旨在保护**美国电影产业**，并指责其他国家通过税收优惠吸引美国制片方，构成**"国家安全威胁"**。美国商务部长回应已着手实施，但未透露细节。澳大利亚和新西兰政府表示将捍卫本国影视业利益。此前，特朗普的关税政策已引发中美贸易摩擦，中国减少了美国电影进口配额。专家警告，此举可能引发报复性措施，重创美国电影行业。

---

## <a name="7"></a>7. AWS安全工具反成漏洞源头：跨账户权限升级风险曝光 
<small>🔗 [token.security](https://www.token.security/blog/aws-built-a-security-tool-it-introduced-a-security-risk): AWS Built a Security Tool. It Introduced a Security Risk</small>


| 🔥🔥: 180 \| 💬: [72](https://news.ycombinator.com/item?id=43893906) \| 🗓️ 2025-05-05


<br />
AWS推出的**Account Assessment for AWS Organizations**工具本用于审计跨账户访问策略，却因部署指南缺陷导致严重安全隐患。官方文档错误建议将核心**hub角色**部署在非管理账户（如开发环境），使得低安全账户能通过信任链获取高敏感账户权限。攻击者一旦入侵开发账户，可借此横向移动至生产和管理账户，列举IAM角色、S3存储桶等关键资源。AWS于2025年1月28日更新文档，明确要求将hub角色部署在与管理账户同等级的安全环境中。已部署该工具的企业需检查角色创建时间，若早于修复日期应立即卸载并重新配置。

---

## <a name="8"></a>8. 2024年拥有Pi-Hole的妙处 
<small>🔗 [den.dev](https://den.dev/blog/pihole/): The Beauty of Having a Pi-Hole (2024)</small>


| 🔥🔥: 165 \| 💬: [125](https://news.ycombinator.com/item?id=43894175) \| 🗓️ 2025-05-05


<br />
在当今网络环境中，广告、追踪脚本和恶意域名泛滥成灾，**Pi-Hole**作为一款开源DNS过滤工具，能有效拦截这类请求。它通过**Raspberry Pi**硬件运行，充当家庭网络的DNS代理，默认屏蔽广告、分析服务和恶意域名。作者实测其拦截了66.6%的无用流量，且不影响正常使用。  

设置只需基础硬件（如树莓派套件）和简单配置，配合社区维护的**域名黑名单**（如Firebog）可进一步提升效果。进阶用户还能通过正则表达式屏蔽特定国家顶级域（如.cn/.ru）。此外，文中分享了强制设备使用Pi-Hole的iptables技巧，并建议搭配浏览器插件（如uBlock Origin）实现多层防护。  

最终结论：Pi-Hole显著提升网络体验，是隐私保护的必备工具。

---

## <a name="9"></a>9. 实时AI语音聊天：延迟仅500毫秒的自然对话工具 
<small>🔗 [github.com](https://github.com/KoljaB/RealtimeVoiceChat): Show HN: Real-time AI Voice Chat at ~500ms Latency</small>


| 🔥🔥: 162 \| 💬: [86](https://news.ycombinator.com/item?id=43899028) \| 🗓️ 2025-05-05


<br />
该项目通过**浏览器麦克风**捕捉用户语音，利用WebSocket实时传输至Python后端，经**Whisper模型**快速转文本后，由Ollama或OpenAI等**大语言模型**生成响应，再通过TTS引擎转换为语音回传。支持打断交互、多语音选项，并提供Docker一键部署。核心优势在于低延迟架构设计，需NVIDIA GPU保障性能，适合开发者快速搭建AI语音对话系统。

---

## <a name="10"></a>10. 2025年网络犯罪分子的敛财新招 
<small>🔗 [vin01.github.io](https://vin01.github.io/piptagole/cybcecrime/security/cybersecurity/2025/05/05/state-cyber-security.html): How are cyber criminals rolling in 2025?</small>


| 🔥🔥: 161 \| 💬: [60](https://news.ycombinator.com/item?id=43896188) \| 🗓️ 2025-05-05


<br />
网络犯罪分子正利用**政府机构**、**高校**等组织的薄弱网络安全防线，将其作为免费内容托管平台。他们通过SEO优化和**可信域名**（如Google服务）绕过企业安全工具检测，散布虚假链接。攻击手段包括过时的WordPress插件、缓存投毒和子域名劫持，最终通过多层跳转链接牟利或实施钓鱼（如针对儿童的游戏货币“**Robux**”诈骗）。尽管部分漏洞已修复，但攻击者仍持续进化，传统防御措施难以应对。

---

## <a name="11"></a>11. 冷战情报中的“潜伏狡辩”陷阱 
<small>🔗 [kucharski.substack.com](https://kucharski.substack.com/p/possibly-a-serious-possibility): Possibly a Serious Possibility</small>


| 🔥🔥: 144 \| 💬: [58](https://news.ycombinator.com/item?id=43898380) \| 🗓️ 2025-05-05


<br />
1951年，CIA分析师Sherman Kent发现术语**“严重可能性”**在评估苏联入侵南斯拉夫风险时引发混乱——同事对其概率的理解从20%到80%不等。这暴露了情报界长期存在的**语言模糊性**问题：专业术语（如“可能”“很可能”）缺乏统一量化标准，导致决策误判。Kent将情报分为事实、可推断与不可推断三类，指出后两类因不确定性易滋生**“潜伏狡辩”**（如法律中的“非随意怀疑”），即用权威措辞推卸责任。近年英国等尝试用概率标尺（如“极可能”=80%-95%）规范表述，但人类对不确定性的沟通仍面临挑战。

---

## <a name="12"></a>12. 自托管赛事管理系统Bracket：支持多赛制的开源解决方案 
<small>🔗 [github.com](https://github.com/evroon/bracket): Show HN: Bracket – selfhosted tournament system</small>


| 🔥🔥: 120 \| 💬: [26](https://news.ycombinator.com/item?id=43895456) \| 🗓️ 2025-05-05


<br />
Bracket是一个基于**FastAPI**（异步Python）和**Next.js**构建的自托管赛事管理平台，支持单淘汰、循环赛和瑞士制等多种赛制。核心功能包括多阶段赛事编排、拖拽调整赛程、多俱乐部管理及动态瑞士制匹配。提供30分钟在线演示，支持Docker快速部署（含PostgreSQL），默认账号为test@example.org/aeGhoe1ahng2Aezai0Dei6Aih6dieHoo。采用**AGPL-3.0协议**开源，已获378星标，支持通过Crowdin贡献多语言翻译。

---

## <a name="13"></a>13. 没有Instagram，就没有隐私 
<small>🔗 [blog.wouterjanleys.com](https://blog.wouterjanleys.com/blog/no-instagram-no-privacy/): No Instagram, no privacy</small>


| 🔥🔥: 111 \| 💬: [97](https://news.ycombinator.com/item?id=43896228) \| 🗓️ 2025-05-05


<br />
作者庆幸自己没有Instagram账号，避免了社交媒体的压力，但发现**他人通过朋友发布的动态**仍能了解自己的私生活。这种**信息失控**让他感到不安，尤其是无法掌控他人如何解读这些内容。虽然现实社交中人们会注意言辞，但社交媒体的公开性让这种**细腻沟通**消失。他提出可能需要建立新的社交礼仪，限制聚会内容的分享范围，但承认这与社交媒体本质相悖。最后，他选择继续享受无知带来的平静，希望未被邀请的朋友能理解并保持关系。

---

## <a name="14"></a>14. 用SQL轻松查询CSV/JSON/Excel数据的本地工具 
<small>🔗 [textquery.app](https://textquery.app/): Show HN: TextQuery – Query CSV, JSON, XLSX Files with SQL</small>


| 🔥🔥: 107 \| 💬: [40](https://news.ycombinator.com/item?id=43897129) \| 🗓️ 2025-05-05


<br />
TextQuery是一款**桌面应用**，支持通过SQL直接查询、修改和可视化CSV/JSON/XLSX等文件数据，无需编写代码或定义结构。提供**智能SQL编辑器**（自动补全、历史记录）、多种图表（折线/饼图等）及数据导出功能。所有操作在本地完成，**保障数据隐私**，支持一次性买断授权。免费版可试用，适合数据分析师快速处理本地文件。

---

## <a name="15"></a>15. 从几何视角理解反函数的微积分（2023） 
<small>🔗 [tobylam.xyz](https://tobylam.xyz/2023/11/27/inverse-functions-legendre-part-1): Geometrically understanding calculus of inverse functions (2023)</small>


| 🔥: 96 \| 💬: [4](https://news.ycombinator.com/item?id=43895852) \| 🗓️ 2025-05-05


<br />
本文通过几何方法探讨**反函数定理**和**勒让德变换**，避免枯燥的公式推导。反函数定理表明，若函数\(f\)在点\(a\)可导且导数非零，则其反函数\(f^{-1}\)的导数为\(\frac{1}{f'(f^{-1}(x))}\)。几何上，反函数是原函数图像关于直线\(y=x\)的对称变换，斜率也随之取倒数。  

对于积分，勒让德变换将原函数积分与反函数积分关联，公式为\(G(y) = y \cdot g(y) - F(g(y)) + C\)。例如，通过\(\tan x\)的积分可推导出\(\arctan x\)的积分表达式。这种方法不仅直观，还在物理学中有广泛应用。

---

## <a name="16"></a>16. 2024年：用systemd替代Kubernetes的实践 
<small>🔗 [blog.yaakov.online](https://blog.yaakov.online/replacing-kubernetes-with-systemd/): Replacing Kubernetes with systemd (2024)</small>


| 🔥: 96 \| 💬: [55](https://news.ycombinator.com/item?id=43899236) \| 🗓️ 2025-05-05


<br />
作者回顾了2018年使用**Kubernetes**搭建家庭集群的经历，发现其虽能通过**自动化循环**（如创建Pod、管理证书）实现强大功能，但资源消耗过高（CPU常驻6%-12%），导致设备发热、噪音大，甚至影响睡眠。尽管依赖其便捷的GitOps和容器更新能力，作者最终转向**Podman**方案：通过生成systemd服务文件实现容器自启，结合`io.containers.autoupdate`标签自动更新镜像，辅以用户常驻（`loginctl enable-linger`），以极低开销复现了Kubernetes 99%的核心功能。迁移后，新VPS性能更轻量、成本更低，但Podman未来可能转向Quadlet配置，留下新学习课题。

---

## <a name="17"></a>17. 西班牙和葡萄牙停电期间的互联网使用模式 
<small>🔗 [blog.akamai-mpulse.com](https://blog.akamai-mpulse.com/blog/2025-05-03-iberian-power-outage/): Internet usage pattern during power outage in Spain and Portugal</small>


| 🔥: 92 \| 💬: [100](https://news.ycombinator.com/item?id=43894363) \| 🗓️ 2025-05-05


<br />
本文分析了2025年4月28日伊比利亚半岛大停电期间的网络流量数据。**西班牙和葡萄牙**的桌面流量骤降80%，而移动流量仅减少40%，表明用户转向手机上网。**移动设备**主要通过蜂窝网络连接，WiFi使用量下降50%。用户主要访问**政府网站**和新闻平台，西班牙人更依赖官方信息，而葡萄牙人则频繁查询食品安全。手机电量比平时低10%，但随着电力恢复逐渐正常。此次事件凸显了分布式网络基础设施在紧急情况下的重要性。

---

## <a name="18"></a>18. 数学家证实126维空间存在奇异扭曲形状 
<small>🔗 [quantamagazine.org](https://www.quantamagazine.org/dimension-126-contains-strangely-twisted-shapes-mathematicians-prove-20250505/): Dimension 126 Contains Twisted Shapes, Mathematicians Prove</small>


| 🔥: 91 \| 💬: [47](https://news.ycombinator.com/item?id=43896199) \| 🗓️ 2025-05-05


<br />
经过65年的研究，数学家最终证明**126维空间**中存在无法通过简单手术转化为球体的**奇异扭曲形状**。这一发现与**拓扑学**中高维球面的关系密切相关。此前，类似形状仅在2、6、14、30和62维中被发现。复旦大学和加州大学的团队通过计算机计算与理论结合，解决了这一遗留问题，标志着拓扑学领域一项重大突破。

---

## <a name="19"></a>19. 雅达利2600经典游戏《冒险》的开发秘史 
<small>🔗 [atariarchive.org](https://www.atariarchive.org/blog/adventure-march-1980/): History of "Adventure" for the Atari 2600</small>


| 🔥: 86 \| 💬: [14](https://news.ycombinator.com/item?id=43895237) \| 🗓️ 2025-05-05


<br />
《冒险》是雅达利2600最具影响力的原创游戏之一，由**沃伦·罗宾内特**受文字游戏《巨洞冒险》启发开发。游戏将文本探索转化为图形界面，玩家需在30个屏幕中收集圣杯、对抗**三条性格各异的龙**，并解开迷宫谜题。罗宾内特秘密加入了史上首个广为人知的**彩蛋**——隐藏房间中的开发者署名，此举后来成为游戏行业传统。游戏还首创了难度分级和随机物品机制，奠定了早期动作冒险游戏的框架。

---

## <a name="20"></a>20. SpaceX曾向联邦调查局提出“狙击手”炸毁火箭的离奇理论 
<small>🔗 [arstechnica.com](https://arstechnica.com/space/2025/05/spacex-pushed-sniper-theory-with-the-feds-far-more-than-is-publicly-known/): SpaceX pushed "sniper" theory with the feds</small>


| 🔥: 83 \| 💬: [49](https://news.ycombinator.com/item?id=43894678) \| 🗓️ 2025-05-05


<br />
2016年9月，SpaceX的**猎鹰9号**火箭在静态点火测试中突然爆炸，导致价值不菲的Amos-6卫星损毁。事故调查初期，由于缺乏明确原因，SpaceX创始人**埃隆·马斯克**一度怀疑是竞争对手ULA（联合发射联盟）的狙击手从附近建筑屋顶射击所致。公司甚至进行了实弹测试并请求检查ULA屋顶，但最终被FAA和FBI否决。真相是**超低温燃料加载过快**导致氦气罐破裂。这一事件成为SpaceX低谷，但随后公司迅速崛起，如今发射量远超ULA。

---

## <a name="21"></a>21. 泰克TDS 684B示波器：揭秘CCD模拟存储技术 
<small>🔗 [tomverbeure.github.io](https://tomverbeure.github.io/2025/05/04/TDS684B-CCD-Memory.html): A Tektronix TDS 684B Oscilloscope Uses CCD Analog Memory</small>


| 🔥: 82 \| 💬: [49](https://news.ycombinator.com/item?id=43895622) \| 🗓️ 2025-05-05


<br />
本文拆解了一台1990年代的**泰克TDS 684B示波器**，探究其如何实现**5Gsps超高采样率**。该设备通过**CCD模拟存储器（ADG286D芯片）**暂存高速信号，再以8MHz低速ADC数字化。实测发现：无论设置如何，每次固定采集16k样本（2毫秒突发），丢弃多余数据后显示。尽管ADC输入噪声明显，CRT却能呈现干净波形。这一巧妙设计使其在当年性能领先，但存储深度仅15k点，且无法扩展。

---

## <a name="22"></a>22. 欧盟拟2027年起全面禁止匿名加密货币账户和隐私币 
<small>🔗 [cointelegraph.com](https://cointelegraph.com/news/eu-crypto-ban-anonymous-privacy-tokens-2027): EU to ban anonymous crypto accounts and privacy coins by 2027</small>


| 🔥: 77 \| 💬: [104](https://news.ycombinator.com/item?id=43892964) \| 🗓️ 2025-05-05


<br />
欧盟将于2027年实施新**反洗钱法规（AMLR）**，禁止金融机构和**加密货币服务商（CASPs）**处理匿名账户或**隐私币**（如门罗币、Zcash）。新规要求对超1000欧元交易进行客户尽职调查，并直接监管跨国运营的CASPs。此举是欧盟加强加密货币监管的一部分，旨在提升透明度并打击非法金融活动。

---

## <a name="23"></a>23. AI编程工具Cursor估值飙升至90亿美元 
<small>🔗 [ft.com](https://www.ft.com/content/a7b34d53-a844-4e69-a55c-b9dee9a97dd2): Cursor hits $9B valuation</small>


| 🔥: 76 \| 💬: [134](https://news.ycombinator.com/item?id=43895516) \| 🗓️ 2025-05-05


<br />
人工智能编程应用**Cursor**的开发商近期估值达到**90亿美元**，引发市场关注。该工具主打“氛围编程”（**vibe coding**）概念，旨在提升开发效率。文章同时介绍了《金融时报》的订阅方案，包括标准版、高级版及印刷+数字组合套餐，提供全球新闻、专家分析和独家内容。

---

## <a name="24"></a>24. Databricks拟10亿美元收购开源数据库公司Neon 
<small>🔗 [upstartsmedia.com](https://www.upstartsmedia.com/p/scoop-databricks-talks-to-acquire-neon): Databricks in Talks to Acquire Startup Neon for About $1B</small>


| 🔥: 76 \| 💬: [43](https://news.ycombinator.com/item?id=43899016) \| 🗓️ 2025-05-05


<br />
据独家消息，**数据与AI巨头Databricks**正就收购开源Postgres引擎开发商**Neon**进行深入谈判，交易估值约**10亿美元**。知情人士透露，若计入员工留任方案，最终金额可能超这一数字。但交易尚未最终敲定，仍存变数。Neon CEO及公司均未置评，Databricks亦拒绝回应。此次收购将延续该独角兽企业通过并购扩张的战略。

---

## <a name="25"></a>25. 美国政府官员使用的定制版Signal应用TeleMessage遭黑客入侵 
<small>🔗 [techcrunch.com](https://techcrunch.com/2025/05/05/telemessage-a-modified-signal-clone-used-by-us-govt-officials-has-been-hacked/): TeleMessage, a modified Signal clone used by US govt. officials, has been hacked</small>


| 🔥: 74 \| 💬: [6](https://news.ycombinator.com/item?id=43893550) \| 🗓️ 2025-05-05


<br />
黑客利用**TeleMessage**的漏洞窃取了美国官员及企业的**存档消息**和联系人信息。该应用提供定制版Signal、Telegram等加密通讯工具的存档服务，但曝光的聊天记录显示其**存储过程未端到端加密**。尽管内阁成员数据未泄露，但海关、Coinbase和银行信息被提取。母公司Smarsh暂未回应。

---
