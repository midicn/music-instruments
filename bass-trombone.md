---
id: bass-trombone
site: inst
cat: I3
title: 低音长号
title_en: Bass Trombone
summary: 管径更粗、加装阀门的低音长号，长号声部的低音骨干
summary_en: The wider-bored trombone with valve attachments — the bass of the trombone section
level: standard
tags: [乐器, 铜管, 西洋]
tags_en: [instrument, brass, western]
alias: [低音长号, bass trombone, 低音伸缩号]
order: 48
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:trombone]]"
  - "[[instrument:tuba]]"
  - "[[instrument:euphonium]]"
  - "[[instrument:french-horn]]"
instances:
  - giantmidi-000250 | 低音长号奏鸣曲 Op.41 —— 库内标题可确认为低音长号的曲目
  - giantmidi-000776 | 为圆号、低音长号与钢琴而作的三重奏 —— 低音长号在室内乐里的写法
  - pdmx-001338 | Trombone Concerto —— **次中音长号**的协奏曲，可对照两支的音区与音色差别
sources:
  - 结构依通行制琴资料：管径比次中音长号更粗，喇叭口更大；滑管 + **一至两个阀门**（常见为 F 附属管，部分另加低音 G♭ 管）
  - 「音域约 B♭1–B♭4」依通行配器资料
  - 「阀门的作用是扩展低音区（把位 7 无法到达的音靠阀门补齐）」依管乐器声学
  - 「低音长号与次中音长号是两支独立的乐器，管径与喇叭口都不同」依乐器制作与配器通识
updated: 2026-09-26
---

::: zh
低音长号不是"更大的长号"，而是长号族里一支**独立的乐器**：
**管径更粗、喇叭口更大**，并且**加装了阀门**。

它解决的正是[[instrument:trombone|次中音长号]]的一个结构性短板：**把位 7 仍然不够低**，
而滑管再往外拉就够不着了 —— 于是用阀门补上最后一段。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· **唇鸣**（lip-vibrated） |
| **次级类型** | 杯形号嘴 · **滑管 + 一至两个阀门** · 管径更粗 · 按 C 调实音记谱 |
| **所属族** | 西洋 · 铜管（长号族 · 低音支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，低音长号不在其中 |

> ⚠️ **一个概念上的要点**：**阀门在长号上的作用与在[[instrument:trumpet|小号]]上不同。**
> 小号用阀门**代替**滑管（全部音靠阀门组合）；长号用阀门**补充**滑管（只在滑管够不到的地方用）。
> 所以低音长号是**两种技术并存**的一件乐器：
> **主要靠把位，阀门只负责把低音区"补到底"。**

## 结构：更粗的管 + 阀门

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="低音长号的结构：更粗的管身与更大的喇叭口，滑管之外还装有一至两个阀门用于扩展低音区">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">低音长号 · 更粗的管身 + 阀门（扩展低音区）</text>
  </g>
  <rect x="76" y="130" width="32" height="20" rx="7" fill="#17171A" stroke="#9C7A3C" stroke-width="1.4"/>
  <path d="M108,132 L262,120 L262,160 L108,148 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M262,120 L412,106 L412,174 L262,160 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M412,106 C470,100 512,112 536,140 C512,168 470,180 412,174 Z" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <path d="M536,140 L556,116 L564,164 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M156,152 L156,224 C156,246 184,250 204,240" fill="none" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M204,240 L368,240" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M368,240 C392,240 402,226 402,204" fill="none" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M300,174 L300,196 L346,196 L346,174" fill="none" stroke="#E07A3F" stroke-width="8" stroke-linecap="round"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,116 L186,102"/><path d="M186,250 L186,266"/>
    <path d="M486,86 L512,100"/><path d="M186,312 L280,206"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="99" text-anchor="end">杯形号嘴（管径更粗）</text>
    <text x="180" y="269" text-anchor="end" fill="#5B7FA8">滑管（比次中音更粗）</text>
    <text x="518" y="83">更大的喇叭口</text>
    <text x="180" y="315" text-anchor="end" fill="#E07A3F">阀门（F 附属管）</text>
  </g>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">管径与喇叭口更大 → 低音更厚、音量更大；阀门则在滑管够不到的地方接着往下补。</text>
</svg>
```

三处要点：

1. **管径与喇叭口都更大**。这让它在低音区的**厚度与音量**明显超过次中音长号 ——
   而不只是"低几个音"。
2. **阀门接在滑管之后**。踩下阀门会接入一段额外的管，把整个音高降低一个纯四度（F 附属管）。
3. **两种技术共存**。把位仍是主体，阀门只在低音区使用 ——
   这与小号"全靠阀门"的逻辑不同。

## 阀门怎么扩展低音区

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="不加阀门与加阀门时可达最低音的比较：阀门把可及的最低音再往下扩展一个纯四度">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">阀门让最低音再往下走一段</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">不加阀门（只用把位）</text>
  <rect x="70" y="86" width="180" height="24" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <text x="160" y="103" text-anchor="middle" font-size="10.5" fill="#5B7FA8">最低可达 E2（把位 7）</text>
  <text x="160" y="132" text-anchor="middle" font-size="10.5" fill="#6E6A64">滑管再往外就够不着了</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">加阀门（F 附属管）</text>
  <rect x="340" y="86" width="240" height="24" rx="3" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="460" y="103" text-anchor="middle" font-size="10.5" fill="#E07A3F">最低可达 B♭1（比 E2 再低一个纯四度）</text>
  <path d="M300,98 L336,98" stroke="#6E6A64" stroke-width="1.4" stroke-dasharray="4 3"/>
  <path d="M322,90 L336,98 L322,106 Z" fill="#6E6A64"/>
  <text x="20" y="176" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">阀门接入的额外管把整件乐器"整体下移"，于是把位 1 就相当于原来的把位 7 再往下 —— 低音区因此打通。</text>
  <text x="20" y="198" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">有些低音长号再加一个阀门（G♭ 管），进一步补齐阀门区的音准与音孔空缺。</text>
  <text x="20" y="224" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">注意：这与小号「三个阀门组合出七种管长」是「同一原理的不同用法」 —— 一个是主角，一个是补丁。</text>
</svg>
```

**它与次中音长号的差别可以归纳成两条**：

| | 次中音长号 | 低音长号 |
|---|---|---|
| 管径 | 较细 | **更粗** |
| 喇叭口 | 较小 | **更大** |
| 阀门 | 通常无 | **一至两个** |
| 最低音 | E2（把位 7） | **B♭1**（阀门） |
| 角色 | 中音声部 | **低音骨干** |

## 音域

```range
{"range":"B♭1–B♭4","common":"B♭1–F3","caption":"低音长号的音域","caption_en":"Bass trombone range","note":"低音长号在管弦乐里按 C 调实音记谱。音域约 B♭1–B♭4 —— 下方那段（B♭1 到 E2）需要阀门才能到达。它是长号声部的低音骨干。"}
```

- **实音 B♭1–B♭4**，约三个八度；其中**下方的纯四度靠阀门**。
- **常用区 B♭1–F3**：它的工作重心全在低音区。
- **高音区（B♭4 以上）** 能吹，但音色会变薄 —— 那一段留给次中音长号。

## 音色与听辨

四条线索：

1. **比次中音长号更厚、更暗、更"沉"**。管径与喇叭口的差别直接反映在这里。
2. **低音区极有分量**。管弦乐里它常与[[instrument:tuba|大号]]一起构成低音的"双层底"。
3. **仍然保留长号的语言**。滑音、替用把位、弱音器 —— 这些它都有，只是低音区更慢、更重。
4. **音量可观**。它是铜管组里少数能在极低音区保持大音量的乐器之一。

```audiolab
{"type":"instrument","gm":"Trombone","synth":"brass","phrase":["B♭1","B♭2","F2","B♭2","F3"],"label":"低音长号的低音区：B♭1 到 F3","label_en":"The bass trombone's low register — B♭1 up to F3","hint":"注意比次中音长号更厚更沉的音色 —— 通用音色表里没有低音长号，这里借长号音色近似","hint_en":"Hear the extra weight and depth. General MIDI has no bass trombone, so a tenor sample stands in."}
```

> ⚠️ **关于试听**：通用音色表（General MIDI）里**没有低音长号**。
> 上面播放的是**次中音长号**音色 —— 音区接近，但**管径带来的厚度听不到。**

## 演奏技法

- **阀门与把位的配合**是核心技艺：同一个音常有"把位方案"与"阀门方案"两种选择，
  演奏者要按乐句与音准需要取舍。
- **耗气量极大**。更粗的管径与更低的音区需要充沛的气流。
- **替用把位仍然重要**，尤其在快速乐句里减少滑管的移动距离。
- **弱音器**可用，但在极低音区效果有限。

## 家族与近亲

| 乐器 | 阀门 | 音域（实音） | 常用处 |
|---|---|---|---|
| 高音长号 | 无 | 约 B♭3–B♭5 | 罕见，历史乐器 |
| [[instrument:trombone\|次中音长号]] | 通常无 | E2–B♭4 | 标准配置 |
| **低音长号** | **一至两个** | B♭1–B♭4 | 低音骨干 |
| [[instrument:tuba\|大号]] | 四至六 | D1–F4 | 低音基础 |
| [[instrument:euphonium\|上低音号]] | 三至四 | A1–B♭4 | 管乐团中低音 |

**低音长号与[[instrument:euphonium|上低音号]]、[[instrument:tuba|大号]]共享同一段音区**，
但三者分工清楚：**低音长号给低音线条"棱角"，上低音号给它"柔和"，大号给它"地基"。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 19 世纪 | 管径逐渐加大的长号出现；三支长号的编制（两中一低）在管弦乐里定型 |
| 19 世纪后期 | **阀门（F 附属管）**被加到低音长号上，低音区得以打通 |
| 20 世纪 | 低音长号成为管弦乐与管乐团的标准配置；管径与阀门方案逐步统一 |
| 20 世纪中后期 | 第二个阀门（G♭ 管）出现在部分型号上；爵士大乐队里它也承担低音声部 |

## 常见误解

- **"低音长号就是更大的次中音长号。"** 管径与喇叭口都不同，还有阀门 ——
  它是**独立的乐器**，需要专门练习。
- **"阀门是用来吹快速乐句的。"** 它的主要作用是**扩展低音区**（补齐滑管够不到的音）。
- **"有了阀门就不需要把位了。"** 恰恰相反：**把位仍是主体**，阀门只在低音区补位。
- **"它只是低音声部的填充。"** 它有独奏文献，也在爵士大乐队里承担实际的低音线条。
- **"通用音色表里有它。"** General MIDI 里**没有**低音长号，只能借次中音近似（本页试听件即如此）。

## 下一步

长号族到这里就齐了。铜管组还剩三件：
[[instrument:euphonium|上低音号]] · [[instrument:sousaphone|苏萨号]] ·
[[instrument:wagner-tuba|瓦格纳大号]]。

前两件是"音区介于长号与大号之间"与"为行进而改造的大号"，
最后一件则是**号嘴与管身可以分别选配**的实证 —— 值得单独看。
:::

::: en
The bass trombone is not "a bigger trombone" but a **separate instrument** in the family: **a wider bore,
a larger bell**, and **valve attachments**.

It solves a structural shortcoming of the [[instrument:trombone|tenor trombone]]: **position 7 is still not
low enough**, and the slide cannot reach further — so a valve supplies the last stretch.

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · **lip-vibrated** |
| **Sub-type** | Cup mouthpiece · **slide plus one or two valves** · wider bore · written in C at pitch |
| **Family** | Western · Brass (trombone family, bass branch) |
| **Bayin** | Not applicable — a Chinese system; the bass trombone is outside it |

> ⚠️ **One conceptual point**: **a valve does a different job on a trombone than on a
> [[instrument:trumpet|trumpet]].** A trumpet's valves **replace** the slide (all notes come from valve
> combinations); a trombone's valve **supplements** it (used only where the slide cannot reach).
> So the bass trombone is an instrument where **two technologies coexist**:
> **positions do the main work, and the valve only extends the bottom.**

## Structure: a wider tube plus a valve

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bass trombone parts: a wider bore and larger bell, with one or two valve attachments beside the slide">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Bass trombone — a wider bore plus valve attachments</text>
  </g>
  <rect x="76" y="130" width="32" height="20" rx="7" fill="#17171A" stroke="#9C7A3C" stroke-width="1.4"/>
  <path d="M108,132 L262,120 L262,160 L108,148 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M262,120 L412,106 L412,174 L262,160 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M412,106 C470,100 512,112 536,140 C512,168 470,180 412,174 Z" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <path d="M536,140 L556,116 L564,164 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M156,152 L156,224 C156,246 184,250 204,240" fill="none" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M204,240 L368,240" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M368,240 C392,240 402,226 402,204" fill="none" stroke="#5B7FA8" stroke-width="11" stroke-linecap="round"/>
  <path d="M300,174 L300,196 L346,196 L346,174" fill="none" stroke="#E07A3F" stroke-width="8" stroke-linecap="round"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,116 L186,102"/><path d="M186,250 L186,266"/>
    <path d="M486,86 L512,100"/><path d="M186,312 L280,206"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="99" text-anchor="end">Cup mouthpiece (wider bore)</text>
    <text x="180" y="269" text-anchor="end" fill="#5B7FA8">Slide (wider than a tenor's)</text>
    <text x="518" y="83">A larger bell</text>
    <text x="180" y="315" text-anchor="end" fill="#E07A3F">Valve (F attachment)</text>
  </g>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A wider bore and bell mean more weight and volume down low; the valve continues where the slide stops.</text>
</svg>
```

Three points:

1. **A wider bore and a larger bell**, giving clearly more **weight and volume** in the low register than a
   tenor — not merely "a few notes lower".
2. **The valve sits after the slide.** Engaging it routes air through extra tubing, lowering everything by a
   perfect fourth (the F attachment).
3. **Two technologies coexist**: positions remain the main system, and the valve is used only down low —
   unlike a trumpet, where valves do everything.

## How a valve extends the low register

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Lowest reachable notes compared with and without a valve: the valve extends the bottom by a perfect fourth">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">A valve takes the bottom a stretch further down</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">No valve (positions only)</text>
  <rect x="70" y="86" width="180" height="24" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <text x="160" y="103" text-anchor="middle" font-size="10.5" fill="#5B7FA8">lowest note E2 (position 7)</text>
  <text x="160" y="132" text-anchor="middle" font-size="10.5" fill="#6E6A64">the slide simply cannot reach further</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">With valve (F attachment)</text>
  <rect x="340" y="86" width="240" height="24" rx="3" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="460" y="103" text-anchor="middle" font-size="10.5" fill="#E07A3F">lowest note B♭1 (a fourth lower)</text>
  <path d="M300,98 L336,98" stroke="#6E6A64" stroke-width="1.4" stroke-dasharray="4 3"/>
  <path d="M322,90 L336,98 L322,106 Z" fill="#6E6A64"/>
  <text x="20" y="176" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The valve shifts the whole instrument down, so position 1 reaches past position 7 — opening the low register.</text>
  <text x="20" y="198" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Some bass trombones add a second valve (a G♭ attachment) to fill in tuning and gaps in the valve register.</text>
  <text x="20" y="224" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Note this is the same principle as a trumpet's valves — one is the main system, the other a patch.</text>
</svg>
```

**The differences from a tenor trombone reduce to two**:

| | Tenor trombone | Bass trombone |
|---|---|---|
| Bore | narrower | **wider** |
| Bell | smaller | **larger** |
| Valves | usually none | **one or two** |
| Lowest note | E2 (position 7) | **B♭1** (valve) |
| Role | the middle voice | **the bass backbone** |

## Range

```range
{"range":"B♭1–B♭4","common":"B♭1–F3","caption":"低音长号的音域","caption_en":"Bass trombone range","note":"低音长号在管弦乐里按 C 调实音记谱。音域约 B♭1–B♭4 —— 下方那段（B♭1 到 E2）需要阀门才能到达。它是长号声部的低音骨干。"}
```

- **Sounding B♭1–B♭4**, about three octaves; the **lower fourth needs the valve**.
- **The working register is B♭1–F3**: its weight is entirely low.
- **Above B♭4** it plays, but thinner — that region belongs to the tenor.

## Timbre, and how to hear it

Four cues:

1. **Thicker, darker, heavier** than a tenor trombone — the bore and bell difference showing directly.
2. **Enormous low-register weight**; orchestras often pair it with a [[instrument:tuba|tuba]] for a double
   bottom.
3. **Still speaks the trombone's language** — glissando, alternate positions, mutes — only slower and heavier
   down low.
4. **Considerable volume**, one of the few brass that stays loud in the deepest register.

```audiolab
{"type":"instrument","gm":"Trombone","synth":"brass","phrase":["B♭1","B♭2","F2","B♭2","F3"],"label":"低音长号的低音区：B♭1 到 F3","label_en":"The bass trombone's low register — B♭1 up to F3","hint":"注意比次中音长号更厚更沉的音色 —— 通用音色表里没有低音长号，这里借长号音色近似","hint_en":"Hear the extra weight and depth. General MIDI has no bass trombone, so a tenor sample stands in."}
```

> ⚠️ **On the audio**: the General MIDI set has **no bass trombone**. A **tenor trombone** sample plays
> above — the register is close, but **the extra weight of the wider bore is absent.**

## Playing techniques

- **Coordinating valve and slide** is the core skill: many notes have both a position solution and a valve
  solution, chosen for phrasing and intonation.
- **A very large air requirement** for a wider bore and a lower register.
- **Alternate positions still matter**, especially to shorten slide travel in fast passages.
- **Mutes** work, but with limited effect very low down.

## The family

| Instrument | Valves | Range (sounding) | Usual role |
|---|---|---|---|
| Soprano trombone | none | about B♭3–B♭5 | rare, historical |
| [[instrument:trombone\|Tenor trombone]] | usually none | E2–B♭4 | the standard |
| **Bass trombone** | **one or two** | B♭1–B♭4 | the bass backbone |
| [[instrument:tuba\|Tuba]] | four to six | D1–F4 | the bass foundation |
| [[instrument:euphonium\|Euphonium]] | three to four | A1–B♭4 | band tenor-bass |

**The bass trombone, [[instrument:euphonium|euphonium]] and [[instrument:tuba|tuba]] share a register**, but
their jobs are distinct: **the bass trombone gives the low line an edge, the euphonium softness, the tuba a
foundation.**

## History

| Period | State |
|---|---|
| 19th c. | trombones with wider bores appear; the three-trombone section (two tenor, one bass) settles in orchestras |
| Late 19th c. | the **F attachment valve** is added to the bass trombone, opening the low register |
| 20th c. | it becomes standard in orchestras and bands; bore and valve practice gradually standardise |
| Mid–late 20th c. | a second valve (G♭) appears on some models; it also takes the bass in jazz big bands |

## Common misconceptions

- **"A bass trombone is a bigger tenor."** Bore, bell and valves all differ — it is a **separate instrument**
  needing its own practice.
- **"The valve is for fast passages."** Its main job is **extending the low register** (notes the slide cannot
  reach).
- **"With a valve you no longer need positions."** The opposite: **positions do the main work**, and the valve
  only extends the bottom.
- **"It merely fills in the bass."** It has a solo repertoire and carries real bass lines in jazz big bands.
- **"General MIDI has one."** It does not; a tenor sample is the only stand-in (as on this page).

## Next

The trombone family is complete. Three brass remain: the [[instrument:euphonium|euphonium]], the
[[instrument:sousaphone|sousaphone]], and the [[instrument:wagner-tuba|Wagner tuba]].

The first two are "a register between trombone and tuba" and "a tuba rebuilt for marching". The last is the
proof that **mouthpiece and body can be chosen separately** — worth its own entry.
:::
