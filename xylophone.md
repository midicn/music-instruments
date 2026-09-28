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
木琴是"木条一族"里最干脆的一件：**硬木条 + 下方的共鸣管**，
音色**干、脆、颗粒清楚** —— 每个音像一颗独立的珠子。

它与[[instrument:marimba|马林巴]]是同一族的近亲，但两者的取舍正好相反：
**木琴要"点"，马林巴要"线"。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **体鸣**（Idiophone）· **有音高** |
| **次级类型** | 硬木条按音高排列 · 每条约有一根共鸣管 · 用硬头槌击奏 |
| **所属族** | 西洋 · 打击（体鸣·木条族） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，木琴不在其中 |

> ⚠️ **一个概念上的要点**：**"有音高"的打击乐器与"无音高"的，差别在于振动体能不能给出稳定的音高。**
> 木琴的每一根**木条**经过修削（下方挖出弧形）之后，其振动频率就被固定下来了 ——
> 所以它能按乐谱奏出指定音高，属"有音高打击乐"。
> 而[[instrument:snare-drum|小鼓]]、[[instrument:cymbals|铙钹]]的振动体没有这种定音结构，
> 所以是"无音高"。**判据不是"能不能听出高低"，而是"能不能按要求奏出指定音高"。**

## 结构：木条与共鸣管

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

三处要点：

1. **共鸣管是"放大器"**。木条本身振动幅度很小、声音很轻，
   下方的共鸣管把它接住并辐射出去 —— 所以木琴不是"木条自己响"。
2. **木条越短音越高**。同族的马林巴、颤音琴都遵循这条，只是材料不同（木 / 金属）。
3. **硬头槌**。木琴用硬头（木、橡胶或塑料），这是它音色"脆"的直接原因之一 ——
   换软槌会立刻变成另一种音色。

## 木条一族：三件同构、三种音色

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

**这三件的对比是全站"同构不同音色"的又一例**（与[[instrument:trumpet|小号族三兄弟]]、长笛族三支同理）：

| 乐器 | 琴条材料 | 共鸣管 | 余音 | 音色 |
|---|---|---|---|---|
| **木琴** | 硬木（薄） | 短 | 短 | 干、脆、颗粒 |
| **马林巴** | 软木（厚） | **长** | 长 | 暖、厚、绵 |
| **颤音琴** | **金属** | 长 + 旋转阀 | **最长** | 金属感、闪烁 |

## 音域

```range
{"range":"F4–C8","common":"C5–C7","caption":"木琴的音域","caption_en":"Xylophone range","note":"木琴属体鸣的有音高乐器。常见音域约 F4–C8（视琴条数）——比马林巴高一个八度左右。记谱即实音。"}
```

- **约 F4–C8**，比[[instrument:marimba|马林巴]]高一个八度左右。
- **常用区 C5–C7**：它的"珠子感"在这一带最清楚。
- **它是"高音区的点缀乐器"**。管弦乐里用它来加亮、加"骨感"，
  或者用来表现骷髅、机械、怪异一类形象。

## 音色与听辨

四条线索：

1. **"骨感"**。音头硬、余音短 —— 听感像敲击干燥的木块，很有"物理感"。
2. **颗粒清晰**。快速音型不会糊，所以它能打很快的跑动。
3. **不易做连奏**。余音短意味着"唱"不起来，这是它与马林巴最大的用法差别。
4. **换槌就换音色**。硬槌 → 脆；软槌 → 圆。但仍比马林巴"干"。

```audiolab
{"type":"instrument","gm":"Xylophone","synth":"struck","phrase":["C5","E5","G5","C6","E6","G6"],"label":"木琴的常用区：C5 到 G6","label_en":"The xylophone's working register — C5 up to G6","hint":"注意音头硬、余音短 —— 每个音像一颗独立的珠子","hint_en":"Hear the hard attack and short tail — each note is a separate bead."}
```

## 演奏技法

- **双槌或四槌**。四槌（每手两槌）可奏和声与复调 —— 这是现代木琴类乐器的常规技术。
- **硬头槌**为默认；换软头会得到更圆的音色，但会失去它的辨识度。
- **快速音型与滚奏**都是它的强项。
- **止音**：余音短，所以不像马林巴那样需要频繁止音。

## 家族与近亲

| 乐器 | 材料 | 音高 | 余音 | 音色 |
|---|---|---|---|---|
| **木琴** | 硬木 | **有** | 短 | 干、脆 |
| [[instrument:marimba\|马林巴]] | 软木 | **有** | 长 | 暖、厚 |
| [[instrument:vibraphone\|颤音琴]] | 金属 | **有** | 最长 | 金属、闪烁 |
| [[instrument:glockenspiel\|钟琴]] | **钢** | **有** | 长 | 极亮、通透 |
| [[instrument:tubular-bells\|管钟]] | 金属管 | **有** | 极长 | 钟声 |

**这五件都是"体鸣 + 有音高"**，靠**材料与共鸣结构**分出五个音色档位 ——
它们构成了管弦乐打击乐里"能奏出音高"的全部常规手段。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代—中世纪 | 亚洲与非洲有木条琴；东南亚的**竹排琴**传统尤为发达 |
| 19 世纪 | 欧洲改良为带共鸣管的版本；进入管弦乐（圣-桑《骷髅之舞》是著名用例） |
| 19 世纪末—20 世纪 | 成为管弦乐与管乐团的标准乐器；**马林巴在美国与日本被大幅改良**（音域扩展、四槌技术） |
| 20 世纪 | 现代作品常给它独立声部；马林巴成为独奏乐器 |
| 20 世纪后期至今 | 木条一族（木琴 · 马林巴 · 颤音琴）在爵士、影视与当代音乐里全面通用 |

## 常见误解

- **"木琴与马林巴是同一种乐器。"** 同族同构，但**材料与共鸣管长度不同** →
  音色差别明显（干脆 vs 暖厚），在乐队里的用法也不同。
- **"它是木头的所以音色柔。"** 它是木条一族里**最刚硬**的一件 —— 音头硬、余音短。
- **"它没有音高。"** **有明确音高**，能按乐谱演奏旋律与和声。
- **"它只能在管弦乐里当点缀。"** 它有独立的独奏文献，四槌技术让它能演奏复调。
- **"共鸣管只是装饰。"** 没有共鸣管，木条的声音会小得几乎听不见 —— 它是必需的放大器。

## 下一步

木条一族的另外两件是 [[instrument:marimba|马林巴]]（暖厚、余音长）与
[[instrument:vibraphone|颤音琴]]（金属、带旋转阀）。
从木质转向金属之后，还有 [[instrument:glockenspiel|钟琴]] 与 [[instrument:tubular-bells|管钟]]。
:::

::: en
The xylophone is the crispest member of the "wooden bar family": **hard wooden bars over resonators**,
giving a **dry, brittle, clearly grained** tone — every note is a separate bead.

It and the [[instrument:marimba|marimba]] are close relatives with opposite priorities:
**the xylophone wants points, the marimba wants lines.**

| Classification | Value |
|---|---|
| **HS class** | **Idiophone** · **pitched** |
| **Sub-type** | Hard wooden bars arranged by pitch · one resonator per bar · struck with hard mallets |
| **Family** | Western · Percussion (idiophone, wooden-bar family) |
| **Bayin** | Not applicable — a Chinese system; the xylophone is outside it |

> ⚠️ **One conceptual point**: **the difference between pitched and unpitched percussion is whether the
> vibrating body can produce a stable pitch.** Each xylophone **bar** is tuned by carving (an arch is cut
> underneath), fixing its frequency — so it can play specified notes and counts as *pitched* percussion.
> A [[instrument:snare-drum|snare]] or [[instrument:cymbals|cymbals]] has no such tuning structure, so it is
> unpitched. **The test is not "can I hear a height" but "can it produce the required note".**

## Structure: bars and resonators

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

Three points:

1. **The resonator is the amplifier.** A bar vibrates only slightly and is almost inaudible alone; the
   resonator below catches and radiates it — so a xylophone is not "just bars ringing".
2. **Shorter bar, higher note** — the same for marimba and vibraphone, only the material differs (wood,
   metal).
3. **Hard mallets.** Wood, rubber or plastic heads are the default, and they are a direct cause of the brittle
   tone; switching to soft heads changes the instrument at once.

## The wooden-bar family: one structure, three settings

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

**This trio is another case of "one structure, different colours"** (like the
[[instrument:trumpet|trumpet's three brothers]] and the flute family):

| Instrument | Bar material | Resonator | Tail | Colour |
|---|---|---|---|---|
| **Xylophone** | hard wood (thin) | short | short | dry, brittle, grained |
| **Marimba** | softer wood (thick) | **long** | long | warm, thick, smooth |
| **Vibraphone** | **metal** | long + vanes | **longest** | metallic, shimmering |

## Range

```range
{"range":"F4–C8","common":"C5–C7","caption":"木琴的音域","caption_en":"Xylophone range","note":"木琴属体鸣的有音高乐器。常见音域约 F4–C8（视琴条数）——比马林巴高一个八度左右。记谱即实音。"}
```

- **About F4–C8**, roughly an octave above the [[instrument:marimba|marimba]].
- **The working register is C5–C7**, where its beaded quality is clearest.
- **It is the high-register garnish of the orchestra** — used to brighten, to add "bone", or to depict
  skeletons, machinery and the uncanny.

## Timbre, and how to hear it

Four cues:

1. **Bone-dry.** A hard attack and a short tail — like striking dry wood, with a strong physical quality.
2. **Clear grains**, so fast passagework never smears.
3. **Legato is hard.** A short tail cannot "sing" — its biggest difference in use from the marimba.
4. **Change the mallet, change the instrument.** Hard is brittle, soft is rounder — but still drier than a
   marimba.

```audiolab
{"type":"instrument","gm":"Xylophone","synth":"struck","phrase":["C5","E5","G5","C6","E6","G6"],"label":"木琴的常用区：C5 到 G6","label_en":"The xylophone's working register — C5 up to G6","hint":"注意音头硬、余音短 —— 每个音像一颗独立的珠子","hint_en":"Hear the hard attack and short tail — each note is a separate bead."}
```

## Playing techniques

- **Two or four mallets.** Four (two per hand) allows harmony and polyphony — standard modern practice.
- **Hard heads** are the default; soft heads round the tone but lose the instrument's identity.
- **Fast passagework and rolls** are both strengths.
- **Damping** is needed less than on a marimba, since the tail is short.

## The family

| Instrument | Material | Pitch | Tail | Colour |
|---|---|---|---|---|
| **Xylophone** | hard wood | **yes** | short | dry, brittle |
| [[instrument:marimba\|Marimba]] | softer wood | **yes** | long | warm, thick |
| [[instrument:vibraphone\|Vibraphone]] | metal | **yes** | longest | metallic, shimmering |
| [[instrument:glockenspiel\|Glockenspiel]] | **steel** | **yes** | long | very bright, clear |
| [[instrument:tubular-bells\|Tubular bells]] | metal tubes | **yes** | extremely long | bell-like |

**All five are "idiophone + pitched"**, separated into five colour stops by **material and resonator
design** — together they form the whole standard means of playing pitch on orchestral percussion.

## History

| Period | State |
|---|---|
| Antiquity–Middle Ages | bar instruments exist in Asia and Africa; Southeast Asia's **bamboo ensemble** tradition is especially developed |
| 19th c. | European makers add resonators; it enters the orchestra (Saint-Saëns's *Danse macabre* is the famous case) |
| Late 19th–20th c. | standard in orchestra and band; the **marimba is greatly developed** in the USA and Japan (wider range, four-mallet technique) |
| 20th c. | contemporary works give it independent parts; the marimba becomes a solo instrument |
| Late 20th c. onward | the wooden-bar family (xylophone, marimba, vibraphone) is universal in jazz, film and contemporary music |

## Common misconceptions

- **"A xylophone and a marimba are the same instrument."** Same family and mechanics, but **different
  materials and resonator lengths** → audibly different (brittle versus warm), and scored differently.
- **"Being wooden, it must sound soft."** It is the **hardest** member of the family — hard attack, short
  tail.
- **"It has no pitch."** It **has definite pitch** and can play melody and harmony.
- **"It is only an orchestral garnish."** It has a solo repertoire, and four-mallet technique allows
  polyphony.
- **"The resonators are decorative."** Without them a bar is almost inaudible — they are essential
  amplifiers.

## Next

The family's other two members are the [[instrument:marimba|marimba]] (warm, long-tailed) and the
[[instrument:vibraphone|vibraphone]] (metal, with rotating vanes). Moving from wood to metal brings in the
[[instrument:glockenspiel|glockenspiel]] and [[instrument:tubular-bells|tubular bells]].
:::
