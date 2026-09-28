---
id: tuba
site: inst
cat: I3
title: 大号
title_en: Tuba
summary: 管长与管径都最大的常规铜管，管弦乐与管乐团的地音基础
summary_en: The largest common brass — the bass foundation of orchestra and wind band
level: standard
tags: [乐器, 铜管, 西洋]
tags_en: [instrument, brass, western]
alias: [大号, tuba, 低音号, 大喇叭, 低音大号]
order: 47
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:trombone]]"
  - "[[instrument:french-horn]]"
  - "[[instrument:euphonium]]"
  - "[[instrument:ophicleide]]"
instances:
  - giantmidi-008775 | 大号奏鸣曲 —— 欣德米特为它写的独奏作品，是大号独奏文献的代表
  - giantmidi-009783 | 为上低音号与低音大号而作的二重奏 Op.1087 —— 大号族的两件同台
  - giantmidi-006214 | 上低音号协奏曲 —— 同族的另一支（音区比大号高一个八度）
sources:
  - 结构依通行制琴资料：管身展开约 5.5 米，是全族最长；管径最大，**圆锥比例大**，喇叭口宽大且朝上；深杯号嘴；四至六个活塞
  - 「大号在管弦乐里按 C 调实音记谱；英式铜管乐队里按降 B 调移调记谱」依通行配器与铜管乐队惯例
  - 「音域约 D1–F4」依通行配器资料
  - 「低音区泛音间距极大，必须靠更多活塞补齐中间的音」依管乐器声学
  - 「大号在 1835 年取得专利，取代了此前承担低音的奥菲克莱德号」依乐器史
updated: 2026-09-26
---

::: zh
大号是铜管组的地基：**管最长（约 5.5 米）、管径最粗、圆锥比例最大**，
所以它音最低、音色最厚。它在管弦乐与管乐团里承担的是同一个角色 ——
**让整个和声有一个牢靠的底部。**

它身上还有一个别的铜管没有的问题：**低音区的泛音太稀**，
因此它必须比[[instrument:trumpet|小号]]多好几个活塞。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· **唇鸣**（lip-vibrated） |
| **次级类型** | 深杯号嘴 · **四至六活塞** · **圆锥比例最大** · **管弦乐里按 C 调实音记谱** |
| **所属族** | 西洋 · 铜管（大号族 · 低音支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，大号不在其中 |

> ⚠️ **一个概念上的要点**：**同一件乐器可以有两套记谱惯例。**
> 大号在**管弦乐**里按 **C 调实音**记谱（低音谱号）；在**英式铜管乐队**里
> 按**降 B 调移调**记谱。两者指的是同一件乐器，只是读谱方式不同。
> 所以"这件乐器要怎么读谱"这个问题，答案取决于**它在什么编制里** ——
> 这一点在木管批（[[instrument:alto-saxophone|萨克斯]]族的通用指法 vs [[instrument:clarinet|单簧管]]族的分支偏移）
> 也出现过，铜管里则是"编制决定惯例"。

## 结构：最长的管与最多的活塞

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="大号外形与主要部件：深杯号嘴、盘绕的粗大管身、四至六个活塞以及朝上的宽大喇叭口">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">大号 · 外形与主要部件（管最长、管径最粗、活塞最多）</text>
  </g>
  <path d="M150,120 C120,150 118,210 146,248 C176,290 254,300 300,272 C346,244 356,180 328,144 C304,112 250,104 216,124" fill="none" stroke="#17171A" stroke-width="34" stroke-linecap="round"/>
  <path d="M216,124 C190,138 168,138 150,120" fill="none" stroke="#17171A" stroke-width="30" stroke-linecap="round"/>
  <path d="M120,118 L92,110 L96,134 Z" fill="#17171A" stroke="#9C7A3C" stroke-width="1.4"/>
  <path d="M300,272 C356,256 402,204 406,152 C408,124 398,102 380,90 L444,74 C466,100 470,150 458,196 C440,266 366,314 300,320 Z" fill="#17171A" stroke="#343439" stroke-width="1.5"/>
  <ellipse cx="412" cy="82" rx="34" ry="10" fill="#0E0E10" stroke="#343439" stroke-width="1.2"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="250" y="316" width="11" height="34" rx="4"/>
    <rect x="268" y="324" width="11" height="30" rx="4"/>
    <rect x="286" y="330" width="11" height="26" rx="4"/>
    <rect x="304" y="332" width="11" height="24" rx="4"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,104 L128,108"/><path d="M186,200 L172,196"/>
    <path d="M186,336 L240,336"/><path d="M486,110 L444,92"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="101" text-anchor="end">深杯号嘴</text>
    <text x="180" y="203" text-anchor="end" fill="#5B7FA8">管身展开约 5.5 米</text>
    <text x="180" y="339" text-anchor="end" fill="#E07A3F">四个活塞（亦有五至六个）</text>
    <text x="492" y="107">喇叭口朝上</text>
  </g>
  <text x="20" y="376" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">喇叭口朝上是低音乐器的共同做法：低频向下辐射会被地面吸收，朝上才能传出去。</text>
</svg>
```

三处要点：

1. **管最长（约 5.5 米）**，盘绕成一个大圈。这是它音最低的直接原因。
2. **管径最粗、圆锥比例最大**。这两点让它的音色**厚、暗、圆**，
   而不是像[[instrument:trombone|长号]]那样"亮而方正"。
3. **活塞最多（通常四个，也有五到六个）**。为什么需要这么多？见下节。

## 低音区泛音稀，所以要更多活塞

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="小号与大号的泛音分布对比：大号工作在低泛音区，泛音间距大，需要更多活塞补齐中间的音">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一个泛音列，工作音区越高泛音越密</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">小号 · 工作在较高的泛音区</text>
  <g stroke="#5B7FA8" stroke-width="7" stroke-linecap="round">
    <path d="M70,142 L70,116"/><path d="M104,142 L104,124"/>
    <path d="M138,142 L138,130"/><path d="M172,142 L172,134"/>
    <path d="M206,142 L206,137"/><path d="M240,142 L240,139"/>
  </g>
  <path d="M54,142 L258,142" stroke="#343439" stroke-width="1.3"/>
  <text x="160" y="166" text-anchor="middle" font-size="10.5" fill="#A9A49B">泛音挨得近 → 活塞补的空档小</text>
  <text x="160" y="188" text-anchor="middle" font-size="10.5" fill="#5B7FA8">三个活塞够用</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">大号 · 工作在很低的泛音区</text>
  <g stroke="#E07A3F" stroke-width="7" stroke-linecap="round">
    <path d="M370,142 L370,108"/><path d="M470,142 L470,126"/>
    <path d="M540,142 L540,136"/><path d="M576,142 L576,139"/>
  </g>
  <path d="M354,142 L592,142" stroke="#343439" stroke-width="1.3"/>
  <text x="480" y="166" text-anchor="middle" font-size="10.5" fill="#A9A49B">泛音隔得很远 → 活塞要补的空档大</text>
  <text x="480" y="188" text-anchor="middle" font-size="10.5" fill="#E07A3F">需要四个以上活塞</text>
  <text x="20" y="224" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">大号的第 1、2 次泛音之间就是一个八度 —— 这个空档要靠活塞一格一格地填，三个远远不够。</text>
  <text x="20" y="246" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">第四个活塞通常加长一个纯四度，让低音区多出几个可用的音；五六活塞则进一步补齐。</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">这与圆号"管子长所以音准难"是同一条规律的两种表现 —— 都源于泛音列在各音区的疏密不同。</text>
</svg>
```

**这条规律可以在铜管组里通用**：

| 乐器 | 主要工作的泛音区 | 泛音疏密 | 活塞数 |
|---|---|---|---|
| [[instrument:trumpet\|小号]] | 第 2–8 次 | 较密 | 3 |
| [[instrument:trombone\|长号]] | 第 2–6 次 | 中 | 0（滑管连续） |
| [[instrument:french-horn\|圆号]] | 第 3–12 次 | 密（但管长） | 3（+ 拇指阀） |
| **大号** | **第 1–5 次** | **极疏** | **4–6** |

**大号正好相反于圆号**：它的管子最长，但工作在**低泛音区**，
所以泛音稀疏、音准反而比圆号宽容（人对低音的容忍度也更大），
代价则是需要**更多活塞**才能把音凑齐。

## 音域

```range
{"range":"D1–F4","common":"D1–C3","caption":"大号的音域","caption_en":"Tuba range","note":"大号在管弦乐里按 C 调实音记谱（低音谱号）；英式铜管乐队里则按降 B 调移调记谱 —— 同一件乐器两套惯例。标准音域 D1–F4，约三个八度。"}
```

- **实音 D1–F4**，约三个八度 —— 是管弦乐团里**音最低的常规乐器之一**。
- **常用区 D1–C3**：它的工作几乎全在低音区。
- **高音区（C3 以上）** 可以吹，音色会变紧；独奏文献（如欣德米特的奏鸣曲）会用到它，
  但乐队里用得少。

## 音色与听辨

四条线索：

1. **厚、暗、圆**。它的音色里没有[[instrument:trumpet|小号]]那种"金属的锋利"，
   而是一团有重量的低频。
2. **不易辨认细节，但极易辨认存在**。"有没有大号"在音响上一耳可辨 ——
   它改变的是整个和声的重心。
3. **强奏时能"顶"住整个乐队**。管弦乐的高潮需要它撑住底部；管乐团里它是低音的骨架。
4. **中音区意外地灵活**。它不只是"低音机器"——
   在大号独奏文献里，它在 C2–F3 一带可以相当流动。

```audiolab
{"type":"instrument","gm":"Tuba","synth":"brass","phrase":["D1","D2","A2","D3","F3"],"label":"大号的常用区：D1 到 F3","label_en":"The tuba's working register — D1 up to F3","hint":"注意最低音更像「重量」而不是「音」—— 这是低音铜管的共同特征","hint_en":"At the bottom, weight matters more than pitch — a trait shared by all low brass."}
```

## 演奏技法

- **持握有两大类**：**抱持式**（号身抱在身前，喇叭口朝上）与**扛肩式**（号身放在肩上，用于行进乐队）。
  大型大号重量可观，持握方式直接影响耐力。
- **气量要求极高**。管最长管径最粗，维持低音需要非常大的稳定气流。
- **吐音要"厚"**。低音区的音头如果不控制，会变成模糊的一团 ——
  所以低音大号的吐音技术比小号更讲究"重量感"。
- **弱音器**可用，但在低音区效果有限。

## 家族与近亲

| 乐器 | 管长 | 圆锥度 | 活塞 | 音域（实音） | 常用处 |
|---|---|---|---|---|---|
| [[instrument:euphonium\|上低音号]] | 约 2.7 米 | 大 | 3–4 | A1–B♭4 | 管乐团中低音 |
| **大号** | 约 5.5 米 | 最大 | 4–6 | D1–F4 | 管弦乐 / 管乐团低音 |
| [[instrument:sousaphone\|苏萨号]] | 与大号相同 | 大 | 3–4 | D1–F4 | **行进乐队**（可套在身上） |
| [[instrument:ophicleide\|奥菲克莱德号]] | 相近 | 中 | **0（指孔 + 键）** | C2–C4 | 19 世纪初，大号之前的低音 |

**注意最后一行**：[[instrument:ophicleide|奥菲克莱德号]]是**用指孔而不是活塞**的低音铜管 ——
它是"大号之前承担低音的那一件"，也是理解大号为什么能取代它的关键（见其条目）。

## 历史演变

| 时期 | 状态 |
|---|---|
| 18 世纪末—19 世纪初 | 低音铜管主要靠**蛇形号**（[[instrument:serpent|serpent]]）与**奥菲克莱德号**承担 |
| **1835** | **大号取得专利**（Wieprecht 与 Moritz），活塞式低音铜管的现代形制成立 |
| 19 世纪中后期 | 迅速取代奥菲克莱德号；进入管弦乐与军乐队；出现不同调性与尺寸的多种版本 |
| 19 世纪末—20 世纪 | **苏萨号**为行进乐队而造；**上低音号**在管乐团里承担中低音 |
| 20 世纪 | 独奏文献出现（欣德米特等人）；爵士里也用于低音线条（尤其是早期的低音号用法） |
| 20 世纪后期至今 | 管弦乐、管乐团、爵士、流行全面通用 |

**它取代奥菲克莱德号的理由很直接**：活塞系统让低音区更容易吹准、更容易吹响，
而音量也更大。**技术上的"更容易"，往往就是乐器更替的真正原因。**

## 常见误解

- **"大号只要吹低音。"** 它的独奏文献相当丰富（欣德米特的奏鸣曲是代表作），
  中音区也有实际的流动性。
- **"它与上低音号是同一件乐器。"** 同族、形制相似，但**音区差一个八度**，
  管长与管径都不同。
- **"大号要移调。"** 取决于编制：**管弦乐里按 C 调实音记谱**，
  英式铜管乐队里按降 B 调移调记谱。**同一件乐器可以有两套惯例。**
- **"它需要四个活塞是因为低音难吹。"** 是因为**低音区泛音稀** ——
  三个活塞的管长组合在低音区填不满十二个半音。
- **"大号在乐队里只是加厚。"** 它同时决定**和声的重心位置** ——
  加与不加、或者换成苏萨号，整个音响的稳定性会变。

## 下一步

铜管组的低音线到这里就完整了。想看清它是怎么演化来的，就去看
[[instrument:ophicleide|奥菲克莱德号]]（指孔 + 键系的低音铜管）与
[[instrument:serpent|蛇形号]]（木制的低音铜管）——
这两件会解释"为什么活塞最终赢了"。

铜管的另一端还有一件特殊乐器：[[instrument:wagner-tuba|瓦格纳大号]] ——
它用**圆号的号嘴**配**大号式的管身**，是"号嘴与管身可以分别选配"的实证。
:::

::: en
The tuba is the brass group's foundation: **the longest tube (about 5.5 m), the widest bore, the largest
conical proportion** — hence the lowest pitch and the thickest tone. Its job in orchestra and band is the
same: **give the harmony a dependable floor.**

It also has a problem no other brass has: **the partials in its low register are far apart**, so it needs
several more valves than a [[instrument:trumpet|trumpet]].

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · **lip-vibrated** |
| **Sub-type** | Deep cup mouthpiece · **four to six valves** · **largest conical proportion** · **written in C at pitch in the orchestra** |
| **Family** | Western · Brass (tuba family, bass branch) |
| **Bayin** | Not applicable — a Chinese system; the tuba is outside it |

> ⚠️ **One conceptual point**: **one instrument can carry two notation conventions.** In the
> **orchestra** the tuba is written in **C at sounding pitch** (bass clef); in a **British brass band** it is
> written as a **B♭ transposing** instrument. Same instrument, different reading practice.
> So "how is this instrument read?" depends on **which ensemble it is in** — a theme already met in the
> woodwind batch (the [[instrument:alto-saxophone|saxophone]] family's shared fingerings versus the
> [[instrument:clarinet|clarinet]] family's divergent shifts); in brass it becomes "the ensemble decides the
> convention".

## Structure: the longest tube and the most valves

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tuba parts: deep cup mouthpiece, coiled wide body, four to six valves, and a wide upward-facing bell">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Tuba — outer form and principal parts (longest tube, widest bore, most valves)</text>
  </g>
  <path d="M150,120 C120,150 118,210 146,248 C176,290 254,300 300,272 C346,244 356,180 328,144 C304,112 250,104 216,124" fill="none" stroke="#17171A" stroke-width="34" stroke-linecap="round"/>
  <path d="M216,124 C190,138 168,138 150,120" fill="none" stroke="#17171A" stroke-width="30" stroke-linecap="round"/>
  <path d="M120,118 L92,110 L96,134 Z" fill="#17171A" stroke="#9C7A3C" stroke-width="1.4"/>
  <path d="M300,272 C356,256 402,204 406,152 C408,124 398,102 380,90 L444,74 C466,100 470,150 458,196 C440,266 366,314 300,320 Z" fill="#17171A" stroke="#343439" stroke-width="1.5"/>
  <ellipse cx="412" cy="82" rx="34" ry="10" fill="#0E0E10" stroke="#343439" stroke-width="1.2"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="250" y="316" width="11" height="34" rx="4"/>
    <rect x="268" y="324" width="11" height="30" rx="4"/>
    <rect x="286" y="330" width="11" height="26" rx="4"/>
    <rect x="304" y="332" width="11" height="24" rx="4"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,104 L128,108"/><path d="M186,200 L172,196"/>
    <path d="M186,336 L240,336"/><path d="M486,110 L444,92"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="101" text-anchor="end">Deep cup mouthpiece</text>
    <text x="180" y="203" text-anchor="end" fill="#5B7FA8">About 5.5 m of tube</text>
    <text x="180" y="339" text-anchor="end" fill="#E07A3F">Four valves (five or six exist)</text>
    <text x="492" y="107">Bell facing up</text>
  </g>
  <text x="20" y="376" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">An upward bell is standard on low instruments: low frequencies aimed at the floor are absorbed.</text>
</svg>
```

Three points:

1. **The longest tube (about 5.5 m)**, coiled into a large circle — the direct cause of its low pitch.
2. **The widest bore and largest conical proportion**, giving a **thick, dark, round** tone rather than the
   [[instrument:trombone|trombone]]'s bright squareness.
3. **The most valves (usually four, sometimes five or six)**. Why so many? Next section.

## Few partials down low, hence more valves

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Partial spacing compared between a trumpet and a tuba: the tuba works in low partials where the gaps are large, needing more valves">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One series, but the higher you work the closer the partials</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Trumpet · works in higher partials</text>
  <g stroke="#5B7FA8" stroke-width="7" stroke-linecap="round">
    <path d="M70,142 L70,116"/><path d="M104,142 L104,124"/>
    <path d="M138,142 L138,130"/><path d="M172,142 L172,134"/>
    <path d="M206,142 L206,137"/><path d="M240,142 L240,139"/>
  </g>
  <path d="M54,142 L258,142" stroke="#343439" stroke-width="1.3"/>
  <text x="160" y="166" text-anchor="middle" font-size="10.5" fill="#A9A49B">close partials → small gaps to fill</text>
  <text x="160" y="188" text-anchor="middle" font-size="10.5" fill="#5B7FA8">three valves are enough</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">Tuba · works in very low partials</text>
  <g stroke="#E07A3F" stroke-width="7" stroke-linecap="round">
    <path d="M370,142 L370,108"/><path d="M470,142 L470,126"/>
    <path d="M540,142 L540,136"/><path d="M576,142 L576,139"/>
  </g>
  <path d="M354,142 L592,142" stroke="#343439" stroke-width="1.3"/>
  <text x="480" y="166" text-anchor="middle" font-size="10.5" fill="#A9A49B">wide gaps → much to fill</text>
  <text x="480" y="188" text-anchor="middle" font-size="10.5" fill="#E07A3F">four or more valves needed</text>
  <text x="20" y="224" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A tuba's first and second partials are an octave apart — filling that gap step by step needs far more than three.</text>
  <text x="20" y="246" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The fourth valve usually adds a perfect fourth, unlocking several low notes; five and six extend further.</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">This mirrors the horn's tuning difficulty — both follow from how partial spacing changes with register.</text>
</svg>
```

**This rule generalises across the brass**:

| Instrument | Usual partials | Spacing | Valves |
|---|---|---|---|
| [[instrument:trumpet\|Trumpet]] | 2nd–8th | closer | 3 |
| [[instrument:trombone\|Trombone]] | 2nd–6th | medium | 0 (continuous slide) |
| [[instrument:french-horn\|Horn]] | 3rd–12th | close (but long tube) | 3 (+ thumb valve) |
| **Tuba** | **1st–5th** | **very wide** | **4–6** |

**The tuba is the horn's opposite**: its tube is the longest, but it works in the **lowest partials**, so
spacing is wide and intonation is actually more forgiving (the ear is tolerant down there too). The price is
needing **more valves** to fill the gaps.

## Range

```range
{"range":"D1–F4","common":"D1–C3","caption":"大号的音域","caption_en":"Tuba range","note":"大号在管弦乐里按 C 调实音记谱（低音谱号）；英式铜管乐队里则按降 B 调移调记谱 —— 同一件乐器两套惯例。标准音域 D1–F4，约三个八度。"}
```

- **Sounding D1–F4**, about three octaves — among the **lowest standard instruments** in an orchestra.
- **The working register is D1–C3**; almost all its work is low.
- **Above C3** it still speaks, but more tightly; solo repertoire (such as Hindemith's sonata) uses it, though
  bands rarely do.

## Timbre, and how to hear it

Four cues:

1. **Thick, dark, round.** No metallic edge as on a [[instrument:trumpet|trumpet]] — a mass of low
   frequency with weight.
2. **Hard to hear in detail, impossible to miss in presence.** Whether a tuba is playing is obvious at once;
   what changes is the centre of gravity of the harmony.
3. **At full power it holds a whole orchestra.** Orchestral climaxes need it at the bottom; in a band it is
   the skeleton of the bass.
4. **Its middle register is surprisingly agile**, not merely a bass machine — the solo repertoire moves
   fluently around C2–F3.

```audiolab
{"type":"instrument","gm":"Tuba","synth":"brass","phrase":["D1","D2","A2","D3","F3"],"label":"大号的常用区：D1 到 F3","label_en":"The tuba's working register — D1 up to F3","hint":"注意最低音更像「重量」而不是「音」—— 这是低音铜管的共同特征","hint_en":"At the bottom, weight matters more than pitch — a trait shared by all low brass."}
```

## Playing techniques

- **Two ways of holding it**: **upright** (body in front, bell up) and **shoulder-carried** (for marching
  bands). A large tuba is heavy, and the hold directly affects endurance.
- **A very large air requirement** — the longest, widest tube needs a big, steady supply for the low register.
- **A "heavy" attack.** Uncontrolled low notes turn into a blur, so low-tuba articulation is more about
  weight than speed.
- **Mutes** work, but with limited effect down low.

## The family

| Instrument | Tube | Conical? | Valves | Range (sounding) | Usual role |
|---|---|---|---|---|---|
| [[instrument:euphonium\|Euphonium]] | about 2.7 m | large | 3–4 | A1–B♭4 | band tenor-bass |
| **Tuba** | about 5.5 m | largest | 4–6 | D1–F4 | orchestra / band bass |
| [[instrument:sousaphone\|Sousaphone]] | as a tuba | large | 3–4 | D1–F4 | **marching band** (wraps around the body) |
| [[instrument:ophicleide\|Ophicleide]] | similar | medium | **0 (holes + keys)** | C2–C4 | early 19th c., the tuba's predecessor |

**Note the last row**: the [[instrument:ophicleide|ophicleide]] is a low brass **with holes instead of
valves** — the instrument that held the bass before the tuba (see its entry).

## History

| Period | State |
|---|---|
| Late 18th–early 19th c. | low brass is carried by the [[instrument:serpent|serpent]] and then the ophicleide |
| **1835** | **the tuba is patented** (Wieprecht and Moritz); the modern valved low brass is established |
| Mid–late 19th c. | quickly replaces the ophicleide; enters orchestra and military band; versions in several keys and sizes appear |
| Late 19th–20th c. | the **sousaphone** is built for marching; the **euphonium** takes the band's tenor-bass |
| 20th c. | a solo repertoire appears (Hindemith among others); jazz also uses it on bass lines |
| Late 20th c. onward | used across orchestra, band, jazz and pop |

**Why it replaced the ophicleide is straightforward**: a valve system makes the low register easier to play
in tune and easier to sound, and louder. **"Easier" is very often the real reason one instrument replaces
another.**

## Common misconceptions

- **"A tuba only plays low."** Its solo repertoire is substantial (Hindemith's sonata is the reference), and
  its middle register is genuinely mobile.
- **"It is the same instrument as a euphonium."** Same family and similar shape, but **an octave apart**, with
  different tube length and bore.
- **"A tuba transposes."** Depends on the ensemble: **in the orchestra it is written in C at pitch**; in a
  British brass band it transposes. **One instrument, two conventions.**
- **"It needs four valves because low notes are hard."** It needs them because **low partials are far
  apart** — three valves' worth of lengths cannot fill every semitone down there.
- **"In a band the tuba is just thickness."** It also **places the centre of gravity of the harmony** —
  whether it plays, or is replaced by a sousaphone, changes the stability of the whole sound.

## Next

The brass bass line is now complete. To see how it evolved, read the
[[instrument:ophicleide|ophicleide]] (a low brass with holes and keys) and the
[[instrument:serpent|serpent]] (a wooden low brass) — together they explain **why valves won**.

At the other end of the brass sits a special instrument, the [[instrument:wagner-tuba|Wagner tuba]]:
a **horn mouthpiece on a tuba-like body** — proof that mouthpiece and body can be chosen separately.
:::
