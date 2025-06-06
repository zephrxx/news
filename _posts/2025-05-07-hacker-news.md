---
layout: page
title: 勒西科技日报 - 2025年05月07日
date: 2025-05-07 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. Ty：基于 Rust 的极速 Python 类型检查器与语言服务器；
1. JetBrains宣布CLion免费供非商业用途使用；
1. Unity的双标开源政策：封杀VLC事件始末；
1. PostgreSQL 18前瞻：异步I/O加速磁盘读取性能；
1. 美国血液出口真相：数据背后的玄机；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. Ty：基于 Rust 的极速 Python 类型检查器与语言服务器 
<small>🔗 [github.com](https://github.com/astral-sh/ty): Ty: A fast Python type checker and language server</small>


| 🔥🔥: 656 \| 💬: [180](https://news.ycombinator.com/item?id=43918484) \| 🗓️ 2025-05-07


<br />
Ty 是一款**用 Rust 编写**的 Python **类型检查工具**和语言服务器，主打**极高性能**，目前仍处于开发阶段，尚未投入生产环境。项目采用 MIT 许可证，开发者可通过提交 Issue 反馈问题，或前往 Ruff 仓库参与代码贡献（核心 Rust 代码位于 ruff 子模块）。当前已获 319 颗星，但需注意其**非稳定版本**的特性。

---

## <a name="2"></a>2. JetBrains宣布CLion免费供非商业用途使用 
<small>🔗 [blog.jetbrains.com](https://blog.jetbrains.com/clion/2025/05/clion-is-now-free-for-non-commercial-use/): CLion Is Now Free for Non-Commercial Use</small>


| 🔥🔥: 547 \| 💬: [338](https://news.ycombinator.com/item?id=43914705) \| 🗓️ 2025-05-07


<br />
JetBrains宣布其**跨平台C/C++集成开发环境CLion**现可免费用于**非商业用途**，包括学习、开源项目、内容创作及个人爱好开发。此举旨在降低使用门槛，支持开发者学习和创新。**商业用途**仍需付费订阅。免费版功能与付费版几乎相同，但需同意收集**匿名使用数据**以改进产品。用户可通过IDE内选项直接申请非商业许可证。

---

## <a name="3"></a>3. Unity的双标开源政策：封杀VLC事件始末 
<small>🔗 [mfkl.github.io](https://mfkl.github.io/2024/01/10/unity-double-oss-standards.html): Unity’s Open-Source Double Standard: the ban of VLC</small>


| 🔥🔥: 486 \| 💬: [144](https://news.ycombinator.com/item?id=43914832) \| 🗓️ 2025-05-07


<br />
2019年起，开发者通过**Unity商店**分发开源工具**VLC for Unity**的二进制文件，该工具实现了Unity引擎与VLC多媒体引擎的跨平台整合。然而2023年夏，Unity突然以违反LGPL协议为由封禁其账号，尽管**Unity自身及商店内大量资产**均依赖LGPL库（如FFmpeg）。  

封禁后，团队转向自建**Videolabs商店**，继续提供VLC插件及多媒体技术支持，并推出按需定制的咨询套餐（3/10/24小时）。事件暴露Unity对开源协议执行的随意性，引发开发者社区争议。

---

## <a name="4"></a>4. PostgreSQL 18前瞻：异步I/O加速磁盘读取性能 
<small>🔗 [pganalyze.com](https://pganalyze.com/blog/postgres-18-async-io): Waiting for Postgres 18: Accelerating Disk Reads with Asynchronous I/O</small>


| 🔥🔥: 419 \| 💬: [102](https://news.ycombinator.com/item?id=43916577) \| 🗓️ 2025-05-07


<br />
PostgreSQL 18引入了**异步I/O**（AIO）功能，通过并行处理磁盘读取请求显著提升性能，尤其适用于云环境等高延迟场景。新参数**io_method**支持三种模式：传统同步（`sync`）、后台工作进程（`worker`）和基于Linux内核的高效接口（`io_uring`）。基准测试显示，`io_uring`在冷缓存下将读取性能提升2-3倍。此外，**effective_io_concurrency**参数现直接控制预读请求数量，需结合实际I/O子系统调优。异步I/O虽优化吞吐量，但使得I/O等待事件更难追踪，新增的`pg_aios`视图可辅助监控。目前该功能仅支持读操作，写入仍为同步。

---

## <a name="5"></a>5. 美国血液出口真相：数据背后的玄机 
<small>🔗 [dynomight.net](https://dynomight.net/blood/): So Much Blood</small>


| 🔥🔥: 359 \| 💬: [158](https://news.ycombinator.com/item?id=43913751) \| 🗓️ 2025-05-07


<br />
一篇《经济学人》文章称美国**血液制品**占商品出口的1.8%，引发热议。作者深入调查发现：该数据包含疫苗等非血液产品，实际**纯血液出口**仅占0.53%。通过海关编码拆解，**血浆**（0.29%）和**血清**（0.24%）是主力，其余可能含血液的免疫产品（如抗体）占比约0.16%。美国供应全球70%药用血浆，但统计口径差异导致公众认知偏差。

---

## <a name="6"></a>6. Mistral推出企业级本地化AI助手Le Chat Enterprise 
<small>🔗 [mistral.ai](https://mistral.ai/news/le-chat-enterprise): Mistral ships Le Chat – enterprise AI assistant that can run on prem</small>


| 🔥🔥: 319 \| 💬: [88](https://news.ycombinator.com/item?id=43916098) \| 🗓️ 2025-05-07


<br />
Mistral AI发布**Le Chat Enterprise**，搭载全新Mistral Medium 3模型，为企业提供统一AI平台，解决工具碎片化、数据安全隐患等问题。支持**混合部署**、企业级搜索、自定义代理构建及私有化知识库整合，确保数据隐私与灵活部署。新增自动摘要、跨平台连接（如Google Drive/SharePoint）功能，**无需代码**即可创建定制AI助手。现已在Google Cloud上架，即将登陆Azure和AWS。

---

## <a name="7"></a>7. 让摩托车骑行更安全的创新之旅 
<small>🔗 [gill.net.in](https://gill.net.in/posts/my-quest-to-make-motorcycle-riding-safer/): My quest to make motorcycle riding that tad bit safer</small>


| 🔥🔥: 246 \| 💬: [273](https://news.ycombinator.com/item?id=43914235) \| 🗓️ 2025-05-07


<br />
作者重拾摩托车爱好时，在一次培训中意识到**引擎制动时后车难以察觉减速**的风险。受此启发，他开发了**BrakeBright**——一款智能刹车灯系统，通过加速度传感器自动检测减速并激活刹车灯（包括紧急闪烁功能）。历经多次迭代和实地测试（如苏格兰NC500路线），该设备克服了振动干扰等问题，最终实现防水抗震的可靠设计。目前产品已量产，支持用户自定义固件升级，旨在**普及高端车型才有的安全技术**，让骑行更安全。

---

## <a name="8"></a>8. 开源替代Google Analytics的工具：Rybbit 
<small>🔗 [github.com](https://github.com/rybbit-io/rybbit): Open source Google Analytics replacement</small>


| 🔥🔥: 235 \| 💬: [118](https://news.ycombinator.com/item?id=43918620) \| 🗓️ 2025-05-07


<br />
Rybbit是一款**开源、隐私友好**的Google Analytics替代方案，比传统工具**直观10倍**。它提供所有核心网站分析指标（如会话、独立用户、页面浏览量等），且**无需Cookie或用户追踪**，完全符合GDPR和CCPA规范。支持实时仪表盘、自定义事件、地理位置追踪（国家→地区→城市）及高级过滤功能，可自托管或使用托管服务。目前已在GitHub获得970颗星，采用AGPL-3.0许可证。

---

## <a name="9"></a>9. 专为电子墨水屏优化的漫画转换工具Kindle Comic Converter 
<small>🔗 [github.com](https://github.com/ciromattia/kcc): Show HN: eInk optimized manga with Kindle Comic Converter (+Kobo/ReMarkable)</small>


| 🔥🔥: 211 \| 💬: [41](https://news.ycombinator.com/item?id=43916956) \| 🗓️ 2025-05-07


<br />
Kindle Comic Converter（KCC）是一款**开源工具**，可将漫画、漫画文件（如CBZ/CBR/PDF等）转换为适配**Kindle、Kobo、reMarkable等电子墨水屏设备**的格式。其核心功能包括：**全屏无边框显示**、图像优化（针对电子墨水屏特性调整色彩和对比度）、文件体积压缩（按设备分辨率智能缩放）。支持输出MOBI/EPUB/KEPUB等格式，并提供命令行版本供高级用户使用。  

工具需配合KindleGen、7-Zip等依赖项，提供Windows/macOS/Linux多平台支持，开发者可通过GitHub参与贡献。注意：KCC与亚马逊官方工具无关，完全面向读者需求开发。

---

## <a name="10"></a>10. Anthropic API推出网页搜索功能 
<small>🔗 [anthropic.com](https://www.anthropic.com/news/web-search-api): Web search on the Anthropic API</small>


| 🔥🔥: 202 \| 💬: [46](https://news.ycombinator.com/item?id=43920188) \| 🗓️ 2025-05-07


<br />
Anthropic宣布为Claude API新增**网页搜索工具**，开发者可构建能获取实时信息的AI应用。Claude能自主判断是否需要搜索，生成精准查询并分析结果，提供带引用的答案。**金融、法律、开发工具**等领域均可受益。管理员可通过域名白名单/黑名单控制访问范围，确保数据安全。该功能已集成至Claude Code，支持查询最新技术文档。定价为每千次搜索10美元，现支持Claude 3.7 Sonnet等模型。

---

## <a name="11"></a>11. Gemini 2.0 预览版上线：AI 图像生成与编辑新功能 
<small>🔗 [developers.googleblog.com](https://developers.googleblog.com/en/generate-images-gemini-2-0-flash-preview/): Create and edit images with Gemini 2.0 in preview</small>


| 🔥🔥: 189 \| 💬: [84](https://news.ycombinator.com/item?id=43917461) \| 🗓️ 2025-05-07


<br />
Google AI Studio 宣布 **Gemini 2.0 Flash** 预览版开放图像生成功能，开发者可通过 API 集成对话式图像创作与编辑，并享受更高的速率限制。新版本优化了**视觉质量**和**文本渲染准确性**，同时大幅降低过滤拦截率。支持实时协作编辑、局部图像修改及动态生成产品图等场景。开发者现可通过 Google AI Studio 或 Vertex AI 体验这一功能，未来还将推出更多改进。

---

## <a name="12"></a>12. Mac主题花园：经典Mac主题的宝库上线 
<small>🔗 [damien.zone](https://damien.zone/introducing-mac-themes-garden/): Mac Themes Garden</small>


| 🔥🔥: 148 \| 💬: [41](https://news.ycombinator.com/item?id=43919868) \| 🗓️ 2025-05-07


<br />
Mac主题花园（Mac Themes Garden）是一个展示**3000多款**经典Mac时代Kaleidoscope主题的网站，支持浏览、下载和探索。网站还提供RSS订阅功能，方便用户获取最新主题更新。  

开发者通过手动截图和记录信息，耗时数年整理这些主题，尽管过程繁琐，但确保了数据的准确性。网站采用**Astro框架**构建，优化了性能以处理近5000个页面。UI设计复刻了Mac OS 9的风格，运用了大量**CSS技巧**还原经典界面元素，如窗口边框和按钮。  

目前项目已完成约一半，但开发者决定提前发布，让用户尽早体验这一怀旧宝藏。

---

## <a name="13"></a>13. 从程序员到CTO再到董事会：我在Cloudflare的13年旅程 
<small>🔗 [blog.cloudflare.com](https://blog.cloudflare.com/en-us/three-chapters-at-cloudflare-programmer-to-cto-to-board-of-directors/): Three Chapters at Cloudflare: Programmer to CTO to Board of Directors</small>


| 🔥🔥: 146 \| 💬: [27](https://news.ycombinator.com/item?id=43918600) \| 🗓️ 2025-05-07


<br />
Cloudflare前CTO John Graham-Cumming回顾了他在公司的13年职业生涯：从2012年以**程序员**身份加入初创团队，到主导推出**Universal SSL**等关键技术，再到如今加入董事会。他特别提到2017年**Cloudbleed事件**中团队展现的危机处理能力，以及建立伦敦和里斯本国际办公室的经历。作为技术领导者，他参与了WAF、DNS等核心产品的开发，并推动公司通过Project Galileo等项目践行"构建更好互联网"的使命。文章最后介绍了新任CTO Dane Knecht的接任，并表达了自己将以董事会成员身份继续关注AI等前沿技术领域的发展。

---

## <a name="14"></a>14. 变老并非你想的那样 
<small>🔗 [katycowan.co.uk](https://www.katycowan.co.uk/blog/getting-old): Getting Older Isn't What You Think</small>


| 🔥🔥: 141 \| 💬: [216](https://news.ycombinator.com/item?id=43917855) \| 🗓️ 2025-05-07


<br />
作者Katy Cowan以幽默笔触反思中年心境：36岁被称“老”令人失笑，50岁临近却发现自己**偏爱宁静**——早睡、爵士乐和书籍取代了音乐节喧嚣。作为夹在X世代与千禧一代之间的“Xennials”，她见证从磁带流媒体、拨号上网到AI的巨变，**兼具线下与线上生活的智慧**。文章批判社交媒体制造的焦虑，呼吁保持好奇与开放：“**确定性被高估，倾听却被低估**”——年龄增长不是封闭，而是更清晰地认识自我与世界的开始。

---

## <a name="15"></a>15. 我花钱买了整块GPU，就要物尽其用 
<small>🔗 [modal.com](https://modal.com/blog/gpu-utilization-guide): 'I paid for the whole GPU, I am going to use the whole GPU'</small>


| 🔥🔥: 127 \| 💬: [40](https://news.ycombinator.com/item?id=43920544) \| 🗓️ 2025-05-07


<br />
本文探讨了**GPU利用率**的三种衡量维度：**分配利用率**（GPU运行应用代码的时间占比）、**内核利用率**（GPU执行计算任务的时间占比）以及**模型浮点运算利用率（MFU）**（实际算力与理论算力的比值）。作者指出，由于GPU成本高昂，优化利用率至关重要，但不同层级的瓶颈（如经济限制、主机开销或数据传输）可能导致利用率低下。文中以Modal平台为例，说明通过快速资源分配、多云集群管理和定制化容器技术，可将分配利用率提升至90%以上。同时强调，高内核利用率未必代表高效算力使用，需结合通信优化和批处理等策略提升MFU。

---

## <a name="16"></a>16. 从诗人到菲尔兹奖得主：许埈珥的数学奇迹 
<small>🔗 [quantamagazine.org](https://www.quantamagazine.org/june-huh-high-school-dropout-wins-the-fields-medal-20220705/): June Huh dropped out to become a poet, now he’s won a Fields Medal (2022)</small>


| 🔥🔥: 114 \| 💬: [65](https://news.ycombinator.com/item?id=43920792) \| 🗓️ 2025-05-07


<br />
许埈珥（June Huh）高中辍学追求诗歌，却在大学第六年偶然接触数学后彻底改变人生。2022年，他因**连接组合数学与几何学**的突破性成果获得**菲尔兹奖**。他的研究揭示了图论中**色多项式系数**的深层几何结构，解决了40年未解的猜想。许埈珥将艺术直觉融入数学，认为探索真理的过程如同“捕捉已存在的美”。从“迷失的诗人”到顶尖数学家，他的故事展现了偶然与坚持的奇妙交织。

---

## <a name="17"></a>17. 三星斥资3.5亿美元收购B&W、天龙、马兰士等音频品牌 
<small>🔗 [engadget.com](https://www.engadget.com/audio/samsung-is-paying-350-million-for-audio-brands-bowers--wilkins-denon-marantz-and-polk-131514754.html): Samsung is paying $350M for audio brands B&W, Denon, Marantz and Polk</small>


| 🔥🔥: 111 \| 💬: [142](https://news.ycombinator.com/item?id=43918437) \| 🗓️ 2025-05-07


<br />
三星旗下**哈曼国际**以3.5亿美元现金收购医疗科技公司Masimo的音频业务，交易预计2025年底完成。此次收购将整合**宝华韦健（B&W）**、天龙、马兰士等品牌，强化哈曼在消费音频市场的领先地位。三星计划将这些技术应用于手机、电视等设备，同时保留原团队以推动创新。哈曼去年占据便携音频设备60%市场份额，此次收购旨在巩固其全球第一地位。

---

## <a name="18"></a>18. 迷走神经刺激疗法彻底消除PTSD症状 
<small>🔗 [neurosciencenews.com](https://neurosciencenews.com/vagus-nerve-stimulation-ptsd-28818/): Vagus Nerve Stimulation Erases PTSD: Study</small>


| 🔥🔥: 111 \| 💬: [67](https://news.ycombinator.com/item?id=43919812) \| 🗓️ 2025-05-07


<br />
一项突破性临床研究表明，将**迷走神经刺激（VNS）**与传统暴露疗法结合后，所有参与研究的创伤后应激障碍（PTSD）患者在治疗结束六个月内均摆脱了诊断。这种疗法通过植入设备发送短脉冲刺激颈部迷走神经，显著增强**神经可塑性**，使难治性PTSD患者获得持久缓解。目前第二阶段双盲试验正在进行，有望为现有疗法无效的患者提供新选择。该研究由得克萨斯大学达拉斯分校团队主导，成果发表于《Brain Stimulation》期刊。

---

## <a name="19"></a>19. Yggdrasil：一种去中心化的实验性紧凑路由方案 
<small>🔗 [yggdrasil-network.github.io](https://yggdrasil-network.github.io/about.html): Yggdrasil is an experimental compact routing scheme that is fully decentralised</small>


| 🔥🔥: 111 \| 💬: [31](https://news.ycombinator.com/item?id=43921624) \| 🗓️ 2025-05-07


<br />
Yggdrasil 是一种**完全去中心化**的实验性路由方案，仅需少量状态即可运行。它采用**最短路径算法**，节点通过对等连接自动传递流量，支持跨NAT通信，并能自我修复网络故障。每个节点拥有**加密身份**，生成稳定的IPv6地址，适合网状网络和边缘计算。与Tor等匿名覆盖网络不同，Yggdrasil 不追求匿名性，也非传统VPN，而是专注于测试路由方案的可扩展性。目前处于Alpha阶段，欢迎参与公测，但暂不建议用于关键任务。

---

## <a name="20"></a>20. OpenSearch 3.0正式发布：性能提升9.5倍，助力AI搜索与分析 
<small>🔗 [opensearch.org](https://opensearch.org/blog/opensearch-3-0-enhances-vector-database-performance/): OpenSearch 3.0 Released</small>


| 🔥🔥: 101 \| 💬: [25](https://news.ycombinator.com/item?id=43917122) \| 🗓️ 2025-05-07


<br />
OpenSearch 3.0作为开源搜索与分析平台的最新版本，**性能较1.3版提升9.5倍**，并针对AI应用（如生成式AI、混合搜索和推荐系统）优化了**向量搜索**能力。新增**GPU加速**功能可将索引构建速度提高9.3倍，同时降低3.75倍成本。平台还引入gRPC支持、Apache Calcite集成等数据管理改进，并升级至Lucene 10和Java 21，增强可维护性与扩展性。该版本由OpenSearch软件基金会发布，致力于推动开放协作与创新。

---

## <a name="21"></a>21. 巴基斯坦公司向美国走私芬太尼类似物并实施诈骗 
<small>🔗 [krebsonsecurity.com](https://krebsonsecurity.com/2025/05/pakistani-firm-shipped-fentanyl-analogs-scams-to-us/): Pakistani firm shipped fentanyl analogs, scams to us</small>


| 🔥: 98 \| 💬: [36](https://news.ycombinator.com/item?id=43921129) \| 🗓️ 2025-05-07


<br />
调查显示，**eWorldTrade**这家德州公司涉嫌通过在线平台分销合成阿片类药物（如比芬太尼更强的**异托尼太嗪**和卡芬太尼），并与巴基斯坦的**Abtach Ltd**等企业构成庞大诈骗网络。这些公司以低价商标注册、图书出版和网站设计为诱饵，骗取西方客户钱财后实施**勒索**。  

Abtach创始人Azneem Bilwani还涉及巴基斯坦史上最大洗钱案，其关联公司Digitonics Labs通过伪造商标证书和钓鱼网站月入250万美元。部分涉案人员曾效力于**Axact**（2015年因贩卖假文凭被查），如今以新名义继续行骗。美国德州多家关联企业也因欺诈和违约被起诉。

---

## <a name="22"></a>22. 密西西比州的教育逆袭：偏见之下的成功典范 
<small>🔗 [educationdaly.us](https://www.educationdaly.us/p/mississippi-cant-possibly-have-good): Mississippi Can't Possibly Have Good Schools</small>


| 🔥: 94 \| 💬: [179](https://news.ycombinator.com/item?id=43915586) \| 🗓️ 2025-05-07


<br />
尽管密西西比州长期因**贫困、健康问题**和**历史遗留问题**被视为教育洼地，但近年来其教育系统却成为全美进步最快的典范。调整学生 demographics 后，该州在四年级数学和阅读测试中排名**全美第一**，黑人学生成绩甚至超越许多经费更充裕的州。然而，这种成功常被精英阶层的**地域偏见**忽视，甚至引发质疑。文章指出，这种“教育势利”阻碍了其他州向南方学习，导致资源浪费和进步停滞。同时，作者警告两党：民主党需重视教育议题，而共和党应避免因文化战争分散教育改革的专注力。

---

## <a name="23"></a>23. 大学生正用AI作弊席卷校园 
<small>🔗 [nymag.com](https://nymag.com/intelligencer/article/openai-chatgpt-ai-cheating-education-college-students-school.html): Everyone Is Cheating Their Way Through College</small>


| 🔥: 85 \| 💬: [138](https://news.ycombinator.com/item?id=43914834) \| 🗓️ 2025-05-07


<br />
文章揭露了以哥伦比亚大学学生Chungin "Roy" Lee为代表的**AI作弊现象**：他通过ChatGPT完成80%的作业，甚至开发面试作弊工具。调查显示近90%学生用AI辅助作业，教授们难以甄别**AI生成内容**。尽管学校尝试限制，学生仍将AI视为"必备工具"，甚至依赖其完成论文框架。学者警告这可能导致**学历贬值**，削弱批判性思维。教育界陷入监管困境，而学生已无法想象脱离AI的学习方式。

---

## <a name="24"></a>24. 全球最富10%人群造成三分之二气候变暖 
<small>🔗 [e360.yale.edu](https://e360.yale.edu/digest/worlds-richest-10-percent-responsible-for-two-thirds-of-warming): Richest 10 Percent Responsible for Two-Thirds of Warming</small>


| 🔥: 85 \| 💬: [63](https://news.ycombinator.com/item?id=43914876) \| 🗓️ 2025-05-07


<br />
《自然·气候变化》最新研究显示，自1990年以来，**全球最富有的10%人口**贡献了三分之二的气候变暖，其中**最富1%人群**单独导致五分之一的升温。其影响不仅源于高能耗生活方式，更因投资**化石燃料等重污染行业**。该群体对极端高温的“贡献”是普通人的26倍，并导致亚马逊干旱风险激增17倍。研究指出，科学已能追溯企业气候责任，例如雪佛龙公司或需为全球高温损失承担3.6万亿美元赔偿。

---

## <a name="25"></a>25. 12年前的老主板竟获M.2 SSD启动支持 
<small>🔗 [tomshardware.com](https://www.tomshardware.com/pc-components/motherboards/sandy-bridge-era-motherboard-gains-m-2-ssd-boot-support-12-years-after-launch-first-new-bios-in-a-decade-for-decommissioned-motherboard): Sandy Bridge-era motherboard gets M.2 SSD boot support 12 years after launch</small>


| 🔥: 72 \| 💬: [40](https://news.ycombinator.com/item?id=43914677) \| 🗓️ 2025-05-07


<br />
中国网友WhiteCamellia发现，**技嘉**为已停产的**B75M-D3H**主板（2012年发布）发布了新固件F16f，主要修复2024年曝光的PKfail漏洞，但意外加入了**NVMe启动支持**。这款主板原本仅配备SATA接口，但通过PCIe转接卡可连接M.2 SSD。尽管受限于PCIe 2.0带宽（实测读写约2000MB/s），性能仍远超传统SATA III。这是该主板十年来首次更新，尚不清楚该功能是否为技嘉有意添加。类似情况可能也存在于同期其他主板中。

---
