---
layout: page
title: 勒西科技日报 - 2025年01月12日
date: 2025-01-12 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 坏苹果，但它是 6,500 个在 Vim 中搜索的正则表达式；
1. uv 的杀手锏：轻松创建临时环境；
1. 后门中的后门——又一个20美元的域名，更多政府被入侵；
1. AI 创始人将学到苦涩的教训；
1. 我删除了我的社交媒体账户；

以上是今天的前五条黑科技新闻标题。

总共20条，具体内容您往下读...


![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 坏苹果，但它是 6,500 个在 Vim 中搜索的正则表达式 
<small>🔗 [eieio.games](https://eieio.games/blog/bad-apple-with-regex-in-vim/): Bad Apple but it's 6,500 regexes that I search for in Vim</small>


| 🔥🔥: 443 \| 💬: [47](https://news.ycombinator.com/item?id=42674116) \| 🗓️ 2025-01-12


<br />
作者通过将《坏苹果》音乐视频的每一帧转换为 **120x90** 的二进制图像，并使用 **Vim 的正则表达式搜索功能** 在终端中逐帧显示。通过将图像分解为多个矩形，并利用 Vim 的搜索模式匹配特定行和列，实现了在 Vim 中播放视频的效果。虽然算法在某些情况下表现不佳，但通过组合多种简单算法，最终实现了流畅的播放效果。

---

## <a name="2"></a>2. uv 的杀手锏：轻松创建临时环境 
<small>🔗 [valatka.dev](https://valatka.dev/2025/01/12/on-killer-uv-feature.html): Uv's killer feature is making ad-hoc environments easy</small>


| 🔥🔥: 369 \| 💬: [280](https://news.ycombinator.com/item?id=42676432) \| 🗓️ 2025-01-12


<br />
uv 的核心优势并非性能或与 Python 的严格对齐，而是其**简化临时环境创建**的能力。传统方式需要多步操作（如创建虚拟环境、安装依赖等），而 uv 只需一条命令即可完成，如 `uv run --python 3.12 --with pandas python`。这种方式不仅**快速高效**，还不会留下任何痕迹，非常适合临时脚本开发。

---

## <a name="3"></a>3. 后门中的后门——又一个20美元的域名，更多政府被入侵 
<small>🔗 [labs.watchtowr.com](https://labs.watchtowr.com/more-governments-backdoors-in-your-backdoors/): Backdooring Your Backdoors – Another $20 Domain, More Governments</small>


| 🔥🔥: 327 \| 💬: [26](https://news.ycombinator.com/item?id=42674455) \| 🗓️ 2025-01-12


<br />
在2024年，研究人员通过利用未注册的域名，成功绕过了TLS/SSL证书颁发机构（CA）的域名所有权验证流程，从而能够为任何.MOBI域名签发有效的TLS/SSL证书。这一发现促使Google推动CAB论坛彻底弃用WHOIS进行所有权验证。此次，研究人员再次利用**废弃的基础设施**和过期域名，通过“自动化大规模入侵”技术，成功接管了数千个系统中的**后门**。这些后门原本依赖于已废弃的基础设施或过期域名，研究人员通过注册这些域名，获得了对这些系统的控制权。目前已发现超过4000个活跃后门，涉及多个**政府**、大学等敏感系统。

---

## <a name="4"></a>4. AI 创始人将学到苦涩的教训 
<small>🔗 [lukaspetersson.com](https://lukaspetersson.com/blog/2025/bitter-vertical/): AI founders will learn the bitter lesson</small>


| 🔥🔥: 312 \| 💬: [251](https://news.ycombinator.com/item?id=42672790) \| 🗓️ 2025-01-12


<br />
AI 历史表明，**通用方法**总是胜出。当前 AI 应用领域的创始人重复了研究者过去的错误：过度依赖领域知识和工程优化，而忽视了**计算能力**的扩展。随着 AI 模型的进步，**工程努力的价值将逐渐减少**，通用 AI 应用将主导市场。创始人应避免依赖当前模型的局限性，而是为未来更强大的模型做好准备。

---

## <a name="5"></a>5. 我删除了我的社交媒体账户 
<small>🔗 [asylumsquare.com](https://asylumsquare.com/backstage/2025-01-12/why-i-deleted-my-social-media-accounts): I deleted my social media accounts</small>


| 🔥🔥: 239 \| 💬: [247](https://news.ycombinator.com/item?id=42677587) \| 🗓️ 2025-01-12


<br />
作者因**Meta放弃事实核查**、**马斯克与极右翼人士互动**等事件，决定删除所有社交媒体账户。他认为**社交媒体平台道德滑坡**，利用心理技巧让人沉迷，对青少年尤其有害。尽管失去推广渠道和粉丝，他仍选择退出，并呼吁大家反思是否继续支持这些平台。删除过程繁琐，但最终让他意识到社交媒体对生活的控制。未来可能回归博客写作。

---

## <a name="6"></a>6. Tabby：自托管的AI编程助手 
<small>🔗 [github.com](https://github.com/TabbyML/tabby): Tabby: Self-hosted AI coding assistant</small>


| 🔥🔥: 215 \| 💬: [68](https://news.ycombinator.com/item?id=42675725) \| 🗓️ 2025-01-12


<br />
Tabby是一款**自托管的AI编程助手**，提供开源且本地化的替代方案，类似于GitHub Copilot。它支持**消费级GPU**，无需依赖数据库或云服务，并具备**OpenAPI接口**，易于与现有基础设施集成。Tabby还支持多种IDE插件，如VSCode、Vim和IntelliJ，并持续更新功能，如代码补全、团队管理和企业级升级。

---

## <a name="7"></a>7. Mullenweg解散WordPress可持续发展团队，引发强烈反对 
<small>🔗 [therepository.email](https://www.therepository.email/mullenweg-shuts-down-wordpress-sustainability-team-igniting-backlash): Mullenweg Shuts Down WordPress Sustainability Team, Igniting Backlash</small>


| 🔥🔥: 201 \| 💬: [153](https://news.ycombinator.com/item?id=42672675) \| 🗓️ 2025-01-12


<br />
WordPress联合创始人Matt Mullenweg突然解散了**可持续发展团队**，引发社区强烈反弹。团队代表Thijs Buijs因Mullenweg在Reddit上制造“2025年WordPress戏剧”的帖子而辞职，随后Mullenweg宣布解散团队，称其“未达预期”。此举被知名科技记者Kara Swisher批评为“**极其恶劣的行为**”，并引发广泛批评。团队曾发布《可持续活动手册》并开发插件，致力于推动WordPress的**社会、经济和环境可持续性**。

---

## <a name="8"></a>8. Rust 不仅仅是性能的亮点 
<small>🔗 [ntietz.com](https://ntietz.com/blog/great-things-about-rust-beyond-perf/): Great things about Rust that aren't just performance</small>


| 🔥🔥: 184 \| 💬: [209](https://news.ycombinator.com/item?id=42675219) \| 🗓️ 2025-01-12


<br />
Rust 不仅以高性能著称，其**类型系统**的**表达力**和**安全性**也令人印象深刻。通过枚举、结构体和特质，开发者可以将设计直接体现在类型中，同时编译器确保类型正确使用。Rust 还通过**借用检查器**有效防止数据竞争，使并发编程更加安全。此外，Rust 的**编译器错误提示**非常友好，提供了详细的修复建议。总的来说，Rust 不仅高效，还让编程变得有趣且可靠。

---

## <a name="9"></a>9. Show HN: 《毁灭战士》(1993) 嵌入 PDF 文件 
<small>🔗 [doompdf.pages.dev](https://doompdf.pages.dev/doom.pdf): Show HN: Doom (1993) in a PDF</small>


| 🔥🔥: 183 \| 💬: [33](https://news.ycombinator.com/item?id=42678754) \| 🗓️ 2025-01-12


<br />
该内容展示了一个将经典游戏《毁灭战士》(1993) 嵌入 PDF 文件的项目。通过 **JavaScript 代码** 和 **PDF 表单** 的交互，用户可以在 PDF 中直接运行游戏。项目利用了 **Emscripten** 将游戏编译为 WebAssembly，并嵌入到 PDF 中，展示了 PDF 文件的强大功能。

---

## <a name="10"></a>10. 我在Linux控制台度过的18年 
<small>🔗 [eugene-andrienko.com](https://eugene-andrienko.com/en/it/2024/01/02/life-in-console): I spent 18 years in the Linux console</small>


| 🔥🔥: 180 \| 💬: [126](https://news.ycombinator.com/item?id=42674153) \| 🗓️ 2025-01-12


<br />
本文讲述了作者从早期在无网络环境下学习**Linux**的经历，到后来在大学和工作中的成长。作者通过书籍、命令行和源代码自学，掌握了系统编程和**正则表达式**等技能，并逐渐形成了对**控制台工具**的依赖。这段经历不仅塑造了他的技术能力，也让他对Linux系统有了深刻的理解。

---

## <a name="11"></a>11. Mac Mini G4 – 经典 Macintosh 的最佳复古游戏机？ 
<small>🔗 [xtof.info](https://www.xtof.info/MacMiniG4-the-best-classic-macintosh-for-retrogaming.html): Mac Mini G4 – The best « classic » Macintosh for retro-gaming?</small>


| 🔥🔥: 177 \| 💬: [93](https://news.ycombinator.com/item?id=42674385) \| 🗓️ 2025-01-12


<br />
Mac Mini G4 是苹果最后一款搭载 **PowerPC G4** 处理器的电脑，因其小巧的体积和强大的性能，成为运行 2000 年前经典 Mac 游戏的理想选择。通过社区改造，它支持 **Mac OS 9**，使其能够流畅运行大量老游戏。G4 处理器的 **Altivec** 技术进一步提升了多媒体处理能力，使其在复古游戏领域表现卓越。

---

## <a name="12"></a>12. 让马里布燃烧的理由（1995） 
<small>🔗 [longreads.com](https://longreads.com/2018/12/04/the-case-for-letting-malibu-burn/): The case for letting Malibu burn (1995)</small>


| 🔥🔥: 148 \| 💬: [185](https://news.ycombinator.com/item?id=42675274) \| 🗓️ 2025-01-12


<br />
本文探讨了洛杉矶贫民区与马里布海岸在火灾问题上的对比。**马里布**作为北美野火最频繁的地区，其火灾与自然生态息息相关，而贫民区的火灾则多因人为疏忽。尽管**富人区**享有大量资源应对火灾，但专家认为开发马里布是徒劳的，因为火灾是其生态的一部分。相比之下，贫民区的火灾本可通过加强建筑安全来避免。

---

## <a name="13"></a>13. 扎克伯格批准在LibGen上训练Llama 
<small>🔗 [storage.courtlistener.com](https://storage.courtlistener.com/recap/gov.uscourts.cand.415175/gov.uscourts.cand.415175.377.0_1.pdf): Zuckerberg approved training Llama on LibGen [pdf]</small>


| 🔥🔥: 141 \| 💬: [173](https://news.ycombinator.com/item?id=42673628) \| 🗓️ 2025-01-12


<br />
根据内容，**Meta**的CEO马克·扎克伯格批准了使用**LibGen**（一个知名的盗版电子书平台）的数据来训练**Llama**模型。这一决定引发了关于数据来源合法性和道德问题的讨论。尽管LibGen提供了大量免费资源，但其内容的版权问题一直备受争议。

---

## <a name="14"></a>14. 2025年最佳笔具推荐 
<small>🔗 [jetpens.com](https://www.jetpens.com/blog/The-46-Best-Pens-for-2025-Gel-Ballpoint-Rollerball-and-Fountain-Pens/pt/974): Best Pens for 2025</small>


| 🔥🔥: 136 \| 💬: [72](https://news.ycombinator.com/item?id=42676274) \| 🗓️ 2025-01-12


<br />
本文介绍了**JetPens**提供的各类笔具，包括**钢笔**、**圆珠笔**、**凝胶笔**、**多色笔**等，涵盖多种品牌和用途。还推荐了**2025年最佳钢笔**、**铅笔**和**文具配件**，适合不同需求的用户。文章还提供了详细的购买指南和使用建议，帮助用户选择最适合的笔具。

---

## <a name="15"></a>15. Qubes OS：一个相对安全的操作系统 
<small>🔗 [qubes-os.org](https://www.qubes-os.org/): Qubes OS: A reasonably secure operating system</small>


| 🔥🔥: 133 \| 💬: [60](https://news.ycombinator.com/item?id=42677608) \| 🗓️ 2025-01-12


<br />
Qubes OS 是一个基于 **Xen 虚拟机**的操作系统，提供**强大的隔离功能**，确保不同任务之间的安全性。它支持多种操作系统环境，并集成了 **Whonix** 以实现匿名上网。Qubes OS 被广泛用于高安全需求场景，如记者工作站和远程服务器访问。

---

## <a name="16"></a>16. 重归野性自我 
<small>🔗 [worldsensorium.com](https://worldsensorium.com/rewilding-the-self/): Rewilding the Self</small>


| 🔥🔥: 129 \| 💬: [54](https://news.ycombinator.com/item?id=42672758) \| 🗓️ 2025-01-12


<br />
人类与自然的联系正在逐渐消失，许多人甚至忽视了自然对生存的重要性。**重归野性**不仅指恢复生态系统的自然状态，也意味着重新连接人与自然的感官体验。通过沉浸于自然、种植本地植物或参与城市园艺，我们可以重新培养对生态的感知与责任感。**重归野性**呼吁集体行动，保护生物多样性，重建与自然的和谐关系。

---

## <a name="17"></a>17. 怀念20年前“友好”网络世界的错误 
<small>🔗 [english.elpais.com](https://english.elpais.com/lifestyle/2025-01-07/the-internet-hasnt-made-us-bad-we-were-already-like-that-the-mistake-of-yearning-for-the-friendly-online-world-of-20-years-ago.html): The mistake of yearning for the 'friendly' online world of 20 years ago</small>


| 🔥🔥: 120 \| 💬: [138](https://news.ycombinator.com/item?id=42673596) \| 🗓️ 2025-01-12


<br />
近年来，Y2K美学和**Flow 2K**复兴引发了对20年前互联网的怀旧情绪，许多人认为那时的网络更友好、有趣。然而，这种怀旧忽略了早期网络中的**性别歧视**和**种族主义**问题。尽管今天的互联网被大公司主导，充满仇恨和数据剥削，但仍有希望。关键在于**数字主权**和个体行动，而非沉溺于怀旧或技术恐惧。

---

## <a name="18"></a>18. 我永远不需要再买新电脑了 
<small>🔗 [82mhz.net](https://82mhz.net/posts/2025/01/i-will-never-need-to-buy-a-new-computer-again/): I will never need to buy a new computer again</small>


| 🔥🔥: 118 \| 💬: [152](https://news.ycombinator.com/item?id=42674888) \| 🗓️ 2025-01-12


<br />
作者回顾了90年代和2000年代电脑硬件飞速发展的时代，指出如今**硬件性能**已足够强大，普通用户不再需要频繁升级。他以自己2011年购买的i5 2500k和2019年升级的Ryzen 5 3600为例，说明即使旧设备仍能满足需求。**未来**，他计划继续使用现有设备，直到损坏或无法满足需求时，再考虑从二手市场购买旧硬件。

---

## <a name="19"></a>19. 从ASCII到ASIC：将donut.c移植到一小片硅片上 
<small>🔗 [a1k0n.net](https://www.a1k0n.net/2025/01/10/tiny-tapeout-donut.html): From ASCII to ASIC: Porting donut.c to a tiny slice of silicon</small>


| 🔥🔥: 116 \| 💬: [18](https://news.ycombinator.com/item?id=42675208) \| 🗓️ 2025-01-12


<br />
作者将经典的**donut.c**程序从ASCII艺术演变为硬件实现，使用**CORDIC算法**和**移位加法**在硅片上实时渲染3D甜甜圈。该设计通过**Tiny Tapeout 8**项目制造，仅占用0.8%的芯片面积，展示了如何在极简硬件上实现复杂图形渲染。

---

## <a name="20"></a>20. 如果我们拥有最好的产品工程组织，它会是什么样子？ 
<small>🔗 [jamesshore.com](https://www.jamesshore.com/v2/blog/2025/the-best-product-engineering-org-in-the-world): If we had the best product engineering organization, what would it look like?</small>


| 🔥🔥: 115 \| 💬: [61](https://news.ycombinator.com/item?id=42676123) \| 🗓️ 2025-01-12


<br />
在2025年东京Scrum Gathering会议上，演讲者分享了如何应对CEO要求衡量工程生产力的挑战。通过团队讨论，他们定义了六个关键领域：**人员**、**内部质量**、**用户喜爱度**、**可见性**、**敏捷性**和**盈利能力**。这些领域旨在推动持续改进，而非追求完美。演讲者强调了团队协作、**同行领导力**和**所有权**的重要性，并分享了如何通过改变组织文化来实现这些目标。

---
