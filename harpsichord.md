---
id: harpsichord
site: inst
cat: I5
title: 大键琴
title_en: Harpsichord
summary: 键盘拨弦的弦鸣乐器，音量不随触键变化，靠音栓与多排弦改变音色
summary_en: The keyboard-plucked chordophone — plucking fixes the volume, so colour comes from stops and string sets
level: standard
tags: [乐器, 键盘, 西洋, 早期乐器]
tags_en: [instrument, keyboard, western, early]
alias: [大键琴, harpsichord, 羽管键琴, 拨弦键琴, clavicembalo]
order: 80
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:piano]]"
  - "[[instrument:clavichord]]"
  - "[[instrument:organ]]"
  - "[[instrument:theorbo]]"
instances:
  - pdmx-001939 | 六首圆号四重奏 Op.35 —— 巴洛克与古典早期的重奏语言，可对照大键琴所处的时代
  - pdmx-002820 | 为三支小号与定音鼓而作的协奏曲 TWV 54:D4 —— 巴洛克协奏曲的写法，通奏低音正是大键琴的岗位
  - pdmx-001882 | Carol of the Bells —— 标题指向钟铃一类音色的曲目，可作音色联想
sources:
  - 结构依通行制琴资料：**键盘**经拨子（传统为**羽管**，现代多为塑料）拨弦；每音可有多根弦与多组拨子；**音栓（stops）**控制哪一组弦发声
  - 「大键琴属**弦鸣**乐器（键盘拨弦）」依 Hornbostel–Sachs 分类
  - 「常见音域约 F1–F6，视乐器形制而定」依通行乐器资料
  - 「拨弦的力度由机械固定，按键快慢不影响音量 —— 因此大键琴不能靠触键控制力度」依乐器声学
updated: 2026-09-26
---

::: zh
大键琴是[[instrument:piano|钢琴]]的"前任"，也是**巴洛克时期键盘音乐的主角**。
它与钢琴共用一件东西：**键盘**。但它做另一件事：**拨弦**。

而"拨弦"这一点，决定了它的全部音乐语言。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— **振动的是弦** |
| **次级类型** | 键盘经拨子拨弦 · 可有多根弦与多组拨子 · **音栓**控制发声组合 |
| **所属族** | 西洋 · 键盘（拨弦支系）· 同时是**早期乐器** |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，大键琴不在其中 |

> ⚠️ **一个概念上的要点**：**"不能控制力度"不是缺陷，而是一种音乐语言的起点。**
> 钢琴的强弱来自击弦速度；大键琴的拨子由机械弹起，**力度是固定的**。
> 于是巴洛克作曲家不去写"渐强"，而是写：
> - **音型与装饰**（用密度而不是音量做层次）
> - **音区的对比**（高低音区的音色差异）
> - **音栓的切换**（用音色变化代替音量变化）
>
> **一件乐器"做不到什么"，会塑造出整套写作惯例** —— 大键琴是这条规律最清楚的例子。

## 结构：拨子、弦与音栓

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="大键琴的结构：键盘经拨子拨弦、可有多根弦与多组拨子、音栓控制哪一组弦发声">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">大键琴 · 结构（拨子拨弦 + 多组弦 + 音栓）</text>
  </g>
  <rect x="70" y="72" width="240" height="34" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M82,72 L82,106"/><path d="M100,72 L100,106"/><path d="M118,72 L118,106"/>
    <path d="M136,72 L136,106"/><path d="M154,72 L154,106"/><path d="M172,72 L172,106"/>
    <path d="M190,72 L190,106"/><path d="M208,72 L208,106"/><path d="M226,72 L226,106"/>
    <path d="M244,72 L244,106"/><path d="M262,72 L262,106"/><path d="M280,72 L280,106"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="3">
    <path d="M118,124 L118,152"/><path d="M172,124 L172,152"/><path d="M226,124 L226,152"/>
  </g>
  <path d="M100,158 L340,158" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M100,172 L340,172" stroke="#E07A3F" stroke-width="2" stroke-dasharray="5 3"/>
  <path d="M100,186 L340,186" stroke="#9C7A3C" stroke-width="2.4"/>
  <g fill="#9C7A3C">
    <rect x="114" y="146" width="7" height="14" rx="3"/>
    <rect x="168" y="146" width="7" height="14" rx="3"/>
    <rect x="222" y="146" width="7" height="14" rx="3"/>
  </g>
  <rect x="70" y="216" width="240" height="26" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,56 L186,66"/><path d="M186,118 L186,112"/>
    <path d="M186,200 L186,210"/><path d="M186,258 L186,246"/>
    <path d="M486,120 L356,140"/><path d="M486,200 L480,150"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">键盘（操作界面）</text>
    <text x="180" y="121" text-anchor="end" fill="#9C7A3C">拨子（传统为羽管）</text>
    <text x="180" y="203" text-anchor="end" fill="#5B7FA8">同一音的多根弦（音色不同）</text>
    <text x="180" y="261" text-anchor="end" fill="#E07A3F">音栓（选择哪一组弦发声）</text>
    <text x="492" y="117">拨子由机械弹起</text>
    <text x="492" y="203">音栓切换 = 音色切换</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">拨子由机械弹起，与按键快慢无关 —— 所以音量是固定的：这既是它的限制，也是它均匀音色的来源。</text>
  <text x="20" y="314" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">多个音栓对应不同的弦组（常以 8′ 与 4′ 标记指音高八度），拉出不同音栓就得到不同音量与音色。</text>
</svg>
```

三处要点：

1. **拨子由机械弹起**。按键只是"释放"这个机械动作 ——
   所以**按键的快慢不改变拨弦的力度**。这是它不能控制力度的物理原因。
2. **同一音可有多根弦**，对应不同音色（有时还对应不同八度）。
3. **音栓（stops）切换弦组**。拉出不同的栓就得到不同的音量与音色组合 ——
   这是它用**音色变化**替代**音量变化**的办法。

## 音栓：它如何弥补"没有力度"

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="大键琴用音栓与音区对比替代力度变化：不同音栓对应不同弦组，得到音量与音色的对比">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">没有力度，就用音色与音区做层次</text>
  </g>
  <rect x="60" y="60" width="150" height="70" rx="5" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="135" y="84" text-anchor="middle" font-size="11" fill="#5B7FA8">只开一组弦</text>
  <text x="135" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">单一音色、较薄</text>
  <rect x="230" y="60" width="150" height="70" rx="5" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <text x="305" y="84" text-anchor="middle" font-size="11" fill="#9C7A3C">开两组弦</text>
  <text x="305" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">更厚、更响</text>
  <rect x="400" y="60" width="180" height="70" rx="5" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="490" y="84" text-anchor="middle" font-size="11" fill="#E07A3F">加上高八度弦组</text>
  <text x="490" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">明亮、穿透</text>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M212,95 L228,95"/><path d="M382,95 L398,95"/>
  </g>
  <text x="20" y="170" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">演奏者（或助手）在乐曲中间拉动音栓，就得到了"突然变响/变亮"的效果 ——</text>
  <text x="20" y="192" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">这不是渐强，而是「音色的切换」。巴洛克音乐里那种"段落之间的对比"，很多就来自这里。</text>
  <text x="20" y="222" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">另一个层次来源是音区：大键琴的高音区明亮、低音区厚实，作曲家会利用这个差异做呼应。</text>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">所以"不能控制力度"这件事，反而塑造了巴洛克键盘音乐的语言：密度、装饰、音区、音栓。</text>
</svg>
```

**这条"限制塑造语言"值得记住**：
当代听者常觉得大键琴"没有表情"，但巴洛克的表达方式本来就不在力度上 ——
它在**音型的密度、装饰音的多少、音区的对比、音栓的切换**上。

## 音域

```range
{"range":"F1–F6","common":"C2–C6","caption":"大键琴的音域（以常见形制为例）","caption_en":"Harpsichord range (a typical instrument)","note":"大键琴属弦鸣乐器（键盘拨弦）。常见音域约 F1–F6，视乐器形制而定 —— 比钢琴窄，不同乐器之间差别也较大。"}
```

- **约 F1–F6**，视乐器而定 —— 比[[instrument:piano|钢琴]]窄。
- **常用区 C2–C6**：巴洛克键盘作品的绝大多数都在这里。
- **不同形制差别大**。大键琴没有一个统一的"标准音域"，
  这与钢琴（88 键统一）形成对照。

## 音色与听辨

四条线索：

1. **清亮、颗粒分明、音头明确**。拨弦带来清晰的起音，与钢琴的击弦不同 ——
   大键琴的每个音都是"弹"出来的。
2. **余音短**。拨子离开弦后振动很快衰减，所以**快速音型不会糊** ——
   这是巴洛克密集音型能成立的原因。
3. **音量固定**。无论怎么按键都一样响 —— 这是它最被误解的一点。
4. **不同音栓的音色差异明显**。8′ 与 4′ 的组合带来截然不同的质感。

```audiolab
{"type":"instrument","gm":"Harpsichord","synth":"plucked","phrase":["C3","E3","G3","C4","E4","G4"],"label":"大键琴的常用区：C3 到 G4","label_en":"The harpsichord's working register — C3 up to G4","hint":"注意每个音都是「弹」出来的、音头清晰 —— 而且无论按键多用力，音量都一样","hint_en":"Every note is plucked with a clear attack — and no matter how hard you press, the volume stays the same."}
```

## 演奏技法

- **触键不影响力度**，但影响**音色细节**（按键的速度与深度会稍微影响拨子的动作）。
- **装饰音是它的核心技法**。因为不能靠力度做表情，**装饰音（颤音、波音、倚音）承担了大量表现任务**。
- **音栓切换**：在乐句之间或段落之间改变音色。
- **多排键盘**：较大的乐器有两排键盘，可分别对应不同音栓组合，
  也可以让两手在不同键盘上做出音色对比。
- **不平均律与调律**：巴洛克时期的调律方式与今天不同，这直接影响和声的色彩。

## 家族与近亲

| 乐器 | 触发 | 力度可控 | 音量 | 余音 | 音域 |
|---|---|---|---|---|---|
| [[instrument:piano\|钢琴]] | 击弦 | **可** | 大 | 长 | A0–C8 |
| **大键琴** | **拨弦** | **不可** | 中 | 短 | F1–F6 |
| [[instrument:clavichord\|击弦古钢琴]] | 击弦（铜片） | 可 | **极小** | 极短 | C2–C6 |
| [[instrument:organ\|管风琴]] | 气流 | 不可 | 极大 | 可持续 | C2–C7 |

**大键琴与管风琴都是"不能靠触键控制力度"的键盘乐器** ——
所以它们的表现手段都在别处：**一个靠音栓与装饰，一个靠音栓与声部**。

## 历史演变

| 时期 | 状态 |
|---|---|
| 14—15 世纪 | 拨弦键盘乐器在欧洲出现，形制逐步发展 |
| 16—17 世纪 | 在意大利、佛兰德斯、法国、英国形成各自的制作传统；音域与音栓系统逐步扩展 |
| **18 世纪** | **巴洛克时期的主角**：独奏、通奏低音、协奏曲都用它；大量作品专为它而写 |
| 18 世纪末 | 被[[instrument:piano\|钢琴]]取代（后者能控制力度，契合新音乐语言） |
| 19 世纪 | 几乎退出使用 |
| 20 世纪 | **古乐运动复兴**；仿古乐器与现代制作并行 |
| 20 世纪后期至今 | 巴洛克作品的标准乐器；也有当代作曲家为它写新作 |

**它退场的原因很具体**：18 世纪末的音乐开始要求**渐强渐弱**，
而这是它做不到的。**一次审美需求的变化，就足以让一件主导乐器退场。**

## 常见误解

- **"大键琴是"老式钢琴"。"** 触发方式完全不同（拨弦 vs 击弦），
  因此**力度是否可控**这一点根本不同 —— 两者是两种语言。
- **"它的声音小是因为做得不好。"** 音量小与固定是**拨弦机械的必然结果**，
  不是工艺问题；相反，好的大键琴的音色层次很丰富。
- **"它没有表情。"** 表情在**装饰、音型密度、音区与音栓**上，
  而不是在力度上 —— 巴洛克的表达方式本来就不在力度。
- **"它只能弹巴洛克音乐。"** 20 世纪以来有大量当代作品为它写作，
  也用到了音栓切换等它独有的手段。
- **"它和大键琴、击弦古钢琴是一回事。"** 三者都是"早期键盘"，
  但触发方式不同（拨弦 / 击弦），可控性与音量差别极大。

## 下一步

键盘组的下一站是[[instrument:clavichord|击弦古钢琴]] ——
它**能控制力度**（甚至能做颤音），但音量小到只能在室内使用。
再往后是[[instrument:organ|管风琴]]：键盘下的气鸣乐器。
:::

::: en
The harpsichord is the [[instrument:piano|piano]]'s predecessor and **the leading keyboard instrument of the
Baroque.** It shares one thing with the piano — **the keyboard** — and does another: it **plucks** the strings.

And that single fact of plucking determines its entire musical language.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — **the strings vibrate** |
| **Sub-type** | Keyboard drives a plectrum against the string · several strings and plectrum sets possible · **stops** select which sound |
| **Family** | Western · Keyboard (plucked branch) · also an **early instrument** |
| **Bayin** | Not applicable — a Chinese system; the harpsichord is outside it |

> ⚠️ **One conceptual point**: **"no dynamic control" is not a defect; it is the starting point of a musical
> language.**
> A piano's loudness comes from hammer speed; a harpsichord's plectrum is flipped by a mechanism, so **its
> dynamics are fixed.** Baroque composers therefore did not write crescendos. They wrote:
> - **figuration and ornament** (density in place of volume)
> - **registral contrast** (the colour difference between high and low)
> - **stop changes** (colour change in place of volume change)
>
> **What an instrument *cannot* do shapes an entire writing convention** — the harpsichord is the clearest
> example of that rule.

## Structure: plectrum, strings and stops

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Harpsichord structure: a keyboard driving plectra against strings, with several string sets and stops selecting which sound">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Harpsichord — structure (plectra, several string sets, stops)</text>
  </g>
  <rect x="70" y="72" width="240" height="34" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M82,72 L82,106"/><path d="M100,72 L100,106"/><path d="M118,72 L118,106"/>
    <path d="M136,72 L136,106"/><path d="M154,72 L154,106"/><path d="M172,72 L172,106"/>
    <path d="M190,72 L190,106"/><path d="M208,72 L208,106"/><path d="M226,72 L226,106"/>
    <path d="M244,72 L244,106"/><path d="M262,72 L262,106"/><path d="M280,72 L280,106"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="3">
    <path d="M118,124 L118,152"/><path d="M172,124 L172,152"/><path d="M226,124 L226,152"/>
  </g>
  <path d="M100,158 L340,158" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M100,172 L340,172" stroke="#E07A3F" stroke-width="2" stroke-dasharray="5 3"/>
  <path d="M100,186 L340,186" stroke="#9C7A3C" stroke-width="2.4"/>
  <g fill="#9C7A3C">
    <rect x="114" y="146" width="7" height="14" rx="3"/>
    <rect x="168" y="146" width="7" height="14" rx="3"/>
    <rect x="222" y="146" width="7" height="14" rx="3"/>
  </g>
  <rect x="70" y="216" width="240" height="26" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.4"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,56 L186,66"/><path d="M186,118 L186,112"/>
    <path d="M186,200 L186,210"/><path d="M186,258 L186,246"/>
    <path d="M486,120 L356,140"/><path d="M486,200 L480,150"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">Keyboard (the interface)</text>
    <text x="180" y="121" text-anchor="end" fill="#9C7A3C">Plectrum (quill traditionally)</text>
    <text x="180" y="203" text-anchor="end" fill="#5B7FA8">Several strings per note</text>
    <text x="180" y="261" text-anchor="end" fill="#E07A3F">Stops (which set sounds)</text>
    <text x="492" y="117">Plectrum is mechanical</text>
    <text x="492" y="203">Stops change the colour</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The plectrum is flipped mechanically, so key speed does not change the volume: a limit.</text>
  <text x="20" y="314" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Stops engage different string sets (often marked 8′ and 4′); each changes volume and colour.</text>
</svg>
```

Three points:

1. **The plectrum is flipped by a mechanism.** Pressing a key only releases that action — so **key speed does
   not change the force of the pluck.** The physical reason it cannot control dynamics.
2. **Several strings per note**, corresponding to different colours (sometimes different octaves).
3. **Stops select string sets.** Pulling different stops gives different combinations of volume and colour —
   its substitute for dynamic change.

## Stops: how it compensates for having no dynamics

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The harpsichord substitutes stop and register contrast for dynamic change: different stops engage different string sets">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Without dynamics, layers come from colour and register</text>
  </g>
  <rect x="60" y="60" width="150" height="70" rx="5" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="135" y="84" text-anchor="middle" font-size="11" fill="#5B7FA8">One string set</text>
  <text x="135" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">single colour, thinner</text>
  <rect x="230" y="60" width="150" height="70" rx="5" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <text x="305" y="84" text-anchor="middle" font-size="11" fill="#9C7A3C">Two string sets</text>
  <text x="305" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">thicker, louder</text>
  <rect x="400" y="60" width="180" height="70" rx="5" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="490" y="84" text-anchor="middle" font-size="11" fill="#E07A3F">Plus an octave set</text>
  <text x="490" y="108" text-anchor="middle" font-size="10.5" fill="#A9A49B">bright, penetrating</text>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M212,95 L228,95"/><path d="M382,95 L398,95"/>
  </g>
  <text x="20" y="170" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Pulling a stop mid-piece gives a sudden change of weight or brightness —</text>
  <text x="20" y="192" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">not a crescendo but a 「switch of colour」. Much Baroque sectional contrast comes from exactly this.</text>
  <text x="20" y="222" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The other source of layering is register: bright on top, full below.</text>
  <text x="20" y="252" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">So "no dynamic control" shaped Baroque keyboard language: density, ornament, register, stops.</text>
</svg>
```

**"Limitations shape the language" is worth remembering**: modern listeners often find the harpsichord
"expressionless", but Baroque expression was never in dynamics — it lives in **the density of figuration, the
amount of ornament, registral contrast and stop changes**.

## Range

```range
{"range":"F1–F6","common":"C2–C6","caption":"大键琴的音域（以常见形制为例）","caption_en":"Harpsichord range (a typical instrument)","note":"大键琴属弦鸣乐器（键盘拨弦）。常见音域约 F1–F6，视乐器形制而定 —— 比钢琴窄，不同乐器之间差别也较大。"}
```

- **About F1–F6**, depending on the instrument — narrower than a [[instrument:piano|piano]].
- **The working register is C2–C6**; the great majority of Baroque keyboard writing sits there.
- **Forms vary widely.** There is no single "standard range" for a harpsichord, unlike the piano's uniform 88
  keys.

## Timbre, and how to hear it

Four cues:

1. **Bright, clearly grained, with a definite attack.** Plucking gives a crisp onset, unlike the piano's
   strike — every note is *plucked*.
2. **A short tail.** Once the plectrum leaves, the vibration decays quickly, so **fast figuration never smears**
   — the reason the dense Baroque textures work.
3. **Fixed volume.** However hard you press, it sounds the same — its most misunderstood feature.
4. **Marked colour differences between stops**: 8′ and 4′ combinations give completely different textures.

```audiolab
{"type":"instrument","gm":"Harpsichord","synth":"plucked","phrase":["C3","E3","G3","C4","E4","G4"],"label":"大键琴的常用区：C3 到 G4","label_en":"The harpsichord's working register — C3 up to G4","hint":"注意每个音都是「弹」出来的、音头清晰 —— 而且无论按键多用力，音量都一样","hint_en":"Every note is plucked with a clear attack — and no matter how hard you press, the volume stays the same."}
```

## Playing techniques

- **Touch does not change dynamics**, though it slightly affects the colour (key speed and depth influence the
  plectrum's action).
- **Ornament is the core technique.** Because dynamics cannot shape expression, **ornaments (trills, mordents,
  appoggiaturas) carry much of the expressive load.**
- **Stop changes** between phrases or sections.
- **Multiple manuals**: larger instruments have two keyboards, assignable to different stop combinations and
  allowing the hands to contrast colours.
- **Temperament and tuning**: Baroque temperaments differ from today's, directly affecting harmonic colour.

## The family

| Instrument | Trigger | Dynamics | Volume | Tail | Range |
|---|---|---|---|---|---|
| [[instrument:piano\|Piano]] | struck | **yes** | large | long | A0–C8 |
| **Harpsichord** | **plucked** | **no** | medium | short | F1–F6 |
| [[instrument:clavichord\|Clavichord]] | struck (tangent) | yes | **tiny** | very short | C2–C6 |
| [[instrument:organ\|Organ]] | air | no | huge | sustained | C2–C7 |

**The harpsichord and the organ are both keyboard instruments whose touch cannot control dynamics** — so both
place their expression elsewhere: **one in stops and ornament, the other in stops and part-writing.**

## History

| Period | State |
|---|---|
| 14th–15th c. | plucked keyboard instruments appear in Europe and their forms develop |
| 16th–17th c. | distinct making traditions arise in Italy, Flanders, France and England; ranges and stop systems expand |
| **18th c.** | **the star of the Baroque**: solo, continuo and concerto all use it, with a large dedicated repertoire |
| Late 18th c. | replaced by the [[instrument:piano|piano]] (whose touch controls dynamics, matching the new language) |
| 19th c. | almost entirely out of use |
| 20th c. | **revived by the early-music movement**; copies and modern instruments coexist |
| Late 20th c. onward | the standard instrument for Baroque repertoire, with new works written for it |

**Its departure has a concrete cause**: music around 1800 began to demand **crescendo and diminuendo**, which
it cannot do. **A change in taste alone was enough to retire a dominant instrument.**

## Common misconceptions

- **"A harpsichord is an old piano."** The trigger is entirely different (plucked versus struck), so **whether
  dynamics are controllable** differs fundamentally — two different languages.
- **"It is quiet because it is badly made."** The small, fixed volume is a **necessary consequence of the
  plucking mechanism**, not a fault; a good harpsichord has rich colour.
- **"It has no expression."** Expression lives in **ornament, figuration density, register and stops**, not in
  dynamics — Baroque expression was never dynamic.
- **"It can only play Baroque music."** Since the 20th century much contemporary music has been written for it,
  including music exploiting its unique stop changes.
- **"Harpsichord, clavichord, spinet — all the same."** All are "early keyboards" but their triggers differ
  (plucked versus struck), with huge differences in control and volume.

## Next

The keyboard group's next stop is the [[instrument:clavichord|clavichord]] — which **can control dynamics** (and
even add vibrato) but is too quiet to be heard outside a room. Beyond it comes the
[[instrument:organ|organ]]: an aerophone under a keyboard.
:::
