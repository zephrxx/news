---
layout: page
title: 勒西科技日报 - 2025年04月22日
date: 2025-04-22 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 举报人指控DOGE窃取美国劳工关系委员会敏感数据；
1. Supabase完成2亿美元D轮融资，估值达20亿美元；
1. Sapphire：基于Rust的macOS包管理器（Homebrew替代品）；
1. ClickHouse引入惰性物化技术，查询性能提升千倍；
1. SerenityOS：一封献给90年代用户界面的情书；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 举报人指控DOGE窃取美国劳工关系委员会敏感数据 
<small>🔗 [krebsonsecurity.com](https://krebsonsecurity.com/2025/04/whistleblower-doge-siphoned-nlrb-case-data/): Whistleblower: DOGE Siphoned NLRB Case Data</small>


| 🔥🔥: 773 \| 💬: [410](https://news.ycombinator.com/item?id=43760801) \| 🗓️ 2025-04-22


<br />
美国劳工关系委员会（NLRB）安全架构师Daniel Berulis举报称，**Elon Musk旗下政府效率部门（DOGE）**在3月初通过临时账户转移了数十GB敏感案件数据，并试图掩盖网络痕迹。举报文件显示，DOGE账户拥有**最高权限**，可随意访问、修改甚至删除数据，同时伴随来自俄罗斯IP的异常登录尝试。NLRB高层被指控压制内部调查，并阻止向网络安全部门上报。举报人还收到无人机拍摄的威胁照片，疑似与披露事件相关。目前NLRB否认系统遭入侵，但内部IT权限已被大幅限制。

---

## <a name="2"></a>2. Supabase完成2亿美元D轮融资，估值达20亿美元 
<small>🔗 [finance.yahoo.com](https://finance.yahoo.com/news/exclusive-supabase-raises-200-million-112154867.html): Supabase raises $200M Series D at $2B valuation</small>


| 🔥🔥: 266 \| 💬: [243](https://news.ycombinator.com/item?id=43763225) \| 🗓️ 2025-04-22


<br />
开源应用开发平台**Supabase**宣布完成**2亿美元D轮融资**，估值达20亿美元，由Accel领投，Coatue、Y Combinator等跟投。联合创始人Paul Copplestone透露，Accel合伙人专程飞赴新西兰与其会面，最终敲定投资。Supabase目前拥有200万开发者用户，管理超350万个数据库，主打**Postgres兼容**和**“氛围编程”**（vibe coding）理念。公司坚持远程办公，全球团队中28%为连续创业者。名称灵感源自Nicki Minaj的热单《Super Bass》，现已成为开源领域新星。

---

## <a name="3"></a>3. Sapphire：基于Rust的macOS包管理器（Homebrew替代品） 
<small>🔗 [github.com](https://github.com/alexykn/sapphire): Sapphire: Rust based package manager for macOS (Homebrew replacement)</small>


| 🔥🔥: 199 \| 💬: [168](https://news.ycombinator.com/item?id=43765011) \| 🗓️ 2025-04-22


<br />
Sapphire是一款**实验性**的Rust开发包管理器，专为macOS设计，旨在替代Homebrew。目前仅支持ARM架构，未来可能扩展x86。核心功能包括**公式（命令行工具）**和**Cask（桌面应用）**的安装与管理，支持并行下载、依赖自动解析及源码编译（早期阶段）。项目处于Alpha阶段，路径与Homebrew不兼容，需谨慎使用。未来计划支持升级、清理、环境初始化等功能。开发者可通过源码构建参与贡献，项目采用BSD-3-Clause许可证。

---

## <a name="4"></a>4. ClickHouse引入惰性物化技术，查询性能提升千倍 
<small>🔗 [clickhouse.com](https://clickhouse.com/blog/clickhouse-gets-lazier-and-faster-introducing-lazy-materialization): ClickHouse gets lazier and faster: Introducing lazy materialization</small>


| 🔥🔥: 196 \| 💬: [47](https://news.ycombinator.com/item?id=43763688) \| 🗓️ 2025-04-22


<br />
ClickHouse最新推出的**惰性物化**技术通过延迟读取列数据，仅在查询真正需要时加载，大幅减少了I/O操作。这一优化特别适用于**Top N查询**（如排序后取LIMIT的场景），测试中某查询从219秒缩短至139毫秒，提速1576倍。  

ClickHouse原有的**列式存储**、**稀疏索引**和**PREWHERE过滤**已显著降低数据扫描量，而惰性物化进一步推迟大字段（如评论文本）的读取，直到排序和LIMIT完成后才加载必要部分。测试使用1.5亿条亚马逊评论数据，在冷缓存环境下，传统全表扫描需3分钟，而结合多层优化后仅需毫秒级响应。

---

## <a name="5"></a>5. SerenityOS：一封献给90年代用户界面的情书 
<small>🔗 [serenityos.org](https://serenityos.org/): SerenityOS is a love letter to '90s user interfaces</small>


| 🔥🔥: 171 \| 💬: [176](https://news.ycombinator.com/item?id=43760626) \| 🗓️ 2025-04-22


<br />
SerenityOS 是一款**图形化类Unix操作系统**，专为桌面电脑设计，灵感源自**90年代经典界面美学**，同时融合了现代类Unix系统的强大功能。它以真诚的态度借鉴了多个系统的优秀设计，目标是结合**90年代生产力软件的风格**与2000年代末期类Unix系统的用户友好性。该项目由爱好者打造，完全基于个人喜好，提供GitHub源码、Discord社区及详细的文档支持。

---

## <a name="6"></a>6. 机器编织的代数语义 
<small>🔗 [uwplse.org](https://uwplse.org/2025/03/31/Algebraic-Knitting.html): Algebraic Semantics for Machine Knitting</small>


| 🔥🔥: 167 \| 💬: [11](https://news.ycombinator.com/item?id=43763614) \| 🗓️ 2025-04-22


<br />
编程语言通常有严格的**语义**定义，但机器编织领域尚缺乏此类规范。作者探讨如何为机器编织建立数学语义，涉及**代数拓扑**、**群论**等理论。核心问题是判断编织指令是否可交换（如并行执行），传统编程依赖数据依赖性，而机器编织还需考虑三维空间中纱线的交叉缠绕（可能引发“钩挂”）。现有研究用纽结理论描述编织语义，但计算机难以处理连续变形，因此需转向更计算机友好的代数方法（如**辫群**）。这一探索甚至与拓扑量子计算存在奇妙关联。

---

## <a name="7"></a>7. 用SQL画3D图形：在浏览器里滥用DuckDB-WASM的疯狂实验 
<small>🔗 [hey.earth](https://www.hey.earth/posts/duckdb-doom): Abusing DuckDB-WASM by making SQL draw 3D graphics (Sort Of)</small>


| 🔥🔥: 160 \| 💬: [30](https://news.ycombinator.com/item?id=43761998) \| 🗓️ 2025-04-22


<br />
作者通过**DuckDB-WASM**（浏览器内的分析型数据库）构建了一个文本风格的《毁灭战士》克隆版，完全用SQL管理游戏状态和渲染逻辑。**地图、玩家坐标、子弹碰撞**等均由SQL表存储和计算，甚至用递归CTE实现光线追踪渲染。虽然性能有限（约6-7帧/秒），但证明了SQL在非常规场景下的潜力。过程中克服了WASM加载、SQL方言差异、异步竞态等问题，最终形成了一种**混合SQL计算与JavaScript渲染**的奇特架构。

---

## <a name="8"></a>8. Atuin Desktop：让运维手册真正“跑起来” 
<small>🔗 [blog.atuin.sh](https://blog.atuin.sh/atuin-desktop-runbooks-that-run/): Atuin Desktop: Runbooks That Run</small>


| 🔥🔥: 141 \| 💬: [35](https://news.ycombinator.com/item?id=43766200) \| 🗓️ 2025-04-22


<br />
传统运维依赖零散记忆的指令和过时文档，**Atuin CLI**虽解决了历史命令同步问题，但团队需要更系统的解决方案。Atuin Desktop作为**本地优先的可执行手册编辑器**，将终端操作、数据库查询等整合为动态工作流，支持模板化与实时执行，确保文档不失效。其特点包括：**CRDT本地协同**、与Atuin Hub同步共享，现已用于发布管理、环境迁移等场景。团队版和自动化生成功能即将推出，现开放早期体验。

---

## <a name="9"></a>9. 我本该爱上生物学 
<small>🔗 [nehalslearnings.substack.com](https://nehalslearnings.substack.com/p/i-should-have-loved-biology-too): I should have loved biology too</small>


| 🔥🔥: 140 \| 💬: [95](https://news.ycombinator.com/item?id=43764076) \| 🗓️ 2025-04-22


<br />
作者回忆自己曾因枯燥的教科书对**生物学**毫无兴趣，直到阅读《大灭绝时代》和《基因传》等书籍，被**生动的科学叙事**所震撼。这些作品将生物学描绘成探索生命奥秘的冒险，而非死记硬背的学科。文中特别提到南希·韦克斯勒寻找亨廷顿舞蹈症基因的感人故事，以及**神经元传导**的诗意描述，展现了科学背后的魅力与人性。最终，作者从厌恶转为痴迷，认为**伟大的写作**能重塑人们对科学的认知。

---

## <a name="10"></a>10. 开源基于ESP32和OpenAI的实时AI玩具公司项目 
<small>🔗 [github.com](https://github.com/akdeb/ElatoAI): Show HN: I open-sourced my AI toy company that runs on ESP32 and OpenAI realtime</small>


| 🔥🔥: 126 \| 💬: [62](https://news.ycombinator.com/item?id=43762409) \| 🗓️ 2025-04-22


<br />
该项目利用**ESP32微控制器**和**OpenAI实时API**，通过安全WebSocket与Deno边缘函数实现全球范围内超过10分钟的实时AI语音对话，适用于智能玩具、伴侣及设备。核心功能包括**实时语音转换**、自定义AI角色、Opus音频压缩及低延迟边缘计算。技术栈涵盖Next.js前端、Supabase数据库和Arduino框架，支持设备管理与用户认证。项目已开源，采用MIT许可证，欢迎开发者贡献。

---

## <a name="11"></a>11. 多项式特征真是万恶之源吗？(2024) 
<small>🔗 [alexshtf.github.io](https://alexshtf.github.io/2024/01/21/Bernstein.html): Are polynomial features the root of all evil? (2024)</small>


| 🔥🔥: 117 \| 💬: [44](https://news.ycombinator.com/item?id=43764101) \| 🗓️ 2025-04-22


<br />
本文探讨了**高次多项式**在机器学习中的误解，指出其“易过拟合”的坏名声源于两大误区：一是使用了不合适的**标准基**，二是误解了魏尔斯特拉斯逼近定理（仅适用于区间内连续函数）。通过对比**切比雪夫基**和**伯恩斯坦基**的实验，作者证明只要选择合适基函数（如伯恩斯坦基）并规范化数据，高次多项式也能通过常规正则化有效控制。**伯恩斯坦基**因其系数单位一致性和加权平均特性，特别适合拟合任务，打破了“多项式必然振荡”的刻板印象。

---

## <a name="12"></a>12. π0.5：具备开放世界泛化能力的视觉-语言-动作模型 
<small>🔗 [pi.website](https://pi.website/blog/pi05): π0.5: A VLA with open-world generalization</small>


| 🔥🔥: 107 \| 💬: [26](https://news.ycombinator.com/item?id=43764439) \| 🗓️ 2025-04-22


<br />
由Physical Intelligence公司开发的**π0.5**是一种新型**视觉-语言-动作模型（VLA）**，专注于在陌生环境中实现任务泛化。该模型通过**异构数据协同训练**（如多模态网络数据、跨机器人动作数据等），使机器人能在未经训练的家庭场景中完成整理厨房、收拾卧室等复杂任务。实验显示，π0.5在100个训练环境后泛化性能接近直接训练基准，并能结合高层语义推理与底层动作控制，展现类人的灵活性和适应性。尽管仍需优化，这一成果标志着**通用物理智能**的重要进展。

---

## <a name="13"></a>13. 让电脑杂志广告焕发生机的浣熊们 
<small>🔗 [technologizer.com](https://technologizer.com/home/2025/04/22/pc-connection-ads-raccoons/): The raccoons who made computer magazine ads great</small>


| 🔥🔥: 103 \| 💬: [30](https://news.ycombinator.com/item?id=43761633) \| 🗓️ 2025-04-22


<br />
这篇文章回顾了20世纪80至90年代电脑杂志广告的黄金时代，重点讲述了**PC Connection**公司如何通过**拟人化浣熊插画**在众多邮购广告中脱颖而出。插画师Erick Ingraham和文案David Blistein合作，创作了一系列温馨幽默的乡村场景，将**高科技产品与人性化服务**巧妙结合。这些广告不仅强化了品牌形象，还成为杂志读者难忘的亮点。背后的故事源于创始人Patricia Gallup和David Hall在新罕布什尔州小镇的创业历程，以及他们对“消除电脑恐惧”的独特营销理念。

---

## <a name="14"></a>14. 开源多模态RAG工具Morphik：本地运行，支持PDF图像解析 
<small>🔗 [github.com](https://github.com/morphik-org/morphik-core): Show HN: Morphik – Open-source RAG that understands PDF images, runs locally</small>


| 🔥🔥: 101 \| 💬: [21](https://news.ycombinator.com/item?id=43763814) \| 🗓️ 2025-04-22


<br />
Morphik是一款**开源多模态检索增强生成（RAG）工具**，专为处理技术文档和视觉内容设计。它支持**多模态搜索**（包括PDF、图像、视频等），能通过知识图谱和元数据提取高效管理非结构化数据。开发者可免费使用基础功能，或通过Python SDK/REST API快速集成。开源版本支持本地部署，但部分高级功能（如控制台）需付费。其特色包括**缓存增强生成**和与Slack等工具的预置集成，适合私有知识库构建。

---

## <a name="15"></a>15. 数据压缩专家都讨厌的这个神奇技巧 
<small>🔗 [media.ccc.de](https://media.ccc.de/v/eh22-8-more-than-just-quite-ok-data-compression-nerds-hate-this-one-trick): Data Compression Nerds Hate This One Trick [video]</small>


| 🔥: 98 \| 💬: [38](https://news.ycombinator.com/item?id=43760099) \| 🗓️ 2025-04-22


<br />
在Easterhegg 2025技术分享会上，一位开发者仅用一年时间（几乎独自）**超越了PNG数十年的无损图像压缩成果**，而他的工具是新兴的**低复杂度格式QOI**（Quite Okay Image Format）。演讲探讨了PNG、JPEG与QOI的优劣，指出**复杂度≠性能**，并深入解析数据压缩的数学原理。视频提供多语言音轨，含1080p/576p版本及音频下载。

---

## <a name="16"></a>16. 重返编程的原始健身房：在AI时代守护手艺精神 
<small>🔗 [cekrem.github.io](https://cekrem.github.io/posts/coding-as-craft-going-back-to-the-old-gym/): Coding as Craft: Going Back to the Old Gym</small>


| 🔥: 95 \| 💬: [88](https://news.ycombinator.com/item?id=43760723) \| 🗓️ 2025-04-22


<br />
Shopify CEO提出**“反射性使用AI”**已成为编码新标准，但作者认为过度依赖AI会剥夺开发者**直面问题**的成长机会。他借用《洛奇3》中“老健身房”的比喻，强调编程的核心价值在于**思考与设计**的锤炼过程，而非单纯产出代码。AI适合处理文档摘要、样板代码等枯燥工作，但算法架构等创造性环节应保留为手艺人的修炼场。作者提出“有界限的AI协作”原则：设定使用边界、坚持手动编码、深入理解生成代码，并拥抱解题过程中的认知挣扎——因为真正的技艺提升，往往诞生于那些抓狂后顿悟的瞬间。

---

## <a name="17"></a>17. FreeDOS 1.4 正式发布 
<small>🔗 [freedos.org](https://www.freedos.org/download/announce.html): FreeDOS 1.4 Is Here</small>


| 🔥: 87 \| 💬: [23](https://news.ycombinator.com/item?id=43760485) \| 🗓️ 2025-04-22


<br />
FreeDOS 1.4 是继 1.3 版本后的重大更新，包含多项改进：**程序包更新**（如 FreeCOM、Xcopy、Fdisk 等工具的优化与修复）、**精简包管理**（移除了不稳定的图形桌面，保留 OpenGEM）以及**安装介质重组**（优化 CD 内容分布，减少冗余）。新版本采用滚动测试发布机制，每月更新测试版，最终稳定版更高效可靠。此外，**内核暂未升级**，但未来将通过测试版逐步迭代。用户可通过 Live CD 或 USB 安装体验完整 DOS 环境。

---

## <a name="18"></a>18. 大卫·汤的理论物理讲座与教材系列 
<small>🔗 [damtp.cam.ac.uk](https://www.damtp.cam.ac.uk/user/tong/books.html): David Tong Lectures on Theoretical Physics</small>


| 🔥: 84 \| 💬: [9](https://news.ycombinator.com/item?id=43763223) \| 🗓️ 2025-04-22


<br />
大卫·汤（David Tong）将其广受欢迎的理论物理**讲义**升级为正式出版的教材系列，由剑桥大学出版社发行。尽管讲义可免费获取，但书籍包含**更多内容**、更清晰的解释，且价格仅为其他教材的一半。目前已出版四本，涵盖经典力学、电磁学等领域。多位知名物理学家高度评价该系列，称其兼具深度与教学艺术，有望成为当代理论物理的**经典教材**。书中语言生动幽默，既适合学生入门，也能为研究者提供启发。

---

## <a name="19"></a>19. 习惯养成并非21天 
<small>🔗 [thelogicaloptimist.com](https://thelogicaloptimist.com/index.php/2015/10/25/the-21-day-myth-create-new-habit/): It Does Not Take 21 Days to Form a Habit</small>


| 🔥: 83 \| 💬: [37](https://news.ycombinator.com/item?id=43765084) \| 🗓️ 2025-04-22


<br />
1960年，马尔茨博士提出“21天养成习惯”的说法，但这一观点仅是观察性结论，缺乏科学依据。2010年《欧洲社会心理学杂志》的研究显示，**习惯形成平均需66天**，且因习惯类型和个人差异，可能持续2至8个月。研究发现，**偶尔中断不会破坏习惯养成**，关键在于持续努力。作者强调，**习惯不应设时限**，专注“为何改变”比天数更重要。

---

## <a name="20"></a>20. 关税将如何影响你的电子产品 
<small>🔗 [spectrum.ieee.org](https://spectrum.ieee.org/tariffs-electronics-prices): The many ways tarrifs will hit electronics</small>


| 🔥: 76 \| 💬: [122](https://news.ycombinator.com/item?id=43760262) \| 🗓️ 2025-04-22


<br />
IEEE Spectrum半导体编辑Samuel K. Moore采访了IPC首席经济学家Shawn DuBravac，探讨**关税**对消费电子产品的多重影响。文章以2025年4月纽约苹果零售店的iPhone为例，指出**供应链成本上升**可能导致电子产品价格上涨，并分析**全球贸易政策**对科技行业的潜在冲击。

---

## <a name="21"></a>21. RISC-V RVA23配置文件：生态发展的重要里程碑 
<small>🔗 [riscv.org](https://riscv.org/ecosystem-news/2025/04/risc-v-rva23-a-major-milestone/): RISC-V RVA23 Profile: A major milestone</small>


| 🔥: 75 \| 💬: [24](https://news.ycombinator.com/item?id=43760686) \| 🗓️ 2025-04-22


<br />
2024年北美RISC-V峰会上，**RVA23配置文件**正式获批，标志着RISC-V生态迈出关键一步。该配置文件通过统一64位应用处理器的实现标准，确保**丰富的操作系统栈**可跨硬件移植，同时避免**供应商锁定**，为RISC-V在应用处理器领域竞争奠定基础。

---

## <a name="22"></a>22. 开源多智能体系统IDE：Rowboat 
<small>🔗 [github.com](https://github.com/rowboatlabs/rowboat): Show HN: Rowboat – Open-source IDE for multi-agent systems</small>


| 🔥: 72 \| 💬: [18](https://news.ycombinator.com/item?id=43763967) \| 🗓️ 2025-04-22


<br />
Rowboat是一款**开源多智能体构建工具**，基于OpenAI的Agents SDK开发，可快速创建AI驱动的多智能体工作流。用户通过自然语言描述需求（如“构建外卖公司助手”），**AI协作者**会自动生成相应工作流。支持连接MCP服务器，并通过**HTTP API**或Python SDK集成到应用中。提供Docker快速部署，本地访问地址为`http://localhost:3000`。项目采用Apache-2.0许可，当前获49星。

---

## <a name="23"></a>23. 强化学习能否激励大语言模型超越基础模型的推理能力？ 
<small>🔗 [limit-of-rlvr.github.io](https://limit-of-rlvr.github.io/): Does RL Incentivize Reasoning in LLMs Beyond the Base Model?</small>


| 🔥: 71 \| 💬: [26](https://news.ycombinator.com/item?id=43760625) \| 🗓️ 2025-04-22


<br />
杨跃目前致力于研究**激励LLM/MLLM推理**的新范式、**广义世界模型**的构建以及**视觉语言模型（VLA）**的泛化能力探索。他寻求与企业合作，希望对方能提供自由探索前沿问题的空间、充足资源和浓厚技术氛围，同时也在寻找博士访学机会。欢迎有意向者联系洽谈合作。

---

## <a name="24"></a>24. 逻辑中的惊人发现（2016） 
<small>🔗 [math.ucr.edu](https://math.ucr.edu/home/baez/surprises.html): Surprises in Logic (2016)</small>


| 🔥: 71 \| 💬: [29](https://news.ycombinator.com/item?id=43763291) \| 🗓️ 2025-04-22


<br />
约翰·贝兹在文中探讨了**逻辑的复杂性屏障**：存在一个极低的界限L，我们无法证明任何特定事物的复杂度超过L。这一现象与**柴廷不完备定理**相关，该定理指出，尽管无限多的字符串复杂度高于L，但无法具体指认任一字符串。文章还结合了**意外考试悖论**，揭示了数学系统自证一致性时的矛盾。最后，作者提到存在一种计算机模型能计算任何不可计算函数，展现了逻辑与计算的深层奥秘。

---

## <a name="25"></a>25. 《冷启动难题：如何利用网络效应规模化产品》书评摘要 
<small>🔗 [madhavajay.com](https://madhavajay.com/the-cold-start-problem-using-network-effects-to-scale-your-product/): The Cold Start Problem: Using Network Effects to Scale Your Product – A Review</small>


| 🔥: 67 \| 💬: [13](https://news.ycombinator.com/item?id=43761835) \| 🗓️ 2025-04-22


<br />
本书深入探讨了构建网络化产品的核心策略，重点解析了**原子网络**（最小可独立运行的稳定用户群）和**硬边用户**（如Uber司机、Airbnb房东等创造核心价值的群体）的概念。作者Andrew Chen指出，成功网络效应的悖论在于：必须从**小规模原子网络**起步，通过解决硬边用户痛点（如早期Reddit人工填充内容）逐步扩张。常见误区包括过早追求大规模、忽视网络密度或依赖不可持续的补贴。关键策略分为**冷启动阶段**（聚焦工具价值、打造“魔法时刻”）和**增长阶段**（差异化防御竞争），强调“软件本身不构成壁垒，用户互动才是护城河”。

---
