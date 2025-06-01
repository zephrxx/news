---
layout: page
title: 勒西科技日报 - 2025年05月31日
date: 2025-05-31 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 高精度时钟Mk IV开发全记录；
1. 《分析学I的简明Lean指南》；
1. 用组合工具暴力拦截爬虫；
1. 马斯克削减美国援助资金致30万人死亡 逾20万为儿童；
1. 渐进式JSON：优化数据传输的新思路；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 高精度时钟Mk IV开发全记录 
<small>🔗 [mitxela.com](https://mitxela.com/projects/precision_clock_mk_iv): Precision Clock Mk IV</small>


| 🔥🔥: 421 \| 💬: [109](https://news.ycombinator.com/item?id=44144750) \| 🗓️ 2025-05-31


<br />
本文详细介绍了**Precision Clock Mk IV**的设计与开发过程。这款时钟具备**毫秒级精度**，采用**双处理器架构**和创新的**四线铰链设计**，实现无闪烁显示与自动时区调整。核心亮点包括：通过**GPS驯服**确保长期稳定性，TCXO振荡器保障断电后的时间保持，以及可折叠铰链满足不同显示需求。开发中克服了芯片短缺、显示同步等挑战，最终打造出一款集高精度、低干扰与用户友好性于一体的时钟。

---

## <a name="2"></a>2. 《分析学I的简明Lean指南》 
<small>🔗 [terrytao.wordpress.com](https://terrytao.wordpress.com/2025/05/31/a-lean-companion-to-analysis-i/): A Lean companion to Analysis I</small>


| 🔥🔥: 181 \| 💬: [19](https://news.ycombinator.com/item?id=44145517) \| 🗓️ 2025-05-31


<br />
该内容来自WordPress博客，作者为Ben Eastaugh和Chris Sternal-Johnson。文章聚焦于**Lean定理证明工具**在数学分析基础课程（如**分析学I**）中的应用，旨在为学习者提供**实用辅助**。通过结合形式化验证与经典理论，帮助读者更高效地掌握核心概念与证明技巧。

---

## <a name="3"></a>3. 用组合工具暴力拦截爬虫 
<small>🔗 [lambdacreate.com](https://lambdacreate.com/posts/68): Using lots of little tools to aggressively reject the bots</small>


| 🔥🔥: 178 \| 💬: [98](https://news.ycombinator.com/item?id=44142761) \| 🗓️ 2025-05-31


<br />
作者的小型服务器突然遭到大量爬虫（如Amazon、Facebook、OpenAI的机器人）的疯狂抓取，导致资源耗尽。通过分析日志工具**lnav**和**goaccess**，发现这些爬虫以伪造用户代理的方式批量请求数据。作者通过**Nginx配置**直接屏蔽已知恶意代理，并配合**Fail2Ban**对频繁触发403的IP实施24小时封禁，最终成功抵御攻击。文中强调，这些抓取行为并非为了内容消费，而是为训练AI模型，对小型服务器造成极大负担。

---

## <a name="4"></a>4. 马斯克削减美国援助资金致30万人死亡 逾20万为儿童 
<small>🔗 [thetimes.com](https://www.thetimes.com/us/american-politics/article/usaid-doge-deaths-children-cuts-7nb83dfkp): Doge cuts to USAid blamed for 300k deaths – most of them children</small>


| 🔥🔥: 113 \| 💬: [60](https://news.ycombinator.com/item?id=44142790) \| 🗓️ 2025-05-31


<br />
波士顿大学全球健康教授**布鲁克·尼科尔斯**的模型显示，**埃隆·马斯克**领导的美国政府效率部（Doge）大幅削减美国国际开发署（USAid）预算，导致全球每3分钟1人死亡，累计30万（其中20万儿童）因**可预防疾病**（腹泻、肺炎、营养不良）及中断的艾滋病防治项目丧生。特朗普政府冻结90%援助资金后，尼科尔斯创建实时追踪网站揭露影响，但国务卿卢比奥否认数据。马斯克称USAid为“极左心理战组织”，但被迫承认部分分析错误。学者警告若资金不恢复，艾滋病死亡人数将翻三倍。

---

## <a name="5"></a>5. 渐进式JSON：优化数据传输的新思路 
<small>🔗 [overreacted.io](https://overreacted.io/progressive-json/): Progressive JSON</small>


| 🔥🔥: 111 \| 💬: [55](https://news.ycombinator.com/item?id=44147945) \| 🗓️ 2025-05-31


<br />
本文提出**渐进式JSON**的概念，灵感来自渐进式JPEG。传统JSON传输需等待全部数据到达才能解析，而**流式JSON解析器**虽能处理不完整数据，但会导致结构不完整。作者提出**广度优先**的传输方式：先发送框架（含占位符），再分批填充数据，客户端用`Promise`表示未加载部分。这种方法允许**并行处理**数据，尤其适合慢速查询场景。最后以React服务端组件为例，说明如何结合`<Suspense>`实现优雅的渐进式UI加载。

---

## <a name="6"></a>6. 穿孔卡片密钥备份工具：pckb 
<small>🔗 [github.com](https://github.com/volution/punchcard-key-backup): Show HN: PunchCard Key Backup</small>


| 🔥🔥: 110 \| 💬: [33](https://news.ycombinator.com/item?id=44145202) \| 🗓️ 2025-05-31


<br />
该项目提供了一种将**128位数据**（如加密密钥）通过**穿孔卡片**形式备份到物理介质（如铝板）的方法。用户只需访问自包含的HTML工具（[链接](https://volution.ro/pckb)），生成打孔模板，并使用常见工具（冲头、钻头等）制作实体备份。恢复时，通过相同工具或手动二进制转换即可还原数据。  

**关键点**：  
1. **无需依赖软件**：数据可完全离线处理，HTML工具无外部依赖。  
2. **低成本材料**：仅需铝板、打孔工具等常见物品。  
3. **灵活扩展**：支持通过加密工具（如age/GPG）备份更长数据，仅需保存128位密钥。  

项目开源（CC BY 4协议），适合实验或安全备份需求。

---

## <a name="7"></a>7. YOLO-World：实时开放词汇目标检测新突破 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2401.17270): YOLO-World: Real-Time Open-Vocabulary Object Detection</small>


| 🔥🔥: 101 \| 💬: [33](https://news.ycombinator.com/item?id=44146858) \| 🗓️ 2025-05-31


<br />
该研究提出**YOLO-World**，通过**视觉-语言建模**和大规模数据集预训练，赋予YOLO系列检测器**开放词汇识别能力**。创新点包括可重参数化的视觉-语言路径聚合网络（RepVL-PAN）和区域-文本对比损失，显著提升零样本检测效率。在LVIS数据集上达到35.4 AP（52 FPS/V100），兼顾速度与精度，并在下游任务（如开放词汇实例分割）中表现优异。代码模型已开源。

---

## <a name="8"></a>8. Oniux：为任意Linux应用提供内核级Tor隔离 
<small>🔗 [blog.torproject.org](https://blog.torproject.org/introducing-oniux-tor-isolation-using-linux-namespaces/): Oniux: Kernel-level Tor isolation for any Linux app</small>


| 🔥: 96 \| 💬: [21](https://news.ycombinator.com/item?id=44146830) \| 🗓️ 2025-05-31


<br />
Oniux是一款基于**Linux命名空间**的命令行工具，通过内核级隔离确保应用流量强制经过**Tor网络**，杜绝代理配置错误或系统调用导致的数据泄露。其核心原理是将目标应用放入独立网络命名空间，仅开放定制接口`onion0`，相比传统方案`torsocks`（依赖动态链接库劫持），Oniux能覆盖静态二进制文件且彻底阻断恶意流量泄漏。当前支持通过Rust安装，可隔离命令行或图形应用，但作为实验性项目，仍需社区测试完善。底层依赖Arti和onionmasq，采用**Rust编写**，强调隐私关键场景的可靠性。

---

## <a name="9"></a>9. 四大聊天机器人应用的第三方追踪与开发工具分析 
<small>🔗 [jamesoclaire.com](https://jamesoclaire.com/2025/05/31/the-trackers-and-sdks-in-chatgpt-claude-grok-and-perplexity/): The Trackers and SDKs in ChatGPT, Claude, Grok and Perplexity</small>


| 🔥: 92 \| 💬: [13](https://news.ycombinator.com/item?id=44142839) \| 🗓️ 2025-05-31


<br />
通过逆向工程和流量分析，发现**OpenAI、Perplexity、Anthropic和Grok**的安卓应用广泛使用第三方SDK。开发工具以Kotlin为主，商业工具涵盖**Google、Firebase、Statsig**等，涉及分析、支付（如RevenueCat）和语音服务（如LiveKit）。Perplexity独特整合了MapBox和Shopify，而OpenAI依赖多种分析平台。数据流向透明度有限，部分功能可能通过API实现。

---

## <a name="10"></a>10. AI同行评审员：多智能体系统助力学术论文分析 
<small>🔗 [github.com](https://github.com/robertjakob/rigorous): Show HN: AI Peer Reviewer – Multiagent system for scientific manuscript analysis</small>


| 🔥: 92 \| 💬: [78](https://news.ycombinator.com/item?id=44144280) \| 🗓️ 2025-05-31


<br />
这款工具通过**多AI评审员**为学术论文提供全面反馈，涵盖**方法论**、清晰度和影响力等关键维度。用户可快速获得详细建议（**分钟级响应**），无需漫长等待，还能利用先进AI识别潜在改进点，显著提升投稿前的论文质量。

---

## <a name="11"></a>11. CCD共同发明者乔治·E·史密斯逝世，享年95岁 
<small>🔗 [nytimes.com](https://www.nytimes.com/2025/05/30/science/george-e-smith-dead.html): CCD co-inventor George E. Smith dies at 95</small>


| 🔥: 85 \| 💬: [6](https://news.ycombinator.com/item?id=44146619) \| 🗓️ 2025-05-31


<br />
**乔治·E·史密斯**（George E. Smith）是**电荷耦合器件（CCD）**的共同发明者，这一技术彻底改变了数码成像领域。他与威拉德·博伊尔共同获得了2009年诺贝尔物理学奖。史密斯于95岁去世，他的贡献为现代相机、医学成像和天文观测奠定了基础。CCD技术至今仍是许多**关键应用**的核心。

---

## <a name="12"></a>12. 我改用UTC时区后，生活彻底改变了 
<small>🔗 [timestripe.com](https://timestripe.com/magazine/blog/timezone/): My five-year experiment with UTC</small>


| 🔥: 84 \| 💬: [115](https://news.ycombinator.com/item?id=44144224) \| 🗓️ 2025-05-31


<br />
程序员Adam Arutyunov因厌倦时区混乱，五年前将所有设备设为**协调世界时（UTC）**。最初需脑内转换时间，但两周后，他的大脑能自动关联UTC与本地时间，甚至轻松处理多时区切换。**UTC的稳定性**尤其适合频繁出差或远程工作者，避免因时区变化导致的日程混乱。唯一缺点是需适应12小时制与24小时制的转换。Adam认为这一改变大幅提升了效率，并建议他人尝试。

---

## <a name="13"></a>13. 核电站投资风险最高，太阳能最低 
<small>🔗 [bu.edu](https://www.bu.edu/igs/2025/05/19/investment-risk-for-energy-infrastructure-construction-is-highest-for-nuclear-power-plants-lowest-for-solar/): Investment Risk Is Highest for Nuclear Power Plants, Lowest for Solar</small>


| 🔥: 78 \| 💬: [131](https://news.ycombinator.com/item?id=44143432) \| 🗓️ 2025-05-31


<br />
波士顿大学全球可持续发展研究所最新研究发现，全球超60%的能源基建项目存在**预算超支**问题。核电站表现最差，平均成本超支达**102.5%**（超预期15.6亿美元），工期延误严重。氢能、碳捕获等新兴技术同样风险较高。相比之下，**太阳能**和电网项目成本控制最佳，风电场也表现优异。研究强调，**可再生能源**不仅环保，还能降低财务风险。该分析涵盖83国662个项目（总投资1.358万亿美元），为全球能源规划提供了关键风险参考。

---

## <a name="14"></a>14. 用ed(1)作为我的静态网站生成器 
<small>🔗 [aartaka.me](https://aartaka.me/this-post-is-ed.html): Using Ed(1) as My Static Site Generator</small>


| 🔥: 73 \| 💬: [29](https://news.ycombinator.com/item?id=44144308) \| 🗓️ 2025-05-31


<br />
作者Artyom Bologov分享了他用**ed文本编辑器**替代传统静态网站生成器的实验。他经历了从Lisp引擎、C预处理器到ed的多次技术转换，最终通过**ed脚本**实现多格式内容生成（支持5种格式）。**优势**包括语法自由、兼容旧格式及规避特殊字符问题；**局限**在于缺乏文件包含功能及版本差异带来的调试难题。尽管承认这是“古怪选择”，他仍推荐爱好者尝试这种极简而有趣的方案。全文贯穿对技术边界的探索精神。

---

## <a name="15"></a>15. 科幻场景中的NFS 4冷冻舱间隔技术 
<small>🔗 [kolektiva.social](https://kolektiva.social/@beka_valentine/114600567753999701): The NFS 4 Freezer Spacer In Science Fiction Sets</small>


| 🔥: 71 \| 💬: [11](https://news.ycombinator.com/item?id=44147631) \| 🗓️ 2025-05-31


<br />
该文本提到使用Mastodon网页应用需启用JavaScript，或可下载平台对应的原生应用。**关键点**在于技术实现方式的选择，但主要内容缺失，可能为片段或提示性说明。**冷冻舱间隔技术**作为科幻设定元素未展开描述，推测与**存储**或**休眠系统**相关。

---

## <a name="16"></a>16. 秘密知识宝典：开发者与运维者的终极资源库 
<small>🔗 [github.com](https://github.com/trimstray/the-book-of-secret-knowledge): The Book of Secret Knowledge</small>


| 🔥: 66 \| 💬: [3](https://news.ycombinator.com/item?id=44142852) \| 🗓️ 2025-05-31


<br />
这是一份涵盖**Linux、安全、DevOps**等领域的综合资源合集，包含实用清单、手册、速查表、博客、命令行工具等。项目采用MIT许可，社区活跃（17.1万星标），适合**系统管理员、渗透测试员**和开发者。内容按主题分类，如网络工具（nmap、curl）、SSL检测（OpenSSL）、调试工具（strace）等，强调高质量与易用性。鼓励贡献，遵循简洁、实用的原则。

---

## <a name="17"></a>17. 得州警察动用8.3万摄像头追踪堕胎女性 
<small>🔗 [eff.org](https://www.eff.org/deeplinks/2025/05/she-got-abortion-so-texas-cop-used-83000-cameras-track-her-down): She Got an Abortion. So a Texas Cop Used 83,000 Cameras to Track Her Down</small>


| 🔥: 58 \| 💬: [6](https://news.ycombinator.com/item?id=44142835) \| 🗓️ 2025-05-31


<br />
美国得州一名警察利用**8.3万个车牌识别摄像头**（ALPR）跨州追踪一名涉嫌自行堕胎的女性，搜查范围包括华盛顿州和伊利诺伊州等堕胎合法地区。此案暴露了**大规模监控系统**被滥用于生殖健康管控，且数据共享缺乏监管。电子前线基金会（EFF）警告，**车牌识别技术**正从追查犯罪工具演变为侵犯公民自由的帮凶，甚至可能被反堕胎组织利用。各州需立法限制数据共享，遏制监控越权。

---

## <a name="18"></a>18. 新型自适应光学技术揭示太阳大气层精细结构 
<small>🔗 [nso.edu](https://nso.edu/press-release/new-adaptive-optics-shows-stunning-details-of-our-stars-atmosphere/): New Adaptive Optics Shows Details of Our Star's Atmosphere</small>


| 🔥: 57 \| 💬: [4](https://news.ycombinator.com/item?id=44147573) \| 🗓️ 2025-05-31


<br />
科学家利用**新型自适应光学系统Cona**，成功消除了地球大气湍流造成的图像模糊，拍摄到迄今最清晰的太阳**日冕层**高清影像。该系统安装在1.6米古德太阳望远镜上，以每秒2200次的速度调整镜面，分辨率达63公里，首次捕捉到宽度不足20公里的**日冕雨**、等离子体流动态及耀斑精细结构。这一突破性技术将助力研究日冕加热机制与空间天气，未来还将应用于4米丹尼尔·井上太阳望远镜，开启太阳物理学新纪元。研究成果发表于《自然·天文学》。

---

## <a name="19"></a>19. Sguaba：为工程师设计的防误用刚体变换工具 
<small>🔗 [blog.helsing.ai](https://blog.helsing.ai/sguaba-hard-to-misuse-rigid-body-transforms-for-engineers-with-other-things-to-worry-about-than-aeaa45af9e0d): Sguaba: Hard-to-misuse rigid body transforms for engineers</small>


| 🔥: 52 \| 💬: [13](https://news.ycombinator.com/item?id=44146744) \| 🗓️ 2025-05-31


<br />
Sguaba是一个基于Rust的库，旨在解决**坐标系统转换**中的常见错误。它通过强类型系统确保不同坐标系（如**WGS84**、**NED**、**FRD**）和表示方式（笛卡尔坐标、球坐标等）不会混淆，从而避免灾难性错误。该工具面向工程师而非数学家，提供了直观的类型（如`Coordinate`、`Pose`）和安全的转换操作（如`RigidBodyTransform`）。示例展示了如何将飞行员的观测数据从FRD转换为WGS84坐标。Sguaba已开源，目前支持部分坐标系，未来计划扩展更多功能。

---

## <a name="20"></a>20. 发现网站字体神器：Fontofweb 
<small>🔗 [fontofweb.com](https://fontofweb.com): Show HN: Fontofweb – Discover Fonts Used on a Website or Websites Using Font(s)</small>


| 🔥: 51 \| 💬: [18](https://news.ycombinator.com/item?id=44144451) \| 🗓️ 2025-05-31


<br />
Fontofweb 是一个帮助用户**快速识别**并收藏网站所用字体的工具。目前已收录 **457 种字体**，分析过 **288 个网站**，拥有 **128 名注册用户**。每日推荐一款字体（如5月31日的 *Cirka*），并提供字体设计者及使用该字体的网站列表（如 bettershotz.com 等）。支持按字体搜索网站，或反向查询网站字体组合，适合设计师和开发者**高效获取灵感**。

---

## <a name="21"></a>21. 域的两种理想 
<small>🔗 [susam.net](https://susam.net/two-ideals-of-fields.html): The Two Ideals of Fields</small>


| 🔥: 49 \| 💬: [39](https://news.ycombinator.com/item?id=44144331) \| 🗓️ 2025-05-31


<br />
本文探讨了**域**的理想结构及其与**交换环**的关系。**域**只有两个**理想**：零理想（仅含加法单位元）和自身，称为**平凡理想**。反之，若一个含单位元的交换环（且加法与乘法单位元不同）仅有平凡理想，则它必为域。这一对称性揭示了域与理想结构的深刻联系，并通过环的乘法逆元存在性加以证明。

---

## <a name="22"></a>22. 1974年的钚动力心脏起搏器 
<small>🔗 [orau.org](https://www.orau.org/health-physics-museum/collection/miscellaneous/pacemaker.html): Plutonium Powered Pacemaker (From 1974)</small>


| 🔥: 47 \| 💬: [22](https://news.ycombinator.com/item?id=44146847) \| 🗓️ 2025-05-31


<br />
该文介绍了1974年生产的**钚动力心脏起搏器**，其通过**钚-238衰变产生的热能发电**（半衰期88年），为心跳异常患者提供持续电力。起搏器采用**钛金属外壳**，可抵御枪击或火化等极端情况，表面辐射剂量为5-15毫雷姆/小时。美国曾有3家公司生产此类设备，目前（2003年）仍有50-100名使用者，去世后需移除并回收钚材料。捐赠方为洛斯阿拉莫斯国家实验室。

---

## <a name="23"></a>23. “丢工作给AI：被算法取代的劳动者们” 
<small>🔗 [theguardian.com](https://www.theguardian.com/technology/2025/may/31/the-workers-who-lost-their-jobs-to-ai-chatgpt): 'just put it in ChatGPT': the workers who lost their jobs to AI</small>


| 🔥: 35 \| 💬: [12](https://news.ycombinator.com/item?id=44145288) \| 🗓️ 2025-05-31


<br />
本文讲述了多位因**AI技术**失业的从业者经历：波兰记者抗议电台用**AI虚拟主播**取代真人，印尼插画师因Midjourney抄袭作品收入锐减，英国文案被ChatGPT抢走园艺博客工作，美国配音演员发现声音被AI盗用，而英国设计师因公司全面采用AI遭解雇。他们共同指出：**AI缺乏人类的情感与创造力**，且当前法律对AI滥用缺乏监管，呼吁重视技术伦理与劳动者权益。

---

## <a name="24"></a>24. 为何本科计算机课程抄袭屡禁不止（2018） 
<small>🔗 [kevinchen.co](https://kevinchen.co/blog/cant-stop-plagiarism-in-computer-science/): We still can't stop plagiarism in undergraduate computer science (2018)</small>


| 🔥: 29 \| 💬: [57](https://news.ycombinator.com/item?id=44146599) \| 🗓️ 2025-05-31


<br />
本文揭示了本科计算机课程中**抄袭现象普遍**却难以根治的困境。作者以助教经历指出，尽管检测工具（如MOSS）能发现大量抄袭案例（每学期20-40起），但**处理成本高昂**（耗时、学生抵赖、行政不作为）和**缺乏激励机制**（教师因差评或晋升压力选择忽视）导致问题持续。抄袭的**核心诱因**在于学生面临“高收益（省时高分）零风险”的扭曲激励。解决方案需从**统一课程政策**、**优化检测工具**和**校方支持**入手，但当前仍任重道远。

---

## <a name="25"></a>25. ATLAS：学习在测试时最优记忆上下文 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2505.23735): Atlas: Learning to Optimally Memorize the Context at Test Time</small>


| 🔥: 28 \| 💬: [2](https://news.ycombinator.com/item?id=44144407) \| 🗓️ 2025-05-31


<br />
该论文提出**ATLAS**，一种新型**长时记忆模块**，旨在解决现有Transformer和循环神经网络在长上下文任务中的局限性。ATLAS通过优化记忆容量、动态更新机制和更灵活的内存管理，显著提升了模型在语言建模、常识推理和长上下文理解等任务中的表现。实验表明，ATLAS在10M长度的BABILong基准测试中准确率提升80%，性能超越传统Transformer和线性循环模型。

---
