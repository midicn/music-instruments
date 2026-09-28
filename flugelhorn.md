---
id: flugelhorn
site: inst
cat: I3
title: 富鲁格号
title_en: Flugelhorn
summary: 圆锥度与号嘴深度都推到极端的小号族成员，音色最柔最暗
summary_en: The trumpet family's softest member — the extreme of conical bore and deep cup
level: standard
tags: [乐器, 铜管, 西洋, 爵士]
tags_en: [instrument, brass, western, jazz]
alias: [富鲁格号, flugelhorn, 弗吕格号, 柔音号, 降B调富鲁格号]
order: 44
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:trumpet]]"
  - "[[instrument:cornet]]"
  - "[[instrument:french-horn]]"
  - "[[instrument:tuba]]"
instances:
  - pdmx-001449 | Sound the trumpet（普赛尔）—— 号角式语汇，对照富鲁格号最不擅长的方向
  - pdmx-002313 | 海顿 降 E 大调小号协奏曲 Hob.VIIe:1 —— **小号**演奏；同一族同一套指法，可对照音色差多远
  - mutopia-001624 | 为两支 cornetto 与三支 sackbut 而作的奏鸣曲 —— 文艺复兴的铜管组合，与本族隔了三百年
sources:
  - 结构依通行制琴资料：管长与小号相同（约 1.48 米），但**管身圆锥度是本族最大**，号嘴杯最深（常为漏斗型过渡）；三活塞阀
  - 「降 B 调富鲁格号是移调乐器，记谱比实音高大二度；音域与小号相同」依通行配器资料
  - 「富鲁格号的圆锥度大于短号，号嘴更深，因此音色最柔最暗」依管乐器声学
  - 「在爵士里是常用的柔音色彩，在管乐团与铜管重奏里承担柔声部」依通行配器惯例
  - ⚠️ 库内没有标题可确认为富鲁格号的曲目 —— 本条给出的是**同族小号曲目**作对照，音色由试听件负责
updated: 2026-09-26
---

::: zh
富鲁格号是[[instrument:trumpet|小号]]族里最"柔"的一支：
它把小号族的两个参数 —— **圆锥度**与**号嘴深度** —— 同时推到了极端。

于是它得到了本族最暗、最柔、最接近[[instrument:french-horn|圆号]]与**人声**的音色。
它也是"管形与号嘴决定音色"这条规律在铜管里最彻底的例证。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· **唇鸣**（lip-vibrated） |
| **次级类型** | 深杯/漏斗过渡号嘴 · **三活塞阀** · **圆锥度本族最大** · **降 B 调移调乐器** |
| **所属族** | 西洋 · 铜管（小号族 · 柔音支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，富鲁格号不在其中 |

> ⚠️ **一个概念上的要点**：到这里可以看清一件事 ——
> **小号族的"三兄弟"不是三件不同的乐器，而是一条连续谱上的三个采样点。**
> 三者**管长一样、指法一样、音域一样**，只在两个参数上取值不同：
> **管身圆锥度**（小 → 大）与**号嘴深度**（浅 → 深）。
> 两个参数朝同一个方向走，就得到"亮 → 圆 → 柔暗"的三档。
> **这是全站最干净的一组"控制变量"对照。**

## 两个参数，一条连续谱

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="以圆锥度和号嘴深度为两轴的铜管分布图：小号、短号、富鲁格号、圆号、长号与大号各自的位置">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">铜管的两个参数：圆锥度 × 号嘴深度</text>
  </g>
  <path d="M120,270 L600,270" stroke="#343439" stroke-width="1.4"/>
  <path d="M120,270 L120,70" stroke="#343439" stroke-width="1.4"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="124" y="288">圆柱为主</text>
    <text x="560" y="288">圆锥为主</text>
    <text x="112" y="62" text-anchor="end">号嘴深</text>
    <text x="112" y="278" text-anchor="end">号嘴浅</text>
  </g>
  <g stroke="#242427" stroke-width="1" stroke-dasharray="3 3">
    <path d="M120,170 L600,170"/><path d="M360,70 L360,270"/>
  </g>
  <circle cx="200" cy="228" r="7" fill="#5B7FA8"/>
  <text x="212" y="232" font-size="10.5" fill="#5B7FA8">小号</text>
  <circle cx="205" cy="216" r="6" fill="#5B7FA8" opacity=".7"/>
  <text x="217" y="212" font-size="10.5" fill="#5B7FA8">长号</text>
  <circle cx="320" cy="196" r="7" fill="#9C7A3C"/>
  <text x="332" y="200" font-size="10.5" fill="#9C7A3C">短号</text>
  <circle cx="430" cy="150" r="8" fill="#E07A3F"/>
  <text x="442" y="154" font-size="10.5" fill="#E07A3F">富鲁格号</text>
  <circle cx="510" cy="112" r="7" fill="#A9A49B"/>
  <text x="522" y="116" font-size="10.5" fill="#A9A49B">圆号</text>
  <circle cx="560" cy="96" r="9" fill="#6E6A64"/>
  <text x="548" y="82" font-size="10.5" fill="#6E6A64">大号</text>
  <text x="20" y="312" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">两个参数朝同一个方向走，音色就朝同一个方向变 —— 从"亮而尖"到"厚而暗"。</text>
  <text x="20" y="332" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">富鲁格号位于小号族的最软一端；再往右上方去，就是圆号与大号的地盘。</text>
</svg>
```

**这张图把铜管的音色差异整理成了两个可测量的参数**：

| 参数 | 影响 | 极端取值 |
|---|---|---|
| **管身圆锥度** | 高次泛音能否被激起 | 圆柱（亮）↔ 圆锥（柔暗） |
| **号嘴深度** | 嘴唇振动的高频成分 | 浅杯（亮）↔ 深杯/漏斗（柔暗） |

于是小号族的定位很清楚：**三兄弟都在"浅到中"与"圆柱到中锥"这一段**，
而富鲁格号是它们中间**最靠"柔"的那一格**。它没有越过圆号那条线 ——
**它仍然是"小号的指法与音域"，只是换了一件最柔的外衣。**

## 结构：本族最大的锥度与最深的号嘴

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="富鲁格号的结构：深杯号嘴、锥度更大的管身与略外张的喇叭口">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">富鲁格号 · 外形与主要部件（深号嘴 + 大锥度）</text>
  </g>
  <rect x="92" y="146" width="38" height="24" rx="8" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <path d="M130,148 L214,138 L214,178 L130,168 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <rect x="212" y="116" width="54" height="84" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="220" y="88" width="10" height="30" rx="4"/>
    <rect x="234" y="80" width="10" height="38" rx="4"/>
    <rect x="248" y="92" width="10" height="26" rx="4"/>
  </g>
  <path d="M266,136 L382,118 L382,198 L266,180 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M382,120 C446,110 512,116 556,158 C512,200 446,206 382,196 Z" fill="#17171A" stroke="#343439" stroke-width="1.5"/>
  <path d="M556,158 L574,132 L582,184 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <rect x="360" y="204" width="64" height="9" rx="4" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,140 L186,128"/><path d="M186,86 L186,100"/>
    <path d="M186,246 L186,212"/><path d="M480,108 L470,120"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="125" text-anchor="end" fill="#E07A3F">深杯号嘴（最深）</text>
    <text x="180" y="83" text-anchor="end">三活塞阀（与小号相同）</text>
    <text x="180" y="249" text-anchor="end">管身自吹口起持续外张</text>
    <text x="492" y="105">更宽的喇叭口</text>
  </g>
  <text x="20" y="278" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">管身从号嘴端就开始明显加粗 —— 这与小号"几乎等径"形成最直观的对比。</text>
</svg>
```

要点很短：**同样的管长与活塞，换了一副"更粗的管子 + 更深的杯子"**。
演奏者拿起它时指法不用改，但**气息要更松、更沉** —— 因为深号嘴需要更慢的气流与更放松的嘴唇。

## 音域

```range
{"range":"E3–B♭5","written":"F♯3–C6","caption":"富鲁格号的记谱音域与实音音域","caption_en":"The flugelhorn: notated range above, sounding range below","note":"⚠️ 降 B 调富鲁格号是移调乐器 —— 记谱比实音高大二度。谱面写 F♯3–C6，实际出声 E3–B♭5 —— 与小号、短号完全相同。三兄弟的差别只在音色。"}
```

- **实音 E3–B♭5**，与[[instrument:trumpet|小号]]、[[instrument:cornet|短号]]**完全一致**。
- **常用区 C4–C6**，但它的甜点其实在**中低音区**（C4–F4）——
  那里它的柔暗最动人，也是爵士独奏最常停留的地方。
- **高音区偏费力**。深号嘴让高频更难激起，所以它吹到 C6 以上比小号吃力。

## 音色与听辨

四条线索：

1. **柔、暗、圆、厚**。它是小号族里唯一听起来"不像铜管"的一支 ——
   常被形容为"接近圆号"或"接近人声"。
2. **起音柔和**。小号的音头是"钉"上去的，富鲁格号的音头更**包**、更圆。
3. **强奏也不容易刺耳**。同样的力度下它仍然保持圆润 —— 这是圆锥管的典型行为。
4. **音量与穿透力较弱**。它在安静段落里最好听；在大编制里容易被盖住，
   所以编制里常给它"独奏时刻"而不是持续声部。

```audiolab
{"type":"instrument","gm":"Trumpet","synth":"brass","phrase":["E3","B3","E4","G4","B♭4","E5"],"label":"富鲁格号的常用区：E3 到 E5","label_en":"The flugelhorn's working register — E3 up to E5","hint":"注意比短号更柔更暗的音色 —— 通用音色表里没有富鲁格号，这里借小号音色近似","hint_en":"Hear a softer, darker tone than a cornet's. General MIDI has no flugelhorn, so a trumpet sample stands in."}
```

> ⚠️ **关于试听**：通用音色表（General MIDI）里**没有富鲁格号**。
> 上面播放的是**小号**音色 —— 音区对了，但**最关键的柔暗完全听不到**。
> 想听真实音色，最直接的办法是找一段爵士富鲁格号独奏。

## 演奏技法

指法与[[instrument:trumpet|小号]]完全相同，需要重新适应的是**气息**：

- **气流要更慢、更松**。深号嘴需要更多"气量"但更少"气速"，用吹小号的方式吹它容易偏紧、偏亮。
- **唇部张力更低**。嘴唇不必绷得像小号那样紧，但**耐力消耗的方式不同** —— 低张力长时间吹同样累。
- **高音区更难**。深号嘴的代价就在这里。
- **弱音器可用**，但效果不如在小号上那么戏剧化。

## 家族与近亲

| 乐器 | 圆锥度 | 号嘴 | 音色 | 常用处 |
|---|---|---|---|---|
| [[instrument:trumpet\|小号]] | 最小 | 浅 | 亮、集中 | 管弦乐 / 爵士主角 |
| [[instrument:cornet\|短号]] | 中 | 中 | 圆、柔 | 管乐团 / 铜管乐队主力 |
| **富鲁格号** | **最大** | **最深** | 柔、暗、近人声 | 爵士色彩 / 柔声部 |
| [[instrument:french-horn\|圆号]] | 大 | **漏斗形** | 温润、远 | 管弦乐中音声部 |
| [[instrument:tuba\|大号]] | 大 | 很深 | 厚、暗 | 低音基础 |

**注意圆号那一行**：它的号嘴是**漏斗形**（funnel），与三兄弟的杯形不同 ——
这是另一个参数（号嘴形状而非深度），也是圆号音色迟迟无法被小号族替代的原因。

## 历史演变

| 时期 | 状态 |
|---|---|
| 19 世纪 | 在德国出现（名称意为"翼号"），与短号同源，但锥度更大；最初用于军乐队与管乐团 |
| 19 世纪末—20 世纪初 | 进入管乐团与铜管乐队，承担柔和的抒情声部 |
| 20 世纪中期 | **在爵士里找到新的位置**：作为与小号互补的柔音选择，成为独奏色彩 |
| 20 世纪后期至今 | 爵士、流行与电影配乐里的常见柔音；管乐团与铜管重奏中的固定色彩声部 |
| 与圆号的关系 | 常被描述为"小号与圆号之间的音色"，但**指法与音域仍属小号族** —— 它没有跨族 |

## 常见误解

- **"富鲁格号就是更柔的小号。"** 结构上确实如此，但两个参数（锥度与号嘴）**都推到了本族极端** ——
  所以它的音色差异是**质变**而不是"调低亮度"。
- **"它的音域比小号窄。"** **完全相同**（记谱 F♯3–C6 / 实音 E3–B♭5）。
- **"它与圆号是一类。"** 音色接近，但**号嘴形状不同**（杯形 vs 漏斗形），
  族属、指法、音域都不同 —— **音色相似不等于同类**。
- **"爵士里它只是小号的替代品。"** 它有独立的语汇：更接近人声的连奏与气声，
  许多独奏者是**专门**吹富鲁格号的。
- **"通用音色表里有它。"** General MIDI 里**没有**富鲁格号，只能借小号近似（本页试听件即如此）。

## 下一步

到这里，**小号族的三兄弟（[[instrument:trumpet|小号]] · [[instrument:cornet|短号]] · 富鲁格号）就齐了**。
它们合起来讲清了一件事：**在管长与指法完全相同的前提下，音色可以差多远。**

铜管这条线的下一个维度是"管长的改变方式"：
[[instrument:trombone|长号]]不用活塞，而用**滑管连续改变管长** ——
它是常规铜管里唯一能真正滑音的乐器。
再往后就是铜管组的低音：[[instrument:tuba|大号]]与它的前身
（[[instrument:ophicleide|奥菲克莱德号]] · [[instrument:serpent|蛇形号]]）。
:::

::: en
The flugelhorn is the softest member of the [[instrument:trumpet|trumpet]] family: it pushes both of the
family's parameters — **conicality** and **cup depth** — to the extreme at once.

That yields the family's darkest, softest tone, the closest to a [[instrument:french-horn|horn]] and to a
**human voice**. It is also the most thorough demonstration in brass that **bore and mouthpiece decide the
colour**.

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · **lip-vibrated** |
| **Sub-type** | Deep cup / funnel-edged mouthpiece · **three piston valves** · **widest taper in the family** · **B♭ transposing instrument** |
| **Family** | Western · Brass (trumpet family, soft branch) |
| **Bayin** | Not applicable — a Chinese system; the flugelhorn is outside it |

> ⚠️ **One conceptual point**: by now one thing is clear — **the trumpet's "three brothers" are not three
> instruments but three sample points on one continuum.** All three share **one length, one set of
> fingerings, one range**, and differ only in two parameters: **bore conicality** (small → large) and
> **cup depth** (shallow → deep). Both move the same way, giving three stops: **bright → round → soft-dark**.
> **The cleanest controlled comparison on this site.**

## Two parameters, one continuum

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Brass plotted against two axes, conicality and mouthpiece depth, showing where trumpet, cornet, flugelhorn, horn, trombone and tuba fall">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Two parameters of brass: conicality × mouthpiece depth</text>
  </g>
  <path d="M120,270 L600,270" stroke="#343439" stroke-width="1.4"/>
  <path d="M120,270 L120,70" stroke="#343439" stroke-width="1.4"/>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="124" y="288">mostly cylindrical</text>
    <text x="556" y="288">mostly conical</text>
    <text x="112" y="62" text-anchor="end">deep cup</text>
    <text x="112" y="278" text-anchor="end">shallow</text>
  </g>
  <g stroke="#242427" stroke-width="1" stroke-dasharray="3 3">
    <path d="M120,170 L600,170"/><path d="M360,70 L360,270"/>
  </g>
  <circle cx="200" cy="228" r="7" fill="#5B7FA8"/>
  <text x="212" y="232" font-size="10.5" fill="#5B7FA8">Trumpet</text>
  <circle cx="205" cy="216" r="6" fill="#5B7FA8" opacity=".7"/>
  <text x="217" y="212" font-size="10.5" fill="#5B7FA8">Trombone</text>
  <circle cx="320" cy="196" r="7" fill="#9C7A3C"/>
  <text x="332" y="200" font-size="10.5" fill="#9C7A3C">Cornet</text>
  <circle cx="430" cy="150" r="8" fill="#E07A3F"/>
  <text x="442" y="154" font-size="10.5" fill="#E07A3F">Flugelhorn</text>
  <circle cx="510" cy="112" r="7" fill="#A9A49B"/>
  <text x="522" y="116" font-size="10.5" fill="#A9A49B">Horn</text>
  <circle cx="560" cy="96" r="9" fill="#6E6A64"/>
  <text x="548" y="82" font-size="10.5" fill="#6E6A64">Tuba</text>
  <text x="20" y="312" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Both parameters move one way, so the colour moves one way — from bright and sharp to thick and dark.</text>
  <text x="20" y="332" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The flugelhorn is the soft end of the trumpet family; further up and right is horn and tuba country.</text>
</svg>
```

**This diagram reduces brass timbre to two measurable parameters**:

| Parameter | Affects | Extremes |
|---|---|---|
| **Bore conicality** | whether upper harmonics can be excited | cylindrical (bright) ↔ conical (soft, dark) |
| **Mouthpiece depth** | the high-frequency content of the lip vibration | shallow cup (bright) ↔ deep cup / funnel (soft, dark) |

So the trumpet family's place is clear: **all three brothers sit in the "shallow-to-medium" and
"cylindrical-to-medium-conical" region**, and the flugelhorn is its softest cell. It never crosses the horn's
line — **it keeps a trumpet's fingering and range, in its softest coat.**

## Structure: the family's widest taper and deepest cup

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Flugelhorn parts: a deep cup mouthpiece, a more strongly tapered body and a slightly flaring bell">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Flugelhorn — outer form and principal parts (deep cup, wide taper)</text>
  </g>
  <rect x="92" y="146" width="38" height="24" rx="8" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <path d="M130,148 L214,138 L214,178 L130,168 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <rect x="212" y="116" width="54" height="84" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="220" y="88" width="10" height="30" rx="4"/>
    <rect x="234" y="80" width="10" height="38" rx="4"/>
    <rect x="248" y="92" width="10" height="26" rx="4"/>
  </g>
  <path d="M266,136 L382,118 L382,198 L266,180 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M382,120 C446,110 512,116 556,158 C512,200 446,206 382,196 Z" fill="#17171A" stroke="#343439" stroke-width="1.5"/>
  <path d="M556,158 L574,132 L582,184 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <rect x="360" y="204" width="64" height="9" rx="4" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,140 L186,128"/><path d="M186,86 L186,100"/>
    <path d="M186,246 L186,212"/><path d="M480,108 L470,120"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="125" text-anchor="end" fill="#E07A3F">Deep cup (the deepest)</text>
    <text x="180" y="83" text-anchor="end">Three valves (as a trumpet)</text>
    <text x="180" y="249" text-anchor="end">Body flares from the mouthpiece</text>
    <text x="492" y="105">A wider bell</text>
  </g>
  <text x="20" y="278" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The body thickens visibly from the start — the plainest contrast with a trumpet's nearly even bore.</text>
</svg>
```

The point is short: **the same length and the same valves, with a fatter tube and a deeper cup.** A player
picks it up without changing fingerings, but **the air must be looser and slower** — a deep cup wants a
slower stream and a more relaxed lip.

## Range

```range
{"range":"E3–B♭5","written":"F♯3–C6","caption":"富鲁格号的记谱音域与实音音域","caption_en":"The flugelhorn: notated range above, sounding range below","note":"⚠️ 降 B 调富鲁格号是移调乐器 —— 记谱比实音高大二度。谱面写 F♯3–C6，实际出声 E3–B♭5 —— 与小号、短号完全相同。三兄弟的差别只在音色。"}
```

- **Sounding E3–B♭5**, **identical** to the [[instrument:trumpet|trumpet]] and [[instrument:cornet|cornet]].
- **The working register is C4–C6**, but its sweet spot is the **middle-low area (C4–F4)**, where its soft
  darkness is most moving and where jazz solos tend to linger.
- **The top is relatively laborious**: a deep cup makes high partials harder to excite, so above C6 it works
  harder than a trumpet.

## Timbre, and how to hear it

Four cues:

1. **Soft, dark, round, thick.** The only member of the family that does not sound "brassy" — often described
   as close to a horn or to a voice.
2. **A soft attack.** Where a trumpet's onset is nailed on, the flugelhorn's is rounder, more wrapped.
3. **It will not turn harsh** even at full power — typical conical-bore behaviour.
4. **Less volume and projection.** It sounds best in quiet passages and can be covered in a large ensemble,
   which is why scores give it **moments** rather than a continuous part.

```audiolab
{"type":"instrument","gm":"Trumpet","synth":"brass","phrase":["E3","B3","E4","G4","B♭4","E5"],"label":"富鲁格号的常用区：E3 到 E5","label_en":"The flugelhorn's working register — E3 up to E5","hint":"注意比短号更柔更暗的音色 —— 通用音色表里没有富鲁格号，这里借小号音色近似","hint_en":"Hear a softer, darker tone than a cornet's. General MIDI has no flugelhorn, so a trumpet sample stands in."}
```

> ⚠️ **On the audio**: the General MIDI set has **no flugelhorn**. A **trumpet** sample is playing above —
> the register is right, but **the softness, the whole point, is not there**. For the real sound, find a jazz
> flugelhorn solo.

## Playing techniques

The fingerings are identical to the [[instrument:trumpet|trumpet]]; what must be relearned is **the air**:

- **Slower, looser air.** A deep cup wants more **volume** of air but less **speed**; blown like a trumpet it
  turns tight and bright.
- **Less lip tension**, though the way endurance is spent differs — low tension for a long time tires you too.
- **The top register is harder.** That is the price of the deep cup.
- **Mutes work**, but less dramatically than on a trumpet.

## The family

| Instrument | Conical? | Mouthpiece | Timbre | Usual role |
|---|---|---|---|---|
| [[instrument:trumpet\|Trumpet]] | least | shallow | bright, focused | orchestra / jazz lead |
| [[instrument:cornet\|Cornet]] | medium | medium | round, soft | band lead |
| **Flugelhorn** | **most** | **deepest** | soft, dark, voice-like | jazz colour / soft voice |
| [[instrument:french-horn\|Horn]] | large | **funnel** | warm, distant | orchestral middle |
| [[instrument:tuba\|Tuba]] | large | very deep | thick, dark | the bass |

**Note the horn's row**: its mouthpiece is a **funnel**, not a cup — a third parameter (mouthpiece *shape*
rather than depth), and a reason the horn's colour can never quite be replaced from within the trumpet family.

## History

| Period | State |
|---|---|
| 19th c. | appears in Germany (the name means "wing horn"), related to the cornet but more conical; first used in military and wind bands |
| Late 19th–early 20th c. | enters wind and brass bands as a soft lyrical voice |
| Mid-20th c. | **finds a new home in jazz** as a soft alternative to the trumpet, and as a solo colour |
| Late 20th c. onward | a regular soft voice in jazz, pop and film scores, and a fixed colour in wind bands and brass ensembles |
| Relation to the horn | often described as "between trumpet and horn", but its **fingerings and range remain the trumpet family's** — it does not cross over |

## Common misconceptions

- **"A flugelhorn is just a softer trumpet."** Structurally yes, but both parameters (taper and cup) are
  pushed to the family's **extreme** — so the difference is qualitative, not just "less bright".
- **"Its range is smaller."** **Identical** (written F♯3–C6 / sounding E3–B♭5).
- **"It belongs with the horn."** The colour is close, but the **mouthpiece shape differs** (cup versus
  funnel), as do family, fingerings and range — **similar colour is not the same family.**
- **"In jazz it is only a substitute trumpet."** It has its own vocabulary of voice-like legato and breath;
  many soloists play the flugelhorn **specifically**.
- **"General MIDI has one."** It does not; a trumpet sample is the only stand-in (as on this page).

## Next

That completes **all three brothers** ([[instrument:trumpet|trumpet]] · [[instrument:cornet|cornet]] ·
flugelhorn). Together they show one thing clearly: **how far the colour can move while length and fingerings
stay identical.**

The next dimension of brass is **how the length changes**: the [[instrument:trombone|trombone]] uses no
valves but a **slide that changes the tube continuously** — the only common brass that can truly glide.
Beyond that lie the group's basses: the [[instrument:tuba|tuba]] and its forebears (the
[[instrument:ophicleide|ophicleide]] and the [[instrument:serpent|serpent]]).
:::
