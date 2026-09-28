---
id: pan-flute
site: inst
cat: I2
title: 排箫
title_en: Pan Flute
summary: 多根闭管并排、每管一音，世界多地独立出现的古老乐器
summary_en: Several closed tubes in a row, one note each — an ancient instrument invented worldwide
level: standard
tags: [乐器, 木管, 西洋, 世界]
tags_en: [instrument, woodwind, western, world]
alias: [排箫, pan flute, panpipes, 潘笛, 排笛, nai, siku, 箫管]
order: 41
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:recorder]]"
  - "[[instrument:ocarina]]"
  - "[[instrument:flute]]"
  - "[[instrument:clarinet]]"
instances:
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— **竖笛**演奏；对照"管"与"多根闭管"的音色差别
  - giantmidi-000507 | C 小调竖笛协奏曲 —— 同为无簧边棱音的独奏写法
  - pdmx-002065 | 为竖笛与长笛而作的协奏曲 —— 对照哨嘴驱动与嘴唇驱动两种边棱音
sources:
  - 结构依通行乐器资料：若干根**一端封闭的管**按音高并排固定，每管一音，管口为开口端（吹奏端），无簧片、无键
  - 「闭管只产生奇次泛音，因此音色偏暗、带气流声」依管乐器声学（与单簧管同属奇次泛音体系）
  - 「排箫音域约 G3–G6（视管数与形制而定）」依通行乐器资料
  - 「同类乐器在世界多地独立出现：古希腊的潘笛、罗马尼亚的 nai、中国的排箫、安第斯山的 siku 与 zampoña 等」依乐器史与民族音乐学
  - ⚠️ 库内没有标题可确认为排箫的曲目 —— 本条给出的是**同为无簧边棱音**的竖笛曲目作音色参照，音色由试听件负责
updated: 2026-09-26
---

::: zh
排箫是木管里结构最简单、分布却最广的一件：**把若干根一端封闭的管按音高并排绑在一起，每管一音。**
没有簧片、没有键、没有可变的长度 —— 想要哪个音，就吹哪根管。

它的"闭"和[[instrument:ocarina|陶笛]]的"闭"不是一回事：陶笛闭的是**腔**（音高看容积），
排箫闭的是**管**（音高看管长）。而这个"闭"字带来一个很具体的声学后果。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· 边棱音 · **多根闭管** |
| **次级类型** | 竖吹 · 无簧片 · 无键 · **每管一音** |
| **所属族** | 西洋 · 木管（哨嘴族 · 多管支系）· 同时是世界乐器 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系；中国的**排箫属竹**，见中国乐器部分 |

> ⚠️ **一个概念上的要点**：**闭管只产生奇次泛音**（1、3、5…）。
> 这一条把排箫与[[instrument:clarinet|单簧管]]归到同一个声学家族 —— 两者的音色都因此偏暗、带"空"，
> 而[[instrument:flute|长笛]]、[[instrument:recorder|竖笛]]这类**开管**则泛音齐全、音色更亮。
> **同一件乐器的音色"亮还是暗"，在木管里很多时候先由"开管还是闭管"决定，
> 然后才轮到材料。**

## 结构：每管一音

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="排箫的结构：一排长短不等的闭管并排，管长者音低；下端封闭，上端开口为吹口">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">排箫 · 多根一端封闭的管并排（管越长，音越低）</text>
  </g>
  <rect x="100" y="150" width="30" height="150" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="134" y="132" width="30" height="168" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="168" y="116" width="30" height="184" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="202" y="102" width="30" height="198" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="236" y="90" width="30" height="210" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="270" y="80" width="30" height="220" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="304" y="72" width="30" height="228" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="338" y="66" width="30" height="234" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="372" y="62" width="30" height="238" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="406" y="60" width="30" height="240" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="440" y="60" width="30" height="240" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <path d="M100,300 L470,300" stroke="#9C7A3C" stroke-width="4"/>
  <path d="M96,150 L474,150 L474,142 L96,142 Z" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,80 L110,146"/><path d="M186,120 L160,120"/>
    <path d="M186,250 L104,250"/><path d="M186,300 L300,300"/>
    <path d="M486,116 L452,116"/><path d="M486,270 L462,270"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="83" text-anchor="end">上端开口：气流切过棱边</text>
    <text x="180" y="123" text-anchor="end" fill="#5B7FA8">管长依次递增</text>
    <text x="180" y="253" text-anchor="end">下端封闭（闭管）</text>
    <text x="180" y="303" text-anchor="end">固定用的横梁或框架</text>
    <text x="492" y="119">每管一音</text>
    <text x="492" y="273">管越长，音越低</text>
  </g>
  <text x="20" y="328" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">它把"音阶"直接做成了实物：一排管就是一条音阶，吹哪根就响哪个音 —— 这是最直白的乐器。</text>
</svg>
```

三处要点：

1. **每管一音，管长即音高**。这排管本身就是一条可视化的音阶。
2. **闭管 → 只产生奇次泛音**。所以它的音色偏暗、带气流声，
   与[[instrument:clarinet|单簧管]]属同一个声学体系（见下节）。
3. **吹奏靠嘴唇与气流角度**。它不用哨嘴，而是靠嘴唇对准管口的边缘 ——
   所以它的**可塑性比竖笛大**，但比长笛小。

## 闭管与开管

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="开管与闭管的泛音对比：开管泛音齐全音色亮，闭管只有奇次泛音音色暗">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">开管与闭管：音色的第一次分岔</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">开管（长笛 · 竖笛）</text>
  <rect x="60" y="90" width="200" height="26" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <g stroke="#5B7FA8" stroke-width="7" stroke-linecap="round">
    <path d="M96,168 L96,124"/><path d="M126,168 L126,136"/>
    <path d="M156,168 L156,146"/><path d="M186,168 L186,154"/>
    <path d="M216,168 L216,160"/>
  </g>
  <path d="M82,168 L240,168" stroke="#343439" stroke-width="1.2"/>
  <text x="160" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">1 · 2 · 3 · 4 · 5 次泛音齐全</text>
  <text x="160" y="214" text-anchor="middle" font-size="10.5" fill="#5B7FA8">音色亮、泛音丰富</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">闭管（排箫 · 单簧管）</text>
  <rect x="380" y="90" width="200" height="26" rx="3" fill="#17171A" stroke="#E07A3F" stroke-width="1.4"/>
  <path d="M380,90 L380,116" stroke="#E07A3F" stroke-width="4"/>
  <g stroke="#E07A3F" stroke-width="7" stroke-linecap="round">
    <path d="M416,168 L416,124"/><path d="M446,168 L446,146"/>
    <path d="M476,168 L476,158"/><path d="M506,168 L506,164"/>
  </g>
  <path d="M402,168 L560,168" stroke="#343439" stroke-width="1.2"/>
  <text x="480" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">只有 1 · 3 · 5 次泛音</text>
  <text x="480" y="214" text-anchor="middle" font-size="10.5" fill="#E07A3F">音色暗、带气流声</text>
  <text x="20" y="250" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">左图的竖线是各次泛音的强度：开管两端的边界条件一致，泛音齐全；闭管一端封闭，偶次泛音被排除。</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">这一条同时解释了单簧管为什么"缺一个八度"（超吹得十二度）—— 与排箫是同一个原因。</text>
</svg>
```

**这里出现了木管声学的第三个层次**（前两个是驱动方式与管形）：

| 层次 | 决定什么 | 例 |
|---|---|---|
| **驱动** | 音色的可塑性与稳定度 | 边棱音 / 单簧 / 双簧 |
| **管形** | 音区是否分裂 | 圆柱 / 圆锥 |
| **开闭** | 泛音齐不齐 → 亮不亮 | 开管 / 闭管 |

排箫是"闭管"这一条最干净的例证 —— 它没有任何按键、没有簧片，
**唯一的声学特征就是"闭"**，而音色立刻变暗。

## 音域

```range
{"range":"G3–G6","common":"C4–C6","caption":"排箫的音域（以约 20 管的形制为例）","caption_en":"Pan flute range (a roughly 20-tube instrument)","note":"排箫的音域随管数与形制变化很大 —— 从安第斯山区两组各六支的小型 siku，到罗马尼亚约二十管的 nai。这里以较完整的形制为例，约 G3–G6（三个八度）。记谱即实音，不移调。"}
```

- **约 G3–G6**（三个八度），是管数较多的形制。
- **小型形制窄得多**：安第斯 siku 常做成**两组各六到八支**，一人只管一组，
  两人交替吹奏才能奏出完整音阶 —— 这是一种**社会性的乐器设计**。
- **换管即换音**。演奏者靠移动乐器（而不是按孔）来选择音高，所以快速乐句要求极高的准确性。

## 音色与听辨

四条线索：

1. **暗、空、带明显的气流声**。这是闭管的直接结果，也是它在世界音乐里最容易被认出的特征。
2. **音量不大，但穿透有特点**。它的高频少，却在安静的段落里非常醒目。
3. **滑音天然可行**。因为靠移动管口对准嘴唇，滑音几乎是它的本能动作。
4. **各管音色略有差异**。管子越短，音越高，气流声占比越大 —— 所以它的高音区比低音区更"沙"。

```audiolab
{"type":"instrument","gm":"Pan Flute","synth":"blown","phrase":["G4","C5","E5","G5","C6"],"label":"排箫的常用区：G4 到 C6","label_en":"The pan flute's working register — G4 up to C6","hint":"注意音色里的「空」与气流声 —— 闭管只有奇次泛音，所以它天生比长笛暗","hint_en":"Hear the hollowness and the air — a closed tube has only odd harmonics, so it is darker than a flute."}
```

## 演奏技法

- **移动乐器选音**（不按键）。这是它与其他所有木管最根本的操作差别。
- **滑音与"甩"音**。靠嘴唇在管口滑动，可以做出极流畅的滑音 ——
  罗马尼亚与安第斯的演奏风格都大量使用它。
- **循环呼吸**。为了做长线条，排箫演奏者普遍使用循环呼吸 ——
  这在民族演奏传统里是基本功。
- **气息角度控制音高**。同一根管上靠角度可以做到约一个半音的微调（与陶笛类似）。

## 家族与近亲

| 乐器 | 驱动 | 共鸣 | 泛音 | 音色 |
|---|---|---|---|---|
| [[instrument:recorder\|竖笛]] | 哨嘴风道 | 开管 | 齐全 | 清亮、直朴 |
| [[instrument:ocarina\|陶笛]] | 哨嘴风道 | **闭腔** | 少 | 圆润、近乎纯音 |
| **排箫** | 嘴唇 | **多根闭管** | **只有奇次** | 暗、空、带气声 |
| [[instrument:flute\|长笛]] | 嘴唇 | 开管 | 齐全 | 亮、可塑性强 |
| [[instrument:clarinet\|单簧管]] | 单簧片 | **闭管**（圆柱） | **只有奇次** | 暗、厚、音区分裂 |

**排箫与单簧管在同一列（只有奇次泛音）**，但驱动方式完全不同 ——
一个靠嘴唇、一个靠簧片。**音色的"明暗"由开闭决定，音色的"性格"由驱动决定** ——
两个维度各管一段。

## 世界分布

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="排箫在世界各地的不同名称与形制：古希腊潘笛、罗马尼亚nai、中国排箫、安第斯siku与zampona、非洲与大洋洲的竹排箫">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一件乐器，世界各地的名字与形制</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="62" fill="#5B7FA8">古希腊 · 潘笛（syrinx）</text>
    <text x="20" y="82" fill="#6E6A64">神话里潘神的乐器；后世欧洲排箫的源头</text>
    <text x="20" y="122" fill="#E07A3F">罗马尼亚 · nai</text>
    <text x="20" y="142" fill="#6E6A64">约二十管，音域最宽的形制之一；东欧与吉普赛音乐常用</text>
    <text x="20" y="182" fill="#9C7A3C">中国 · 排箫</text>
    <text x="20" y="202" fill="#6E6A64">竹制，属八音中的「竹」；先秦已有，后世多用于雅乐</text>
    <text x="20" y="242" fill="#A9A49B">安第斯 · siku / zampoña</text>
    <text x="20" y="262" fill="#6E6A64">常做成两组各六至八支，两人交替吹奏成完整音阶</text>
    <text x="20" y="302" fill="#6E6A64">非洲与大洋洲 · 竹排箫</text>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M420,56 L520,56"/><path d="M420,116 L520,116"/>
    <path d="M420,176 L520,176"/><path d="M420,236 L520,236"/>
    <path d="M420,296 L520,296"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="526" y="60">单排 · 平直</text>
    <text x="526" y="120">单排 · 平直</text>
    <text x="526" y="180">单排 / 双翼</text>
    <text x="526" y="240">双排 · 拱形</text>
    <text x="526" y="300">单排 / 阶梯</text>
  </g>
</svg>
```

**它是"独立发明"的典型例子**：古希腊、中国、安第斯、非洲各自的排箫**没有共同的源头**，
而是不同的人群各自发现了同一种最简单的解决方案 ——
"想要更多音，就并排多放几根管"。

这也让它在民族音乐学里成为一个常被引用的案例：
**形制相似不等于传播，也可能只是同一个物理约束下的必然结果。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 史前—古代 | 竹、木、骨、陶制成的多管吹奏器在世界多地出现；古希腊的潘笛最早见于文献与图像 |
| 中国先秦 | **排箫**（一名箫管）已见于记载；竹制，用于宫廷雅乐与祭祀 |
| 欧洲 | 中世纪与文艺复兴时期作为民间乐器使用，也见于绘画；巴洛克后逐渐退出艺术音乐 |
| 19—20 世纪 | 罗马尼亚的 **nai** 被改良为可完整演奏半音的乐器；东欧与吉普赛乐队常用 |
| 20 世纪 | 安第斯的 siku / zampoña 随南美民谣（如《El Cóndor Pasa》）传遍世界 |
| 20 世纪后期至今 | 在民族音乐、新世纪音乐与影视配乐中广泛使用 |

## 常见误解

- **"排箫是玩具或民俗乐器。"** 它有完整的音阶与成体系的演奏技法，
  罗马尼亚的 nai 能演奏高度复杂的古典与民间曲目。
- **"它和陶笛是一回事。"** 都被叫做"闭"，但闭的对象不同：
  陶笛闭的是**腔**（音高看容积），排箫闭的是**管**（音高看管长）。
- **"排箫一定是同一个东西传遍世界的。"** 它是**独立发明**的典型 ——
  各地形制相似，但没有共同的源头，只是物理约束下的同一种解法。
- **"排箫的音色亮。"** 闭管只有奇次泛音，所以它天生**偏暗、带气流声** ——
  想要亮的音色就得用开管（如长笛、竖笛）。
- **"中国的排箫是外来乐器。"** 中国的排箫是**独立发展的竹制乐器**，
  属八音中的「竹」，先秦已有记载 —— 与古希腊的潘笛是并行传统。

## 下一步

到这里，**西洋木管组（I2）18 条全部完成**。

这一批留下的不只是条目，还有一条贯穿全组的主线 —— **木管的三个声学层次**：
**驱动方式**（边棱音 / 单簧 / 双簧）决定音色的性格与稳定性，
**管形**（圆柱 / 圆锥）决定音区是否分裂，
**开闭**（开管 / 闭管）决定泛音齐不齐、音色亮不亮。
三个层次各管一段，**任何一件木管都能在它们构成的坐标里被定位**。

接下来木管组要正式交棒 —— 下一组是**铜管**，
那是一个全新的驱动原理：**靠嘴唇振动**，而不是靠气流切边或簧片开合。
:::

::: en
The pan flute is the simplest woodwind to describe and the most widely distributed: **several tubes, closed
at one end, bound together in pitch order — one note per tube.** No reed, no keys, no moving parts: to play
a note, aim at the right tube.

Its "closed" is not the [[instrument:ocarina|ocarina]]'s "closed": the ocarina closes a **cavity** (pitch by
volume), the pan flute closes **tubes** (pitch by length). And that word carries a very concrete acoustic
consequence.

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · edge-tone · **several closed tubes** |
| **Sub-type** | Vertical · reedless · keyless · **one note per tube** |
| **Family** | Western · Woodwinds (duct family, multi-tube branch) · also a world instrument |
| **Bayin** | Not applicable — a Chinese system; the Chinese **paixiao is a bamboo (竹) instrument**, covered with Chinese instruments |

> ⚠️ **One conceptual point**: **a closed tube produces only odd harmonics** (1, 3, 5…). That places the pan
> flute in the same acoustic family as the [[instrument:clarinet|clarinet]]: both sound dark and hollow,
> while **open** tubes such as the [[instrument:flute|flute]] and [[instrument:recorder|recorder]] carry all
> the harmonics and sound brighter. **In woodwinds, whether a tone is bright or dark is often settled first
> by open versus closed, and only then by material.**

## Structure: one note per tube

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pan flute structure: a row of tubes of increasing length, closed at the bottom and open at the top where the air is blown across the edge">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Pan flute — many tubes closed at one end (longer tube, lower note)</text>
  </g>
  <rect x="100" y="150" width="30" height="150" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="134" y="132" width="30" height="168" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="168" y="116" width="30" height="184" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="202" y="102" width="30" height="198" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="236" y="90" width="30" height="210" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="270" y="80" width="30" height="220" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="304" y="72" width="30" height="228" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="338" y="66" width="30" height="234" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="372" y="62" width="30" height="238" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="406" y="60" width="30" height="240" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <rect x="440" y="60" width="30" height="240" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.3"/>
  <path d="M100,300 L470,300" stroke="#9C7A3C" stroke-width="4"/>
  <path d="M96,150 L474,150 L474,142 L96,142 Z" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,80 L110,146"/><path d="M186,120 L160,120"/>
    <path d="M186,250 L104,250"/><path d="M186,300 L300,300"/>
    <path d="M486,116 L452,116"/><path d="M486,270 L462,270"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="83" text-anchor="end">Open top: the jet edge</text>
    <text x="180" y="123" text-anchor="end" fill="#5B7FA8">Tubes grow longer in step</text>
    <text x="180" y="253" text-anchor="end">Closed at the bottom</text>
    <text x="180" y="303" text-anchor="end">A rail or frame holds them</text>
    <text x="492" y="119">One note per tube</text>
    <text x="492" y="273">Longer tube, lower note</text>
  </g>
  <text x="20" y="328" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">It makes a scale into an object: one row of tubes is one scale — blow the tube you want.</text>
</svg>
```

Three points:

1. **One note per tube; length is pitch.** The row of tubes is a visible scale.
2. **Closed tubes give only odd harmonics**, hence the dark, airy tone — the same acoustic family as the
   [[instrument:clarinet|clarinet]] (next section).
3. **It is blown across the edge with the lips**, not through a duct — so it is **more flexible than a
   recorder**, though less than a flute.

## Open and closed tubes

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Open versus closed tubes: an open tube carries all harmonics and sounds bright, a closed tube only odd ones and sounds dark">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Open and closed: the first fork in the road for colour</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Open tube (flute · recorder)</text>
  <rect x="60" y="90" width="200" height="26" rx="3" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <g stroke="#5B7FA8" stroke-width="7" stroke-linecap="round">
    <path d="M96,168 L96,124"/><path d="M126,168 L126,136"/>
    <path d="M156,168 L156,146"/><path d="M186,168 L186,154"/>
    <path d="M216,168 L216,160"/>
  </g>
  <path d="M82,168 L240,168" stroke="#343439" stroke-width="1.2"/>
  <text x="160" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">harmonics 1 · 2 · 3 · 4 · 5 all present</text>
  <text x="160" y="214" text-anchor="middle" font-size="10.5" fill="#5B7FA8">bright and harmonically rich</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Closed tube (pan flute · clarinet)</text>
  <rect x="380" y="90" width="200" height="26" rx="3" fill="#17171A" stroke="#E07A3F" stroke-width="1.4"/>
  <path d="M380,90 L380,116" stroke="#E07A3F" stroke-width="4"/>
  <g stroke="#E07A3F" stroke-width="7" stroke-linecap="round">
    <path d="M416,168 L416,124"/><path d="M446,168 L446,146"/>
    <path d="M476,168 L476,158"/><path d="M506,168 L506,164"/>
  </g>
  <path d="M402,168 L560,168" stroke="#343439" stroke-width="1.2"/>
  <text x="480" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">only 1 · 3 · 5 present</text>
  <text x="480" y="214" text-anchor="middle" font-size="10.5" fill="#E07A3F">dark, with audible air</text>
  <text x="20" y="250" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The bars show each harmonic's strength: matching ends keep all of them; one closed end excludes the even ones.</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The same fact explains the clarinet's twelfth and its "missing octave" — one cause, two instruments.</text>
</svg>
```

**A third layer of woodwind acoustics appears here** (after drive and bore shape):

| Layer | Decides | Examples |
|---|---|---|
| **Drive** | flexibility and stability of colour | edge-tone / single reed / double reed |
| **Bore** | whether registers split | cylindrical / conical |
| **Open or closed** | harmonic completeness → brightness | open / closed |

The pan flute is the cleanest demonstration of the "closed" layer: no keys, no reed — **the only acoustic
feature is being closed**, and the colour turns dark at once.

## Range

```range
{"range":"G3–G6","common":"C4–C6","caption":"排箫的音域（以约 20 管的形制为例）","caption_en":"Pan flute range (a roughly 20-tube instrument)","note":"排箫的音域随管数与形制变化很大 —— 从安第斯山区两组各六支的小型 siku，到罗马尼亚约二十管的 nai。这里以较完整的形制为例，约 G3–G6（三个八度）。记谱即实音，不移调。"}
```

- **About G3–G6** (three octaves) for a fuller instrument.
- **Small forms are far narrower**: an Andean siku is often **two rows of six to eight tubes**, one row per
  player, so a complete scale needs two people alternating — a **social instrument design**.
- **Changing note means moving the instrument**, not covering a hole, so fast passagework demands great
  accuracy.

## Timbre, and how to hear it

Four cues:

1. **Dark, hollow, audibly airy** — the direct result of a closed tube, and its most recognisable trait in
   world music.
2. **Modest volume with a distinctive presence**: little high frequency, yet very noticeable in quiet
   passages.
3. **Glissando is built in**, since the player moves the tube mouth across the lips.
4. **Each tube colours slightly differently**: shorter tubes mean more air noise, so the top sounds
   "sandier" than the bottom.

```audiolab
{"type":"instrument","gm":"Pan Flute","synth":"blown","phrase":["G4","C5","E5","G5","C6"],"label":"排箫的常用区：G4 到 C6","label_en":"The pan flute's working register — G4 up to C6","hint":"注意音色里的「空」与气流声 —— 闭管只有奇次泛音，所以它天生比长笛暗","hint_en":"Hear the hollowness and the air — a closed tube has only odd harmonics, so it is darker than a flute."}
```

## Playing techniques

- **Moving the instrument to choose the note** — the fundamental operational difference from every other
  woodwind.
- **Slides and scoops.** Drawing the lips across the tube mouths gives very smooth glissandi — heavily used
  in Romanian and Andean styles.
- **Circular breathing.** To sustain long lines, pan flute players commonly use it; in folk traditions it is
  basic technique.
- **Air angle controls pitch**: on one tube, roughly a semitone of adjustment (as on an ocarina).

## The family

| Instrument | Drive | Resonator | Harmonics | Timbre |
|---|---|---|---|---|
| [[instrument:recorder\|Recorder]] | duct head | open tube | all | clear, plain |
| [[instrument:ocarina\|Ocarina]] | duct head | **closed vessel** | few | round, near-pure |
| **Pan flute** | lips | **several closed tubes** | **odd only** | dark, hollow, airy |
| [[instrument:flute\|Flute]] | lips | open tube | all | bright, flexible |
| [[instrument:clarinet\|Clarinet]] | single reed | **closed tube** (cylindrical) | **odd only** | dark, thick, split registers |

**The pan flute and the clarinet share the "odd harmonics only" column**, but their drives are entirely
different — one by lips, one by reed. **Brightness comes from open versus closed; character comes from the
drive** — two dimensions, each handling its own stretch.

## Around the world

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Names and forms of panpipes around the world: the Greek syrinx, the Romanian nai, the Chinese paixiao, Andean siku and zampona, and African and Pacific bamboo panpipes">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One instrument, many names and forms</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="62" fill="#5B7FA8">Ancient Greece · syrinx</text>
    <text x="20" y="82" fill="#6E6A64">the pipes of Pan; an ancestor in European imagery</text>
    <text x="20" y="122" fill="#E07A3F">Romania · nai</text>
    <text x="20" y="142" fill="#6E6A64">about twenty tubes, among the widest forms; common in Eastern European music</text>
    <text x="20" y="182" fill="#9C7A3C">China · paixiao</text>
    <text x="20" y="202" fill="#6E6A64">bamboo, a 竹 instrument in the eight categories; documented since pre-Qin times</text>
    <text x="20" y="242" fill="#A9A49B">Andes · siku / zampoña</text>
    <text x="20" y="262" fill="#6E6A64">often two rows of six to eight; two players alternate for a full scale</text>
    <text x="20" y="302" fill="#6E6A64">Africa and Oceania · bamboo panpipes</text>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M420,56 L494,56"/><path d="M420,116 L494,116"/>
    <path d="M420,176 L494,176"/><path d="M420,236 L494,236"/>
    <path d="M420,296 L494,296"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="500" y="60">single row, straight</text>
    <text x="500" y="120">single row, straight</text>
    <text x="500" y="180">two-winged</text>
    <text x="500" y="240">arched pair</text>
    <text x="500" y="300">stepped</text>
  </g>
</svg>
```

**It is the classic case of independent invention**: the panpipes of ancient Greece, China, the Andes and
Africa share **no common source**. Different peoples each arrived at the simplest possible solution —
"want more notes? line up more tubes."

That has made it a favourite example in ethnomusicology: **similar form does not imply transmission; it can
simply be the inevitable answer to the same physical constraint.**

## History

| Period | State |
|---|---|
| Prehistory–antiquity | multi-tube wind instruments of bamboo, wood, bone and clay appear worldwide; the Greek syrinx is the earliest well documented in text and image |
| Pre-Qin China | the **paixiao** is already recorded; bamboo, used in court and ritual music |
| Europe | used as a folk instrument through the Middle Ages and Renaissance, and shown in painting; fades from art music after the Baroque |
| 19th–20th c. | the Romanian **nai** is developed into a fully chromatic instrument; common in Eastern European and Romani bands |
| 20th c. | the Andean siku / zampoña spreads worldwide with South American folk music |
| Late 20th c. onward | widely used in folk, new-age and film music |

## Common misconceptions

- **"A pan flute is a toy or a folk curio."** It has a full scale and a systematic technique; the Romanian
  nai plays highly complex classical and folk repertoire.
- **"It is the same as an ocarina."** Both are called "closed", but of different things: the ocarina closes
  a **cavity** (pitch by volume), the pan flute closes **tubes** (pitch by length).
- **"All panpipes descend from one origin."** It is a textbook case of **independent invention** — similar
  forms, no common source, the same solution forced by the same physics.
- **"A pan flute sounds bright."** A closed tube has only odd harmonics, so it is inherently **dark and
  airy**; brightness needs an open tube (flute, recorder).
- **"The Chinese paixiao came from abroad."** China's paixiao is an **independently developed bamboo
  instrument**, classed under 竹 in the eight categories and documented since pre-Qin times — a parallel
  tradition to the Greek syrinx.

## Next

That completes **all 18 entries of the Western woodwind group (I2)**.

This batch leaves behind more than entries: one thread runs through the whole group — **the three acoustic
layers of woodwinds**. The **drive** (edge-tone / single reed / double reed) sets the character and
stability of the colour; the **bore** (cylindrical / conical) decides whether registers split; being **open
or closed** decides harmonic completeness and therefore brightness. Three layers, each handling its own
stretch — **and every woodwind can be located in the coordinates they form.**

The woodwind group now hands over: the next section is **brass**, built on an entirely new principle —
**vibrating lips**, rather than a cut jet or a beating reed.
:::


