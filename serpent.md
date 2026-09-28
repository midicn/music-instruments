---
id: serpent
site: inst
cat: I3
title: 蛇形号
title_en: Serpent
summary: 木制蒙皮、蛇形弯曲的低音铜管，靠指孔而不是活塞取音
summary_en: A wooden, leather-covered low brass in a snake shape — stopped by finger holes, not valves
level: standard
tags: [乐器, 铜管, 西洋, 早期乐器]
tags_en: [instrument, brass, western, early]
alias: [蛇形号, serpent, 蛇形管, 蛇号]
order: 52
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:tuba]]"
  - "[[instrument:ophicleide]]"
  - "[[instrument:natural-trumpet]]"
  - "[[instrument:recorder]]"
instances:
  - giantmidi-002227 | Serpent-Soleil —— 库内标题可确认为蛇形号的曲目
  - openscore-000879 | Les tronçons du serpent —— 另一条以 snake 为题的曲目，可作时代语汇的参照
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 低音铜管成熟后的编制，与蛇形号的时代形成对照
sources:
  - 结构依通行制琴资料：木制管身外裹皮革、以蛇形（S 形）弯曲，顶端为杯形号嘴，管身开六个指孔（取音靠指孔）
  - 「音域约 C3–C5」依通行乐器资料
  - 「16 世纪末起源于法国，用于教堂音乐的低音声部」依乐器史
  - 「蛇形号是唇鸣驱动 + 指孔取音的混合体 —— 驱动方式属铜管，取音方式属木管」依 Hornbostel–Sachs 分类
  - ⚠️ 库内标题可确认为蛇形号的曲目极少 —— 本条另给两条作时代与编制对照，音色由试听件负责
updated: 2026-09-26
---

::: zh
蛇形号是铜管史上一个"杂交"的答案：**它用嘴唇发声（铜管的驱动方式），却用指孔取音（木管的取音方式）。**
外形像一条竖起来的蛇，木制管身外裹皮革 —— 名字与做法都来自它的形状。

它的历史地位很明确：**在活塞出现之前，低音铜管一直缺一个可靠的解法。**
蛇形号是其中一种尝试，[[instrument:ophicleide|奥菲克莱德号]]是它的改进版，大号是终点。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· **唇鸣**（lip-vibrated）· 指孔取音 |
| **次级类型** | 杯形号嘴 · **无阀门**（六个指孔） · 木制管身外裹皮革 · 蛇形弯曲 |
| **所属族** | 西洋 · 铜管（早期支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，蛇形号不在其中 |

> ⚠️ **一个概念上的要点**：**"铜管"是一类驱动方式，不是一个材料类别。**
> 蛇形号是**木头的、蒙皮的**，但它靠嘴唇振动发声 → 属**铜管**；
> 而[[instrument:recorder|竖笛]]是木头的、靠气流切边 → 属**木管**。
> 反过来，金属的长笛属木管。**材料、外形、名称都不判类 —— 只有"什么在振动"判类。**

## 结构：蛇形、木胎、蒙皮、指孔

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="蛇形号的外形与主要部件：杯形号嘴、蛇形弯曲的木制管身、外裹皮革与排列在管身的指孔">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">蛇形号 · 外形与主要部件（木胎蒙皮 + 六个指孔）</text>
  </g>
  <rect x="96" y="196" width="30" height="15" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.3"/>
  <path d="M126,198 C210,190 250,214 300,226 C350,238 380,268 380,310 C380,346 350,364 314,364 C280,364 256,344 254,318 C252,294 268,278 288,278"
        fill="none" stroke="#17171A" stroke-width="26" stroke-linecap="round"/>
  <path d="M126,198 C210,190 250,214 300,226 C350,238 380,268 380,310 C380,346 350,364 314,364 C280,364 256,344 254,318 C252,294 268,278 288,278"
        fill="none" stroke="#9C7A3C" stroke-width="26" stroke-linecap="round" opacity=".24"/>
  <g fill="#070706" stroke="#E07A3F" stroke-width="1.4">
    <circle cx="196" cy="204" r="7"/><circle cx="238" cy="214" r="7"/>
    <circle cx="284" cy="226" r="7"/><circle cx="330" cy="248" r="7"/>
    <circle cx="364" cy="288" r="7"/><circle cx="376" cy="336" r="7"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,150 L140,192"/><path d="M186,300 L246,318"/>
    <path d="M186,222 L190,204"/><path d="M486,240 L352,240"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="147" text-anchor="end">杯形号嘴（嘴唇振动）</text>
    <text x="180" y="303" text-anchor="end" fill="#9C7A3C">木胎外裹皮革</text>
    <text x="180" y="225" text-anchor="end" fill="#E07A3F">六个指孔</text>
    <text x="492" y="237">蛇形弯曲（S 形）</text>
  </g>
  <text x="20" y="384" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">指孔的位置由演奏者的手指远近决定 —— 所以它的音准很不稳定，低音区尤其难以吹准。</text>
</svg>
```

三处要点：

1. **驱动是铜管式的**（嘴唇振动 + 杯形号嘴），**取音是木管式的**（六个指孔）。
   这个组合让它既不像木管那样容易吹准，也不像后来的活塞铜管那样稳定。
2. **木胎 + 蒙皮**。木管身外面裹一层皮革以防开裂 —— 这是它音色"朦胧、粗糙"的一部分原因。
   皮革也给它的音色加了一层柔和的阻尼。
3. **音准是它最大的问题**。指孔的位置固定，但演奏者的手型与气息变化会显著影响音高 ——
   这正是它后来被键系与活塞取代的原因。

## 它为"低音铜管"提供过什么

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="低音铜管的技术谱系：从蛇形号到奥菲克莱德号再到大号，取音方式的演进">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">低音铜管的取音技术：一路走向"更稳定"</text>
  </g>
  <path d="M60,150 L580,150" stroke="#343439" stroke-width="2"/>
  <circle cx="120" cy="150" r="10" fill="#9C7A3C"/>
  <circle cx="300" cy="150" r="11" fill="#E07A3F"/>
  <circle cx="500" cy="150" r="12" fill="#5B7FA8"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="120" y="180">16 世纪末</text><text x="300" y="180">19 世纪初</text>
    <text x="500" y="180">1835 年至今</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="120" y="118" text-anchor="middle" fill="#9C7A3C">蛇形号</text>
    <text x="120" y="204" text-anchor="middle" fill="#6E6A64">指孔</text>
    <text x="300" y="114" text-anchor="middle" fill="#E07A3F">奥菲克莱德号</text>
    <text x="300" y="204" text-anchor="middle" fill="#6E6A64">指孔 + 键系</text>
    <text x="500" y="110" text-anchor="middle" fill="#5B7FA8">大号</text>
    <text x="500" y="204" text-anchor="middle" fill="#6E6A64">活塞</text>
  </g>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">每一步都在解决同一个问题：把音吹准、吹响、吹快。而"更容易演奏"往往就是乐器更替的真正原因。</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">蛇形号在教堂音乐里服务了近三百年，然后在几十年内被奥菲克莱德号取代。</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">技术的"更好"是残酷的 —— 它不保留情感上的习惯。</text>
</svg>
```

**它在音乐史里留下了两个痕迹**：

- **教堂低音的传统**。它在法国教堂音乐里长期承担低音声部 ——
  在没有大号的时代，这是"给合唱的低音加厚度"的常用做法。
- **一种独特的音色记忆**。柏辽兹等作曲家记得它的音色，
  并把它写进了新的作品（见[[instrument:ophicleide|奥菲克莱德号]]一条）。

## 音域

```range
{"range":"C3–C5","common":"C3–G4","caption":"蛇形号的音域","caption_en":"Serpent range","note":"蛇形号是木制、蒙皮、蛇形弯曲的低音管乐器，靠唇鸣驱动、指孔取音。音域约 C3–C5。记谱即实音。"}
```

- **约 C3–C5**，两个八度 —— 正好落在当时合唱低音声部的音区。
- **常用区 C3–G4**：这一段是它最"朦胧厚实"的地方。
- **它的音准问题在低音区最严重** —— 指孔与泛音列的组合在低音区容错很小。

## 音色与听辨

四条线索：

1. **朦胧、粗糙、带"咆哮"**。皮革与木胎给它的音色加了一层柔和的模糊 ——
   这是它常被形容为"低沉而笨拙"的原因。
2. **音量不大但向前**。它的投射力不如现代低音铜管，但在小编制与教堂空间里够用。
3. **低音区困难**。低音区音准难、发音难 —— 这也是它被取代的直接原因之一。
4. **高音区意外地"开"**。上到 C5 附近时音色反而清晰一些，历史上也有演奏者用它吹较高声部。

```audiolab
{"type":"instrument","gm":"Tuba","synth":"brass","phrase":["C3","G3","C4","E4","G4"],"label":"蛇形号的常用区：C3 到 G4","label_en":"The serpent's working register — C3 up to G4","hint":"注意音色的朦胧与粗糙 —— 通用音色表里没有蛇形号，这里借大号音色近似","hint_en":"Hear the veiled, coarse tone. General MIDI has no serpent, so a tuba sample stands in."}
```

> ⚠️ **关于试听**：通用音色表（General MIDI）里**没有蛇形号**。
> 上面播放的是**大号**音色 —— 音区对了，但**皮革与木胎带来的模糊完全听不到。**

## 演奏技法

- **指孔按孔位置固定，全靠气息与唇部微调音准** —— 这是它最难的地方。
- **持握姿势特殊**。蛇形弯曲的管身要双手分别扶住，指孔的排列与现代木管完全不同。
- **唇部控制要求高**。它没有键系可以"补偿"，所以音准责任全在演奏者身上。

## 家族与近亲

| 乐器 | 驱动 | 取音 | 材料 | 时代 |
|---|---|---|---|---|
| **蛇形号** | 唇鸣 | **指孔** | 木 + 皮革 | 16 世纪末—19 世纪 |
| [[instrument:ophicleide\|奥菲克莱德号]] | 唇鸣 | **指孔 + 键** | 铜 | 19 世纪 |
| [[instrument:tuba\|大号]] | 唇鸣 | **活塞** | 铜 | 1835 年起 |
| [[instrument:natural-trumpet\|自然小号]] | 唇鸣 | 仅泛音列 | 铜 | 巴洛克 |
| [[instrument:recorder\|竖笛]] | **气流切边** | 指孔 | 木 | 中世纪起 |

**对照最后一行**：蛇形号与[[instrument:recorder|竖笛]]都靠指孔取音，
但**驱动方式完全不同** —— 一个嘴唇、一个气流。**"指孔"是取音方式，不是分类依据。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 16 世纪末（法国） | 出现；用于教堂音乐的低音声部，替代或加强低音人声 |
| 17—18 世纪 | 在法国与英国教堂、乐队里广泛使用；也有用于管弦乐的例子 |
| 18 世纪末 | 改良版本出现（加固、加键、加长），但根本问题（音准）未解 |
| 19 世纪初 | 被**奥菲克莱德号**逐步取代 |
| 19 世纪后期 | 退出常规编制；只在少数复古演奏中保留 |
| 20 世纪 | 古乐运动把它带回少量演出；也有当代作曲家为它写新作 |

## 常见误解

- **"蛇形号是木管。"** 它是**木制的铜管** —— 判据是"什么在振动"（嘴唇），不是材料。
- **"它是大号的前身，所以差不多。"** 取音方式完全不同（指孔 vs 活塞）——
  它的音准、音量、灵活性都远不如大号。
- **"它只是猎奇乐器。"** 它在法国教堂音乐里服务了近三百年，
  是一段很实在的音乐实践。
- **"它有指孔所以容易吹准。"** 恰恰相反：指孔位置固定，音准则要靠气息与唇部硬找 ——
  这是它最大的弱点。
- **"它已经消失。"** 古乐运动保留了它，当代也有作曲家为它写新作。

## 下一步

它的直接继任者是 [[instrument:ophicleide|奥菲克莱德号]]（铜制、加键）——
那一条会讲清"为什么键系也没能救低音铜管"。

想直接看结论，就去 [[instrument:tuba|大号]]：**活塞最终胜出的原因很朴素 —— 更容易演奏。**
:::

::: en
The serpent is a "hybrid" answer in brass history: **it is driven by the lips (the brass way) but stops
notes with finger holes (the woodwind way).** It looks like a snake standing up, its wooden body sheathed in
leather — the name and the shape come from the same fact.

Its historical position is clear: **before valves, low brass had no reliable solution.** The serpent was one
attempt, the [[instrument:ophicleide|ophicleide]] its improved version, and the tuba the endpoint.

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · **lip-vibrated** · stopped by finger holes |
| **Sub-type** | Cup mouthpiece · **no valves** (six holes) · wooden body sheathed in leather · snake-shaped |
| **Family** | Western · Brass (early branch) |
| **Bayin** | Not applicable — a Chinese system; the serpent is outside it |

> ⚠️ **One conceptual point**: **"brass" names a drive, not a material.** The serpent is **wooden and
> leather-covered**, but it sounds by vibrating lips → it is **brass**; a [[instrument:recorder|recorder]] is
> wooden and driven by a cut jet → a **woodwind**. Conversely the metal flute is a woodwind.
> **Material, shape and name decide nothing — only what vibrates does.**

## Structure: snake shape, wood, leather, finger holes

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Serpent parts: cup mouthpiece, snake-shaped wooden body sheathed in leather, and six finger holes along the body">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Serpent — outer form and principal parts (wood, leather, six finger holes)</text>
  </g>
  <rect x="96" y="196" width="30" height="15" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.3"/>
  <path d="M126,198 C210,190 250,214 300,226 C350,238 380,268 380,310 C380,346 350,364 314,364 C280,364 256,344 254,318 C252,294 268,278 288,278"
        fill="none" stroke="#17171A" stroke-width="26" stroke-linecap="round"/>
  <path d="M126,198 C210,190 250,214 300,226 C350,238 380,268 380,310 C380,346 350,364 314,364 C280,364 256,344 254,318 C252,294 268,278 288,278"
        fill="none" stroke="#9C7A3C" stroke-width="26" stroke-linecap="round" opacity=".24"/>
  <g fill="#070706" stroke="#E07A3F" stroke-width="1.4">
    <circle cx="196" cy="204" r="7"/><circle cx="238" cy="214" r="7"/>
    <circle cx="284" cy="226" r="7"/><circle cx="330" cy="248" r="7"/>
    <circle cx="364" cy="288" r="7"/><circle cx="376" cy="336" r="7"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,150 L140,192"/><path d="M186,300 L246,318"/>
    <path d="M186,222 L190,204"/><path d="M486,240 L352,240"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="147" text-anchor="end">Cup mouthpiece (lip vibration)</text>
    <text x="180" y="303" text-anchor="end" fill="#9C7A3C">Wood sheathed in leather</text>
    <text x="180" y="225" text-anchor="end" fill="#E07A3F">Six finger holes</text>
    <text x="492" y="237">Snake-shaped (S-curve)</text>
  </g>
  <text x="20" y="384" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The holes are fixed while the hands decide how they are covered — so its intonation is unstable, worst low down.</text>
</svg>
```

Three points:

1. **Brass drive** (lip vibration, cup mouthpiece) with **woodwind note-selection** (six holes). The
   combination made it neither as easy to tune as a woodwind nor as stable as later valved brass.
2. **Wood sheathed in leather.** The leather kept the wooden body from splitting — and its damping is part of
   why the tone is veiled and coarse.
3. **Intonation was its great weakness.** The holes are fixed, yet hand position and air change the pitch
   markedly — the direct reason keys and valves later displaced it.

## What it contributed to "low brass"

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The technical lineage of low brass: serpent to ophicleide to tuba, and how notes came to be selected">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Selecting notes in low brass: a road towards stability</text>
  </g>
  <path d="M60,150 L580,150" stroke="#343439" stroke-width="2"/>
  <circle cx="120" cy="150" r="10" fill="#9C7A3C"/>
  <circle cx="300" cy="150" r="11" fill="#E07A3F"/>
  <circle cx="500" cy="150" r="12" fill="#5B7FA8"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="120" y="180">late 16th c.</text><text x="300" y="180">early 19th c.</text>
    <text x="500" y="180">1835 onwards</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="120" y="118" text-anchor="middle" fill="#9C7A3C">Serpent</text>
    <text x="120" y="204" text-anchor="middle" fill="#6E6A64">finger holes</text>
    <text x="300" y="114" text-anchor="middle" fill="#E07A3F">Ophicleide</text>
    <text x="300" y="204" text-anchor="middle" fill="#6E6A64">holes + keys</text>
    <text x="500" y="110" text-anchor="middle" fill="#5B7FA8">Tuba</text>
    <text x="500" y="204" text-anchor="middle" fill="#6E6A64">valves</text>
  </g>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Each step solved the same problem — "easier to play" is why instruments get replaced.</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The serpent served church music for nearly three centuries, then was displaced within a few decades.</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Technical "better" is ruthless — it keeps no sentimental attachment.</text>
</svg>
```

**It left two traces**:

- **A church-bass tradition.** It long carried the bass in French church music — before the tuba, a standard
  way to thicken a choir's bottom.
- **A remembered timbre.** Composers such as Berlioz remembered its colour and wrote it into new works (see
  the [[instrument:ophicleide|ophicleide]] entry).

## Range

```range
{"range":"C3–C5","common":"C3–G4","caption":"蛇形号的音域","caption_en":"Serpent range","note":"蛇形号是木制、蒙皮、蛇形弯曲的低音管乐器，靠唇鸣驱动、指孔取音。音域约 C3–C5。记谱即实音。"}
```

- **About C3–C5**, two octaves — exactly the register of a choral bass part.
- **The working register is C3–G4**, where it is at its veiled, thickest best.
- **Its intonation problem is worst low down**, where holes and partials leave little tolerance.

## Timbre, and how to hear it

Four cues:

1. **Veiled, coarse, growling.** Leather over wood adds a soft blur — why it is often called "deep and
   clumsy".
2. **Moderate volume but forward**: less projecting than modern low brass, adequate in small ensembles and
   church acoustics.
3. **The low register is difficult** — hard to tune and hard to sound, a direct reason for its replacement.
4. **The top is surprisingly open**: around C5 the tone clears, and players historically used it for higher
   parts too.

```audiolab
{"type":"instrument","gm":"Tuba","synth":"brass","phrase":["C3","G3","C4","E4","G4"],"label":"蛇形号的常用区：C3 到 G4","label_en":"The serpent's working register — C3 up to G4","hint":"注意音色的朦胧与粗糙 —— 通用音色表里没有蛇形号，这里借大号音色近似","hint_en":"Hear the veiled, coarse tone. General MIDI has no serpent, so a tuba sample stands in."}
```

> ⚠️ **On the audio**: the General MIDI set has **no serpent**. A **tuba** sample plays above — the register
> is right, but **the leather-and-wood blur is entirely absent.**

## Playing techniques

- **The holes are fixed; pitch is corrected by air and lips alone** — its hardest aspect.
- **An unusual hold**: the S-curve must be steadied by both hands, and the hole layout is unlike any modern
  woodwind's.
- **High lip control demanded**, since there is no keywork to compensate.

## The family

| Instrument | Drive | Note selection | Material | Era |
|---|---|---|---|---|
| **Serpent** | lip | **finger holes** | wood + leather | late 16th–19th c. |
| [[instrument:ophicleide\|Ophicleide]] | lip | **holes + keys** | brass | 19th c. |
| [[instrument:tuba\|Tuba]] | lip | **valves** | brass | from 1835 |
| [[instrument:natural-trumpet\|Natural trumpet]] | lip | series only | brass | Baroque |
| [[instrument:recorder\|Recorder]] | **cut jet** | finger holes | wood | from the Middle Ages |

**Compare the last row**: the serpent and the [[instrument:recorder|recorder]] both select notes with holes,
but their **drives differ completely** — lips versus air. **Holes are a way of selecting notes, not a
classification.**

## History

| Period | State |
|---|---|
| Late 16th c. (France) | appears; used in church music for the bass, supporting or replacing the bass voice |
| 17th–18th c. | widely used in French and English churches and bands; occasional orchestral use |
| Late 18th c. | improved versions appear (reinforcement, added keys, longer), but intonation stays unsolved |
| Early 19th c. | progressively displaced by the **ophicleide** |
| Late 19th c. | leaves standard ensembles, surviving only in occasional revival performances |
| 20th c. | the early-music movement brings it back for a few performances; composers write new works for it |

## Common misconceptions

- **"The serpent is a woodwind."** It is a **wooden brass** — the test is what vibrates (lips), not material.
- **"It is the tuba's ancestor, so they are similar."** Note selection is entirely different (holes versus
  valves) — its intonation, volume and agility are far below a tuba's.
- **"It is a curiosity."** It served French church music for nearly three centuries: an entirely practical
  musical life.
- **"Holes make it easy to play in tune."** The opposite: fixed holes leave intonation to air and lips — its
  greatest weakness.
- **"It has disappeared."** The early-music movement keeps it alive, and contemporary composers write for it.

## Next

Its direct successor is the [[instrument:ophicleide|ophicleide]] (brass, with keys) — that entry explains
**why keys also failed to save low brass**.

For the conclusion, go to the [[instrument:tuba|tuba]]: **valves won for a plain reason — they are easier to
play.**
:::
