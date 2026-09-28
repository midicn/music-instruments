---
id: acoustic-guitar
site: inst
cat: I1
title: 民谣吉他
title_en: Acoustic Guitar
summary: 六根钢弦、X 形音梁的拨弦乐器，琴颈接入琴体第 14 品
summary_en: Six steel strings over X-bracing, with the neck joining the body at the fourteenth fret
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [民谣吉他, acoustic guitar, 钢弦吉他, 木吉他, 拨片吉他]
order: 15
links:
  - "[[concept:register]]"
  - "[[concept:clef]]"
  - "[[concept:concert-pitch]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:harmonic-series]]"
  - "[[instrument:classical-guitar]]"
  - "[[instrument:ukulele]]"
  - "[[instrument:mandolin]]"
  - "[[instrument:lute]]"
instances:
  - giantmidi-003737 | Carulli 的短曲集 —— 吉他教学传统里最常被钢弦演奏者借用的那一路，句法短、织体清楚
  - giantmidi-003748 | Sor 的主题与变奏 —— 单把吉他上"低音加旋律"的典型写法，钢弦上会更清楚
  - giantmidi-003739 | Carulli 的 G 大调行板，慢速、单音为主，最容易听出钢弦的音头与余音
  - thesession-000006 | 单声部传统舞曲 Childgrove —— 吉他一族最常见的实际用途之一，伴奏一条旋律
  - thesession-000011 | 另一首单声部舞曲，节奏更方整，可与上一条对照
sources:
  - 琴体尺寸取通行制琴数据：琴体长 508 毫米（Dreadnought 体型）、上腰宽 300、腰宽 273、下腰宽 400 毫米，弦长 645 毫米
  - 定弦 E–A–D–G–B–E 与「记谱比实音高一个八度」属通行乐器学常识，本文为原创表述
  - X 形音梁为钢弦吉他常用结构（19 世纪中叶起由 C. F. Martin 体系确立），扇形音梁为尼龙弦常用结构，依通行制琴史与工艺叙述
  - ⚠️ 库内没有标题或作曲家可确认指向「民谣吉他」的曲目 —— 本条给出的 5 首是**吉他族**曲目（同族可对照），音色由试听件负责
updated: 2026-09-25
---

::: zh
民谣吉他就是大多数人心里「吉他」的样子：**六根钢弦、用拨片扫、能弹唱、能伴奏**。
它与 [[instrument:classical-guitar|古典吉他]]外形几乎一样，但换了两样东西 ——
**弦的材料**和**面板内侧的结构**。这两样一换，声音与用途就分开了。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 拨奏（拨片或手指）· 有颈、有板腔共鸣箱、有品 |
| **所属族** | 西洋 · 弦乐（弹拨支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，民谣吉他不在其中 |

## 结构：X 形音梁是给钢弦定做的

```svg
<svg viewBox="0 0 640 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="民谣吉他外形与主要部件：琴头、弦轴、14 品接入琴颈、音孔、琴码、护板与内部 X 形音梁位置">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">民谣吉他 · 外形与主要部件（六根钢弦，琴颈接在第 14 品）</text>
  </g>
  <!-- 琴颈与指板 -->
  <path d="M307,80 L333,80 L342,222 L298,222 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M299,110 L341,110"/><path d="M300,140 L340,140"/><path d="M301,170 L339,170"/>
    <path d="M302,200 L338,200"/>
  </g>
  <!-- 琴头与弦轴 -->
  <path d="M307,40 L333,40 L335,80 L305,80 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="287" y="46" width="18" height="6" rx="1"/><rect x="335" y="46" width="18" height="6" rx="1"/>
    <rect x="287" y="60" width="18" height="6" rx="1"/><rect x="335" y="60" width="18" height="6" rx="1"/>
    <rect x="287" y="74" width="18" height="6" rx="1"/><rect x="335" y="74" width="18" height="6" rx="1"/>
  </g>
  <!-- 琴体 -->
  <path d="M320,120 C329.4,121.3 364.7,123.2 378,127.8 C391.2,132.3 397.9,137.8 400.3,147.3 C402.7,156.8 395.4,172.7 392.4,185 C389.4,197.3 383,209 382.9,222.7 C382.9,236.3 385.6,252.2 391.6,266.9 C397.7,281.6 419.2,296.6 419.2,311.1 C419.2,325.6 403.1,343.6 391.6,354 C380.1,364.4 362,369.2 350.1,373.5 C338.3,377.8 325.2,378.9 320,380 M320,380 C314.8,378.9 301.7,377.8 289.9,373.5 C278,369.2 259.9,364.4 248.4,354 C236.9,343.6 220.8,325.6 220.8,311.1 C220.8,296.6 242.3,281.6 248.4,266.9 C254.4,252.2 257.1,236.3 257.1,222.7 C257,209 250.6,197.3 247.6,185 C244.6,172.7 237.3,156.8 239.7,147.3 C242.1,137.8 248.8,132.3 262,127.8 C275.3,123.2 310.6,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 内部：X 形音梁（虚线标位置）-->
  <g stroke="#9C7A3C" stroke-width="1.6" stroke-dasharray="3 3" fill="none" opacity=".95">
    <path d="M252,286 L392,352"/>
    <path d="M392,286 L252,352"/>
  </g>
  <!-- 音孔 -->
  <circle cx="320" cy="264" r="26" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <!-- 护板 -->
  <path d="M286,240 C276,262 280,296 296,318 C304,306 306,272 300,248 Z" fill="#111113" stroke="#343439" stroke-width="1"/>
  <!-- 琴码与琴桥 -->
  <path d="M292,306 L348,306 L348,315 L292,315 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M296,306 L344,306" stroke="#A9A49B" stroke-width="1.8"/>
  <!-- 六根钢弦（更细更亮）-->
  <g stroke="#C9A227" opacity=".9">
    <path d="M309.5,82 L309.5,308" stroke-width="1.4"/><path d="M313.6,82 L313.6,308" stroke-width="1.3"/>
    <path d="M317.7,82 L317.7,308" stroke-width="1.2"/><path d="M321.8,82 L321.8,308" stroke-width=".9"/>
    <path d="M325.9,82 L325.9,308" stroke-width=".8"/><path d="M330,82 L330,308" stroke-width=".7"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,48 L340,52"/><path d="M186,68 L340,68"/><path d="M186,100 L304,102"/>
    <path d="M186,158 L238,160"/><path d="M186,252 L290,252"/>
    <path d="M186,344 L250,330"/><path d="M186,364 L276,362"/>
    <path d="M186,282 L288,282"/><path d="M186,312 L288,312"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="51" text-anchor="end">琴头 · 六枚弦轴</text>
    <text x="180" y="71" text-anchor="end">弦枕（弦颈起点）</text>
    <text x="180" y="103" text-anchor="end">指板 · 细而略呈弧面</text>
    <text x="180" y="161" text-anchor="end">上腰</text>
    <text x="180" y="255" text-anchor="end">音孔</text>
    <text x="180" y="285" text-anchor="end" fill="#9C7A3C">X 形音梁（在面板内侧）</text>
    <text x="180" y="315" text-anchor="end">护板（拨片常碰的位置）</text>
    <text x="180" y="347" text-anchor="end">琴码与琴桥</text>
    <text x="180" y="367" text-anchor="end">下腰</text>
  </g>
  <text x="20" y="416" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">琴颈在第 14 品接进琴体（古典吉他是第 12 品）—— 高把位因此好按得多。</text>
</svg>
```

两处可见的差别，一处看不见的：

| | 古典吉他 | **民谣吉他** |
|---|---|---|
| 弦 | 尼龙（前三根，后三根缠金属） | **全部钢弦** |
| 面板内侧 | 扇形音梁 | **X 形音梁** |
| 琴颈接入 | 第 12 品 | **第 14 品** |
| 指板 | 平、宽 | **略呈弧面、窄** |
| 琴头弦轴 | 横向（两侧各三） | 常见**后倾一排六枚** |
| 常见用途 | 独奏、重奏 | **伴奏与弹唱**、指弹独奏 |

看不见的那处（X 形音梁）才是根因。钢弦的张力加起来约 **80 公斤**，
是尼龙弦的一倍。这么大的拉力如果只靠细木条摊开，面板会被拉变形，
所以钢弦吉他改用**两根交叉的主梁（X 形）**：交叉点落在音孔下方，
把拉力沿对角线分到琴体的两侧。**它不是为了让声音更好，是为了让琴不散架。**

## 发声原理：同一套路径，两倍的驱动力

路径与所有板腔体一致：弦 → 琴码 → 面板 → 箱内空气 → 音孔辐射。
民谣吉他多出来的，是**驱动力**：

- 钢弦张力高一倍 → 面板被推得更狠 → **音量更大**。
- 钢弦的内阻尼小 → **高次谐波留得更多** → 声音更亮、更有"金属感"。
- 代价同样来自这里：钢弦按下去更费力（尤其大横按），
  手指的磨损更重，弦的寿命更短（尼龙弦几个月不换，钢弦几周就失亮）。

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="钢弦吉他的 X 形音梁俯视示意：两根主梁在音孔下方交叉，另有若干辅助梁与横向琴桥板">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">面板内侧 · X 形音梁（俯视，把面板翻过来看）</text>
  </g>
  <path d="M320,44 C358,46 400,54 416,76 C432,98 424,128 416,150 C408,172 400,190 400,208 C400,228 408,246 420,262 C432,278 428,296 408,306 C380,318 342,320 320,320"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <path d="M320,44 C282,46 240,54 224,76 C208,98 216,128 224,150 C232,172 240,190 240,208 C240,228 232,246 220,262 C208,278 212,296 232,306 C260,318 298,320 320,320 Z"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <!-- 音孔 -->
  <circle cx="320" cy="132" r="28" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="320" y="136" text-anchor="middle" font-size="11" fill="#5B7FA8">音孔</text>
  <!-- X 形主梁 -->
  <g stroke="#9C7A3C" stroke-width="7" stroke-linecap="round">
    <path d="M228,204 L410,300"/>
    <path d="M412,204 L230,300"/>
  </g>
  <!-- 交叉点标记 -->
  <circle cx="320" cy="252" r="6" fill="none" stroke="#E8C547" stroke-width="2.4"/>
  <text x="332" y="246" font-size="11" fill="#E8C547">交叉点落在音孔下方</text>
  <!-- 辅助梁 -->
  <g stroke="#9C7A3C" stroke-width="4.4" stroke-linecap="round" opacity=".75">
    <path d="M250,84 L390,84"/>
    <path d="M240,182 L272,182"/>
    <path d="M368,182 L400,182"/>
  </g>
  <text x="404" y="82" font-size="11" fill="#9C7A3C">横向辅助梁</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">X 形把钢弦的拉力沿对角线分到琴体两侧 —— 这是"张力大一倍"所需要的结构。</text>
</svg>
```

**一处反直觉的事实**：民谣吉他音量比古典大，但**低频并不更深**。
两件的共鸣箱共振频率都在 100 Hz 上下，最低空弦都是 E2（82 Hz）。
钢弦增加的是**中高频**与**音量** —— 所以"民谣吉他低音更猛"其实常常是错觉：
听起来更"响"，容易被当成更低。

## 音域

```range
{"range":"E2–E6","written":"E3–E7","common":"E2–C5","caption":"民谣吉他的记谱音域与实音音域","caption_en":"Acoustic guitar: notated range above, sounding range below","note":"与古典吉他同定弦、同音域 —— 记谱比实音高一个八度。"}
```

定弦完全一样：**E2–A2–D3–G3–B3–E4**。所以两件吉他的**指法可以直接搬**
——这是弹唱者能从古典教材里借练习曲的原因。

音域上与古典吉他的差别是**实际可用性**：琴颈接入第 14 品，
上面的音（比如 E6）比以前容易按到；同时又多了用**变调夹**换调这条捷径
（夹在第 2 品，指法不动就成了 D 调）。古典吉他用变调夹很少，民谣里几乎是标配。

## 音色与听辨

三条识别线索：

1. **音头更"脆"**。钢弦被拨的瞬间有清亮的爆音，比尼龙的圆音头明显得多。
   在独奏里这像"颗粒"，在扫弦里它变成整个和弦的"边"。
2. **余音里有金属泛音**。衰减时不是均匀变轻，而是上方的泛音先退、
   留下一层带金属味的芯。这是钢弦内阻尼小的直接结果。
3. **扫弦时的"弦噪"**。拨片划过缠弦会有细微的摩擦噪声，
   转调夹与手指滑动也有。这些噪声在高保真录音里很清楚，
   是民谣吉他录音的"指纹"之一。

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (steel)","synth":"plucked","phrase":["E2","A2","D3","G3","B3","E4"],"label":"六根空弦：钢弦与尼龙的差别在哪","label_en":"Six open strings — what steel changes","hint":"先听这一遍钢弦，再去听古典吉他页的尼龙弦：音量、音头的脆度、泛音的多寡","hint_en":"Hear this steel set, then compare with the nylon set on the classical guitar page — volume, attack, overtones."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由上面的试听件负责。另外如实说明：库内没有标题或作曲家可确认指向「民谣吉他」的曲目
> —— 上面 5 首是吉他族（同一定弦）的曲目，用于听织体，不是钢弦吉他的录音。

## 演奏技法

民谣吉他的右手**通常用拨片**，这是它与古典吉他最直观的分界。三种主流做法：

- **拨片扫弦（strumming）**：手腕带动，上下往复。上扫与下扫的音量比例、
  扫的弦数范围，决定了伴奏的"形状"。这是弹唱的核心技术。
- **指弹（fingerstyle）**：放下拨片，用拇指负责低音三根、食指中指无名指负责高音三根。
  它与古典吉他的右手体系同源，但通常用指腹或指套而不是指甲，音色更闷、更"木"。
- **混合拨弦（hybrid picking）**：握着拨片的同时用中指无名指补音 ——
  介于两者之间，乡村与布鲁斯常用。

左手方面，因为钢弦张力大，民谣吉他有几件古典吉他很少用的技术：

- **大横按（barre）**：一根手指按住六根弦。钢弦上这是体力活，
  但也正是它让一个和弦指型能整体移动（所以常用变调夹省力）。
- **击弦与勾弦（hammer-on / pull-off）**：靠左手发音，不需要右手拨。
- **滑音与推弦**：民谣里滑音常见；推弦（把弦横向推高）主要在电吉他上，
  钢弦民谣上也能做，但幅度小。
- **打板（percussive）**：用小指侧或手掌敲面板当节奏 —— 指弹独奏里常用。

## 家族与近亲

| 乐器 | 弦 | 面板内侧 | 音头特征 | 常见用途 |
|---|---|---|---|---|
| [[instrument:classical-guitar\|古典吉他]] | 6 根尼龙 | 扇形音梁 | 圆、柔 | 独奏、重奏 |
| **民谣吉他** | 6 根钢弦 | **X 形音梁** | 脆、亮 | 伴奏、弹唱、指弹 |
| [[instrument:ukulele\|尤克里里]] | 4 根尼龙 | 多为扇梁 / 单梁 | 小、短 | 弹唱、轻伴奏 |
| [[instrument:mandolin\|曼陀林]] | 4 组**复弦**钢弦 | 纵向音梁（拱形面板） | 极脆、颤音 | 民间舞曲、蓝草 |
| [[instrument:lute\|鲁特琴]] | 6 组以上复弦（羊肠） | 横梁为主 | 轻、干 | 文艺复兴独奏 |

一个常被混淆的点：**"民谣"这个词说的是用途，不是结构**。
同一把钢弦吉他，弹民谣叫民谣吉他，弹蓝草叫平顶吉他，弹指弹叫指弹吉他 ——
**乐器是同一件**。真正分结构的是弦与音梁（见上表），不是曲风。

## 历史演变

钢弦吉他不是某一天被发明出来的，而是**弦的进步逼出来的结构变化**。

19 世纪以前，欧洲的吉他用的都是羊肠弦（后来是尼龙）。羊肠弦张力小、音色柔，
但**音量小、易断、怕潮**。19 世纪末美国的制琴师开始尝试钢弦 —— 一上来问题就出现了：
面板被拉变形，琴体开胶。于是结构跟着改：

| 年代 | 变化 | 原因 |
|---|---|---|
| 19 世纪中叶起 | 音梁从扇形改为**X 形** | 钢弦张力一倍，需要抗拉而不是摊力 |
| 同期 | 琴体加大（出现 Dreadnought 等体型） | 加大共鸣箱换音量 |
| 20 世纪初 | 琴颈接入点从第 12 品移到**第 14 品** | 高把位可用，适应弹唱与独奏 |
| 20 世纪 | 出现钢芯缠弦（磷青铜、黄铜） | 音量与音色稳定，寿命更长 |

这套结构后来直接搬到了电吉他上：**电吉他的琴体形状、定弦、指法与民谣吉他同源**，
只是把"用共鸣箱放大"换成了"用拾音器转换成电信号"。
所以民谣吉他是理解电声乐器的第一块台阶，也是 20 世纪流行音乐里出现次数最多的乐器。

## 常见误解

- **"民谣吉他比古典吉他好，音量更大。"** → 它们服务不同目的。钢弦换来的音量，
  代价是**动态层次更粗**、按弦更费力、弦寿命更短。古典吉他那种极弱的渐弱，
  钢弦很难做到。
- **"民谣吉他低音更猛。"** → 音量更大 ≠ 低频更深。两件的最低空弦都是 E2（82 Hz），
  共鸣箱共振也都在 100 Hz 上下。钢弦多出来的主要是中高频与总响度。
- **"琴颈接在第 14 品只是好看。"** → 那是实打实的可用性差别：
  第 12 品接入时，第 15 品以上的位置要避过琴体去按，非常吃力。
- **"变调夹是偷懒。"** → 它是**换调与换音色的工具**。夹上以后空弦音变了，
  同一个和弦指型的音响也会变（开放弦的共鸣与按弦音不同）——
  这是编曲上的选择，不只是省力。
- **"吉他谱上的音就是听到的音。"** → 和古典吉他一想，是**移调乐器**，
  记谱比实音高一个八度。看音域图的两行就清楚。
- **"弦断了随便换一根就行。"** → 钢弦有规格（粗细、材质、缠法），
  混用会让张力失衡，面板受力不均。整套换是常规做法。

## 下一步

往两头看：往同源看 [[instrument:classical-guitar|古典吉他]]（同一形状、换一套弦与一套音梁），
往历史看 [[instrument:lute|鲁特琴]]（吉他的复弦祖先）。
想听"小一号的同一件事"，去 [[instrument:ukulele|尤克里里]] ——
只有四根弦，但定弦里藏着一个小反直觉。
:::

::: en
The acoustic guitar is what most people picture when they hear "guitar": **six steel strings, played
with a pick, for songs and accompaniment**. It looks almost identical to a
[[instrument:classical-guitar|classical guitar]], but two things changed — **the string material** and
**the structure inside the top plate**. Those two changes separate the sound and the job.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Plucked (pick or fingers) · necked, with a box resonator, fretted |
| **Family** | Western · Strings (plucked branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the acoustic guitar is outside it |

## Structure: X-bracing is built for steel

```svg
<svg viewBox="0 0 640 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Acoustic guitar parts: headstock, tuning machines, fingerboard joining at the fourteenth fret, soundhole, bridge, pickguard and the X-bracing inside">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Acoustic guitar — outer form and principal parts (six steel strings; neck joins at fret 14)</text>
  </g>
  <path d="M307,80 L333,80 L342,222 L298,222 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M299,110 L341,110"/><path d="M300,140 L340,140"/><path d="M301,170 L339,170"/>
    <path d="M302,200 L338,200"/>
  </g>
  <path d="M307,40 L333,40 L335,80 L305,80 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="287" y="46" width="18" height="6" rx="1"/><rect x="335" y="46" width="18" height="6" rx="1"/>
    <rect x="287" y="60" width="18" height="6" rx="1"/><rect x="335" y="60" width="18" height="6" rx="1"/>
    <rect x="287" y="74" width="18" height="6" rx="1"/><rect x="335" y="74" width="18" height="6" rx="1"/>
  </g>
  <path d="M320,120 C329.4,121.3 364.7,123.2 378,127.8 C391.2,132.3 397.9,137.8 400.3,147.3 C402.7,156.8 395.4,172.7 392.4,185 C389.4,197.3 383,209 382.9,222.7 C382.9,236.3 385.6,252.2 391.6,266.9 C397.7,281.6 419.2,296.6 419.2,311.1 C419.2,325.6 403.1,343.6 391.6,354 C380.1,364.4 362,369.2 350.1,373.5 C338.3,377.8 325.2,378.9 320,380 M320,380 C314.8,378.9 301.7,377.8 289.9,373.5 C278,369.2 259.9,364.4 248.4,354 C236.9,343.6 220.8,325.6 220.8,311.1 C220.8,296.6 242.3,281.6 248.4,266.9 C254.4,252.2 257.1,236.3 257.1,222.7 C257,209 250.6,197.3 247.6,185 C244.6,172.7 237.3,156.8 239.7,147.3 C242.1,137.8 248.8,132.3 262,127.8 C275.3,123.2 310.6,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#9C7A3C" stroke-width="1.6" stroke-dasharray="3 3" fill="none" opacity=".95">
    <path d="M252,286 L392,352"/>
    <path d="M392,286 L252,352"/>
  </g>
  <circle cx="320" cy="264" r="26" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <path d="M286,240 C276,262 280,296 296,318 C304,306 306,272 300,248 Z" fill="#111113" stroke="#343439" stroke-width="1"/>
  <path d="M292,306 L348,306 L348,315 L292,315 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M296,306 L344,306" stroke="#A9A49B" stroke-width="1.8"/>
  <g stroke="#C9A227" opacity=".9">
    <path d="M309.5,82 L309.5,308" stroke-width="1.4"/><path d="M313.6,82 L313.6,308" stroke-width="1.3"/>
    <path d="M317.7,82 L317.7,308" stroke-width="1.2"/><path d="M321.8,82 L321.8,308" stroke-width=".9"/>
    <path d="M325.9,82 L325.9,308" stroke-width=".8"/><path d="M330,82 L330,308" stroke-width=".7"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,48 L340,52"/><path d="M186,68 L340,68"/><path d="M186,100 L304,102"/>
    <path d="M186,158 L238,160"/><path d="M186,252 L290,252"/>
    <path d="M186,344 L250,330"/><path d="M186,364 L276,362"/>
    <path d="M186,282 L288,282"/><path d="M186,312 L288,312"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="51" text-anchor="end">Headstock · six machines</text>
    <text x="180" y="71" text-anchor="end">Nut (where the neck starts)</text>
    <text x="180" y="103" text-anchor="end">Fingerboard (narrow)</text>
    <text x="180" y="161" text-anchor="end">Upper bout</text>
    <text x="180" y="255" text-anchor="end">Soundhole</text>
    <text x="180" y="285" text-anchor="end" fill="#9C7A3C">X-bracing (inside)</text>
    <text x="180" y="315" text-anchor="end">Pickguard</text>
    <text x="180" y="347" text-anchor="end">Bridge and saddle</text>
    <text x="180" y="367" text-anchor="end">Lower bout</text>
  </g>
  <text x="20" y="400" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The neck joins the body at fret 14 (a classical guitar joins at fret 12) —</text>
  <text x="20" y="416" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">which makes the upper positions far easier to reach.</text>
</svg>
```

Two visible differences and one invisible:

| | Classical guitar | **Acoustic guitar** |
|---|---|---|
| Strings | nylon (three plain, three wound) | **all steel** |
| Bracing inside | fan | **X** |
| Neck joint | fret 12 | **fret 14** |
| Fingerboard | flat, wide | **slightly radiused, narrow** |
| Tuners | side-mounted, three a side | often **six in a row on a back-angled head** |
| Typical use | solo, chamber | **accompaniment and song**, fingerstyle solo |

The invisible one — the X-bracing — is the root cause. A steel set pulls about **80 kg**, double a
nylon set. That much pull distributed through thin struts would deform the top plate, so steel-string
guitars use **two main braces crossing in an X**, with the crossing point below the soundhole, sending
the tension diagonally into the sides. **It is not there to sound better; it is there to keep the
instrument from folding up.**

## How it sounds: same path, twice the drive

The acoustic path is common to every box-bodied instrument: string → saddle → top plate → air →
out through the soundhole. What the acoustic guitar adds is **drive**:

- Steel pulls twice as hard → the plate is pushed harder → **more volume**.
- Steel has lower damping → **more high overtones survive** → brighter, more metallic.
- The cost comes from the same place: higher string tension means harder fretting (especially barre
  chords), more wear on the fingers, and a shorter string life — nylon lasts months, steel loses its
  brightness in weeks.

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Looking at the inside of a steel-string guitar top: two main braces crossing in an X below the soundhole, plus transverse auxiliary braces">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Inside the top plate · X-bracing (seen from inside)</text>
  </g>
  <path d="M320,44 C358,46 400,54 416,76 C432,98 424,128 416,150 C408,172 400,190 400,208 C400,228 408,246 420,262 C432,278 428,296 408,306 C380,318 342,320 320,320"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <path d="M320,44 C282,46 240,54 224,76 C208,98 216,128 224,150 C232,172 240,190 240,208 C240,228 232,246 220,262 C208,278 212,296 232,306 C260,318 298,320 320,320 Z"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <circle cx="320" cy="132" r="28" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="320" y="136" text-anchor="middle" font-size="11" fill="#5B7FA8">soundhole</text>
  <g stroke="#9C7A3C" stroke-width="7" stroke-linecap="round">
    <path d="M228,204 L410,300"/>
    <path d="M412,204 L230,300"/>
  </g>
  <circle cx="320" cy="252" r="6" fill="none" stroke="#E8C547" stroke-width="2.4"/>
  <text x="336" y="246" font-size="11" fill="#E8C547">the crossing sits below the soundhole</text>
  <g stroke="#9C7A3C" stroke-width="4.4" stroke-linecap="round" opacity=".75">
    <path d="M250,84 L390,84"/>
    <path d="M240,182 L272,182"/>
    <path d="M368,182 L400,182"/>
  </g>
  <text x="396" y="70" font-size="11" fill="#9C7A3C">transverse braces</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The X sends steel-string tension diagonally into the sides — the structure that double tension requires.</text>
</svg>
```

**One counter-intuitive fact**: an acoustic guitar is louder than a classical, but its bass is **not
deeper**. Both boxes resonate near 100 Hz and both have E2 (82 Hz) as their lowest open string. What
steel adds is **mid and high frequency energy plus overall loudness** — so "steel-string guitars have
a bigger bass" is usually an illusion: it sounds *louder*, and loudness gets mistaken for depth.

## Range

```range
{"range":"E2–E6","written":"E3–E7","common":"E2–C5","caption":"民谣吉他的记谱音域与实音音域","caption_en":"Acoustic guitar: notated range above, sounding range below","note":"与古典吉他同定弦、同音域 —— 记谱比实音高一个八度。"}
```

The tuning is identical: **E2–A2–D3–G3–B3–E4**. Fingerings transfer directly between the two guitars —
which is why a strummer can borrow studies from classical method books.

The practical difference is **access and keys**: with the neck joining at fret 14, high positions are
much easier to reach, and the **capo** becomes a routine tool (clamp at fret 2 and the same shapes
sound in D). Classical players rarely use a capo; acoustic players treat it as standard equipment.

## Timbre, and how to hear it

Three identifying cues:

1. **A crisper attack.** A plucked steel string has a bright burst that nylon's rounder attack lacks.
   In a solo it reads as "grain"; in a strummed chord it becomes the chord's edge.
2. **Metallic overtones in the decay.** Steel does not fade evenly — the top end goes last,
   leaving a metallic core behind. That is low damping at work.
3. **String noise.** A pick across wound strings makes a fine scraping sound, as do capo and finger
   slides. Close-miked recordings capture it clearly; it is part of the instrument's fingerprint.

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (steel)","synth":"plucked","phrase":["E2","A2","D3","G3","B3","E4"],"label":"六根空弦：钢弦与尼龙的差别在哪","label_en":"Six open strings — what steel changes","hint":"先听这一遍钢弦，再去听古典吉他页的尼龙弦：音量、音头的脆度、泛音的多寡","hint_en":"Hear this steel set, then compare with the nylon set on the classical guitar page — volume, attack, overtones."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above. For transparency: no track in the
> library carries a title or composer that identifies it as acoustic-guitar music. The five above are
> guitar-family works (same tuning) chosen for texture, not steel-string recordings.

## Playing techniques

The right hand **usually holds a pick**, the most visible divide from the classical guitar.
Three mainstream approaches:

- **Strumming**: the wrist drives the pick up and down. The loudness ratio between up- and downstrokes,
  and how many strings each stroke covers, define the shape of an accompaniment. The core technique of
  playing and singing.
- **Fingerstyle**: put the pick down; the thumb takes the three bass strings and the index, middle and
  ring fingers the top three. It shares ancestry with the classical right hand, but usually plays with
  fingertips or picks rather than nails — duller, woodier.
- **Hybrid picking**: hold the pick and add the middle and ring fingers. Between the two worlds, common
  in country and blues.

On the left hand, high tension brings techniques a classical player rarely needs:

- **Barre chords**: one finger across all six strings. Physically demanding on steel — which is exactly
  why a capo is so useful, since it lets a shape move without the effort.
- **Hammer-ons and pull-offs**: sounding notes with the left hand alone.
- **Slides and bends**: slides are common; bends (pushing the string sideways to raise pitch) belong
  mainly to electric guitars, but work in a small range on steel too.
- **Percussive playing**: tapping the top plate with the side of the palm or fingers for rhythm —
  routine in fingerstyle solo work.

## The family

| Instrument | Strings | Bracing | Attack | Typical use |
|---|---|---|---|---|
| [[instrument:classical-guitar\|Classical guitar]] | 6 nylon | fan | round, soft | solo, chamber |
| **Acoustic guitar** | 6 steel | **X** | crisp, bright | accompaniment, song, fingerstyle |
| [[instrument:ukulele\|Ukulele]] | 4 nylon | fan or single brace | small, short | song, light accompaniment |
| [[instrument:mandolin\|Mandolin]] | 4 **doubled** courses, steel | longitudinal (arched top) | very crisp, tremolo | folk dance, bluegrass |
| [[instrument:lute\|Lute]] | 6+ doubled courses, gut | transverse braces | light, dry | Renaissance solo |

One frequent confusion: **"acoustic" names a use, not a structure.** The same steel-string instrument
is called a folk guitar when strummed and a fingerstyle guitar when played without a pick —
**it is one instrument**. What actually separates instruments is strings and bracing (the table above),
not repertoire.

## History

The steel-string guitar was not invented on a single day; **string technology forced a structural
change**.

Before the 19th century European guitars used gut strings (later nylon). Gut is low-tension and mellow
but **quiet, fragile and humidity-sensitive**. Late in the 19th century American makers began
experimenting with steel — and immediately hit problems: tops deformed, bodies came apart. So the
structure followed:

| Period | Change | Why |
|---|---|---|
| From the mid-19th c. | bracing changed from fan to **X** | double tension needs resistance, not spreading |
| Same period | bodies enlarged (Dreadnought and similar) | a bigger box for more volume |
| Early 20th c. | neck joint moved from fret 12 to **fret 14** | upper positions become usable for song and solo |
| 20th c. | steel-core wound strings (phosphor bronze, brass) | stable tone and volume, longer life |

That structure was then carried straight into the electric guitar: **the electric guitar's body shape,
tuning and fingering all descend from the steel-string acoustic**, replacing "amplify with a box" with
"convert to a signal with a pickup". So the acoustic guitar is the first step towards understanding
electric instruments — and the most frequently heard instrument in 20th-century popular music.

## Common misconceptions

- **"Acoustic is better than classical — more volume."** They serve different purposes. Steel buys
  volume at the cost of **coarser dynamics**, harder fretting and shorter string life. The classical
  guitar's very soft pianissimo is hard to achieve on steel.
- **"Acoustic guitars have a bigger bass."** More volume is not deeper bass. Both have E2 (82 Hz) as
  their lowest string, and both boxes resonate near 100 Hz. Steel adds mostly mid and high energy and
  overall loudness.
- **"The 14th-fret neck joint is just cosmetic."** It is a real usability difference: with a 12th-fret
  joint, notes above fret 15 require reaching past the body.
- **"A capo is for people who cannot transpose."** It is a tool for **changing key and colour**. Once
  clamped, the open strings change, so the same chord shapes sound different — an arranging decision,
  not just convenience.
- **"What you read is what sounds."** As with the classical guitar, this is a **transposing**
  instrument, notated an octave above sounding pitch.
- **"When a string breaks, replace just that one."** Steel strings have specs — gauge, material,
  winding. Mixing them unbalances tension across the top. Replacing the set is standard practice.

## Next

Look both ways: to the [[instrument:classical-guitar|classical guitar]] (same shape, a different set
of strings and bracing) and back in history to the [[instrument:lute|lute]] (the guitar's
doubled-course ancestor). To hear "the same thing, one size down", go to the
[[instrument:ukulele|ukulele]] — only four strings, but there is a small counter-intuitive fact hidden
in its tuning.
:::
