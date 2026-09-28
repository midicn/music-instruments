---
id: tubular-bells
site: inst
cat: I4
title: 管钟
title_en: Tubular Bells
summary: 一排悬挂的金属管，一管一音，用来模拟教堂钟声
summary_en: A row of hung metal tubes, one note each — the orchestral imitation of church bells
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [管钟, tubular bells, 排钟, 管状钟, chimes]
order: 66
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:glockenspiel]]"
  - "[[instrument:gong]]"
  - "[[instrument:celesta]]"
  - "[[instrument:vibraphone]]"
instances:
  - pdmx-001882 | Carol of the Bells —— 标题指向"钟声"的曲目，可作音色联想与时代语汇的参照
  - pdmx-000746 | 霍尔斯特《行星组曲》Op.32 —— 配器里管钟的用法（土星乐章）可在此听到
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里的金属打击乐用法
sources:
  - 结构依通行制琴资料：一排**金属管**（多为黄铜或青铜）按音高悬挂，管上有一处**敲击点**标记；另有踩板控制余音
  - 「管钟属**体鸣**的有音高乐器 —— 金属管本身整体振动」依 Hornbostel–Sachs 分类
  - 「常见音域 C4–F6（一组半），另有音域更宽的形制」依通行乐器资料
  - 「每根管有一个由制造者标定的敲击位置 —— 在那里击奏才得到正确音高」依乐器制作通识
  - 「**管越长 → 音越低**，与气鸣管乐器的方向一致」依金属壳体／管体振动原理
updated: 2026-09-26
---

::: zh
管钟是打击乐里"最容易被认出、也最容易被写坏"的一件：
**一排悬挂的金属管，一管一音**。它的声音与教堂钟声几乎一样，
所以它在管弦乐里承担一个非常具体的任务 —— **让音乐"有钟声"**。

值得注意的细节是：**每根管上都有一个标定的敲击点**，
击在那里才得到正确的音高（与[[instrument:timpani|定音鼓]]的击奏位置不同，
那不是"音色选择"而是一种**结构要求**）。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **体鸣**（Idiophone）· **有音高** |
| **次级类型** | 金属管按音高悬挂 · 一管一音 · 管上有标定敲击点 · 踩板控制余音 |
| **所属族** | 西洋 · 打击（体鸣·琴条族的"管"支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，管钟不在其中 |

> ⚠️ **一个概念上的要点**：**"一管一音"与"一排管"是两件事。**
> [[instrument:pan-flute|排箫]]也是"多管一音"，但它是**气鸣乐器** —— 靠气流切边发声；
> 管钟是**体鸣乐器** —— 靠金属管本身振动发声。
> 两者外形逻辑相似（按音高排列的管），**但振动体完全不同**。
> **形状相似 ≠ 同类。** 判据永远是"什么在振动"。

## 结构：悬挂的管与标定的敲击点

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管钟的结构：一排按音高悬挂的金属管、每管上的敲击点标记、顶端悬挂架与踩板">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">管钟 · 结构（一管一音，管上有标定敲击点）</text>
  </g>
  <path d="M100,58 L500,58" stroke="#343439" stroke-width="6"/>
  <g stroke="#6E6A64" stroke-width="2">
    <path d="M130,58 L130,74"/><path d="M180,58 L180,74"/><path d="M230,58 L230,74"/>
    <path d="M280,58 L280,74"/><path d="M330,58 L330,74"/><path d="M380,58 L380,74"/>
    <path d="M430,58 L430,74"/><path d="M480,58 L480,74"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.6" fill="#17171A">
    <rect x="120" y="74" width="20" height="200" rx="8"/>
    <rect x="170" y="74" width="20" height="184" rx="8"/>
    <rect x="220" y="74" width="20" height="168" rx="8"/>
    <rect x="270" y="74" width="20" height="154" rx="8"/>
    <rect x="320" y="74" width="20" height="142" rx="8"/>
    <rect x="370" y="74" width="20" height="130" rx="8"/>
    <rect x="420" y="74" width="20" height="120" rx="8"/>
    <rect x="470" y="74" width="20" height="112" rx="8"/>
  </g>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M118,104 L142,104"/><path d="M168,104 L192,104"/>
    <path d="M218,104 L242,104"/><path d="M268,104 L292,104"/>
    <path d="M318,104 L342,104"/><path d="M368,104 L392,104"/>
    <path d="M418,104 L442,104"/><path d="M468,104 L492,104"/>
  </g>
  <path d="M540,120 L578,142" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <ellipse cx="584" cy="146" rx="12" ry="9" fill="#9C7A3C"/>
  <path d="M520,276 L560,276" stroke="#6E6A64" stroke-width="4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L186,52"/><path d="M186,104 L186,104"/>
    <path d="M186,240 L186,214"/><path d="M486,100 L500,110"/>
    <path d="M486,276 L566,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="41" text-anchor="end">悬挂架</text>
    <text x="180" y="241" text-anchor="end" fill="#5B7FA8">管越长音越低</text>
    <text x="492" y="97" fill="#E07A3F">标定敲击点</text>
    <text x="492" y="279">踩板控制余音</text>
  </g>
  <text x="20" y="308" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">注意：这里是「金属管越短音越高」 —— 与气鸣管乐器（越短音越高）方向一致，但机理不同：一个是空气柱，一个是金属本体。</text>
</svg>
```

三处要点：

1. **敲击点是标定的**。管钟的每根管在制造时就确定了"击哪里音最准"，
   演奏者必须击在那里 —— 否则音高会偏低、泛音也会变。
2. **踩板控制余音**。管钟的余音极长，踩板让演奏者可以在需要时立刻收干声音。
3. **音高与管长的关系**：管越长音越低 —— 与气鸣管乐器方向一致，
   但**振动体不同**（金属本体 vs 空气柱），这是它与[[instrument:pan-flute|排箫]]的根本区别。

## 音域

```range
{"range":"C4–F6","common":"C4–C6","caption":"管钟的音域（以一组半的形制为例）","caption_en":"Tubular bells range (a one-and-a-half-octave set)","note":"管钟属体鸣的有音高乐器。常见音域 C4–F6（一组半），另有音域更宽的形制。记谱即实音。"}
```

- **C4–F6**（以一组半的形制为例）—— **窄，但足够**，
  因为它模拟的是钟声，而钟声本身不需要宽音域。
- **常用区 C4–C6**：管弦乐里的管钟声部几乎都在这里。
- **它的功能是"音色"而不是"音域"** —— 一次钟声的出现比它奏了多少音更重要。

## 音色与听辨

四条线索：

1. **钟声**。它的音色与真实教堂钟非常接近 —— 这是它存在的唯一理由。
2. **余音极长**。一次击奏能响很久，所以快速连续击奏会叠成一片。
3. **低频有分量**。管径大、管长长，所以钟声的"重量"是真实的。
4. **泛音复杂**。钟声的泛音不是谐波列，所以听起来"有厚度、不干净"——
   这正是钟之所以为钟的原因。

```audiolab
{"type":"instrument","gm":"Tubular Bells","synth":"metal","phrase":["C4","E4","G4","C5"],"label":"管钟的钟声：C4 到 C5","label_en":"Tubular bells — C4 up to C5","hint":"注意余音极长与泛音的复杂性 —— 听起来是一个「钟」而不是一个「音」","hint_en":"Hear the very long tail and complex partials — it sounds like a bell, not a note."}
```

## 演奏技法

- **击标定敲击点**（见上图）—— 这是正确音高的前提。
- **软头或中硬头槌**。硬槌会引出更多金属噪声。
- **踩板控制余音**：需要收干时踩下。
- **多次击奏的取舍**：余音长，所以连续击奏必须考虑"叠不叠得上"。

## 家族与近亲

| 乐器 | 振动体 | 音高 | 余音 | 用途 |
|---|---|---|---|---|
| [[instrument:glockenspiel\|钟琴]] | 钢条 | 有 | 中 | 加亮、勾轮廓 |
| **管钟** | **金属管** | **有** | **极长** | **模拟钟声** |
| [[instrument:celesta\|钢片琴]] | 钢片 | 有 | 中 | 玻璃般的音色 |
| [[instrument:gong\|锣]] | 合金盘 | **无** | 极长 | 气氛与高潮 |
| [[instrument:pan-flute\|排箫]] | **空气柱** | 有 | 短 | 旋律（**气鸣，不同类**） |

**管钟与[[instrument:glockenspiel|钟琴]]都在"金属 + 有音高"这一格**，
但一个模拟钟声（长余音）、一个加亮音色（中余音）——
**同一格里还能继续分档，分档依据是"余音长度"**。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代—中世纪 | 真实的教堂钟（大型青铜钟）是欧洲城市生活的一部分 |
| 19 世纪 | 管钟出现 —— 用一排金属管模拟钟声，比真钟便携得多 |
| 19 世纪末—20 世纪 | 成为管弦乐的标准打击乐器；柴可夫斯基、霍尔斯特等人的用法使之广为人知 |
| 20 世纪 | 用法扩展到影视配乐（教堂、仪式、回忆场景几乎是标配） |
| 20 世纪后期至今 | 管弦乐、管乐团、影视配乐的通用乐器 |

**它是一项"替代技术"的胜利**：真钟无法搬进音乐厅，
而管钟用一排金属管给出了几乎相同的声音 ——
这与[[instrument:tubular-bells|大号取代奥菲克莱德号]]是同一种逻辑：
**更方便的方案往往会赢。**

## 常见误解

- **"管钟与钟琴是同一件乐器。"** 一个是**悬挂的管**（模拟钟声、余音极长），
  一个是**平放的钢条**（加亮音色、余音中等）——
  形制、音色、用途都不同。
- **"随便击哪里都一样。"** **每根管都有标定的敲击点** ——
  击偏了音高会偏低、泛音也会变化。
- **"它和排箫是一类。"** 都是"多管一音"，但排箫是**气鸣**（空气柱振动），
  管钟是**体鸣**（金属振动）—— **不同类**。
- **"它音域窄所以少见。"** 它出现得不多，但每次出现都是为了**整个段落的色彩**，
  不是为了弹旋律。
- **"它只是模仿教堂钟。"** 影视与当代作品也用它表现"时间、记忆、仪式"等抽象意涵 ——
  它的音色本身已成了一种符号。

## 下一步

金属一类里还剩两件：[[instrument:celesta|钢片琴]]（键盘击奏的钢片，玻璃般）
与 [[instrument:gong|锣]]（无音高、余音极长的合金盘）。
锣会把打击批带出"有音高"的范围，进入"只用音色本身说话"的那一片。
:::

::: en
The tubular bells are the most instantly recognisable — and most easily mis-written — instrument in
percussion: **a row of hung metal tubes, one note each**. The sound is nearly identical to church bells, so
its orchestral job is very specific: **make the music have bells.**

One detail matters: **each tube has a marked striking point**, and hitting it there is what gives the correct
pitch. Unlike a [[instrument:timpani|timpani]], that spot is not a colour choice but a **structural
requirement**.

| Classification | Value |
|---|---|
| **HS class** | **Idiophone** · **pitched** |
| **Sub-type** | Metal tubes hung in pitch order · one note per tube · a marked striking point · pedal damps the tail |
| **Family** | Western · Percussion (idiophone; "tube" branch of the bar family) |
| **Bayin** | Not applicable — a Chinese system; tubular bells are outside it |

> ⚠️ **One conceptual point**: **"one note per tube" and "a row of tubes" are two separate matters.**
> The [[instrument:pan-flute|pan flute]] is also "many tubes, one note each", but it is an **aerophone** —
> driven by a cut jet; tubular bells are an **idiophone** — the metal tube itself vibrates.
> The layout logic is similar (tubes in pitch order) but **the vibrating body is entirely different**.
> **Similar shape is not the same class.** The test is always what vibrates.

## Structure: hung tubes and a marked striking point

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tubular bells structure: a row of metal tubes hung in pitch order, each with a marked striking point, plus the frame and damper pedal">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Tubular bells — structure (one note per tube, marked striking point)</text>
  </g>
  <path d="M100,58 L500,58" stroke="#343439" stroke-width="6"/>
  <g stroke="#6E6A64" stroke-width="2">
    <path d="M130,58 L130,74"/><path d="M180,58 L180,74"/><path d="M230,58 L230,74"/>
    <path d="M280,58 L280,74"/><path d="M330,58 L330,74"/><path d="M380,58 L380,74"/>
    <path d="M430,58 L430,74"/><path d="M480,58 L480,74"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.6" fill="#17171A">
    <rect x="120" y="74" width="20" height="200" rx="8"/>
    <rect x="170" y="74" width="20" height="184" rx="8"/>
    <rect x="220" y="74" width="20" height="168" rx="8"/>
    <rect x="270" y="74" width="20" height="154" rx="8"/>
    <rect x="320" y="74" width="20" height="142" rx="8"/>
    <rect x="370" y="74" width="20" height="130" rx="8"/>
    <rect x="420" y="74" width="20" height="120" rx="8"/>
    <rect x="470" y="74" width="20" height="112" rx="8"/>
  </g>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M118,104 L142,104"/><path d="M168,104 L192,104"/>
    <path d="M218,104 L242,104"/><path d="M268,104 L292,104"/>
    <path d="M318,104 L342,104"/><path d="M368,104 L392,104"/>
    <path d="M418,104 L442,104"/><path d="M468,104 L492,104"/>
  </g>
  <path d="M540,120 L578,142" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <ellipse cx="584" cy="146" rx="12" ry="9" fill="#9C7A3C"/>
  <path d="M520,276 L560,276" stroke="#6E6A64" stroke-width="4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,44 L186,52"/><path d="M186,104 L186,104"/>
    <path d="M186,240 L186,214"/><path d="M486,100 L500,110"/>
    <path d="M486,276 L566,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="41" text-anchor="end">Suspension frame</text>
    <text x="180" y="241" text-anchor="end" fill="#5B7FA8">Longer tube, lower note</text>
    <text x="492" y="97" fill="#E07A3F">Striking point</text>
    <text x="492" y="279">Damper pedal</text>
  </g>
  <text x="20" y="308" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A shorter tube is higher — same direction as an air column, but metal, not air.</text>
</svg>
```

Three points:

1. **The striking point is marked.** Each tube's best-sounding spot is set at manufacture, and the player must
   hit it — off it, the pitch drops and the partials change.
2. **A pedal damps the tail**, letting the player cut the sound off when needed.
3. **Pitch versus length**: a longer tube is lower, as with air columns — but the **vibrating body differs**
   (metal versus air), which is the fundamental difference from the [[instrument:pan-flute|pan flute]].

## Range

```range
{"range":"C4–F6","common":"C4–C6","caption":"管钟的音域（以一组半的形制为例）","caption_en":"Tubular bells range (a one-and-a-half-octave set)","note":"管钟属体鸣的有音高乐器。常见音域 C4–F6（一组半），另有音域更宽的形制。记谱即实音。"}
```

- **C4–F6** for a one-and-a-half-octave set — **narrow, but sufficient**, since it imitates bells, which do
  not need a wide range.
- **The working register is C4–C6**; nearly all orchestral writing sits there.
- **Its function is colour, not range** — that a bell appears at all matters more than how many notes it
  plays.

## Timbre, and how to hear it

Four cues:

1. **Bells.** The colour is very close to real church bells — the sole reason it exists.
2. **An extremely long tail**, so fast repeated strokes pile up.
3. **Real weight low down**, from wide, long tubes.
4. **Complex partials.** A bell's overtones are not a harmonic series, so it sounds thick and impure — which
   is exactly why a bell is a bell.

```audiolab
{"type":"instrument","gm":"Tubular Bells","synth":"metal","phrase":["C4","E4","G4","C5"],"label":"管钟的钟声：C4 到 C5","label_en":"Tubular bells — C4 up to C5","hint":"注意余音极长与泛音的复杂性 —— 听起来是一个「钟」而不是一个「音」","hint_en":"Hear the very long tail and complex partials — it sounds like a bell, not a note."}
```

## Playing techniques

- **Strike the marked spot** (see the diagram) — the precondition for correct pitch.
- **Soft or medium mallets**; hard ones bring out more metallic noise.
- **The damper pedal** cuts the tail when required.
- **Judging repeated strokes**: with such a long tail, the player must decide what may overlap.

## The family

| Instrument | Vibrating body | Pitch | Tail | Use |
|---|---|---|---|---|
| [[instrument:glockenspiel\|Glockenspiel]] | steel bars | yes | medium | brighten, outline |
| **Tubular bells** | **metal tubes** | **yes** | **very long** | **imitate bells** |
| [[instrument:celesta\|Celesta]] | steel plates | yes | medium | glassy colour |
| [[instrument:gong\|Gong]] | alloy disc | **no** | very long | atmosphere, climax |
| [[instrument:pan-flute\|Pan flute]] | **air column** | yes | short | melody (**aerophone, a different class**) |

**Tubular bells and the [[instrument:glockenspiel|glockenspiel]] share the "metal + pitched" cell**, yet one
imitates bells (long tail) and the other brightens colour (medium tail) — **one cell can be divided further,
and the divider is tail length.**

## History

| Period | State |
|---|---|
| Antiquity–Middle Ages | real church bells are part of European town life |
| 19th c. | tubular bells appear — a row of metal tubes imitating bells, far more portable than the real thing |
| Late 19th–20th c. | become standard orchestral percussion; Tchaikovsky and Holst make them widely known |
| 20th c. | their use extends to film scoring, where churches, ceremonies and memory are near-standard cues |
| Late 20th c. onward | universal in orchestra, band and film music |

**It is a victory of substitution technology**: real bells cannot be moved into a concert hall, and a row of
metal tubes gives almost the same sound — the same logic as the tuba replacing the ophicleide:
**the more convenient solution tends to win.**

## Common misconceptions

- **"Tubular bells and a glockenspiel are the same instrument."** One is **hung tubes** (bell imitation, very
  long tail), the other **flat steel bars** (brightening, medium tail) — different form, colour and use.
- **"Anywhere on the tube will do."** **Each tube has a marked striking point**; off it the pitch drops and
  the partials change.
- **"It is the same class as a pan flute."** Both are "many tubes, one note", but the pan flute is an
  **aerophone** (air column) and this an **idiophone** (metal) — **different classes**.
- **"A narrow range makes it rare."** It appears seldom, but each time for the **colour of a whole passage**,
  not to play melody.
- **"It only imitates church bells."** Film and contemporary music also use it for time, memory and ritual —
  its colour has become a symbol in itself.

## Next

Two metal instruments remain: the [[instrument:celesta|celesta]] (keyboard-struck steel plates, glassy) and
the [[instrument:gong|gong]] (unpitched alloy disc, extremely long tail). The gong takes percussion out of
"pitched" territory into the region where **timbre alone speaks**.
:::
