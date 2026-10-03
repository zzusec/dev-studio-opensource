# Product

## Register

brand

## Users

开发者同行。他们带着具体目标而来：判断这些开源项目的代码质量、维护活跃度、能否被复用；顺带了解作者的技术品味与工作节奏。他们会跳过形容词、直接看仓库、看提交、看 issue 反应速度。他们不需要被推销，需要被认真对待。

## Product Purpose

一个个人开源作品集站点。承载两类信息：（1）作者正在维护的开源项目，包括每个项目做什么、用什么语言、状态如何；（2）作者的写作与思考方式，通过短小的项目描述、当前的兴趣方向、和维护哲学体现出来。成功标准：一位开发者在 30 秒内能判断"这个人的作品值得点开 GitHub 看看"，并且感受到作者的严谨与品味。

## Brand Personality

**冷静 / 具体 / 有物质感**。像一份 1970 年代的仪器维修手册（Tektronix、Fluke、HP），不像产品发布页。信息密度高、装饰低、每个数字都有出处、排版有工程上的克制。不喊口号，不写"赋能/极致/优雅"。用词直接，允许一点干燥的技术幽默。

## Anti-references

- **不要 GitHub Dark / 通用开发者作品集**：黑紫渐变 hero、大字号 clamp 到 8rem、每个 section 上面顶一个 all-caps eyebrow、彩色圆角小图标 + 卡片网格 + 星标数字堆。用户明确排除这个方向。
- **不要 SaaS landing page**：三行 hero + "Get started / Book demo" 双按钮 + Feature grid + Testimonials + Pricing + Footer。
- **不要编辑排版风**：display serif 斜体大标题 + 分隔横线 + 小字 mono 标签的杂志化布局，这是 2026 年"避开 SaaS cream"之后的第二层陷阱。
- **不要 cream / sand / beige 米色底**。
- **不要 Fraunces / Newsreader / Inter / Space Grotesk / IBM Plex / Syne / Outfit 等训练数据默认字体**。

## Design Principles

1. **Show the work, don't advertise the work.** 首页就是项目本身：项目名、做什么、什么状态、什么语言、什么版本。不需要 hero 段落再解释"我做的都是好工具"。
2. **Structure over decoration.** 布局信息用文档式排印（编号、右侧对齐元数据、细分隔线）而不是卡片、圆角、彩色块。任何非信息性装饰都要问一句"这告诉读者什么"，答不上就删。
3. **One committed color, not a rainbow.** 单一强调色（信号橙）用于状态、链接与关键元数据；其余全部走中性灰阶。语言/项目/分类不再各分配一个色。
4. **Type carries the identity, not imagery.** 不用插画、不用 stock photo、不用 SVG 手绘场景。字体（General Sans + Departure Mono 双家族）+ 排印节奏 + 空格结构本身就是设计。
5. **Everything a real developer might ask is one click away.** 每个项目直接链到仓库；作者联系入口在明显位置；不藏起来让人找。

## Accessibility & Inclusion

WCAG 2.1 AA。深色底 + 主文字对比度 ≥ 7:1，弱化文字对比度 ≥ 4.5:1。全键盘可达、focus-visible 状态清晰、语义化 HTML（nav / main / section / article / h1 序）。所有动效响应 `prefers-reduced-motion`。移动端 320px 起可读、无水平溢出。
