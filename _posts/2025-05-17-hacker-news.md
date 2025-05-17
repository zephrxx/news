---
layout: page
title: 勒西科技日报 - 2025年05月17日
date: 2025-05-17 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 将条件判断上移，循环下移；
1. Proton威胁退出瑞士：新监控法案将破坏用户隐私；
1. N64调色板光照技巧解析；
1. Pyrefly：Python 新型类型检查器与IDE体验革新；
1. 死星不会辐射霍金辐射；

以上是今天的前五条黑科技新闻标题。

总共15条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 将条件判断上移，循环下移 
<small>🔗 [matklad.github.io](https://matklad.github.io/2023/11/15/push-ifs-up-and-fors-down.html): Push Ifs Up and Fors Down</small>


| 🔥🔥: 293 \| 💬: [124](https://news.ycombinator.com/item?id=44013157) \| 🗓️ 2025-05-17


<br />
这篇短文提出了两条编程优化原则：**将条件判断上移**到调用方，通过类型或断言确保前置条件，减少冗余检查并集中控制流；同时**将循环下移**到批量处理层，通过批操作提升性能，甚至实现向量化计算。前者能简化逻辑、消除死代码，后者可分摊开销、优化处理顺序。二者结合时（如先判断条件再批量执行），能避免重复分支并释放硬件并行潜力。文末以TigerBeetle架构和jQuery为例，说明该模式在系统设计和抽象表达中的普适价值。

---

## <a name="2"></a>2. Proton威胁退出瑞士：新监控法案将破坏用户隐私 
<small>🔗 [techradar.com](https://www.techradar.com/vpn/vpn-privacy-security/we-would-be-less-confidential-than-google-proton-threatens-to-quit-switzerland-over-new-surveillance-law): "We would be less confidential than Google" Proton threatens to quit Switzerland</small>


| 🔥🔥: 176 \| 💬: [106](https://news.ycombinator.com/item?id=44014808) \| 🗓️ 2025-05-17


<br />
瑞士拟修订监控法案，要求**VPN服务**和通讯应用**记录用户数据**，此举可能危及加密技术和匿名性。**Proton**和NymVPN等公司强烈反对，称若法案通过将撤离瑞士。Proton CEO批评该法案类似俄罗斯法律，违背隐私权，并损害瑞士国际声誉。目前公众咨询已结束，多方施压要求政府重新考量。

---

## <a name="3"></a>3. N64调色板光照技巧解析 
<small>🔗 [30fps.net](https://30fps.net/pages/palette-lighting-tricks-n64/): Palette lighting tricks on the Nintendo 64</small>


| 🔥🔥: 165 \| 💬: [27](https://news.ycombinator.com/item?id=44014587) \| 🗓️ 2025-05-17


<br />
本文介绍了在**Nintendo 64**上实现**调色板空间着色**的创新技术。作者通过动态更新调色板而非逐像素计算，显著提升了光照渲染效率，并实现了**法线贴图**和实时高光效果。尽管存在光照不连续、仅支持灰度纹理等局限，但结合预烘焙的环境光与方向光，最终在自制Demo中呈现了令人惊艳的视觉效果。技术核心包括**共享漫反射与法线调色板**、基于球体近似的高光模拟，以及手动分组的类切线空间优化。

---

## <a name="4"></a>4. Pyrefly：Python 新型类型检查器与IDE体验革新 
<small>🔗 [engineering.fb.com](https://engineering.fb.com/2025/05/15/developer-tools/introducing-pyrefly-a-new-type-checker-and-ide-experience-for-python/): Pyrefly: A new type checker and IDE experience for Python</small>


| 🔥🔥: 129 \| 💬: [97](https://news.ycombinator.com/item?id=44013913) \| 🗓️ 2025-05-17


<br />
Meta团队推出开源工具**Pyrefly**，这是一个用Rust编写的Python静态类型检查器，支持CLI和IDE集成（如VSCode扩展），旨在提升代码类型一致性与错误检测效率。其核心优势包括**高性能**（每秒检查180万行代码）、**IDE优先设计**（实时类型推断与快速反馈）以及**开源协作**（MIT许可）。Pyrefly脱胎于Pyre项目，专为大规模代码库优化，并支持未标注类型的自动推断。团队呼吁开发者试用alpha版本并参与GitHub社区共建，计划今夏发布正式版。

---

## <a name="5"></a>5. 死星不会辐射霍金辐射 
<small>🔗 [johncarlosbaez.wordpress.com](https://johncarlosbaez.wordpress.com/2025/05/17/dead-stars-dont-radiate-and-shrink/): Dead Stars Don't Radiate</small>


| 🔥🔥: 116 \| 💬: [53](https://news.ycombinator.com/item?id=44015872) \| 🗓️ 2025-05-17


<br />
近期有三位物理学家提出**任何大质量物体都会发射霍金辐射**，包括死亡后的冷恒星，并声称宇宙会因此更快消亡。然而，这一观点与已知的**量子场论**和**广义相对论**相矛盾，且已被专家反驳。研究表明，静态引力场不会产生粒子-反粒子对，这一结论早在1975年就已确立。尽管相关论文发表在知名期刊，但因其近似计算存在缺陷，未获学界认可。部分科学媒体未核实便夸大报道，误导公众。权威文献和教科书（如Wald的著作）明确指出，**静态时空中的真空是稳定的**，不会自发衰变。

---

## <a name="6"></a>6. 如何在CSS中让浏览器自动选择对比色 
<small>🔗 [webkit.org](https://webkit.org/blog/16929/contrast-color/): How to have the browser pick a contrasting color in CSS</small>


| 🔥: 99 \| 💬: [29](https://news.ycombinator.com/item?id=44015367) \| 🗓️ 2025-05-17


<br />
CSS新特性`contrast-color()`可自动根据背景色选择**黑色或白色文本**，确保最佳对比度。该功能基于**WCAG 2对比度算法**，但当前版本对中色调背景的判断存在争议（如中蓝色背景可能错误选择黑色文本）。未来或改用**APCA感知对比算法**提升准确性。开发者仍需手动确保颜色组合满足无障碍标准，并可通过`prefers-contrast`媒体查询适配高对比度需求。此功能尤其适合管理多主题、多状态的色彩系统，但现阶段仅支持黑白二选一。

---

## <a name="7"></a>7. O2 VoLTE漏洞：一通电话即可定位任何用户 
<small>🔗 [mastdatabase.co.uk](https://mastdatabase.co.uk/blog/2025/05/o2-expose-customer-location-call-4g/): O2 VoLTE: locating any customer with a phone call</small>


| 🔥: 94 \| 💬: [12](https://news.ycombinator.com/item?id=44014046) \| 🗓️ 2025-05-17


<br />
英国运营商O2的**VoLTE（4G语音）服务**存在严重隐私漏洞，通话时会将双方的**IMSI（国际移动用户识别码）**、**IMEI（设备识别码）**及**基站位置信息**通过IMS信令泄露给呼叫方。攻击者利用公开的基站地图数据（如Cellmapper）可精确定位用户，城市环境中误差甚至小于100米。该漏洞自2025年3月曝光后，O2未回应修复请求，用户无法通过关闭4G通话功能避免风险。作者呼吁运营商移除敏感信令头并建立安全披露渠道。

---

## <a name="8"></a>8. 如果无人筛选信息，我们如何找到所需？ 
<small>🔗 [tadaima.bearblog.dev](https://tadaima.bearblog.dev/if-nothing-is-curated-how-do-we-find-things/): If nothing is curated, how do we find things</small>


| 🔥: 92 \| 💬: [56](https://news.ycombinator.com/item?id=44015144) \| 🗓️ 2025-05-17


<br />
作者反思社交媒体时代**信息过载**的困境：虽然技术让内容触手可及，但算法推送将人困在**信息茧房**中，难以发现新事物。过去通过电台、杂志等**专业筛选**渠道高效获取文化内容的体验已消失，如今人们被迫在碎片化信息中自行挖掘。批评指出，算法依赖削弱了艺术发现的惊喜感，而传统媒体（如乐评、影评）的衰落加剧了这一现象。解决方案或许是主动记录兴趣，但作者承认这仍像一份"工作"，并感叹社会或已默认这种疲惫的新常态。  

（注：关键概念加粗，符合字数要求）

---

## <a name="9"></a>9. 计算几何领域的开放性问题 
<small>🔗 [topp.openproblem.net](https://topp.openproblem.net/): Open Problems in Computational geometry</small>


| 🔥: 80 \| 💬: [12](https://news.ycombinator.com/item?id=44013181) \| 🗓️ 2025-05-17


<br />
该项目由Erik D. Demaine等人编辑，旨在收录**计算几何**及相关领域的重要未解决问题。最初发布于2001年，包含30个问题，后扩展至75个以上。虽然不再接受新问题提交，但鼓励对现有问题的更新（尤其是已解决或部分解决的问题）。每个问题按**唯一编号**和**分类**（如凸包、数据结构、图绘制等）整理，涵盖**几何图论**、**机器人路径规划**、**多面体展开**等方向。问题列表可通过PDF或Github仓库获取，部分经典问题包括动态凸包计算（Problem 12）、最小欧氏生成树（Problem 5）等。

---

## <a name="10"></a>10. 日本森林再生技术落地墨西哥 
<small>🔗 [english.elpais.com](https://english.elpais.com/climate/2025-05-17/miyawaki-in-nezahualcoyotl-the-japanese-method-of-creating-forests-comes-to-mexico.html): The Japanese method of creating forests comes to Mexico</small>


| 🔥: 80 \| 💬: [3](https://news.ycombinator.com/item?id=44013933) \| 🗓️ 2025-05-17


<br />
墨西哥州内萨瓦尔科约特尔市采用**宫胁造林法**，在城市化严重的盐碱地上打造高密度原生林。该方法由日本植物学家宫胁昭创立，通过密集种植本地物种（如龙舌兰、仙人掌）加速生态恢复，30年可形成自维持森林。项目由智利林业专家指导，600平方米试验林预计可降低周边温度10-15℃，改善雨水渗透并吸引传粉者。当地居民称此为对抗"热岛效应"的重要一步，但专家强调需结合其他措施解决环境问题。

---

## <a name="11"></a>11. 我开发了一款刀具钢材对比工具 
<small>🔗 [new.knife.day](https://new.knife.day/blog/knife-steel-comparisons/all): Show HN: I built a knife steel comparison tool</small>


| 🔥: 67 \| 💬: [49](https://news.ycombinator.com/item?id=44015649) \| 🗓️ 2025-05-17


<br />
这款工具允许用户**对比最多5种钢材的性能**，涵盖**耐腐蚀性**、**韧性**、**刀刃保持性**和**易磨性**等关键指标（1-10分制）。目前收录了150种钢材的详细对比数据，其中147种包含可视化图表，例如1095 vs 5160、CPM S30V vs D2等常见组合。适合刀具爱好者或专业人士快速评估不同钢材的优劣。

---

## <a name="12"></a>12. 世界上最长的火车之旅：史诗级路线，却无人完成 
<small>🔗 [bigthink.com](https://bigthink.com/strange-maps/portugal-to-singapore-train/): The longest train journey is epic – but nobody's ever taken it</small>


| 🔥: 67 \| 💬: [19](https://news.ycombinator.com/item?id=44015657) \| 🗓️ 2025-05-17


<br />
理论上，从葡萄牙南部的**拉古什**到新加坡的火车旅程横跨13个国家、8个时区，全长18,755公里，需约14天。2021年**中老铁路**通车后，这条路线才成为可能。然而，**无人完成过全程**，原因包括俄乌战争导致巴黎-莫斯科线路中断、需换乘20次且无法购买联程票等争议。若未来亚洲高铁网络建成，昆明至新加坡的行程或缩短至15小时。相比之下，莫斯科至平壤的单一列车（10,214公里）才是吉尼斯认证的**最长不换乘路线**。

---

## <a name="13"></a>13. Transformer神经网络仅通过示例学习运行《生命游戏》 
<small>🔗 [sidsite.com](https://sidsite.com/posts/life-transformer/): Transformer neural net learns to run Conway's Game of Life just from examples</small>


| 🔥: 62 \| 💬: [32](https://news.ycombinator.com/item?id=44013154) \| 🗓️ 2025-05-17


<br />
研究发现，一个高度简化的**Transformer神经网络**仅通过训练《生命游戏》的示例，就能完美模拟该游戏。模型结构显示，它并非基于统计预测，而是真正学会了游戏规则——其**注意力机制**实现了3x3卷积运算（用于计算细胞邻居数量）。该模型名为**SingleAttentionNet**，仅包含单头注意力模块，将网格编码为令牌处理。实验表明，模型通过注意力矩阵学习排除中心细胞的3x3平均池化，训练后能准确运行100步游戏。研究还发现，若手动替换注意力层为邻居计算或平均池化，模型学习速度更快且能泛化到任意网格尺寸。

---

## <a name="14"></a>14. 你并不需要在桌面端使用NixOS 
<small>🔗 [aruarian.dance](https://aruarian.dance/blog/you-do-not-need-nixos/): You do not need NixOS on the desktop</small>


| 🔥: 60 \| 💬: [84](https://news.ycombinator.com/item?id=44012915) \| 🗓️ 2025-05-17


<br />
作者分享了自己从Manjaro转向**NixOS**一年的体验，最终选择回归基于Fedora Silverblue的发行版。NixOS虽以**可复现系统**和声明式配置为卖点，但实际使用中面临文档匮乏、错误信息晦涩、开发环境配置繁琐等问题。尤其当需要为不同项目维护`flake.nix`文件时，反而增加了复杂性。相比之下，**不可变系统**（如Silverblue）通过Flatpak、Distrobox等工具实现了类似目标，同时更贴近普通用户"开箱即用"的需求。作者认为NixOS更适合服务器场景，而桌面端应优先考虑易用性而非绝对可控性。

---

## <a name="15"></a>15. 神秘编程语言：用魔法阵书写PostScript 
<small>🔗 [suberic.net](https://suberic.net/~dmm/projects/mystical/README.html): Mystical</small>


| 🔥: 58 \| 💬: [3](https://news.ycombinator.com/item?id=44016037) \| 🗓️ 2025-05-17


<br />
本文介绍了一种名为**Mystical**的编程语言设计，其灵感源自魔法阵的环形结构。Mystical将PostScript代码转化为由**环形文本**和**符号**组成的图形化表达，包含三种核心结构：**可执行数组**（带星形标记）、**非执行数组**（三角形标记）和**字典**（双边框多边形）。符号系统替代传统操作符，用户可自定义新符号。目前Mystical仅作为可视化工具，需人工转换为PostScript执行，但设计理念可扩展至Forth等语言。布局算法仍需优化以减少图形间距。

---
