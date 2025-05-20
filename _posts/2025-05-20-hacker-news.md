---
layout: page
title: 勒西科技日报 - 2025年05月20日
date: 2025-05-20 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 谷歌推出Veo 3、Imagen 4和AI电影制作工具Flow；
1. 深度学习即应用拓扑学；
1. 表情符号的困境（2022）；
1. 从零实现一个简易搜索引擎；
1. 90s.dev：一款基于浏览器的复古游戏开发工具；

以上是今天的前五条黑科技新闻标题。

总共15条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 谷歌推出Veo 3、Imagen 4和AI电影制作工具Flow 
<small>🔗 [blog.google](https://blog.google/technology/ai/generative-media-models-io-2025/): Veo 3 and Imagen 4, and a new tool for filmmaking called Flow</small>


| 🔥🔥: 298 \| 💬: [160](https://news.ycombinator.com/item?id=44044043) \| 🗓️ 2025-05-20


<br />
谷歌DeepMind发布新一代生成式媒体模型：**Veo 3**支持视频与音频同步生成，具备真实物理效果和精准口型同步；**Imagen 4**提升图像细节与排版能力，支持2K分辨率；**Flow**整合多模型实现电影级叙事控制。同时，Lyria 2为音乐创作提供实时生成工具，所有输出均含SynthID水印以标识AI内容。这些工具现已面向部分用户开放，旨在赋能创作者高效实现创意。

---

## <a name="2"></a>2. 深度学习即应用拓扑学 
<small>🔗 [theahura.substack.com](https://theahura.substack.com/p/deep-learning-is-applied-topology): Deep Learning Is Applied Topology</small>


| 🔥🔥: 289 \| 💬: [141](https://news.ycombinator.com/item?id=44041738) \| 🗓️ 2025-05-20


<br />
本文探讨了**深度学习**与**拓扑学**的深刻联系。拓扑学研究空间变形下的不变性质，而神经网络通过矩阵运算（线性代数）本质上是在高维空间中扭曲数据流形，使其可分。例如，图像和词语均可视为高维流形上的点，神经网络通过调整流形结构实现分类或翻译。**嵌入向量**将概念映射为数学对象，支持"国王-男人+女人=女王"等运算。当前AI训练（如指令微调、RLHF）可视为在**推理流形**上向更优区域移动，而强化学习（如Deepseek R1）尝试直接优化推理路径。最终，一切数据皆存在于某种流形之上，而AI的核心能力正是发现并利用这些隐式拓扑结构。

---

## <a name="3"></a>3. 表情符号的困境（2022） 
<small>🔗 [artofproblemsolving.com](https://artofproblemsolving.com/community/c2532359h2760821_the_emoji_problem__part_i?srsltid=AfmBOor9TbMq_A7hGHSJGfoWaa2HNzducSYZu35d_LFlCSNLXpvt-pdS): The emoji problem (2022)</small>


| 🔥🔥: 284 \| 💬: [48](https://news.ycombinator.com/item?id=44039864) \| 🗓️ 2025-05-20


<br />
该博客来自AoPS社区的Turtle Math板块，讨论了**表情符号在现代通信中的挑战**。文章指出，虽然表情符号能丰富表达，但也存在**加载问题**和**跨平台兼容性差异**，导致用户体验不一致。作者呼吁开发者关注这些技术缺陷，以提升**数字化交流**的流畅性。

---

## <a name="4"></a>4. 从零实现一个简易搜索引擎 
<small>🔗 [bernsteinbear.com](https://bernsteinbear.com/blog/simple-search/): A simple search engine from scratch</small>


| 🔥🔥: 214 \| 💬: [43](https://news.ycombinator.com/item?id=44039744) \| 🗓️ 2025-05-20


<br />
作者与Chris Gregory合作，基于**word2vec词嵌入**技术，用几小时搭建了一个博客搜索引擎。核心思路是将文章和查询词转换为300维向量（通过叠加各单词向量），再用**余弦相似度**排序结果。文中详细解释了向量距离计算、文本归一化处理，并演示了终端REPL和网页前端的实现。为优化网页性能，采用分块加载词向量文件（仅下载所需部分）。最后通过自制评估集测试搜索效果，验证了该方法的实用性。

---

## <a name="5"></a>5. 90s.dev：一款基于浏览器的复古游戏开发工具 
<small>🔗 [90s.dev](https://90s.dev/blog/finally-releasing-90s-dev.html): Show HN: 90s.dev – Game maker that runs on the web</small>


| 🔥🔥: 186 \| 💬: [77](https://news.ycombinator.com/item?id=44042371) \| 🗓️ 2025-05-20


<br />
开发者耗时数月打造了**90s.dev**，这是一个独特的网页端游戏开发平台，灵感源自《魔兽争霸》等经典游戏。其核心是一个**320x180画布**的API框架，支持TypeScript和WebGL2，可实现60帧游戏或像素艺术工具（如地图编辑器）。平台采用**模块化设计**，允许通过GitHub或NPM共享应用，并创新性地引入**抽象视图**和**自动布局系统**简化GUI开发。社区可协作扩展功能，未来计划支持更多第三方应用集成。

---

## <a name="6"></a>6. 大语言模型在招聘决策中的系统性偏见：性别与位置偏好显著 
<small>🔗 [davidrozado.substack.com](https://davidrozado.substack.com/p/the-strange-behavior-of-llms-in-hiring): The behavior of LLMs in hiring decisions: Systemic biases in candidate selection</small>


| 🔥🔥: 179 \| 💬: [157](https://news.ycombinator.com/item?id=44039563) \| 🗓️ 2025-05-20


<br />
研究发现，22种主流**大语言模型（LLMs）**在模拟招聘任务中普遍存在**性别偏见**，女性候选人被选中的概率比男性高13.8%（56.9% vs 43.1%）。即使简历资质完全相同，添加显性性别字段后偏见进一步加剧。实验还发现模型存在明显的**位置偏见**，63.5%的情况下优先选择提示词中排首位的候选人。值得注意的是，掩盖性别信息后偏见消失，但模型规模与偏见程度无显著关联。这些发现对当前企业宣称的"无偏见AI招聘工具"提出了质疑，凸显了**高风险决策中AI部署的伦理风险**。

---

## <a name="7"></a>7. 用Janet编写的Windows平铺窗口管理器 
<small>🔗 [agent-kilo.github.io](https://agent-kilo.github.io/jwno/): Show HN: A Tiling Window Manager for Windows, Written in Janet</small>


| 🔥🔥: 163 \| 💬: [48](https://news.ycombinator.com/item?id=44042490) \| 🗓️ 2025-05-20


<br />
Jwno是一款为Windows 10/11设计的**高度可定制**平铺窗口管理器，采用**Janet语言**开发，主打**括号魔法**操作体验（开发者保证“完全可控”）。支持管理Emacs框架、Sonic Pi等应用，并提供REPL交互窗口。当前文档仍在完善中，但已提供新手指南（功能、安装、教程）和进阶资源（参考手册、开发指南）。开源代码托管于GitHub/Chisel，用户可通过itch.io下载体验。注：部分文档链接可能暂不可用。

---

## <a name="8"></a>8. 关于Deno消亡的报道言过其实 
<small>🔗 [deno.com](https://deno.com/blog/greatly-exaggerated): Reports of Deno's Demise Have Been Greatly Exaggerated</small>


| 🔥🔥: 155 \| 💬: [154](https://news.ycombinator.com/item?id=44040332) \| 🗓️ 2025-05-20


<br />
近期针对**Deno**及其生态（如Deploy、KV、Fresh）的质疑被夸大。尽管部分批评合理（如沟通不足），但Deno实际发展强劲：**Deno 2**发布后用户数翻倍，Node兼容性提升显著。**Deno Deploy**正转型为全栈应用平台，优化区域部署策略；**KV**将保持测试版，未来重点整合计算与状态管理。团队承诺加强沟通，并透露多项新计划正在推进，包括JSR开源治理和TC39标准参与。Deno的目标始终是打造更完善的JavaScript开发生态。

---

## <a name="9"></a>9. 为何美国长期存在贸易逆差？ 
<small>🔗 [libertystreeteconomics.newyorkfed.org](https://libertystreeteconomics.newyorkfed.org/2025/05/why-does-the-u-s-always-run-a-trade-deficit/): Why Does the U.S. Always Run a Trade Deficit?</small>


| 🔥🔥: 155 \| 💬: [325](https://news.ycombinator.com/item?id=44040407) \| 🗓️ 2025-05-20


<br />
美国贸易逆差的直接原因是**出口未能匹配进口需求**，但更深层因素在于**国内储蓄不足**，需依赖外资填补投资缺口。国民账户分析显示，逆差本质是储蓄与投资的宏观失衡：当国内储蓄不足以支撑投资时，需通过贸易逆差引入外资。数据表明，储蓄率长期低于投资占比，且家庭与政府储蓄常相互抵消。政策（如自由贸易协定）可能改变贸易结构，但只有调整储蓄或投资才能缩小逆差。尽管特定商品（如石油）逆差消失，整体逆差仍随储蓄缺口扩大。减少逆差需经历投资下降或储蓄提升的阵痛，如2008年金融危机后的调整。

---

## <a name="10"></a>10. 谷歌AI至尊版发布：最强AI订阅计划上线 
<small>🔗 [blog.google](https://blog.google/products/google-one/google-ai-ultra/): Google AI Ultra</small>


| 🔥🔥: 148 \| 💬: [157](https://news.ycombinator.com/item?id=44044367) \| 🗓️ 2025-05-20


<br />
谷歌推出**Google AI Ultra**订阅服务，提供最高级别的AI模型访问权限和高级功能，包括**Gemini**深度研究、**Veo 3**视频生成早期体验及**Flow**电影制作工具。该计划面向开发者、创意人士等高端用户，月费249.99美元（首三月5折优惠）。同时，**Google AI Pro**用户将免费升级，获得Flow工具和Chrome版Gemini早期访问。此外，部分国家大学生可免费使用AI Pro一学年。

---

## <a name="11"></a>11. Gemma 3n预览版发布：专为移动端打造的高效AI 
<small>🔗 [developers.googleblog.com](https://developers.googleblog.com/en/introducing-gemma-3n/): Gemma 3n preview: Mobile-first AI</small>


| 🔥🔥: 127 \| 💬: [1](https://news.ycombinator.com/item?id=44044451) \| 🗓️ 2025-05-20


<br />
Google推出**Gemma 3n**预览版，这是一款基于全新架构的**开源模型**，专为手机、平板和笔记本等移动设备优化。通过与高通、联发科等厂商合作，该模型实现了低内存占用（动态内存仅2GB/3GB）和快速响应（速度提升1.5倍），支持**多模态交互**（文本、图像、音频和视频）及离线隐私保护。开发者可通过Google AI Studio或AI Edge工具提前体验，为Android和Chrome平台构建智能应用。

---

## <a name="12"></a>12. OpenAI Codex 实测体验：潜力与待完善的AI编程助手 
<small>🔗 [zackproser.com](https://zackproser.com/blog/openai-codex-review): OpenAI Codex hands-on review</small>


| 🔥🔥: 106 \| 💬: [58](https://news.ycombinator.com/item?id=44042070) \| 🗓️ 2025-05-20


<br />
作者试用**OpenAI Codex**后，认为其**多线程任务并行处理**的设计契合高效工作流，能通过自然语言快速发起多个代码维护任务（如文本修改、样式调整）。当前亮点包括GitHub仓库无缝对接、手机端操作支持，以及自动生成PR描述的功能。但存在明显短板：**错误处理不稳定**，复杂重构任务体验卡顿，且**沙箱无网络连接**导致依赖更新受限。尽管尚未带来颠覆性效率提升，作者看好其未来通过模型优化和分支管理改进，成为日常工作的核心调度工具。

---

## <a name="13"></a>13. 如果AI代理都搞不懂你的API，用户更搞不懂 
<small>🔗 [stytch.com](https://stytch.com/blog/if-an-ai-agent-cant-figure-out-how-your-api-works-neither-can-your-users/): If an AI agent can't figure out how your API works, neither can your users</small>


| 🔥: 96 \| 💬: [48](https://news.ycombinator.com/item?id=44042311) \| 🗓️ 2025-05-20


<br />
文章指出，**AI代理**（如LangChain、OpenAI工具）在调用API时的表现直接反映了API设计的清晰度。若代理因文档模糊、错误信息不明确或设计不一致而卡住，人类开发者同样会受阻。**关键改进点**包括：提供**一致的API设计**、编写**详尽的文档**，以及返回**清晰的错误提示**。优化这些方面不仅能提升AI代理的成功率，也能显著改善人类开发者的体验。AI代理的失败日志如同精准的**用户体验测试**，暴露出API设计的短板。

---

## <a name="14"></a>14. NSA选择器：将网络数据流转换为音频的Eurorack模块 
<small>🔗 [github.com](https://github.com/wenzellabs/the_NSA_selector): The NSA Selector</small>


| 🔥: 91 \| 💬: [14](https://news.ycombinator.com/item?id=44044459) \| 🗓️ 2025-05-20


<br />
这是一款**Eurorack模块**，配备两个以太网接口和一个音频输出，可将网络数据流实时转换为音频信号。**不依赖任何协议**，直接截取原始比特流生成声音，支持创意应用如监听未加密图像传输（如.bmp文件）或游戏数据。模块内置4位DAC，采样率高达25MHz，需搭配低通滤波器使用。提供组装套件或成品，适用于实验音乐和网络艺术探索。  

关键词：**数据转音频**、**4位DAC**、**以太网监听**

---

## <a name="15"></a>15. Kubernetes原生分布式大模型推理框架llm-d发布 
<small>🔗 [llm-d.ai](https://llm-d.ai/blog/llm-d-announce): llm-d, Kubernetes native distributed inference</small>


| 🔥: 88 \| 💬: [13](https://news.ycombinator.com/item?id=44040883) \| 🗓️ 2025-05-20


<br />
llm-d是一个基于**Kubernetes**的高性能分布式大模型推理框架，旨在通过**KV缓存感知路由**和**解耦式服务**等优化技术，实现高效、低成本的规模化部署。它整合了vLLM引擎和Kubernetes工具链，支持多硬件平台（如NVIDIA GPU、TPU），并针对LLM推理的独特负载特性（如长尾延迟、多轮请求）设计了智能调度和自动扩展功能。用户可通过模块化架构快速部署，显著提升吞吐量（QPS）并降低首令牌延迟（TTFT）。现已开源，欢迎开发者参与社区共建。

---
