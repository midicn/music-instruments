---
id: mandolin
site: inst
cat: I1
title: 曼陀林
title_en: Mandolin
summary: 四组复弦、定弦与小提琴完全相同，用拨片演奏，颤音是它的招牌
summary_en: Four doubled courses tuned exactly like a violin, played with a pick — tremolo is its signature
level: standard
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [曼陀林, mandolin, 曼陀铃, mandoline]
order: 17
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:violin]]"
  - "[[instrument:lute]]"
  - "[[instrument:ukulele]]"
  - "[[instrument:classical-guitar]]"
instances:
  - pdmx-000374 | 维瓦尔第的双曼陀林协奏曲 RV 532 —— 曼陀林最著名的曲目，复弦与颤音都听得到
  - pdmx-001196 | 同一首协奏曲的另一个版本，可对照不同改编对复弦织体的处理
  - thesession-000860 | 传统舞曲 Dawn's Mandolin —— 曼陀林在民间舞曲里的典型位置，单旋律加伴奏
  - thesession-007865 | 另一首传统舞曲，速度更快，可听拨片在快速乐句里的颗粒感
  - thesession-007583 | 第三首传统舞曲，节奏更方整，适合对照同一条旋律的不同拨法
sources:
  - 琴体尺寸取通行制琴数据：A 型曼陀林琴体长 330 毫米、最大宽 200 毫米，弦长 350 毫米
  - 「四组复弦、定弦 G–D–A–E 与小提琴完全相同」属通行乐器学常识，本文为原创表述
  - 曼陀林出自 17–18 世纪的意大利 mandolino 一族、维瓦尔第与贝多芬都为其写过作品、20 世纪在美国蓝草音乐中成为核心乐器，依通行乐器史叙述
  - 音域数据依通行乐谱与乐器词典，本文为原创表述
updated: 2026-09-25
---

::: zh
曼陀林有两件事让人意外：

1. **它用八根弦，但只有四组。** 每两根同音成一组，拨一次等于同时拨两根。
2. **它的定弦和[[instrument:violin|小提琴]]一模一样** —— 都是 G–D–A–E。

所以曼陀林常被形容成"用拨片弹的小提琴"。这个说法有依据：定弦相同，
**音域、和弦结构、甚至很多乐句的思路都能互通**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 拨奏（拨片）· 有颈、有板腔共鸣箱、有品 |
| **所属族** | 西洋 · 弦乐（弹拨支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，曼陀林不在其中 |

## 结构：梨形琴体与八根弦

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="A 型曼陀林外形与主要部件：琴头、八枚弦轴、指板、椭圆音孔、拉弦板与四组复弦">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">A 型曼陀林 · 外形与主要部件（四组复弦 = 八根弦）</text>
  </g>
  <!-- 琴颈与指板 -->
  <path d="M308,70 L332,70 L340,190 L300,190 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M302,94 L338,94"/><path d="M303,118 L337,118"/><path d="M303,142 L337,142"/>
    <path d="M304,166 L336,166"/>
  </g>
  <!-- 琴头与八枚弦轴 -->
  <path d="M309,34 L331,34 L333,70 L307,70 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="291" y="38" width="16" height="5" rx="1"/><rect x="333" y="38" width="16" height="5" rx="1"/>
    <rect x="291" y="48" width="16" height="5" rx="1"/><rect x="333" y="48" width="16" height="5" rx="1"/>
    <rect x="291" y="58" width="16" height="5" rx="1"/><rect x="333" y="58" width="16" height="5" rx="1"/>
    <rect x="291" y="68" width="14" height="5" rx="1"/><rect x="335" y="68" width="14" height="5" rx="1"/>
  </g>
  <!-- 梨形琴体 -->
  <path d="M320,120 C321.9,120.8 327,120.8 331.2,124.6 C335.3,128.4 340.2,134.6 345.1,143 C350,151.4 355.1,162.5 360.4,175.2 C365.8,187.8 372.3,202.8 377.2,218.9 C382,235 389,256.9 389.7,271.8 C390.4,286.8 386,298.2 381.3,308.6 C376.7,319 369.5,327.6 361.8,333.9 C354.2,340.2 342.3,343.9 335.3,346.5 C328.4,349.2 322.6,349.4 320,350 M320,350 C317.4,349.4 311.6,349.2 304.7,346.5 C297.7,343.9 285.8,340.2 278.2,333.9 C270.5,327.6 263.3,319 258.7,308.6 C254,298.2 249.6,286.8 250.3,271.8 C251,256.9 258,235 262.8,218.9 C267.7,202.8 274.2,187.8 279.6,175.2 C284.9,162.5 290,151.4 294.9,143 C299.8,134.6 304.7,128.4 308.8,124.6 C313,120.8 318.1,120.8 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 椭圆音孔 -->
  <ellipse cx="320" cy="232" rx="20" ry="13" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <!-- 拉弦板与琴桥 -->
  <path d="M304,292 L336,292 L333,318 L307,318 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M300,278 L340,278 L340,284 L300,284 Z" fill="#111113" stroke="#343439" stroke-width="1"/>
  <path d="M304,278 L336,278" stroke="#A9A49B" stroke-width="1.5"/>
  <!-- 八根弦（四组复弦）-->
  <g stroke="#C9A227" opacity=".85">
    <path d="M311.5,72 L311.5,286" stroke-width="1"/><path d="M314.5,72 L314.5,286" stroke-width="1"/>
    <path d="M317.5,72 L317.5,286" stroke-width=".95"/><path d="M320.5,72 L320.5,286" stroke-width=".95"/>
    <path d="M323.5,72 L323.5,286" stroke-width=".9"/><path d="M326.5,72 L326.5,286" stroke-width=".9"/>
    <path d="M329.5,72 L329.5,286" stroke-width=".85"/><path d="M332.5,72 L332.5,286" stroke-width=".85"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L288,46"/><path d="M186,86 L298,88"/>
    <path d="M186,150 L262,152"/><path d="M186,232 L296,232"/>
    <path d="M186,280 L296,280"/><path d="M186,318 L266,318"/>
    <path d="M186,350 L276,348"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="47" text-anchor="end">琴头 · 四组弦轴</text>
    <text x="180" y="89" text-anchor="end">指板（窄、有品）</text>
    <text x="180" y="153" text-anchor="end">上腰（梨形，无明确腰）</text>
    <text x="180" y="235" text-anchor="end">椭圆音孔</text>
    <text x="180" y="283" text-anchor="end">琴桥（可调）</text>
    <text x="180" y="321" text-anchor="end">拉弦板</text>
    <text x="180" y="351" text-anchor="end">琴体 330 mm</text>
  </g>
  <text x="20" y="380" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">八根弦排得很密 —— 所以拨片一次扫过，通常同时碰到好几组，这就是它声音"厚"的来源。</text>
</svg>
```

三个结构要点：

1. **梨形琴体，没有明确的腰**。曼陀林不是"缩小的小提琴"，
   它的琴体是水滴形（A 型），最宽处在中下部。这个形状与
   [[instrument:lute|鲁特琴]]同一路线。
2. **四组复弦**。每组两根同音，共八根。拨一次等于同时拨两根 →
   **音量与余音都加倍**，代价是**调音与换弦的工作量翻倍**（八根弦要配成四对）。
3. **可调琴桥 + 有品**。琴桥可以从音孔里调节位置与高度，
   这在拨弦乐器里是"方便但容易被动坏"的设计；有品则让音准固定下来。

## 发声原理：复弦是"免费"的加倍

单根弦被拨响后，能量很快耗完。**两根同音弦紧挨着同时被拨**，会发生两件事：

- 它们的振动几乎同步，声波在空气里叠加 → 音量明显更大。
- 两根弦不可能完全同频（哪怕差几赫兹），叠加时会产生缓慢的**拍音**（颤动感）
  → 余音听起来更长、更有"波纹"。

这正是复弦的全部作用：**用一倍的材料，换更大的音量与更长的余音**。
不需要更大的共鸣箱 —— 这对一件要抱在怀里、还要用拨片快速换弦的乐器来说很关键。

> 代价要说清楚：八根弦意味着**调音时间翻倍**，只要有一根跑音，
> 整组的音量与余音都会打折。所以曼陀林手对调音的敏感度普遍高于吉他手。

## 音域

```range
{"range":"G3–E7","common":"G3–E6","caption":"曼陀林的实音音域与常用音区","caption_en":"The mandolin’s sounding range and its working register","note":"曼陀林与小提琴同一套定弦（G–D–A–E），所以音域也相同。它不是移调乐器，记谱音与实际音高一致。"}
```

因为定弦与小提琴相同，**音域也相同**：G3 到 E7（约四个八度）。
但两者的实际用法差别很大：

- 小提琴的高把位是常态；曼陀林的高把位需要**越过琴体**去按，
  指板也短，所以实际常用区集中在中音区。
- 曼陀林的高音区音色变"尖"而不是变"亮"，所以乐曲里很少长时间停在高把位。

## 音色与听辨

三条线索：

1. **极短的音头 + 极快的衰减**。拨片碰上钢弦是"啪"的一声，之后迅速退去。
   所以曼陀林几乎天生适合**快速音型**，不适合长音 ——
   除非用下面那个技巧。
2. **颤音（tremolo）**。因为单音留不住，曼陀林用**极快的上下交替拨弦**
   把一个音"续"下去 —— 听起来像长音，其实是每秒十几次的重复。
   这是它最著名的技法，也是它听上去"在抖"的原因。
3. **复弦的"波纹"**。同音双弦叠加出的拍音，让每个音都带一层细微的颤动 ——
   这是它与[[instrument:ukulele|尤克里里]]（单弦、四根）最容易分辨的地方。

```audiolab
{"type":"instrument","gm":"Banjo","synth":"plucked","phrase":["G3","D4","A4","E5"],"label":"四组空弦：与小提琴同一套定弦","label_en":"Four open courses — the violin's tuning","hint":"⚠️ GM 音色表里没有曼陀林，这里借最接近的拨弦采样（Banjo）示范音头。请与小提琴页的同一组空弦对比：音高一样，但曼陀林的音头更脆、余音更短","hint_en":"The GM palette has no mandolin, so this borrows the nearest sampled pluck (Banjo). Compare with the violin's open strings — same pitches, but a crisper attack and a shorter decay."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由上面的试听件负责。

## 与小提琴：同定弦、异命运

这是曼陀林最有意思的一节。同一条 G–D–A–E，在两件乐器上是两种活法：

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="曼陀林的四组复弦与小提琴的四根单弦对照，两者的定弦完全相同">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一个定弦，两种排法：上面是复弦（八根），下面是单弦（四根）</text>
  </g>
  <!-- 曼陀林：4 组复弦 -->
  <text x="20" y="58">曼陀林 · 四组复弦</text>
  <g stroke="#C9A227" stroke-width="2.4" opacity=".9">
    <path d="M196,72 L196,200"/><path d="M208,72 L208,200"/>
    <path d="M296,72 L296,200"/><path d="M308,72 L308,200"/>
    <path d="M396,72 L396,200"/><path d="M408,72 L408,200"/>
    <path d="M496,72 L496,200"/><path d="M508,72 L508,200"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#9C7A3C" text-anchor="middle">
    <text x="202" y="66">G3</text><text x="302" y="66">D4</text>
    <text x="402" y="66">A4</text><text x="502" y="66">E5</text>
  </g>
  <g stroke="#343439" stroke-width="1.4">
    <path d="M150,204 L560,204"/>
  </g>
  <text x="576" y="208" font-size="11" fill="#6E6A64">拨片方向</text>
  <!-- 小提琴：4 根单弦 -->
  <text x="20" y="248">小提琴 · 四根单弦</text>
  <g stroke="#C9A227" stroke-width="3" opacity=".9">
    <path d="M202,262 L202,320"/><path d="M302,262 L302,320"/>
    <path d="M402,262 L402,320"/><path d="M502,262 L502,320"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8" text-anchor="middle">
    <text x="202" y="256">G3</text><text x="302" y="256">D4</text>
    <text x="402" y="256">A4</text><text x="502" y="256">E5</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M202,208 L202,250"/><path d="M302,208 L302,250"/><path d="M402,208 L402,250"/><path d="M502,208 L502,250"/>
  </g>
</svg>
```

| | 曼陀林 | 小提琴 |
|---|---|---|
| 定弦 | G3 D4 A4 E5 | G3 D4 A4 E5 |
| 每音弦数 | 2（复弦） | 1 |
| 发音 | 拨片 | 弓摩擦 |
| 音头 | 啪（极快） | 擦（有毛刺，随后持续） |
| 持续能力 | 短，靠**颤音**续 | 长，靠弓持续 |
| 有品 | 有 | 无 |

**同一套音、两种命运**：曼陀林换来的是"音头清楚、节奏有颗粒"，
失去的是持续音；小提琴反过来。
所以同一条旋律，两件乐器会演化出完全不同的写法 ——
曼陀林偏爱分解和弦与快速音型，小提琴偏爱长句与歌唱性连弓。

至于为什么会有这么巧的重合，答案在历史上（下一节）。

## 家族与近亲

| 乐器 | 弦 | 定弦 | 发音 | 演奏姿势 |
|---|---|---|---|---|
| **曼陀林** | 4 组复弦（8 根） | G3 D4 A4 E5 | 拨片 | 抱持 |
| [[instrument:violin\|小提琴]] | 4 根单弦 | G3 D4 A4 E5 | 弓 | 夹在肩与下颌之间 |
| [[instrument:lute\|鲁特琴]] | 6+ 组复弦（羊肠） | 随调性变化 | 指腹 | 抱持、琴颈斜向上 |
| [[instrument:ukulele\|尤克里里]] | 4 根单弦 | G4 C4 E4 A4（复入式） | 指腹 | 抱持 |
| [[instrument:classical-guitar\|古典吉他]] | 6 根单弦 | E2 A2 D3 G3 B3 E4 | 指甲 | 抱持 |

曼陀林是这张表里**唯一一件"复弦 + 高音定弦 + 拨片"**的乐器。
复弦家族里其他成员（鲁特琴、俄罗斯的多种多姆拉琴）多数不在中音偏高区，
所以曼陀林的位置是独特的。

## 历史演变

要理解曼陀林的定弦为什么和小提琴一样，得从**拨弦乐器的复弦传统**说起。

16–17 世纪的欧洲，拨弦乐器普遍用**复弦**：鲁特琴是，曼陀林的前身
**mandolino**（意大利的小型复弦拨弦乐器）也是。它们当时的定弦往往成对配置
（两组接近的音 + 两组），不是今天这套 G–D–A–E。

到了 18 世纪，意大利的制琴传统把这个体系整理成了**四组复弦、定弦取小提琴那一套**——
这样**小提琴曲可以直接搬到曼陀林上弹**。这是关键的一步：
曼陀林从此有了一个"上游曲库"。维瓦尔第、贝多芬等人都为它写过作品，
写的时候直接借用了弦乐界的乐句语言。

| 时期 | 变化 |
|---|---|
| 17–18 世纪 | 意大利 mandolino 一族；那波里式（碗状背板）与今天的形制接近 |
| 18 世纪 | 定弦统一为 G–D–A–E，与小提琴接上 |
| 19 世纪末 | 传入美国，成为流行与舞曲乐器 |
| 20 世纪 30–40 年代 | 成为美国**蓝草音乐**的核心乐器（Bill Monroe 的影响力） |
| 今天 | 两条线并存：古典／室内乐的传统，与蓝草／民间的传统 |

顺带说一个今天最容易被忽略的细节：**"曼陀林"其实有好几种形制**。
那波里式的背板是**碗状**（像半个瓢），A 型是**平背梨形**，F 型有**涡卷与 f 孔**。
它们的定弦一样，音色与音量不同 —— F 型音量最大，是蓝草的标配。

## 常见误解

- **"曼陀林就是小号的小提琴。"** → 定弦与音域确实相同，但**发音方式完全不同**：
  拨片拨弦（音头极短）对弓摩擦（可无限持续）。这一条差别决定了它俩的曲目写法分道扬镳。
- **"八根弦，所以是八音。"** → 是**四组**、每组两根同音。听起来是四个音，不是八个。
- **"定弦和小提琴一样，所以指法可以照搬。"** → 音程关系可以照搬，但**有品 vs 无品**、
  把位高度、右手发音方式都不同。同一段旋律的合理写法会不一样。
- **"颤音是装饰。"** → 不是。因为单音留不住，**颤音是曼陀林做出长音的唯一手段**。
  它是生存技术，不是花样。
- **"曼陀林只有一种样子。"** → 至少三种形制：那波里式（碗背）、A 型（平背）、F 型（带 f 孔）。
  定弦相同，音响差别不小。
- **"它只是民间乐器。"** → 18 世纪欧洲作曲界就为它写过作品（协奏曲、奏鸣曲），
  古典传统一直在。蓝草只是它的第二个舞台。

## 下一步

想继续听：[[instrument:lute|鲁特琴]] 是这条复弦传统的源头，
[[instrument:ukulele|尤克里里]] 是"四组弦但用单弦"的对照（一个四组单弦、一个四组复弦）。
想理解复弦为什么能加倍音量，[[concept:harmonic-series|泛音列]]与
[[concept:interval|音程]]两节能给出机制。
:::

::: en
Two things about the mandolin surprise people:

1. **It has eight strings but only four notes.** Each pair is tuned in unison, so one stroke sounds two
   strings at once.
2. **It is tuned exactly like a [[instrument:violin|violin]]** — G–D–A–E.

So it is often described as "a violin played with a pick". There is a real basis for that: with the
same tuning, **the range, the chord shapes and much of the melodic thinking transfer**.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Plucked (with a pick) · necked, with a box resonator, fretted |
| **Family** | Western · Strings (plucked branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the mandolin is outside it |

## Structure: a pear-shaped body and eight strings

```svg
<svg viewBox="0 0 640 414" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="A-style mandolin parts: headstock, eight tuning pegs, fingerboard, oval soundhole, tailpiece and four doubled courses">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">A-style mandolin — outer form and principal parts (four courses, eight strings)</text>
  </g>
  <path d="M308,70 L332,70 L340,190 L300,190 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M302,94 L338,94"/><path d="M303,118 L337,118"/><path d="M303,142 L337,142"/>
    <path d="M304,166 L336,166"/>
  </g>
  <path d="M309,34 L331,34 L333,70 L307,70 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="291" y="38" width="16" height="5" rx="1"/><rect x="333" y="38" width="16" height="5" rx="1"/>
    <rect x="291" y="48" width="16" height="5" rx="1"/><rect x="333" y="48" width="16" height="5" rx="1"/>
    <rect x="291" y="58" width="16" height="5" rx="1"/><rect x="333" y="58" width="16" height="5" rx="1"/>
    <rect x="291" y="68" width="14" height="5" rx="1"/><rect x="335" y="68" width="14" height="5" rx="1"/>
  </g>
  <path d="M320,120 C321.9,120.8 327,120.8 331.2,124.6 C335.3,128.4 340.2,134.6 345.1,143 C350,151.4 355.1,162.5 360.4,175.2 C365.8,187.8 372.3,202.8 377.2,218.9 C382,235 389,256.9 389.7,271.8 C390.4,286.8 386,298.2 381.3,308.6 C376.7,319 369.5,327.6 361.8,333.9 C354.2,340.2 342.3,343.9 335.3,346.5 C328.4,349.2 322.6,349.4 320,350 M320,350 C317.4,349.4 311.6,349.2 304.7,346.5 C297.7,343.9 285.8,340.2 278.2,333.9 C270.5,327.6 263.3,319 258.7,308.6 C254,298.2 249.6,286.8 250.3,271.8 C251,256.9 258,235 262.8,218.9 C267.7,202.8 274.2,187.8 279.6,175.2 C284.9,162.5 290,151.4 294.9,143 C299.8,134.6 304.7,128.4 308.8,124.6 C313,120.8 318.1,120.8 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <ellipse cx="320" cy="232" rx="20" ry="13" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <path d="M304,292 L336,292 L333,318 L307,318 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M300,278 L340,278 L340,284 L300,284 Z" fill="#111113" stroke="#343439" stroke-width="1"/>
  <path d="M304,278 L336,278" stroke="#A9A49B" stroke-width="1.5"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M311.5,72 L311.5,286" stroke-width="1"/><path d="M314.5,72 L314.5,286" stroke-width="1"/>
    <path d="M317.5,72 L317.5,286" stroke-width=".95"/><path d="M320.5,72 L320.5,286" stroke-width=".95"/>
    <path d="M323.5,72 L323.5,286" stroke-width=".9"/><path d="M326.5,72 L326.5,286" stroke-width=".9"/>
    <path d="M329.5,72 L329.5,286" stroke-width=".85"/><path d="M332.5,72 L332.5,286" stroke-width=".85"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L288,46"/><path d="M186,86 L298,88"/>
    <path d="M186,150 L262,152"/><path d="M186,232 L296,232"/>
    <path d="M186,280 L296,280"/><path d="M186,318 L266,318"/>
    <path d="M186,350 L276,348"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="47" text-anchor="end">Headstock · four pairs of pegs</text>
    <text x="180" y="89" text-anchor="end">Fingerboard (narrow, fretted)</text>
    <text x="180" y="153" text-anchor="end">Upper end (pear shape, no waist)</text>
    <text x="180" y="235" text-anchor="end">Oval soundhole</text>
    <text x="180" y="283" text-anchor="end">Bridge (adjustable)</text>
    <text x="180" y="321" text-anchor="end">Tailpiece</text>
    <text x="180" y="351" text-anchor="end">Body 330 mm</text>
  </g>
  <text x="20" y="380" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Eight strings packed close together — a pick stroke</text>
  <text x="20" y="396" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">usually catches several courses at once, which is why it sounds thick.</text>
</svg>
```

Three structural points:

1. **A pear-shaped body with no real waist.** The mandolin is not a shrunken violin; the A-style body
   is teardrop-shaped, widest in the lower half — the same line of construction as the
   [[instrument:lute|lute]].
2. **Four doubled courses.** Two strings per note, eight in total. One stroke sounds both →
   **volume and sustain roughly double**, at the cost of **twice the tuning and restringing work**
   (eight strings must be matched into four pairs).
3. **An adjustable bridge plus frets.** The bridge can be repositioned and raised through the soundhole
   — convenient, and easy to knock out of adjustment. Frets fix the intonation.

## How it sounds: doubling for free

When a single string is plucked its energy runs out quickly. **Two unison strings struck together**
do two things:

- Their vibrations are almost synchronised, so the sound waves add in the air → noticeably more volume.
- They can never be *exactly* the same frequency (a few hertz apart at most); the addition produces a
  slow **beating** → the sustain sounds longer and slightly rippled.

That is the whole point of courses: **twice the material for more volume and longer sustain**, with no
need for a bigger box — which matters a great deal for an instrument held in the lap and played with a
fast-moving pick.

> The cost should be stated: eight strings means **double the tuning time**, and one string drifting
> dulls the volume and sustain of its whole course. Mandolin players tend to be more sensitive to tuning
> than guitarists.

## Range

```range
{"range":"G3–E7","common":"G3–E6","caption":"曼陀林的实音音域与常用音区","caption_en":"The mandolin’s sounding range and its working register","note":"曼陀林与小提琴同一套定弦（G–D–A–E），所以音域也相同。它不是移调乐器，记谱音与实际音高一致。"}
```

Because the tuning is the violin's, **the range is the violin's**: G3 to E7, about four octaves.
In practice the two use it very differently:

- A violinist lives in high positions; a mandolinist must reach **past the body** and the fingerboard is
  short, so the working register sits in the middle.
- High notes on a mandolin turn *thin* rather than bright, so music rarely stays up there long.

## Timbre, and how to hear it

Three cues:

1. **An extremely short attack and a fast decay.** A pick on steel is a "clack" followed by a rapid
   fade. That makes the mandolin naturally suited to **fast figures** and unsuited to long notes —
   unless you use the technique below.
2. **Tremolo.** Because a single note will not hold, the mandolin **alternates the pick at great speed**
   to sustain it. It sounds like a long note but is really a dozen-plus repetitions a second. This is
   its best-known technique, and the reason it seems to shimmer.
3. **The ripple of doubled courses.** The beating between unison pairs leaves a faint tremble on every
   note — the easiest way to tell a mandolin from a [[instrument:ukulele|ukulele]] (four single strings).

```audiolab
{"type":"instrument","gm":"Banjo","synth":"plucked","phrase":["G3","D4","A4","E5"],"label":"四组空弦：与小提琴同一套定弦","label_en":"Four open courses — the violin's tuning","hint":"⚠️ GM 音色表里没有曼陀林，这里借最接近的拨弦采样（Banjo）示范音头。请与小提琴页的同一组空弦对比：音高一样，但曼陀林的音头更脆、余音更短","hint_en":"The GM palette has no mandolin, so this borrows the nearest sampled pluck (Banjo). Compare with the violin's open strings — same pitches, but a crisper attack and a shorter decay."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above.

## Mandolin and violin: one tuning, two fates

The same G–D–A–E lives two very different lives:

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The mandolin's four doubled courses compared with the violin's four single strings; both share the same tuning">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One tuning, two arrangements — doubled courses above, single strings below</text>
  </g>
  <text x="20" y="58">Mandolin · four doubled courses</text>
  <g stroke="#C9A227" stroke-width="2.4" opacity=".9">
    <path d="M196,72 L196,200"/><path d="M208,72 L208,200"/>
    <path d="M296,72 L296,200"/><path d="M308,72 L308,200"/>
    <path d="M396,72 L396,200"/><path d="M408,72 L408,200"/>
    <path d="M496,72 L496,200"/><path d="M508,72 L508,200"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#9C7A3C" text-anchor="middle">
    <text x="202" y="66">G3</text><text x="302" y="66">D4</text>
    <text x="402" y="66">A4</text><text x="502" y="66">E5</text>
  </g>
  <g stroke="#343439" stroke-width="1.4">
    <path d="M150,204 L548,204"/>
  </g>
  <text x="20" y="248">Violin · four single strings</text>
  <g stroke="#C9A227" stroke-width="3" opacity=".9">
    <path d="M202,262 L202,320"/><path d="M302,262 L302,320"/>
    <path d="M402,262 L402,320"/><path d="M502,262 L502,320"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8" text-anchor="middle">
    <text x="202" y="256">G3</text><text x="302" y="256">D4</text>
    <text x="402" y="256">A4</text><text x="502" y="256">E5</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M202,208 L202,250"/><path d="M302,208 L302,250"/><path d="M402,208 L402,250"/><path d="M502,208 L502,250"/>
  </g>
</svg>
```

| | Mandolin | Violin |
|---|---|---|
| Tuning | G3 D4 A4 E5 | G3 D4 A4 E5 |
| Strings per note | 2 (a course) | 1 |
| Sound produced by | pick | bow friction |
| Attack | clack (extremely short) | scrape, then steady |
| Sustaining | short — tremolo does the work | long — the bow sustains |
| Frets | yes | no |

**One set of notes, two fates.** The mandolin buys a clear attack and rhythmic grain, and pays with
sustain; the violin is the reverse. Given the same melody, the two evolve completely different
writing — the mandolin favours broken chords and fast figures, the violin long phrases and singing
legato.

Why the coincidence of tuning? The answer is historical (next section).

## The family

| Instrument | Strings | Tuning | Sound | Hold |
|---|---|---|---|---|
| **Mandolin** | 4 doubled courses (8) | G3 D4 A4 E5 | pick | in the lap |
| [[instrument:violin\|Violin]] | 4 single | G3 D4 A4 E5 | bow | chin and shoulder |
| [[instrument:lute\|Lute]] | 6+ doubled courses (gut) | varies with key | fingertips | in the lap, neck angled up |
| [[instrument:ukulele\|Ukulele]] | 4 single | G4 C4 E4 A4 (re-entrant) | fingertips | in the lap |
| [[instrument:classical-guitar\|Classical guitar]] | 6 single | E2 A2 D3 G3 B3 E4 | nails | in the lap |

The mandolin is the only member of this table that combines **doubled courses, a high tuning and a
pick**. Other course-strung instruments (the lute, the various Russian domras) mostly sit at or below
the middle register, so the mandolin's position is unique.

## History

To understand why the mandolin shares the violin's tuning, start with the **course-strung plucked
tradition**.

In 16th- and 17th-century Europe plucked instruments commonly used courses: the lute did, and so did
the mandolin's ancestor, the Italian **mandolino** — a small course-strung instrument. Its tunings were
usually arranged in pairs (two adjacent notes plus two others), not today's G–D–A–E.

In the 18th century the Italian making tradition settled it into **four courses tuned like a violin** —
which meant **violin music could be played directly on the mandolin**. That was the decisive step: the
mandolin acquired an upstream repertoire. Vivaldi, Beethoven and others wrote for it, using the
phrasing language of the string world directly.

| Period | Change |
|---|---|
| 17th–18th c. | the Italian mandolino family; the Neapolitan bowl-back form close to today's |
| 18th c. | tuning settled to G–D–A–E, connecting it to the violin |
| Late 19th c. | reaches the United States; becomes a popular and dance-hall instrument |
| 1930s–40s | becomes central to American **bluegrass** (Bill Monroe's influence) |
| Today | two traditions coexist: classical/chamber and bluegrass/folk |

One easily missed detail: **"mandolin" covers several constructions**. Neapolitan mandolins have a
**bowl back** (half a gourd), the A-style is a **flat-backed pear**, and the F-style has **scrolls and
f-holes**. The tuning is the same; volume and tone differ — the F-style is the loudest and is standard
in bluegrass.

## Common misconceptions

- **"A mandolin is a small violin."** Same tuning and range, but the **sound production is completely
  different**: a pick (vanishingly short attack) versus bow friction (sustainable indefinitely). That
  one difference sends their repertoires in different directions.
- **"Eight strings, so eight notes."** Four **courses**, two strings each in unison. You hear four
  notes, not eight.
- **"Same tuning as a violin, so fingerings carry over."** Interval relationships do — but **frets
  versus none**, position height and right-hand technique all differ. What a good line looks like
  changes.
- **"Tremolo is ornament."** It is not. Because a single note will not sustain, **tremolo is the only
  way a mandolin makes a long note**. It is survival technique, not decoration.
- **"There is one kind of mandolin."** At least three: Neapolitan (bowl back), A-style (flat back) and
  F-style (with f-holes). Same tuning, noticeably different sound.
- **"It is only a folk instrument."** European composers wrote concertos and sonatas for it in the 18th
  century; the classical tradition never stopped. Bluegrass is its second stage.

## Next

To keep listening: the [[instrument:lute|lute]] is the source of this course-strung tradition, and the
[[instrument:ukulele|ukulele]] is the mirror image (four courses, but single-strung). For why doubling
a course doubles the volume, [[concept:harmonic-series|the harmonic series]] and
[[concept:interval|intervals]] give the mechanism.
:::
