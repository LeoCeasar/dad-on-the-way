# 从孕期到青少年的养育资料库

## 公开文档入口

根目录保存对外阅读文档，使用“阶段数字＋字母.中文主题.html”命名。字母表示阶段内的阅读顺序；版本和核验日期写在正文中。

| 编号 | 已发布文档 | 用途 |
| --- | --- | --- |
| 0a | [孕期产检规划与指标解读](0a.孕期产检规划与指标解读.html) | 孕周检查、报告指标、日常血糖与糖耐、孕前糖尿病随访 |
| 0b | [孕期陪伴与胎教方法](0b.孕期陪伴与胎教方法.html) | 通用规则、智力提示、概念定义、活动方法和来源 |
| 0c | [孕期陪伴与胎教执行计划](0c.孕期陪伴与胎教执行计划.html) | 阶段甘特图、一周示例、音乐与语言材料、条件适配 |

全程分8个阶段：**0孕期 → 1产后恢复与新生儿（最初6周） → 2婴儿（6周至1岁） → 3幼儿（1–3岁） → 4学龄前（3–6岁） → 5学龄期（6–12岁） → 6青春期前段（12–15岁） → 7青春期后段（15–18岁）**。这些是资料导航分段，不是统一发育标准；6周也不是产后恢复的结束线。

目前仅发布上述3份孕期HTML。其他阶段不创建空白占位文件。底稿在`docs/drafts/`，审核记录在`docs/reviews/`，原图在`assets/references/`，第三方镜像保留在`thrid_party/`。

[目录架构与完整命名规划](docs/architecture.md) · [文档与来源索引](docs/source-map.md)

本项目先建立可检索、可追溯的资料底座：保存第三方仓库原文，区分知识笔记、资源导航和记录工具，再据此整理家庭行动指南。

**核查日期：2026-11-01。已将 7 个 GitHub 仓库拉取到 `./thrid_party/`。**目录名沿用本项目约定的 `thrid_party`。本 README 基于本地 README、目录、代表性正文、数据文件和许可证核读，不只是转述项目介绍。

当前最有价值的组合是：**Pregnancy-Knowledge 提供孕产笔记，learn-pregnancy 提供学习和记录模板，hands-on-dad 提供长期资源地图，HowToLiveBetter 补充办事与安全选题；BloomTalk 和 LittleSteps 用来理解计划与成长记录的组织方式，awesome-parenting 用来扩展教育理念和亲子沟通资源。**这些仓库仍不足以直接拼成经过医学审校的孕期至 18 岁执行体系。

已整理的专题：[孕检规划与关键指标解读](docs/drafts/0a.孕检规划与指标解读.md)，包含中国大陆通用孕周时间表、检查意义、关键指标、就诊准备与记录模板；[双向核验记录](docs/reviews/0a.孕检双向核验记录.md)保存本地资料到官方依据的逐项校正，以及官方框架反查得到的补充内容。专题联网核验日期为2026-11-01，筛查窗口纳入2025国家文件，贫血指标参考2026专项共识。

图解阅读版：[孕检规划与指标图解](0a.孕期产检规划与指标解读.html)。单个HTML文件，可离线打开，支持孕周窗口高亮、来源跳转及打印。内容采用ASD-STE100短句、明确动作和统一术语原则的中文适配，不声明受控英语标准合规。

2026-11-01二次审核：图解版已增加**日常控糖与糖耐诊断对照、从第一口计时图、孕前1型/2型糖尿病检查与随访、低血糖和产后分流**，并补齐检查俗称。依据与访问限制见[HTML二次审核记录](docs/reviews/0a.孕检HTML二次审核记录.md)。小红书完整原始图文尚未读取，未将其列作已验证来源。

## 孕检章节形成的整理经验

孕检章节最重要的反馈是：**数字正确，不代表表达已经清楚。**上一版突出显示糖耐2小时诊断界值8.5，却没有同等突出日常餐后目标，导致用户难以与医生的“小于7.0”对应。后续专题统一采用以下方法。

1. **先写通用规则，再写适用条件。**正文面向一般孕妇与家属；糖尿病等情况另列条件适配。实际需求可以触发补充，但不把某一家庭的病史当作所有读者的默认情况。低风险、GDM及孕前1型/2型方案分别说明。
2. **每个数字带齐条件。**写明检查/活动名称、对象、孕周或计时起点、样本或测量方法、单位，以及它属于诊断界值、管理目标、参考区间还是家庭安排示例。保留`＜`、`≥`等边界，不只写一个数字。
3. **个人医嘱只作注明边界的情境。**例如某位孕妇被要求餐后2小时＜7.0，该数值不能复制成所有人的目标，也不能用OGTT的8.5放宽。通用规则解释场景、测量条件和咨询方法；病例匿名另列。
4. **区分证据能回答的问题。**研究发现胎儿对声音有反应或形成早期记忆，不等于证明未来智力、语言或音乐能力提高。研究采用的时长、音量，不自动成为家庭推荐剂量。没有依据时，不编造“开课孕周”和安全上限。
5. **双向查缺，不只为原稿找支持。**正向逐条检查原稿、仓库和图片的说法；反向从官方指南和原始研究检查遗漏，包括适用人群、复查、低血糖、停止条件和产后路径。转载与解读不重复计算为独立证据。
6. **官方内容也逐条审核。**国家文件、专业指南、医院科普的用途不同；版本、地区和定义可能有差别。保留冲突及采用理由，不能只因域名官方就照搬整表。小红书和图片用于发现问题、学习表达，不替代医学依据。
7. **名称、目的、结果与行动连起来。**同时写正式名称与常用名；检查窗口不画成人人必须完成的清单。异常时写清联系谁、是否复查。家庭活动也写“现在做什么、何时减少或停止”。
8. **图解要防止误读。**不同用途的数值分开画；示例不得伪装成个人结果。用短句和明确动作表达，保留必要条件。核对手机、电脑、离线阅读、来源链接与打印；相关HTML、文字版和README同步更新。

这些是本项目的编辑与验证规则，不是临床指南或ASD-STE100认证流程。当前孕周以产科核定值为准，不根据旧文件日期或对话中的“即将16周”自动推算。

## 胎教与孕期陪伴专题

2026-11-01已结合两份旧HTML、用户提供的七类胎教图和联网证据进行修订。两份HTML现按0b、0c编号命名，内容版本均为2.2。2026-11-01进一步完成[海内外概念与出处对照](docs/reviews/0bc.胎教海内外对照审核.md)：通用规则为主、条件适配另列、个人医嘱仅作匿名情境。

| 入口 | 用途 |
| --- | --- |
| [方法与依据说明版](<0b.孕期陪伴与胎教方法.html>) | 对照原图七项说法；理解方法、适用范围、家庭分工与安全边界 |
| [阶段甘特执行版](0c.孕期陪伴与胎教执行计划.html) | 按当前孕周选阶段；查看一周示例、音乐与语言材料，以及减量方法 |
| [胎教内容双向核验记录](docs/reviews/0bc.胎教内容双向核验记录.md) | 保存原始说法与2.0版的逐项修订 |
| [海内外对照审核](docs/reviews/0bc.胎教海内外对照审核.md) | 2.1版的C01–C07定义、发布机构、原文位置、相同点及差异 |
| [智力提示与方法论审核](docs/reviews/0bc.胎教智力提示与方法论审核.md) | 2.2版的I01–I04提示、M01–M06检索方法、架构问题与修订、访问限制 |

此次修订取消了方法版的人为十分制评分，统一为“P0健康照护、P1父母准备、P2自愿陪伴”。图中的12/16/18/21/24/28/30周起点与固定分钟数不作为必修课表。保留音乐、人声、轻触和情绪支持的可选安排；不安排照腹训练和胎内知识课程。新增孕前糖尿病的活动前、中、后配合方法，运动与血糖监测继续服从个人医嘱。

2.2版新增醒目的智力提示和可跳转索引。提示区分早期声音记忆、新生儿行为评分与长期智力；纳入2026语言综述及报告正向结果的试验，保留它们的适用限制。方法审核覆盖检索词、纳入／排除、偏倚、双向核对和更新，不宣称完成注册系统综述或专家联合会诊。

国内外来源按“对象、行为、观察结果”对照。名称不同但定义重合时可以合并解释；父母产前教育与胎儿声音学习等对象不同的内容保留差异，不因译名相近而合并。

本次已核读用户提供的图片，但作者、日期与原始发布链接未知，不能将其身份认定为已核验的小红书笔记。检查窗口与血糖指标继续以[孕检图解](0a.孕期产检规划与指标解读.html)及对应审核记录为入口，避免每个专题各写一套不一致的数字。

## 阅读导航

- [项目身份与本地版本](#项目身份与本地版本)
- [先纠正几处容易误解的介绍](#先纠正几处容易误解的介绍)
- [逐项目理解](#逐项目理解)
- [按阶段与目标检索](#按阶段与目标检索)
- [证据和内容质量](#证据和内容质量)
- [孕检章节形成的整理经验](#孕检章节形成的整理经验)
- [胎教与孕期陪伴专题](#胎教与孕期陪伴专题)
- [本地检索方法](#本地检索方法)
- [后续整理的结构](#后续整理的结构)
- [同步与许可](#同步与许可)

## 项目身份与本地版本

仓库保留独立 `.git`，采用 `git clone --depth 1` 获取默认分支的工作树；历史为浅克隆，外链网页、电子书、视频、课程及 Release 附件没有随之下载。上游原文没有修改，没有安装依赖或运行这些应用。

| 项目 / 已核实的上游 | 本地入口 | 类型与实际价值 | 本地 HEAD / 最近提交日期 |
| --- | --- | --- | --- |
| [Qianli-Ma/Pregnancy-Knowledge](https://github.com/Qianli-Ma/Pregnancy-Knowledge) | [原仓库](thrid_party/Pregnancy-Knowledge/README.md) | 中文孕产、饮食、产后与婴儿护理笔记 | `44f73fde4f71` / 2025-06-04 |
| [pxiuqin/hands-on-dad](https://github.com/pxiuqin/hands-on-dad) | [资源目录](thrid_party/hands-on-dad/README.md) | 从胚胎到 17 岁的教育资源导航，深度不均 | `7b8b5c8ebed0` / 2026-02-28 |
| [zhangluustb/learn-pregnancy](https://github.com/zhangluustb/learn-pregnancy) | [课程文件](thrid_party/learn-pregnancy/docs/) | 孕产学习课、问答、健康档案与沟通模板 | `407eb6a40410` / 2026-05-15 |
| [zhiyuzi/BloomTalk](https://github.com/zhiyuzi/BloomTalk) | [使用说明](thrid_party/BloomTalk/README.md) | 供 Agent 使用的孕期支持工作流、知识与记录模板 | `7349937c8a46` / 2026-04-05 |
| [sean1093/LittleSteps](https://github.com/sean1093/LittleSteps) | [应用说明](thrid_party/LittleSteps/README.md) | 中国台湾地区孕期、婴幼儿记录及周边服务 PWA | `38edae19a38b` / 2026-10-19 |
| [davidpelayo/awesome-parenting](https://github.com/davidpelayo/awesome-parenting) | [英文索引](thrid_party/awesome-parenting/README.md) | 教育理念、亲子沟通书目、网站与课程导航 | `1998d859dde6` / 2026-07-31 |
| [eternity4719/HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter) | [全书目录](thrid_party/HowToLiveBetter/README.md) | 综合生活指南，含孕产办事、新生儿与学龄期安全专题 | `e2605d3e2242` / 2026-10-21 |

完整 URL、分支、40 位提交 SHA、提交时间、跟踪文件数量与许可观察保存在 [sources.lock.json](thrid_party/sources.lock.json)。提交日期只说明仓库发生过变更，不代表所有资料都在当天重新核验。

**awesome-parenting 的身份有歧义。**原介绍没有作者或 URL；本次比较同名仓库后，选择同时包含 Montessori、Reggio Emilia、Positive Discipline、亲子沟通书目及 Courses 的 `davidpelayo/awesome-parenting`。`Athen-Player1/awesome-parenting` 更偏课程、网络安全及工具，`daugaard/awesome-parenting` 更偏家庭工具与 App。所选版本与描述最匹配，但无法证明原介绍唯一指向它。`hands-on-dad` 则已按内容确认是 `pxiuqin` 的资源导航，不是同名育儿博客。

## 先纠正几处容易误解的介绍

| 原介绍容易让人产生的理解 | 本地文件核查结果 | 对后续使用的影响 |
| --- | --- | --- |
| Pregnancy-Knowledge 已有完整 0–5 岁宝典 | 文件存在，但正文明显集中在母乳、配方奶、新生儿护理、用品与睡眠 | 不能据文件名认定已覆盖 1–5 岁培养 |
| learn-pregnancy 有 420 道问答、12 张漫画、多格式成品 | 有 20 节课；10 个题库中前 9 个共 90 个显式 `Q` 条目，最后一个有 18 个判断、填空、场景及论述项目；漫画实际是 12 份提示词；HTML/PDF 提供构建脚本 | 不照抄宣传数量；本地没有现成漫画图片或导出成品 |
| learn-pregnancy 的 README 目录可直接使用 | 课程和题库相对链接共发现 12 处目标不存在，涉及不同连字符及旧题库文件名 | 使用本 README 的实际路径和 `rg --files` 查找 |
| BloomTalk 是开箱即用、自动安排的胎教 App | 核心是 Agent 指令、Markdown 知识库和记忆文件，附 HTML 日历；档案为空白，计划/日志有示例 | 可以借鉴流程，不能称已部署的个人管理系统 |
| LittleSteps 只是 0–3 岁记录工具 | 当前版本是六项服务，增加孕期、外出地点、哺乳室地图和疾病雷达 | 应按服务与数据文件检索；地区数据不可直接迁移到中国大陆 |
| HowToLiveBetter 只覆盖出生前后到 1 岁 | 除第 20、27 节外，第 30 节还覆盖学龄儿童及青少年健康安全 | 能补足长期安全选题，但不是学科或兴趣培养课程 |
| 收入育儿资源清单就意味着已经科学验证 | 多数仓库混合官方资料、书介、个人笔记、论坛、商业课程及作者判断 | 需要逐条追溯，不能给整个仓库贴统一的高证据标签 |

上述题目计数只统计 `interview/` 的显式题目，不把课程末练习重复叠加；Web 元数据宣称的题数合计为 110，也不能作为正文已写题数。

## 逐项目理解

### 1. Pregnancy-Knowledge：孕产主题笔记底稿

**定位：**作者为家庭整理的阅读笔记，适合快速找主题和解释材料。仓库声明参考梅奥、海蒂、西尔斯、协和及 AAP 相关书籍，但正文没有统一的逐条引文或医学审校记录。

核心只有几个长篇 Markdown，图片多放在 `assets/`。以当前快照计，`孕期知识.md` 2075 行、`饮食.md` 589 行、`产后恢复.md` 110 行、`0-5岁带娃宝典.md` 625 行。

| 实际入口 | 可以检索什么 | 适合整理的对象 |
| --- | --- | --- |
| [孕期知识](thrid_party/Pregnancy-Knowledge/孕期知识.md) | 孕前准备、准爸爸支持、运动、不适、疾病用药、旅行、疫苗、逐月发育、分娩 | 主题解释、阶段入口、家庭分工候选条目 |
| [饮食](thrid_party/Pregnancy-Knowledge/饮食.md) | 营养素、食品安全、孕吐、饮食不适 | 需要进一步核验的饮食问答 |
| [产后恢复](thrid_party/Pregnancy-Knowledge/产后恢复.md) | 乳房、会阴、恶露、如厕、体重等 | 产后关注点目录 |
| [0–5 岁带娃宝典](thrid_party/Pregnancy-Knowledge/0-5岁带娃宝典.md) | 母乳与配方奶、用品、新生儿外观、哭闹、睡眠、洗澡、换尿片 | 婴儿照护主题，而非五年课程 |

**理解重点：**“孕周”与“主题”是两条交叉索引，主文和饮食文有重复，后续抽取时要去重。准爸爸支持部分比单纯胎儿发育表更适合转换为家庭分工。产后短文不能承担完整的产后评估与康复方案。

**边界：**常用药表、补充剂单位、胎动自查及筛查路径需要优先复核，具体问题见后文质量表。部分笔记体现境外书籍或就医路径，不能直接当成国内医院统一流程。许可文件为 [GPL v3](thrid_party/Pregnancy-Knowledge/LICENSE)。

### 2. hands-on-dad：长期教育资源地图

**定位：**以单个长 README 为主体的导航，适合发现“下一步去哪里查”，很少直接提供成套课程。1405 行 README 外，仓库主要只有图片和两个 PDF。

目录从发育评估、胚胎、新生儿、1–2、3–5、6–11、12–14、15–17 岁展开，再进入家庭教育、学校教育、社会教育和 STEAM。年龄分节的存在不代表各阶段内容充实，青春期部分尤其偏书目。

| [README 内的分类](thrid_party/hands-on-dad/README.md) | 实际用途 | 使用时要补的内容 |
| --- | --- | --- |
| 儿童发展阶段 / 发育评估 | 找官方指南、监测图和书目 | 发布机构、版本、适用人群；工具用途需核实 |
| 家庭教育 / 健康安全 | 找卫健委、UNICEF、WHO 等资料线索 | 获取原文并核对现行建议 |
| 亲子时间 / 童谣、故事、绘本、自然、动手 | 找亲子互动素材 | 适龄性、材料准备、活动步骤和安全边界 |
| 学校教育 / 语言 | 中文、粤语、英语等学习资源 | 区分婴幼儿、学龄儿童和成人学习内容 |
| STEAM / 音乐 | 乐理、乐器、欣赏、制作及科学探索线索 | 筛除成人工具；不能当作逐龄乐感训练课 |

可离线访问的附带资料是 [儿童心理行为发育问题预警征象筛查表](thrid_party/hands-on-dad/docs/儿童心理行为发育问题预警征象筛查表.pdf) 和 [中文经典儿歌大全](thrid_party/hands-on-dad/docs/中文经典儿歌大全.pdf)。本次仅核实文件存在，没有逐页审阅 PDF 的来源、版本或全部内容。

**理解重点：**最合适的抽取单位是“资源名称、分类、原始 URL、来源类型、适龄范围待核验、是否已获得全文”。书介和资源推荐语不能并入科学结论，例如关于语言发展窗口及“最优秀教育法”的绝对化表述。根目录未发现许可证文件，后续公开再利用须另行确认范围。

### 3. learn-pregnancy：学习结构和就诊记录模板

**定位：**明确引用 Pregnancy-Knowledge 的衍生学习材料，两者不是完全独立的证据来源。结构比原始笔记更清楚，但包装完整度和医学准确性要分开判断。

`docs/` 的 L01–L20 分为四组：孕前与产检安全基础；按月发育与营养；孕晚期及分娩；产后、新生儿、爸爸参与、档案和沟通。`interview/` 实际按主题排列，和 README 中旧的“孕早/中/晚期各 100 题”目录不同。

| 实际入口 | 核读后的价值 |
| --- | --- |
| [L03 产检时间表](thrid_party/learn-pregnancy/docs/L03-与医生同行——产检时间表全解.md) | 学习检查目的，具体时间和流程仍需所在地核对 |
| [L08 第 4–5 月](thrid_party/learn-pregnancy/docs/L08-第4–5月——第一次感受到你.md) / [L12 第 8–9 月](thrid_party/learn-pregnancy/docs/L12-第8–9月——最后的准备.md) | 这里链接的是实际使用长连接号的文件名 |
| [L18 孕父指南](thrid_party/learn-pregnancy/docs/L18-孕父完全指南.md) | 支持、准备与参与的学习素材 |
| [L19 健康档案模板](thrid_party/learn-pregnancy/docs/L19-孕期健康档案模板.md) | 基本资料、检查、症状、医生意见、下次安排、分娩计划与产后记录字段 |
| [L20 沟通稿](thrid_party/learn-pregnancy/docs/L20-医患沟通STAR完整稿.md) | 标题称 STAR，正文还包含 SBAR、疼痛描述和就诊前问题清单 |
| [实际题库目录](thrid_party/learn-pregnancy/interview/) | 复习与发现待问问题，不能用答案替代医疗判断 |
| [漫画目录说明](thrid_party/learn-pregnancy/assets/comics/README.md) | 明确说明为生成提示词，当前没有那 12 张成品漫画 |

**最值得借鉴的是 L19 的记录字段及 L20 的提问方式。**可以提取“发生了什么、何时开始、相关孕周、已有检查、医生交代、下次要问什么”，但模板夹带的正常范围、诊断条件与急症阈值仍须独立复核。

技术上，`web/` 是 Next.js/React 阅读站，`scripts/build_html.py` 和 `scripts/build_pdf.py` 提供导出逻辑；不能据脚本存在声称构建已经成功。本次没有运行脚本，部分脚本会尝试安装 Python 依赖。许可文件为 [MIT](thrid_party/learn-pregnancy/LICENSE)，但其声明参考的其他仓库和第三方素材不因此自动改变许可。

### 4. BloomTalk：孕期支持的计划—反馈工作流

**定位：**将知识与家庭记录分开的 Agent Runtime 仓库。它依赖助手读取指令、整理档案并更新 Markdown；HTML 日历是展示载体，不能理解为独立的后台调度服务。

| 路径 | 职责与可借鉴点 |
| --- | --- |
| [README](thrid_party/BloomTalk/README.md) / [AGENTS.md](thrid_party/BloomTalk/AGENTS.md) | 使用入口及助手工作流规范；这里作为上游资料阅读，不代表已安装启用 |
| [知识库索引](thrid_party/BloomTalk/bloom-talk-kb/index.md) | 将音乐、对话、情绪、运动、营养、触摸、自然、美育、光照等分开组织 |
| [音乐](thrid_party/BloomTalk/bloom-talk-kb/music.md) / [对话](thrid_party/BloomTalk/bloom-talk-kb/dialog.md) / [光照](thrid_party/BloomTalk/bloom-talk-kb/light.md) | 比较活动目标、适用与不推荐做法的写法，分类不等于疗效认证 |
| [档案模板](thrid_party/BloomTalk/bloom-talk-mem/profile-template.md) | 计划前先收集孕周、生活与照护条件的方式 |
| [每日计划示例](thrid_party/BloomTalk/bloom-talk-mem/plans/2026-04-03.example.md) / [晚间日志示例](thrid_party/BloomTalk/bloom-talk-mem/logs/2026-04-03.example.md) | 从建议到执行反馈，再据反馈调整 |
| [主题轨迹](thrid_party/BloomTalk/bloom-talk-mem/tracks/) | 跨天保留某一主题的偏好与变化 |
| [日历模板](thrid_party/BloomTalk/bloom-talk-calendar-template.html) / [任务列表](thrid_party/BloomTalk/docs/tasks.md) | 展示层与项目进度线索，任务列表不能替代功能验证 |

**理解重点：**可复用的是“档案 → 今日计划 → 晚间反馈 → 主题轨迹”的闭环，以及知识库与个人记忆分离。当前 `profile.md` 是空白档案，计划和日志含 example，不应误当成真实家庭记录或已验证个性化建议。

**证据边界：**A–D 分级是作者自己的分类，不等同于临床 GRADE；抽查知识页未形成可逐条追溯的外部参考链。胎教分类和自动生成计划都不能证明未来智商、外语或音乐能力获益。许可为 [MIT](thrid_party/BloomTalk/LICENSE)。

### 5. LittleSteps：结构化成长记录与地区服务

**定位：**移动端 PWA，适合研究如何把阶段内容、记录、提醒和检索连接起来。当前 README 的六项服务是 LittleBloom（孕期）、LittleSteps（0–12 月）、LittleExplorer（1–3 岁）、LittleOuting（外出地点）、BabyOasis（哺乳室地图）、LittleGuard（疾病雷达）。

| 实际内容入口 | 可检索与借鉴的内容 |
| --- | --- |
| [资料来源索引](thrid_party/LittleSteps/src/common/about/dataSources.ts) | 按功能查来源、适用地区和核验信息 |
| [孕周资料](thrid_party/LittleSteps/src/littlebloom/data/pregnancyGuides.ts) / [孕期 Wiki](thrid_party/LittleSteps/src/littlebloom/data/wiki.ts) | 孕周内容与孕期问题条目 |
| [婴儿 Wiki](thrid_party/LittleSteps/src/littlesteps/data/babyWiki.ts) / [里程碑](thrid_party/LittleSteps/src/littlesteps/data/milestones.ts) | 以结构化数据连接月龄与主题 |
| [疫苗](thrid_party/LittleSteps/src/littlesteps/data/vaccines.ts) | 地区接种计划的数据建模，不能直接作为大陆接种日历 |
| [辅食](thrid_party/LittleSteps/src/littlesteps/data/complementaryFood.ts) / [睡眠](thrid_party/LittleSteps/src/littlesteps/data/sleep.ts) | 按阶段呈现指导和记录的产品组织方式，证据需另核 |
| [幼儿 Wiki](thrid_party/LittleSteps/src/littleexplorer/data/toddlerWiki.ts) | 语言、情绪、如厕、饮食与健康等幼儿条目 |
| [疾病雷达快照](thrid_party/LittleSteps/public/data/diseaseRadar.json) | 区分数据覆盖周、核查时间和应用更新时间 |

技术为 React/TypeScript/Vite，使用 Firebase 的账号与数据服务。与前几个 Markdown 项目不同，许多可检索正文存放在 TypeScript 数组里，只搜 `.md` 会漏掉内容。这里完成的是静态源码与资料核读，没有启动应用，也没有验证账号、同步、提醒或部署。

本地数据对象核对得到孕期、婴儿、幼儿百科分别为 25、15、45 篇，共 85 篇；另有 33 条里程碑、30 条幼儿发展检核。疫苗文件有 36 条时程记录，含不同适用条件和替代选择，不能解释为每个孩子必须接种 36 针。README 中部分旧数量与当前数据不同，检索时以具体文件和版本为准。

记录设计也值得单独理解：`users/$uid` 管理账号与孩子关联，`children/$childId` 管理档案及阶段进度，`childRecords/$childId` 保存持续增加的日志。知识内容、阶段进度、实际记录由此分开；跨百科检索入口为 [crossWikiSearch.ts](thrid_party/LittleSteps/src/common/wiki/crossWikiSearch.ts)。源码具备六项服务的页面和数据模块，付费层、社区、英语/简体中文和更丰富分析等仍列在后续规划中，不能当成现有完整能力。软件睡眠评分和警报规则也不等于医学诊断。

**地区与时效：**产检、疫苗、公共服务地点和疫情来源主要面向中国台湾地区。不同数据模块的引文完整度不一致；不能因为有官方来源索引就给所有文章统一背书。雷达快照覆盖 `2026-W34`，`verifiedOn` 为 `2026-09-04`，不是本次核查日的实时疫情。

README 声明 MIT，但当前 Git 跟踪树未发现独立 LICENSE/COPYING 文件；因此许可记录为“README 声称 MIT，缺少许可证文件”，后续再发布前应确认。

此外，应用数据有各自的来源条款：疫情和部分公共服务数据标有政府资料开放授权，部分交通站点来源为 OpenStreetMap / ODbL。即使应用代码许可得到确认，也应保留这些数据的独立来源和许可要求。

### 6. awesome-parenting：理念和沟通资源发现

**定位：**英文资源清单；主体是 [README](thrid_party/awesome-parenting/README.md)，分 Resources、Platforms、Books、Techniques 和 Courses。它连接 AAP HealthyChildren 等机构、育儿媒体、论坛、16 本书目和 6 个课程入口，也包含 Montessori、Waldorf、Reggio Emilia、Positive Discipline 等方法链接。

**可用价值：**围绕亲子沟通、情绪、手足关系、执行功能与父母学习整理候选书单，比较不同教育理念。仓库不包含那些书籍全文、课程讲义、作业或逐龄活动计划。论坛、商业课程和官方机构并列，仍需逐项判断内容来源。

`es/`、`fr/`、`pt/`、`ca/`、`de/`、`it/` 是六个其他语言版本；抽读可见地区化资源，不是完全相同的逐句翻译。它们可以帮助寻找当地语言的父母资料，不能视为儿童多语言培养课程。`index.html` 是静态资源展示页，未实现成长记录。

**边界：**没有统一年龄标签、证据评级或所有外链的复核日期；课程是否仍开放、收费和内容版本，本次未逐一核验。被收录的测验也不能自动当成发育筛查或心理诊断工具。仓库自身为 [MIT](thrid_party/awesome-parenting/LICENSE)，外链作品的权利仍属于各自权利人。

### 7. HowToLiveBetter：办事与安全专题的补充

**定位：**综合生活指南，本项目只取与孕产和养育相关的入口。比多数个人笔记更强调条目出处和核实过程，但不等于完成了独立临床审查。

| 精确入口 | 与当前资料库的关系 |
| --- | --- |
| [孩子出生前后要办的事](thrid_party/HowToLiveBetter/docs/孩子出生前后要办的事.md) | 备孕、孕期、生产、出院、首月和满月后到一岁的时间顺序入口 |
| [第 27 节：怀孕和生产](thrid_party/HowToLiveBetter/book/27-怀孕和生产.md) | 产检、安全信号、分娩、出生证明、参保与登记等主题 |
| [第 20 节：刚出生的孩子怎么带](thrid_party/HowToLiveBetter/book/20-刚出生的孩子怎么带.md) | 安全睡眠、喂养、疫苗、筛查、黄疸及家庭照护风险 |
| [第 18 节：养孩子划不划算](thrid_party/HowToLiveBetter/book/18-养孩子划不划算.md) | 家庭成本、假期和待遇的查证入口；具体政策必须另核 |
| [第 30 节：上学以后的孩子](thrid_party/HowToLiveBetter/book/30-上学以后的孩子.md) | 眼口健康、欺凌、情绪、学校与家庭保护、运动安全等 |
| [核实记录](thrid_party/HowToLiveBetter/docs/核实记录/) / [引用对照](thrid_party/HowToLiveBetter/docs/引用对照.md) | 从摘要回到条目、再追到原始来源的路径 |

每条通常有成本、通俗解释、收益、证据等级、来源与备注，适合借鉴“行动—理由—适用人群—出处”的写法。时间清单通过节号回指正文，不宜只复制短句，否则会丢失限定条件。

**理解重点：**作者自定义 A/B/C，其中 A 包含随机试验、队列、荟萃分析以及政策原文；同一字母不代表相同研究设计、因果强度或推荐等级。作者也区分“证据等级”和自己的性价比判断。办事、补贴、接种与医疗条目都要保留地区和版本，不能因为最新有提交就默认当下通用。

它能补充 3–18 岁的健康安全，但没有系统的阅读、数学、音乐、运动或多语言课程。正文许可为 [CC BY 4.0](thrid_party/HowToLiveBetter/LICENSE)，代码为 [MIT](thrid_party/HowToLiveBetter/LICENSE-CODE)，采用或改写正文时需保留署名、来源、许可与修改说明。

## 按阶段与目标检索

下表评价的是本地材料可用性，不是医学证据等级，也不表示列出项目后该阶段就已完整。

| 阶段 | 优先检索项目 | 已有材料 | 仍明显缺少 |
| --- | --- | --- | --- |
| 备孕与孕期 | Pregnancy-Knowledge、learn-pregnancy；BloomTalk 看流程 | 主题笔记、孕周课程、档案、沟通与陪伴计划模板 | 针对所在地的核验版检查安排与逐条安全审校 |
| 分娩与产后 | learn-pregnancy、HowToLiveBetter、Pregnancy-Knowledge | 分娩学习、恢复关注点、出生前后办事目录 | 结合医院流程、家庭条件与医生建议的安排 |
| 0–1 岁 | LittleSteps、Pregnancy-Knowledge、HowToLiveBetter | 喂养、睡眠、安全、记录、里程碑和护理主题 | 本地适用的接种与保健安排、内容冲突处理 |
| 1–3 岁 | LittleSteps、hands-on-dad | 幼儿条目、月龄入口、资源导航 | 经核验的互动活动规格和分龄筛查路径 |
| 3–6 岁 | hands-on-dad、awesome-parenting | 绘本、童谣、家庭活动、教育理念入口 | 连贯且不施加能力达标压力的家庭活动库 |
| 6–12 岁 | hands-on-dad、HowToLiveBetter、awesome-parenting | 学习资源、STEAM、沟通和健康安全主题 | 分龄阅读、数学、运动与兴趣发展的完整方案 |
| 12–18 岁 | hands-on-dad、HowToLiveBetter | 青春期书目、学校与心理健康安全主题 | 深入的青春期沟通、独立生活与生涯探索材料 |

| 关注目标 | 推荐检索入口 | 能得到什么 / 不能推出什么 |
| --- | --- | --- |
| 多语言语感 | hands-on-dad 的语言、儿歌和绘本；awesome-parenting 地区化资源 | 得到素材线索；不能推出胎儿外语训练收益或统一语言窗口 |
| 音乐与乐感 | BloomTalk 的 music；hands-on-dad 的音乐与童谣 | 得到陪伴和音乐资源；缺少完整的逐龄乐感课程及效果评估 |
| 表达与沟通 | hands-on-dad 的故事与情感教育；awesome-parenting 的书籍和课程 | 得到亲子互动和沟通方法线索；需要再核适龄性和活动步骤 |
| 肢体协调与运动 | LittleSteps 里程碑；hands-on-dad 发育与活动入口 | 得到观察和游戏选题；里程碑不是训练指标或诊断 |
| 胎教与家庭陪伴 | BloomTalk 的计划/反馈；已有本地 HTML | 得到组织方式；分类、打卡和研究中的胎儿反应都不等于长期能力收益 |

现有的 [孕期陪伴与胎教计划](<0b.孕期陪伴与胎教方法.html>)、[分阶段甘特执行计划](0c.孕期陪伴与胎教执行计划.html) 已于2026-11-01修订至2.2版。仓库内容用于发现选题与冲突，医学说明回查外部原始来源；没有将第三方默认计划直接套给所有孕妇或特定临床人群。

## 证据和内容质量

这里区分三个问题：文件是否存在，来源能否追溯，建议是否适用于当前家庭。此次完成第一项及部分第二项，未进行全量医学逐条审校。以下是**抽查已发现的问题**，不是对所有内容的完整审计。

| 本地位置 | 发现的问题 | 导入行动指南之前的处理 |
| --- | --- | --- |
| Pregnancy-Knowledge / 0–5 岁宝典 / 母乳维生素段 | 维生素 D 剂量单位存在异常 | 标记待复核，不生成补充剂用量提醒，不在此复述为家庭剂量 |
| Pregnancy-Knowledge / 孕期知识 / 常用药表 | 按“安全、谨慎、避免”粗分，缺少逐药适应证、孕周和版本 | 把主题作为咨询线索，不能整表采信 |
| [learn-pregnancy L04](thrid_party/learn-pregnancy/docs/L04-孕期安全守则——饮食禁忌与用药.md) | 将肉类熟度和盒装鸡蛋处理作宽泛概括 | 按食材实际处理和安全烹调标准重核；包装不等于已巴氏消毒 |
| learn-pregnancy L04 与用药题库 | 布洛芬等风险按宽泛孕早中晚阶段归纳 | 对照 FDA 关于约孕 20 周起 NSAIDs 风险的说明，不能把“中期”当成自行用药许可 |
| hands-on-dad / 语言与教育理论书介 | 绝对化语言学习窗口及教育方法优劣宣传 | 保留为书介，不标为科学共识 |
| BloomTalk / 知识分级 | 自定义 A–D，未形成完整逐条参考链 | 保存原分级文字，不换算成临床证据级别 |
| LittleSteps / 地区数据与雷达 | 地区不同，且数据快照早于仓库最新提交 | 保存适用地区、数据覆盖期和核查日期 |
| HowToLiveBetter / A–C | 混合研究与政策来源，自定义标准 | 保留研究设计、人群与限定条件，不把 A 等同于已证明因果 |

两项安全复核使用了官方原文：[FoodSafety.gov 孕期食品安全](https://www.foodsafety.gov/people-at-risk/pregnant-women)要求避免未熟肉禽，并按安全内部温度判断；[FDA NSAIDs 孕期安全通告](https://www.fda.gov/drugs/drug-safety-and-availability/fda-recommends-avoiding-use-nsaids-pregnancy-20-weeks-or-later-because-they-can-result-low-amniotic)说明约孕 20 周起的风险及医嘱下的特殊情形。本 README 只说明原资料为什么需要复核，不提供用药方案。

胎教方面，[2023 年声音刺激系统综述](https://link.springer.com/article/10.1186/s12887-023-03990-7)纳入 8 项研究，结果主要涉及新生儿期的刺激特异性记忆和反应，研究方案差异和偏倚限制推断。因此，这篇综述不能被用来证明特定音乐、胎儿外语训练能提高未来智商或长期学业能力，也不应把研究刺激方案直接改成家庭训练剂量。

后续条目建议分别标记：`官方现行建议已核验`、`研究原文已阅读`、`仅有二手总结`、`作者经验/推荐`、`待核验`。这是工作状态，不是自行建立另一套医学分级。

## 本地检索方法

以下命令在本项目根目录执行。只检索内容时排除锁文件和测试文件，可减少技术噪音；需要研究实现时再加入它们。

```bash
# 先定位知识与数据文件
rg --files thrid_party -g '*.md' -g '*.ts' -g '*.tsx' -g '*.json' \
  -g '!package-lock.json' -g '!*.test.*' -g '!*.spec.*'

# 跨项目查某个主题（这里以胎动和筛查为例）
rg -n '胎动|胎動|唐筛|唐篩|NIPT|OGTT' thrid_party \
  -g '*.md' -g '*.ts' -g '!*.test.*'

# 中英文、多种中文写法一起搜，减少漏项
rg -ni '绘本|繪本|亲子阅读|親子閱讀|语言|語言|bilingual|reading|language' \
  thrid_party/hands-on-dad thrid_party/awesome-parenting \
  thrid_party/LittleSteps/src -g '*.md' -g '*.ts' -g '!*.test.*'

# 找来源、核查时间与证据，而不只看结论
rg -ni '来源|來源|参考|參考|doi.org|pubmed|verifiedOn|source|reviewed' \
  thrid_party/BloomTalk/bloom-talk-kb \
  thrid_party/LittleSteps/src/common/about \
  thrid_party/HowToLiveBetter/book -g '*.md' -g '*.ts'

# 看指定仓库版本和是否有本地改动
git -C thrid_party/Pregnancy-Knowledge log -1 --format='%H %cI %s'
git -C thrid_party/Pregnancy-Knowledge status --short
```

`rg` 不解析 PDF 或图片文字；上述命令不会检索两个 PDF 的正文，也不能读取图片中的表格。`hands-on-dad` 和 `awesome-parenting` 命中的多数是链接及简介，要获取详细知识仍需阅读外部来源。外链全面可访问性本次未验证。

## 后续整理的结构

目录与阶段编号按[命名规范](docs/architecture.md)执行。内容组织以“阶段 × 主题 × 行动”为主索引，保留仓库和提交作为来源信息，避免按仓库重复堆放相似段落。以下是后续建议，本次没有创建完整知识体系或应用。

| 层次 | 组织方式 | 当前来源 |
| --- | --- | --- |
| 原始资料 | 保留上游文件与版本，不直接修改 | `thrid_party/` |
| 主题知识 | 一条主题合并多仓库线索，另存分歧与待核项 | 孕产笔记、课程、Wiki、导航 |
| 家庭行动 | 清楚写明何时做、谁负责、为何做、何时停止/咨询、来源何时核验 | 档案模板、陪伴流程、办事清单 |
| 实际记录 | 记录家人感受、完成情况和医生意见，区别于通用知识 | BloomTalk 闭环与 LittleSteps 记录模型 |

一条候选行动至少保存：

```text
主题 / 阶段或适龄范围 / 目标
建议行动 / 执行人 / 频率与停止条件（若有已核验依据）
适用地区与特殊情况 / 是否需要医生或专业人员确认
原始来源 URL / 仓库路径 / 提交 SHA / 核验日期
证据追溯状态 / 已知争议 / 与其他来源的冲突
```

先整理孕期与出生后一年，再扩展 1–3 岁和更大年龄；语言、音乐、表达及协调单独保留长期主题。对资源导航先建立候选资源表，对医学条目先查证，对计划模板先提取字段，三类材料采用不同处理方式。

## 同步与许可

本项目已初始化为Git仓库，远端为[LeoCeasar/dad-on-the-way](https://github.com/LeoCeasar/dad-on-the-way)，主分支为`main`。7个第三方项目使用Git子模块固定到核验提交，`.gitmodules`保存上游地址，`thrid_party/sources.lock.json`保存核验元数据。主仓库不复制这些项目的全部文件。

首次获取完整资料：

```bash
git clone --recurse-submodules https://github.com/LeoCeasar/dad-on-the-way.git
cd dad-on-the-way
```

如果已克隆主仓库，再运行`git submodule update --init --recursive`。仅下载主仓库ZIP不会包含第三方子模块正文；3份公开HTML本身仍可离线阅读。当前不启用GitHub Pages。

需要更新某个仓库时，先查看本地修改，再获取远端变化和差异，最后快进更新：

```bash
git -C thrid_party/BloomTalk status --short
git -C thrid_party/BloomTalk fetch --depth 1 origin
git -C thrid_party/BloomTalk diff HEAD..origin/main --stat
git -C thrid_party/BloomTalk merge --ff-only origin/main
```

这是单仓库更新示例：若有本地修改应先处理；LittleSteps 和 awesome-parenting 当前默认分支为 `master`，其余为 `main`。需要完整历史可使用 `git fetch --unshallow`。更新之后应重新检查差异，刷新 `sources.lock.json` 和本 README 的相关结论，并在主仓库提交对应子模块的新提交指针；单纯 `pull` 不会更新分析记录。

| 仓库 | 实际许可观察 |
| --- | --- |
| Pregnancy-Knowledge | 根目录 GPL v3 LICENSE |
| hands-on-dad | 未发现许可证文件 |
| learn-pregnancy | 根目录 MIT LICENSE；衍生内容来源许可仍需保留 |
| BloomTalk | 根目录 MIT LICENSE |
| LittleSteps | README 声称 MIT，但未发现独立 LICENSE/COPYING 文件 |
| awesome-parenting | 根目录 MIT LICENSE；不覆盖外链书籍、课程与其他作品 |
| HowToLiveBetter | 正文 CC BY 4.0，代码 MIT，范围由上游 README 说明 |

这里汇总的是文件和上游声明，不是对全部第三方素材权利的审计。资料复制进新文档时保留出处、原许可和修改说明；本地镜像便于检索，不意味着可以把外链书籍、课程、图片或 PDF 全部重新发布。
