---
id: viol
site: inst
cat: I1
title: 维奥尔琴
title_en: Viol
summary: 有品、六弦、用下握弓的弓弦乐器，文艺复兴与巴洛克早期室内乐的主角
summary_en: A fretted six-string bowed instrument played with an underhand grip — the chamber instrument of the Renaissance
level: core
tags: [乐器, 弦乐, 西洋, 早期乐器]
tags_en: [instrument, strings, western, early music]
alias: [维奥尔琴, viol, viola da gamba, 低音维奥尔, gamba, 古大提琴]
order: 20
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:clef]]"
  - "[[instrument:lute]]"
  - "[[instrument:cello]]"
  - "[[instrument:violin]]"
  - "[[instrument:double-bass]]"
instances:
  - pdmx-000385 | 巴赫为维奥尔琴写的奏鸣曲 BWV 1027 —— 库内**唯一**可确认为维奥尔琴的曲目，低音声部的走动与上方旋律的对话正是它的本职
  - pdmx-000337 | 伊丽莎白时代的英国琉特琴加利亚德舞曲 —— 同代、同体裁，维奥尔与鲁特琴共享同一个曲目池
  - mutopia-001206 | 16 世纪西班牙维乌埃拉琴的帕凡舞曲 —— 弓弦维奥尔所出的那一支，可听早期独奏曲的句法
sources:
  - 琴体尺寸取通行制琴数据：低音维奥尔琴体长约 680 毫米，上腰宽 320、腰宽 260、下腰宽 420 毫米
  - 「低音维奥尔六弦定弦 D–G–C–E–A–d（四度夹三度），琴颈有 7 个可移动的肠弦品」依通行乐器学与早期音乐演奏惯例
  - 「文弓持于手心向上（下握）」、外凸弓杆、轻张力低音量，依通行乐器史叙述
  - 「维奥尔琴不是大提琴的前身」属乐器学界的通行结论（两者并行发展、来源不同），本文据此纠正常见说法
  - ⚠️ 库内可确认为维奥尔琴的曲目只有 1 首（BWV 1027）—— 另两条取同代（16–17 世纪）独奏曲，本条已如实说明
updated: 2026-09-26
---

::: zh
维奥尔琴是[[instrument:cello|大提琴]]的**同代人，不是它的前身** ——
这句话值得放在最前面，因为几乎所有人都会搞反。

它 15 世纪末出现在西班牙，16–17 世纪是欧洲上层家庭的标准配置，
到 18 世纪末被小提琴族挤出主流。它与大提琴并行存在过两百年。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 摩擦激励（用弓擦弦）· **有品**、有颈、平背折角的板腔共鸣箱 |
| **所属族** | 西洋 · 弦乐（早期乐器支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，维奥尔琴不在其中 |

## 结构：三处与大提琴相反的地方

```svg
<svg viewBox="0 0 640 480" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="低音维奥尔琴外形与主要部件：斜肩、平背折角、C 形音孔、七个肠弦品、六根弦与雕花琴头">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">低音维奥尔琴 · 外形与主要部件（两侧斜肩、平背折角、七个品）</text>
  </g>
  <!-- 琴颈与指板（品） -->
  <path d="M308,74 L332,74 L338,206 L302,206 Z" fill="#0E0E10"/>
  <g stroke="#E8C547" stroke-width="2.4" opacity=".9">
    <path d="M304,96 L336,96"/><path d="M304,114 L336,114"/><path d="M304,132 L336,132"/>
    <path d="M305,150 L335,150"/><path d="M305,168 L335,168"/><path d="M305,186 L335,186"/>
    <path d="M306,204 L334,204"/>
  </g>
  <!-- 琴头（雕花，不是涡卷） -->
  <path d="M309,34 L331,34 L333,74 L307,74 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="291" y="40" width="16" height="5" rx="1"/><rect x="333" y="40" width="16" height="5" rx="1"/>
    <rect x="291" y="52" width="16" height="5" rx="1"/><rect x="333" y="52" width="16" height="5" rx="1"/>
    <rect x="291" y="64" width="16" height="5" rx="1"/><rect x="333" y="64" width="16" height="5" rx="1"/>
  </g>
  <path d="M320,32 C310,32 302,24 305,15 C308,7 318,3 325,8 C332,13 331,23 324,26"
        fill="none" stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round"/>
  <!-- 琴体（两侧斜肩，镜像 0.000） -->
  <path d="M320,120 C323.3,121.5 328,120.8 339.8,129 C351.5,137.2 383.3,157.5 390.6,169.5 C397.9,181.5 385.7,189.5 383.5,201 C381.3,212.5 376.8,223.8 377.4,238.5 C377.9,253.2 380.8,272.5 386.7,289.5 C392.6,306.5 412.6,323.8 412.6,340.5 C412.6,357.2 397.5,378 386.7,390 C375.9,402 358.9,407.5 347.8,412.5 C336.7,417.5 324.6,418.8 320,420 M320,420 C315.4,418.8 303.3,417.5 292.2,412.5 C281.1,407.5 264.1,402 253.3,390 C242.5,378 227.4,357.2 227.4,340.5 C227.4,323.8 247.4,306.5 253.3,289.5 C259.2,272.5 262.1,253.2 262.6,238.5 C263.2,223.8 258.7,212.5 256.5,201 C254.3,189.5 242.1,181.5 249.4,169.5 C256.7,157.5 288.5,137.2 300.2,129 C312,120.8 316.7,121.5 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 平背折角（虚线） -->
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,132 L320,404"/>
    <path d="M290,240 L320,320"/><path d="M350,240 L320,320"/>
  </g>
  <!-- C 形音孔 -->
  <g stroke="#0E0E10" stroke-width="6.5" stroke-linecap="round" fill="none">
    <path d="M284,206 C270,232 270,266 284,292"/>
    <path d="M356,206 C370,232 370,266 356,292"/>
  </g>
  <!-- 琴桥与系弦板 -->
  <path d="M296,278 L344,278 L340,286 L300,286 Z" fill="#A9A49B"/>
  <path d="M304,310 L336,310 L331,382 L309,382 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <!-- 六根弦 -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,76 L310,312" stroke-width="1.5"/><path d="M314,76 L314,312" stroke-width="1.3"/>
    <path d="M318,76 L318,312" stroke-width="1.1"/><path d="M322,76 L322,312" stroke-width="1"/>
    <path d="M326,76 L326,312" stroke-width=".9"/><path d="M330,76 L330,312" stroke-width=".8"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L300,48"/><path d="M186,110 L298,112"/>
    <path d="M186,152 L242,152"/><path d="M186,230 L262,232"/>
    <path d="M186,290 L290,290"/><path d="M186,330 L298,332"/>
    <path d="M186,366 L302,368"/><path d="M186,300 L306,300"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="47" text-anchor="end">琴头常雕成人头或兽头</text>
    <text x="180" y="113" text-anchor="end">指板 · 六个弦轴</text>
    <text x="180" y="155" text-anchor="end" fill="#E8C547">七个品（可移动的肠弦）</text>
    <text x="180" y="233" text-anchor="end">斜肩（两侧）</text>
    <text x="180" y="293" text-anchor="end">C 形音孔（不是 f 孔）</text>
    <text x="180" y="333" text-anchor="end">琴桥</text>
    <text x="180" y="369" text-anchor="end">系弦板</text>
    <text x="180" y="303" text-anchor="end" fill="#9C7A3C">平背折角（在背侧）</text>
  </g>
  <text x="20" y="452" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">背板是平的（不拱），在靠上处折一个角 —— 与小提琴族、大提琴都不同。</text>
</svg>
```

三处与大提琴**正好相反**：

| | 维奥尔琴 | [[instrument:cello\|大提琴]] |
|---|---|---|
| 指板 | **有品**（7 个可移动的肠弦品） | 无品 |
| 背板 | **平的**，靠上处折角 | 拱形（与面板一样外凸） |
| 肩部 | **斜肩**（两侧都斜） | 圆肩 |
| 音孔 | **C 形**（少数用 f 形） | f 形 |
| 弦数 | **6**（法国后来加到 7） | 4 |
| 持弓 | **下握**（手心向上） | 正握（手心向下） |
| 音量 | 小（弓与弦都是低张力） | 大 |

还要加一句：**琴头常常雕成人头或兽头**，而不是小提琴那种涡卷 ——
这是它作为"上层家庭乐器"的一个外观印记。

## 有品 + 可移动：一件会调律的乐器

维奥尔的品不是金属，而是**缠绕在琴颈上的肠弦**，可以**上下移动**。

这一点比"有品"本身更重要。固定品只能给你十二平均律的格子；
而**可移动的品让演奏者能按需要的律制去摆** —— 文艺复兴的音乐在
**中庸律**（meantone）下才最协和，维奥尔琴因此可以"跟着律制走"。

```svg
<svg viewBox="0 0 640 330" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="维奥尔的七个品给出第一弦上的半音八度，下方是六根弦的四度夹三度定弦">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">七个品 = 第 1 弦上的一个半音八度；六根弦的定弦是四度夹三度</text>
  </g>
  <!-- 指板与品 -->
  <rect x="110" y="68" width="392" height="42" rx="3" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#E8C547" stroke-width="3">
    <path d="M155,68 L155,110"/><path d="M200,68 L200,110"/><path d="M245,68 L245,110"/>
    <path d="M290,68 L290,110"/><path d="M335,68 L335,110"/><path d="M380,68 L380,110"/>
    <path d="M425,68 L425,110"/>
  </g>
  <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
    <text x="131" y="134">空弦</text><text x="177" y="134">D♯</text><text x="222" y="134">E</text>
    <text x="267" y="134">F</text><text x="312" y="134">F♯</text><text x="357" y="134">G</text>
    <text x="402" y="134">G♯</text><text x="447" y="134">A</text>
  </g>
  <text x="510" y="100" font-size="11" fill="#E8C547">第 1 弦 D4</text>
  <text x="20" y="134" font-size="11" fill="#6E6A64">品的位置 →</text>
  <!-- 六根弦与定弦 -->
  <g stroke="#C9A227" stroke-width="3">
    <path d="M160,206 L160,268"/><path d="M230,206 L230,268"/><path d="M300,206 L300,268"/>
    <path d="M370,206 L370,268"/><path d="M440,206 L440,268"/><path d="M510,206 L510,268"/>
  </g>
  <g font-family="Georgia,serif" font-size="12" fill="#9C7A3C" text-anchor="middle">
    <text x="160" y="286">D2</text><text x="230" y="286">G2</text><text x="300" y="286">C3</text>
    <text x="370" y="286">E3</text><text x="440" y="286">A3</text><text x="510" y="286">D4</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="195" y="200">四度</text><text x="265" y="200">四度</text><text x="335" y="200" fill="#E8C547">三度</text>
    <text x="405" y="200">四度</text><text x="475" y="200">四度</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M160,190 L230,190"/><path d="M230,190 L300,190"/><path d="M300,190 L370,190"/>
    <path d="M370,190 L440,190"/><path d="M440,190 L510,190"/>
  </g>
  <text x="20" y="318" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">四度—四度—三度—四度—四度 —— 与鲁特琴同一套音程格局，所以两个曲目池可以互通。</text>
</svg>
```

这张图里有两个可引用的事实：

1. **七个品就是一个半音八度**。第 1 弦空弦是 D4，品到第七个正好是 **A4** ——
   所以低音维奥尔的音域可以用一句话说清：**D2（第 6 弦空弦）到 A4（第 1 弦第 7 品）**。
   这是一个自洽的、由结构直接推出来的音域，不是估计值。
2. **定弦的格局是「四度—四度—三度—四度—四度」**，中间那个三度让它
   **与[[instrument:lute|鲁特琴]]共用同一套音程逻辑**。所以 16–17 世纪的演奏者
   在鲁特琴与维奥尔之间转移是很自然的 —— 这也解释了两件乐器的曲目为什么互相流通。

## 音域

```range
{"range":"D2–A4","common":"D2–D4","caption":"低音维奥尔琴的音域（六弦 + 七个品）","caption_en":"Bass viol range — six strings plus seven frets","note":"最低的 D2 是第 6 弦空弦，最高的 A4 是第 1 弦第 7 品 —— 这两端正好是「六弦 + 七个品」能覆盖的全部范围。维奥尔琴是实音乐器，记谱音与实际音高相同。"}
```

两个半八度，比大提琴窄得多。但**窄在这里不是缺陷**：

- 维奥尔的音乐**以声部为单位**。它的本职是在合奏里唱**一条独立的声部**，
  而不是覆盖整个音域。
- **它天生适合和弦**。有品让左手可以同时按多个音而音准可靠，
  所以维奥尔的写法里大量出现**和弦与和声织体**（这一点更接近鲁特琴，而不是大提琴）。
- **它的高低两端都常用**。因为品把音高固定了，两端的发音都很稳 ——
  不像无品乐器那样在高把位变紧张。

当时的家庭配置是所谓**一箱维奥尔（chest of viols）**：
高音、次中音各一把、低音两把，正好组成一个重奏组 ——
这也是唱片与文献里最常见的那种编制。

## 音色与听辨

四条线索：

1. **音量小、衰减快、音色"轻而多色"**。弓与弦都是低张力，琴体又是轻结构 ——
   它进不了大音乐厅，但在小房间里色彩极为丰富。
2. **音头比小提琴族"软"**。下握的持弓方式（手心向上）让手指能**直接控制弓毛的张力**，
   所以极弱的地方可以做得非常细 —— 这是它"像说话"的声誉的来源。
3. **和弦听得出"一个一个音"**。有品让每个按下的音都干净利落，
   **按音与空弦的音色差别比小提琴族小得多**。
4. **揉弦曾是"装饰音"**。在维奥尔的演奏传统里，揉弦不是持续的美化手段，
   而是**偶尔用到的强调**。这与 20 世纪弦乐演奏的习惯正好相反 ——
   古乐运动今天就是在恢复这种"少揉弦"的做法。

```audiolab
{"type":"instrument","gm":"Cello","synth":"bowed","phrase":["D2","G2","C3","E3","A3","D4"],"label":"六根空弦：四度夹三度","label_en":"Six open strings — fourths with a third in the middle","hint":"⚠️ GM 音色表里没有维奥尔琴，这里借大提琴的采样；维奥尔更轻、更干、音量小得多，请按下握持弓、少揉弦的印象去听","hint_en":"The GM palette has no viol, so this borrows the cello; a viol is lighter, drier and far quieter — imagine an underhand bow and almost no vibrato."}
```

> 本页「在库中听例子」里的曲子是**同代曲目**（库内可确认为维奥尔琴的只有 BWV 1027），
> 详见页末说明。音色由上面的试听件负责。

## 演奏技法

维奥尔的右手与左手都有成套的规矩，与[[instrument:cello|大提琴]]互不通用：

**右手（下握）**

- **弓杆外凸**（向手心一侧弯），像一张弓 —— 与小提琴族的内凹弓相反。
- **手心向上握弓毛箱**（食指与拇指从下方夹住），
  好处是**手指能直接调节弓毛张力**，弱奏的控制力极强。
- **运弓以手腕与手指为主**，手臂的参与比现代弦乐少 —— 这决定了它的力度范围偏小。

**左手**

- **有品的按弦**：手指落在品上（不是品间），音高固定、清晰。
- **和弦与复调**：可以同时按出多个声部的音 —— 这是它作为室内乐乐器的核心能力。
- **不需要"找音"**：品让音准可靠，所以左手的注意力更多在**声部的独立**上。

**特殊技法（史料里有明确记载）**

- **拨弦（pizzicato）**：已经出现在 17 世纪的英国曲集里（Tobias Hume 还特意注明"用手指弹"）。
- **用弓杆敲弦（col legno）**：同一份史料里也有要求"用弓背敲"的地方。
- **里拉维奥尔（lyra viol）风格**：低音维奥尔的一种独奏写法 ——
  用**多种变格定弦（scordatura）**、大量和弦，以及一种叫 "thump" 的特殊拨弦，
  常记成符号谱（tablature）而不是五线谱。这是一整块独立的技法与曲库。

## 家族与近亲

维奥尔分**五个尺寸**，加上一个含糊的"维奥洛内（violone）"：

| 尺寸 | 大致音区 | 对等于 |
|---|---|---|
| 帕德苏斯（pardessus） | 最高 | （无对应，18 世纪法国出现） |
| 高音维奥尔 | 高 | [[instrument:violin\|小提琴]] |
| 中音维奥尔 | 中（较少见） | [[instrument:viola\|中提琴]] |
| 次中音维奥尔（A 调或 G 调） | 中低 | 介于中提琴与大提琴之间 |
| **低音维奥尔** | 低（最常用） | [[instrument:cello\|大提琴]] |
| 维奥洛内（violone） | 最低 | 低音区（术语用法不统一） |

**所有尺寸的持琴方式都一样**：夹在两腿之间、琴颈向上（gamba 就是意大利语的"腿"）。
这一点连最小的帕德苏斯也不例外 —— 与[[instrument:violin|小提琴]]族的"肩上"路线完全不同。

另一个亲缘关系常被搞混：**维奥尔与[[instrument:cello|大提琴]]不是同一条线**。
维奥尔的祖先是**维乌埃拉**（西班牙的拨弦乐器，见 [[instrument:lute|鲁特琴]] 一节），
琴型上更接近"给拨弦乐器加一把弓"；大提琴出自小提琴族。
两者在 16–17 世纪**同时存在、互相竞争**，最后大提琴胜出。

## 历史演变

| 时期 | 状态 |
|---|---|
| 15 世纪末 | 出现在**西班牙**（由维乌埃拉加上弓发展而来）；很快传到意大利与欧洲各地 |
| 16 世纪 | 成为**上层家庭的标配**：一箱维奥尔（高音、次中音 ×1、低音 ×2）组成重奏 |
| 17 世纪 | **英国**的维奥尔合奏曲（fantasia、In Nomine）达到高峰；**法国**的低音维奥尔独奏传统兴起 |
| 17 世纪末 | 法国把低音维奥尔加到 **7 根弦**（多加一根低音弦） |
| 18 世纪初 | 最后的黄金期：巴赫的《勃兰登堡协奏曲第六号》用了两把维奥尔琴；Abel 常被认为是最后一位伟大的维奥尔演奏者 |
| 18 世纪中后期 | **退出主流** —— 音乐厅变大，维奥尔的音量撑不住；大提琴胜出 |
| 20 世纪 | **古乐运动**把它复活：Dolmetsch 家族、1948 年成立的英国维奥尔琴协会 |
| 1991 年 | 电影《世界的每一个早晨》（Tous les matins du monde）以两位法国维奥尔演奏者为主角，把它带给了大众 |

**它为什么会被淘汰？** 答案很直接：**音量**。
18 世纪末公共音乐会成为常态，音乐厅越来越大，而维奥尔"弓与弦都是低张力"的
设计在结构上就注定它响不起来。这不是音乐水平的问题，是物理问题 ——
和 [[instrument:viola|中提琴]]"尺寸被人的身体限制"是同一种情形。

## 常见误解

- **"维奥尔琴是大提琴的前身。"** → **不是**。这是关于这件乐器最普遍的误解。
  它出自西班牙的维乌埃拉（拨弦乐器），大提琴出自小提琴族；
  两者**并行发展了两百多年**，大提琴是竞争者而不是后裔。
- **"有品就是音准更准。"** → 有品固定了音高，但它真正的好处是**可以移动** ——
  于是能按**中庸律**去摆，这才是文艺复兴音乐需要的。
  固定品（如现代吉他）反而做不到这一点。
- **"它的定弦和大提琴一样。"** → 定弦格局完全不同：维奥尔是**四度夹三度**（与鲁特琴同源），
  大提琴是**纯五度**（与小提琴族同源）。
- **"下握弓只是握法不同。"** → 它带来的是**完全不同的力度逻辑**：
  手指能直接控制弓毛张力，所以极弱奏的控制力极强，但整体音量上限低。
- **"它的音域窄所以更简单。"** → 音域窄，但**声部写作更复杂**。
  维奥尔的音乐以多声部线条为核心，读谱与分声部的难度不低于大提琴。
- **"揉弦是弦乐的基本功，自古如此。"** → 在维奥尔的传统里，揉弦是**偶尔使用的装饰**，
  不是持续的美化。今天古乐演奏者的"少揉弦"正是在恢复这一点。

## 下一步

到这里，**西洋弦乐（I1）14 条全部完成**。想继续看这条早期支系：
[[instrument:lute|鲁特琴]] 是它共享曲目的邻居（同一套音程格局），
[[instrument:cello|大提琴]] 是那个"胜出的竞争者"。
再往下就是本站的下一族 —— 木管。
:::

::: en
The viol is the [[instrument:cello|cello]]'s **contemporary, not its ancestor** — and that sentence
belongs at the top, because almost everyone gets it backwards.

It appeared in Spain late in the 15th century, became standard equipment in European households through
the 16th and 17th, and was pushed out of the mainstream by the violin family by the late 18th.
For two hundred years it existed **alongside** the cello.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Friction-excited (bowed) · **fretted**, necked, with a flat, folded back |
| **Family** | Western · Strings (early-instrument branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the viol is outside it |

## Structure: three things opposite to the cello

```svg
<svg viewBox="0 0 640 480" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bass viol parts: sloping shoulders, flat folded back, C-holes, seven gut frets, six strings and a carved head">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Bass viol — outer form and principal parts (sloping shoulders, flat folded back, seven frets)</text>
  </g>
  <path d="M308,74 L332,74 L338,206 L302,206 Z" fill="#0E0E10"/>
  <g stroke="#E8C547" stroke-width="2.4" opacity=".9">
    <path d="M304,96 L336,96"/><path d="M304,114 L336,114"/><path d="M304,132 L336,132"/>
    <path d="M305,150 L335,150"/><path d="M305,168 L335,168"/><path d="M305,186 L335,186"/>
    <path d="M306,204 L334,204"/>
  </g>
  <path d="M309,34 L331,34 L333,74 L307,74 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="291" y="40" width="16" height="5" rx="1"/><rect x="333" y="40" width="16" height="5" rx="1"/>
    <rect x="291" y="52" width="16" height="5" rx="1"/><rect x="333" y="52" width="16" height="5" rx="1"/>
    <rect x="291" y="64" width="16" height="5" rx="1"/><rect x="333" y="64" width="16" height="5" rx="1"/>
  </g>
  <path d="M320,32 C310,32 302,24 305,15 C308,7 318,3 325,8 C332,13 331,23 324,26"
        fill="none" stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round"/>
  <path d="M320,120 C323.3,121.5 328,120.8 339.8,129 C351.5,137.2 383.3,157.5 390.6,169.5 C397.9,181.5 385.7,189.5 383.5,201 C381.3,212.5 376.8,223.8 377.4,238.5 C377.9,253.2 380.8,272.5 386.7,289.5 C392.6,306.5 412.6,323.8 412.6,340.5 C412.6,357.2 397.5,378 386.7,390 C375.9,402 358.9,407.5 347.8,412.5 C336.7,417.5 324.6,418.8 320,420 M320,420 C315.4,418.8 303.3,417.5 292.2,412.5 C281.1,407.5 264.1,402 253.3,390 C242.5,378 227.4,357.2 227.4,340.5 C227.4,323.8 247.4,306.5 253.3,289.5 C259.2,272.5 262.1,253.2 262.6,238.5 C263.2,223.8 258.7,212.5 256.5,201 C254.3,189.5 242.1,181.5 249.4,169.5 C256.7,157.5 288.5,137.2 300.2,129 C312,120.8 316.7,121.5 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,132 L320,404"/>
    <path d="M290,240 L320,320"/><path d="M350,240 L320,320"/>
  </g>
  <g stroke="#0E0E10" stroke-width="6.5" stroke-linecap="round" fill="none">
    <path d="M284,206 C270,232 270,266 284,292"/>
    <path d="M356,206 C370,232 370,266 356,292"/>
  </g>
  <path d="M296,278 L344,278 L340,286 L300,286 Z" fill="#A9A49B"/>
  <path d="M304,310 L336,310 L331,382 L309,382 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,76 L310,312" stroke-width="1.5"/><path d="M314,76 L314,312" stroke-width="1.3"/>
    <path d="M318,76 L318,312" stroke-width="1.1"/><path d="M322,76 L322,312" stroke-width="1"/>
    <path d="M326,76 L326,312" stroke-width=".9"/><path d="M330,76 L330,312" stroke-width=".8"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L300,48"/><path d="M186,110 L298,112"/>
    <path d="M186,152 L242,152"/><path d="M186,230 L262,232"/>
    <path d="M186,290 L290,290"/><path d="M186,330 L298,332"/>
    <path d="M186,366 L302,368"/><path d="M186,300 L306,300"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="47" text-anchor="end">Carved head, not a scroll</text>
    <text x="180" y="113" text-anchor="end">Fingerboard · six tuning pegs</text>
    <text x="180" y="155" text-anchor="end" fill="#E8C547">Seven frets (movable gut)</text>
    <text x="180" y="233" text-anchor="end">Sloping shoulders (both sides)</text>
    <text x="180" y="293" text-anchor="end">C-holes (not f-holes)</text>
    <text x="180" y="333" text-anchor="end">Bridge</text>
    <text x="180" y="369" text-anchor="end">Tailpiece</text>
    <text x="180" y="303" text-anchor="end" fill="#9C7A3C">Flat folded back</text>
  </g>
  <text x="20" y="452" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The back is flat — not arched — with a fold near the top. Unlike a cello, unlike a violin.</text>
</svg>
```

Three deliberate opposites to the cello:

| | Viol | [[instrument:cello\|Cello]] |
|---|---|---|
| Fingerboard | **fretted** (seven movable gut frets) | unfretted |
| Back | **flat**, with a fold near the top | arched (like the top) |
| Shoulders | **sloping** (both sides) | rounded |
| Soundholes | **C-shaped** (occasionally f) | f-shaped |
| Strings | **six** (seven in later French instruments) | four |
| Bow grip | **underhand** (palm up) | overhand (palm down) |
| Volume | small (low tension in bow and strings) | large |

One more detail: **the head is usually carved as a human or animal figure**, not a scroll —
a visible mark of an instrument made for well-off households.

## Frets you can move: an instrument that adjusts its temperament

The frets are not metal but **gut tied around the neck**, and they can be **slid up and down**.

That matters more than the frets themselves. Fixed frets give you the twelve-tone grid; **movable frets
let the player set the instrument to the temperament the music needs** — and Renaissance music is most
consonant in **meantone**, which a viol can therefore adopt.

```svg
<svg viewBox="0 0 640 346" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The viol's seven frets give a chromatic octave on the first string; below, the six strings tuned in fourths with a third in the middle">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Seven frets = one chromatic octave on the first string; the six strings are tuned in fourths with a third</text>
  </g>
  <rect x="110" y="68" width="392" height="42" rx="3" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#E8C547" stroke-width="3">
    <path d="M155,68 L155,110"/><path d="M200,68 L200,110"/><path d="M245,68 L245,110"/>
    <path d="M290,68 L290,110"/><path d="M335,68 L335,110"/><path d="M380,68 L380,110"/>
    <path d="M425,68 L425,110"/>
  </g>
  <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
    <text x="131" y="134">open</text><text x="177" y="134">D♯</text><text x="222" y="134">E</text>
    <text x="267" y="134">F</text><text x="312" y="134">F♯</text><text x="357" y="134">G</text>
    <text x="402" y="134">G♯</text><text x="447" y="134">A</text>
  </g>
  <text x="510" y="100" font-size="11" fill="#E8C547">1st string D4</text>
  <g stroke="#C9A227" stroke-width="3">
    <path d="M160,206 L160,268"/><path d="M230,206 L230,268"/><path d="M300,206 L300,268"/>
    <path d="M370,206 L370,268"/><path d="M440,206 L440,268"/><path d="M510,206 L510,268"/>
  </g>
  <g font-family="Georgia,serif" font-size="12" fill="#9C7A3C" text-anchor="middle">
    <text x="160" y="286">D2</text><text x="230" y="286">G2</text><text x="300" y="286">C3</text>
    <text x="370" y="286">E3</text><text x="440" y="286">A3</text><text x="510" y="286">D4</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M160,190 L230,190"/><path d="M230,190 L300,190"/><path d="M300,190 L370,190"/>
    <path d="M370,190 L440,190"/><path d="M440,190 L510,190"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="195" y="184">4th</text><text x="265" y="184">4th</text><text x="335" y="184" fill="#E8C547">3rd</text>
    <text x="405" y="184">4th</text><text x="475" y="184">4th</text>
  </g>
  <text x="20" y="314" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Fourth–fourth–third–fourth–fourth — the lute's interval pattern,</text>
  <text x="20" y="330" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">which is why the two repertoires flowed into each other.</text>
</svg>
```

Two quotable facts come out of that diagram:

1. **Seven frets make exactly one chromatic octave.** The first string's open note is D4 and the seventh
   fret gives **A4** — so the bass viol's range can be stated in one line: **D2 (open sixth string) to
   A4 (seventh fret of the first string)**. That range is derived from the structure, not estimated.
2. **The tuning pattern is fourth–fourth–third–fourth–fourth**, and the third in the middle means it
   **shares its interval logic with the [[instrument:lute|lute]]**. Players of the period moved between
   lute and viol easily — which is why the two repertoires cross-fed each other.

## Range

```range
{"range":"D2–A4","common":"D2–D4","caption":"低音维奥尔琴的音域（六弦 + 七个品）","caption_en":"Bass viol range — six strings plus seven frets","note":"最低的 D2 是第 6 弦空弦，最高的 A4 是第 1 弦第 7 品 —— 这两端正好是「六弦 + 七个品」能覆盖的全部范围。维奥尔琴是实音乐器，记谱音与实际音高相同。"}
```

Two and a half octaves — far narrower than a cello. But **narrow is not inferior here**:

- Viol music is **written by voice**. Its job is to sing **one independent part** in an ensemble, not to
  span a whole range.
- **It is naturally chordal.** Frets let the left hand stop several strings with reliable intonation, so
  viol writing is full of **chords and contrapuntal textures** — closer to a lute than to a cello.
- **Both ends are in regular use**, because frets keep the pitch stable at either extreme.

A household set was a **"chest of viols"**: one treble, one or two tenors and two basses — the
combination heard most often on recordings and in the sources.

## Timbre, and how to hear it

Four cues:

1. **Quiet, fast-decaying, light and many-coloured.** Low tension in bow and strings, plus a light
   build: it cannot fill a concert hall, but in a room it is remarkably colourful.
2. **A softer attack than the violin family.** The underhand grip (palm up) lets the fingers **control
   bow-hair tension directly**, so the softest dynamics are exquisitely shaped — the origin of its
   "speaking" reputation.
3. **Chords are heard one note at a time.** Frets make every stopped note clean, and the difference in
   colour between stopped and open strings is much smaller than in the violin family.
4. **Vibrato was an ornament.** In the viol tradition vibrato was an **occasional emphasis**, not a
   continuous beautifying device — the opposite of 20th-century string playing. Today's early-music players are
   restoring the older practice.

```audiolab
{"type":"instrument","gm":"Cello","synth":"bowed","phrase":["D2","G2","C3","E3","A3","D4"],"label":"六根空弦：四度夹三度","label_en":"Six open strings — fourths with a third in the middle","hint":"⚠️ GM 音色表里没有维奥尔琴，这里借大提琴的采样；维奥尔更轻、更干、音量小得多，请按下握持弓、少揉弦的印象去听","hint_en":"The GM palette has no viol, so this borrows the cello; a viol is lighter, drier and far quieter — imagine an underhand bow and almost no vibrato."}
```

> The tracks under “Listen in the library” are **music of the same period** (only BWV 1027 can be
> confirmed as viol music in the library) — see the note below. Timbre comes from the player above.

## Playing techniques

The viol's right and left hands follow rules that do **not** transfer to a [[instrument:cello|cello]]:

**Right hand (underhand)**

- **The bow stick is convex** (bending towards the palm) — the opposite of the violin family's concave stick,
  and shaped like an archer's bow.
- **Palm up, gripping the frog from below** (thumb and index underneath). The advantage is that the fingers
  can **adjust hair tension directly**, giving extraordinary control at low volume.
- **The stroke comes mostly from wrist and fingers**, with less arm than modern strings — which is why its
  dynamic ceiling is low.

**Left hand**

- **Frets are stopped on, not between**: pitch is fixed and clear.
- **Chords and polyphony**: several voices can sound at once — the core skill for a chamber instrument.
- **No hunting for pitch**: frets make intonation reliable, so the left hand concentrates on **keeping
  voices independent**.

**Documented special techniques**

- **Pizzicato**: already present in 17th-century English collections (Tobias Hume explicitly writes "play
  with your finger").
- **Col legno**: the same sources ask for "drum this with the back of your bow".
- **Lyra viol style**: a solo idiom for the bass viol using **many scordatura tunings**, heavy chordal
  writing and a special pizzicato called a "thump" — often written in tablature. A whole separate
  technique and repertoire.

## The family

The viol comes in **five sizes**, plus the ambiguous "violone":

| Size | Register | Counterpart |
|---|---|---|
| Pardessus | highest | (none — a French 18th-century speciality) |
| Treble viol | high | [[instrument:violin\|violin]] |
| Alto viol | middle (rare) | [[instrument:viola\|viola]] |
| Tenor viol (in A or G) | low middle | between viola and cello |
| **Bass viol** | low (the workhorse) | [[instrument:cello\|cello]] |
| Violone | lowest | the bass register (terminology is inconsistent) |

**Every size is held the same way**: upright between the legs with the neck rising — *gamba* is Italian
for "leg". Even the tiny pardessus. That is a completely different route from the
[[instrument:violin|violin]] family's shoulder hold.

One kinship that is often confused: **the viol and the [[instrument:cello|cello]] are not the same line.**
The viol descends from the **vihuela** (a Spanish plucked instrument — see [[instrument:lute|lute]]);
structurally it is "a plucked instrument given a bow". The cello comes out of the violin family. The two
**coexisted and competed** through the 16th and 17th centuries, and the cello won.

## History

| Period | State |
|---|---|
| Late 15th c. | appears in **Spain** (vihuela plus a bow); spreads quickly to Italy and across Europe |
| 16th c. | becomes **standard in wealthy households**: a chest of viols (treble, tenor(s), two basses) |
| 17th c. | **England** peaks in viol consort music (fantasias, In Nomine); **France** develops the bass viol solo tradition |
| Late 17th c. | French makers add a **seventh string** to the bass viol |
| Early 18th c. | a last golden age: Bach's Brandenburg Concerto No. 6 uses two viole da gamba; Abel is often called the last great gambist |
| Mid–late 18th c. | **leaves the mainstream** — halls grew, the viol could not fill them; the cello won |
| 20th c. | **the early-music revival** brings it back: the Dolmetsch family, and the Viola da Gamba Society founded in Britain in 1948 |
| 1991 | the film *Tous les matins du monde*, about two French viol players, brought it to a wide audience |

**Why did it lose?** The answer is blunt: **volume**. When public concerts became the norm at the end of
the 18th century and halls grew larger, an instrument designed with low tension in bow and strings simply
could not compete. That is a physical limit, not an artistic verdict — the same kind of story as the
[[instrument:viola|viola]]'s size being limited by the player's body.

## Common misconceptions

- **"The viol is the ancestor of the cello."** It is **not** — the most widespread error about this
  instrument. It descends from the Spanish vihuela; the cello descends from the violin family. They
  **developed in parallel for two centuries**, and the cello was a competitor, not a descendant.
- **"Frets mean better intonation."** Frets fix the pitches, but their real advantage is that they are
  **movable** — so the instrument can be set to **meantone**, which is what Renaissance music wants.
  Fixed frets (as on a modern guitar) cannot do that.
- **"It is tuned like a cello."** The pattern is completely different: **fourths with a third** (shared
  with the lute), against the cello's **perfect fifths** (shared with the violin family).
- **"The underhand grip is just a different hold."** It brings a **different dynamic logic**: fingers
  control hair tension directly, so the softest playing is superb while the ceiling is low.
- **"A narrow range makes it simpler."** Narrow, but the **part-writing is more complex**. Viol music is
  built on independent voices; reading and balancing them is no easier than a cello.
- **"Vibrato has always been basic string technique."** In the viol tradition it was **an occasional
  ornament**, not continuous beautifying. Today's early-music players are restoring that.

## Next

With this entry, **all 14 entries of I1 (Western strings) are complete**. To keep following the early
branch: the [[instrument:lute|lute]] shares its repertoire and its interval pattern, and the
[[instrument:cello|cello]] is the competitor that won. Next on this site comes the woodwind family.
:::
