---
layout: page
title: 勒西科技日报 - 2025年04月11日
date: 2025-04-11 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 但如果我只想要一匹更快的马呢？；
1. Meta内部数据曝光：以色列大规模删除亲巴勒斯坦内容；
1. Fedora计划实现99%软件包的可复现构建；
1. 优势即劣势；
1. 为什么我选择用Lisp编程；

以上是今天的前五条黑科技新闻标题。

总共16条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 但如果我只想要一匹更快的马呢？ 
<small>🔗 [rakhim.exotext.com](https://rakhim.exotext.com/but-what-if-i-really-want-a-faster-horse): But what if I want a faster horse?</small>


| 🔥🔥: 1089 \| 💬: [493](https://news.ycombinator.com/item?id=43652723) \| 🗓️ 2025-04-11


<br />
科技圈常引用亨利·福特的名言：“如果问人们想要什么，他们会说更快的马”，以此强调**颠覆性创新**的价值，如iPhone重塑手机市场。然而，作者指出，如今许多产品过度追求“体验”而牺牲了实用性：**Netflix**从清晰的影片库沦为算法驱动的混乱推荐流，**Spotify**从音乐库变成内容轰炸机，甚至YouTube和LinkedIn也趋同于TikTok的无限刷模式。用户失去对内容的控制权，**一致性**和实用功能被削弱，一切都在向“电视式”被动消费退化。有时，人们真的只需要一匹“更快的马”。

---

## <a name="2"></a>2. Meta内部数据曝光：以色列大规模删除亲巴勒斯坦内容 
<small>🔗 [dropsitenews.com](https://www.dropsitenews.com/p/leaked-data-israeli-censorship-meta): Leaked Meta data reveals campaign to remove pro-Palestine posts</small>


| 🔥🔥: 430 \| 💬: [244](https://news.ycombinator.com/item?id=43655603) \| 🗓️ 2025-04-11


<br />
根据Drop Site News获取的**Meta内部数据**，自2023年10月7日起，以色列政府通过**高优先级渠道**向Meta提交内容删除请求，**94%的请求被迅速执行**，导致超9万帖子被移除，38.8万帖子遭限流。数据显示，以方请求主要针对阿拉伯和穆斯林国家用户（如埃及、约旦、巴勒斯坦），仅1.3%涉及以色列本土内容。Meta内部AI系统被曝以这些操作为训练数据，未来可能持续压制亲巴言论。人权观察报告指出，被删内容中99.9%为和平支持巴勒斯坦的帖子。Meta高管团队与以色列政府存在密切关联，包括前以军情报官员Guy Rosen及以总理前顾问Jordana Cutler。

---

## <a name="3"></a>3. Fedora计划实现99%软件包的可复现构建 
<small>🔗 [lwn.net](https://lwn.net/Articles/1014979/): Fedora change aims for 99% package reproducibility</small>


| 🔥🔥: 269 \| 💬: [113](https://news.ycombinator.com/item?id=43653672) \| 🗓️ 2025-04-11


<br />
Fedora项目正推进一项变革，目标是在Fedora 43开发周期中实现**99%软件包的可复现构建**。可复现构建指在相同源代码、构建环境和指令下，能生成完全一致的二进制产物。Fedora采用与Debian不同的定义，允许排除签名和部分元数据差异。目前通过基础设施改进（如固定文件修改时间、标准化元数据工具）已实现90%复现率。下一步将要求维护者将不可复现问题视为缺陷，并部署**rebuilderd**系统进行独立验证。该举措不仅能增强供应链安全，还能提升软件质量，例如发现架构无关包中的隐藏错误。讨论焦点包括工具集成方案及维护成本，预计10月随Fedora 43发布。

---

## <a name="4"></a>4. 优势即劣势 
<small>🔗 [terriblesoftware.org](https://terriblesoftware.org/2025/03/31/your-strengths-are-your-weaknesses/): Strengths Are Your Weaknesses</small>


| 🔥🔥: 244 \| 💬: [82](https://news.ycombinator.com/item?id=43652024) \| 🗓️ 2025-04-11


<br />
文章指出，**个人优势与劣势往往是同一特质的双面表现**。例如，编码速度快可能提升效率，但也可能导致细节疏忽。作者提出三个应对方法：在1对1沟通中正视这种二元性、明确不同场景下的行为边界，以及**利用团队成员的互补性**。关键在于培养自我认知，而非消除特质差异，因为正是这些特质让每个人独特且有价值。

---

## <a name="5"></a>5. 为什么我选择用Lisp编程 
<small>🔗 [funcall.blogspot.com](http://funcall.blogspot.com/2025/04/why-i-program-in-lisp.html): Why I Program in Lisp</small>


| 🔥🔥: 198 \| 💬: [176](https://news.ycombinator.com/item?id=43651576) \| 🗓️ 2025-04-11


<br />
尽管Lisp并非最流行的语言，且其他语言拥有更丰富的库和社区支持，作者仍坚持使用Lisp。**Lisp语法统一**（如剑桥波兰表示法），减少了记忆负担；**支持函数式编程**，便于抽象和重构；**动态类型**和**REPL环境**则加速了原型开发与问题探索。此外，Lisp的**调试安全性**和**多态性**（如`+`运算符的泛用性）使其成为高效的问题解决工具。作者认为，Lisp的核心价值在于它能将编程转化为一种“思维工具”，从而提升创造乐趣。

---

## <a name="6"></a>6. 欧洲：如今真正的自由之地 
<small>🔗 [economist.com](https://www.economist.com/europe/2025/04/10/the-thing-about-europe-its-the-actual-land-of-the-free-now): The thing about Europe: it's the actual land of the free now</small>


| 🔥🔥: 150 \| 💬: [244](https://news.ycombinator.com/item?id=43651489) \| 🗓️ 2025-04-11


<br />
尽管欧洲常被嘲讽**过度监管**、缺乏像亚马逊或特斯拉这样的万亿级企业，但同时也避免了**科技寡头**对政治的操控。欧洲没有富豪将巨额资金注入竞选，也没有高管在社交媒体炫耀“粉碎国家机器”。相比之下，欧洲的**现实问题**反而显得不那么严峻，成为一片更纯粹的自由之地。

---

## <a name="7"></a>7. 美国社保局将公共沟通全面转向X平台 
<small>🔗 [wired.com](https://www.wired.com/story/social-security-administration-regional-office-elon-musk-x/): Social Security Administration Moving Public Communications to X</small>


| 🔥🔥: 142 \| 💬: [71](https://news.ycombinator.com/item?id=43657079) \| 🗓️ 2025-04-11


<br />
美国社会保障局（SSA）宣布**停止通过新闻稿和“同事信”与媒体及公众沟通**，转而**仅通过X平台（原推特）发布信息**。此举引发内部担忧，因员工需特殊申请才能用政府电脑访问社交媒体，可能影响工作效率。此外，**老年人等群体或难以获取关键福利信息**。同时，SSA正大幅裁员，区域办公室员工将削减87%，恐削弱反欺诈能力。白宫回应称“资源重组是为优化服务”，但员工质疑此举将导致“信息断层”。

---

## <a name="8"></a>8. Erlang的核心并非轻量进程，而是行为模式 
<small>🔗 [stevana.github.io](https://stevana.github.io/erlangs_not_about_lightweight_processes_and_message_passing.html): Erlang's not about lightweight processes and message passing</small>


| 🔥🔥: 133 \| 💬: [66](https://news.ycombinator.com/item?id=43655221) \| 🗓️ 2025-04-11


<br />
Erlang常被误解为以**轻量进程**和**消息传递**为核心，但其真正价值在于**行为模式**（behaviours）。这些预定义的接口（如`gen_server`、`supervisor`）封装了并发与容错逻辑，开发者只需专注业务代码。例如，AXD301交换机系统通过122个`gen_server`实例和20个**监督树**构建，实现了九九个九的可靠性。行为模式将分布式系统的复杂性抽象为可复用的组件，其"快速失败+重启"哲学（**Let it crash**）大幅提升了系统稳定性。这一设计思想远超语言特性本身，成为构建高可用系统的范式。

---

## <a name="9"></a>9. 如何制作长弓 
<small>🔗 [howtomakealongbow.co.uk](https://www.howtomakealongbow.co.uk): How to Make a Longbow</small>


| 🔥🔥: 114 \| 💬: [37](https://news.ycombinator.com/item?id=43652160) \| 🗓️ 2025-04-11


<br />
该网站持续更新扩展内容，欢迎用户反馈希望获取的信息。**长弓制作**需要耐心和技巧，建议定期回访以获取最新指南。**关键材料**包括优质木材和专用工具，**核心步骤**涉及木材成型、弓弦安装及张力测试。用户互动是优化内容的重要方式。

---

## <a name="10"></a>10. PS3：一颗被舔过的多核糖果 
<small>🔗 [darkcephas.github.io](https://darkcephas.github.io/ps3_failed/ps3_failed.html): The PS3 Licked the Many Cookie</small>


| 🔥🔥: 101 \| 💬: [83](https://news.ycombinator.com/item?id=43656279) \| 🗓️ 2025-04-11


<br />
本文从开发者视角剖析PS3失败原因：其**异构计算架构**严重阻碍了开发效率。尽管Cell处理器SPE单元理论性能强大，但实际仅能调用5-6个核心，且**本地内存限制**（仅128KB可用）迫使代码必须深度定制。与Xbox360的统一架构相比，PS3的GPU算力分散（顶点/像素单元分离）、组件协同成本高昂，导致开发者需耗费大量精力优化基础功能。最终，这种**半成品多核设计**未能兑现性能承诺，反而成为行业教训。

---

## <a name="11"></a>11. Datastar：未来网页开发框架的新选择？ 
<small>🔗 [chrismalek.me](https://chrismalek.me/posts/data-star-first-impressions/): Datastar: Web Framework for the Future?</small>


| 🔥: 90 \| 💬: [54](https://news.ycombinator.com/item?id=43655914) \| 🗓️ 2025-04-11


<br />
Datastar是一款新兴的**超媒体框架**，专注于简化实时网页应用开发。它采用**服务器驱动架构**，通过**信号机制**实现UI自动更新，并利用**服务器推送事件（SSE）**提升性能。相比HTMX，Datastar整合了前端状态管理与交互功能，无需依赖额外JS库，适合追求高效、厌恶复杂JavaScript生态的开发者。其核心理念强调后端主导、响应式编程，为传统前后端分离模式提供了另一种思路。

---

## <a name="12"></a>12. 基于重心坐标的四边形双线性插值法 
<small>🔗 [gpuopen.com](https://gpuopen.com/learn/bilinear-interpolation-quadrilateral-barycentric-coordinates/): Bilinear interpolation on a quadrilateral using Barycentric coordinates</small>


| 🔥: 88 \| 💬: [25](https://news.ycombinator.com/item?id=43654912) \| 🗓️ 2025-04-11


<br />
最新发布的**AgilitySDK预览版1.716.0**新增了对**Microsoft® DirectX®**和视频编码功能的支持。此次更新重点引入了利用**重心坐标**在四边形上实现双线性插值的先进技术，为图形处理和视频编码提供了更高效的解决方案。该版本要求开发者熟悉相关API，并适用于需要高精度插值的应用场景。

---

## <a name="13"></a>13. Rust CUDA 项目：用 Rust 编写高性能 GPU 代码的生态 
<small>🔗 [github.com](https://github.com/Rust-GPU/Rust-CUDA): Rust CUDA Project</small>


| 🔥: 82 \| 💬: [20](https://news.ycombinator.com/item?id=43654881) \| 🗓️ 2025-04-11


<br />
该项目旨在构建一个完整的工具链和库生态系统，使 **Rust** 成为 **CUDA** 高性能 GPU 计算的一流语言。核心功能包括通过 `rustc_codegen_nvvm` 将 Rust 代码编译为优化的 PTX 指令，并提供 `cuda_std`、`cust` 等库支持 GPU/CPU 端开发。项目仍处早期阶段，但计划覆盖 CUDA 全生态（如深度学习库 `cudnn`、光线追踪 `optix`）。相比传统 LLVM PTX 方案，它更稳定且专为 Rust 设计，强调 **安全性** 和 **高性能**。项目采用 Apache-2.0/MIT 双协议，欢迎贡献。

---

## <a name="14"></a>14. Adobe遭抵制后删除Bluesky所有帖文 
<small>🔗 [petapixel.com](https://petapixel.com/2025/04/10/adobe-deletes-bluesky-posts-after-furious-backlash/): Adobe deletes Bluesky posts after backlash</small>


| 🔥: 77 \| 💬: [129](https://news.ycombinator.com/item?id=43653885) \| 🗓️ 2025-04-11


<br />
Adobe在Twitter替代平台Bluesky的首次尝试引发强烈反弹。用户因不满其**订阅模式涨价**和**AI生成内容立场**，在帖文下集体抗议，迫使Adobe删除了所有内容。尽管账号保留，但首条问候帖和Photoshop账号的帖文均被清空，用户嘲讽此举“暴露了艺术家群体对Adobe的普遍厌恶”。矛盾根源可追溯至十年前Adobe转向订阅制，近年**价格飙升**和**社区沟通缺失**进一步激化矛盾。

---

## <a name="15"></a>15. 卡内基梅隆大学中国留学生毕业前夕突遭签证撤销 
<small>🔗 [cbsnews.com](https://www.cbsnews.com/pittsburgh/news/carnegie-mellon-student-visa-revoked-interview/): Carnegie Mellon student with one semester left learns his visa was revoked</small>


| 🔥: 75 \| 💬: [44](https://news.ycombinator.com/item?id=43653611) \| 🗓️ 2025-04-11


<br />
卡内基梅隆大学大四学生**Jayson Ma**在仅剩3周毕业时，突然接到通知称其**学生签证被无故撤销**，且未获解释。他2016年从中国赴美读高中，现攻读电气计算机工程学位，母亲在中国身患晚期癌症仍坚持让他完成学业。律师推测可能与2023年一项已撤销的DUI记录有关。宾州多所高校也出现类似案例，校方建议国际学生随身携带证件以应对突发核查。Ma表示已做好随时离境准备，但仍希望完成学业。

---

## <a name="16"></a>16. 铅对大脑的危害从未消失 
<small>🔗 [neurofrontiers.blog](https://neurofrontiers.blog/why-lead-is-still-bad-for-your-brain/): Lead is still bad for your brain</small>


| 🔥: 70 \| 💬: [79](https://news.ycombinator.com/item?id=43651532) \| 🗓️ 2025-04-11


<br />
尽管铅已从汽油、油漆等产品中逐步淘汰，但其**持久性污染**仍威胁健康。铅是**不可降解的重金属**，会长期存在于环境与人体中，尤其对儿童危害更大——通过肠道或肺部吸收后，铅会沉积在骨骼和大脑，导致**认知缺陷、行为问题及智商下降**。研究证实，**任何剂量的铅暴露都不安全**，其毒性机制包括破坏细胞膜流动性、干扰钙信号和产生自由基。预防措施包括更换含铅建材、参与社区清理行动，而早期干预可部分逆转儿童铅中毒的影响。

---
