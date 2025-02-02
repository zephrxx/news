---
layout: page
title: 勒西科技日报 - 2025年02月02日
date: 2025-02-02 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 你的位置无所遁形：通过应用内广告追踪自己的经历；
1. 生活不止是一个工程问题；
1. SanDisk High Endurance microSDXC 存储卡逆向工程与分析（2020）；
1. Show HN: Lume - 专为Apple Silicon设计的轻量级macOS/Linux虚拟机CLI工具；
1. 深入解析高性能缓存库Caffeine的代码架构；

以上是今天的前五条黑科技新闻标题。

总共11条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 你的位置无所遁形：通过应用内广告追踪自己的经历 
<small>🔗 [timsh.org](https://timsh.org/tracking-myself-down-through-in-app-ads/): Everyone knows your location: tracking myself down through in-app ads</small>


| 🔥🔥: 626 \| 💬: [208](https://news.ycombinator.com/item?id=42909921) \| 🗓️ 2025-02-02


<br />
作者通过实验发现，**广告SDK（如Unity Ads）** 即使在关闭位置权限时仍会收集精确地理坐标、IP及设备信息，并通过实时竞价协议（OpenRTB）流向广告交易平台。数据经纪公司（如Redmob）以高价出售含**IDFA**等标识符的定位数据库，结合个人身份信息（PII）可精准追踪个体轨迹。欧盟用户数据最贵，而**用户选择“禁止追踪”仅屏蔽跨应用ID，无法阻止基础数据泄露**。

---

## <a name="2"></a>2. 生活不止是一个工程问题 
<small>🔗 [lareviewofbooks.org](https://lareviewofbooks.org/article/life-is-more-than-an-engineering-problem/): Life is more than an engineering problem</small>


| 🔥🔥: 282 \| 💬: [164](https://news.ycombinator.com/item?id=42907268) \| 🗓️ 2025-02-02


<br />
Ted Chiang 在与 Julien Crockett 的对话中探讨了人工智能、语言哲学与科技未来。他批判当前大型语言模型（**LLMs**）仅是“网络信息的模糊JPEG”，缺乏真实理解与推理能力，强调**人类主义**在技术变革中的核心地位。Chiang 认为，语言与数学无法完全替代人类复杂交流，而历史上对**完美语言**的追求本质是徒劳的。他通过科幻故事揭示哲学问题，主张科技应服务于人性，而非将其简化为工程难题。面对AI热潮，他呼吁警惕技术乌托邦叙事，重视现实中的伦理与情感维度。

---

## <a name="3"></a>3. SanDisk High Endurance microSDXC 存储卡逆向工程与分析（2020） 
<small>🔗 [ripitapart.com](https://ripitapart.com/2020/07/16/reverse-engineering-and-analysis-of-sandisk-high-endurance-microsdxc-card/): Reverse-engineering and analysis of SanDisk High Endurance microSDXC card (2020)</small>


| 🔥🔥: 210 \| 💬: [82](https://news.ycombinator.com/item?id=42907766) \| 🗓️ 2025-02-02


<br />
作者通过逆向工程拆解 SanDisk 高耐久度存储卡，发现其采用 **3D TLC 闪存**，而 MAX Endurance 系列则通过 **pMLC 模式**提升耐用性。面对官方技术支持信息缺失，作者通过物理暴露测试点、自制转接板及逻辑分析仪追踪信号，最终解析出闪存 ID 并确认芯片规格。研究揭示了 SanDisk 对内部技术细节的严格保密，以及存储卡控制器与闪存总线间的复杂交互机制，为同类设备逆向工程提供了参考路径。

---

## <a name="4"></a>4. Show HN: Lume - 专为Apple Silicon设计的轻量级macOS/Linux虚拟机CLI工具 
<small>🔗 [github.com](https://github.com/trycua/lume): Show HN: Lume – OS lightweight CLI for MacOS and Linux VMs on Apple Silicon</small>


| 🔥🔥: 207 \| 💬: [60](https://news.ycombinator.com/item?id=42908061) \| 🗓️ 2025-02-02


<br />
Lume 是一款基于 **Apple Virtualization.Framework** 的轻量级命令行工具，支持在Apple Silicon设备上快速创建、运行和管理macOS与Linux虚拟机。核心功能包括一键启动预构建镜像（如macOS Sonoma 15.2和Ubuntu 24.04）、动态调整CPU/内存/磁盘配置，以及通过本地API服务器实现自动化管理。通过 **ghcr.io/trycua** 提供优化镜像，支持SSH和共享目录，并采用MIT开源协议，支持Homebrew安装及社区贡献。

---

## <a name="5"></a>5. 深入解析高性能缓存库Caffeine的代码架构 
<small>🔗 [adriacabeza.github.io](https://adriacabeza.github.io/2024/07/12/caffeine-cache.html): Analyzing the codebase of Caffeine, a high performance caching library</small>


| 🔥🔥: 179 \| 💬: [32](https://news.ycombinator.com/item?id=42907488) \| 🗓️ 2025-02-02


<br />
本文探讨了Caffeine缓存库的核心机制，重点分析其**Window TinyLFU驱逐策略**：通过准入窗口筛选新条目，结合**频率草图（CountMinSketch）**估算访问频率，并采用分段LRU优化热点数据留存。同时，库内通过无哨兵节点的双链表队列和分层时间轮实现高效过期管理。这些设计以O(1)时间复杂度保障高命中率与低内存开销，支撑了Kafka、Cassandra等大型系统的缓存需求。

---

## <a name="6"></a>6. Sniffnet：网络流量监控工具 
<small>🔗 [github.com](https://github.com/GyulyVGC/sniffnet): Sniffnet – monitor your Internet traffic</small>


| 🔥🔥: 161 \| 💬: [66](https://news.ycombinator.com/item?id=42909530) \| 🗓️ 2025-02-02


<br />
一款**跨平台应用**，可直观监测互联网流量，支持实时流量图表、自定义通知及深度数据包分析。提供多语言界面，支持 Windows/macOS/Linux 系统，可通过 Homebrew、Cargo 等多种方式安装。内置**6000+协议识别**功能，支持 IP 地理定位、本地网络连接检测及 PCAP 报告导出。完全免费开源（Apache-2.0/MIT 双许可），需注意系统依赖项安装，并提供故障排查指南与用户手册。

---

## <a name="7"></a>7. 间隔重复法可实现无限记忆（2022年） 
<small>🔗 [efavdb.com](https://www.efavdb.com/memory%20recall): Spaced repetition can allow for infinite recall (2022)</small>


| 🔥🔥: 119 \| 💬: [140](https://news.ycombinator.com/item?id=42908041) \| 🗓️ 2025-02-02


<br />
通过**间隔重复**记忆法，新知识需高频复习巩固，但随着复习次数增加，保留时间呈**幂律增长**（T(s)∼s^γ）。研究表明，若按特定规则筛选记忆内容（N(t)∼t^{-[1/(γ+1)+ε]}），每日有限复习时间可覆盖无限增长的知识库。数学推导证明，当γ>0时，总记忆量随时间呈t^{γ/(γ+1)}增长，最终实现**无限记忆**。核心在于动态调整旧知识复习频率，确保系统可持续扩展。

---

## <a name="8"></a>8. 修复文法中的左递归与相互递归问题 
<small>🔗 [brightprogrammer.in](https://brightprogrammer.in/posts/fixing-recursions-in-grammar/): Fixing left and mutual recursions in grammars</small>


| 🔥: 91 \| 💬: [22](https://news.ycombinator.com/item?id=42907139) \| 🗓️ 2025-02-02


<br />
在上下文无关文法（CFG）中，**左递归**会导致自上而下解析算法陷入无限循环。例如，形如 `⟨S⟩ ::= ⟨S⟩ a | b` 的规则可通过转换为**右递归**解决：引入辅助符号 `⟨S’⟩` 改写为 `⟨S⟩ ::= b⟨S’⟩` 和 `⟨S’⟩ ::= a⟨S’⟩ | ε`。对于**相互递归**（如规则A→B、B→A），需重构语法树使其仅含右递归。作者以C++ demangler重构为例，展示了如何通过拆分规则、引入中间符号（如 `prefix_X`、`template_prefix_S2`）消除复杂递归，避免堆栈溢出。核心思路是将递归转移至右侧，确保解析器能有限步数内终止。

---

## <a name="9"></a>9. Waydroid——Linux 容器中的安卓系统 
<small>🔗 [waydro.id](https://waydro.id/): Waydroid – Android in a Linux container</small>


| 🔥: 80 \| 💬: [12](https://news.ycombinator.com/item?id=42911042) \| 🗓️ 2025-02-02


<br />
通过 **Linux 命名空间**技术，在基于 Wayland 的 GNU/Linux 桌面环境中运行完整安卓系统，实现**原生级性能**与硬件直通。支持多架构（ARM/x86）及主流 GPU，提供多窗口模式、全屏应用集成，并深度整合安卓应用至 Linux 程序目录。项目基于 LineageOS 定制安卓 11 镜像，开源社区驱动，含详细安装指南及定制化发行版（如 Ubuntu/Debian），需注意 NVIDIA GPU 需使用软件渲染。

---

## <a name="10"></a>10. 强化学习：综述 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2412.05265): Reinforcement Learning: An Overview</small>


| 🔥: 64 \| 💬: [10](https://news.ycombinator.com/item?id=42910028) \| 🗓️ 2025-02-02


<br />
本文全面概述了（深度）强化学习与序列决策领域的最新进展，涵盖**基于价值的强化学习**、**策略梯度方法**、**基于模型的方法**等核心方向，并简要探讨了强化学习与大语言模型（LLMs）的结合。作者Kevin Murphy系统梳理了相关技术脉络与未来趋势。

---

## <a name="11"></a>11. 马斯克“政府效率部”背后的年轻工程师：资历浅，权限大 
<small>🔗 [wired.com](https://www.wired.com/story/elon-musk-government-young-engineers/): The Young, Inexperienced Engineers Aiding Elon Musk’s Government Takeover</small>


| 🔥: 57 \| 💬: [15](https://news.ycombinator.com/item?id=42910910) \| 🗓️ 2025-02-02


<br />
**年轻且缺乏经验的工程师团队**（19-24岁）正协助马斯克通过“政府效率部”（DOGE）项目接管联邦机构，多数与马斯克或彼得·蒂尔有关联。他们已控制人事管理办公室（OPM）和总务署（GSA），并获准访问财政部支付系统，**可能获取数千万公民敏感数据**。部分成员被曝试图越权访问机密信息，引发专家对“私营势力操控政府”的质疑。  

团队成员包括SpaceX前实习生、Palantir关联者及OpenAI资助的创业者，**多人无政府工作经验却拥有高级安全权限**。学者警告此举或构成“全球首富对政府机器的敌意接管”，存在监管缺失与公共利益风险。

---
