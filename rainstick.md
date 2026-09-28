---
id: rainstick
site: inst
cat: I4
title: 雨棍
title_en: Rainstick
summary: 内部螺旋加细粒的摇奏体鸣乐器，声音形态由倾斜速度决定
summary_en: A shaken idiophone of internal spirals and grains — its shape of sound set by how fast you tilt it
level: standard
tags: [乐器, 打击, 世界]
tags_en: [instrument, percussion, world]
alias: [雨棍, rainstick, 雨声棒, 雨棒, 雨棍（智利）]
order: 74
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:maracas]]"
  - "[[instrument:wind-chimes]]"
  - "[[instrument:gong]]"
  - "[[instrument:latin-percussion]]"
instances:
  - oga-000217 | 9149carribeansteeldrums5 —— 加勒比地区的打击乐素材，可作氛围类打击乐的听觉参照
  - oga-000110 | 9046caribeansteeldrums1 —— 同类素材的另一版本
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 西方管乐团里的打击乐写法，可对照"节奏型"与"氛围型"两种用法
sources:
  - 结构依通行乐器资料：多为**干仙人掌**（传统）或木/塑料**管**，内壁插有**螺旋排列的刺或隔片**，管中装**细粒（小石、籽、沙）**
  - 「雨棍属**体鸣**的无音高乐器」依 Hornbostel–Sachs 分类
  - 「声音由颗粒沿螺旋逐级落下产生 —— 因此倾斜速度决定声音的密度与延续时间」依乐器声学
  - 「传统形制见于南美（智利、秘鲁一带），与求雨仪式有关；20 世纪后期成为世界性的氛围乐器」依乐器史
updated: 2026-09-26
---

::: zh
雨棍是打击乐里唯一一件"**演奏的是过程而不是音符**"的乐器：
它的声音**不是一个点、也不是一层沙，而是一段有开始有结束的"雨"**。

而这段雨的长短、密度与轻重，**完全由演奏者倾斜它的速度决定**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **体鸣**（Idiophone）· **无固定音高** |
| **次级类型** | 管状 · 内壁有螺旋刺或隔片 · 管内装细粒 · 倾斜使其流动发声 |
| **所属族** | 世界乐器 · 打击（体鸣 · 摇奏） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，雨棍不在其中 |

> ⚠️ **一个概念上的要点**：**"声音的形态"本身可以是乐器的设计对象。**
> - 击奏乐器设计的是"**一个音的音色**"（鼓的膜、木琴的条）。
> - 摇奏乐器（[[instrument:maracas|砂槌]]）设计的是"**一层连续声音**"的**颗粒粗细**。
> - **雨棍设计的是"一段声音的过程"**：它有**渐起、持续、渐落**，
>   而这三点由管内的**螺旋结构**保证 —— 颗粒必须逐级落下，不能一次倒完。
>
> **乐器不只是"发声的器件"，也可以是"时间形状的器件"** —— 雨棍是这条路线的极致。

## 结构：螺旋让颗粒"逐级落下"

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="雨棍的结构：管状外壳、内壁螺旋排列的隔片与管内细粒，倾斜后颗粒逐级落下">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">雨棍 · 结构（螺旋隔片让颗粒逐级落下，形成"雨"的过程）</text>
  </g>
  <rect x="90" y="126" width="460" height="40" rx="20" fill="#17171A" stroke="#9C7A3C" stroke-width="1.8"/>
  <g stroke="#5B7FA8" stroke-width="2.4" stroke-linecap="round">
    <path d="M126,130 L136,162"/><path d="M166,130 L176,162"/>
    <path d="M206,130 L216,162"/><path d="M246,130 L256,162"/>
    <path d="M286,130 L296,162"/><path d="M326,130 L336,162"/>
    <path d="M366,130 L376,162"/><path d="M406,130 L416,162"/>
    <path d="M446,130 L456,162"/><path d="M486,130 L496,162"/>
    <path d="M526,130 L536,162"/>
  </g>
  <g fill="#E07A3F">
    <circle cx="150" cy="152" r="3.4"/><circle cx="190" cy="148" r="3.4"/>
    <circle cx="230" cy="154" r="3.4"/><circle cx="270" cy="150" r="3.4"/>
    <circle cx="310" cy="152" r="3.4"/><circle cx="350" cy="148" r="3.4"/>
    <circle cx="390" cy="154" r="3.4"/><circle cx="430" cy="150" r="3.4"/>
    <circle cx="470" cy="152" r="3.4"/><circle cx="510" cy="150" r="3.4"/>
  </g>
  <path d="M60,146 L86,146" stroke="#6E6A64" stroke-width="2.4"/>
  <path d="M64,138 L60,146 L64,154" fill="none" stroke="#6E6A64" stroke-width="2.4"/>
  <path d="M90,196 C240,214 400,214 550,196" stroke="#6E6A64" stroke-width="2" fill="none" stroke-dasharray="5 3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L252,124"/><path d="M186,146 L186,146"/>
    <path d="M186,224 L232,206"/><path d="M486,70 L440,124"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end" fill="#5B7FA8">内壁螺旋隔片</text>
    <text x="180" y="227" text-anchor="end">倾斜方向（颗粒由此向下）</text>
    <text x="492" y="67">管状外壳（传统为干仙人掌）</text>
  </g>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">螺旋的作用是"限制流速"：颗粒必须一格一格地绕行，所以声音从第一粒到最后一粒有一个明确的时长。</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">如果没有螺旋，颗粒会一次倒完 —— 那就只剩一声"哗"，没有"雨"。</text>
</svg>
```

三处要点：

1. **螺旋是"限流器"**。它让颗粒必须逐级绕行落下 ——
   于是声音有一个明确的**开始与结束**，而不是一声"哗"。
2. **传统形制用干仙人掌**：把刺向内压入形成螺旋，这是最省工的做法。
   现代多为木或塑料管内插隔片。
3. **倾斜角度与速度是两个变量**：角度决定颗粒是否流动，
   倾斜的**速度**决定流动的快慢 —— 也就是"雨"的疏密。

## 音域

雨棍属于**无固定音高**乐器，本站不为其生成音域图。它的表现手段在**倾斜的速度与角度**：

| 动作 | 声音 |
|---|---|
| **缓慢竖直倾斜** | 稀疏的、渐起渐落的"雨" |
| **快速翻转** | 急密的"雨" |
| **只倾一点** | 少量颗粒落下，稀疏的滴答 |
| **水平放置** | 静止（颗粒不流动） |
| **轻晃** | 细碎的沙沙 |

**注意"水平放置即静止"这一条**：它是**静默状态**也是**可控状态** ——
演奏者可以让它停在任意时刻，这是击奏类乐器做不到的。

## 音色与听辨

四条线索：

1. **宽带的细密噪声**，形态像雨 —— 这是它存在的全部理由。
2. **有明确的过程感**。渐起、持续、渐落是它的天然结构。
3. **音量中等偏小**。它适合安静的段落、氛围层与场景描绘，
   不适合在强奏里出头。
4. **声音的疏密可控**。倾斜速度变化直接反映为雨的疏密。

```audiolab
{"type":"instrument","drum":82,"synth":"perc","phrase":[82,82,82,82,82,82],"label":"雨棍的倾斜声：一段渐起渐落的雨","label_en":"A rainstick tilt — a rain that rises and falls","hint":"注意声音有明确的过程 —— 这不是一个「音」，是一段「雨」","hint_en":"Hear the process rather than a note — this is a stretch of rain."}
```

## 演奏技法

- **竖直缓慢倾斜**是主要用法：得到最完整的"雨"。
- **翻转**得到急雨；**来回轻晃**得到细碎的沙沙。
- **与其他氛围乐器组合**：与[[instrument:wind-chimes|风铃]]、[[instrument:gong|锣]]叠在一起，
  是影视配乐里常见的"氛围层"。
- **不需要准拍**。它的功能是**色彩与场景**，不是节奏。

## 家族与近亲

| 乐器 | 声音的时间形态 | 用途 |
|---|---|---|
| **雨棍** | **一段有始有终的"雨"** | 氛围与场景 |
| [[instrument:maracas\|砂槌]] | 一层持续的"沙" | 节奏底色 |
| [[instrument:wind-chimes\|风铃]] | 成片的余响（可很长） | 氛围 |
| [[instrument:gong\|锣]] | 单次击发的长余音 | 气氛与高潮 |

**这四件都是"无音高的氛围型乐器"**，但它们的**时间形态各不相同**：
雨棍是"过程"，砂槌是"层"，风铃是"片"，锣是"一击"。
**选哪件，取决于需要哪种时间形态。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代—前哥伦布时期 | 南美（智利、秘鲁一带）已有干仙人掌制成的雨棍，与**求雨仪式**相关 |
| 16—19 世纪 | 在美洲原住民音乐中使用；因材料易得而流传 |
| 20 世纪后期 | 作为"氛围乐器"被世界音乐与影视配乐大量采用；木、塑料版本出现 |
| 20 世纪后期至今 | 世界音乐、新世纪音乐、影视配乐的常用色彩乐器；也是常见的儿童乐器 |

**它从"仪式器物"变成"影视音效"** ——
这个转变过程说明了乐器功能可以被重新定义：
**同一个声音，在不同的语境里承担完全不同的意义。**

## 常见误解

- **"雨棍就是摇一摇。"** 它的价值在**倾斜速度的控制** ——
  慢倾与快翻是完全不同的两段"雨"。
- **"它和砂槌是一回事。"** 都是摇奏，但**时间形态不同**：
  砂槌给"层"，雨棍给"过程"。
- **"它有音高。"** 无固定音高。
- **"它只是玩具。"** 它是影视配乐与当代音乐里常用的氛围乐器；
  也是"乐器可以设计时间形态"这一类的代表。
- **"里面装的是水。"** 装的是**细粒**（小石、籽或沙）——
  水无法在螺旋里形成可控的逐级落下。

## 下一步

打击批只剩 4 条：鞭响器 · 乐砧 · 风铃 · 木鱼。
其中 [[instrument:wind-chimes|风铃]] 与它一样属"氛围型"，但时间形态不同（片 vs 过程）；
[[instrument:woodblock|木鱼（西洋用法）]] 则回到"硬木小响器"一系。
:::

::: en
The rainstick is percussion's only instrument that **plays a process rather than a note**: its sound is not a
point and not a layer, but **a stretch of rain with a beginning and an end.**

And the length, density and weight of that rain are **decided entirely by how fast the player tilts it.**

| Classification | Value |
|---|---|
| **HS class** | **Idiophone** · **unpitched** |
| **Sub-type** | Tubular · internal spiral spines or baffles · grains inside · tilted to make them flow |
| **Family** | World instruments · Percussion (idiophone, shaken) |
| **Bayin** | Not applicable — a Chinese system; the rainstick is outside it |

> ⚠️ **One conceptual point**: **the *shape in time* of a sound can itself be a design target.**
> - A struck instrument designs **the colour of one note** (a drum's head, a xylophone's bar).
> - A shaken instrument such as [[instrument:maracas|maracas]] designs **the grain of a continuous layer**.
> - **The rainstick designs "a process of sound"**: it has a **fade-in, a sustain and a fade-out**, guaranteed
>   by the internal **spiral**, which forces the grains to descend step by step instead of all at once.
>
> **An instrument can be a device for shaping time, not only a device for making sound** — the rainstick is
> the extreme of that idea.

## Structure: the spiral makes the grains descend step by step

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Rainstick structure: a tubular body with spiral baffles inside and grains that descend step by step when tilted">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Rainstick — structure (spiral baffles make the grains descend in steps, producing "rain")</text>
  </g>
  <rect x="90" y="126" width="460" height="40" rx="20" fill="#17171A" stroke="#9C7A3C" stroke-width="1.8"/>
  <g stroke="#5B7FA8" stroke-width="2.4" stroke-linecap="round">
    <path d="M126,130 L136,162"/><path d="M166,130 L176,162"/>
    <path d="M206,130 L216,162"/><path d="M246,130 L256,162"/>
    <path d="M286,130 L296,162"/><path d="M326,130 L336,162"/>
    <path d="M366,130 L376,162"/><path d="M406,130 L416,162"/>
    <path d="M446,130 L456,162"/><path d="M486,130 L496,162"/>
    <path d="M526,130 L536,162"/>
  </g>
  <g fill="#E07A3F">
    <circle cx="150" cy="152" r="3.4"/><circle cx="190" cy="148" r="3.4"/>
    <circle cx="230" cy="154" r="3.4"/><circle cx="270" cy="150" r="3.4"/>
    <circle cx="310" cy="152" r="3.4"/><circle cx="350" cy="148" r="3.4"/>
    <circle cx="390" cy="154" r="3.4"/><circle cx="430" cy="150" r="3.4"/>
    <circle cx="470" cy="152" r="3.4"/><circle cx="510" cy="150" r="3.4"/>
  </g>
  <path d="M60,146 L86,146" stroke="#6E6A64" stroke-width="2.4"/>
  <path d="M64,138 L60,146 L64,154" fill="none" stroke="#6E6A64" stroke-width="2.4"/>
  <path d="M90,196 C240,214 400,214 550,196" stroke="#6E6A64" stroke-width="2" fill="none" stroke-dasharray="5 3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L252,124"/><path d="M186,146 L186,146"/>
    <path d="M186,224 L232,206"/><path d="M486,70 L440,124"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end" fill="#5B7FA8">Spiral baffles inside</text>
    <text x="180" y="227" text-anchor="end">Direction of tilt</text>
    <text x="492" y="67">Tubular body (cactus)</text>
  </g>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The spiral limits the flow rate: grains must travel one baffle at a time, so the sound has a definite duration.</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Without it the grains would fall at once — a single splash, not rain.</text>
</svg>
```

Three points:

1. **The spiral is a flow limiter.** It forces the grains around one baffle at a time, so the sound has a
   definite **beginning and end** instead of one splash.
2. **Traditionally a dried cactus**, with the spines pushed inward to form the spiral — the least labour-intensive
   method. Modern ones use wood or plastic with inserted baffles.
3. **Angle and speed are two variables**: the angle decides whether grains flow, the **speed** of tilting
   decides how fast — that is, the density of the rain.

## Range

The rainstick is **unpitched**, so no range chart is generated. Its means are **tilt speed and angle**:

| Motion | Sound |
|---|---|
| **Slow vertical tilt** | a sparse rain that rises and falls |
| **Quick flip** | a dense, urgent rain |
| **Slight tilt** | a few grains falling — sparse ticking |
| **Held level** | silence (grains do not flow) |
| **Gentle sway** | a fine rustle |

**Note that "held level" means silence** — it is both the resting state and a **controllable** one: the player
can stop it at any moment, which no struck instrument can do.

## Timbre, and how to hear it

Four cues:

1. **Broadband fine noise shaped like rain** — the entire reason it exists.
2. **A clear sense of process**: fade-in, sustain, fade-out are its natural structure.
3. **Medium-quiet**: suited to quiet passages, atmospheric layers and scene painting, not to cutting through a
   loud texture.
4. **Density is controllable**: tilting speed translates directly into how thick the rain is.

```audiolab
{"type":"instrument","drum":82,"synth":"perc","phrase":[82,82,82,82,82,82],"label":"雨棍的倾斜声：一段渐起渐落的雨","label_en":"A rainstick tilt — a rain that rises and falls","hint":"注意声音有明确的过程 —— 这不是一个「音」，是一段「雨」","hint_en":"Hear the process rather than a note — this is a stretch of rain."}
```

## Playing techniques

- **A slow vertical tilt** is the main use, giving the fullest rain.
- **A flip** gives a downpour; **a gentle sway** a fine rustle.
- **Combined with other atmospheric instruments** — [[instrument:wind-chimes|wind chimes]] and the
  [[instrument:gong|gong]] — it forms a common "atmosphere layer" in film scoring.
- **No need to keep time**: its function is **colour and scene**, not rhythm.

## The family

| Instrument | Shape of sound in time | Use |
|---|---|---|
| **Rainstick** | **a rain with a beginning and an end** | atmosphere and scene |
| [[instrument:maracas\|Maracas]] | a continuous layer of shiver | rhythmic underlay |
| [[instrument:wind-chimes\|Wind chimes]] | a sheet of ringing (can be very long) | atmosphere |
| [[instrument:gong\|Gong]] | a single stroke with a long tail | atmosphere and climax |

**All four are unpitched atmospheric instruments**, but their **shapes in time differ**: the rainstick is a
process, the maracas a layer, the wind chimes a sheet, the gong a single stroke.
**Which one you choose depends on which shape in time you need.**

## History

| Period | State |
|---|---|
| Antiquity–pre-Columbian | rainsticks of dried cactus already exist in South America (Chile, Peru), tied to **rain-making ritual** |
| 16th–19th c. | used in Native American music; spreads because the material is easy to obtain |
| Late 20th c. | widely adopted as an "atmospheric instrument" in world and film music; wooden and plastic versions appear |
| Late 20th c. onward | a common colour instrument in world, new-age and film music, and a familiar children's instrument |

**It moved from ritual object to film effect** — showing that an instrument's function can be redefined:
**the same sound can carry completely different meanings in different contexts.**

## Common misconceptions

- **"A rainstick is just shaken."** Its value lies in **controlling the tilt speed** — a slow tilt and a quick
  flip are two entirely different rains.
- **"It is the same as maracas."** Both are shaken, but the **shape in time differs**: maracas give a layer,
  the rainstick a process.
- **"It has pitch."** Unpitched.
- **"It is only a toy."** It is a standard atmospheric instrument in film and contemporary music, and the
  representative of "instruments that design a shape in time".
- **"It is filled with water."** It is filled with **grains** (small stones, seeds or sand) — water cannot form
  a controlled step-by-step descent through a spiral.

## Next

Four percussion entries remain: whip · anvil · wind chimes · woodblock. The
[[instrument:wind-chimes|wind chimes]] are atmospheric like the rainstick but with a different shape in time
(a sheet rather than a process); the [[instrument:woodblock|woodblock]] returns to the small-hardwood family.
:::
