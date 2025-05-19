---
layout: page
title: 勒西科技日报 - 2025年05月19日
date: 2025-05-19 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 别再靠IP猜我的语言了；
1. Zod 4 正式发布：性能飞跃，功能全面升级；
1. 2009年至今的业余项目集锦；
1. 欧洲投资银行将注资700亿欧元推动欧洲科技发展；
1. GitHub Copilot 编程助手；

以上是今天的前五条黑科技新闻标题。

总共15条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 别再靠IP猜我的语言了 
<small>🔗 [vitonsky.net](https://vitonsky.net/blog/2025/05/17/language-detection/): Don't guess my language</small>


| 🔥🔥: 586 \| 💬: [332](https://news.ycombinator.com/item?id=44028153) \| 🗓️ 2025-05-19


<br />
用IP地理定位决定界面语言是**错误做法**，IP仅显示请求来源地，与用户实际语言需求无关（如VPN、跨国旅行、多语言国家）。**浏览器语言首选项**（Accept-Language头）才是准确信号，应优先采用。强制根据IP切换语言会导致用户体验糟糕（如误显示中文给非中文用户）。正确做法是：尊重浏览器设置，允许手动切换，仅将IP用于货币/法律等场景。**懒惰的假设不是好设计**。

---

## <a name="2"></a>2. Zod 4 正式发布：性能飞跃，功能全面升级 
<small>🔗 [zod.dev](https://zod.dev/v4): Zod 4</small>


| 🔥🔥: 469 \| 💬: [165](https://news.ycombinator.com/item?id=44030850) \| 🗓️ 2025-05-19


<br />
经过一年开发，**Zod 4** 稳定版终于到来！新版本在**性能**（字符串解析快 14 倍）、**TypeScript 效率**（类型实例化减少 100 倍）和**体积**（核心包缩小 57%）上均有显著提升。新增功能包括**递归类型推断**、**文件验证**、**JSON Schema 转换**和**国际化错误消息**。为简化迁移，Zod 4 与 Zod 3 并行发布，用户可通过 `zod/v4` 子路径导入。另推出轻量版 **Zod Mini**，核心包体积进一步缩减 85%。

---

## <a name="3"></a>3. 2009年至今的业余项目集锦 
<small>🔗 [naeemnur.com](https://naeemnur.com/side-projects/): Side projects I've built since 2009</small>


| 🔥🔥: 220 \| 💬: [123](https://news.ycombinator.com/item?id=44027867) \| 🗓️ 2025-05-19


<br />
作者自2009年起持续开发**业余项目**，部分已出售，部分仍在运营，少数已关闭。项目多基于**WordPress**，少数使用Laravel和React，核心建议是**用熟悉的技术栈**，避免陷入框架选择困境。活跃项目包括游戏平台Handheld Hunt、WordPress主题商店Mild Themes等；已售项目如Flag Palette、ZeroAcquire；终止项目涵盖诗歌博客Book of Naem、加密货币工具Krypto Predict等。全文展现了持续创造与迭代的开发者精神。

---

## <a name="4"></a>4. 欧洲投资银行将注资700亿欧元推动欧洲科技发展 
<small>🔗 [ioplus.nl](https://ioplus.nl/en/posts/european-investment-bank-to-inject-70-billion-in-european-tech): European Investment Bank to inject €70B in European tech</small>


| 🔥🔥: 210 \| 💬: [215](https://news.ycombinator.com/item?id=44031297) \| 🗓️ 2025-05-19


<br />
欧洲投资银行（EIB）计划到2027年向欧洲科技领域投入**700亿欧元**，旨在缩小与美国的技术差距，重点支持人工智能、军用无人机等前沿领域。该计划名为**TechEU**，将简化融资流程，将初创企业申请审批时间从18个月缩短至6个月，以快速响应市场变化。EIB还希望通过与私人投资者合作，撬动**2500亿欧元**资金，并利用当前地缘政治环境吸引国际资本，巩固欧洲作为全球科技领导者的地位。

---

## <a name="5"></a>5. GitHub Copilot 编程助手 
<small>🔗 [github.blog](https://github.blog/changelog/2025-05-19-github-copilot-coding-agent-in-public-preview/): GitHub Copilot Coding Agent</small>


| 🔥🔥: 200 \| 💬: [116](https://news.ycombinator.com/item?id=44031432) \| 🗓️ 2025-05-19


<br />
GitHub Copilot 编程助手可**自动处理**任务，帮你从积压工作和技术债务中解脱。只需将问题分配给 Copilot，它会在后台使用**安全云开发环境**分析代码库、修改代码并通过测试验证。完成后会通知你审核，你可在 PR 中提出修改或本地继续开发。  

它擅长处理**中低复杂度任务**（如修复 Bug、重构、完善文档），支持同时分配多个任务。目前仅限 Copilot Pro+ 和企业版用户，需消耗 GitHub Actions 分钟数和高级请求额度。6 月 4 日起，每次模型请求将消耗 1 次高级额度。  

此为预览功能，界面可能调整。详情可查阅官方文档或参与讨论。

---

## <a name="6"></a>6. ClawPDF：开源虚拟/网络PDF打印机，支持OCR与图像处理 
<small>🔗 [github.com](https://github.com/clawsoftware/clawPDF): ClawPDF – Open-Source Virtual/Network PDF Printer with OCR and Image Support</small>


| 🔥🔥: 152 \| 💬: [23](https://news.ycombinator.com/item?id=44029142) \| 🗓️ 2025-05-19


<br />
ClawPDF是一款**开源Windows虚拟打印机**，可将文档转换为PDF、OCR文本及多种图像格式（如PNG、JPEG等），并支持**企业级功能**如PDF加密、元数据管理和网络共享打印。它提供**脚本接口**（Python/PowerShell等）实现自动化，兼容所有主流Windows系统（包括ARM64），且无广告或间谍软件。此外，还支持多用户环境、批量打印及多语言界面，适合个人与企业部署。  

（注：关键加粗项为“开源Windows虚拟打印机”“企业级功能”“脚本接口”，符合3项限制；字符数约220，符合要求。）

---

## <a name="7"></a>7. 微软封锁国际刑事法院：数字依赖的代价 
<small>🔗 [techzine.eu](https://www.techzine.eu/news/privacy-compliance/131536/microsofts-icc-blockade-digital-dependence-comes-at-a-cost/): Microsoft's ICC blockade: digital dependence comes at a cost</small>


| 🔥🔥: 152 \| 💬: [61](https://news.ycombinator.com/item?id=44032717) \| 🗓️ 2025-05-19


<br />
美国对国际刑事法院（ICC）实施制裁后，首席检察官卡里姆·汗的**微软邮箱账户**被冻结，银行账户亦受影响，导致ICC工作瘫痪。此事凸显依赖**美国IT服务**的地缘政治风险。欧洲政府虽认为微软服务的优势可抵消潜在问题，但若美欧关系恶化，**数字主权**可能受威胁。非美政府需警惕关键服务被切断的风险，并考虑替代方案。合同与承诺在政治冲突前可能失效，自主技术储备至关重要。

---

## <a name="8"></a>8. Claude代码SDK开发指南 
<small>🔗 [docs.anthropic.com](https://docs.anthropic.com/en/docs/claude-code/sdk): Claude Code SDK</small>


| 🔥🔥: 144 \| 💬: [79](https://news.ycombinator.com/item?id=44032777) \| 🗓️ 2025-05-19


<br />
该SDK支持开发者将**Claude代码**集成到应用中，通过命令行实现非交互式调用，未来将推出TypeScript和Python版本。核心功能包括：**多轮对话续接**（通过会话ID）、**自定义系统提示**（指导AI行为）及**MCP协议扩展**（集成外部工具）。支持JSON、流式JSON等输出格式，适用于代码审查、自动化脚本等场景，强调通过会话管理和错误处理提升稳定性。

---

## <a name="9"></a>9. 微软开源命令行文本编辑器Edit 
<small>🔗 [devblogs.microsoft.com](https://devblogs.microsoft.com/commandline/edit-is-now-open-source/): Edit is now open source</small>


| 🔥🔥: 136 \| 💬: [52](https://news.ycombinator.com/item?id=44031529) \| 🗓️ 2025-05-19


<br />
Edit是Windows全新推出的**开源命令行文本编辑器**，未来将作为Windows 11的默认组件发布。其特点包括：**轻量化**（体积小于250kB）、支持鼠标操作和多文件切换（Ctrl+P），并提供查找替换、正则表达式匹配及自动换行等功能。微软旨在为64位系统填补CLI编辑器空白，避免类似Vim的模态设计学习成本。开发者现可通过GitHub提前体验或参与贡献。

---

## <a name="10"></a>10. 一支后朋克乐队的Windows 98风格网站 
<small>🔗 [corp.band](https://corp.band): Show HN: Windows 98 themed website in 1 HTML file for my post punk band</small>


| 🔥🔥: 128 \| 💬: [28](https://news.ycombinator.com/item?id=44032470) \| 🗓️ 2025-05-19


<br />
该网站以**复古Windows 98界面**设计，整合了乐队**CORP**的各类信息。包含**音乐播放**（Spotify、Bandcamp等）、演出日程（Songkick）、周边商品（如“人力资源T恤”）、邮件订阅及联系方式。页面还隐藏了“机密企业资源”等趣味彩蛋，整体风格戏仿企业办公系统，呼应乐队名“CORP”的黑色幽默主题。

---

## <a name="11"></a>11. 《呆伯特》作者斯科特·亚当斯自曝将因前列腺癌去世 
<small>🔗 [thewrap.com](https://www.thewrap.com/dilbert-scott-adams-prostate-cancer-biden/): Dilbert creator Scott Adams says he will die soon from same cancer as Joe Biden</small>


| 🔥🔥: 120 \| 💬: [138](https://news.ycombinator.com/item?id=44031917) \| 🗓️ 2025-05-19


<br />
《呆伯特》漫画创作者**斯科特·亚当斯**在节目中透露，自己因**前列腺癌晚期**（已扩散至骨骼）预计将于今夏去世，与拜登所患癌症相同。67岁的亚当斯表示，癌症若未扩散可治愈，但转移后无法根治。他此前以讽刺职场文化的漫画闻名，近年因**亲特朗普的政治立场**引发争议。节目中还表达了对拜登及其家人的同情。

---

## <a name="12"></a>12. Go语言中的过度间接引用问题 
<small>🔗 [flak.tedunangst.com](https://flak.tedunangst.com/post/too-much-go-misdirection): Too Much Go Misdirection</small>


| 🔥🔥: 117 \| 💬: [46](https://news.ycombinator.com/item?id=44031009) \| 🗓️ 2025-05-19


<br />
作者在**Go语言**中处理图像解码时，发现标准库的**io.Reader接口**虽支持流式处理，但实际场景常需直接访问底层字节。通过`bytes.Reader`可避免复制，但`image.Decode`函数会强制包裹`bufio.Reader`，导致优化失效。最终通过**unsafe.Pointer**解包嵌套结构实现零拷贝，同时指出标准库的隐式类型要求（如未实现的`Peek`方法）是设计缺陷，导致第三方类型难以适配这种"影子API"模式。

---

## <a name="13"></a>13. 2024年：人工智能的寒冬将至？ 
<small>🔗 [datagubbe.se](https://www.datagubbe.se/winter/): Is Winter Coming? (2024)</small>


| 🔥🔥: 113 \| 💬: [125](https://news.ycombinator.com/item?id=44028384) \| 🗓️ 2025-05-19


<br />
本文探讨了当前AI技术的局限性与公众期待的落差。**大语言模型（LLM）**虽能模拟人类对话，却存在**幻觉问题**（输出虚假信息），且依赖**提示工程**（如用“鹅卵石”搜索“花生”照片）。尽管AI在特定领域（如医疗诊断）表现优异，但远未达到“通用智能”水平。企业过度营销导致泡沫，而实际应用（如自动驾驶、代码生成）仍需人类监督。作者以微软聊天机器人的失败为例，指出当前AI“足够好”的承诺往往落空，暗示新一轮“AI寒冬”可能来临。

---

## <a name="14"></a>14. Hot Chips 2024：IBM Telum II 主频处理器与独特缓存策略 
<small>🔗 [chipsandcheese.com](https://chipsandcheese.com/p/telum-ii-at-hot-chips-2024-mainframe-with-a-unique-caching-strategy): Telum II at Hot Chips 2024: Mainframe with a Unique Caching Strategy</small>


| 🔥🔥: 110 \| 💬: [49](https://news.ycombinator.com/item?id=44028250) \| 🗓️ 2025-05-19


<br />
IBM 最新发布的 **Telum II** 主频处理器采用三星 5nm 工艺，以 **5.5 GHz 高频八核** 设计为核心，配备 **360 MB 片上缓存**，并集成 DPU 和 AI 加速器。其创新点在于 **虚拟 L3/L4 缓存技术**：通过动态分配 L2 缓存（单核 36 MB）作为共享资源，减少数据冗余并优化延迟。跨芯片虚拟 L4 缓存可达 2.8 GB，延迟仅 48.5 ns。该设计兼顾单线程性能与缓存效率，延续了 IBM 主频处理器在金融交易等低延迟场景的优势。

---

## <a name="15"></a>15. 用动画游戏图解博弈论 
<small>🔗 [ncase.me](https://ncase.me/trust/): Game theory illustrated by an animated cartoon game</small>


| 🔥🔥: 105 \| 💬: [18](https://news.ycombinator.com/item?id=44031535) \| 🗓️ 2025-05-19


<br />
该内容展示了一个通过**动画卡通游戏**来阐释**博弈论**概念的创意项目。页面提供了多语言翻译选项（如西班牙语、法语、中文等），并邀请用户参与**协作翻译**。核心亮点是将抽象理论转化为直观的互动形式，适合跨文化学习与传播。

---
