---
layout: page
title: 勒西科技日报 - 2025年04月28日
date: 2025-04-28 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 西班牙葡萄牙大范围停电致马德里网球公开赛取消；
1. 我造了一款能直接运行Python的硬件处理器；
1. 从Rust迁移的决策与收获；
1. 西班牙和葡萄牙多地突发大规模停电；
1. 地狱般的副业：我在初创公司的血泪史；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 西班牙葡萄牙大范围停电致马德里网球公开赛取消 
<small>🔗 [bbc.com](https://www.bbc.com/news/live/c9wpq8xrvd9t): Widespread power outage in Spain and Portugal</small>


| 🔥🔥: 1130 \| 💬: [853](https://news.ycombinator.com/item?id=43819791) \| 🗓️ 2025-04-28


<br />
4月28日，**西班牙全国性停电**波及马德里网球公开赛，主办方为**保障安全**，被迫取消当日全部日场和夜场比赛。停电事件同时影响葡萄牙，但具体范围未详述。路透社图片显示赛事现场商店陷入黑暗。

---

## <a name="2"></a>2. 我造了一款能直接运行Python的硬件处理器 
<small>🔗 [runpyxl.com](https://www.runpyxl.com/gpio): Show HN: I built a hardware processor that runs Python</small>


| 🔥🔥: 780 \| 💬: [217](https://news.ycombinator.com/item?id=43820228) \| 🗓️ 2025-04-28


<br />
**PyXL** 是一款直接执行Python代码的硬件处理器，无需解释器或虚拟机。通过将Python编译为自定义汇编，它在FPGA上实现了**480ns的GPIO响应速度**，比MicroPython快30倍（时钟频率归一化后达50倍）。其核心优势在于**硬件级确定性**和实时性，适用于机器人控制、工业嵌入式等场景。演示视频对比了PyXL与PyBoard的GPIO延迟，前者每次测试结果稳定，后者存在抖动。PyXL的Python工具链运行在标准CPython环境，代码最终在FPGA上以100MHz时钟执行。

---

## <a name="3"></a>3. 从Rust迁移的决策与收获 
<small>🔗 [deadmoney.gg](https://deadmoney.gg/news/articles/migrating-away-from-rust): Migrating away from Rust</small>


| 🔥🔥: 332 \| 💬: [266](https://news.ycombinator.com/item?id=43824640) \| 🗓️ 2025-04-28


<br />
作者最初因个人兴趣选择用**Rust**和**Bevy引擎**开发游戏《Architect of Ruin》，享受其ECS模型和社区活力。但随着项目推进，**协作门槛高**（新手难上手）、**迭代效率低**（Rust抽象不足）和**引擎不稳定**（API频繁变更）等问题凸显。团队最终用6周将游戏重写为**C#/Unity**，发现开发速度显著提升，代码更简洁，尤其利于快速原型设计。尽管仍面临本地化等挑战，但迁移后团队效率大幅改善。作者强调，技术选型需平衡个人偏好与项目实际需求，此次转型虽艰难却必要。

---

## <a name="4"></a>4. 西班牙和葡萄牙多地突发大规模停电 
<small>🔗 [bbc.com](https://www.bbc.com/news/live/c9wpq8xrvd9t): Reports of widespread power cuts in Spain and Portugal</small>


| 🔥🔥: 325 \| 💬: [18](https://news.ycombinator.com/item?id=43820043) \| 🗓️ 2025-04-28


<br />
葡萄牙里斯本因停电导致**刷卡支付系统瘫痪**，民众在ATM前排起长队。当地居民Emily Lansdown描述，**餐厅突然断电**无法结账，且**地铁停运**，只能尝试打车前往海滩。停电对交通和日常生活造成严重影响。

---

## <a name="5"></a>5. 地狱般的副业：我在初创公司的血泪史 
<small>🔗 [blog.jacobstechtavern.com](https://blog.jacobstechtavern.com/p/the-side-hustle-from-hell): The side hustle from hell</small>


| 🔥🔥: 248 \| 💬: [108](https://news.ycombinator.com/item?id=43823620) \| 🗓️ 2025-04-28


<br />
作者Jacob Bartlett分享了他2019年加入汽车维修平台**Fixr**的经历。作为“顾问”加入后，他发现团队开发的App问题重重，甚至无法适配现代手机屏幕。尽管他与朋友Gus熬夜重写代码并成为**联合创始人**，但团队内部矛盾（如股权分配纠纷）和**市场冷启动失败**导致项目最终搁浅。这段经历让他意识到：**初创公司的光鲜背后可能是无薪劳动和无效努力**。

---

## <a name="6"></a>6. 揭秘《冬季挑战赛》的游戏机制 
<small>🔗 [mrwint.github.io](https://mrwint.github.io/winter/writeup/writeup.html): Uncovering the mechanics of The Games: Winter Challenge</small>


| 🔥🔥: 247 \| 💬: [102](https://news.ycombinator.com/item?id=43820076) \| 🗓️ 2025-04-28


<br />
作者重温了1991年由MindSpan开发的经典DOS游戏《The Games: Winter Challenge》，重点探索其**滑雪跳跃项目**的底层逻辑。通过逆向工程，他发现游戏采用**LZEXE压缩**和**覆盖管理技术**来应对早期DOS系统的内存限制。不同版本（包括原版、GOG版和多个破解版）存在代码差异，其中**拷贝保护机制**的移除可能导致部分功能异常。文章深入剖析了游戏的反汇编过程、覆盖加载原理，以及早期软件破解与硬件限制的巧妙博弈。

---

## <a name="7"></a>7. Qwen3重磅发布：更智能的混合思维大模型 
<small>🔗 [qwenlm.github.io](https://qwenlm.github.io/blog/qwen3/): Qwen3: Think deeper, act faster</small>


| 🔥🔥: 235 \| 💬: [75](https://news.ycombinator.com/item?id=43825900) \| 🗓️ 2025-04-28


<br />
阿里云推出新一代大语言模型**Qwen3**，包含2350亿参数的MoE模型**Qwen3-235B-A22B**和6款密集模型，性能超越前代并支持**混合思维模式**（深度推理/快速响应）。模型预训练数据达36万亿token，覆盖119种语言，特别优化了编程与数学能力。开源版本支持Hugging Face等平台，并提供**动态思维切换**功能，用户可通过`/think`指令灵活控制响应方式。

---

## <a name="8"></a>8. 苹果芯片上高效部署大语言模型：系统工程师实战指南 
<small>🔗 [github.com](https://github.com/skyzh/tiny-llm): Tiny-LLM – a course of serving LLM on Apple Silicon for systems engineers</small>


| 🔥🔥: 205 \| 💬: [23](https://news.ycombinator.com/item?id=43820022) \| 🗓️ 2025-04-28


<br />
该项目是一个**面向系统工程师**的教程，指导如何在Apple Silicon上使用MLX框架**从零构建大语言模型（LLM）服务**。内容涵盖注意力机制、量化计算、KV缓存等核心优化技术，并计划实现连续批处理、推测解码等高级功能。目前文档和代码仍在开发中，但已提供部分章节（如RoPE、Transformer块）的实践示例。社区可通过Discord参与协作，目标是通过底层API深入理解**Qwen2模型的高效服务原理**。

---

## <a name="9"></a>9. 纯WebGL图像编辑器：在线滤镜、裁剪与透视校正工具 
<small>🔗 [github.com](https://github.com/xdadda/mini-photo-editor): Show HN: A pure WebGL image editor with filters, crop and perspective correction</small>


| 🔥🔥: 131 \| 💬: [33](https://news.ycombinator.com/item?id=43823044) \| 🗓️ 2025-04-28


<br />
这是一款基于**WebGL2技术**的在线图片编辑器，支持**滤镜特效**、**裁剪**和**透视校正**功能。项目使用MIT协议开源，核心依赖`mini-js`和`mini-gl`库。目前获得21颗星、2个分叉，开发者可通过提供的链接直接体验。编辑器无需安装，适合快速处理图片需求。

---

## <a name="10"></a>10. 加州高铁项目远未终结，批评者忽视了真正挑战 
<small>🔗 [asteriskmag.com](https://asteriskmag.com/issues/10/reports-of-the-death-of-california-high-speed-rail-have-been-greatly-exaggerated): Reports of the death of California High-Speed Rail have been greatly exaggerated</small>


| 🔥🔥: 114 \| 💬: [201](https://news.ycombinator.com/item?id=43824544) \| 🗓️ 2025-04-28


<br />
尽管加州高铁项目（**CAHSR**）面临资金短缺、政治分歧和工程延误等问题，但批评者忽略了其核心困境：**缺乏持续稳定的资金支持**。项目初期依赖的联邦配套资金未能到位，导致建设停滞，而**中央谷地段**的施工又因规划与执行脱节推高成本。地质难题（如穿越山脉的隧道）才是真正的成本驱动因素，而非政治低效。尽管州长纽瑟姆曾缩减规划范围，但2023年联邦拨款重启了希望。批评者提出的替代方案（如沿I-5公路布线）既不现实，也无法服务人口密集区。加州高铁的困境更多源于**系统性投入不足**，而非单纯的技术或管理失败。

---

## <a name="11"></a>11. 现实检验：OpenAI的荒谬营收预言 
<small>🔗 [wheresyoured.at](https://www.wheresyoured.at/reality-check/): Reality Check</small>


| 🔥🔥: 113 \| 💬: [85](https://news.ycombinator.com/item?id=43823492) \| 🗓️ 2025-04-28


<br />
作者激烈批评科技媒体对**OpenAI**不切实际的乐观报道，尤其针对其宣称2029年营收将达**1250亿美元**的预测。文中指出，OpenAI的**AI代理产品**尚未成熟，却声称今年能创收30亿美元，主要依赖软银单一客户。此外，**推理成本**逐年飙升（2025年预计60亿美元），而订阅收入仅80亿，商业模式堪忧。作者斥责媒体盲目追捧，忽视基本经济逻辑，并嘲讽行业对"早期阶段"的辩解，强调当前AI技术远未达到盈利规模。

---

## <a name="12"></a>12. 开源AI智能体工作流构建工具：Sim Studio 
<small>🔗 [github.com](https://github.com/simstudioai/sim): Show HN: Sim Studio – Open-Source Agent Workflow GUI</small>


| 🔥🔥: 105 \| 💬: [36](https://news.ycombinator.com/item?id=43823096) \| 🗓️ 2025-04-28


<br />
Sim Studio是一款**开源**的AI智能体工作流构建平台，基于**Next.js**框架开发，支持可视化编辑与测试。提供三种部署方式：**Docker容器**（推荐）、开发容器和手动配置，支持本地模型集成（如Ollama）。核心功能包括基于ReactFlow的流程编辑器、PostgreSQL数据库及Drizzle ORM，采用Apache-2.0许可。项目已获1.6k星标，适合开发者快速搭建**Agentic工作流**。

---

## <a name="13"></a>13. 《地海传奇》全集：勒古恩的奇幻经典 
<small>🔗 [lars.ingebrigtsen.no](https://lars.ingebrigtsen.no/2025/04/28/book-club-2025-the-books-of-earthsea-by-ursula-k-le-guin/): The Books of Earthsea by Ursula K. Le Guin</small>


| 🔥🔥: 101 \| 💬: [45](https://news.ycombinator.com/item?id=43823462) \| 🗓️ 2025-04-28


<br />
作者重温了乌苏拉·勒古恩的**《地海传奇》**全六册插图合集，由查尔斯·维斯绘制。尽管合订本厚重且字体略小，但维斯的**铅笔插画**与勒古恩的协作令人赞叹。系列从童话风格的首作渐变为**《特哈努》**的暗黑成人叙事，最终以第六册圆满收尾。短篇集和2018年遗作更添彩蛋。**经典历久弥新**，但读完想换口味。

---

## <a name="14"></a>14. 免费发布软件的最佳实践 
<small>🔗 [simonwillison.net](https://simonwillison.net/2025/Apr/28/give-it-away-for-free/): Giving Software Away for Free</small>


| 🔥: 72 \| 💬: [46](https://news.ycombinator.com/item?id=43824153) \| 🗓️ 2025-04-28


<br />
作者推荐使用**静态HTML和JavaScript**搭配免费可靠的网络托管服务（如GitHub Pages）来发布完全免费的软件，这种方式借助**WebAssembly**和Pyodide等工具能支持丰富的应用类型。关键在于选择长期稳定的托管平台（如GitHub），避免因维护成本或平台变动导致服务中断。同时强调**开源许可**虽必要，但直接提供可运行的链接对用户更实用。文章对比了Heroku等平台的兴衰，突显托管选择的重要性。

---

## <a name="15"></a>15. 我们在车祸数据中发现了保险欺诈 
<small>🔗 [levs.fyi](https://www.levs.fyi/blog/we-found-insurance-fraud-in-our-crash-data/): We Found Insurance Fraud in Our Crash Data</small>


| 🔥: 69 \| 💬: [65](https://news.ycombinator.com/item?id=43821578) \| 🗓️ 2025-04-28


<br />
Matrisk AI团队在构建车辆碰撞地理风险评分时，意外通过**车辆识别码（VIN）**和事故时间轴发现了潜在的保险欺诈模式。分析约1500万起事故后，他们识别出可疑特征：**同一车辆6个月内多次事故**、**频繁更换保险公司**、**夜间单车无证人碰撞**等。例如，某车辆3次事故均发生在低流量时段，且保险公司在事故前快速切换。虽然无法直接定罪，但这些异常模式为保险公司调查提供了重要线索，揭示了数据在识别欺诈中的价值。

---

## <a name="16"></a>16. 视觉Transformer需要寄存器 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2309.16588): Vision Transformers Need Registers</small>


| 🔥: 67 \| 💬: [8](https://news.ycombinator.com/item?id=43823485) \| 🗓️ 2025-04-28


<br />
该论文发现**监督学习和自监督学习**的ViT网络在特征图中存在**高范数令牌**的伪影，这些令牌通常出现在图像低信息量的背景区域。作者提出通过向输入序列添加额外令牌（寄存器）来解决问题。该方法不仅修复了特征图异常，还在密集视觉预测任务中刷新了自监督模型的**SOTA性能**，同时提升了特征图和注意力图的下游处理效果。

---

## <a name="17"></a>17. GitHub下架破解OnlyFans DRM的Widevine项目 
<small>🔗 [torrentfreak.com](https://torrentfreak.com/drm-free-onlyfans-downloads-see-widevine-project-nuked-from-github-250428/): DRM-Free OnlyFans Downloads See Widevine Project Nuked from GitHub</small>


| 🔥: 59 \| 💬: [14](https://news.ycombinator.com/item?id=43825716) \| 🗓️ 2025-04-28


<br />
数字版权管理（**DRM**）系统（如谷歌的**Widevine**）被广泛用于保护流媒体内容，但屡遭破解。2025年4月，OnlyFans母公司Fenix International以违反DMCA为由，要求GitHub删除**CDRM-Project**仓库，称其包含破解Widevine的代码，可将受保护视频转为无DRM的MP4。尽管GitHub给予开发者申诉机会，最终整个项目及分叉仓库仍被移除。Fenix罕见地提供了项目所有者信息，凸显其打击力度。目前该项目已迁移至独立网站，但前景未卜。DRM的过度限制常损害正版用户体验，反而可能助长破解需求。

---

## <a name="18"></a>18. 让AI编程助手自主调试的Web评估工具 
<small>🔗 [github.com](https://github.com/Operative-Sh/web-eval-agent): Show HN: Web-eval-agent – Let the coding agent debug itself</small>


| 🔥: 56 \| 💬: [9](https://news.ycombinator.com/item?id=43822659) \| 🗓️ 2025-04-28


<br />
这是一个基于**MCP服务器**的自动化Web应用评估工具，可让**AI编程助手**自主测试和调试代码。核心功能包括：通过**Playwright**实现2倍速浏览器操作、智能捕获网络请求和控制台错误，并将结果反馈至开发环境。支持快速安装（macOS/Linux/Windows），提供实时日志看板。示例展示了完整的API密钥删除流程测试，验证了UX流畅性。开源项目（Apache-2.0协议），已有373星，适合集成到IDE中提升开发效率。

---

## <a name="19"></a>19. AI营销泛滥时代，出站销售将走向终结？ 
<small>🔗 [rnikhil.com](https://rnikhil.com/2025/04/25/sales-outbound-ai-dead): Is outbound going to die?</small>


| 🔥: 56 \| 💬: [66](https://news.ycombinator.com/item?id=43823851) \| 🗓️ 2025-04-28


<br />
AI驱动的销售工具正以**超个性化内容**和**海量触达**重塑营销，短期内效果显著。但用户将逐渐对**AI垃圾信息**产生疲劳，导致信任崩塌、转化率下降。当所有企业都使用相同工具轰炸同一批客户时，竞争将陷入红海。未来，**私域流量**和**人际关系**成为核心——通过社群运营、口碑传播和CEO个人品牌构建护城河，企业自有渠道与网络效应将取代传统出站销售。

---

## <a name="20"></a>20. 葡萄牙和西班牙全国停电导致互联网中断 
<small>🔗 [twitter.com](https://twitter.com/CloudflareRadar/status/1916811587408536055): Nationwide Power Outages Also Disrupt Internet Traffic in Portugal and Spain</small>


| 🔥: 54 \| 💬: [2](https://news.ycombinator.com/item?id=43819914) \| 🗓️ 2025-04-28


<br />
由于**全国性停电**，葡萄牙和西班牙的**互联网流量**受到严重影响。用户访问社交媒体平台时遇到技术问题，提示需启用**JavaScript**或更换浏览器。部分隐私扩展也可能导致访问异常，建议禁用后重试。此次事件凸显基础设施脆弱性对数字服务的关键影响。

---

## <a name="21"></a>21. 问题不在激励机制（2018） 
<small>🔗 [talyarkoni.org](https://talyarkoni.org/blog/2018/10/02/no-its-not-the-incentives-its-you/): It's Not the Incentives (2018)</small>


| 🔥: 42 \| 💬: [48](https://news.ycombinator.com/item?id=43824534) \| 🗓️ 2025-04-28


<br />
本文批判了科学界日益普遍的借口——将**不良行为**归咎于**“激励机制”**。作者指出，许多科学家以“体制逼迫”为由，合理化数据操纵、忽视学术伦理等行为，却对同类借口在极端案例（如数据造假）中的使用嗤之以鼻。这种双重标准暴露了**虚伪性**：若激励机制不能为严重学术不端开脱，也不该为轻微违规辩护。作者强调，科学家应拒绝“体制无能”的消极叙事，主动承担伦理责任，而非将个人利益凌驾于学术诚信之上。

---

## <a name="22"></a>22. 首款iOS心率区间分析工具：Heart Rate Zones Plus 
<small>🔗 [apps.apple.com](https://apps.apple.com/us/app/heart-rate-zones-plus/id6744743232): Show HN: Heart Rate Zones Plus – The first iOS app I ever developed</small>


| 🔥: 42 \| 💬: [26](https://news.ycombinator.com/item?id=43824583) \| 🗓️ 2025-04-28


<br />
这是一款专注于**心率区间追踪**的iOS健康应用，开发者Tobias Willmann通过Apple HealthKit获取数据，**不收集用户隐私**。核心功能包括：自定义时段（日/周/月）的**五大心率区间统计**、运动类型与区间关联分析、多种科学计算最大心率公式（含性别差异），以及个性化目标设定。支持深色/浅色模式，适合运动员、康复者及量化自我爱好者，通过可视化进度条帮助用户**精准优化训练强度**。应用仅6.6MB，免费下载。

---

## <a name="23"></a>23. 开源平台ACI.dev：为AI代理提供600+工具的统一调用接口 
<small>🔗 [github.com](https://github.com/aipotheosis-labs/aci): Show HN: Open-Source Infra for a Single MCP Server to Search and Use 600 Tools</small>


| 🔥: 41 \| 💬: [0](https://news.ycombinator.com/item?id=43821038) \| 🗓️ 2025-04-28


<br />
ACI.dev是一个**开源基础设施平台**，专为AI代理设计，提供**600多种预置工具集成**（如Google Calendar、Slack等），支持多租户认证、细粒度权限管理和动态工具发现。开发者可通过**统一MCP服务器**或轻量级Python SDK直接调用功能，无需重复开发OAuth流程和API客户端。其核心优势包括自然语言权限控制、框架无关性及Apache 2.0开源协议，适用于个人助手、销售自动化等场景。平台提供完整开发文档和社区支持，助力快速构建生产级AI应用。

---

## <a name="24"></a>24. 未经授权的AI机器人正在侵蚀Reddit的社交性 
<small>🔗 [mssv.net](https://mssv.net/2025/04/27/unauthorised-ai-bots-on-r-changemyview-are-eroding-sociality/): Unauthorised AI Bots on Reddit Are Eroding Sociality</small>


| 🔥: 40 \| 💬: [35](https://news.ycombinator.com/item?id=43821600) \| 🗓️ 2025-04-28


<br />
苏黎世大学研究人员在Reddit论坛r/changemyview秘密使用**AI机器人**发表评论，内容涉及敏感话题（如性侵受害者、反对BLM的黑人等），但未标注AI生成。尽管研究者辩称实验“利大于弊”且获伦理委员会批准，但此举引发争议：**未披露的AI互动可能扭曲人类说服力的研究结果**，并加剧网络信任危机。  

文章指出，**匿名AI加剧了线上社交的虚假性**，促使人们转向封闭社群或线下互动。哲学家梅洛-庞蒂的现象学理论被引用，强调真实人际接触对确认“他者真实性”的重要性。作者呼吁创造新型线下社交形式，而非怀旧式复刻，以对抗日益机械化的数字交流。

---

## <a name="25"></a>25. 《暗淡蓝点：为何这张照片让我们深感渺小》 
<small>🔗 [aeon.co](https://aeon.co/essays/why-pale-blue-dot-generates-feelings-of-cosmic-insignificance): Why Pale Blue Dot generates feelings of cosmic insignificance</small>


| 🔥: 39 \| 💬: [64](https://news.ycombinator.com/item?id=43822880) \| 🗓️ 2025-04-28


<br />
1990年情人节，NASA的旅行者1号从60亿公里外拍摄了地球照片**《暗淡蓝点》**。图中地球仅是阳光中的一粒微尘，凸显了人类在宇宙中的**微不足道**。与1968年《地出》展现的生机勃勃不同，这张照片引发了对**宇宙沉默**的恐惧——如帕斯卡所言，无限虚空中的孤独感。尽管有人认为这种渺小感源于认知局限（如人类尺度难以理解光年），但图像的核心冲击在于：**承载人类一切意义的家园，在宇宙中几乎不可见**。这种反差迫使人们重新思考自身存在的意义。

---
