# Loongson Pi 入门手册

## 简介

龙芯，全称龙芯中科技术有限公司，是中国的一家集成电路设计企业，专注于研发和生产具有自主知识产权的CPU芯片。公司成立于2001年，由中国科学院计算技术研究所发起，是中国自主研发CPU技术的重要力量。龙芯的研发始于国家863计划和973计划，旨在打破国外CPU技术的垄断，提升国家信息安全和产业竞争力。

详细的介绍可参考：https://www.bilibili.com/video/BV1Nu4m1K79M



### 发展历程

- **2000年代初：项目启动**
  - 2001年：中国科学院计算技术研究所启动龙芯项目，作为国家863计划和973计划的一部分，旨在研发具有自主知识产权的CPU。
  
  
-  **2002-2005年：早期研发**
  - 2002年：龙芯1号（Godson-1）发布，这是龙芯的首款CPU，主要用于教育和科研领域。
  - 2005年：龙芯2号（Godson-2）发布，性能较1号有所提升，开始尝试在更广泛的应用场景中使用。
  
  
-  **2006-2010年：技术积累与产业化**
  - 2006年：龙芯2E和2F发布，这些产品在性能和功耗方面有所优化。
  - 2009年：龙芯3号（Godson-3）系列的首款产品发布，标志着龙芯技术进入一个新的发展阶段。
  
  
- **2011-2015年：产业化加速**
  - 2011年：龙芯3A1000发布，这是龙芯3号系列的首款四核处理器，性能有了显著提升。
  - 2012年：龙芯3B1000发布，专为服务器市场设计。
  - 2015年：龙芯3A2000发布，进一步增强了性能和能效。
  
  
- **2016-2020年：市场拓展与产品升级**
  - 2016年：龙芯3A3000发布，继续提升性能，优化功耗。
  - 2018年：龙芯3A4000发布，采用新的微架构设计，性能和能效比进一步提升。
  - 2020年：龙芯3A5000开始研发，预计性能将有大幅提高。
  
  
- **2021年至今：持续创新与国际合作**
  
  - 2021年：龙芯中科技术有限公司继续推动龙芯CPU的产业化和市场化，同时加强与国内外合作伙伴的合作。
  - 2023年：龙芯3A6000的研发取得进展，预计将进一步提升性能和能效，增强在国内外市场的竞争力。



### 龙芯派

龙芯派，通常指的是基于龙芯CPU的一系列开发板和相关硬件产品，它们为开发者和爱好者提供了一个平台，用于学习和实验基于龙芯CPU的系统开发。龙芯派产品通常包括主板、处理器、内存、存储和其他接口，支持Linux操作系统，适合用于嵌入式系统开发、教育学习、科研探索等多种应用场景。随着龙芯技术的不断进步，龙芯派产品也在不断更新迭代，为国产软硬件生态的发展做出了积极贡献。

本手册会尽量跟随 Loongson Pi 的发行版本同步更新，让大家可以掌握最新的 Loongson Pi 技巧。以下是本手册对应的章节以及对应代码，请根据需要进行学习：

| 名称         | 介绍                                                         | 入口                          |
| ------------ | ------------------------------------------------------------ | ----------------------------- |
| 龙芯生态介绍 | 认识龙芯软件体系、生态、软件支持平台支持情况。               | [进入](docs/00.Introduce.md)  |
| 龙芯派的使用 | 给没有任何基础或第一次使用龙芯派的小伙伴一个全面的介绍使用说明。 | [进入](docs/01.Quickstart.md) |



本手册将会持续更新，欢迎小伙伴点star或提交PR以及您宝贵的建议。如果有任何错误欢迎指出或提交PR帮助修改。