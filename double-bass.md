---
id: double-bass
site: inst
cat: I1
title: 低音提琴
title_en: Double Bass
summary: 弦乐家族里最大最低的一件，斜肩、四度定弦，记谱比实音高一个八度
summary_en: The largest and lowest of the string family — sloped shoulders, fourths tuning, and written an octave above sounding pitch
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [低音提琴, double bass, contrabass, 倍大提琴, 贝斯, bass]
order: 13
links:
  - "[[concept:register]]"
  - "[[concept:clef]]"
  - "[[concept:concert-pitch]]"
  - "[[concept:interval]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:violin]]"
  - "[[instrument:viola]]"
  - "[[instrument:cello]]"
instances:
  - pdmx-000801 | 低音提琴协奏曲（Dragonetti 名下）—— 把低音乐器当独奏主角写的作品，最能听出它在高把位也能唱
  - pdmx-002098 | 同一作曲家的另一部低音提琴协奏曲，可对照它的快速乐句与换把
  - giantmidi-009130 | 低音提琴与钢琴小品三首 —— 有伴奏的情境，便于听它在合奏里如何"垫住"和声
  - pdmx-001539 | Bottesini 的《遐想》—— 低音提琴独奏传统的源头人物留下的作品
sources:
  - "https://getd.libs.uga.edu/pdfs/amaral_claudia_s_201805_dma.pdf"
  - "https://www.vsl.co.at/academy/strings/double-bass"
  - 琴体尺寸取通行制琴数据：低音提琴（3/4 尺寸，乐队最常用）琴体长约 1,070 毫米、弦长约 1,050 毫米
  - 定弦 E–A–D–G（纯四度）与"记谱比实音高一个八度"属通行乐器学常识，各版乐器词典表述一致
  - 全音指距的换算依弦长与频率关系逐条计算（小提琴 328 毫米得约 36 毫米、大提琴 690 毫米得约 75 毫米、低音提琴 1,050 毫米得约 115 毫米）
  - 血统上出自低音维奥尔（violone）而非小提琴家族的放大、以及德式与法式两种握弓，依通行乐器史叙述
  - ⚠️ 库内标题或作曲家明确指向低音提琴的曲目只找到 4 首，本条已全部列出（数据集覆盖限制，非本条取舍）
updated: 2026-11-02
---

::: zh
低音提琴是弦乐家族里的**最后一件、也是最大的一件**：琴体长 1,070 毫米，
弦长 1,050 毫米 —— 站着拉，或者坐在高凳上拉。

它同时是家族里**最不合群**的一件。别的小提琴族乐器都按同一套规则做：
对称的圆肩、五度定弦、按实音记谱。低音提琴三样都改了：

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 摩擦激励（用弓擦弦）· 有颈、有板腔共鸣箱 |
| **所属族** | 西洋 · 弦乐 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，低音提琴不在其中 |

## 结构：三处与众不同的地方

```svg
<svg viewBox="0 0 640 500" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="低音提琴外形与主要部件：斜肩、齿轮式弦轴、较短的指板、宽弦距的弦、f 孔、琴桥、系弦板、尾柱与地板">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">低音提琴 · 外形与主要部件（不同型号肩形不同）</text>
  </g>
  <!-- 指板（相对琴体显得短） -->
  <path d="M304,100 L336,100 L346,268 L294,268 Z" fill="#0E0E10"/>
  <!-- 琴头与弦轴 -->
  <path d="M304,58 L336,58 L338,100 L302,100 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,56 C308,56 300,46 305,35 C309,25 322,21 331,27 C339,33 338,45 328,48 C321,50 316,46 317,40"
        fill="none" stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="282" y="64" width="18" height="7" rx="1"/><rect x="336" y="64" width="18" height="7" rx="1"/>
    <rect x="284" y="82" width="16" height="7" rx="1"/><rect x="336" y="82" width="16" height="7" rx="1"/>
  </g>
  <!-- 琴体（斜肩：左肩斜坡） -->
  <path d="M320,140 C326.7,141.3 350.3,143.9 360.3,147.8 C370.3,151.7 373.6,154.3 380.3,163.4 C386.9,172.5 403.3,188.1 400.4,202.4 C397.4,216.7 362.5,234.5 362.5,249.2 C362.5,263.9 394.1,277.8 400.4,290.8 C406.7,303.8 400.4,314.2 400.4,327.2 C400.4,340.2 407.7,358.2 400.4,368.8 C393,379.4 369.8,385.7 356.4,390.9 C343,396.1 326.1,398.5 320,400 M320,400 C313.9,398.5 297,396.1 283.6,390.9 C270.2,385.7 247,379.4 239.6,368.8 C232.3,358.2 239.6,340.2 239.6,327.2 C239.6,314.2 233.3,303.8 239.6,290.8 C245.9,277.8 273.1,262.8 277.5,249.2 C281.8,235.6 268.7,220.2 265.8,208.9 C262.8,197.6 253.7,191.8 259.7,181.6 C265.8,171.4 291.9,154.7 301.9,147.8 C312,140.9 317,141.3 320,140 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- f 孔 -->
  <g stroke="#0E0E10" stroke-width="7.5" stroke-linecap="round" fill="none">
    <path d="M285,208 C276,234 294,266 285,292"/>
    <path d="M355,208 C364,234 346,266 355,292"/>
  </g>
  <!-- 琴桥 -->
  <path d="M292,272 L348,272 L344,280 L296,280 Z" fill="#A9A49B"/>
  <!-- 系弦板 -->
  <path d="M306,320 L334,320 L328,384 L312,384 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <!-- 尾柱与地板 -->
  <g stroke="#A9A49B" stroke-width="2.8" stroke-linecap="round">
    <path d="M320,402 L320,458"/>
  </g>
  <path d="M312,458 L328,458 L320,472 Z" fill="#A9A49B"/>
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M170,478 L470,478"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,484 L174,492"/><path d="M220,484 L214,492"/><path d="M260,484 L254,492"/>
    <path d="M300,484 L294,492"/><path d="M340,484 L334,492"/><path d="M380,484 L374,492"/>
    <path d="M420,484 L414,492"/><path d="M460,484 L454,492"/>
  </g>
  <!-- 四根弦（弦距更宽） -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M308,102 L308,326" stroke-width="1.7"/>
    <path d="M316,102 L316,326" stroke-width="1.3"/>
    <path d="M324,102 L324,326" stroke-width="1"/>
    <path d="M332,102 L332,326" stroke-width=".8"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M528,40 L340,50"/><path d="M486,62 L340,64"/><path d="M186,124 L300,126"/>
    <path d="M186,166 L268,164"/><path d="M186,214 L272,216"/><path d="M186,300 L272,300"/>
    <path d="M566,274 L350,274"/><path d="M496,314 L392,314"/><path d="M542,350 L340,348"/>
    <path d="M186,430 L310,432"/><path d="M186,478 L164,478"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="43" text-anchor="end">琴头（更大）</text>
    <text x="600" y="65" text-anchor="end">弦轴 · 齿轮式</text>
    <text x="180" y="127" text-anchor="end">指板（相对琴体偏短）</text>
    <text x="180" y="169" text-anchor="end" fill="#9C7A3C">肩部（有斜肩与圆肩形制）</text>
    <text x="180" y="217" text-anchor="end">f 孔（更长）</text>
    <text x="180" y="303" text-anchor="end">下琴腰</text>
    <text x="610" y="277" text-anchor="end">琴桥</text>
    <text x="610" y="317" text-anchor="end">面板（云杉）</text>
    <text x="610" y="353" text-anchor="end">系弦板</text>
    <text x="180" y="433" text-anchor="end">尾柱（低音提琴必需）</text>
    <text x="610" y="467" text-anchor="end">地板</text>
  </g>
  <text x="20" y="496" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">琴体约 1,070 mm、弦长约 1,050 mm —— 站着演奏，靠尾柱支撑。</text>
</svg>
```

1. 琴体有斜肩、圆肩等不同形制，不能概括为“只有左肩削坡、右肩仍圆”。
2. 齿轮弦轴便于精细调节较粗的琴弦，现代低音提琴普遍使用。
3. 指板、弦长和琴体尺寸随型号而变；弦长与琴体长的比值不能直接说明指板长度。

## 为什么改成四度定弦

这是低音提琴最常被问到的一件事。答案不在音乐上，在手上。

三件家族的弦长差得很远：小提琴 328 毫米、大提琴 690 毫米、低音提琴 1,050 毫米。
弦长决定了一件事 —— 同一个音程，需要把手伸多远。按弦长与频率的关系，
一个全音（两个半音）在三种弦长上的落点分别是：

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="小提琴、大提琴、低音提琴的弦长与全音指距对比：弦长越长，同一个音程需要伸得越远">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一个「全音」，在三种弦长上要伸多远（同一比例尺）</text>
  </g>
  <!-- 小提琴 -->
  <text x="20" y="60">小提琴 · 弦长 328 mm</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,74 L224,74"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,66 L60,82"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M78,66 L78,82"/>
  </g>
  <text x="86" y="70" fill="#9C7A3C" font-size="11">全音 = 36 mm</text>
  <!-- 大提琴 -->
  <text x="20" y="132">大提琴 · 弦长 690 mm</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,146 L405,146"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,138 L60,154"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M97.5,138 L97.5,154"/>
  </g>
  <text x="106" y="142" fill="#9C7A3C" font-size="11">全音 = 75 mm</text>
  <!-- 低音提琴 -->
  <text x="20" y="204">低音提琴 · 弦长 1,050 mm</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,218 L585,218"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,210 L60,226"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M117.5,210 L117.5,226"/>
  </g>
  <text x="126" y="214" fill="#9C7A3C" font-size="11">全音 = 115 mm</text>
  <!-- 说明 -->
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M60,232 L60,262"/>
  </g>
  <text x="196" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">1 - 2 - 4 三指法（跳过第三指）</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">115 mm 是从空弦上端到升全音落点的距离，不是相邻两指的最小间距。</text>
</svg>
```

以空弦为起点，在十二平均律下把音升全音，需要缩短约 10.9% 的振动弦长；328 mm、690 mm、1,050 mm 的弦长，分别对应约 36、75、115 mm。这是空弦到高全音落点的距离，不是每一对相邻手指的最小间距。越到高把位，相同音程所需的距离越短。

- 常见四度定弦为 E1–A1–D2–G2，有助于在较长弦上组织指法与跨弦取音。
- 低把位常用 1–2–4，第三指可协助第四指，不能说第三指在整件乐器上被废弃；高把位、拇指把位还有其他指法。

所以低音提琴的左手不是在"按音"，而是在频繁换把：它靠移动整只手来覆盖音程，
而不是靠手指伸展。听低音提琴的快速乐句时，那种略带"滑动"的连贯感就来自这里。

## 音域

```range
{"range":"E1–G4","written":"E2–G5","common":"E1–C3","caption":"低音提琴的记谱音域与实音音域","caption_en":"The double bass: notated range above, sounding range below","note":"⚠️ 低音提琴是移调乐器 —— 记谱比实音高一个八度。上面一行是记谱，下面一行是实际听到的音高。"}
```

三个八度多一点。注意音域图上的两行：低音提琴是家族里唯一按移调记谱的成员 ——
乐谱上写的 E2，实际响的是 E1。这样处理的原因很实际：如果把实音直接写进低音谱号，
大量音符会掉到五线谱以下，加线画不过来。

标准四弦最低音 E1 约为 41.2 Hz，仍有明确音高。五弦或低音延伸装置可到 C1 甚至 B0；耳朵还会利用上方分音辨认低音音高，不能把 20–40 Hz 一概当成“只能感觉、没有音高”的区域。

| 弦 | 空弦音 | 音色 |
|---|---|---|
| E 弦 | E1 | 最低的标准空弦，具有明确音高与厚实低频 |
| A 弦 | A1 | 厚，乐队最常用的低音区 |
| D 弦 | D2 | 清楚，低音线条的主力 |
| G 弦 | G2 | 最明亮，爵士独奏常在这根弦上爬高 |

谱号用低音谱号。高把位时会改用[[concept:clef|高音谱号]]，
这时记谱与实音的八度关系仍然不变。

## 音色与听辨

低音提琴的听辨要点，与家族里其他三件不一样：

1. 低音区既有厚度，也有可辨认的音高；上方分音帮助耳朵识别最低弦的音高。
2. D 弦、G 弦和更高把位适合旋律与独奏，音色与低音伴奏有所区别。
3. 拨弦通常有清楚音头并逐渐衰减，拉弓可以维持音量与连贯长线条；爵士与管弦乐都可按作品需要使用两种方法。

下面的试听按 E1、A1、D2、G2 播放四根空弦，比较音区上移时的音高、音头与余响变化。

```audiolab
{"type":"instrument","gm":"Contrabass","synth":"bowed","phrase":["E1","A1","D2","G2"],"label":"四根空弦：从 E 弦到 G 弦","label_en":"Four open strings — E up to G","hint":"注意 E1 更像分量、G2 才像音；也注意四度定弦的音程比小提琴的窄","hint_en":"Hear how E1 reads as weight rather than pitch, and how G2 turns into a real note — then note the fourths between them."}
```

> 「在库中听例子」里的曲子是乐谱与演奏的骨架（转写或雕版 MIDI），
> 音色由上面的试听件负责。另外说明一句：库内标题或作曲家明确指向低音提琴的曲目只有 4 首，
> 已全部列出 —— 这是数据集本身的覆盖限制，不是这一条的取舍。

## 演奏技法

低音提琴的右手有两套握弓法，这是家族里独一无二的：

- 法式弓（正握）：手心向下，与大提琴的法式弓同构。
- 德式弓（下握）：手心向上、托住弓毛箱，是低音维奥尔留下的老传统。

两派各自成体系（配重、手腕动作、跳弓做法都不同），职业乐手里两派并存到今天。

左手方面，上一节已经说明了核心：1-2-4 三指法 + 频繁换把。
其余技法与家族共通，但有几件在低音提琴上要单独练：

- 拨弦（pizzicato）：弦粗、张力大，拨弦要用整个手指甚至手掌带动。
  在爵士里它是独奏语言（走路低音、双音、击弦），不是装饰。
- 泛音：弦越长，泛音点分得越开，也越容易做 —— 低音提琴的自然泛音比小提琴更容易听清。
- 弓毛张力：因为弦粗，需要更大的压力；但压力过大会"压死"弦，反而发不出泛音。
  控制这条线是低音提琴右手最难的部分。
- 持琴与尾柱：绝大多数低音提琴用尾柱支撑，但也有人（尤其爵士与民谣）用侧板支撑，
  靠身体夹住琴身拨弦 —— 形态与音色都随之改变。

## 家族与近亲

低音提琴的形制历史涉及维奥尔与小提琴两类传统，不宜用单一路径概括为“完全来自低音维奥尔”。今天的四度定弦、不同肩形、背板与两类弓形应分别说明；violone 在历史上也并不始终指同一种乐器。

| 特征 | 小提琴、中提琴、大提琴的常见做法 | 低音提琴的常见做法 |
|---|---|---|
| 定弦 | 五度 | 四度 |
| 普通记谱 | 实音 | 高八度记谱 |
| 肩形与背板 | 通常圆肩、拱背 | 肩形与平背/拱背随型号而变 |
| 弓形 | 各有相应弓形 | 法式与德式并用 |

| 乐器 | 琴体长约 | 弦长约 | 定弦（低→高） | 实音音域 |
|---|---|---|---|---|
| [[instrument:violin\|小提琴]] | 356 毫米 | 328 毫米 | G3 D4 A4 E5 | G3–E7 |
| [[instrument:viola\|中提琴]] | 410 毫米 | 370 毫米 | C3 G3 D4 A4 | C3–E6 |
| [[instrument:cello\|大提琴]] | 760 毫米 | 690 毫米 | C2 G2 D3 A3 | C2–C6 |
| **低音提琴** | 1,070 毫米 | 1,050 毫米 | E1 A1 D2 G2 | E1–G4 |

所以最准确的说法是：它们是一家人，但低音提琴是带着旧姓过继过来的那一个。

## 历史演变

16 世纪以来，欧洲低音拉弦乐器的尺寸、弦数、定弦和名称曾并存多种做法，逐步形成今天的低音提琴。不能把这些变化写成某一代乐器完整保留另一代的唯一规则。

18 世纪的低音提琴通常只有三根弦（A1、D2、G2）。第四根弦（E1）是后来才普遍加上的 ——
加上之后它才真正具备了管弦乐低音声部所需的深度。Dragonetti 是这一时期的代表人物：
他的技巧与作品让低音提琴在 18 世纪末第一次被当作独奏乐器看待。

19 世纪的 Bottesini 做了 Dragonetti 那件工作的大提琴版 ——
他被称为"低音提琴的帕格尼尼"，把独奏技巧推到极致，也留下了协奏曲与小品。
低音提琴的独奏传统基本上是这一条线。

20 世纪它分成了两个舞台：管弦乐里的低音声部（弓、长音、地基）
与爵士里的拨弦乐器（走路低音、即兴、独奏）。
同一件乐器在两个舞台上几乎是两种不同的演奏法 —— 这一点在家族里也是独一份。

## 常见误解

- 低音提琴不是简单放大的大提琴，历史形制、常见四度定弦与移调记谱都有区别。
- 低音的音高由弦长、张力和单位长度质量共同决定：f = (1/2L)√(T/μ)，不能说弦粗细与张力只是次要配套。
- 四度定弦有助于指法安排，但跨弦的横向距离来自弦距，并非相邻空弦是四度还是五度。
- 1–2–4 是常见低把位方案；换把、拇指把位与其他指法共同覆盖更宽的音域。

## 下一步

到这里，西洋弦乐四件套就齐了。想回看对照，
[[instrument:violin|小提琴]] 一节给出的是家族共同的形状与工艺，
[[instrument:viola|中提琴]] 是"尺寸被迫妥协"的故事，这一条是"人改规则"的故事 ——
三页合起来能看清一件事：乐器的形态是声学需求与人的身体讨价还价的结果。

:::

::: en
The double bass is the **last and largest** member of the string family: a body around 1,070 mm,
a string length around 1,050 mm — played standing up or from a high stool.

It is also the family's **odd one out**. Every other violin-family instrument follows one set of rules:
symmetrical round shoulders, fifths tuning, and notation at sounding pitch. The double bass breaks all
three:

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Friction-excited (bowed) · necked, with a box resonator |
| **Family** | Western · Strings |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the double bass is outside it |

## Structure: three departures from the family

```svg
<svg viewBox="0 0 640 500" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Double bass parts: sloped shoulder, machine tuning gears, a comparatively short fingerboard, wide string spacing, f-holes, bridge, tailpiece, endpin and floor">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Double bass — principal parts (shoulder shapes vary)</text>
  </g>
  <path d="M304,100 L336,100 L346,268 L294,268 Z" fill="#0E0E10"/>
  <path d="M304,58 L336,58 L338,100 L302,100 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,56 C308,56 300,46 305,35 C309,25 322,21 331,27 C339,33 338,45 328,48 C321,50 316,46 317,40"
        fill="none" stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="282" y="64" width="18" height="7" rx="1"/><rect x="336" y="64" width="18" height="7" rx="1"/>
    <rect x="284" y="82" width="16" height="7" rx="1"/><rect x="336" y="82" width="16" height="7" rx="1"/>
  </g>
  <path d="M320,140 C326.7,141.3 350.3,143.9 360.3,147.8 C370.3,151.7 373.6,154.3 380.3,163.4 C386.9,172.5 403.3,188.1 400.4,202.4 C397.4,216.7 362.5,234.5 362.5,249.2 C362.5,263.9 394.1,277.8 400.4,290.8 C406.7,303.8 400.4,314.2 400.4,327.2 C400.4,340.2 407.7,358.2 400.4,368.8 C393,379.4 369.8,385.7 356.4,390.9 C343,396.1 326.1,398.5 320,400 M320,400 C313.9,398.5 297,396.1 283.6,390.9 C270.2,385.7 247,379.4 239.6,368.8 C232.3,358.2 239.6,340.2 239.6,327.2 C239.6,314.2 233.3,303.8 239.6,290.8 C245.9,277.8 273.1,262.8 277.5,249.2 C281.8,235.6 268.7,220.2 265.8,208.9 C262.8,197.6 253.7,191.8 259.7,181.6 C265.8,171.4 291.9,154.7 301.9,147.8 C312,140.9 317,141.3 320,140 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#0E0E10" stroke-width="7.5" stroke-linecap="round" fill="none">
    <path d="M285,208 C276,234 294,266 285,292"/>
    <path d="M355,208 C364,234 346,266 355,292"/>
  </g>
  <path d="M292,272 L348,272 L344,280 L296,280 Z" fill="#A9A49B"/>
  <path d="M306,320 L334,320 L328,384 L312,384 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <g stroke="#A9A49B" stroke-width="2.8" stroke-linecap="round">
    <path d="M320,402 L320,458"/>
  </g>
  <path d="M312,458 L328,458 L320,472 Z" fill="#A9A49B"/>
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M170,478 L470,478"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,484 L174,492"/><path d="M220,484 L214,492"/><path d="M260,484 L254,492"/>
    <path d="M300,484 L294,492"/><path d="M340,484 L334,492"/><path d="M380,484 L374,492"/>
    <path d="M420,484 L414,492"/><path d="M460,484 L454,492"/>
  </g>
  <g stroke="#C9A227" opacity=".85">
    <path d="M308,102 L308,326" stroke-width="1.7"/>
    <path d="M316,102 L316,326" stroke-width="1.3"/>
    <path d="M324,102 L324,326" stroke-width="1"/>
    <path d="M332,102 L332,326" stroke-width=".8"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M504,40 L340,50"/><path d="M466,62 L340,64"/><path d="M186,124 L300,126"/>
    <path d="M186,166 L268,164"/><path d="M186,214 L272,216"/><path d="M186,300 L272,300"/>
    <path d="M566,274 L350,274"/><path d="M496,314 L392,314"/><path d="M542,350 L340,348"/>
    <path d="M186,430 L310,432"/><path d="M186,478 L164,478"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="43" text-anchor="end">Scroll (larger)</text>
    <text x="600" y="65" text-anchor="end">Machine tuning gears</text>
    <text x="180" y="127" text-anchor="end">Fingerboard (short)</text>
    <text x="180" y="169" text-anchor="end" fill="#9C7A3C">Shoulder (shapes vary)</text>
    <text x="180" y="217" text-anchor="end">f-hole (longer)</text>
    <text x="180" y="303" text-anchor="end">Lower bout</text>
    <text x="610" y="277" text-anchor="end">Bridge</text>
    <text x="610" y="317" text-anchor="end">Top plate · spruce</text>
    <text x="610" y="353" text-anchor="end">Tailpiece</text>
    <text x="180" y="433" text-anchor="end">Endpin (essential here)</text>
    <text x="610" y="467" text-anchor="end">Floor</text>
  </g>
  <text x="20" y="496" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Body ≈ 1,070 mm, string length ≈ 1,050 mm — played standing, supported by the endpin.</text>
</svg>
```

1. Basses have different body shapes, including sloping and rounded shoulders; they are not generally made with only the left shoulder cut away.
2. Geared tuning machines make fine adjustment of heavy strings practical and are common on modern basses.
3. Fingerboard, string and body dimensions vary by model. The ratio of string length to body length does not measure fingerboard length.

## Why fourths tuning

This is the most frequently asked question about the instrument, and the answer is not musical.
It is about hands.

The family's string lengths differ enormously: violin 328 mm, cello 690 mm, double bass 1,050 mm.
String length decides one thing above all — how far a hand must travel for a given interval.
Working from the string-length-to-frequency relationship, a whole tone (two semitones) lands at:

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="String length and whole-tone reach on violin, cello and double bass — the longer the string, the further the hand must reach">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">The same whole tone, on three string lengths — drawn to one scale</text>
  </g>
  <text x="20" y="60">Violin · 328 mm string</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,74 L224,74"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,66 L60,82"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M78,66 L78,82"/>
  </g>
  <text x="86" y="70" fill="#9C7A3C" font-size="11">whole tone = 36 mm</text>
  <text x="20" y="132">Cello · 690 mm string</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,146 L405,146"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,138 L60,154"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M97.5,138 L97.5,154"/>
  </g>
  <text x="106" y="142" fill="#9C7A3C" font-size="11">whole tone = 75 mm</text>
  <text x="20" y="204">Double bass · 1,050 mm string</text>
  <g stroke="#6E6A64" stroke-width="4" stroke-linecap="butt">
    <path d="M60,218 L585,218"/>
  </g>
  <g stroke="#343439" stroke-width="2">
    <path d="M60,210 L60,226"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2">
    <path d="M117.5,210 L117.5,226"/>
  </g>
  <text x="126" y="214" fill="#9C7A3C" font-size="11">whole tone = 115 mm</text>
  <text x="196" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">1 - 2 - 4 fingering (the third finger is skipped)</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">115 mm measures nut to whole-tone stopping point, not minimum adjacent-finger spacing.</text>
</svg>
```

Starting from an open string, raising pitch by a whole tone in equal temperament shortens the vibrating length by about 10.9%. For lengths of 328, 690 and 1,050 mm, the stopping distances are about 36, 75 and 115 mm. These are distances from the nut to the whole-tone stopping point, not the minimum spacing between adjacent fingers. The same interval takes less distance higher up the fingerboard.

- Standard fourths tuning E1–A1–D2–G2 helps organise fingering and string crossing on long strings.
- Lower positions often use 1–2–4, with the third finger supporting the fourth. The third finger is not discarded throughout the instrument; higher and thumb positions use other patterns.

So a bass player's left hand is not really "stopping notes" — it is shifting constantly. That
slightly gliding continuity in fast bass lines comes from exactly this.

## Range

```range
{"range":"E1–G4","written":"E2–G5","common":"E1–C3","caption":"低音提琴的记谱音域与实音音域","caption_en":"The double bass: notated range above, sounding range below","note":"⚠️ 低音提琴是移调乐器 —— 记谱比实音高一个八度。上面一行是记谱，下面一行是实际听到的音高。"}
```

A little over three octaves. Note the two rows on the chart: the double bass is the only member of
the family notated as a transposing instrument — an E2 on the page sounds as E1. The reason is
practical: writing sounding pitch in bass clef would push a great many notes below the staff, beyond
any sensible number of ledger lines.

The standard four-string low E1 is about 41.2 Hz and has a definite pitch. Five-string instruments or extensions can reach C1 or B0. Upper partials also help listeners identify a low note, so the whole 20–40 Hz region cannot be treated as sensation without pitch.

| String | Open note | Colour |
|---|---|---|
| E | E1 | lowest standard open string, with definite pitch and low-frequency weight |
| A | A1 | full; the orchestra's usual bass register |
| D | D2 | clear, the workhorse of bass lines |
| G | G2 | the brightest — where jazz soloists climb |

The clef is bass clef; high passages switch to [[concept:clef|treble clef]], with the same
octave relationship to sounding pitch.

## Timbre, and how to hear it

Recognising a double bass works differently from the rest of the family:

1. Low notes have both weight and recognisable pitch; upper partials help the ear identify the lowest notes.
2. The D and G strings and higher positions serve melodic and solo writing with a different colour from the low accompaniment register.
3. Pizzicato has a clear attack and decay, while bowing can sustain a level and connect long lines. Jazz and orchestral writing can use either as required.

The demonstration plays the four open strings E1, A1, D2 and G2. Compare pitch, attack and resonance as the register rises.

```audiolab
{"type":"instrument","gm":"Contrabass","synth":"bowed","phrase":["E1","A1","D2","G2"],"label":"四根空弦：从 E 弦到 G 弦","label_en":"Four open strings — E up to G","hint":"注意 E1 更像分量、G2 才像音；也注意四度定弦的音程比小提琴的窄","hint_en":"Hear how E1 reads as weight rather than pitch, and how G2 turns into a real note — then note the fourths between them."}
```

> The tracks under “Listen in the library” are the skeleton of the music — transcription or
> engraving MIDI — while timbre is handled by the player above. One transparency note: only four tracks
> in the library carry a title or composer that identifies them unambiguously as double-bass music, and
> all four are listed here. That is a limit of the dataset, not a selection made on this page.

## Playing techniques

The right hand has two bow grips, unique in the family:

- French bow (overhand): palm down, structurally like the cello's French bow.
- German bow (underhand): palm up, cradling the frog — the older tradition inherited from the bass
  viol.

The two schools are complete systems (weight distribution, wrist action, spiccato all differ), and both
survive among professional players today.

The left hand follows the previous section: 1-2-4 fingering plus constant shifting. The rest of the
technique is shared with the family, with a few things that need separate work on this instrument:

- Pizzicato: thick strings and high tension mean the whole hand, not just a finger. In jazz it is a
  solo language — walking lines, double stops, slaps — not decoration.
- Harmonics: the longer the string, the further apart its nodes, and the easier they are to hear.
  A double bass's natural harmonics are clearer than a violin's.
- Bow hair tension: thick strings need more pressure, but too much chokes the string and kills the
  harmonics. Controlling that line is the hardest part of the right hand.
- Hold and endpin: most basses use an endpin, but some players — especially in jazz and folk —
  brace the instrument against the body to pluck it, and both the posture and the sound change.

## The family

The double bass’s development involves both viol and violin traditions rather than one simple descent from the bass viol. Modern fourths tuning, shoulder shapes, backs and bow types should be described separately. Historically, violone did not always name one particular instrument.

| Feature | Common violin, viola and cello practice | Common double-bass practice |
|---|---|---|
| Tuning | fifths | fourths |
| Ordinary notation | concert pitch | octave above the sound |
| Shoulders and back | usually rounded shoulders, arched back | shoulder shape and flat/arched back vary |
| Bow | instrument-specific types | French and German bows coexist |

| Instrument | Body | String length | Tuning (low→high) | Range |
|---|---|---|---|---|
| [[instrument:violin\|Violin]] | 356 mm | 328 mm | G3 D4 A4 E5 | G3–E7 |
| [[instrument:viola\|Viola]] | 410 mm | 370 mm | C3 G3 D4 A4 | C3–E6 |
| [[instrument:cello\|Cello]] | 760 mm | 690 mm | C2 G2 D3 A3 | C2–C6 |
| **Double bass** | 1,070 mm | 1,050 mm | E1 A1 D2 G2 | E1–G4 |

So the most accurate way to put it: **they are one family, but the double bass came in carrying an
older name.**

## History

Since the sixteenth century, European low bowed instruments have used varied sizes, string counts, tunings and names, gradually leading to the modern double bass. This was not a single replacement that preserved one earlier instrument’s complete set of rules.

Eighteenth-century basses usually had three strings (A1, D2, G2). The fourth string (E1) came later
and only then gave the instrument the depth an orchestral bass part needs. Dragonetti is the figure of
that period: his technique and his works made the double bass a plausible solo instrument in the late
18th century.

In the 19th century Bottesini did for the double bass what the great virtuosi did for the violin —
called "the Paganini of the double bass", he pushed solo technique to its limit and left concertos and
character pieces. The solo tradition is essentially this line.

In the 20th century the instrument split across two stages: the orchestral bass part (bowed, long
notes, foundation) and the jazz bass (plucked, walking, improvising). One instrument, two almost
unrelated techniques — also a first in this family.

## Common misconceptions

- The double bass is not simply an enlarged cello: its historical forms, usual fourths tuning and transposing notation differ.
- Pitch depends jointly on vibrating length, tension and mass per unit length: f = (1/2L)√(T/μ). Gauge and tension are not merely secondary adjustments.
- Fourths tuning helps organise fingering. Lateral distance between strings comes from string spacing, not from the interval between open strings.
- 1–2–4 is a common lower-position pattern; shifting, thumb position and other fingerings extend its reach.

## Next

That completes the four Western bowed strings. For comparison: the [[instrument:violin|violin]] entry
gives the family's shared shape and craft, the [[instrument:viola|viola]] is the story of size forced
into compromise, and this page is the story of a rule being changed. Together they show one thing
clearly: an instrument's form is a negotiation between acoustic need and the human body.
:::
