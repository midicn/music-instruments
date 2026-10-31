---
id: xylophone
site: inst
cat: I4
title: 木琴
title_en: Xylophone
summary: 硬木条加共鸣管的体鸣乐器，音色干、脆、颗粒清楚
summary_en: Hard wooden bars over resonators — a dry, brittle, clearly grained idiophone
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [木琴, xylophone, 木条琴]
order: 62
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:marimba]]"
  - "[[instrument:glockenspiel]]"
  - "[[instrument:vibraphone]]"
  - "[[instrument:timpani]]"
instances:
  - pdmx-002767 | 赖希《Six Marimbas》—— **马林巴**演奏；与木琴同族，可对照"木条 + 共鸣管"的两种取值
  - pdmx-000746 | 霍尔斯特《行星组曲》Op.32 —— 配器里打击乐极丰富，木琴一族的用法可在此听到
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里木琴类乐器的用法
sources:
  - 结构依通行制琴资料：**硬木条**（传统为玫瑰木，现代亦用合成材料）按音高排列，下方各有**共鸣管**（金属或木制）增强低频与音量
  - 「木琴属**体鸣**的有音高乐器 —— 木条本身是振源」依 Hornbostel–Sachs 分类
  - 「音域约 F4–C8（视琴条数）」依通行乐器资料
  - 「木琴条更硬更薄、共鸣管更短，因此音色比马林巴更干更脆、余音更短」依乐器制作与声学通识
  - 「**木条越短 → 音越高**」依板振动原理（频率与长度的平方成反比）
updated: 2026-09-26
---

::: zh

槌子落下去，声音在一瞬之内就没了。木琴不是不会响，是响完立刻收，干净得像关上一只抽屉。

| 项 | 内容 |
|---|---|
| HS 分类 | 体鸣（Idiophone）· 敲击 · 有固定音高 |
| 八音 | 不适用 —— 周代八音按材料分器，木琴不在其中 |
| 规格 | 硬木条按音高排列，每根下挂一根金属共鸣管，音域约 F4–C8 |

## 木条下面那根管子

木条背面被挖出一道弧，行话叫拱。拱挖得深，条子就软，音低；挖得浅，条子就硬，音高。这条弧是调音留下的痕迹，也是木条能定音的原因：每一根都被单独削到某一个频率上，削完不再改。

木条自己振得很弱，几乎听不见。下面那根管子把振动接住、放大、送出去，管长按音高配，低音配长管。所以木条不是一堆木块，是一套算过长度的系统。

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="木琴的结构：按音高排列的硬木条、每根下方对应的共鸣管与支撑框架，以及硬头琴槌">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">木琴 · 结构（硬木条 + 下方共鸣管）</text>
  </g>
  <g stroke="#9C7A3C" stroke-width="1.4">
    <rect x="130" y="92" width="52" height="25" rx="3" fill="#0E0E10"/>
    <rect x="188" y="92" width="46" height="25" rx="3" fill="#0E0E10"/>
    <rect x="240" y="92" width="40" height="25" rx="3" fill="#0E0E10"/>
    <rect x="286" y="92" width="36" height="25" rx="3" fill="#0E0E10"/>
    <rect x="328" y="92" width="32" height="25" rx="3" fill="#0E0E10"/>
    <rect x="366" y="92" width="30" height="25" rx="3" fill="#0E0E10"/>
    <rect x="402" y="92" width="28" height="25" rx="3" fill="#0E0E10"/>
  </g>
  <g stroke="#343439" stroke-width="2.4">
    <path d="M120,72 L440,72"/><path d="M120,138 L440,138"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5" fill="#17171A">
    <rect x="146" y="146" width="20" height="76" rx="3"/>
    <rect x="200" y="146" width="20" height="76" rx="3"/>
    <rect x="248" y="146" width="20" height="76" rx="3"/>
    <rect x="292" y="146" width="20" height="76" rx="3"/>
    <rect x="332" y="146" width="20" height="76" rx="3"/>
    <rect x="370" y="146" width="20" height="76" rx="3"/>
    <rect x="406" y="146" width="20" height="76" rx="3"/>
  </g>
  <path d="M470,64 L508,86" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <circle cx="514" cy="90" r="10" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,60 L186,86"/><path d="M186,116 L186,104"/>
    <path d="M186,220 L186,190"/><path d="M486,60 L500,72"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="57" text-anchor="end">共鸣管（在木条下方）</text>
    <text x="180" y="119" text-anchor="end" fill="#9C7A3C">硬木条（越短音越高）</text>
    <text x="180" y="223" text-anchor="end" fill="#5B7FA8">共鸣管长度随音高变化</text>
    <text x="492" y="57">硬头琴槌</text>
  </g>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">木条左端略长于右端 —— 有些木琴把音孔开在两端，左右长短不同就是为了调整那个音的音准与泛音。</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">共鸣管的作用是"接住"木条的声音并把它放大 —— 管长按音高匹配。</text>
</svg>
```

## 同一种结构，三种取值

三件的机械结构几乎一样：一段被调过的琴条，加一根共鸣管。差别只有两处，材料与管长。

木琴用薄硬木条、短管，声音干、脆、尾巴短，每个音是一颗珠子。马林巴用厚软木条、长管，声音暖、厚，音与音能接上，所以它能承担和声。颤音琴换成金属条，管里装了会转的阀，余音最长，那点颤动的光泽就从阀上来。

**三件乐器，同一套图纸，三种取值。** 要点，选木琴；要线，选马林巴。

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="木琴、马林巴与颤音琴的对照：材料、共鸣管长度与余音长短决定三种音色">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同一种结构，三种取值</text>
  </g>
  <text x="110" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">木琴</text>
  <rect x="52" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#E07A3F" stroke-width="1.5"/>
  <rect x="76" y="112" width="68" height="52" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <text x="110" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">硬木条 · 短共鸣管</text>
  <text x="110" y="206" text-anchor="middle" font-size="10.5" fill="#E07A3F">干、脆、余音短</text>
  <text x="110" y="228" text-anchor="middle" font-size="10.5" fill="#6E6A64">每个音像一颗珠子</text>
  <text x="320" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">马林巴</text>
  <rect x="262" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.5"/>
  <rect x="286" y="112" width="68" height="86" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <text x="320" y="218" text-anchor="middle" font-size="10.5" fill="#A9A49B">软木条 · 长共鸣管</text>
  <text x="320" y="240" text-anchor="middle" font-size="10.5" fill="#9C7A3C">暖、厚、余音长</text>
  <text x="320" y="262" text-anchor="middle" font-size="10.5" fill="#6E6A64">能和声、能复调</text>
  <text x="530" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">颤音琴</text>
  <rect x="472" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <rect x="496" y="112" width="68" height="86" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <circle cx="530" cy="140" r="9" fill="none" stroke="#5B7FA8" stroke-width="2"/>
  <text x="530" y="218" text-anchor="middle" font-size="10.5" fill="#A9A49B">金属条 · 管内有旋转阀</text>
  <text x="530" y="240" text-anchor="middle" font-size="10.5" fill="#5B7FA8">金属感、余音极长</text>
  <text x="530" y="262" text-anchor="middle" font-size="10.5" fill="#6E6A64">"颤音"来自那个旋转阀</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三件的机械结构几乎一样（琴条 + 共鸣管），差别在「材料」与「共鸣管长度」 —— 音色差异全部由此而来。</text>
</svg>
```

## 音域

```range
{"range":"F4–C8","common":"C5–C7","caption":"木琴的音域","caption_en":"Xylophone range","note":"木琴属体鸣的有音高乐器。常见音域约 F4–C8（视琴条数）——比马林巴高一个八度左右。记谱即实音。"}
```

F4 到 C8，常用的那段是 C5 到 C7。它住在乐队的高处，一段快速跑动在木琴上是清清楚楚的颗粒，搬到弦乐上就糊成一片。圣桑写《骷髅之舞》，让骨架在墓地里跳，用的正是这种颗粒。

## 硬槌与四槌

```audiolab
{"type":"instrument","gm":"Xylophone","synth":"struck","phrase":["C5","E5","G5","C6","E6","G6"],"label":"木琴的常用区：C5 到 G6","label_en":"The xylophone's working register — C5 up to G6","hint":"注意音头硬、余音短 —— 每个音像一颗独立的珠子","hint_en":"Hear the hard attack and short tail — each note is a separate bead."}
```

音色有一半在槌子上。硬橡胶、硬木、塑料，敲出来发脆；换成软槌，声音立刻圆，也不再像木琴。四槌技术是现代曲目的常规写法，每只手两支，能同时给出和声与复调。

它唱不起来。余音太短，连奏几乎做不到，所以它负责标点，不负责句子。马林巴能拉出一条旋律线，木琴只能把它切成一颗一颗。

下次听见一串跑得极快、每个音都清楚的木声，多半就是它。

:::

::: en

The mallet lands and the note is gone almost at once. A xylophone does not fail to ring; it rings and shuts, clean as a drawer closing.

| Item | Value |
|---|---|
| HS class | Idiophone · struck · pitched |
| Bayin | Not applicable — the Zhou system sorts by material |
| Size | Hard bars laid out by pitch, one metal resonator under each, range about F4–C8 |

## The tube under the bar

The underside of each bar is carved into an arch. Cut deep and the bar goes soft and low; cut shallow and it stiffens and rises. That arch is the mark of tuning: every bar was shaved to one frequency, then left alone.

A bar on its own barely moves and can hardly be heard. The tube beneath catches the vibration, amplifies it and sends it out, its length matched to the pitch. The instrument is not a pile of wood but a system of calculated lengths.

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Xylophone structure: hard wooden bars arranged by pitch, a resonator under each bar, the frame, and hard-headed mallets">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Xylophone — structure (hard bars over resonators)</text>
  </g>
  <g stroke="#9C7A3C" stroke-width="1.4">
    <rect x="130" y="92" width="52" height="25" rx="3" fill="#0E0E10"/>
    <rect x="188" y="92" width="46" height="25" rx="3" fill="#0E0E10"/>
    <rect x="240" y="92" width="40" height="25" rx="3" fill="#0E0E10"/>
    <rect x="286" y="92" width="36" height="25" rx="3" fill="#0E0E10"/>
    <rect x="328" y="92" width="32" height="25" rx="3" fill="#0E0E10"/>
    <rect x="366" y="92" width="30" height="25" rx="3" fill="#0E0E10"/>
    <rect x="402" y="92" width="28" height="25" rx="3" fill="#0E0E10"/>
  </g>
  <g stroke="#343439" stroke-width="2.4">
    <path d="M120,72 L440,72"/><path d="M120,138 L440,138"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5" fill="#17171A">
    <rect x="146" y="146" width="20" height="76" rx="3"/>
    <rect x="200" y="146" width="20" height="76" rx="3"/>
    <rect x="248" y="146" width="20" height="76" rx="3"/>
    <rect x="292" y="146" width="20" height="76" rx="3"/>
    <rect x="332" y="146" width="20" height="76" rx="3"/>
    <rect x="370" y="146" width="20" height="76" rx="3"/>
    <rect x="406" y="146" width="20" height="76" rx="3"/>
  </g>
  <path d="M470,64 L508,86" stroke="#9C7A3C" stroke-width="6" stroke-linecap="round"/>
  <circle cx="514" cy="90" r="10" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,60 L186,86"/><path d="M186,116 L186,104"/>
    <path d="M186,220 L186,190"/><path d="M486,60 L500,72"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="57" text-anchor="end">Resonator (below the bar)</text>
    <text x="180" y="119" text-anchor="end" fill="#9C7A3C">Hard bar (shorter = higher)</text>
    <text x="180" y="223" text-anchor="end" fill="#5B7FA8">Resonator length follows pitch</text>
    <text x="492" y="57">Hard-headed mallet</text>
  </g>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">On many instruments the bar is longer on one side than the other — that asymmetry is part of its tuning.</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The resonator catches the bar's sound and radiates it; its length is matched to the pitch.</text>
</svg>
```

## One structure, three settings

The [[instrument:marimba|marimba]] and the [[instrument:vibraphone|vibraphone]] share almost the same mechanics: a bar and a resonator. Only two things change, the material and the length of the tube.

The xylophone uses thin hard bars and short tubes: dry, brittle, short-tailed, every note a bead. The marimba uses thick softer bars and long tubes: warm, full, notes that join, which is why it can carry harmony. The vibraphone swaps in metal bars and puts rotating vanes in the tubes, and the shimmer comes from those vanes.

**One drawing, three settings.** Points: xylophone. Lines: marimba.

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Xylophone, marimba and vibraphone compared: material, resonator length and tail length produce three colours">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One structure, three settings</text>
  </g>
  <text x="110" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">Xylophone</text>
  <rect x="52" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#E07A3F" stroke-width="1.5"/>
  <rect x="76" y="112" width="68" height="52" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <text x="110" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">hard bars · short resonators</text>
  <text x="110" y="206" text-anchor="middle" font-size="10.5" fill="#E07A3F">dry, brittle, short tail</text>
  <text x="110" y="228" text-anchor="middle" font-size="10.5" fill="#6E6A64">each note a separate bead</text>
  <text x="320" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">Marimba</text>
  <rect x="262" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.5"/>
  <rect x="286" y="112" width="68" height="86" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <text x="320" y="218" text-anchor="middle" font-size="10.5" fill="#A9A49B">softer bars · long resonators</text>
  <text x="320" y="240" text-anchor="middle" font-size="10.5" fill="#9C7A3C">warm, thick, long tail</text>
  <text x="320" y="262" text-anchor="middle" font-size="10.5" fill="#6E6A64">can carry harmony and polyphony</text>
  <text x="530" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Vibraphone</text>
  <rect x="472" y="88" width="116" height="16" rx="3" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <rect x="496" y="112" width="68" height="86" rx="3" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <circle cx="530" cy="140" r="9" fill="none" stroke="#5B7FA8" stroke-width="2"/>
  <text x="530" y="218" text-anchor="middle" font-size="10.5" fill="#A9A49B">metal bars · vanes in the tubes</text>
  <text x="530" y="240" text-anchor="middle" font-size="10.5" fill="#5B7FA8">metallic, very long tail</text>
  <text x="530" y="262" text-anchor="middle" font-size="10.5" fill="#6E6A64">the "vibrato" comes from those vanes</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Nearly identical mechanics (bars plus resonators); the differences are material and resonator length.</text>
</svg>
```

## Range

```range
{"range":"F4–C8","common":"C5–C7","caption":"木琴的音域","caption_en":"Xylophone range","note":"木琴属体鸣的有音高乐器。常见音域约 F4–C8（视琴条数）——比马林巴高一个八度左右。记谱即实音。"}
```

F4 to C8, with C5 to C7 doing the work. It lives high. A fast run is a row of clear grains on the xylophone and a smear on strings, which is exactly what Saint-Saëns wanted when he set skeletons dancing in the Danse macabre.

## Hard mallets, four mallets

```audiolab
{"type":"instrument","gm":"Xylophone","synth":"struck","phrase":["C5","E5","G5","C6","E6","G6"],"label":"木琴的常用区：C5 到 G6","label_en":"The xylophone's working register — C5 up to G6","hint":"注意音头硬、余音短 —— 每个音像一颗独立的珠子","hint_en":"Hear the hard attack and short tail — each note is a separate bead."}
```

Half the colour is in the mallet. Hard rubber, wood or plastic gives the brittle edge; a soft head rounds it off and stops sounding like a xylophone. Four mallets, two to a hand, are now standard in modern writing, giving chords and counterpoint at once.

It cannot sing. The tail is too short for legato, so it punctuates rather than phrases; the marimba draws the line, the xylophone cuts it into grains.

Next time a passage runs fast with every note distinct and wooden, it is probably this one.
:::
