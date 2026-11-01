# 第三方资料镜像

7个仓库最初按默认分支浅克隆，现作为主仓库的Git子模块固定版本，用于本地阅读和检索。初始化后仍可分别使用Git查看上游历史和差异。

完整获取方式：在主仓库运行`git submodule update --init --recursive`，或首次使用`git clone --recurse-submodules https://github.com/LeoCeasar/dad-on-the-way.git`。子模块目标提交以主仓库Git记录为准，并与`sources.lock.json`核对。

- [项目深度理解、阶段索引、证据边界与检索方法](../README.md)
- [来源与精确版本记录](sources.lock.json)

| 本地目录 | 上游 |
| --- | --- |
| [Pregnancy-Knowledge](Pregnancy-Knowledge/) | [Qianli-Ma/Pregnancy-Knowledge](https://github.com/Qianli-Ma/Pregnancy-Knowledge) |
| [hands-on-dad](hands-on-dad/) | [pxiuqin/hands-on-dad](https://github.com/pxiuqin/hands-on-dad) |
| [learn-pregnancy](learn-pregnancy/) | [zhangluustb/learn-pregnancy](https://github.com/zhangluustb/learn-pregnancy) |
| [BloomTalk](BloomTalk/) | [zhiyuzi/BloomTalk](https://github.com/zhiyuzi/BloomTalk) |
| [LittleSteps](LittleSteps/) | [sean1093/LittleSteps](https://github.com/sean1093/LittleSteps) |
| [awesome-parenting](awesome-parenting/) | [davidpelayo/awesome-parenting](https://github.com/davidpelayo/awesome-parenting) |
| [HowToLiveBetter](HowToLiveBetter/) | [eternity4719/HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter) |

`awesome-parenting` 存在同名项目；此处保存的是与所给描述最匹配的候选，选择理由见主 README。仓库内容用于研究，克隆不会自动获取外链正文；本次没有安装或运行应用，也没有启用上游提供的 Agent 技能。

核查日期：2026-11-01。上游文件未作修改。请将后续自己的整理写在镜像外，保持来源可比对；更新后同步刷新版本记录和相关分析。
