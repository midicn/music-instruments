---
id: harmonica
site: inst
cat: I5
title: 口琴
title_en: Harmonica
summary: 靠呼吸驱动的自由簧乐器，吹与吸都能发声，可用弯音得到半音
summary_en: A breath-driven free-reed instrument that sounds on both blow and draw, with bends for semitones
level: standard
tags: [乐器, 键盘, 西洋, 世界]
tags_en: [instrument, keyboard, western, world]
alias: [口琴, harmonica, 口琴（十孔）, 蓝调口琴, 口簧（误称）]
order: 85
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:accordion]]"
  - "[[instrument:harmonium]]"
  - "[[instrument:organ]]"
  - "[[instrument:pan-flute]]"
instances:
  - pdmx-000322 | 鲁特琴与竖笛的协奏曲 —— 巴洛克室内乐编制，可对照"旋律 + 伴奏"的格局
  - norbeck-001125 | Yakety Sax —— 流行音乐里独奏乐器的语汇，可对照口琴的独奏传统
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— 独奏乐器的写法，可作旋律语汇的参照
sources:
  - 结构依通行乐器资料：一排**自由簧（free reed）**装在**气道板**上，由**呼吸**（吹与吸）驱动；标准形制为**十孔**（另有多种其他形制）
  - 「口琴属**气鸣**乐器（自由簧）」依 Hornbostel–Sachs 分类
  - 「十孔口琴的音域约 C4–C7；**吹与吸各自对应不同的音**，因此一个孔可以得到两个音」依通行乐器资料
  - 「**弯音（bending）**：靠口腔与气流改变簧片振动状态，使音高下降，可得半音 —— 这是口琴最独特的技术」依乐器声学与演奏通识
updated: 2026-09-26
---

::: zh
口琴是自由簧一族里**最便携的一件** —— 它能放进口袋。
但它真正的独特之处不在体积，而在于一个别的管乐器都没有的事实：
**它靠呼吸驱动，而且"吹"与"吸"都能发声。**

所以它一件乐器上同时有**两组音**：**吹音**与**吸音**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）—— 气流使**自由簧**振动 |
| **次级类型** | 呼吸（吹 + 吸）驱动 · 一排自由簧装在气道板上 · 一个孔两个音 |
| **所属族** | 西洋 · 键盘（自由簧支系）· 同时是**世界乐器** |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，口琴不在其中 |

> ⚠️ **一个概念上的要点**：**"吹"与"吸"都发声，这在管乐器里极为少见。**
> 长笛、竖笛、小号、萨克斯……几乎所有管乐器**只在一个气流方向上发声**。
> 口琴打破了这一条，因为它的簧片是**双向的**：
> **吹时一片簧开，吸时另一片簧开** —— 于是同一个孔可以给出两个音。
> 这个结构带来了两个后果：
> **① 音阶排列不是顺序的**（吹音与吸音交错，构成一个和弦式的排列）；
> **② 可以用"弯音"在中间取值**（见下节）。

## 结构：气道板上的自由簧

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="口琴的结构：气道板上并排的自由簧、吹与吸两个方向的簧片，以及一排音孔">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">口琴 · 结构（气道板 + 双向自由簧）</text>
  </g>
  <rect x="80" y="120" width="420" height="46" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <g stroke="#E07A3F" stroke-width="2.6">
    <rect x="96" y="104" width="10" height="20" rx="4"/>
    <rect x="136" y="104" width="10" height="20" rx="4"/>
    <rect x="176" y="104" width="10" height="20" rx="4"/>
    <rect x="216" y="104" width="10" height="20" rx="4"/>
    <rect x="256" y="104" width="10" height="20" rx="4"/>
    <rect x="296" y="104" width="10" height="20" rx="4"/>
    <rect x="336" y="104" width="10" height="20" rx="4"/>
    <rect x="376" y="104" width="10" height="20" rx="4"/>
    <rect x="416" y="104" width="10" height="20" rx="4"/>
    <rect x="456" y="104" width="10" height="20" rx="4"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="2.6">
    <rect x="116" y="162" width="10" height="20" rx="4"/>
    <rect x="156" y="162" width="10" height="20" rx="4"/>
    <rect x="196" y="162" width="10" height="20" rx="4"/>
    <rect x="236" y="162" width="10" height="20" rx="4"/>
    <rect x="276" y="162" width="10" height="20" rx="4"/>
    <rect x="316" y="162" width="10" height="20" rx="4"/>
    <rect x="356" y="162" width="10" height="20" rx="4"/>
    <rect x="396" y="162" width="10" height="20" rx="4"/>
    <rect x="436" y="162" width="10" height="20" rx="4"/>
    <rect x="476" y="162" width="10" height="20" rx="4"/>
  </g>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M96,126 L96,160"/><path d="M136,126 L136,160"/><path d="M176,126 L176,160"/>
    <path d="M216,126 L216,160"/><path d="M256,126 L256,160"/><path d="M296,126 L296,160"/>
    <path d="M336,126 L336,160"/><path d="M376,126 L376,160"/><path d="M416,126 L416,160"/>
    <path d="M456,126 L456,160"/>
  </g>
  <path d="M60,132 L74,132" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M64,124 L60,132 L64,140" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M60,176 L74,176" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M64,168 L60,176 L64,184" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,72 L200,100"/><path d="M186,220 L200,186"/>
    <path d="M486,100 L440,106"/><path d="M486,190 L440,172"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="69" text-anchor="end" fill="#E07A3F">吹音簧片（吹气时开）</text>
    <text x="180" y="223" text-anchor="end" fill="#5B7FA8">吸音簧片（吸气时开）</text>
    <text x="492" y="97">气道板（每孔两个簧）</text>
    <text x="492" y="193">同一个孔给出两个音</text>
  </g>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">吹气时上排簧片开、吸气时下排簧片开 —— 所以"一个孔两个音"不是设计失误，而是它的基本结构。</text>
  <text x="20" y="274" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">其余所有管乐器都只在单一气流方向上发声，这使口琴成为管乐器里的一个特例。</text>
</svg>
```

三处要点：

1. **每个孔有两片簧**：一片在吹气时开、一片在吸气时开。
2. **所以一孔两个音**，而这直接决定了它的**音阶排列方式**（见下节）。
3. **呼吸就是它的"弓"**。力度、时值、连断都由呼吸控制 ——
   这也是它最"身体化"的一点：**演奏者用自己的呼吸作为动力**。

## 吹吸音阶：为什么它不是顺序排列

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="十孔口琴的吹音与吸音排列：吹音构成主和弦音，吸音穿插其间提供经过音">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">十孔口琴的音阶排列（以 C 调为例）</text>
  </g>
  <g stroke="#343439" stroke-width="1.4">
    <path d="M70,72 L580,72"/>
  </g>
  <g fill="#E07A3F" stroke="#E07A3F">
    <rect x="92" y="96" width="34" height="20" rx="4"/>
    <rect x="188" y="96" width="34" height="20" rx="4"/>
    <rect x="284" y="96" width="34" height="20" rx="4"/>
    <rect x="380" y="96" width="34" height="20" rx="4"/>
    <rect x="476" y="96" width="34" height="20" rx="4"/>
  </g>
  <g fill="#5B7FA8" stroke="#5B7FA8">
    <rect x="140" y="140" width="34" height="20" rx="4"/>
    <rect x="236" y="140" width="34" height="20" rx="4"/>
    <rect x="332" y="140" width="34" height="20" rx="4"/>
    <rect x="428" y="140" width="34" height="20" rx="4"/>
    <rect x="524" y="140" width="34" height="20" rx="4"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#0E0E10" text-anchor="middle">
    <text x="109" y="111">C4</text><text x="205" y="111">E4</text>
    <text x="301" y="111">G4</text><text x="397" y="111">C5</text>
    <text x="493" y="111">E5</text>
    <text x="157" y="155">D4</text><text x="253" y="155">G4</text>
    <text x="349" y="155">B4</text><text x="445" y="155">D5</text>
    <text x="541" y="155">F5</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="109" y="188">孔 1</text><text x="157" y="188">孔 2</text>
    <text x="205" y="188">孔 3</text><text x="253" y="188">孔 4</text>
    <text x="301" y="188">孔 5</text><text x="349" y="188">孔 6</text>
    <text x="397" y="188">孔 7</text><text x="445" y="188">孔 8</text>
    <text x="493" y="188">孔 9</text><text x="541" y="188">孔 10</text>
  </g>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">上排（吹音）：C-E-G-C-E… —— 是主和弦的音，所以连续吹气就能得到和弦。</text>
  <text x="20" y="248" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">下排（吸音）：D-G-B-D-F… —— 穿插在吹音之间，提供经过音与另一组和声。</text>
  <text x="20" y="274" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以口琴的音阶不是"顺着排"的：「吹与吸交错」，这是它与所有其他管乐器在排列逻辑上的根本差别。</text>
</svg>
```

**这张图解释了为什么口琴"上手容易、精进很难"**：
- **连续吹或连续吸**能得到和弦 → 所以初学者很容易吹出"好听的声音"；
- 但要**吹出完整的旋律**，必须精确地交替吹吸 → 技术难度在这里。

## 弯音：口琴最独特的技术

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="弯音技术：通过改变口腔与气流使音高下降，得到排列中缺失的半音">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">弯音（bending）：把本该缺失的半音"拉"出来</text>
  </g>
  <g stroke="#E07A3F" stroke-width="6" stroke-linecap="round">
    <path d="M100,110 L100,88"/>
    <path d="M180,110 L180,88"/>
    <path d="M260,110 L260,88"/>
  </g>
  <path d="M80,110 L290,110" stroke="#343439" stroke-width="1.4"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="100" y="130">孔 1 吹</text><text x="180" y="130">孔 1 吸</text><text x="260" y="130">孔 2 吹</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="3" stroke-linecap="round" stroke-dasharray="4 3">
    <path d="M140,92 L140,110"/>
    <path d="M220,92 L220,110"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">
    <text x="140" y="86">弯音</text><text x="220" y="86">弯音</text>
  </g>
  <text x="20" y="176" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">排列里相邻两个音之间的半音（如 C 与 D 之间的 C♯）本来"没有孔" ——</text>
  <text x="20" y="198" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">但改变口腔形状与气流，可以让簧片以更低的频率振动 → 音高下降 → 「把半音"弯"出来」。</text>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">这是口琴在蓝调里表达力的核心：「吹与吸之间的滑动、以及弯音带来的"哭腔"」。</text>
  <text x="20" y="250" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以一件只有十孔、音阶"缺半音"的乐器，靠演奏技术补回了完整的表现范围。</text>
</svg>
```

**弯音的意义**：口琴的排列里**本来缺半音**；
演奏者用口腔与气流把音高"拉低"，从而补出那些音。
**这是"演奏技术弥补乐器结构限制"的一个典型例子** ——
也说明口琴的表现力很大一部分不在乐器上，而在演奏者身上。

## 音域

```range
{"range":"C4–C7","common":"C4–C5","caption":"十孔口琴的音域","caption_en":"Ten-hole harmonica range","note":"口琴属气鸣乐器（自由簧）。十孔口琴的音域约 C4–C7（视形制）；常用区 C4–C5。吹音与吸音交错构成排列，另有多种其他形制（半音阶口琴 · 低音口琴等）。"}
```

- **约 C4–C7**（十孔），常用区 C4–C5。
- **排列是"吹吸交错"的**，所以看谱时要确认该音是吹还是吸。
- **另有多种形制**：半音阶口琴（有按键，可奏全部半音）、低音口琴、复音口琴等 ——
  它们各有不同的排列与用途。

## 音色与听辨

四条线索：

1. **明亮、带簧片的"甜"**，但比[[instrument:accordion|手风琴]]更窄更集中 ——
   它没有共鸣箱。
2. **力度由呼吸控制**，所以能做细腻的强弱与音头。
3. **弯音是它的签名**。那种"下滑"与"哭腔"几乎只属于口琴。
4. **手（双手罩住口琴）也能改变音色**。手掌的开合会改变共鸣与音量 ——
   这是电声时代之前就有的"哇音"效果。

```audiolab
{"type":"instrument","gm":"Harmonica","synth":"blown","phrase":["C4","E4","G4","C5","E5"],"label":"十孔口琴的吹音：C4 到 E5","label_en":"Ten-hole harmonica — the blow notes, C4 up to E5","hint":"注意音色的集中与簧片的甜 —— 而且这些音都是「吹」出来的，旁边还有一组「吸」的音","hint_en":"Hear the focused, reedy sweetness — and note these are all blow notes, with a set of draw notes alongside."}
```

## 演奏技法

- **呼吸是全部基础**。力度、时值、连断、音头都由呼吸控制。
- **吹与吸要精确交替**（旋律在两组音之间穿梭）。
- **弯音（bending）**：改变口腔与气流使音高下降 —— 蓝调语言的核心。
- **超吹（overblow）**：更高级的技术，用来得到排列里更高的音。
- **手罩（hand cupping）**：双手合拢在口琴外，开合手掌改变音色。
- **舌堵（tongue blocking）**：用舌头挡住部分孔，得到单音或和弦 —— 与"唇堵"并列的两种基本方法。

## 家族与近亲

| 乐器 | 发声体 | 供气 | 便携性 | 音域 |
|---|---|---|---|---|
| [[instrument:organ\|管风琴]] | 空气柱 | 机械鼓风 | 不可移动 | C2–C7 |
| [[instrument:harmonium\|簧风琴]] | 自由簧 | 脚踏 | 较重 | C2–C6 |
| [[instrument:accordion\|手风琴]] | 自由簧 | 左臂手动 | 便携 | F3–A6 |
| **口琴** | 自由簧 | **呼吸** | **口袋** | **C4–C7** |

**同一原理（自由簧）的四种送气方式**：
**机械 · 脚 · 手臂 · 呼吸** ——
送气方式越"贴身"，乐器越小、越便携，但音域与音量也越有限。
**这是一条清晰的工程取舍链。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 1820 年代（欧洲） | 自由簧技术成熟后出现口琴类的簧片乐器；很快工业化生产 |
| 19 世纪 | 大量出口与传播；在德国、美国等地成为大众乐器 |
| 19—20 世纪初 | 随移民与贸易进入美洲、亚洲、非洲；在美国南部与**蓝调音乐**结合 |
| 20 世纪 | 成为**蓝调 · 民谣 · 乡村 · 摇滚**的常用乐器；也用于古典与当代作品 |
| 20 世纪后期至今 | 世界范围内的普及乐器；也有半音阶口琴等专业形制与专门的演奏家 |

**它有一条与其他自由簧乐器相同的传播路径**：
**在欧洲诞生，在美国南部的蓝调里获得灵魂。**
这与[[instrument:harmonium|簧风琴]]"在印度生根"、[[instrument:accordion|手风琴]]"在探戈与卡津音乐里成形"，是同一种现象。

## 常见误解

- **"口琴是玩具。"** 它有完整的技术体系（弯音 · 超吹 · 舌堵 · 手罩），
  在蓝调里有极深的表现传统，也有半音阶口琴等专业形制。
- **"它就是吹气发声。"** **吹与吸都发声**，一孔两个音 ——
  这是它与所有其他管乐器的根本区别。
- **"它的音阶是顺序排列的。"** 不是：吹音与吸音**交错**，
  连续吹或连续吸得到的是和弦。
- **"它只能演奏简单的旋律。"** 靠弯音与超吹可以覆盖完整的半音；
  半音阶口琴进一步解决了这个问题。
- **"它与手风琴无关。"** 两者同属**自由簧**一族，
  差别只在送气方式（呼吸 vs 手臂）。

## 下一步

**键盘组到这里全部完成**（钢琴 · 大键琴 · 击弦古钢琴 · 管风琴 · 簧风琴 · 手风琴 · 口琴）。

接下来进入**早期乐器**一组：[[instrument:shawm|肖姆管]] · [[instrument:crumhorn|克鲁姆管]] ·
[[instrument:racket|拉凯特管]] —— 三件都是"**双簧 + 管身变化**"的产物，
正好可以看到同一个原理在不同形制上的三种解法。
:::

::: en
The harmonica is the **most portable** member of the free-reed family — it fits in a pocket. But its real
distinction is not size; it is a fact no other wind instrument offers: **it is driven by breathing, and both
blowing and drawing sound.**

So one instrument carries **two sets of notes**: **blow notes** and **draw notes.**

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** — the air sets **free reeds** vibrating |
| **Sub-type** | Breath-driven (blow + draw) · a row of free reeds on a reed plate · two notes per hole |
| **Family** | Western · Keyboard (free-reed branch) · also a **world instrument** |
| **Bayin** | Not applicable — a Chinese system; the harmonica is outside it |

> ⚠️ **One conceptual point**: **sounding on both blow and draw is extremely rare among wind instruments.**
> Flute, recorder, trumpet, saxophone — almost every wind instrument sounds in **one airflow direction only.**
> The harmonica breaks that rule because its reeds are **two-directional**: **blowing opens one reed, drawing
> opens another** — so one hole yields two notes. Two consequences follow:
> **① the scale is not in order** (blow and draw notes interleave, forming a chord-like layout);
> **② bends are possible** (see below).

## Structure: free reeds on a reed plate

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Harmonica structure: free reeds side by side on a reed plate, blow and draw reed sets, and a row of holes">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Harmonica — structure (reed plate plus two-directional free reeds)</text>
  </g>
  <rect x="80" y="120" width="420" height="46" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <g stroke="#E07A3F" stroke-width="2.6">
    <rect x="96" y="104" width="10" height="20" rx="4"/>
    <rect x="136" y="104" width="10" height="20" rx="4"/>
    <rect x="176" y="104" width="10" height="20" rx="4"/>
    <rect x="216" y="104" width="10" height="20" rx="4"/>
    <rect x="256" y="104" width="10" height="20" rx="4"/>
    <rect x="296" y="104" width="10" height="20" rx="4"/>
    <rect x="336" y="104" width="10" height="20" rx="4"/>
    <rect x="376" y="104" width="10" height="20" rx="4"/>
    <rect x="416" y="104" width="10" height="20" rx="4"/>
    <rect x="456" y="104" width="10" height="20" rx="4"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="2.6">
    <rect x="116" y="162" width="10" height="20" rx="4"/>
    <rect x="156" y="162" width="10" height="20" rx="4"/>
    <rect x="196" y="162" width="10" height="20" rx="4"/>
    <rect x="236" y="162" width="10" height="20" rx="4"/>
    <rect x="276" y="162" width="10" height="20" rx="4"/>
    <rect x="316" y="162" width="10" height="20" rx="4"/>
    <rect x="356" y="162" width="10" height="20" rx="4"/>
    <rect x="396" y="162" width="10" height="20" rx="4"/>
    <rect x="436" y="162" width="10" height="20" rx="4"/>
    <rect x="476" y="162" width="10" height="20" rx="4"/>
  </g>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M96,126 L96,160"/><path d="M136,126 L136,160"/><path d="M176,126 L176,160"/>
    <path d="M216,126 L216,160"/><path d="M256,126 L256,160"/><path d="M296,126 L296,160"/>
    <path d="M336,126 L336,160"/><path d="M376,126 L376,160"/><path d="M416,126 L416,160"/>
    <path d="M456,126 L456,160"/>
  </g>
  <path d="M60,132 L74,132" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M64,124 L60,132 L64,140" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M60,176 L74,176" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M64,168 L60,176 L64,184" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,72 L200,100"/><path d="M186,220 L200,186"/>
    <path d="M486,100 L440,106"/><path d="M486,190 L440,172"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="69" text-anchor="end" fill="#E07A3F">Blow reeds</text>
    <text x="180" y="223" text-anchor="end" fill="#5B7FA8">Draw reeds</text>
    <text x="492" y="97">Two reeds per hole</text>
    <text x="492" y="193">One hole, two notes</text>
  </g>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Blowing opens the upper reed, drawing opens the lower one — so "two notes per hole" is basic structure, not a flaw.</text>
  <text x="20" y="274" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Every other wind instrument sounds in one airflow direction only, which makes the harmonica an exception.</text>
</svg>
```

Three points:

1. **Two reeds per hole**: one opens on blowing, one on drawing.
2. **Hence two notes per hole**, which directly determines its **layout** (next section).
3. **Breath is its bow.** Dynamics, duration and articulation all come from breathing — the most "bodily"
   aspect: **the player's own breath is the power source.**

## Blow and draw: why it is not in order

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The blow and draw layout of a ten-hole harmonica: blow notes form the tonic chord while draw notes interleave as passing tones">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">The ten-hole harmonica layout (in C)</text>
  </g>
  <g stroke="#343439" stroke-width="1.4">
    <path d="M70,72 L580,72"/>
  </g>
  <g fill="#E07A3F" stroke="#E07A3F">
    <rect x="92" y="96" width="34" height="20" rx="4"/>
    <rect x="188" y="96" width="34" height="20" rx="4"/>
    <rect x="284" y="96" width="34" height="20" rx="4"/>
    <rect x="380" y="96" width="34" height="20" rx="4"/>
    <rect x="476" y="96" width="34" height="20" rx="4"/>
  </g>
  <g fill="#5B7FA8" stroke="#5B7FA8">
    <rect x="140" y="140" width="34" height="20" rx="4"/>
    <rect x="236" y="140" width="34" height="20" rx="4"/>
    <rect x="332" y="140" width="34" height="20" rx="4"/>
    <rect x="428" y="140" width="34" height="20" rx="4"/>
    <rect x="524" y="140" width="34" height="20" rx="4"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#0E0E10" text-anchor="middle">
    <text x="109" y="111">C4</text><text x="205" y="111">E4</text>
    <text x="301" y="111">G4</text><text x="397" y="111">C5</text>
    <text x="493" y="111">E5</text>
    <text x="157" y="155">D4</text><text x="253" y="155">G4</text>
    <text x="349" y="155">B4</text><text x="445" y="155">D5</text>
    <text x="541" y="155">F5</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="109" y="188">hole 1</text><text x="157" y="188">hole 2</text>
    <text x="205" y="188">hole 3</text><text x="253" y="188">hole 4</text>
    <text x="301" y="188">hole 5</text><text x="349" y="188">hole 6</text>
    <text x="397" y="188">hole 7</text><text x="445" y="188">hole 8</text>
    <text x="493" y="188">hole 9</text><text x="541" y="188">hole 10</text>
  </g>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Blow notes: C-E-G-C-E… — the tonic chord, so blowing continuously gives a chord.</text>
  <text x="20" y="248" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Draw notes: D-G-B-D-F… — interleaved, supplying passing tones and another harmony.</text>
  <text x="20" y="274" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">So the scale is not laid out in order: 「blow and draw alternate」 — a fundamental difference from other winds.</text>
</svg>
```

**This diagram explains why the harmonica is "easy to start, hard to master"**: blowing or drawing
continuously gives chords, so beginners quickly make pleasant sounds; but playing a **full melody** requires
precise alternation of blow and draw — where the difficulty lies.

## Bending: the harmonica's most distinctive technique

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bending: changing the mouth cavity and air stream lowers the pitch to reach semitones missing from the layout">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Bending: pulling out the semitones the layout lacks</text>
  </g>
  <g stroke="#E07A3F" stroke-width="6" stroke-linecap="round">
    <path d="M100,110 L100,88"/>
    <path d="M180,110 L180,88"/>
    <path d="M260,110 L260,88"/>
  </g>
  <path d="M80,110 L290,110" stroke="#343439" stroke-width="1.4"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="100" y="130">hole 1 blow</text><text x="180" y="130">hole 1 draw</text><text x="260" y="130">hole 2 blow</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="3" stroke-linecap="round" stroke-dasharray="4 3">
    <path d="M140,92 L140,110"/>
    <path d="M220,92 L220,110"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">
    <text x="140" y="86">bend</text><text x="220" y="86">bend</text>
  </g>
  <text x="20" y="176" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The semitone between two adjacent notes (C to D needs C♯) has no hole of its own —</text>
  <text x="20" y="198" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">but by reshaping the mouth cavity and air stream the reed can be made to vibrate lower → 「the note bends down」.</text>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">This is the heart of the harmonica's blues expression: 「slides between blow and draw, and the wail of a bend」.</text>
  <text x="20" y="250" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">So a ten-hole instrument with a gappy scale regains a full expressive range through playing technique.</text>
</svg>
```

**What bending means**: the layout **lacks semitones**; the player pulls the pitch down with mouth shape and
air, supplying the missing notes. **A textbook case of technique compensating for structure** — and evidence
that much of the harmonica's expression lives in the player, not the instrument.

## Range

```range
{"range":"C4–C7","common":"C4–C5","caption":"十孔口琴的音域","caption_en":"Ten-hole harmonica range","note":"口琴属气鸣乐器（自由簧）。十孔口琴的音域约 C4–C7（视形制）；常用区 C4–C5。吹音与吸音交错构成排列，另有多种其他形制（半音阶口琴 · 低音口琴等）。"}
```

- **About C4–C7** (ten holes); working register C4–C5.
- **The layout interleaves blow and draw**, so reading music means checking whether a note is blown or drawn.
- **Other forms exist**: chromatic harmonica (with a slide for all semitones), bass harmonica, tremolo
  harmonica — each with its own layout and use.

## Timbre, and how to hear it

Four cues:

1. **Bright, with a reedy sweetness**, but narrower and more focused than an
   [[instrument:accordion|accordion]] — it has no soundbox.
2. **Dynamics come from breathing**, allowing fine shaping and attack.
3. **The bend is its signature**: that slide and wail belong almost exclusively to the harmonica.
4. **The hands change the colour too.** Cupping and opening the hands alters resonance and volume — a "wah"
   effect that predates electronics.

```audiolab
{"type":"instrument","gm":"Harmonica","synth":"blown","phrase":["C4","E4","G4","C5","E5"],"label":"十孔口琴的吹音：C4 到 E5","label_en":"Ten-hole harmonica — the blow notes, C4 up to E5","hint":"注意音色的集中与簧片的甜 —— 而且这些音都是「吹」出来的，旁边还有一组「吸」的音","hint_en":"Hear the focused, reedy sweetness — and note these are all blow notes, with a set of draw notes alongside."}
```

## Playing techniques

- **Breathing is the whole foundation**: dynamics, duration, legato and attack all follow the breath.
- **Precise alternation of blow and draw** (the melody moves between two note sets).
- **Bending**: reshaping the mouth and air stream to lower the pitch — the core of blues language.
- **Overblowing**: a more advanced technique for notes above the basic layout.
- **Hand cupping**: closing and opening the hands around the instrument to change colour.
- **Tongue blocking**: using the tongue to block holes for single notes or chords — one of the two basic
  methods alongside lip pursing.

## The family

| Instrument | Vibrating body | Air supplied by | Portability | Range |
|---|---|---|---|---|
| [[instrument:organ\|Organ]] | air columns | mechanical blower | immovable | C2–C7 |
| [[instrument:harmonium\|Harmonium]] | free reeds | foot | heavy | C2–C6 |
| [[instrument:accordion\|Accordion]] | free reeds | left arm | portable | F3–A6 |
| **Harmonica** | free reeds | **breath** | **pocket-sized** | **C4–C7** |

**One principle (free reed), four ways of supplying air**: **machine · foot · arm · breath** — the more
"personal" the air supply, the smaller and more portable the instrument, and the narrower its range and volume.
**A clear engineering trade-off chain.**

## History

| Period | State |
|---|---|
| 1820s (Europe) | reed instruments of the harmonica kind appear once free-reed technology matures; factory production follows quickly |
| 19th c. | exported and disseminated widely; becomes a popular instrument in Germany, the USA and beyond |
| Late 19th–early 20th c. | travels with migration and trade to the Americas, Asia and Africa; fuses with **blues** in the American South |
| 20th c. | a standard instrument in **blues, folk, country and rock**; also used in classical and contemporary works |
| Late 20th c. onward | a popular instrument worldwide, with professional forms such as the chromatic harmonica and dedicated virtuosos |

**Its path matches the other free-reed instruments**: **born in Europe, given its soul by blues in the American
South** — the same phenomenon as the [[instrument:harmonium|harmonium]] taking root in India and the
[[instrument:accordion|accordion]] maturing in tango and Cajun music.

## Common misconceptions

- **"A harmonica is a toy."** It has a full technique system (bending, overblowing, tongue blocking, hand
  cupping), a deep blues tradition, and professional forms such as the chromatic harmonica.
- **"It just sounds by blowing."** **Blowing and drawing both sound**, two notes per hole — the fundamental
  difference from every other wind instrument.
- **"Its scale is laid out in order."** It is not: blow and draw notes **interleave**, so continuous blowing or
  drawing gives a chord.
- **"It can play only simple tunes."** Bending and overblowing cover the full chromatic range; the chromatic
  harmonica solves it by design.
- **"It is unrelated to the accordion."** Both are **free-reed** instruments, differing only in how the air is
  supplied (breath versus arm).

## Next

**That completes the keyboard group** (piano · harpsichord · clavichord · organ · harmonium · accordion ·
harmonica).

Next comes the **early instruments** group: the [[instrument:shawm|shawm]], the
[[instrument:crumhorn|crumhorn]] and the [[instrument:racket|racket]] — all three are products of
"**double reed plus a modified body**", showing three solutions of one principle.
:::
