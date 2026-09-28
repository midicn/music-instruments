---
id: bass-drum
site: inst
cat: I4
title: 大鼓
title_en: Bass Drum
summary: 两面大膜的膜鸣鼓，无固定音高，管弦乐与爵士鼓组的低频来源
summary_en: The two-headed membranophone with the deepest low end — in orchestra and drum kit alike
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [大鼓, bass drum, 大军鼓, 低音鼓, gran cassa]
order: 57
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:snare-drum]]"
  - "[[instrument:timpani]]"
  - "[[instrument:cymbals]]"
  - "[[instrument:drum-kit]]"
instances:
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里大鼓的实际用法
  - pdmx-000510 | Drake's Drum —— 标题指向鼓的曲目，可作时代语汇的参照
  - pdmx-002820 | 为三支小号与定音鼓而作的协奏曲 TWV 54:D4 —— 巴洛克打击乐的写法，与大鼓的现代用法形成对照
sources:
  - 结构依通行制琴资料：大型圆筒鼓身，**两面蒙皮**，无响弦；管弦乐用单槌（或双槌）击奏，鼓身通常竖立或斜挂
  - 「大鼓属**膜鸣**乐器，无固定音高」依 Hornbostel–Sachs 分类
  - 「管弦乐用大鼓与爵士鼓组的底鼓是同一原理的两种形态 —— 前者竖立、单槌击；后者横放、脚踏」依乐器制作与演奏通识
  - 「管弦乐里的大鼓鼓面直径常达 80 厘米以上」依通行制琴规格
  - 「**鼓面越大 → 基频越低**（张力不变时，膜的振动频率与直径成反比），余音也越难控制」依膜振动原理
updated: 2026-09-26
---

::: zh
大鼓是打击乐里最直接的一件：**它只做一件事 —— 给出低频的重量。**
与[[instrument:snare-drum|小鼓]]同属**膜鸣**、同属**无固定音高**，
但它的全部能量都在频谱的最低端。

它还有一个别的乐器不常有的情况：**同一个名字下其实是两种形态**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **膜鸣**（Membranophone）· **无固定音高** |
| **次级类型** | 大型圆筒鼓身 · **两面蒙皮** · 无响弦 · 用单槌或双槌击奏 |
| **所属族** | 西洋 · 打击（膜鸣支系 · 无音高） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，大鼓不在其中 |

> ⚠️ **一个概念上的要点**：**"大鼓"在两个场合是两种不同的乐器形态。**
> - **管弦乐大鼓**：鼓面竖立（或斜挂），用**单支大鼓槌**从侧面击奏，声音散得开、余音长。
> - **爵士鼓组的底鼓**：鼓面**横放**，用**脚踏板**带动槌头击奏，声音短促、指向性强。
>
> 两者的声学原理完全相同（都是膜鸣、都无音高），
> **但持握与击奏方式让它们在音乐里承担完全不同的功能** ——
> 一个负责"轰鸣的重量"，一个负责"每拍的推进"。这与[[instrument:sousaphone|大号与苏萨号]]的情况类似。

## 结构：两面大膜，没有响弦

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管弦乐大鼓的结构：大型圆筒鼓身、两面鼓皮与单支大鼓槌，鼓身竖立悬挂">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">管弦乐大鼓 · 结构（两面大膜、无响弦、单槌击奏）</text>
  </g>
  <ellipse cx="300" cy="160" rx="70" ry="106" fill="#0E0E10" stroke="#9C7A3C" stroke-width="2.2"/>
  <ellipse cx="300" cy="160" rx="52" ry="80" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M230,160 C248,120 352,120 370,160 C352,200 248,200 230,160 Z" fill="none" stroke="#343439" stroke-width="1"/>
  <g stroke="#6E6A64" stroke-width="2.4" stroke-linecap="round">
    <path d="M234,92 L244,74"/><path d="M266,60 L282,44"/>
    <path d="M300,52 L300,34"/><path d="M334,60 L318,44"/>
    <path d="M366,92 L356,74"/>
    <path d="M234,228 L244,246"/><path d="M300,268 L300,286"/>
    <path d="M366,228 L356,246"/>
  </g>
  <path d="M300,54 C300,34 320,26 336,34" fill="none" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <path d="M392,132 L448,102" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <ellipse cx="456" cy="96" rx="16" ry="11" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L212,80"/><path d="M186,160 L232,160"/>
    <path d="M186,256 L214,246"/><path d="M186,110 L186,124"/>
    <path d="M498,90 L474,92"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end" fill="#5B7FA8">悬挂用吊环（鼓身竖立）</text>
    <text x="180" y="163" text-anchor="end" fill="#9C7A3C">鼓皮（直径常达 80 厘米以上）</text>
    <text x="180" y="259" text-anchor="end">张力螺栓（两面都要调）</text>
    <text x="180" y="107" text-anchor="end">无响弦，低频干净</text>
    <text x="504" y="87">单支大鼓槌（软头）</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">鼓身竖立悬挂 —— 这样低频可以向四周散开，余音也留得久，得到"轰鸣"的效果。</text>
</svg>
```

三处要点：

1. **无响弦**。这是它与小鼓决定性的差别：没有高频噪声，**能量全部集中在低频**。
2. **鼓面很大（常达 80 厘米以上）**。鼓面越大，基频越低 —— 这就是它"低"的原因。
3. **竖立悬挂 + 单槌**（管弦乐用法）。竖立让声音向四周辐射，余音长；
   这与爵士鼓组那个**横放、脚踏**的底鼓是完全不同的使用方式。

## 两种形态，两种功能

```svg
<svg viewBox="0 0 640 312" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管弦乐大鼓与爵士鼓组底鼓的对比：竖立单槌击奏对比横放脚踏">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一个原理，两种形态</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">管弦乐大鼓 · 竖立、单槌</text>
  <ellipse cx="160" cy="150" rx="54" ry="78" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <path d="M228,138 L272,116" stroke="#9C7A3C" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="278" cy="112" rx="12" ry="9" fill="#9C7A3C"/>
  <text x="160" y="252" text-anchor="middle" font-size="10.5" fill="#A9A49B">声音向四周散开、余音长</text>
  <text x="160" y="272" text-anchor="middle" font-size="10.5" fill="#9C7A3C">给强拍"轰鸣的重量"</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">爵士鼓组底鼓 · 横放、脚踏</text>
  <ellipse cx="480" cy="150" rx="78" ry="54" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M480,96 L480,66" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="480" cy="58" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M404,196 L360,214" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <rect x="330" y="208" width="34" height="12" rx="4" fill="#5B7FA8"/>
  <text x="480" y="252" text-anchor="middle" font-size="10.5" fill="#A9A49B">声音短促、指向性强</text>
  <text x="480" y="272" text-anchor="middle" font-size="10.5" fill="#5B7FA8">给每一拍"推进力"</text>
  <text x="20" y="300" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">管弦乐大鼓追求"共鸣"，爵士底鼓追求"控制" —— 所以一个竖立悬挂，一个横放贴地。</text>
</svg>
```

**这条对比说明"同一个乐器原理可以走出完全不同的音乐角色"**：
声学上两者都是无音高的膜鸣低频鼓，但
**一个要"散"（音乐厅的轰鸣），一个要"收"（节奏组的颗粒）**。

## 音域

大鼓属于**无固定音高**乐器，本站不为其生成音域图。它的表现手段在**击奏方式与力度**：

| 用法 | 效果 |
|---|---|
| **单槌轻击** | 远处的雷声、暗涌的低频 |
| **单槌重击** | 强拍、宣示、戏剧性瞬间 |
| **双槌交替（滚奏）** | 持续的轰鸣，用于渐强与张力 |
| **双槌同击** | 极重的强调 |
| **止音（手按鼓皮）** | 短促、干脆的一击 |

**在管弦乐里它是"配器工具"而不是"节奏乐器"** ——
它出现的次数通常很少，但每一次都改变整个音响的重量。

## 音色与听辨

四条线索：

1. **极低频为主，几乎听不出音高的细节**。听感更接近"震动"与"分量"。
2. **余音很长**（管弦乐用法）。所以快速连击会糊，需要止音控制。
3. **强击有"拍胸"的物理感**。低频在身体上的作用比在耳朵上更明显。
4. **弱奏极暗**。管弦乐里用弱奏大鼓制造"远处的雷声"是很经典的手法。

```audiolab
{"type":"instrument","drum":35,"synth":"perc","phrase":[35,35,35,35,35,35],"label":"大鼓的击奏：低频的一击","label_en":"Bass drum — the low thud","hint":"注意听感更接近「震动」而不是「音高」—— 低频是它唯一的语言","hint_en":"It reads as vibration rather than pitch — low frequency is its only language."}
```

## 演奏技法

- **管弦乐**：单槌或双槌击奏；鼓面竖立，槌头常裹软毡 → 圆厚的轰鸣。
- **滚奏**：双槌快速交替，得到持续的渐强 —— 与定音鼓滚奏类似但更低更散。
- **止音**：击后用手或身体靠住鼓皮，得到短促的一击。
- **爵士鼓组**：脚踏板（单踩或双踩）—— 强调每一拍的"落点"，技术重点在**控制与稳定**。

## 家族与近亲

| 乐器 | 鼓面 | 响弦 | 音高感 | 角色 |
|---|---|---|---|---|
| **大鼓** | 两面大膜 | 无 | 无 | 低频重量 |
| [[instrument:snare-drum\|小鼓]] | 两面 | **有** | 无 | 节奏骨架 |
| [[instrument:timpani\|定音鼓]] | 单面、封闭 | 无 | **有** | 低频音高 |
| [[instrument:tambourine\|铃鼓]] | 单面框鼓 | 无（有钹片） | 无 | 节奏色彩 |

**大鼓与定音鼓都在低音区工作**，但一个无音高、一个有音高 ——
所以管弦乐里两者常**同时出现**：定音鼓给音高，大鼓给重量。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代—中世纪 | 各地有大型蒙皮鼓；土耳其军乐（mehter）里的**大鼓**是最重要的来源之一 |
| 17—18 世纪 | 随土耳其风格（alla turca）进入欧洲管弦乐；莫扎特、贝多芬用过 |
| 19 世纪 | 成为管弦乐的标准打击乐器；开始出现专门的鼓槌与悬挂方式 |
| 20 世纪初 | **爵士鼓组**把大鼓改为脚踏底鼓 —— 从此有了"用脚打鼓"这一支技术 |
| 20 世纪后期 | 双踩踏板技术出现；大鼓在摇滚、放克与流行里成为节奏的核心落点 |
| 20 世纪后期至今 | 管弦乐、管乐团、爵士、摇滚、流行的通用乐器 |

## 常见误解

- **"大鼓和小鼓只是大小不同。"** 结构与功能都不同：大鼓**无响弦**、能量全在低频；
  小鼓**有响弦**、能量全在高频。两者在乐队里的角色完全互补。
- **"管弦乐大鼓和爵士底鼓是同一种乐器。"** 声学原理相同，**形态与功能不同**：
  一个竖立单槌、追求共鸣；一个横放脚踏、追求控制。
- **"大鼓越大越好。"** 鼓面越大基频越低，但也越难控制余音；尺寸按音乐需要选择。
- **"它只是加强拍。"** 它在管弦乐里更常作为**配器手段** ——
  一次重击就能改变整个音响的重量。
- **"打大鼓不需要技巧。"** 止音、滚奏、以及"何时不击"的判断都是专业素养；
  弱奏的层次控制尤其难。

## 下一步

打击乐继续分两条走。膜鸣里还有 [[instrument:tambourine|铃鼓]]（框架鼓 + 钹片，横跨两类），
体鸣的第一站是 [[instrument:cymbals|铙钹]] —— 与小鼓的高频同属"噪声型"，
但来自金属的整体振动。
:::

::: en
The bass drum is the most direct instrument in percussion: **it does one thing — supply weight at low
frequency.** It belongs to the same class as the [[instrument:snare-drum|snare]] (**membranophone**,
**unpitched**), but all its energy sits at the bottom of the spectrum.

It also has a situation few instruments share: **one name covering two forms.**

| Classification | Value |
|---|---|
| **HS class** | **Membranophone** · **no definite pitch** |
| **Sub-type** | Large cylindrical shell · **two heads** · no snares · struck with one or two mallets |
| **Family** | Western · Percussion (membranophone branch, unpitched) |
| **Bayin** | Not applicable — a Chinese system; the bass drum is outside it |

> ⚠️ **One conceptual point**: **"bass drum" names two different instruments in two settings.**
> - **Orchestral bass drum**: head vertical (or hung at an angle), struck from the side with **one large
>   mallet** — it spreads, and rings long.
> - **Drum-kit kick drum**: head **horizontal**, struck by a beater driven by a **foot pedal** — short and
>   directional.
>
> Acoustically identical (both membranophones, both unpitched), but **the way they are held and struck makes
> them do completely different musical jobs** — one supplies "a roaring weight", the other "the push of every
> beat". The same situation as the [[instrument:sousaphone|tuba and the sousaphone]].

## Structure: two large heads, no snares

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Orchestral bass drum structure: a large cylindrical shell, two heads and a single soft mallet, hung vertically">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Orchestral bass drum — structure (two large heads, no snares, one mallet)</text>
  </g>
  <ellipse cx="300" cy="160" rx="70" ry="106" fill="#0E0E10" stroke="#9C7A3C" stroke-width="2.2"/>
  <ellipse cx="300" cy="160" rx="52" ry="80" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M230,160 C248,120 352,120 370,160 C352,200 248,200 230,160 Z" fill="none" stroke="#343439" stroke-width="1"/>
  <g stroke="#6E6A64" stroke-width="2.4" stroke-linecap="round">
    <path d="M234,92 L244,74"/><path d="M266,60 L282,44"/>
    <path d="M300,52 L300,34"/><path d="M334,60 L318,44"/>
    <path d="M366,92 L356,74"/>
    <path d="M234,228 L244,246"/><path d="M300,268 L300,286"/>
    <path d="M366,228 L356,246"/>
  </g>
  <path d="M300,54 C300,34 320,26 336,34" fill="none" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <path d="M392,132 L448,102" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <ellipse cx="456" cy="96" rx="16" ry="11" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L212,80"/><path d="M186,160 L232,160"/>
    <path d="M186,256 L214,246"/><path d="M186,110 L186,124"/>
    <path d="M498,90 L474,92"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end" fill="#5B7FA8">Suspension ring (head vertical)</text>
    <text x="180" y="163" text-anchor="end" fill="#9C7A3C">Head (often over 80 cm)</text>
    <text x="180" y="259" text-anchor="end">Tension bolts (both heads tuned)</text>
    <text x="180" y="107" text-anchor="end">No snares</text>
    <text x="504" y="87">One soft mallet</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Hung vertically, so the low frequencies spread in all directions and ring long — the "roar".</text>
</svg>
```

Three points:

1. **No snares.** This is the decisive difference from a snare drum: with no high-frequency noise, **all the
   energy goes low**.
2. **A very large head (often over 80 cm).** The larger the head, the lower the fundamental — the reason it
   is "bass".
3. **Vertical and hung, one mallet** (orchestral practice). Vertical radiates outward and rings long, in
   complete contrast to the kit's horizontal, pedal-struck drum.

## Two forms, two functions

```svg
<svg viewBox="0 0 640 312" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Orchestral bass drum and kit kick drum compared: vertical with one mallet versus horizontal with a pedal">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One principle, two forms</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">Orchestral · vertical, one mallet</text>
  <ellipse cx="160" cy="150" rx="54" ry="78" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <path d="M228,138 L272,116" stroke="#9C7A3C" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="278" cy="112" rx="12" ry="9" fill="#9C7A3C"/>
  <text x="160" y="252" text-anchor="middle" font-size="10.5" fill="#A9A49B">spreads outward, rings long</text>
  <text x="160" y="272" text-anchor="middle" font-size="10.5" fill="#9C7A3C">"roaring weight" on accents</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Kit kick · horizontal, pedal</text>
  <ellipse cx="480" cy="150" rx="78" ry="54" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M480,96 L480,66" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="480" cy="58" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M404,196 L360,214" stroke="#5B7FA8" stroke-width="5" stroke-linecap="round"/>
  <rect x="330" y="208" width="34" height="12" rx="4" fill="#5B7FA8"/>
  <text x="480" y="252" text-anchor="middle" font-size="10.5" fill="#A9A49B">short and directional</text>
  <text x="480" y="272" text-anchor="middle" font-size="10.5" fill="#5B7FA8">"push" on every beat</text>
  <text x="20" y="300" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">One wants resonance, the other control — hence one hangs vertically and one lies flat.</text>
</svg>
```

**This comparison shows one principle producing two entirely different musical roles**: acoustically both
are unpitched low membranophones, but **one must spread (a hall's roar) and the other must tighten (a
rhythm section's grain).**

## Range

The bass drum is **unpitched**, so no range chart is generated. Its expressive means are **how and how hard
it is struck**:

| Playing | Effect |
|---|---|
| **One light stroke** | distant thunder, a low swell |
| **One heavy stroke** | downbeats, proclamation, dramatic moments |
| **Two-mallet roll** | sustained roar, for crescendos and tension |
| **Both mallets together** | maximum emphasis |
| **Damping by hand** | a short, dry stroke |

**In an orchestra it is a scoring tool rather than a rhythm instrument** — it appears rarely, but each
appearance changes the weight of the whole sound.

## Timbre, and how to hear it

Four cues:

1. **Almost entirely low frequency**, with little pitch detail — closer to **vibration** than to notes.
2. **A long ring** (orchestral use), so fast repeated strokes blur and need damping.
3. **A physical thump in the chest** at high volume; below a certain frequency it is felt as much as heard.
4. **Extremely dark when played softly** — a classic way to suggest distant thunder.

```audiolab
{"type":"instrument","drum":35,"synth":"perc","phrase":[35,35,35,35,35,35],"label":"大鼓的击奏：低频的一击","label_en":"Bass drum — the low thud","hint":"注意听感更接近「震动」而不是「音高」—— 低频是它唯一的语言","hint_en":"It reads as vibration rather than pitch — low frequency is its only language."}
```

## Playing techniques

- **Orchestral**: one or two mallets, head vertical, mallet heads usually felt-covered → a round roar.
- **Rolls**: fast alternation for a sustained crescendo — like a timpani roll but lower and looser.
- **Damping** by hand or body for a short stroke.
- **Drum kit**: a foot pedal (single or double) where the technique is **control and steadiness** rather
  than power.

## The family

| Instrument | Heads | Snares | Pitch | Role |
|---|---|---|---|---|
| **Bass drum** | two large | no | none | low weight |
| [[instrument:snare-drum\|Snare drum]] | two | **yes** | none | rhythmic skeleton |
| [[instrument:timpani\|Timpani]] | one, closed | no | **yes** | low pitch |
| [[instrument:tambourine\|Tambourine]] | one, frame | no (jingles) | none | rhythmic colour |

**The bass drum and the timpani both work low**, but one is unpitched and the other pitched — which is why
orchestras often use **both at once**: the timpani supply the note, the bass drum the weight.

## History

| Period | State |
|---|---|
| Antiquity–Middle Ages | large skin drums worldwide; the **davul** of Turkish military music is a key source |
| 17th–18th c. | enters European orchestras with Turkish style (alla turca); Mozart and Beethoven use it |
| 19th c. | becomes standard orchestral percussion, with dedicated mallets and hanging methods |
| Early 20th c. | the **jazz drum kit** turns it into a pedal-operated kick — the birth of playing drums with a foot |
| Late 20th c. | double pedals appear; the kick becomes the rhythmic anchor of rock, funk and pop |
| Late 20th c. onward | universal across orchestra, band, jazz, rock and pop |

## Common misconceptions

- **"The bass drum is just a big snare."** The structures and jobs differ: the bass drum has **no snares**
  and all its energy is low; the snare has **snares** and all its energy is high. They complement each other.
- **"An orchestral bass drum and a kick drum are the same instrument."** Same acoustics,
  **different form and function**: one vertical with one mallet for resonance, one horizontal with a pedal for
  control.
- **"Bigger is better."** A larger head lowers the fundamental but makes the ring harder to control; sizes
  follow the music.
- **"It only reinforces downbeats."** In an orchestra it is more often a **scoring device** — a single heavy
  stroke can change the whole weight of the sound.
- **"Anyone can play a bass drum."** Damping, rolls, and knowing **when not to play** are professional skills,
  and dynamic control at low volume is especially hard.

## Next

Percussion continues along both branches. Among the membranes remains the
[[instrument:tambourine|tambourine]] (a frame drum with jingles, straddling both classes), and the first
idiophone is the [[instrument:cymbals|cymbals]] — the same "noise-like" high frequencies as a snare, but from
a metal body vibrating as a whole.
:::
