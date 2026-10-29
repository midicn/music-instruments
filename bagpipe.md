---
id: bagpipe
site: inst
cat: I12
title: 风笛
title_en: The bagpipe
summary: 气袋储气，旋律管与持续管同时发声，换气也不断音
summary_en: A bag stores the breath, a chanter carries the melody and drones hold the bass, so the sound never stops for a breath
level: standard
tags: [乐器, 世界, 欧洲, 气鸣, 风笛, 民间]
tags_en: [instrument, world, europe, aerophone, bagpipe, folk]
alias: [风笛, bagpipe, 苏格兰风笛, 高地风笛, 爱尔兰风笛, uilleann pipes, gaida, 风袋管]
order: 232
links:
  - "[[instrument:hurdy-gurdy]]"
  - "[[instrument:shawm]]"
  - "[[instrument:portative-organ]]"
instances:
  - thesession-022376 | 《Bagpipe》是一首以风笛命名的爱尔兰曲调；曲库版本是单线旋律，能听旋律管的九音骨架，不是风笛音色
  - nottingham-000134 | 《The Leaking Bagpipe》把漏气写进标题：气袋漏气，持续音就撑不住；可对照气密这件决定成败的工艺
  - thesession-018016 | 《Cicerenella For Bagpipe》是那不勒斯曲调，标题写明为风笛而作，把风笛放进意大利南方的舞曲语境
  - thesession-007335 | 《Svanda The Bagpiper》源自波希米亚的风笛手故事，同一件乐器在另一片传统里成了人物绰号
sources:
  - 结构、高地九音与低音 A 470–480 Hz 定音，uilleann 风箱与 regulators、gaida 与 mizwad 分布，参 Wikipedia "Bagpipes" 与 Grove "Bagpipe"
  - 曲库无风笛录音，实例取 C1 相关旋律并说明
updated: 2026-10-28
---

::: zh
风笛的关键不在管子，在**气袋**。嘴或风箱只负责补气，袋子以稳定压力供气给旋律管与持续管。

## 主线与结构：气袋、旋律管、持续管

这是一条**能量链**：气源 → 气袋 → 簧片 → 管子。**旋律管**（chanter）有指孔，唱旋律；**持续管**（drones）没有指孔，只钉住一个音。气袋把肺的脉冲抹平；肖姆管的句子必须为换气让路，风笛不必。

| 部件 | 作用 | 关键点 |
|---|---|---|
| 气袋 | 储气、稳压 | 皮革或合成材料，手臂压袋 |
| 吹管 | 补气 | 单向阀，气只进不出 |
| 旋律管 | 唱旋律 | 双簧、圆锥管、指孔；高地风笛九音 |
| 持续管 | 守低音 | 单簧、圆柱管；定主音、五度或八度 |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="风笛结构：吹管给气袋补气，气袋以稳定压力驱动带指孔的旋律管和三根持续管">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">风笛 · 气袋把断续的呼吸变成持续气流</text>
  <path d="M150,160 C180,128 285,126 318,158 C350,190 338,262 288,280 C232,300 164,286 140,246 C122,214 124,188 150,160 Z" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="2"/>
  <path d="M108,118 L164,146" stroke="#8A6B34" stroke-width="9" stroke-linecap="round"/>
  <path d="M103,114 L117,121" stroke="#B5761E" stroke-width="12" stroke-linecap="round"/>
  <path d="M218,280 L218,344" stroke="#8A6B34" stroke-width="11" stroke-linecap="round"/>
  <path d="M268,184 L416,92" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <path d="M282,198 L440,112" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <path d="M296,214 L464,134" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <text x="70" y="108" font-size="11" fill="#5A554E">吹管</text>
  <text x="188" y="226" font-size="11" fill="#5A554E">气袋</text>
  <text x="218" y="364" font-size="11" fill="#5A554E" text-anchor="middle">旋律管</text>
  <text x="470" y="70" font-size="11" fill="#5A554E">持续管</text>
</svg>
```

## 连续的代价：换气与力度

吸气时手臂继续压袋，袋子仍在供气，所以听不到换气缝。代价是**力度**：气压必须稳，否则持续管走音；重音靠**装饰音**与指法，不靠气流。

uilleann 用风箱，旋律管可膝上停音，三根 regulators 还能配和弦；**"风笛不能停"只对嘴吹的战争型风笛成立。**

## 音域与音色

```range
{"range":"G4–D6","common":"A4–A5","caption":"风笛的音域（家族合幅：高地风笛与 uilleann）","caption_en":"Bagpipe range (family composite: Highland and uilleann)","note":"高地九音记谱 G4–A5，低音 A 定 470–480 Hz，实际高半音；uilleann 为 D4–D6。本图为家族合幅，只比较跨度。","note_en":"Highland nine are written G4–A5, sounding a semitone higher at low A 470–480 Hz; uilleann runs D4–D6. A composite fence for span only."}
```

高地九音是 **G、A、B、C♯、D、E、F♯、G、A**，没有 C 自然音，总带调式色彩。持续管定 A：两根 tenor 在 A3，一根 bass 在 A2。

```audiolab
{"type":"instrument","gm":"Bagpipe","synth":"reed","phrase":["G4","A4","B4","C#5","D5","E5","F#5","G5","A5"],"label":"高地风笛的九音：低 G 到高 A","label_en":"The Highland chanter's nine notes, low G to high A","hint":"GM 表里有 Bagpipe；它没有持续管与装饰音，只能听九音骨架","hint_en":"GM has a Bagpipe program; without drones or gracenotes it gives only the nine-note skeleton."}
```

## 家族与手摇琴对照

| 类型 | 气源 | 特征 |
|---|---|---|
| 高地风笛 | 嘴吹 | 三持续管、九音、无断音 |
| 爱尔兰 uilleann | 风箱 | 两八度、可停音、regulators |
| 巴尔干 gaida | 嘴吹或风箱 | 单或双旋律管，常伴圈舞 |
| 马格里布 mizwad | 嘴吹 | 皮袋、单或双管，婚礼节庆 |

与[[instrument:hurdy-gurdy|手摇琴]]对照：两者都把持续低音做进乐器，差别在发声体——风笛是**空气柱**，手摇琴是**弦**。

## HS 分类

| 项 | 内容 |
|---|---|
| HS 类 | **气鸣**（Aerophone）· 簧管 + 气袋 |
| 次级类型 | 旋律管 422.112.2（双簧、圆锥管）· 持续管 422.221.1（单簧、圆柱管） |
| 所属族 | 欧洲 · 民间（苏格兰、爱尔兰、巴尔干、伊比利亚、马格里布） |
| 关键特征 | 气袋稳压 · 持续管常鸣 · 换气不断音 · 力度近乎恒定 |

## 常见误解

- **"风笛是苏格兰发明的。"** 风笛遍布欧洲、北非与西亚；高地风笛只是最有名的一支。
- **"风笛手用嘴直接吹出声音。"** 嘴只补气，声音由袋内气压驱动簧片。
- **"风笛可以渐强渐弱。"** 高地风笛几乎不能；稳定气压是音准前提。

## 带走三件事

1. **气袋是机关**：把断续的呼吸变成连续的气压。
2. **旋律管加持续管**：旋律与低音同时出自同一袋气。
3. **连续有代价**：没有换气缝，也几乎没有力度变化；uilleann 用风箱与停音换回了另一种可能。
:::

::: en
A bagpipe's mechanism is not in the pipes but in the **bag**. A mouth or bellows only fills it; the bag feeds a chanter and drones at steady pressure.

## The main line and structure: bag, chanter, drones

It is a **chain of energy**: source → bag → reed → pipe. The **chanter** has finger holes and carries the melody; the **drones** have none and hold one note each. The bag smooths the pulses of the lungs, which separates it from a [[instrument:shawm|shawm]]: a shawm's phrases must leave room for breath, a bagpipe's need not.

| Part | Job | Key point |
|---|---|---|
| Bag | stores air, smooths pressure | leather or synthetic; pressed by the arm |
| Blowpipe | refills the bag | one-way valve, air in but not out |
| Chanter | plays the melody | double reed, conical bore, finger holes; nine notes on the Highland pipe |
| Drones | hold the bass | single reeds, cylindrical bores; tonic, fifth or octave |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bagpipe structure: a blowpipe refills the bag, which feeds a fingered chanter and three drones at steady pressure">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">Bagpipe — the bag turns an intermittent breath into a steady stream</text>
  <path d="M150,160 C180,128 285,126 318,158 C350,190 338,262 288,280 C232,300 164,286 140,246 C122,214 124,188 150,160 Z" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="2"/>
  <path d="M108,118 L164,146" stroke="#8A6B34" stroke-width="9" stroke-linecap="round"/>
  <path d="M103,114 L117,121" stroke="#B5761E" stroke-width="12" stroke-linecap="round"/>
  <path d="M218,280 L218,344" stroke="#8A6B34" stroke-width="11" stroke-linecap="round"/>
  <path d="M268,184 L416,92" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <path d="M282,198 L440,112" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <path d="M296,214 L464,134" stroke="#8A6B34" stroke-width="7" stroke-linecap="round"/>
  <text x="70" y="108" font-size="11" fill="#5A554E">Blowpipe</text>
  <text x="188" y="226" font-size="11" fill="#5A554E">Bag</text>
  <text x="218" y="364" font-size="11" fill="#5A554E" text-anchor="middle">Chanter</text>
  <text x="470" y="70" font-size="11" fill="#5A554E">Drones</text>
</svg>
```

## The price of continuity: breath and dynamics

While the player inhales, the arm keeps pressing, so no breath is heard. The price is **dynamics**: pressure must stay steady or the drones drift; accents come from **gracenotes** and fingering, not from air.

The Irish uilleann pipes are the counterexample: bellows supply air, the chanter can be stopped on the knee, and three regulators add chords. **"A bagpipe cannot stop" is true only of the mouth-blown pipe.**

## Range and timbre

```range
{"range":"G4–D6","common":"A4–A5","caption":"风笛的音域（家族合幅：高地风笛与 uilleann）","caption_en":"Bagpipe range (family composite: Highland and uilleann)","note":"高地九音记谱 G4–A5，低音 A 定 470–480 Hz，实际高半音；uilleann 为 D4–D6。本图为家族合幅，只比较跨度。","note_en":"Highland nine are written G4–A5, sounding a semitone higher at low A 470–480 Hz; uilleann runs D4–D6. A composite fence for span only."}
```

The Highland nine are **G, A, B, C♯, D, E, F♯, G, A**, with no natural C, hence its modal colour. The drones tune to A: two tenors on A3, one bass on A2.

```audiolab
{"type":"instrument","gm":"Bagpipe","synth":"reed","phrase":["G4","A4","B4","C#5","D5","E5","F#5","G5","A5"],"label":"高地风笛的九音：低 G 到高 A","label_en":"The Highland chanter's nine notes, low G to high A","hint":"GM 表里有 Bagpipe；它没有持续管与装饰音，只能听九音骨架","hint_en":"GM has a Bagpipe program; without drones or gracenotes it gives only the nine-note skeleton."}
```

## The family, and the hurdy-gurdy

| Type | Air supply | Features |
|---|---|---|
| Highland pipe | mouth | three drones, nine notes, no stopping |
| Irish uilleann | bellows | two octaves, stoppable, regulators |
| Balkan gaida | mouth or bellows | one or two chanters, circle dances |
| Maghrebi mizwad | mouth | skin bag, one or two pipes, weddings |

Against the [[instrument:hurdy-gurdy|hurdy-gurdy]]: both build in a drone, but a bagpipe moves an **air column**, a hurdy-gurdy a **string**.

## HS classification

| Item | Content |
|---|---|
| HS class | **Aerophone** · reedpipes with a bag |
| Sub-type | chanter 422.112.2 (double reed, conical bore) · drones 422.221.1 (single reed, cylindrical bore) |
| Family | Europe · folk (Scotland, Ireland, the Balkans, Iberia, the Maghreb) |
| Key features | steady bag pressure · always-on drones · no break for breath · nearly constant dynamics |

## Common misconceptions

- **"The bagpipe was invented in Scotland."** Bagpipes are spread across Europe, North Africa and West Asia; the Highland pipe is only the most famous branch.
- **"The player blows the sound directly."** The mouth only refills the bag; its pressure drives the reeds.
- **"A bagpipe can crescendo."** The Highland pipe hardly can; steady pressure keeps it in tune.

## Three things to take away

1. **The bag is the mechanism**: it turns intermittent breath into continuous pressure.
2. **Chanter plus drones**: melody and bass come from the same bag of air.
3. **Continuity has a price**: no breath seam and almost no dynamics; the uilleann pipe buys another possibility with bellows and stopping.
:::
