---
layout: page
title: 勒西科技日报 - 2025年03月26日
date: 2025-03-26 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. Debian bookworm 实时镜像现已实现完全可复现；
1. OpenAI为Agents SDK添加MCP支持；
1. 一封写给CSV格式的情书；
1. 加美航线需求暴跌超70%，航空业面临严峻挑战；
1. 谷歌下周起将闭门开发Android系统；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. Debian bookworm 实时镜像现已实现完全可复现 
<small>🔗 [lwn.net](https://lwn.net/Articles/1015402/): Debian bookworm live images now reproducible</small>


| 🔥🔥: 433 \| 💬: [91](https://news.ycombinator.com/item?id=43484520) \| 🗓️ 2025-03-26


<br />
Debian 开发者 Roland Clobus 在**可复现构建**邮件列表中宣布，Debian 12.10（代号 "bookworm"）的**实时镜像**现已达到 100% 可复现。这一进展意味着用户可以通过相同构建流程生成完全一致的镜像文件，进一步增强了安全性和可信度。详细信息可参考 Debian 维基上的相关页面。

---

## <a name="2"></a>2. OpenAI为Agents SDK添加MCP支持 
<small>🔗 [openai.github.io](https://openai.github.io/openai-agents-python/mcp/): OpenAI adds MCP support to Agents SDK</small>


| 🔥🔥: 412 \| 💬: [140](https://news.ycombinator.com/item?id=43485566) \| 🗓️ 2025-03-26


<br />
**模型上下文协议(MCP)** 是一种为LLM提供工具和上下文的开放标准协议，类似于AI应用的"USB-C接口"，实现模型与数据源的标准化连接。Agents SDK现已支持MCP，可通过**MCPServerStdio**（本地子进程）或**MCPServerSse**（远程HTTP服务）接入各类MCP服务器。每次运行Agent时，SDK会调用服务器的`list_tools()`方法，并在LLM使用工具时触发`call_tool()`。新增的`cache_tools_list`参数可缓存工具列表以降低延迟，还支持调用`invalidate_tools_cache()`清除缓存。完整示例见代码库的`examples/mcp`目录。

---

## <a name="3"></a>3. 一封写给CSV格式的情书 
<small>🔗 [github.com](https://github.com/medialab/xan/blob/master/docs/LOVE_LETTER.md): A love letter to the CSV format</small>


| 🔥🔥: 316 \| 💬: [314](https://news.ycombinator.com/item?id=43484382) \| 🗓️ 2025-03-26


<br />
尽管常被诟病为“过时”，**CSV格式**凭借其**极简设计**（逗号分隔值、换行分隔行）和**普适性**（纯文本、无版权、跨平台）始终屹立不倒。它支持流式处理、动态类型解析，甚至逆向读取仍有效，尤其适合**海量数据**场景。虽然列式存储（如Parquet）在特定场景更优，但CSV的**人类可读性**和**低开销**使其成为不可替代的数据交换基石。正如作者所言：“Excel讨厌CSV，恰恰证明它做对了什么。”

---

## <a name="4"></a>4. 加美航线需求暴跌超70%，航空业面临严峻挑战 
<small>🔗 [onemileatatime.com](https://onemileatatime.com/news/airline-demand-canada-united-states-collapses/): Airline Demand Between Canada and United States Collapses, Down 70%+</small>


| 🔥🔥: 283 \| 💬: [358](https://news.ycombinator.com/item?id=43485649) \| 🗓️ 2025-03-26


<br />
数据显示，2025年夏季**加美跨境航班预订量**同比骤降71.4%至75.7%，例如2024年4月预订量为121万张，而2025年同期仅29.6万张。尽管航空公司已削减1.6%-3.5%的航班，但调整远未匹配需求下滑。**加拿大航空**作为最大跨境运营商或被迫转向国内及其他国际市场。分析指出，政治摩擦与关税政策可能是主因，但行业复苏前景仍不明朗。

---

## <a name="5"></a>5. 谷歌下周起将闭门开发Android系统 
<small>🔗 [9to5google.com](https://9to5google.com/2025/03/26/google-android-aosp-developement-private/): Google will develop Android OS behind closed doors starting next week</small>


| 🔥🔥: 242 \| 💬: [176](https://news.ycombinator.com/item?id=43484927) \| 🗓️ 2025-03-26


<br />
谷歌宣布从下周开始，**Android操作系统**的开发将转为闭门模式，不再公开代码。此举旨在加快迭代速度并加强**系统安全性**。同时，谷歌发布了**Gemini 2.5 Pro**，称其为目前“最智能的AI模型”，具备内置推理能力。这一调整可能影响第三方厂商的适配节奏。

---

## <a name="6"></a>6. 选择Next.js前必须了解的三件事 
<small>🔗 [eduardoboucas.com](https://eduardoboucas.com/posts/2025-03-25-you-should-know-this-before-choosing-nextjs/): You should know this before choosing Next.js</small>


| 🔥🔥: 236 \| 💬: [108](https://news.ycombinator.com/item?id=43481295) \| 🗓️ 2025-03-26


<br />
本文揭露了Next.js作为开源框架存在的三大问题：**缺乏适配器支持**导致其他平台难以兼容，**无官方Serverless方案**迫使开发者依赖Vercel，以及**Vercel专属代码路径**造成功能垄断。作者以近期安全漏洞事件为例，批评Vercel对社区透明度不足，8天后才通知竞争对手Netlify，暴露出**开源治理的隐患**。核心矛盾在于框架与商业公司的边界模糊，可能影响技术选型的长期自由度。

---

## <a name="7"></a>7. 告别核心类型：回归我们熟悉的Go语言 
<small>🔗 [go.dev](https://go.dev/blog/coretypes): Good-bye core types; Hello Go as we know and love it</small>


| 🔥🔥: 221 \| 💬: [120](https://news.ycombinator.com/item?id=43483842) \| 🗓️ 2025-03-26


<br />
Go 1.18引入了泛型，带来了**类型参数**、**类型约束**等新特性，同时引入了抽象概念**核心类型**以简化泛型操作数的处理。然而，核心类型在实际应用中存在诸多问题：规则过于严格、增加了学习复杂度，并使得语言规范显得冗余。Go 1.25决定移除核心类型概念，回归更直接的描述方式。这一改动简化了语言规范，使非泛型代码更易理解，同时为未来功能扩展（如更灵活的切片操作）铺平道路。核心改动包括删除相关规范章节、优化编译器错误提示，确保行为不变但表达更清晰。

---

## <a name="8"></a>8. 博茨瓦纳成功发射首颗卫星BOTSAT-1 
<small>🔗 [spaceinafrica.com](https://spaceinafrica.com/2025/03/15/botswana-successfully-launches-first-satellite-botsat-1/): Botswana Successfully Launches First Satellite, Botsat-1</small>


| 🔥🔥: 200 \| 💬: [74](https://news.ycombinator.com/item?id=43483660) \| 🗓️ 2025-03-26


<br />
2025年3月15日，博茨瓦纳首颗卫星**BOTSAT-1**由SpaceX猎鹰9号火箭搭载，在美国范登堡太空军基地成功发射。该卫星由博茨瓦纳国际科技大学（BIUST）与EnduroSat合作开发，采用南非Dragonfly Aerospace的**Mantis高光谱成像仪**，将为农业、环境监测和城市规划提供关键数据。此次发射标志着博茨瓦纳迈入太空技术领域，并计划后续开发**BOTSAT-2**。卫星数据将通过BIUST地面站接收，助力非洲区域可持续发展。

---

## <a name="9"></a>9. 超轻量WASM：快速、安全且无操作系统的JavaScript执行方案 
<small>🔗 [opensource.microsoft.com](https://opensource.microsoft.com/blog/2025/03/26/hyperlight-wasm-fast-secure-and-os-free/): Hyperlight WASM: Fast, secure, and OS-free</small>


| 🔥🔥: 198 \| 💬: [76](https://news.ycombinator.com/item?id=43482556) \| 🗓️ 2025-03-26


<br />
本文介绍如何构建一个**Hyperlight C客户端**，实现在**安全沙箱**中高效运行JavaScript代码。通过**WebAssembly (WASM)**技术，该方案无需依赖操作系统，兼具高性能与隔离性。文章详细演示了开发步骤，并强调其在嵌入式场景与边缘计算中的潜力。核心优势包括极低资源占用和防止恶意代码逃逸的设计。

---

## <a name="10"></a>10. 甲骨文客户证实云服务泄露数据属实 
<small>🔗 [bleepingcomputer.com](https://www.bleepingcomputer.com/news/security/oracle-customers-confirm-data-stolen-in-alleged-cloud-breach-is-valid/): Oracle customers confirm data stolen in alleged cloud breach is valid</small>


| 🔥🔥: 174 \| 💬: [40](https://news.ycombinator.com/item?id=43486945) \| 🗓️ 2025-03-26


<br />
尽管**甲骨文**否认其云服务遭入侵，但多家企业向BleepingComputer确认，黑客提供的**600万用户数据样本**真实有效。黑客声称利用漏洞（CVE-2021-35587）入侵服务器，并展示了在甲骨文服务器上创建文件的证据。部分泄露数据包含企业域名、邮箱及加密密码，但甲骨文坚称“**未发生云服务泄露**”。网络安全公司Cloudsek发现涉事服务器已下线，但甲骨文未回应后续质询。

---

## <a name="11"></a>11. Linux内核6.14发布：性能飞跃，Windows兼容性大幅提升 
<small>🔗 [zdnet.com](https://www.zdnet.com/article/linux-kernel-6-14-is-a-big-leap-forward-in-performance-and-windows-compatibility/): Linux kernel 6.14 is a big leap forward in performance and Windows compatibility</small>


| 🔥🔥: 165 \| 💬: [110](https://news.ycombinator.com/item?id=43483567) \| 🗓️ 2025-03-26


<br />
Linux内核6.14正式推出，带来多项重磅更新。**NTSYNC驱动**显著优化了Wine和Steam Play的Windows程序运行性能，被赞为“将彻底改变Linux游戏体验”。此外，新增对**AMD RDNA 4显卡**的支持，搭配RADV驱动可提升游戏性能。内核还集成**AMDXDNA驱动**，支持AMD神经网络单元，加速AI任务处理。其他改进包括Rust语言支持扩展、Snapdragon 8 Elite芯片优化，以及修复GhostWrite漏洞。此次更新覆盖游戏、AI及移动设备领域，进一步巩固Linux的多场景优势。

---

## <a name="12"></a>12. npm发现恶意软件通过反向感染本地合法包 
<small>🔗 [reversinglabs.com](https://www.reversinglabs.com/blog/malicious-npm-patch-delivers-reverse-shell): Malware found on NPM infecting local package with reverse shell</small>


| 🔥🔥: 164 \| 💬: [101](https://news.ycombinator.com/item?id=43484845) \| 🗓️ 2025-03-26


<br />
研究人员首次发现**恶意npm本地安装包**正在感染其他**合法包**。这些恶意软件通过**反向shell**实施攻击，威胁开发环境安全。该发现凸显了依赖包管理的潜在风险，需加强安全审查。

---

## <a name="13"></a>13. 生成式AI对批判性思维的负面影响 
<small>🔗 [microsoft.com](https://www.microsoft.com/en-us/research/wp-content/uploads/2025/01/lee_2025_ai_critical_thinking_survey.pdf): The Impact of Generative AI on Critical Thinking [pdf]</small>


| 🔥🔥: 162 \| 💬: [112](https://news.ycombinator.com/item?id=43484224) \| 🗓️ 2025-03-26


<br />
微软和卡内基梅隆大学的研究发现，**过度依赖生成式AI**会导致人类**批判性思维减弱**，甚至造成**认知能力退化**。研究指出，自动化虽能处理常规任务，但剥夺了人类锻炼判断力的机会，导致面对异常情况时能力不足。该研究调查了319名知识工作者，涵盖教师、交易员和护士等职业的AI使用案例，结果显示用户对AI输出的评估信心普遍不足。

---

## <a name="14"></a>14. 特朗普顾问在Signal上泄露的袭击计划引发安全争议 
<small>🔗 [theatlantic.com](https://www.theatlantic.com/politics/archive/2025/03/signal-group-chat-attack-plans-hegseth-goldberg/682176/): Here are the Attack Plans That Trump's Advisers Shared on Signal</small>


| 🔥🔥: 153 \| 💬: [48](https://news.ycombinator.com/item?id=43481521) \| 🗓️ 2025-03-26


<br />
《大西洋月刊》披露，特朗普政府高级官员在**Signal加密群聊**中讨论了针对也门胡塞武装的军事行动细节，包括**战机起飞时间**和攻击目标。尽管官员坚称信息未涉密，但专家警告此类非安全通讯可能危及美军人员安全。报道显示，国防部长海格思在行动前31分钟于群聊中发布作战时间表，若信息外泄恐导致灾难性后果。白宫虽否认泄密，却以"敏感内部讨论"为由反对公开完整聊天记录。事件暴露了政府高层对**国家安全协议**的漠视。

---

## <a name="15"></a>15. 谷歌将Android开发转为私有化，但保持开源发布 
<small>🔗 [arstechnica.com](https://arstechnica.com/gadgets/2025/03/google-makes-android-development-private-will-continue-open-source-releases/): Google makes Android development private, will continue open source releases</small>


| 🔥🔥: 145 \| 💬: [65](https://news.ycombinator.com/item?id=43485950) \| 🗓️ 2025-03-26


<br />
谷歌宣布将**Android系统开发**从公开的AOSP分支转移至内部私有分支，以简化流程并避免版本同步问题。未来新版本完成后，源码仍会照常发布至**AOSP开源项目**，但开发过程中的透明度将降低。此举可能影响开发者提前获取新特性信息，但普通用户无感知。谷歌称此举是为提升效率，部分核心组件（如蓝牙和内核）也将转入内部开发。

---

## <a name="16"></a>16. 如何删除你的23andMe基因数据 
<small>🔗 [eff.org](https://www.eff.org/deeplinks/2025/03/how-delete-your-23andme-data): How to Delete Your 23andMe Data</small>


| 🔥🔥: 141 \| 💬: [76](https://news.ycombinator.com/item?id=43486236) \| 🗓️ 2025-03-26


<br />
基因检测公司23andMe近期申请破产，其收集的百万用户**基因数据可能被出售**。若想避免数据流入第三方，建议立即删除账户信息。操作分两步：**先下载数据**（包括原始基因数据、亲属关系报告等），再通过账户设置**永久删除数据**（需邮件确认）。律师提醒，基因数据包含高度敏感信息（如疾病风险、家族史），破产不应成为数据被随意转卖的理由。其他基因公司也应重视用户隐私权。

---

## <a name="17"></a>17. Gemini 2.5 Pro评估任务可行性并拒绝不合理请求 
<small>🔗 [everything.intellectronica.net](https://everything.intellectronica.net/p/negotiating-with-the-machine): Gemini 2.5 Pro reasons about task feasibility</small>


| 🔥🔥: 135 \| 💬: [60](https://news.ycombinator.com/item?id=43479985) \| 🗓️ 2025-03-26


<br />
用户要求**Gemini 2.5 Pro**复刻经典的**ReBirth RB-338合成器**，但AI经过分析后认为该任务**不可行**，原因是项目复杂度高，涉及数字信号处理、Web音频API等专业知识，需团队数月甚至数年完成。随后，Gemini提供了简化版合成器的代码框架作为替代方案。这一行为展示了AI对自身能力的理性评估，而非盲目尝试。最终用户通过协商获得了基础但可运行的合成器 demo。

---

## <a name="18"></a>18. 后末日操作系统：Collapse OS 
<small>🔗 [collapseos.org](http://collapseos.org/): Collapse OS</small>


| 🔥🔥: 130 \| 💬: [124](https://news.ycombinator.com/item?id=43482705) \| 🗓️ 2025-03-26


<br />
Collapse OS 是一款专为**文明崩溃后**环境设计的 **Forth 操作系统**，旨在帮助用户通过简易设备和拾荒零件维持对微控制器的编程能力。其核心功能包括：在低资源硬件（如Z80、8086）上运行、支持多种MCU的汇编编译、内置文本/二进制编辑器，并能通过串行等简陋接口操作。系统强调**自给自足**，仅需基础工具即可从POSIX环境构建，代码精简（不足2000行）。开发者Virgil Dupras希望该项目能为后末日技术重建提供基石，相关资源已开源。

---

## <a name="19"></a>19. 欧洲最大创客空间落户柏林 
<small>🔗 [berlin-partner.de](https://www.berlin-partner.de/en/news/detail/europas-groesster-makerspace): Europe's Largest Makerspace</small>


| 🔥🔥: 129 \| 💬: [125](https://news.ycombinator.com/item?id=43480396) \| 🗓️ 2025-03-26


<br />
柏林马林多夫区的**ringberlin模型园区**正在建设欧洲最大的创客空间，由知名硬件加速器**MotionLab.Berlin**运营。该空间占地17,000平方米，提供**现代化设施**，包括车间、办公区和测试区，旨在促进创新与合作。柏林州政府投资3600万欧元支持该项目，总预算超6000万欧元。该创客空间将推动深科技发展，并打造**碳中和园区**，成为柏林工业创新的核心枢纽。

---

## <a name="20"></a>20. 塔夫茨大学学生遭蒙面探员逮捕视频曝光 
<small>🔗 [bostonglobe.com](https://www.bostonglobe.com/2025/03/26/metro/tufts-student-video-shows-arrest/): Tufts student: Video shows masked agents arresting Rumeysa Ozturk</small>


| 🔥🔥: 125 \| 💬: [29](https://news.ycombinator.com/item?id=43485577) \| 🗓️ 2025-03-26


<br />
根据《波士顿环球报》获得的监控录像及目击者描述，土耳其籍**塔夫茨大学博士生**Rumeysa Ozturk在校园附近街道被**5名便衣探员**围捕。探员未出示证件且佩戴口罩，强行没收其手机并戴上手铐，全程仅2分半钟。律师指控国土安全部**非法拘留**，但当事人至今下落不明且未被起诉。目击者称Ozturk被捕时哭喊“我是学生”，另有探员尾随旁观者。事件疑与特朗普政府打压亲巴勒斯坦学生活动有关。

---

## <a name="21"></a>21. Playwright MCP：基于结构化数据的浏览器自动化工具 
<small>🔗 [github.com](https://github.com/microsoft/playwright-mcp): Playwright Tools for MCP</small>


| 🔥🔥: 121 \| 💬: [24](https://news.ycombinator.com/item?id=43485740) \| 🗓️ 2025-03-26


<br />
Playwright MCP 是一个基于 **Playwright** 的服务器，通过 **可访问性快照**（非像素输入）为LLM提供浏览器自动化能力，无需依赖视觉模型。支持两种模式：默认的**快照模式**（高效稳定）和**视觉模式**（基于截图交互）。功能包括网页导航、表单填写、数据提取等，适用于VS Code集成或无界面运行。关键优势：**轻量快速**、**LLM友好**、**确定性操作**。

---

## <a name="22"></a>22. Waymo自动驾驶事故率远低于人类司机 
<small>🔗 [understandingai.org](https://www.understandingai.org/p/human-drivers-keep-crashing-into): Waymos crash less than human drivers</small>


| 🔥🔥: 111 \| 💬: [120](https://news.ycombinator.com/item?id=43487231) \| 🗓️ 2025-03-26


<br />
Waymo在行驶5000万英里后，数据显示其自动驾驶车辆的事故率显著低于人类驾驶员。**大多数事故由人类司机违规引发**，如追尾静止的Waymo车辆或闯红灯。Waymo仅对极少数事故负有责任，且其**每英里事故率比人类低83%**。保险索赔数据也显示，Waymo的责任索赔减少约90%。尽管自动驾驶技术仍面临挑战，但其**安全性已明显优于人类驾驶**。

---

## <a name="23"></a>23. 开发者技能在AI辅助编程中的关键作用 
<small>🔗 [martinfowler.com](https://martinfowler.com/articles/exploring-gen-ai.html#memo-13): The role of developer skills in agentic coding</small>


| 🔥: 98 \| 💬: [57](https://news.ycombinator.com/item?id=43480964) \| 🗓️ 2025-03-26


<br />
本文探讨了**生成式AI**（如大型语言模型LLMs）如何改变软件开发实践。作者通过Thoughtworks的实践，分析了当前AI编程工具的分类（如代码生成、代码解释、文档转换）、交互模式（聊天界面、编辑器内辅助、CLI）及模型特性（训练数据、上下文窗口大小）。以GitHub Copilot为例，指出**开发者仍需深刻理解代码逻辑**以验证AI生成的内容，尤其在测试环节。文章强调，尽管AI能提升效率，但**技术栈普及度**和**提示词质量**显著影响工具实用性，未来发展方向可能聚焦于模型优化和开源生态。

---

## <a name="24"></a>24. 堆内存问题的严重性 
<small>🔗 [rachelbythebay.com](https://rachelbythebay.com/w/2025/03/26/atop/): Problems with the heap</small>


| 🔥: 94 \| 💬: [21](https://news.ycombinator.com/item?id=43485980) \| 🗓️ 2025-03-26


<br />
作者用幼儿园游乐场使用锋利材料的比喻，警示当前**堆内存漏洞**的潜在危险。通过终端演示，当`user1`运行某工具时，`user2`的进程会因`malloc()`错误或段错误崩溃，若`user2`是**root权限**，攻击者可能接管系统。作者虽未深入漏洞细节，但强调其危害性，呼吁用户**立即停止运行相关程序**，尤其避免以root身份操作。

---

## <a name="25"></a>25. Firefox终将支持渐进式网页应用(PWA) 
<small>🔗 [omgubuntu.co.uk](https://www.omgubuntu.co.uk/2025/03/firefox-nightly-supports-web-apps-taskbar-tabs): Firefox Is Finally (Re)Adding Support for Web Apps</small>


| 🔥: 93 \| 💬: [78](https://news.ycombinator.com/item?id=43484542) \| 🗓️ 2025-03-26


<br />
Firefox近日在Nightly版本中新增实验性标志`browser.taskbarTabs.enabled`，为**渐进式网页应用(PWA)**支持铺路。与Chromium等浏览器不同，Firefox的PWA功能将保留地址栏、扩展等核心浏览器特性，仅替换"新建标签页"按钮为普通窗口入口。  

产品经理David Rubino强调，该设计旨在提供**应用化体验**的同时保持Firefox特色，支持链接关联、独立任务栏图标等功能。目前该标志尚未生效，但开发进度表明功能即将上线。尽管方案被质疑为"最小可行产品"，但用户对垂直标签、多账号管理等迟来功能的落地仍表期待。

---
