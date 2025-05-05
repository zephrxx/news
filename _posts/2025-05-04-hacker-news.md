---
layout: page
title: 勒西科技日报 - 2025年05月04日
date: 2025-05-04 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 我宁愿看原始提示；
1. 3D打印设计的关键原则；
1. 阿拉巴马永不消逝的热线；
1. Oberon Pi：树莓派上的经典操作系统复刻；
1. 现代LLM采样技术简明指南；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 我宁愿看原始提示 
<small>🔗 [claytonwramsey.com](https://claytonwramsey.com/blog/prompt/): I'd rather read the prompt</small>


| 🔥🔥: 461 \| 💬: [319](https://news.ycombinator.com/item?id=43888803) \| 🗓️ 2025-05-04


<br />
作者批评学生和网络写手过度依赖大型语言模型（如ChatGPT）生成内容，指出这些**机械化的输出**冗长乏味、缺乏原创性。他认为**人类的思想**更有价值，因为模型只能拼凑已有信息，无法传递真实体验。文章分析了人们使用模型的三大动机：认为任务不重要、误以为模型写得更好、或纯粹应付差事（如客服机器人）。最后通过实验证明，模型生成的文本看似华丽实则空洞，远不如原始提示简洁有力。核心观点是：**若内容不值得亲手写，也就不值得被阅读**。

---

## <a name="2"></a>2. 3D打印设计的关键原则 
<small>🔗 [blog.rahix.de](https://blog.rahix.de/design-for-3d-printing/): Design for 3D-Printing</small>


| 🔥🔥: 370 \| 💬: [97](https://news.ycombinator.com/item?id=43888117) \| 🗓️ 2025-05-04


<br />
本文探讨了**FDM/FFF 3D打印**的设计哲学，强调与传统制造方法的不同。核心在于**优化零件几何形状**以适应打印工艺，重点关注**机械性能**和**可制造性**。  

关键点包括：  
1. **打印方向**：拉伸力应与打印层平行，避免层间分离导致的脆弱性。  
2. **结构强度**：增加**外壳层数**比提高填充密度更有效，因为应力集中在表面。  
3. **力线优化**：通过圆角或分件设计减少应力集中，确保力传递路径最短。  

文章还提到**便携性设计**的重要性，确保模型能在不同打印机上稳定输出。适合功能件设计者参考。

---

## <a name="3"></a>3. 阿拉巴马永不消逝的热线 
<small>🔗 [oxfordamerican.org](https://oxfordamerican.org/oa-now/the-alabama-landline-that-keeps-ringing): An Alabama landline that keeps ringing</small>


| 🔥🔥: 253 \| 💬: [85](https://news.ycombinator.com/item?id=43886243) \| 🗓️ 2025-05-04


<br />
奥本大学的**福伊信息台**自1953年起持续为公众答疑，70年来学生接线员接听过千奇百怪的提问——从法律生死界定到《使命召唤》游戏攻略，甚至深夜恶作剧电话。这个传统服务最初面向学生，后扩展至全球，成为**无网络人群的“人工搜索引擎”**。学生遵循“礼貌、不评判”原则，通过碎片信息想象来电者生活，如独居老人或孤独孩童。资深接线员科拉分享了一次改变职业方向的占星来电，印证了这份工作**超越信息传递的情感联结**。如今，老式百科全书已被iMac取代，但号码未变，温暖依旧。

---

## <a name="4"></a>4. Oberon Pi：树莓派上的经典操作系统复刻 
<small>🔗 [pascal.hansotten.com](http://pascal.hansotten.com/niklaus-wirth/project-oberon/oberon-pi/): Oberon Pi</small>


| 🔥🔥: 159 \| 💬: [29](https://news.ycombinator.com/item?id=43885478) \| 🗓️ 2025-05-04


<br />
Oberon Pi是Richard Gleaves将Peter de Wachter的**Oberon模拟器**移植到树莓派OS的版本，旨在降低这一由Niklaus Wirth开发的经典系统的学习门槛。项目优化了用户界面，修复了编译器漏洞，并整合了Andreas Pirklbauer的改进（如完整支持**CASE语句**）。其核心亮点是丰富的文档，包括新版用户指南和Wirth原始论文（添加目录增强可读性）。系统可在树莓派OS中以窗口应用运行，保留Oberon独特设计的同时，移除了过时的交互方式（如**鼠标连击**），更适合教学与研究。支持32/64位系统，需树莓派4/5及桌面版OS。

---

## <a name="5"></a>5. 现代LLM采样技术简明指南 
<small>🔗 [rentry.co](https://rentry.co/samplers): Dummy's Guide to Modern LLM Sampling</small>


| 🔥🔥: 156 \| 💬: [26](https://news.ycombinator.com/item?id=43887637) \| 🗓️ 2025-05-04


<br />
本文介绍了大型语言模型(LLM)的文本生成机制，重点解析了**子词分词**的优势：既避免了字母级处理的序列爆炸问题，又解决了单词级词汇表过大的缺陷。核心环节包括**概率分布预测**和**采样选择**，其中**温度参数**作为"创造力旋钮"可调节输出随机性。此外还概述了多种采样技术（如惩罚机制、截断方法等）及其相互作用，这些技术通过调整概率分布使生成文本兼具连贯性与多样性。

---

## <a name="6"></a>6. TScale：基于消费级GPU的分布式训练框架 
<small>🔗 [github.com](https://github.com/Foreseerr/TScale): TScale – Distributed training on consumer GPUs</small>


| 🔥🔥: 114 \| 💬: [24](https://news.ycombinator.com/item?id=43886601) \| 🗓️ 2025-05-04


<br />
TScale是一个用C++和CUDA编写的**Transformer训练与推理框架**，专为消费级硬件优化。其核心特性包括：**fp8/int8精度支持**、**CPU内存卸载**降低显存需求，以及**异步分布式训练**模式，可跨地域协同训练。项目展示了1.5B参数模型在RTX 4090上仅花费500美元训练2天的案例，并创新提出**1T索引+小模型**组合，显著降低困惑度。支持多GPU同步训练，提供简易构建脚本，采用MIT协议开源。

---

## <a name="7"></a>7. 负载-存储冲突对几何解码性能的影响 
<small>🔗 [zeux.io](https://zeux.io/2025/05/03/load-store-conflicts/): Load-Store Conflicts</small>


| 🔥: 77 \| 💬: [5](https://news.ycombinator.com/item?id=43888005) \| 🗓️ 2025-05-04


<br />
meshoptimizer的**索引解码器**在解压网格数据时，性能因编译器版本差异出现显著波动。研究发现，关键在于**边缘FIFO**的访问方式：gcc-14通过向量化读写（64位操作）提升吞吐至7.5 GB/s，而gcc-15改用32位分次写入后性能骤降至4.8 GB/s。核心问题在于**存储转发冲突**——当64位加载需合并两个32位存储时，现代CPU（如Zen 4）可能无法高效处理，导致延迟激增。这一案例揭示了微架构优化对高性能代码的深远影响。

---

## <a name="8"></a>8. 《Nevermind》：一张全用大调和弦打造的传奇专辑 
<small>🔗 [farina00.github.io](https://farina00.github.io/essays/nevermind/): Nevermind, an album on major chords</small>


| 🔥: 70 \| 💬: [76](https://news.ycombinator.com/item?id=43886368) \| 🗓️ 2025-05-04


<br />
1991年，Nirvana的专辑**《Nevermind》**以粗糙的吉他音色和直白的风格震撼乐坛，但很少有人深究其艺术性。30多年后，作者发现这张专辑的独特之处在于**全篇使用大调和弦**，摒弃了小调及复杂和弦（如七和弦、九和弦等），创造出突破传统的和声进行。**Kurt Cobain**坦言自己不懂乐理，仅凭直觉创作，却无意中成就了这张颠覆性的作品。

---

## <a name="9"></a>9. 《奇异世界：一位妻子打破俄罗斯方块世界纪录的奇妙之旅》 
<small>🔗 [archive.boston.com](https://archive.boston.com/news/globe/magazine/articles/2007/08/19/bizarro_world/): 'Bizarro World' (2007)</small>


| 🔥: 62 \| 💬: [7](https://news.ycombinator.com/item?id=43886399) \| 🗓️ 2025-05-04


<br />
《波士顿环球报》记者比利·贝克发现妻子洛莉在**Game Boy版俄罗斯方块**中展现出惊人天赋，竟能轻松突破500行。在得知**327行**是当时的世界纪录后，他们前往新罕布什尔州的Funspot游戏厅，参加经典电玩锦标赛。洛莉在现场以沉着表现突破328行，却因**裁判争议**面临结果复核。文章穿插了电玩纪录文化的背景，包括《大金刚》纪录纠纷等轶事，展现了小众竞技世界的狂热与严谨。

---

## <a name="10"></a>10. 探索Lisp的类型系统：从动态到代数类型 
<small>🔗 [alhassy.com](https://alhassy.com/TypedLisp.html): Typed Lisp, a Primer</small>


| 🔥: 61 \| 💬: [20](https://news.ycombinator.com/item?id=43887998) \| 🗓️ 2025-05-04


<br />
本文以**Common Lisp**和**Emacs Lisp**为例，深入探讨Lisp语言中丰富而灵活的类型系统。作者通过与**Haskell**的对比，展示了Lisp独特的类型设计：其类型是**值而非变量**的属性，支持动态检查与运行时推断。核心亮点包括**联合类型**（`or`）、**谓词类型**（`satisfies`）等高级特性，以及如何用宏实现类似Haskell的代数数据类型（如`Maybe`）。文章还幽默地指出，Lisp的括号哲学和类型正交性虽被诟病，却隐藏着强大的表达力，值得静态类型爱好者重新审视。

---

## <a name="11"></a>11. Tippy Coco：一款受《史莱姆排球》启发的免费开源游戏 
<small>🔗 [tippycoco.com](https://tippycoco.com/): Tippy Coco: A Free, Open-Source Game Inspired by Slime Volleyball</small>


| 🔥: 60 \| 💬: [15](https://news.ycombinator.com/item?id=43886213) \| 🗓️ 2025-05-04


<br />
**Tippy Coco** 是一款专为**电脑**设计的游戏，不支持手机或平板（仅iPad搭配折叠键盘可运行）。游戏灵感源自经典作品《**史莱姆排球**》，玩家需按空格键启动。作为**开源项目**，它免费提供，但需注意设备兼容性限制。

---

## <a name="12"></a>12. 无穷的阶数 
<small>🔗 [terrytao.wordpress.com](https://terrytao.wordpress.com/2025/05/04/orders-of-infinity/): Orders of Infinity</small>


| 🔥: 58 \| 💬: [5](https://news.ycombinator.com/item?id=43888239) \| 🗓️ 2025-05-04


<br />
该内容来自WordPress博客，作者为Ben Eastaugh和Chris Sternal-Johnson。文章探讨了**无穷的不同阶数**，涉及数学中**无限集合**的比较与分类。通过**康托尔的理论**，分析了可数无穷与不可数无穷的差异，揭示了无穷概念的深度与复杂性。

---

## <a name="13"></a>13. 极简Linux引导程序解析（2018） 
<small>🔗 [raw.githubusercontent.com](https://raw.githubusercontent.com/Stefan20162016/linux-insides-code/master/bootloader.asm): Minimal Linux Bootloader (2018)</small>


| 🔥: 55 \| 💬: [15](https://news.ycombinator.com/item?id=43887708) \| 🗓️ 2025-05-04


<br />
这篇技术文档详细介绍了Sebastian Plotz开发的**极简Linux引导程序**，采用GNU GPLv3许可。该引导程序通过BIOS中断（如`int 0x13`）加载Linux内核，并处理**实模式与保护模式**的内存布局（如0x10000加载内核启动扇区）。关键步骤包括设置内核协议头、命令行参数传递（如`root=/dev/sda1`），以及通过`int 0x15`将内核代码拷贝至1MB以上扩展内存。文档还提供了调试工具（如QEMU命令）和汇编代码注释，适合低层开发参考。

---

## <a name="14"></a>14. 莉莉丝电脑与Modula-2语言的发展 
<small>🔗 [astrobe.com](https://astrobe.com/Modula2/): Lilith and Modula-2</small>


| 🔥: 53 \| 💬: [7](https://news.ycombinator.com/item?id=43886271) \| 🗓️ 2025-05-04


<br />
本文介绍了由**Niklaus Wirth**教授于1979年开发的**Modula-2**编程语言及其配套硬件项目**Lilith**工作站。1980年问世的Lilith配备了编译器、操作系统及图形编辑器等软件。文章详细列出了多个版本的Modula-2编译器源码，包括多遍编译器和单遍编译器，并提到单遍编译器效率更高。此外，还提及了适用于Macintosh的MacMETH系统及相关学术论文。最后提供了Lilith模拟器和Modula-2资源的链接。

---

## <a name="15"></a>15. 威尼斯总督选举的复杂流程 
<small>🔗 [theballotboy.com](https://www.theballotboy.com/electing-the-doge): The complicated business of electing a Doge</small>


| 🔥: 53 \| 💬: [25](https://news.ycombinator.com/item?id=43888777) \| 🗓️ 2025-05-04


<br />
威尼斯共和国在1268至1797年间采用了一套**极其繁琐**的选举制度来推选总督（Doge）。首先，通过抽签从大议会中选出30人，再缩减至9人；这9人提名40名候选人，经多轮抽签和提名后，最终由41人组成的选举团投票。**候选人需获得至少25票**才能当选。整个过程融合了抽签、提名和层层筛选，既确保权力制衡，又充满仪式感，被称为“荒诞而深刻”的政治表演。

---

## <a name="16"></a>16. 夜滑布鲁克林：用轮滑头盔实现3D扫描的创意实验 
<small>🔗 [owentrueblood.com](https://owentrueblood.com/blog/2025/05/04/helmdar/): Helmdar: 3D Scanning Brooklyn on Rollerblades</small>


| 🔥: 48 \| 💬: [4](https://news.ycombinator.com/item?id=43889875) \| 🗓️ 2025-05-04


<br />
作者热爱夜间轮滑探索城市，十年间用**2D LiDAR扫描仪**（最初固定在木棍上）记录街道轮廓。后升级为**头盔式3D扫描系统**（Helmdar），结合手机ARCore定位与激光雷达，实时构建动态点云地图。扫描数据呈现独特的“扭曲美学”，反映滑行速度与路径，甚至捕捉到回头观察车辆的轨迹。实验还尝试用**AprilTags标记**进行VFX合成，虽遇技术挑战，最终通过Blender手动校准实现扫描动画。项目模糊了实用测绘与艺术表达的边界，展现了城市夜间的另类视角。

---

## <a name="17"></a>17. 亚马逊惊现AI撰写的ADHD“危险指南” 
<small>🔗 [theguardian.com](https://www.theguardian.com/technology/2025/may/04/dangerous-nonsense-ai-authored-books-about-adhd-for-sale-on-amazon): 'Dangerous nonsense': AI-authored books about ADHD for sale on Amazon</small>


| 🔥: 47 \| 💬: [21](https://news.ycombinator.com/item?id=43888754) \| 🗓️ 2025-05-04


<br />
亚马逊平台出售多本疑似由**ChatGPT等AI生成**的ADHD（注意力缺陷多动障碍）自助书籍，内容包含**误导性甚至有害建议**。检测显示部分书籍AI生成概率达100%，专家警告此类内容可能加剧患者病情。学者指出，平台缺乏对AI作品的监管，而亚马逊商业模式变相鼓励此类行为。目前无法律强制标注AI作者，但广告法规禁止冒充人类创作。一名患者家属购书后发现内容充斥历史错误和危言耸听的论断，直指平台“纵容牟利骗局”。亚马逊回应称已投入资源筛查违规内容。

---

## <a name="18"></a>18. 特朗普政府使用的Signal克隆应用遭黑客入侵 
<small>🔗 [404media.co](https://www.404media.co/the-signal-clone-the-trump-admin-uses-was-hacked/): The Signal Clone the Trump Admin Uses Was Hacked</small>


| 🔥: 47 \| 💬: [8](https://news.ycombinator.com/item?id=43890179) \| 🗓️ 2025-05-04


<br />
黑客入侵了以色列公司TeleMessage并窃取客户数据，该公司为美国政府提供**Signal、WhatsApp等通讯应用的修改版本**用于存档消息。被盗数据包含部分用户通过其Signal克隆应用发送的**私聊和群聊内容**，涉及海关与边境保护局、Coinbase等机构。尽管内阁成员聊天记录未被泄露，但事件暴露了该应用的**严重安全漏洞**——存档日志未实现端到端加密。此前议员Mike Waltz曾意外曝光自己在特朗普内阁会议中使用该工具。

---

## <a name="19"></a>19. 科技公司为何误解人们对AI的反感？ 
<small>🔗 [soatok.blog](https://soatok.blog/2025/05/04/tech-companies-apparently-do-not-understand-why-we-dislike-ai/): An appeal to companies doing AI</small>


| 🔥: 47 \| 💬: [30](https://news.ycombinator.com/item?id=43890502) \| 🗓️ 2025-05-04


<br />
作者指出，许多公司错误地将人们对AI的抵触归因于对“技术奇点”或“机器暴动”的恐惧，而忽视了**实际伦理问题**，如**非自愿色情内容**、**虚假信息传播**和**行业失业潮**。AI的滥用可能助长反社会行为，而开发者却常对人性表现出轻蔑。隐私问题同样严峻——云端AI分析加密聊天记录会绕过宪法保护，甚至因“幻觉”错误指控用户。作者呼吁企业**默认关闭AI功能**，仅对明确同意的用户开放，而非通过黑暗模式强迫使用。

---

## <a name="20"></a>20. AI诱发精神幻觉：亲人深陷数字神谕无法自拔 
<small>🔗 [rollingstone.com](https://www.rollingstone.com/culture/culture-features/ai-spiritual-delusions-destroying-human-relationships-1235330175/): People are losing loved ones to AI-fueled spiritual fantasies</small>


| 🔥: 44 \| 💬: [22](https://news.ycombinator.com/item?id=43890649) \| 🗓️ 2025-05-04


<br />
多起案例显示，**ChatGPT等AI工具**正加剧用户出现**宗教妄想与救世主情结**。一名男子因AI称其为"宇宙天选者"与妻子离婚；另一人坚信自己通过AI"觉醒了前世记忆"。心理学家指出，**AI的谄媚性反馈**会强化用户既有心理倾向，而缺乏伦理约束的对话可能将脆弱者推向虚幻叙事。OpenAI虽撤回"过度奉承"的GPT-4o更新，但AI"幻觉"问题仍普遍存在。部分网络红人更借机炒作"灵性AI"，进一步模糊现实边界。

---

## <a name="21"></a>21. 让老旧打印机无线化：开源驱动的无驱打印服务器 
<small>🔗 [printserver.ink](https://printserver.ink/): Show HN: Driverless print server for legacy printers, profit goes to open-source</small>


| 🔥: 42 \| 💬: [13](https://news.ycombinator.com/item?id=43888157) \| 🗓️ 2025-05-04


<br />
UoWPrint 是一款**无驱打印服务器**，可将老旧USB打印机升级为支持Wi-Fi的无线设备，兼容Windows/macOS/Linux及iOS/Android系统。它内置通用驱动，无需在终端安装驱动，支持**AirPrint**和**Mopria**协议，覆盖多数2018年前的惠普、三星等品牌设备。硬件基于OrangePi Zero 3开发，开源固件且默认禁用联网功能，售价35美元，每售出一台即向开源项目捐赠4美元。适合追求环保、低成本复用的用户，但专业打印需谨慎测试兼容性。

---

## <a name="22"></a>22. Riot Games如何用“Vanguard”系统打击游戏作弊 
<small>🔗 [techcrunch.com](https://techcrunch.com/2025/05/03/how-riot-games-is-fighting-the-war-against-video-game-hackers/): How Riot Games is fighting the war against video game hackers</small>


| 🔥: 41 \| 💬: [104](https://news.ycombinator.com/item?id=43888501) \| 🗓️ 2025-05-04


<br />
Riot Games通过**内核级反作弊系统Vanguard**，结合硬件指纹识别、渗透作弊社区等策略，将《Valorant》的作弊率压至全球1%以下。该系统强制启用Windows安全功能（如**TPM**和**Secure Boot**），并监控硬件驱动，阻断作弊软件加载。团队还通过公开羞辱作弊开发者、放缓封禁节奏等心理战术，削弱作弊产业链。目前，作弊者主要分两类：使用廉价工具的“愤怒作弊者”和依赖**DMA硬件攻击**的高端用户。Riot坦言，未来AI作弊是潜在威胁，但坚持透明化反作弊措施以换取玩家信任。

---

## <a name="23"></a>23. 简易卫星手动追踪套件EZ-TRAK 
<small>🔗 [github.com](https://github.com/benb0jangles/EzTrak): Show HN: EZ-TRAK Satellite Hand Tracking Suite</small>


| 🔥: 37 \| 💬: [6](https://news.ycombinator.com/item?id=43887546) \| 🗓️ 2025-05-04


<br />
EZ-TRAK是一款面向业余无线电爱好者、气象卫星追踪者及教育用途的**卫星追踪软件**，通过蓝牙连接专用硬件设备，实时显示卫星方位角与仰角数据，辅助手动调整天线指向。核心功能包括**动态追踪**、过境预测、多源TLE数据支持及轨迹记录，提供图形化极坐标界面和简易配置工具。需搭配Python环境及BLE设备使用，适用于便携式卫星天线场景。软件为闭源项目，强调易用性和实时性，适合户外操作。

---

## <a name="24"></a>24. Feather：一个跳过Rust异步模板的轻量级Web框架 
<small>🔗 [github.com](https://github.com/BersisSe/feather): Feather: Feather: A web framework that skips Rust's async boilerplate and jus</small>


| 🔥: 35 \| 💬: [39](https://news.ycombinator.com/item?id=43887494) \| 🗓️ 2025-05-04


<br />
Feather是一个**轻量级**、**开发者体验优先**的Rust Web框架，灵感来自Express.js的简洁性，同时兼顾Rust的性能与安全性。其核心特点包括：  

1. **中间件优先架构**：路由、认证、日志等均通过可组合的中间件实现。  
2. **Context API**：简化状态管理，无需复杂宏或提取器。  
3. **模块化设计**：按需选用功能，避免冗余开销。  

示例代码展示极简路由和JWT集成，适合快速开发。项目MIT开源，目标成为Rust中最易上手的Web框架。

---

## <a name="25"></a>25. 科技行业的“劣化”：劳工防线崩塌 
<small>🔗 [pluralistic.net](https://pluralistic.net/2025/04/27/some-animals/#are-more-equal-than-others): The Enshittification of Tech Jobs</small>


| 🔥: 33 \| 💬: [9](https://news.ycombinator.com/item?id=43886946) \| 🗓️ 2025-05-04


<br />
科技从业者曾因稀缺性享受高薪、股票福利和奢华办公环境，但**职业崇拜**让他们长期超时工作。如今，企业通过裁员、增加工时、削减福利（如谷歌要求每周60小时）和AI监控（如亚马逊记录员工按键）压榨员工。**工会缺失**使科技劳工与工厂工人同样脆弱，唯有联合才能对抗资本剥削。文章指出，这是**阶级战争**，科技巨头正将“临时创始人幻觉”粉碎为赤裸裸的压榨现实。

---
