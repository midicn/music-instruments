---
id: recorder
site: inst
cat: I2
title: 竖笛
title_en: Recorder
summary: 靠哨嘴固定通道发声的古老木管，巴洛克的标准独奏乐器
summary_en: The old duct flute whose air is shaped by a fixed channel — the Baroque's standard solo wind
level: standard
tags: [乐器, 木管, 西洋, 早期乐器]
tags_en: [instrument, woodwind, western, early]
alias: [竖笛, recorder, 直笛, 木笛, flauto dolce, blockflöte]
order: 39
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:flute]]"
  - "[[instrument:ocarina]]"
  - "[[instrument:pan-flute]]"
instances:
  - pdmx-002065 | 为竖笛与长笛而作的协奏曲 —— 竖笛与长笛同台，音色差别一耳可辨
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— 高音竖笛与钢琴的巴洛克奏鸣曲
  - pdmx-000322 | 鲁特琴与竖笛的协奏曲 —— 早期组合中的一个典型搭配
  - giantmidi-000507 | C 小调竖笛协奏曲 —— 独奏协奏曲式的写法
sources:
  - 结构依通行制琴资料：木质（或树脂）管身，分族成套，带**哨嘴（风道）**，指孔无键（或极少键）；中音竖笛全长约 48 厘米
  - 「竖笛为 C 调或 F 调乐器，记谱即实音，不移调」依通行配器资料
  - 「中音竖笛（F 调）音域约 F4–G6」依通行配器资料
  - 「气流由哨嘴的固定通道导向棱边发声 —— 属边棱音，但激振方式与长笛不同」依 Hornbostel–Sachs 分类与管乐器声学
  - 「竖笛在巴洛克时期是标准独奏乐器，18 世纪后衰落，20 世纪由古乐运动与音乐教育复兴」依乐器史
updated: 2026-09-26
---

::: zh
竖笛是木管里最古老、也最容易被低估的一件。它和[[instrument:flute|长笛]]**同属边棱音**，
但**激振方式完全不同**：长笛靠演奏者用嘴唇把气流"送"到吹口边缘，
竖笛则在管头做了一条**固定的风道（哨嘴）**，气流被它自动引向棱边。

这个差别决定了竖笛的全部特点：**发音太容易，可塑性却受限。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· 边棱音（哨嘴 / 风道驱动） |
| **次级类型** | 竖吹 · 无簧片 · **哨嘴风道** · 指孔，基本无键 |
| **所属族** | 西洋 · 木管（哨嘴族）· 也是早期乐器 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，竖笛不在其中 |

> ⚠️ **一个概念上的要点**：**"边棱音"不是一种乐器，而是一类激振方式。**
> [[instrument:flute|长笛]]和竖笛都靠"气流切过棱边"发声，但气流的形成方式不同：
> 长笛由**嘴唇**塑造（可塑性强、难度高），竖笛由**哨嘴的固定通道**塑造（稳定、易响）。
> 所以两者音色的可控范围差别很大 —— **同一个声学原理，两种人机接口。**

## 结构：哨嘴是一条固定风道

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="竖笛外形与主要部件：顶端的哨嘴与风道、棱边、管身与指孔、外张的喇叭口">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">中音竖笛 · 外形与主要部件（哨嘴风道 + 无键指孔）</text>
  </g>
  <rect x="306" y="42" width="28" height="30" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M308,74 C306,96 304,106 302,118" fill="none" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <rect x="298" y="46" width="44" height="6" rx="2" fill="#E8C547"/>
  <path d="M300,120 L340,120 L350,318 L290,318 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M290,318 L350,318 L360,348 L280,348 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M280,348 L360,348" stroke="#9C7A3C" stroke-width="3"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.3">
    <circle cx="320" cy="152" r="5.6"/><circle cx="320" cy="182" r="5.6"/>
    <circle cx="320" cy="212" r="5.6"/><circle cx="320" cy="242" r="5.6"/>
    <circle cx="312" cy="272" r="5.2"/><circle cx="330" cy="272" r="5.2"/>
  </g>
  <g fill="#070706" stroke="#343439" stroke-width="1.1">
    <circle cx="320" cy="300" r="4.6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,58 L300,58"/><path d="M186,110 L292,110"/>
    <path d="M186,182 L306,182"/><path d="M186,344 L274,344"/>
    <path d="M486,150 L336,152"/><path d="M486,272 L342,272"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="61" text-anchor="end">哨嘴（风道入口）</text>
    <text x="180" y="113" text-anchor="end" fill="#E8C547">棱边（气流在此被切开）</text>
    <text x="180" y="185" text-anchor="end">管身（木质或树脂）</text>
    <text x="180" y="347" text-anchor="end">喇叭口略外张</text>
    <text x="492" y="153">指孔（无键）</text>
    <text x="492" y="275">底部两孔由小指控制</text>
  </g>
  <text x="20" y="366" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">哨嘴里的黄色通道把气流固定地导向棱边 —— 演奏者不需要"找角度"，所以竖笛几乎是所有木管里最容易吹响的一件。</text>
</svg>
```

三处要点：

1. **哨嘴 = 一条做在管头里的固定风道**。气流从吹口进入、经风道、撞上棱边，
   一分为二 —— 与长笛的物理过程相同，但**不需要演奏者控制方向**。
2. **基本没有键**。指孔直接用手按/半按，高音靠**半孔**与**叉指（forked fingering）**得到。
   所以竖笛的指法比现代木管"老派"得多。
3. **它是成套的家族乐器**。同一形制做成不同大小（见下节），而不是像萨克斯那样"一族几支各有分工"。

## 哨嘴与嘴唇：两种边棱音

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="竖笛与长笛的激振方式对比：竖笛由哨嘴风道固定导流，长笛由嘴唇直接控制气流">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一个声学原理，两种"人机接口"</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">竖笛 · 哨嘴固定导流</text>
  <rect x="60" y="86" width="200" height="26" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="86" y="86" width="96" height="7" rx="2" fill="#E8C547"/>
  <path d="M182,74 L182,114" stroke="#E07A3F" stroke-width="3.2" stroke-linecap="round"/>
  <path d="M60,74 L60,124" stroke="#5B7FA8" stroke-width="3"/>
  <text x="160" y="146" text-anchor="middle" font-size="10.5" fill="#A9A49B">气流路径由管的形状决定</text>
  <text x="160" y="170" text-anchor="middle" font-size="10.5" fill="#5B7FA8">发音容易 · 音色可调范围小</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">长笛 · 嘴唇直接控制</text>
  <rect x="380" y="86" width="200" height="26" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="440" y="86" width="44" height="12" fill="#070706" stroke="#5B7FA8" stroke-width="1.4"/>
  <path d="M484,84 L484,100" stroke="#E07A3F" stroke-width="3.2" stroke-linecap="round"/>
  <path d="M410,56 C440,70 468,80 480,88" fill="none" stroke="#E07A3F" stroke-width="2.2" stroke-linecap="round"/>
  <path d="M474,79 L484,88 L472,90 Z" fill="#E07A3F"/>
  <text x="480" y="146" text-anchor="middle" font-size="10.5" fill="#A9A49B">气流角度由演奏者控制</text>
  <text x="480" y="170" text-anchor="middle" font-size="10.5" fill="#9C7A3C">发音较难 · 音色可调范围大</text>
  <text x="20" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">这就是为什么竖笛"一吹就响"，而长笛要练很久才吹得出声音 —— 也是为什么长笛能做出</text>
  <text x="20" y="238" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">气声、花舌、大幅音量变化，而竖笛在这几项上天生受限。</text>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">同一个物理原理，取舍完全相反：<tspan font-weight="bold">一边要容易，一边要自由。</tspan></text>
</svg>
```

**这条取舍关系值得记住**：把气流交给固定风道，就换来极低的入门门槛，
代价是放弃对音色的深度控制。**这正是竖笛既是"儿童乐器"又是"古乐重器"的原因** ——
它的价值不在表情的广度，而在音色的**透明与均匀**。

## 音域

```range
{"range":"F4–G6","common":"F4–D6","caption":"中音竖笛的音域","caption_en":"Alto recorder range","note":"竖笛是成套的家族乐器，这里以巴洛克独奏文献最常用的中音竖笛（F 调）为例。记谱即实音，不移调。上方两个音（E6、G6）需要半孔与叉指。"}
```

**它是为什么"成套"的**：同一形制按比例做成不同大小，就得到一整个家族 ——
指法逻辑一致，音高不同，可以合奏。

| 型号 | 调 | 实音音域 | 常用处 |
|---|---|---|---|
| 小超高音（garklein） | C | 约 C6–C8 | 罕见，音极高 |
| 超高音（sopranino） | F | 约 F5–G7 | 巴洛克高音声部 |
| **高音（descant / soprano）** | C | 约 C5–D7 | 学校与初学者最常用 |
| **中音（treble / alto）** | F | 约 F4–G6 | **巴洛克独奏文献的主力** |
| 次中音（tenor） | C | 约 C4–D6 | 合奏的内声部 |
| 低音（bass） | F | 约 F3–G5 | 合奏的低音 |

**注意"同一份指法"这件事**：竖笛族的指法**跨型号通用**（因为都是同一套孔位比例），
所以演奏者可以像萨克斯族那样换型号 —— 但它们的**记谱都是实音**，不含移调。

## 音色与听辨

四条线索：

1. **清亮、直朴、泛音少**。它的音色里没有簧片的"芯"，也没有长笛那种丰富的气声层次 ——
   是一种**接近纯音的干净**。
2. **音量大而均匀**。它可以在整个音域里保持相近的音量，这让它在合奏里很好用。
3. **高音区偏尖**。上到高音区时音色会变薄、变紧，需要半孔与叉指。
4. **可调范围小**。它做不出大幅度的音量与音色变化 —— 这是固定风道带来的天花板。

```audiolab
{"type":"instrument","gm":"Recorder","synth":"blown","phrase":["F4","A4","C5","F5","A5","C6"],"label":"中音竖笛的常用区：F4 到 C6","label_en":"The alto recorder's working register — F4 up to C6","hint":"注意音色的透明与均匀 —— 这是哨嘴驱动的特点，也是它最被低估的地方","hint_en":"Hear the transparency and evenness — the mark of duct drive, and its most underrated quality."}
```

## 演奏技法

- **半孔（half-hole）**：按住某个孔的一半来得到半音 —— 竖笛没有键系，半音主要靠它。
- **叉指（forked fingering）**：中间漏一个孔，得到高音区的一些音 —— 音色会略闷，
  这是竖笛演奏者必须学会弥补的地方。
- **音头靠舌头**（吐音，tonguing）。因为没有键系、气流固定，**吐音是它最主要的发音控制手段**。
- **装饰音**：巴洛克竖笛音乐的装饰音极多，演奏者要按当时的惯例即兴加花 ——
  这在现代演奏里仍然保留。

## 家族与近亲

| 乐器 | 驱动 | 管 / 腔 | 键系 | 特色 |
|---|---|---|---|---|
| **竖笛** | 哨嘴风道 | 管身，指孔 | 基本无键 | 成套家族；巴洛克独奏主力 |
| [[instrument:flute\|长笛]] | 嘴唇 | 圆柱管 | 完整键系 | 可塑性强、难度高 |
| [[instrument:ocarina\|陶笛]] | 哨嘴风道 | **闭腔** | 无键 | 音高由开孔面积决定 |
| [[instrument:pan-flute\|排箫]] | 嘴唇 | 多根**闭管** | 无键 | 每管一音 —— 世界性的乐器 |

**三件"哨嘴 / 无簧"乐器放在一起看**，会发现它们都在做同一件事：
**用最简单的方式得到一个稳定的音**。它们的代价也一样：**可塑性低**。

## 历史演变

| 时期 | 状态 |
|---|---|
| 中世纪 | 欧洲已有简单的管形哨嘴乐器；竖笛的形制逐步成型 |
| 文艺复兴 | 成套制作（不同大小合奏）成为惯常做法；大量合奏音乐为它而写 |
| **巴洛克** | **鼎盛期**：成为标准独奏乐器，大量奏鸣曲与协奏曲专为它而写；音域与指法体系完备 |
| 18 世纪中叶起 | 被[[instrument:flute\|长笛]]（音量大、可塑性强）取代，逐渐退出专业演奏 |
| 20 世纪 | **复兴**：古乐运动把它重新带回舞台；同时成为欧美音乐教育中最常见的入门乐器 |
| 20 世纪后期至今 | 古乐演奏与当代作品两条线并行；也出现了扩音域与超吹等扩展技法 |

## 常见误解

- **"竖笛是玩具，不是正经乐器。"** 它在**巴洛克时期是标准独奏乐器**，
  有大量专为它写的奏鸣曲与协奏曲。20 世纪把它当儿童入门乐器，只是它历史的一段。
- **"竖笛与长笛是同一种乐器。"** 同属边棱音，但**激振方式不同**：
  哨嘴固定风道 vs 嘴唇直接控制 —— 这决定了它们音色可塑性上的巨大差别。
- **"竖笛是移调乐器，和萨克斯一样。"** **记谱即实音**，不移调。
  换型号会换音高，但谱面永远写实音。
- **"竖笛只有一个型号。"** 它是**成套的家族**（从小超高音到低音），
  指法逻辑跨型号通用，是文艺复兴与巴洛克合奏音乐的常用编制。
- **"吹得越用力越好。"** 竖笛的响应太灵敏，用力过猛会直接"跳"到高泛音 ——
  控制音量靠气流的**稳**，不是靠气流的**多**。

## 下一步

木管这条线的最后两条是它的近亲：
[[instrument:ocarina|陶笛]]（闭腔、音高由开孔面积决定）与
[[instrument:pan-flute|排箫]]（多根闭管，每管一音）。

这三件放在一起，就把"无簧木管"这条最古老的支线讲完了。之后木管组正式收口 ——
想看木管与铜管的交界，就要进入铜管组；想看它与弦乐的关系，
[[instrument:flute|长笛]]那一页里有最直接的对照。
:::

::: en
The recorder is the oldest and most underrated of the woodwinds. It is an **edge-tone** instrument like
the [[instrument:flute|flute]], but its **drive is entirely different**: a flute player shapes the jet with
the lips, while a recorder has a **fixed channel (the duct) built into the head** that steers the air at the
edge for you.

That single difference decides everything about it: **very easy to sound, limited in colour.**

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · edge-tone (duct / fipple drive) |
| **Sub-type** | Vertical · reedless · **duct head** · finger holes, essentially keyless |
| **Family** | Western · Woodwinds (duct family) · also an early instrument |
| **Bayin** | Not applicable — a Chinese system; the recorder is outside it |

> ⚠️ **One conceptual point**: **"edge-tone" is not an instrument but a way of driving one.**
> The [[instrument:flute|flute]] and the recorder both sound by having a jet cut against an edge, but the
> jet is formed differently: on a flute by the **lips** (highly controllable, hard to learn), on a recorder
> by a **fixed duct** (stable, easy to sound). So the two differ enormously in how far their colour can be
> shaped — **one acoustic principle, two interfaces.**

## Structure: the duct is a fixed channel

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Recorder parts: the duct head at the top, the edge, the body with finger holes, and a slightly flaring bell">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Alto recorder — outer form and principal parts (duct head, keyless holes)</text>
  </g>
  <rect x="306" y="42" width="28" height="30" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M308,74 C306,96 304,106 302,118" fill="none" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <rect x="298" y="46" width="44" height="6" rx="2" fill="#E8C547"/>
  <path d="M300,120 L340,120 L350,318 L290,318 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M290,318 L350,318 L360,348 L280,348 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M280,348 L360,348" stroke="#9C7A3C" stroke-width="3"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.3">
    <circle cx="320" cy="152" r="5.6"/><circle cx="320" cy="182" r="5.6"/>
    <circle cx="320" cy="212" r="5.6"/><circle cx="320" cy="242" r="5.6"/>
    <circle cx="312" cy="272" r="5.2"/><circle cx="330" cy="272" r="5.2"/>
  </g>
  <g fill="#070706" stroke="#343439" stroke-width="1.1">
    <circle cx="320" cy="300" r="4.6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,58 L300,58"/><path d="M186,110 L292,110"/>
    <path d="M186,182 L306,182"/><path d="M186,344 L274,344"/>
    <path d="M486,150 L336,152"/><path d="M486,272 L342,272"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="61" text-anchor="end">Duct head (air inlet)</text>
    <text x="180" y="113" text-anchor="end" fill="#E8C547">Edge (the jet is cut here)</text>
    <text x="180" y="185" text-anchor="end">Body (wood or resin)</text>
    <text x="180" y="347" text-anchor="end">Slightly flaring bell</text>
    <text x="492" y="153">Finger holes (no keys)</text>
    <text x="492" y="275">Two holes, little finger</text>
  </g>
  <text x="20" y="366" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The yellow channel steers the air at the edge by itself — no angle to find, hence the easiest wind to sound.</text>
</svg>
```

Three points:

1. **The duct is a channel built into the head.** Air enters the mouthpiece, travels the duct, strikes the
   edge and splits — physically the same as a flute, but **the player does not steer it**.
2. **Essentially keyless.** Holes are covered directly, half-covered, or forked to reach the top register,
   so the fingering is far more "period" than a modern woodwind's.
3. **It is a consort family**, not a set of specialists: one design in many sizes (next section).

## Duct and lips: two kinds of edge-tone

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Recorder and flute compared by excitation: the recorder's duct steers the air, the flute player's lips do">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One acoustic principle, two interfaces</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Recorder · the duct steers the air</text>
  <rect x="60" y="86" width="200" height="26" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="86" y="86" width="96" height="7" rx="2" fill="#E8C547"/>
  <path d="M182,74 L182,114" stroke="#E07A3F" stroke-width="3.2" stroke-linecap="round"/>
  <path d="M60,74 L60,124" stroke="#5B7FA8" stroke-width="3"/>
  <text x="160" y="146" text-anchor="middle" font-size="10.5" fill="#A9A49B">The tube decides the air path</text>
  <text x="160" y="170" text-anchor="middle" font-size="10.5" fill="#5B7FA8">easy to sound · narrow colour range</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Flute · the lips steer the air</text>
  <rect x="380" y="86" width="200" height="26" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="440" y="86" width="44" height="12" fill="#070706" stroke="#5B7FA8" stroke-width="1.4"/>
  <path d="M484,84 L484,100" stroke="#E07A3F" stroke-width="3.2" stroke-linecap="round"/>
  <path d="M410,56 C440,70 468,80 480,88" fill="none" stroke="#E07A3F" stroke-width="2.2" stroke-linecap="round"/>
  <path d="M474,79 L484,88 L472,90 Z" fill="#E07A3F"/>
  <text x="480" y="146" text-anchor="middle" font-size="10.5" fill="#A9A49B">The player sets the angle</text>
  <text x="480" y="170" text-anchor="middle" font-size="10.5" fill="#9C7A3C">harder to sound · wide colour range</text>
  <text x="20" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">That is why a recorder sounds at once and a flute takes months — and why a flute can produce</text>
  <text x="20" y="238" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">air sound, flutter tongue and huge dynamic swells that a recorder simply cannot.</text>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The same physics, opposite trade-offs: ease on one side, freedom on the other.</text>
</svg>
```

**This trade-off is worth remembering**: hand the jet to a fixed duct and you buy an extremely low entry
barrier at the cost of deep colour control. **That is exactly why the recorder is both a school instrument
and a serious early-music instrument** — its value is not breadth of expression but the **transparency and
evenness** of its tone.

## Range

```range
{"range":"F4–G6","common":"F4–D6","caption":"中音竖笛的音域","caption_en":"Alto recorder range","note":"竖笛是成套的家族乐器，这里以巴洛克独奏文献最常用的中音竖笛（F 调）为例。记谱即实音，不移调。上方两个音（E6、G6）需要半孔与叉指。"}
```

**Why it comes "in sets"**: the same design scaled to different sizes gives a whole consort — consistent
fingering logic, different pitches, able to play together.

| Size | Key | Sounding range | Usual role |
|---|---|---|---|
| Garklein | C | about C6–C8 | rare, extremely high |
| Sopranino | F | about F5–G7 | Baroque top line |
| **Descant / soprano** | C | about C5–D7 | schools and beginners |
| **Treble / alto** | F | about F4–G6 | **the Baroque solo workhorse** |
| Tenor | C | about C4–D6 | inner parts of a consort |
| Bass | F | about F3–G5 | the consort's low voice |

**Note the shared fingering**: the logic transfers across sizes (the holes are proportional), so a player
can switch like a saxophonist — except that **every recorder is written at sounding pitch**, with no
transposition at all.

## Timbre, and how to hear it

Four cues:

1. **Clear, plain, few harmonics.** No reed core and none of the flute's layered breath — a tone close to a
   pure sound.
2. **Loud and even.** It holds a similar volume across its range, which makes it very usable in a consort.
3. **Thin and tight at the top**, where half-holes and forked fingerings are needed.
4. **A narrow expressive range** — the ceiling imposed by a fixed duct.

```audiolab
{"type":"instrument","gm":"Recorder","synth":"blown","phrase":["F4","A4","C5","F5","A5","C6"],"label":"中音竖笛的常用区：F4 到 C6","label_en":"The alto recorder's working register — F4 up to C6","hint":"注意音色的透明与均匀 —— 这是哨嘴驱动的特点，也是它最被低估的地方","hint_en":"Hear the transparency and evenness — the mark of duct drive, and its most underrated quality."}
```

## Playing techniques

- **Half-hole**: covering half of a hole to get a semitone — with no keys, this is the main way.
- **Forked fingering**: leaving a middle hole open for some top notes — the tone turns duller, and closing
  that gap is part of the player's craft.
- **Tonguing is the main articulation**, since there is no keywork and the air path is fixed.
- **Ornamentation**: Baroque recorder music is thick with ornaments, and players were expected to add them
  from convention — a practice still kept in performance.

## The family

| Instrument | Drive | Tube / cavity | Keywork | Distinction |
|---|---|---|---|---|
| **Recorder** | duct head | tube, finger holes | essentially none | a consort family; Baroque solo workhorse |
| [[instrument:flute\|Flute]] | lips | cylindrical tube | full key system | highly flexible, hard to learn |
| [[instrument:ocarina\|Ocarina]] | duct head | **closed vessel** | none | pitch set by hole area |
| [[instrument:pan-flute\|Pan flute]] | lips | several **closed tubes** | none | one note per tube; found worldwide |

**Set the three reedless duct-blown instruments together** and they are all doing the same thing:
**obtaining a stable note the simplest way possible.** They all pay the same price: **low flexibility.**

## History

| Period | State |
|---|---|
| Medieval | simple duct pipes exist in Europe; the recorder's form gradually settles |
| Renaissance | consort making (mixed sizes playing together) becomes normal; much consort music is written for it |
| **Baroque** | **its high point**: a standard solo instrument with a large repertoire of sonatas and concertos; range and fingering fully worked out |
| From the mid-18th c. | displaced by the [[instrument:flute\|flute]] (louder, more flexible) and leaves professional use |
| 20th c. | **revival**: the early-music movement brings it back to the stage, while it becomes the commonest beginner's instrument in Western schools |
| Late 20th c. onward | early-music and contemporary strands run in parallel; extended techniques (wider range, overblowing) appear |

## Common misconceptions

- **"A recorder is a toy, not a real instrument."** In the **Baroque it was a standard solo instrument**
  with a large dedicated repertoire. Its 20th-century role as a school instrument is one chapter only.
- **"A recorder and a flute are the same instrument."** Both are edge-tone, but **the drive differs**:
  a duct against the lips — which decides how differently their colours can be shaped.
- **"It transposes, like a saxophone."** **It is written at sounding pitch.** Changing size changes the
  pitch, but the page always shows the real sound.
- **"There is only one recorder."** It is a **family of sizes** (garklein to bass) with shared fingering
  logic, and a standard consort in Renaissance and Baroque ensemble music.
- **"Blow harder and it is better."** A recorder is so responsive that excess air jumps to a higher partial —
  volume comes from **steadiness**, not from more air.

## Next

The last two on this line are its relatives: the [[instrument:ocarina|ocarina]] (a closed vessel, pitch set
by hole area) and the [[instrument:pan-flute|pan flute]] (many closed tubes, one note each).

Together they complete the oldest branch of the woodwinds — the reedless ones. After that the woodwind group
closes; the border with brass lies in the brass group, and the closest contrast with strings is on the
[[instrument:flute|flute]] page.
:::
