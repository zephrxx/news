---
layout: page
title: 勒西科技日报 - 2025年05月21日
date: 2025-05-21 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 微软员工被AI逼疯？GitHub Copilot闹剧引热议；
1. Signal默认屏蔽微软Recall截图功能；
1. Devstral：开源代码助手新标杆；
1. 动画分解演示（2012）；
1. 算法领域突破：少量内存可替代大量计算时间；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 微软员工被AI逼疯？GitHub Copilot闹剧引热议 
<small>🔗 [old.reddit.com](https://old.reddit.com/r/ExperiencedDevs/comments/1krttqo/my_new_hobby_watching_ai_slowly_drive_microsoft/): Watching AI drive Microsoft employees insane</small>


| 🔥🔥: 922 \| 💬: [498](https://news.ycombinator.com/item?id=44050152) \| 🗓️ 2025-05-21


<br />
GitHub Copilot近期在.NET运行时仓库中自动提交了大量问题代码，**微软员工被迫花费大量时间审核这些低质量PR**，引发开发者社区热议。网友戏称这是"**反向半人马**"现象——人类沦为AI的辅助工具。尽管部分PR最终被合并，但多数代码存在**基础错误**，甚至需要人工重写。这场闹剧暴露了当前AI编码工具的局限性，也让人质疑企业盲目推行AI的合理性。

---

## <a name="2"></a>2. Signal默认屏蔽微软Recall截图功能 
<small>🔗 [signal.org](https://signal.org/blog/signal-doesnt-recall/): By default, Signal doesn't recall</small>


| 🔥🔥: 444 \| 💬: [351](https://news.ycombinator.com/item?id=44053364) \| 🗓️ 2025-05-21


<br />
Signal桌面端新增**“屏幕安全”设置**，默认在Win11中启用，通过**数字版权管理（DRM）**技术阻止微软Recall等工具截取聊天内容。此举旨在应对Recall自动截屏存储用户活动引发的隐私争议，但可能影响部分无障碍工具使用。用户可手动关闭该功能，但Signal强调**隐私保护优先**，并呼吁操作系统厂商为安全应用提供更完善的开发支持。当前更新已正式推送。

---

## <a name="3"></a>3. Devstral：开源代码助手新标杆 
<small>🔗 [mistral.ai](https://mistral.ai/news/devstral): Devstral</small>


| 🔥🔥: 395 \| 💬: [82](https://news.ycombinator.com/item?id=44051733) \| 🗓️ 2025-05-21


<br />
Mistral AI与All Hands AI联合推出**Devstral**，这是目前**性能最强的开源代码代理模型**，专为解决真实软件开发问题设计。在SWE-Bench Verified基准测试中，Devstral以46.8%的准确率超越其他开源模型6%以上，甚至优于部分闭源大模型（如GPT-4.1-mini）。支持**单卡部署**（如RTX 4090），适用于本地开发与企业级隐私代码库，采用Apache 2.0许可证免费开源。

---

## <a name="4"></a>4. 动画分解演示（2012） 
<small>🔗 [datapointed.net](http://www.datapointed.net/visualizations/math/factorization/animated-diagrams/): Animated Factorization (2012)</small>


| 🔥🔥: 231 \| 💬: [53](https://news.ycombinator.com/item?id=44051958) \| 🗓️ 2025-05-21


<br />
该项目通过**动态可视化**展示数学中的**因数分解**过程，帮助用户直观理解复杂概念。核心特点是**交互式设计**，支持用户调整参数并实时观察结果。适用于教育场景，尤其适合初学者掌握基础数学原理。

---

## <a name="5"></a>5. 算法领域突破：少量内存可替代大量计算时间 
<small>🔗 [quantamagazine.org](https://www.quantamagazine.org/for-algorithms-a-little-memory-outweighs-a-lot-of-time-20250521/): For algorithms, a little memory outweighs a lot of time</small>


| 🔥🔥: 202 \| 💬: [46](https://news.ycombinator.com/item?id=44055347) \| 🗓️ 2025-05-21


<br />
麻省理工学院理论计算机科学家Ryan Williams在2024年提出了一项**里程碑式证明**，首次在50年内改写了计算机科学中对**时间与内存关系**的认知。他的研究表明，**少量内存**的合理运用可以达到与大量计算时间相同的效果，这一发现颠覆了传统认为"内存需求与运行时间成正比"的假设。该证明不仅解决了长期悬而未决的PSPACE与P复杂度类别关系问题，还通过创新的**模拟转换方法**，为所有算法提供了通用内存优化方案。这项被同行誉为"惊人突破"的研究，可能为计算机科学最古老的开放性问题提供新的解决路径。

---

## <a name="6"></a>6. 无需CRDT或OT的协同文本编辑新方案 
<small>🔗 [mattweidner.com](https://mattweidner.com/2025/05/21/text-without-crdts.html): Collaborative Text Editing Without CRDTs or OT</small>


| 🔥🔥: 198 \| 💬: [52](https://news.ycombinator.com/item?id=44053560) \| 🗓️ 2025-05-21


<br />
本文提出了一种**无需复杂算法**（如CRDT或OT）的协同文本编辑方法。核心思路是为每个字符分配**全局唯一ID**，客户端通过“在ID X后插入”指令与服务器同步，避免传统方案中索引冲突的问题。服务器保留已删除字符的ID（标记为`isDeleted`）以处理并发操作。该方法**简化了实现**，支持自定义功能（如分段权限控制），且兼容乐观本地更新。相比CRDT/OT的“黑箱”特性，这种方案更透明灵活，适合需要深度定制的协作应用。

---

## <a name="7"></a>7. 谷歌推出扩散模型Gemini Diffusion：速度提升5倍 
<small>🔗 [simonwillison.net](https://simonwillison.net/2025/May/21/gemini-diffusion/): Gemini Diffusion</small>


| 🔥🔥: 186 \| 💬: [28](https://news.ycombinator.com/item?id=44057820) \| 🗓️ 2025-05-21


<br />
谷歌在I/O大会上发布了**Gemini Diffusion**，这是其首款采用**扩散模型**（类似Imagen和Stable Diffusion）而非传统Transformer架构的LLM。该模型通过逐步降噪生成文本，**速度极快**（实测达857词/秒），且支持实时纠错，擅长代码和数学编辑。谷歌宣称其性能媲美**Gemini 2.0 Flash-Lite**，但速度快5倍。目前尚未有独立基准测试，但实测生成网页应用仅需数秒。此前商用扩散模型仅有2025年2月的Inception Mercury。

---

## <a name="8"></a>8. 大模型函数调用难以扩展，代码编排更简单高效 
<small>🔗 [jngiam.bearblog.dev](https://jngiam.bearblog.dev/mcp-large-data/): LLM function calls don't scale; code orchestration is simpler, more effective</small>


| 🔥🔥: 177 \| 💬: [69](https://news.ycombinator.com/item?id=44053744) \| 🗓️ 2025-05-21


<br />
当前常见做法是将工具调用的完整输出返回给大模型（LLM）处理，但面对真实场景的**大规模数据**（如Linear返回的70k字符JSON）时，这种方法成本高、速度慢且易出错。核心问题在于混淆了**数据编排**与**数据处理**。解决方案是通过**输出模式（output schemas）**直接解析结构化数据，用生成代码替代LLM重复处理。代码编排支持变量存储、工具链式调用及并行处理，并能利用类型系统避免幻觉。未来需设计安全的**AI运行时环境**以支持持久化执行。

---

## <a name="9"></a>9. Roto：为Rust设计的编译型脚本语言 
<small>🔗 [blog.nlnetlabs.nl](https://blog.nlnetlabs.nl/introducing-roto-a-compiled-scripting-language-for-rust/): Roto: A Compiled Scripting Language for Rust</small>


| 🔥🔥: 144 \| 💬: [109](https://news.ycombinator.com/item?id=44050222) \| 🗓️ 2025-05-21


<br />
Roto是一款专为Rust设计的**嵌入式脚本语言**，旨在为Rust应用提供**快速**且**类型安全**的脚本支持。其开发初衷源于BGP引擎Rotonda的需求——用户需要编写复杂路由过滤器，而传统配置语言无法满足。Roto通过**静态类型**和JIT编译（基于Cranelift）实现高性能，同时支持热重载和深度Rust集成（如直接调用Rust类型与方法）。示例展示了如何用Roto编写IP范围过滤器，并强调其**无序列化开销**的特点。目前Roto仍处于开发阶段，但已开放试用。

---

## <a name="10"></a>10. 《揭秘Discord：2015-2024年公开通信全数据集》 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2502.00627): Discord Unveiled: A Comprehensive Dataset of Public Communication (2015-2024)</small>


| 🔥🔥: 134 \| 💬: [151](https://news.ycombinator.com/item?id=44052041) \| 🗓️ 2025-05-21


<br />
该论文发布了迄今最全面的**Discord公开服务器数据集**，涵盖2015年至2024年间3,167个公共服务器的**20.5亿条消息**，涉及474万用户。数据通过API合规采集并匿名化处理，以JSON格式存储，便于计算社会科学研究。初步分析显示，**英语主导**但西语、法语等占比显著，社区主题从游戏扩展至艺术、社交等多元领域。研究填补了Discord学术数据空白，为去中心化治理、信息传播等议题提供基础。论文已提交至ICWSM 2025会议。

---

## <a name="11"></a>11. 谷歌AI Studio推出全新开发者体验升级 
<small>🔗 [developers.googleblog.com](https://developers.googleblog.com/en/google-ai-studio-native-code-generation-agentic-tools-upgrade/): An upgraded dev experience in Google AI Studio</small>


| 🔥🔥: 113 \| 💬: [66](https://news.ycombinator.com/item?id=44054185) \| 🗓️ 2025-05-21


<br />
谷歌AI Studio现支持**Gemini 2.5 Pro代码生成**，开发者可通过文本、图像或视频提示快速构建AI应用，并一键部署至Cloud Run。新增**多模态生成**功能，整合Imagen、Veo等媒体模型，以及原生语音对话和文本转语音（TTS）预览。实验性工具**URL Context**支持链接内容检索，**MCP协议**实现更便捷的开源工具集成。这些更新使AI Studio成为探索谷歌最新模型的首选平台。

---

## <a name="12"></a>12. 太阳系发现新矮行星 
<small>🔗 [minorplanetcenter.net](https://www.minorplanetcenter.net/mpec/K25/K25K47.html): Possible new dwarf planet found in our solar system</small>


| 🔥🔥: 112 \| 💬: [72](https://news.ycombinator.com/item?id=44054620) \| 🗓️ 2025-05-21


<br />
国际天文学联合会小行星中心于2025年5月21日发布通报（MPEC 2025-K47），确认发现编号为**2017 OF201**的新矮行星。该天体轨道参数显示其**半长轴达880天文单位**，**偏心率为0.95**，属于高椭圆轨道，公转周期约2.6万年。观测数据来自加拿大-法国-夏威夷望远镜（CFHT）和托洛洛山美洲际天文台的DECam设备，**绝对星等3.55**表明其直径可能达数百公里。当前该矮行星距太阳约91.5天文单位，正朝向近日点（45.2天文单位）运动。

---

## <a name="13"></a>13. 商业白痴时代 
<small>🔗 [wheresyoured.at](https://www.wheresyoured.at/the-era-of-the-business-idiot/): The Era of the Business Idiot</small>


| 🔥🔥: 102 \| 💬: [122](https://news.ycombinator.com/item?id=44053328) \| 🗓️ 2025-05-21


<br />
文章批判微软CEO纳德拉过度依赖AI工具（如Copilot）处理日常工作，认为这暴露了**现代高管的无能**——他们更关注表面效率而非实质产出。作者进一步指出，**新自由主义经济**将股东利益奉为圭臬，导致企业沦为剥削机器，CEO们脱离实际业务，沉迷短期增长。文中以米尔顿·弗里德曼的极端资本主义理论为例，揭示这种思维如何助长社会不公，并最终催生由“符号化高管”主导的**腐朽经济体系**。

---

## <a name="14"></a>14. 比AI编程助手更重要的5个开发要素 
<small>🔗 [codemanship.wordpress.com](https://codemanship.wordpress.com/2025/05/21/five-boring-things-that-have-a-bigger-impact-than-a-i-coding-assistants-on-dev-team-productivity/): Things that have a bigger impact than coding assistants</small>


| 🔥: 99 \| 💬: [54](https://news.ycombinator.com/item?id=44050843) \| 🗓️ 2025-05-21


<br />
文章指出，**小团队性价比更高**、**高频发布加速价值验证**、**限制并行任务提升交付效率**等传统原则对软件开发的影响远超AI编程助手，但企业常因需**文化变革**而回避。例如，高频发布需完善的持续集成体系，而**团队授权**依赖心理安全感。这些改变虽艰难，却能实现真正的敏捷开发。数据表明，AI助手无法替代这些核心实践。

---

## <a name="15"></a>15. 线粒体不仅是能量工厂，更是细胞的“主板” 
<small>🔗 [scientificamerican.com](https://www.scientificamerican.com/article/why-mitochondria-are-more-like-a-motherboard-than-the-powerhouse-of-the-cell/): Mitochondria Are More Than Powerhouses–They're the Motherboard of the Cell</small>


| 🔥: 95 \| 💬: [44](https://news.ycombinator.com/item?id=44052909) \| 🗓️ 2025-05-21


<br />
本文颠覆了传统认知，指出**线粒体**不仅是细胞的“能量工厂”，更是调控生命活动的核心“主板”。它们源自远古细菌共生，拥有独立DNA，并通过**动态社交行为**（如融合、纳米管连接和激素信号）协调细胞功能。线粒体功能异常与糖尿病、癌症、衰老等疾病密切相关，而健康线粒体间的协作（如嵴结构对齐）能提升能量效率。研究还发现，不同器官的线粒体具有**高度特异性**，甚至在大脑内也存在区域差异。这些发现为理解疾病和健康提供了新视角。

---

## <a name="16"></a>16. 美国建成全球最强激光器ZEUS，功率达2拍瓦 
<small>🔗 [news.engin.umich.edu](https://news.engin.umich.edu/2025/05/the-us-has-a-new-most-powerful-laser/): ZEUS – A new two-petawatt laser facility at the University of Michigan</small>


| 🔥: 94 \| 💬: [94](https://news.ycombinator.com/item?id=44052418) \| 🗓️ 2025-05-21


<br />
美国密歇根大学的**ZEUS激光设施**首次实验达到**2拍瓦**（2千万亿瓦）峰值功率，成为全美最强激光器。其脉冲持续时间仅25飞秒，功率超全球电网总输出百倍。该设施由美国国家科学基金会资助，将推动**医学、国家安全、材料科学**等领域研究。ZEUS采用多光束分束设计，支持国际团队合作实验，未来计划升级至3拍瓦，并探索**等离子体物理**和**粒子加速**等前沿应用。

---

## <a name="17"></a>17. 我开发了一款在线视频编辑器 
<small>🔗 [clipjs.vercel.app](https://clipjs.vercel.app/): Show HN: ClipJS – Edit your videos from a PC or phone</small>


| 🔥: 93 \| 💬: [41](https://news.ycombinator.com/item?id=44055542) \| 🗓️ 2025-05-21


<br />
这款工具主打**无水印编辑**，用户可以直接在网页上剪辑视频，无需担心成品被添加任何水印。操作简单，适合快速处理视频需求，**无需下载软件**，打开浏览器即可使用。核心亮点是**完全免费**且不限制导出视频的清晰度。

---

## <a name="18"></a>18. “涡轮增压”线粒体驱动鸟类史诗级迁徙 
<small>🔗 [quantamagazine.org](https://www.quantamagazine.org/turbocharged-mitochondria-power-birds-epic-migratory-journeys-20250519/): 'Turbocharged' Mitochondria Power Birds' Epic Migratory Journeys</small>


| 🔥: 90 \| 💬: [69](https://news.ycombinator.com/item?id=44051652) \| 🗓️ 2025-05-21


<br />
研究发现，**线粒体**的数量、形状和效率变化为鸟类长途迁徙提供了额外能量。例如，白冠麻雀可飞行4200公里，而北极燕鸥的旅程超过1.6万公里。科学家发现，**迁徙鸟类**的飞行肌肉中线粒体更多、效率更高，且能通过融合或分裂动态调整形态以提升能量产出。这种季节性变化由光照周期触发，无需基因改变，展现了生物的**表型可塑性**。

---

## <a name="19"></a>19. 欧盟初创企业失败源于媒体拒绝炒作 
<small>🔗 [twitter.com](https://twitter.com/RnaudBertrand/status/1925029185052917791): EU startups fail because their press refuses to hype them up</small>


| 🔥: 89 \| 💬: [82](https://news.ycombinator.com/item?id=44049909) \| 🗓️ 2025-05-21


<br />
原文内容因技术问题无法显示（JavaScript未启用），但标题指出**欧盟初创企业**面临困境的核心原因：当地**媒体缺乏宣传造势**，导致它们难以获得关注。相比之下，美国初创企业常借助媒体炒作快速成长。这一现象揭示了**市场环境差异**对初创企业成功的关键影响。

---

## <a name="20"></a>20. 不丹奇妙的可播放邮票传奇（2015年） 
<small>🔗 [thevinylfactory.com](https://thevinylfactory.com/features/the-curious-tale-of-bhutans-playable-record-postage-stamps/): The curious tale of Bhutan's playable record postage stamps (2015)</small>


| 🔥: 89 \| 💬: [6](https://news.ycombinator.com/item?id=44054775) \| 🗓️ 2025-05-21


<br />
1972年，不丹推出全球**首套可播放邮票**，由美国冒险家伯特·托德设计。这套7枚邮票采用微型黑胶材质，以33 1⁄3转速录制了不丹国歌、民间故事等，可用唱机播放。最初被集邮界视为廉价新奇品，但近年因**黑胶收藏家追捧**，价格飙升至300英镑以上。托德还设计了3D、丝绸等创新邮票，而**CD-ROM邮票**则由其女儿延续传奇。这套邮票现仍可在eBay偶遇，成为跨界收藏的珍品。

---

## <a name="21"></a>21. Rocky Linux 10将正式支持RISC-V架构 
<small>🔗 [rockylinux.org](https://rockylinux.org/news/rockylinux-support-for-riscv): Rocky Linux 10 Will Support RISC-V</small>


| 🔥: 89 \| 💬: [28](https://news.ycombinator.com/item?id=44056104) \| 🗓️ 2025-05-21


<br />
Rocky Linux 10宣布将**官方支持RISC-V**架构，提供riscv64gc版本，兼容StarFive VisionFive 2、QEMU及SiFive HiFive Premier P550等平台。该版本基于**上游优先策略**，与Fedora社区紧密合作，推动RISC-V生态发展。虽然RISC-V被列为**替代架构**，但构建失败不会影响其他架构的发布。目前VisionFive 2和QEMU已获完整支持，P550则需依赖厂商内核。社区鼓励开发者参与，共同完善这一跨架构开源生态。

---

## <a name="22"></a>22. 利用嵌入向量的普适几何结构 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2505.12540): Harnessing the Universal Geometry of Embeddings</small>


| 🔥: 86 \| 💬: [36](https://news.ycombinator.com/item?id=44054425) \| 🗓️ 2025-05-21


<br />
该研究提出了一种**无需配对数据**的文本嵌入向量跨空间转换方法，首次实现了不同架构、参数量及训练数据的模型间嵌入向量的无监督翻译。通过将任意嵌入映射到**通用潜在表示空间**（基于柏拉图表示假说），该方法能保持几何结构的高余弦相似度。研究同时警示，这种能力可能威胁向量数据库安全——攻击者仅通过嵌入向量即可推断原始文档的敏感信息，如分类与属性特征。

---

## <a name="23"></a>23. Lune：独立的Luau运行时环境 
<small>🔗 [github.com](https://github.com/lune-org/lune): Lune: Standalone Luau Runtime</small>


| 🔥: 67 \| 💬: [38](https://news.ycombinator.com/item?id=44052106) \| 🗓️ 2025-05-21


<br />
Lune是一个**独立的Luau运行时**，类似Node.js或Deno，专为Luau语言设计。它采用**Rust编写**，注重速度与安全性，提供异步API、文件系统、网络等核心功能，并兼容Roblox开发环境。内置**任务调度器**和文档支持，适合脚本编写与工具开发。体积小巧（约5MB），但功能强大，强调代码可读性而非简洁性。不支持完整Roblox游戏运行，定位为高效开发工具。

---

## <a name="24"></a>24. 让抽签决定我们的政府？重温雅典民主的现代启示 
<small>🔗 [thewalrus.ca](https://thewalrus.ca/why-we-should-let-a-lottery-decide-our-government/): We Should Let a Lottery Decide Our Government (2019)</small>


| 🔥: 56 \| 💬: [74](https://news.ycombinator.com/item?id=44051162) \| 🗓️ 2025-05-21


<br />
本文探讨了**抽签制**（sortition）在古希腊雅典民主中的应用，并分析其在现代政治中的潜在价值。雅典通过随机选择公民参与议会和法庭，体现**轮换治理**原则，避免选举导致的精英垄断。如今，西方学者提出抽签制可解决代议制民主的弊端：当前政坛普遍由白人、富裕男性主导，难以反映多元群体诉求。加拿大不列颠哥伦比亚省曾试行**公民大会**随机遴选民众讨论选举改革，证明普通人具备理性决策能力，但最终因公众沟通不足未能通过公投。支持者认为抽签制能减少金钱政治干扰，提升政策包容性；批评者则指出其存在问责缺失、少数群体代表不充分等问题。部分学者建议设立"抽签议院"与选举议院并存，平衡民主与效率。

---

## <a name="25"></a>25. 为什么基于属性的测试能发现单元测试遗漏的缺陷（2021） 
<small>🔗 [buttondown.com](https://buttondown.com/hillelwayne/archive/why-property-testing-finds-bugs-unit-testing-does/): Why Property Testing Finds Bugs Unit Testing Does Not (2021)</small>


| 🔥: 55 \| 💬: [86](https://news.ycombinator.com/item?id=44050437) \| 🗓️ 2025-05-21


<br />
本文探讨了**基于属性的测试（PBT）**与单元测试的核心差异。PBT通过随机生成输入并验证代码的通用属性（如加法交换律），能覆盖更复杂的边界条件组合。作者以几何空间类比：单输入函数如直线易测，但多输入函数形成高维空间，**组合爆炸**导致人工难以穷举边界（如`x=INT_MAX`且`y=INT_MIN`）。尽管常见PBT示例（如列表反转）过于简单，实际价值在于处理**复杂输入结构**（如嵌套字典）时暴露隐性缺陷。批评者认为手动单元测试足以覆盖分区和边界错误，但作者强调PBT在**非直观边缘场景**中的不可替代性。

---
