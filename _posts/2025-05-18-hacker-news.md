---
layout: page
title: 勒西科技日报 - 2025年05月18日
date: 2025-05-18 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 间隔重复系统迎来重大升级；
1. 用SBERT模型分析《伏尼契手稿》的语言结构；
1. 抛弃Obsidian，我选择自建笔记系统；
1. 硬核Vim训练插件：告别坏习惯，精通移动操作；
1. 30美元自制自动百叶窗开启器；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 间隔重复系统迎来重大升级 
<small>🔗 [domenic.me](https://domenic.me/fsrs/): Spaced repetition systems have gotten better</small>


| 🔥🔥: 642 \| 💬: [403](https://news.ycombinator.com/item?id=44020591) \| 🗓️ 2025-05-18


<br />
传统**间隔重复系统**（如SuperMemo-2）依赖固定公式安排复习间隔，效率有限且易受挫。新一代算法**FSRS**通过机器学习动态预测用户遗忘曲线，优化复习计划：  
1. **三组件模型**（难度/稳定性/可提取性）个性化调整复习频率；  
2. 支持自定义**目标记忆率**（如90%→70%），显著减少每日复习量；  
3. 已整合至Anki等主流工具，实测能降低学习负担并提升长期记忆效果。  

对比WaniKani等服务的僵化间隔设置，FSRS展现了算法革新的巨大潜力。

---

## <a name="2"></a>2. 用SBERT模型分析《伏尼契手稿》的语言结构 
<small>🔗 [github.com](https://github.com/brianmg/voynich-nlp-analysis): Show HN: I modeled the Voynich Manuscript with SBERT to test for structure</small>


| 🔥🔥: 256 \| 💬: [69](https://news.ycombinator.com/item?id=44022353) \| 🗓️ 2025-05-18


<br />
该项目通过**SBERT聚类**、**词性推断**和**马尔可夫转移矩阵**等现代NLP技术，验证了《伏尼契手稿》是否具有真实语言的结构特征。研究发现，手稿中存在**功能词与内容词的分化**，且不同章节（如植物学、生物学）的语法模式差异显著。作者剥离了常见后缀以突出词根，但强调这一预处理可能影响结果。尽管未破解内容，但分析表明手稿具有**系统性构造语言**的特征。项目开源，欢迎语言学家和密码学家协作探索。

---

## <a name="3"></a>3. 抛弃Obsidian，我选择自建笔记系统 
<small>🔗 [amberwilliams.io](https://amberwilliams.io/blogs/building-my-own-pkms): Ditching Obsidian and building my own</small>


| 🔥🔥: 195 \| 💬: [236](https://news.ycombinator.com/item?id=44022448) \| 🗓️ 2025-05-18


<br />
作者Amber Williams分享了她从**Obsidian**转向自建**个人知识管理系统（PKMS）**的历程。她指出商业笔记应用存在**隐私风险**、高昂订阅费及长期可用性问题，最终选择用开源工具Directus搭建专属系统。该系统以Markdown存储笔记，支持多端同步且无需付费，同时确保数据完全自主控制。她强调，自建方案不仅终结了频繁迁移的困扰，更让知识管理回归本质——高效连接与深度思考。

---

## <a name="4"></a>4. 硬核Vim训练插件：告别坏习惯，精通移动操作 
<small>🔗 [github.com](https://github.com/m4xshen/hardtime.nvim): Show HN: Hardtime.nvim – break bad habits and master Vim motions</small>


| 🔥🔥: 152 \| 💬: [58](https://news.ycombinator.com/item?id=44020734) \| 🗓️ 2025-05-18


<br />
这是一个名为 **hardtime.nvim** 的Neovim插件，旨在帮助用户**戒除低效操作习惯**，并通过强制限制和智能提示**掌握高效的Vim移动命令**。核心功能包括：阻止短时间内重复按键、提供替代操作提示（如用`5j`代替连续按`j`）、生成坏习惯报告。支持自定义禁用按键、文件类型及提示规则，适配Neovim 0.10.0+。默认配置已优化常见场景，例如推荐使用相对跳转和文本对象操作。安装后可通过命令开关插件，日志记录于`~/.local/state/nvim/hardtime.nvim.log`。

---

## <a name="5"></a>5. 30美元自制自动百叶窗开启器 
<small>🔗 [sifter.org](https://sifter.org/~simon/journal/20240718.html): $30 Homebrew Automated Blinds Opener</small>


| 🔥🔥: 150 \| 💬: [60](https://news.ycombinator.com/item?id=44022758) \| 🗓️ 2025-05-18


<br />
作者利用周末时间，用**闲置零件**快速组装了一个低成本自动百叶窗系统。核心设计采用**硅胶电机支架**（来自废弃冲牙器）降低噪音，通过**磁编码器**感知扭矩以实现防卡停，整体成本仅30美元（含3D打印部件）。系统以极慢速度（8分钟全开）模拟自然晨光，并通过家庭自动化控制开合度。虽然磁编码方案存在信号不稳定缺陷，但**扭矩反馈机制**能可靠检测百叶窗极限位置。最终成品运行近乎无声，仅保留百叶窗自身轻微吱嘎声作为运行提示。

---

## <a name="6"></a>6. 苹果信用卡导致iCloud、App Store和Apple ID账户被禁用（2021年） 
<small>🔗 [dcurt.is](https://dcurt.is/apple-card-can-disable-your-icloud-account): Apple card disabled my iCloud, App Store, and Apple ID accounts (2021)</small>


| 🔥🔥: 136 \| 💬: [88](https://news.ycombinator.com/item?id=44021792) \| 🗓️ 2025-05-18


<br />
2021年3月，用户因**Apple Card自动付款失败**（银行账号变更未更新）触发苹果系统锁定。尽管欠款仅逾期几天，苹果直接**禁用其所有关联账户**（包括iCloud、App Store和Apple Music），甚至错误关联到不存在的iPhone订单。客服多次推诿，最终耗时多日通过**高盛苹果卡部门**协调解决。事件暴露苹果对自有支付服务的异常严厉政策，且内部沟通混乱，威胁用户数据安全。账户在申诉一周后恢复。

---

## <a name="7"></a>7. 高效记忆法宝：间隔重复记忆系统 
<small>🔗 [notes.andymatuschak.org](https://notes.andymatuschak.org/Spaced_repetition_memory_system): Spaced Repetition Memory System</small>


| 🔥🔥: 136 \| 💬: [12](https://news.ycombinator.com/item?id=44022225) \| 🗓️ 2025-05-18


<br />
**间隔重复记忆系统**结合了**测试效应**与**间隔效应**，能高效记忆海量信息，甚至培养概念理解。首个消费级应用是SuperMemo，后衍生Anki等工具。系统虽强大，但存在挑战：编写优质记忆提示困难、习惯养成不易，且常被误解仅适用于机械记忆。实际它能深化学习，关键在于建立情感连接与持续更新内容。

---

## <a name="8"></a>8. 圆梦童年：打造我心中的终极IBM电脑 
<small>🔗 [fabiensanglard.net](https://fabiensanglard.net/2168/index.html): Building my childhood dream PC</small>


| 🔥🔥: 124 \| 💬: [49](https://news.ycombinator.com/item?id=44021824) \| 🗓️ 2025-05-18


<br />
作者回忆了14岁时与兄弟共用一台性能不足的Cyrix 486电脑的时光，尤其羡慕邻居的**IBM PS/1 2168**（价值约6000美元）。2024年，他通过 eBay 购得一台保存完好的同款机型，并详细记录了修复过程：从开箱、安装**PC-DOS 7**到升级**L2缓存**和CPU，最终流畅运行《DOOM》。这台机器以**可扩展性**和经典设计（如顶部提手、机械键盘）著称，展现了IBM的工艺精髓。

---

## <a name="9"></a>9. Chrome侧边栏AI助手：开源浏览器自动化工具 
<small>🔗 [github.com](https://github.com/parsaghaffari/browserbee): Show HN: A web browser agent in your Chrome side panel</small>


| 🔥🔥: 122 \| 💬: [55](https://news.ycombinator.com/item?id=44020626) \| 🗓️ 2025-05-18


<br />
**BrowserBee** 是一款**隐私优先**的开源Chrome扩展，通过自然语言控制浏览器操作。它结合了**LLM指令解析**与Playwright自动化工具，支持导航、标签管理、鼠标键盘交互等任务，适用于社交媒体管理、新闻聚合、研究辅助等场景。所有数据仅在本地处理，无需后端，确保安全性。支持Anthropic、OpenAI等主流LLM，提供**记忆功能**存储常用操作流程以提升效率。用户可自行安装或从源码构建，未来将登陆Chrome应用商店。

---

## <a name="10"></a>10. 谷歌Logo连字漏洞 
<small>🔗 [jefftk.com](https://www.jefftk.com/p/google-logo-ligature-bug): Google Logo Ligature Bug</small>


| 🔥🔥: 122 \| 💬: [33](https://news.ycombinator.com/item?id=44021028) \| 🗓️ 2025-05-18


<br />
2025年5月17日，Jeffrey Yasskin发现了一个涉及**Google Sans字体**的安全漏洞：若注册域名`googlelogoligature.net`，Chrome等谷歌产品会将其显示为“Google.net”，可能诱导用户误认。该问题源于字体中的**连字功能**（通常用于优化“fi”等组合），但谷歌将其滥用于将特定字符串渲染为品牌Logo。此设计虽便于产品展示，却不应出现在处理用户输入的安全场景中。漏洞非Unicode导致，仅与字体特性相关。

---

## <a name="11"></a>11. 感谢谷歌治好了我的YouTube瘾 
<small>🔗 [rakhim.exotext.com](https://rakhim.exotext.com/thank-you-google-for-breaking-my-youtube-addiction): Thank you Google for breaking my YouTube addiction</small>


| 🔥🔥: 106 \| 💬: [86](https://news.ycombinator.com/item?id=44020653) \| 🗓️ 2025-05-18


<br />
过去几年，**谷歌**成功让YouTube变得**无聊且缺乏吸引力**，反而降低了用户成瘾性。早期推荐订阅内容尚可，但算法首页推送曾让人沉迷。如今主页重复推荐相同视频，**搜索功能混乱**，强行推送无关内容（如看了蜜蜂视频就被打上“蜜蜂爱好者”标签）。这种刻意让平台变得**低效**的策略，意外实现了“不作恶”的初衷。

---

## <a name="12"></a>12. 超级富豪有哪些不为人知的消费？ 
<small>🔗 [old.reddit.com](https://old.reddit.com/r/AskReddit/comments/2s9u0s/comment/cnnmca8/): What do wealthy people buy, that ordinary people know nothing about? (2015)</small>


| 🔥: 93 \| 💬: [101](https://news.ycombinator.com/item?id=44022215) \| 🗓️ 2025-05-18


<br />
这篇来自Reddit的热门回答揭示了不同财富阶层的消费差异：**1000万美元级**富豪可享五星级生活但需谨慎理财；**1亿美元级**拥有私人飞机、岛屿和政商名流社交圈；**10亿美元级**则能购买**顶级资源**——从私人音乐会到国家元首会晤。最震撼的是财富带来的**时间自由**和**全球影响力**，但作者指出，巨额财富无法换取真挚情感关系。文末用收入比例换算（如兰博基尼相当于普通人花23.5美元）直观展现了富豪的消费视角。

---

## <a name="13"></a>13. Vaev：从零构建的浏览器引擎（已支持渲染Google首页） 
<small>🔗 [github.com](https://github.com/skift-org/vaev): Show HN: Vaev – A browser engine built from scratch (It renders google.com)</small>


| 🔥: 91 \| 💬: [36](https://news.ycombinator.com/item?id=44023144) \| 🗓️ 2025-05-18


<br />
Vaev是一款**实验性浏览器引擎**，主打**轻量快速**与安全性，目前支持HTML/XHTML解析、基础CSS渲染（含变量计算与百分比单位）及PDF导出功能。其架构采用模块化设计，依赖LLVM 20等工具链，可通过简单命令本地运行测试。开发者明确标注了当前局限性：仅支持HTTP/File协议、**不兼容CSS Grid布局**，但已通过WPT标准测试页追踪兼容性进展。项目由四人团队开发，需特定环境配置（如Arch Linux）。

---

## <a name="14"></a>14. 加密货币已成终极沼泽资产 
<small>🔗 [economist.com](https://www.economist.com/leaders/2025/05/15/crypto-has-become-the-ultimate-swamp-asset): Crypto has become the ultimate swamp asset</small>


| 🔥: 86 \| 💬: [134](https://news.ycombinator.com/item?id=44020356) \| 🗓️ 2025-05-18


<br />
加密货币行业曾梦想超越政治，如今却与**自我交易**画上等号。文章以特朗普接受卡塔尔政府赠送波音747为例，指出现代政治中利益冲突频发，但最严重的**自我交易**行为实则发生在区块链领域——这里承载着数万亿美元的加密货币市场，成为**腐败温床**的象征。

---

## <a name="15"></a>15. Buckaroo：专为Jupyter设计的现代化数据表格工具 
<small>🔗 [github.com](https://github.com/paddymul/buckaroo): Show HN: Buckaroo – Data table UI for Notebooks</small>


| 🔥: 71 \| 💬: [6](https://news.ycombinator.com/item?id=44022265) \| 🗓️ 2025-05-18


<br />
Buckaroo是一款针对**Jupyter笔记本**优化的高性能数据表格UI，支持**Pandas**和**Polars**等数据框架，提供无限滚动、排序、搜索、统计摘要和直方图等功能。其核心基于AG-Grid，可快速加载数千条数据，并默认固定宽度格式，便于数值对比。此外，Buckaroo还内置**自动清洗**（Beta）和低代码UI功能，支持自定义样式与扩展分析。兼容Jupyter Lab、VS Code、Marimo等多种环境，安装简单（`pip install buckaroo`），适合快速数据探索与分析。

---

## <a name="16"></a>16. 纸艺机械结构大全 
<small>🔗 [cutfoldtemplates.com](https://cutfoldtemplates.com): Paper Mechanisms</small>


| 🔥: 68 \| 💬: [3](https://news.ycombinator.com/item?id=44020315) \| 🗓️ 2025-05-18


<br />
本文展示了33种**纸艺机械结构**，涵盖折叠动画、光学幻觉和工程应用。**六边形折纸动画**（Hexaflexagon）通过扭转展示连续画面；**三浦折叠**（Miura-ori）以刚性折痕实现卫星太阳能板收纳；**双稳态开关**（Bistable mechanism）利用数学不可展性创造纸制触发器。其他亮点包括旋转凸轮、威尼斯盲板显影结构和**折纸闪光器**（Flasher）在NASA卫星中的应用。这些设计融合几何学、材料科学与互动叙事，兼具功能性与艺术性。

---

## <a name="17"></a>17. Roam的衰落与Obsidian的崛起 
<small>🔗 [every.to](https://every.to/superorganizers/the-fall-of-roam): The Fall of Roam</small>


| 🔥: 68 \| 💬: [19](https://news.ycombinator.com/item?id=44023423) \| 🗓️ 2025-05-18


<br />
用户Bryan高度评价了Dan的文章，并指出**Obsidian**在Roam不足的领域表现出色。他特别推荐结合Nick Milo的**“链接思维”笔记法**使用该工具，认为这一组合带来了**颠覆性改变**。虽然语气略带调侃（“暂时如此？”），但整体肯定了Obsidian的当前优势。

---

## <a name="18"></a>18. 法国成为首个支持联合国开源原则的政府 
<small>🔗 [social.numerique.gouv.fr](https://social.numerique.gouv.fr/@codegouvfr/114529954373492878): France Becomes First Government to Endorse UN Open Source Principles</small>


| 🔥: 63 \| 💬: [8](https://news.ycombinator.com/item?id=44024759) \| 🗓️ 2025-05-18


<br />
法国宣布支持**联合国开源原则**，成为全球首个正式采纳该框架的政府。此举旨在推动**数字主权**和**技术透明性**，鼓励公共部门采用开源解决方案以增强协作与创新。该决定可能对全球开源生态产生深远影响。

---

## <a name="19"></a>19. 新视野号飞越冥王星 
<small>🔗 [apod.nasa.gov](https://apod.nasa.gov/apod/ap250518.html): Pluto Flyover from New Horizons</small>


| 🔥: 55 \| 💬: [14](https://news.ycombinator.com/item?id=44022233) \| 🗓️ 2025-05-18


<br />
2015年7月，**新视野号**探测器以每小时8万公里的速度飞越冥王星，拍摄了这段两分钟的延时视频。画面中，**氮冰覆盖的山脉**在晨光中显现，右侧是分裂为奇特多边形的固态氮平原，下方遍布陨石坑与冰峰。视频最终以500米高的**刀脊地形**结束。由于速度过快，新视野号已无法返回，正飞向太阳系外。

---

## <a name="20"></a>20. Sun Enterprise 10000的诞生历程（2007年） 
<small>🔗 [filibeto.org](https://www.filibeto.org/aduritz/truetrue/e10000/how-e10k-wasborn.html): How the Sun Enterprise 10000 was born (2007)</small>


| 🔥: 51 \| 💬: [48](https://news.ycombinator.com/item?id=44020975) \| 🗓️ 2025-05-18


<br />
一群工程师离开知名企业（多为前NCR员工）在圣地亚哥创业，研发基于**Sparc处理器**的**大规模并行计算机**。经历多次并购（包括被Cray收购）后，团队开发出支持**动态系统域**和**交替路径**技术的CS6400服务器。后因SGI无意保留该业务，Sun以5000万美元收购团队，并完成其后续产品——**Ultra Enterprise 10000（Starfire）**。这款服务器凭借卓越的可扩展性（64处理器/64GB内存）和Sun的营销资源大获成功，被Scott McNealy誉为"微软收购DOS后最划算的交易"，首年即创收数十亿美元。

---

## <a name="21"></a>21. RISC OS图形界面的独特设计 
<small>🔗 [telcontar.net](https://telcontar.net/Misc/GUI/RISCOS/): The RISC OS GUI</small>


| 🔥: 51 \| 💬: [15](https://news.ycombinator.com/item?id=44021191) \| 🗓️ 2025-05-18


<br />
本文介绍了1992年由英国Acorn公司发布的**RISC OS 3.11**图形界面，其设计理念在当时极为先进。系统采用**三键鼠标**，分别对应选择、菜单和调整功能，大幅减少键盘依赖。**弹出式菜单**通过中键触发，结合了对话框功能，操作高效。窗口管理支持**后台输入**，焦点与叠放顺序分离，黄色标题栏标记键盘焦点。桌面分为固定图标的Pinboard和显示任务的Icon Bar，体现了高度定制化的交互逻辑。尽管存在窗口堆叠混乱等问题，其创新设计仍为现代界面提供了灵感。

---

## <a name="22"></a>22. 地狱之门的征服 
<small>🔗 [nan.usace.army.mil](https://www.nan.usace.army.mil/portals/37/docs/history/hellgate.pdf): The Conquest of Hell Gate [pdf]</small>


| 🔥: 50 \| 💬: [19](https://news.ycombinator.com/item?id=44020574) \| 🗓️ 2025-05-18


<br />
该PDF文件似乎是一份图像文档的元数据，包含**色彩空间**、**分辨率**和**压缩格式**等技术参数。内容主体为二进制数据流，无法直接提取可读文本。文档可能涉及图像处理或数字艺术领域，但具体主题不明确。**文件结构**显示其为标准PDF格式，但缺乏实质性文字内容。

---

## <a name="23"></a>23. Craft Basic：适用于Windows 95及更高版本的BASIC解释器 
<small>🔗 [lucidapogee.com](https://www.lucidapogee.com/?page=craftbasic): Craft Basic (Windows 95 and up)</small>


| 🔥: 49 \| 💬: [9](https://news.ycombinator.com/item?id=44020019) \| 🗓️ 2025-05-18


<br />
Craft Basic是一款**免费**的BASIC解释器，支持Windows 95及以上系统（包括Win10/Win11）。用户可通过它学习编程、开发简单游戏、交互式编写代码或处理复杂计算，并支持图形显示和窗体构建。内置**位图绘制**、WAV文件播放、窗体控件（如静态文本和按钮）等功能，附带大量示例程序。最新版本为v1.7.1（2023年12月更新），文件大小269kB，提供下载链接及文档支持。近期更新还包括Express BASIC的**位运算操作符**和字符串功能优化。

---

## <a name="24"></a>24. Rust版Model2Vec：高性能静态文本嵌入工具 
<small>🔗 [github.com](https://github.com/MinishLab/model2vec-rs): Show HN: Model2vec-Rs – Fast Static Text Embeddings in Rust</small>


| 🔥: 46 \| 💬: [5](https://news.ycombinator.com/item?id=44021883) \| 🗓️ 2025-05-18


<br />
该项目是**Model2Vec**模型的官方Rust实现，支持从Hugging Face Hub或本地路径加载预训练模型，生成文本嵌入向量。提供**CLI工具**和API两种调用方式，支持批量处理与自定义参数（如最大长度和批次大小）。内置多款预训练模型（如`potion-base-8M`和`M2V_multilingual_output`），涵盖通用和检索任务。性能方面，Rust版本比Python实现快**1.7倍**，吞吐量达8000样本/秒。采用MIT开源协议，适合需要高效嵌入计算的场景。

---

## <a name="25"></a>25. 2023年苹果邮件中处理Git补丁指南 
<small>🔗 [btxx.org](https://btxx.org/posts/mail/): Working with Git Patches in Apple Mail (2023)</small>


| 🔥: 44 \| 💬: [21](https://news.ycombinator.com/item?id=44020914) \| 🗓️ 2025-05-18


<br />
本文介绍了如何在**Apple Mail**中通过邮件接收并应用**Git补丁**。首先需在邮箱内创建专属的**“Patches”文件夹**，将含补丁的邮件移动至此。随后导出该文件夹到本地，通过终端进入目标项目目录，使用`git apply`命令加载补丁文件。虽然流程需手动操作，但能有效实现补丁管理，建议定期清理本地补丁文件夹以保持整洁。适用于MacOS用户处理Git协作场景。

---
