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
1. ClickHouse引入惰性物化技术，查询性能提升千倍；
1. SerenityOS：一封献给90年代用户界面的情书；
1. 用SQL画3D图形：在浏览器里滥用DuckDB-WASM的疯狂实验；

以上是今天的前五条黑科技新闻标题。

总共12条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 举报人指控DOGE窃取美国劳工关系委员会敏感数据 
<small>🔗 [krebsonsecurity.com](https://krebsonsecurity.com/2025/04/whistleblower-doge-siphoned-nlrb-case-data/): Whistleblower: DOGE Siphoned NLRB Case Data</small>


| 🔥🔥: 765 \| 💬: [403](https://news.ycombinator.com/item?id=43760801) \| 🗓️ 2025-04-22


<br />
美国劳工关系委员会（NLRB）安全架构师Daniel Berulis举报称，**Elon Musk旗下政府效率部门（DOGE）**在3月初通过临时账户转移了数十GB敏感案件数据，并试图掩盖网络痕迹。举报文件显示，DOGE账户拥有**最高权限**，可随意访问、修改甚至删除数据，同时伴随来自俄罗斯IP的异常登录尝试。NLRB高层被指控压制内部调查，并阻止向网络安全部门上报。举报人还收到无人机拍摄的威胁照片，疑似与披露事件相关。目前NLRB否认系统遭入侵，但内部IT权限已被大幅限制。

---

## <a name="2"></a>2. Supabase完成2亿美元D轮融资，估值达20亿美元 
<small>🔗 [finance.yahoo.com](https://finance.yahoo.com/news/exclusive-supabase-raises-200-million-112154867.html): Supabase raises $200M Series D at $2B valuation</small>


| 🔥🔥: 236 \| 💬: [216](https://news.ycombinator.com/item?id=43763225) \| 🗓️ 2025-04-22


<br />
开源应用开发平台**Supabase**宣布完成**2亿美元D轮融资**，估值达20亿美元，由Accel领投，Coatue、Y Combinator等跟投。联合创始人Paul Copplestone透露，Accel合伙人专程飞赴新西兰与其会面，最终敲定投资。Supabase目前拥有200万开发者用户，管理超350万个数据库，主打**Postgres兼容**和**“氛围编程”**（vibe coding）理念。公司坚持远程办公，全球团队中28%为连续创业者。名称灵感源自Nicki Minaj的热单《Super Bass》，现已成为开源领域新星。

---

## <a name="3"></a>3. ClickHouse引入惰性物化技术，查询性能提升千倍 
<small>🔗 [clickhouse.com](https://clickhouse.com/blog/clickhouse-gets-lazier-and-faster-introducing-lazy-materialization): ClickHouse gets lazier and faster: Introducing lazy materialization</small>


| 🔥🔥: 170 \| 💬: [42](https://news.ycombinator.com/item?id=43763688) \| 🗓️ 2025-04-22


<br />
ClickHouse最新推出的**惰性物化**技术通过延迟读取列数据，仅在查询真正需要时加载，大幅减少了I/O操作。这一优化特别适用于**Top N查询**（如排序后取LIMIT的场景），测试中某查询从219秒缩短至139毫秒，提速1576倍。  

ClickHouse原有的**列式存储**、**稀疏索引**和**PREWHERE过滤**已显著降低数据扫描量，而惰性物化进一步推迟大字段（如评论文本）的读取，直到排序和LIMIT完成后才加载必要部分。测试使用1.5亿条亚马逊评论数据，在冷缓存环境下，传统全表扫描需3分钟，而结合多层优化后仅需毫秒级响应。

---

## <a name="4"></a>4. SerenityOS：一封献给90年代用户界面的情书 
<small>🔗 [serenityos.org](https://serenityos.org/): SerenityOS is a love letter to '90s user interfaces</small>


| 🔥🔥: 169 \| 💬: [172](https://news.ycombinator.com/item?id=43760626) \| 🗓️ 2025-04-22


<br />
SerenityOS 是一款**图形化类Unix操作系统**，专为桌面电脑设计，灵感源自**90年代经典界面美学**，同时融合了现代类Unix系统的强大功能。它以真诚的态度借鉴了多个系统的优秀设计，目标是结合**90年代生产力软件的风格**与2000年代末期类Unix系统的用户友好性。该项目由爱好者打造，完全基于个人喜好，提供GitHub源码、Discord社区及详细的文档支持。

---

## <a name="5"></a>5. 用SQL画3D图形：在浏览器里滥用DuckDB-WASM的疯狂实验 
<small>🔗 [hey.earth](https://www.hey.earth/posts/duckdb-doom): Abusing DuckDB-WASM by making SQL draw 3D graphics (Sort Of)</small>


| 🔥🔥: 156 \| 💬: [29](https://news.ycombinator.com/item?id=43761998) \| 🗓️ 2025-04-22


<br />
作者通过**DuckDB-WASM**（浏览器内的分析型数据库）构建了一个文本风格的《毁灭战士》克隆版，完全用SQL管理游戏状态和渲染逻辑。**地图、玩家坐标、子弹碰撞**等均由SQL表存储和计算，甚至用递归CTE实现光线追踪渲染。虽然性能有限（约6-7帧/秒），但证明了SQL在非常规场景下的潜力。过程中克服了WASM加载、SQL方言差异、异步竞态等问题，最终形成了一种**混合SQL计算与JavaScript渲染**的奇特架构。

---

## <a name="6"></a>6. 机器编织的代数语义 
<small>🔗 [uwplse.org](https://uwplse.org/2025/03/31/Algebraic-Knitting.html): Algebraic Semantics for Machine Knitting</small>


| 🔥🔥: 147 \| 💬: [11](https://news.ycombinator.com/item?id=43763614) \| 🗓️ 2025-04-22


<br />
编程语言通常有严格的**语义**定义，但机器编织领域尚缺乏此类规范。作者探讨如何为机器编织建立数学语义，涉及**代数拓扑**、**群论**等理论。核心问题是判断编织指令是否可交换（如并行执行），传统编程依赖数据依赖性，而机器编织还需考虑三维空间中纱线的交叉缠绕（可能引发“钩挂”）。现有研究用纽结理论描述编织语义，但计算机难以处理连续变形，因此需转向更计算机友好的代数方法（如**辫群**）。这一探索甚至与拓扑量子计算存在奇妙关联。

---

## <a name="7"></a>7. 我本该爱上生物学 
<small>🔗 [nehalslearnings.substack.com](https://nehalslearnings.substack.com/p/i-should-have-loved-biology-too): I should have loved biology too</small>


| 🔥🔥: 128 \| 💬: [82](https://news.ycombinator.com/item?id=43764076) \| 🗓️ 2025-04-22


<br />
作者回忆自己曾因枯燥的教科书对**生物学**毫无兴趣，直到阅读《大灭绝时代》和《基因传》等书籍，被**生动的科学叙事**所震撼。这些作品将生物学描绘成探索生命奥秘的冒险，而非死记硬背的学科。文中特别提到南希·韦克斯勒寻找亨廷顿舞蹈症基因的感人故事，以及**神经元传导**的诗意描述，展现了科学背后的魅力与人性。最终，作者从厌恶转为痴迷，认为**伟大的写作**能重塑人们对科学的认知。

---

## <a name="8"></a>8. Sapphire：基于Rust的macOS包管理器（Homebrew替代品） 
<small>🔗 [github.com](https://github.com/alexykn/sapphire): Sapphire: Rust based package manager for macOS (Homebrew replacement)</small>


| 🔥🔥: 120 \| 💬: [122](https://news.ycombinator.com/item?id=43765011) \| 🗓️ 2025-04-22


<br />
Sapphire是一款**实验性**的Rust开发包管理器，专为macOS设计，旨在替代Homebrew。目前仅支持ARM架构，未来可能扩展x86。核心功能包括**公式（命令行工具）**和**Cask（桌面应用）**的安装与管理，支持并行下载、依赖自动解析及源码编译（早期阶段）。项目处于Alpha阶段，路径与Homebrew不兼容，需谨慎使用。未来计划支持升级、清理、环境初始化等功能。开发者可通过源码构建参与贡献，项目采用BSD-3-Clause许可证。

---

## <a name="9"></a>9. 开源基于ESP32和OpenAI的实时AI玩具公司项目 
<small>🔗 [github.com](https://github.com/akdeb/ElatoAI): Show HN: I open-sourced my AI toy company that runs on ESP32 and OpenAI realtime</small>


| 🔥🔥: 119 \| 💬: [61](https://news.ycombinator.com/item?id=43762409) \| 🗓️ 2025-04-22


<br />
该项目利用**ESP32微控制器**和**OpenAI实时API**，通过安全WebSocket与Deno边缘函数实现全球范围内超过10分钟的实时AI语音对话，适用于智能玩具、伴侣及设备。核心功能包括**实时语音转换**、自定义AI角色、Opus音频压缩及低延迟边缘计算。技术栈涵盖Next.js前端、Supabase数据库和Arduino框架，支持设备管理与用户认证。项目已开源，采用MIT许可证，欢迎开发者贡献。

---

## <a name="10"></a>10. 多项式特征真是万恶之源吗？(2024) 
<small>🔗 [alexshtf.github.io](https://alexshtf.github.io/2024/01/21/Bernstein.html): Are polynomial features the root of all evil? (2024)</small>


| 🔥: 96 \| 💬: [35](https://news.ycombinator.com/item?id=43764101) \| 🗓️ 2025-04-22


<br />
本文探讨了**高次多项式**在机器学习中的误解，指出其“易过拟合”的坏名声源于两大误区：一是使用了不合适的**标准基**，二是误解了魏尔斯特拉斯逼近定理（仅适用于区间内连续函数）。通过对比**切比雪夫基**和**伯恩斯坦基**的实验，作者证明只要选择合适基函数（如伯恩斯坦基）并规范化数据，高次多项式也能通过常规正则化有效控制。**伯恩斯坦基**因其系数单位一致性和加权平均特性，特别适合拟合任务，打破了“多项式必然振荡”的刻板印象。

---

## <a name="11"></a>11. 数据压缩专家都讨厌的这个神奇技巧 
<small>🔗 [media.ccc.de](https://media.ccc.de/v/eh22-8-more-than-just-quite-ok-data-compression-nerds-hate-this-one-trick): Data Compression Nerds Hate This One Trick [video]</small>


| 🔥: 95 \| 💬: [33](https://news.ycombinator.com/item?id=43760099) \| 🗓️ 2025-04-22


<br />
在Easterhegg 2025技术分享会上，一位开发者仅用一年时间（几乎独自）**超越了PNG数十年的无损图像压缩成果**，而他的工具是新兴的**低复杂度格式QOI**（Quite Okay Image Format）。演讲探讨了PNG、JPEG与QOI的优劣，指出**复杂度≠性能**，并深入解析数据压缩的数学原理。视频提供多语言音轨，含1080p/576p版本及音频下载。

---

## <a name="12"></a>12. 重返编程的原始健身房：在AI时代守护手艺精神 
<small>🔗 [cekrem.github.io](https://cekrem.github.io/posts/coding-as-craft-going-back-to-the-old-gym/): Coding as Craft: Going Back to the Old Gym</small>


| 🔥: 95 \| 💬: [87](https://news.ycombinator.com/item?id=43760723) \| 🗓️ 2025-04-22


<br />
Shopify CEO提出**“反射性使用AI”**已成为编码新标准，但作者认为过度依赖AI会剥夺开发者**直面问题**的成长机会。他借用《洛奇3》中“老健身房”的比喻，强调编程的核心价值在于**思考与设计**的锤炼过程，而非单纯产出代码。AI适合处理文档摘要、样板代码等枯燥工作，但算法架构等创造性环节应保留为手艺人的修炼场。作者提出“有界限的AI协作”原则：设定使用边界、坚持手动编码、深入理解生成代码，并拥抱解题过程中的认知挣扎——因为真正的技艺提升，往往诞生于那些抓狂后顿悟的瞬间。

---
