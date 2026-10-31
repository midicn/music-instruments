---
id: piano
site: inst
cat: I5
title: 钢琴
title_en: Piano
summary: 键盘击弦的弦鸣乐器，能靠触键控制力度，全音域乐器之一
summary_en: A keyboard-struck chordophone with touch-sensitive dynamics — one of the few full-range instruments
level: standard
tags: [乐器, 键盘, 西洋]
tags_en: [instrument, keyboard, western]
alias: [钢琴, piano, 三角钢琴, 立式钢琴, pianoforte]
order: 79
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:harpsichord]]"
  - "[[instrument:clavichord]]"
  - "[[instrument:celesta]]"
  - "[[instrument:organ]]"
instances:
  - pdmx-000071 | 贝多芬 F 大调圆号奏鸣曲 Op.17 —— 原是圆号与钢琴的作品，可听钢琴在室内乐里的角色
  - pdmx-002479 | 为圆号与钢琴的四首小品 Op.35 —— 同为"独奏乐器 + 钢琴"的编制
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 无钢琴的编制，可作对照
sources:
  - 结构依通行制琴资料：**键盘**经**击弦机**驱动包毡木槌击弦；每音由**一至三根弦**构成，弦的振动经**音板**放大；**制音器**在离键时止音，右踏板可整体解除
  - 「钢琴属**弦鸣**乐器 —— 振源是弦；键盘只是操作界面」依 Hornbostel–Sachs 分类
  - 「标准音域 A0–C8（88 键）」依通行制琴规格
  - 「击弦机使音量与音色随触键力度变化 —— 这是它与大键琴最根本的区别」依乐器史与乐器声学
updated: 2026-09-26
---

::: zh
按下琴键，木槌飞出去，击弦，落回。手指按得多快，槌就飞得多快——钢琴与大键琴的全部差别，从这一下开始。

| 分类 | 归属 |
|---|---|
| HS 分类 | 弦鸣 —— 振动的是弦，键盘只是操作界面 |
| 键与弦 | 每音一至三根弦 · 击弦机驱动包毡木槌 · 音板放大 · 制音器止音 |
| 所属族 | 西洋 · 键盘（击弦支系） |
| 八音 | 不适用 —— 八音是周代中国的体系，钢琴不在其中 |

## 三个机制

力度来自击弦：槌与弦的接触只有一瞬，可槌的速度跟着手指走。余音由制音器管：离键即止，右踏板把全部制音器抬起，声音才叠得起来。音量靠音板：弦的振动传到一大片云杉上，才够填满厅堂。

右踏板不只是把声音变大，它改的是和声叠加的方式。三者缺一，就不是这件乐器。只有力度没有音量，是击弦古钢琴；只有音量没有力度，是大键琴；有余音却没有踏板，踩住一片和声这件事根本不存在。

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="钢琴的三个核心机制：击弦机带来力度控制、制音器与踏板控制余音、音板放大音量">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">三个机制，决定了钢琴能做而大键琴做不到的事</text>
  </g>
  <rect x="40" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="124" y="76" text-anchor="middle" font-size="11" fill="#5B7FA8">机制一 · 击弦机</text>
  <path d="M72,130 L140,104" stroke="#5B7FA8" stroke-width="4" stroke-linecap="round"/>
  <ellipse cx="148" cy="100" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M60,150 L100,150" stroke="#5B7FA8" stroke-width="3" stroke-linecap="round"/>
  <text x="124" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">按键 → 木槌击弦</text>
  <text x="124" y="192" text-anchor="middle" font-size="10.5" fill="#5B7FA8">力度可控制</text>
  <rect x="236" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="320" y="76" text-anchor="middle" font-size="11" fill="#9C7A3C">机制二 · 制音器</text>
  <path d="M300,128 L356,112" stroke="#9C7A3C" stroke-width="3.4" stroke-linecap="round"/>
  <rect x="352" y="104" width="16" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M280,144 L360,144" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="320" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">离键即止音</text>
  <text x="320" y="192" text-anchor="middle" font-size="10.5" fill="#9C7A3C">踏板解除限制</text>
  <rect x="432" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="516" y="76" text-anchor="middle" font-size="11" fill="#E07A3F">机制三 · 音板</text>
  <path d="M462,140 C492,120 540,120 570,140" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M462,150 C492,170 540,170 570,150" fill="none" stroke="#E07A3F" stroke-width="2" stroke-dasharray="4 3"/>
  <text x="516" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">弦的振动经音板放大</text>
  <text x="516" y="192" text-anchor="middle" font-size="10.5" fill="#E07A3F">音量足以填满厅堂</text>
  <text x="20" y="234" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三者缺一不可：只有力度没有音量，就是击弦古钢琴；只有音量没有力度，就是大键琴；</text>
  <text x="20" y="256" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">只有力度与音量而没有余音控制，就没有"踩住踏板"这件事 —— 那样音乐的语言会完全不同。</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">钢琴之所以成为 19 世纪音乐的"通用乐器"，正是因为它三项俱全。</text>
  <text x="20" y="306" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以你听到的"钢琴的表现力"，背后是三条具体的机械设计。</text>
</svg>
```

## 键盘只是界面

同样一排黑白键，底下可以是四种东西：钢琴击弦，大键琴拨弦，管风琴送气，钢片琴敲钢片。前两个是弦鸣，第三个是气鸣，第四个是体鸣。

所以「键盘乐器」说的是怎么操作，不是什么东西在响。分类要问的是后者。

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="钢琴、大键琴与击弦古钢琴三种触发方式的对照：击弦可控制力度、拨弦不能、击弦但音量极小">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同样是键盘，三种触发方式</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="66" fill="#5B7FA8">钢琴 · 击弦</text>
    <text x="20" y="88" fill="#A9A49B">木槌击弦，击完即离</text>
    <text x="20" y="110" fill="#6E6A64">力度可控制 ✓ 音量可大 ✓ 余音可控 ✓</text>
    <text x="20" y="146" fill="#9C7A3C">大键琴 · 拨弦</text>
    <text x="20" y="168" fill="#A9A49B">羽管拨弦，拨完即回</text>
    <text x="20" y="190" fill="#6E6A64">力度不可控制 ✗ 音量固定 余音可控 ✓</text>
    <text x="20" y="226" fill="#E07A3F">击弦古钢琴 · 击弦</text>
    <text x="20" y="248" fill="#A9A49B">铜片击弦，击后仍触弦</text>
    <text x="20" y="270" fill="#6E6A64">力度可控制 ✓ 音量极小 ✗（还可用触键做颤音）</text>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M316,50 L316,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="332" y="66">触发方式的差别只有一点：</text>
    <text x="332" y="88">击弦的"接触时间"极短，但击弦的速度</text>
    <text x="332" y="110">可以随按键的速度改变 → 这就是"力度"。</text>
    <text x="332" y="146">拨弦的接触由机械固定，按键快慢</text>
    <text x="332" y="168">不影响拨动的力度 → 因此没有力度层次。</text>
    <text x="332" y="204">击弦古钢琴用铜片，击后铜片继续</text>
    <text x="332" y="226">压在弦上 → 演奏者可以在按键后继续</text>
    <text x="332" y="248">加压，做出颤音（Bebung）——</text>
    <text x="332" y="270" fill="#E07A3F">这是键盘乐器里极少见的一种"后触"效果。</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"能不能控制力度"不是风格问题，而是「机械结构决定的」。</text>
</svg>
```

## 八十八键是一把尺

A0 到 C8，八十八个键，七个多八度。常用区到 C7 为止，最上面那个八度多留给独奏和炫技。

它的宽度成了键盘组的标尺：看大键琴、击弦古钢琴、管风琴的音域，都可以直接摆在它上面，看它们占哪一段。

```range
{"range":"A0–C8","common":"A0–C7","caption":"钢琴的音域（88 键）","caption_en":"Piano range (88 keys)","note":"钢琴属弦鸣乐器 —— 键盘只是操作界面，振源是弦。标准 88 键，音域 A0–C8，是这里键盘条目的参照尺度：其他键盘乐器的音域都可以在这上面标出位置。"}
```

## 力度是它的语言

一台琴能从几乎听不见做到极强，这是它在十九世纪成为通用乐器的理由。1700 年前后，意大利人 Cristofori 做出第一台靠触键控制力度的键盘击弦乐器；到十九世纪，金属框架、交叉弦列、毡槌陆续成熟，音量与音域一起撑开，八十八键在后期定为标准。

它也有做不到的事：击弦之后声音只会衰减，不能像管风琴或弦乐那样把音撑住。写钢琴曲的人，写的就是这种会消失的声音。

立式与三角的弦向不同，击弦机也不同，手感与声音都有差别。

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["A0","A2","A4","C6","C8"],"label":"钢琴的音域：从最低 A0 到最高 C8","label_en":"The piano's range — from A0 up to C8","hint":"注意低音的厚与高音的亮 —— 这个跨度是它成为「通用乐器」的原因","hint_en":"Hear the depth at the bottom and the brightness at the top — this span is why it became the universal instrument."}
```

:::

::: en
Press a key and a hammer flies out, strikes, falls back. The faster the finger, the faster the hammer — and the whole difference between a piano and a harpsichord begins there.

| Class | Assignment |
|---|---|
| **HS class** | Chordophone — the strings vibrate; the keyboard is only the interface |
| Key and string | one to three strings per note · a felt hammer driven by an action · soundboard · dampers |
| Family | Western · keyboard (struck branch) |
| Bayin | not applicable — a Chinese system of the Zhou; the piano is outside it |

## Three mechanisms

Dynamics come from the strike: the hammer touches the string for an instant, but its speed follows the finger. The tail is the dampers' business: release the key and the sound stops, until the right pedal lifts them all and notes pile up. Volume comes from the soundboard, which spreads the string's vibration over a sheet of spruce wide enough for a hall.

Take one away and it is another instrument. Dynamics without volume is a clavichord; volume without dynamics is a harpsichord; with no pedal to hold the harmony, the whole gesture of a sustained chord would not exist.

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The piano's three core mechanisms: hammer action gives dynamic control, dampers and pedal manage the ring, the soundboard amplifies">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Three mechanisms — what the piano can do and a harpsichord cannot</text>
  </g>
  <rect x="40" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="124" y="76" text-anchor="middle" font-size="11" fill="#5B7FA8">1 · Hammer action</text>
  <path d="M72,130 L140,104" stroke="#5B7FA8" stroke-width="4" stroke-linecap="round"/>
  <ellipse cx="148" cy="100" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M60,150 L100,150" stroke="#5B7FA8" stroke-width="3" stroke-linecap="round"/>
  <text x="124" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">key → hammer → string</text>
  <text x="124" y="192" text-anchor="middle" font-size="10.5" fill="#5B7FA8">dynamics controllable</text>
  <rect x="236" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="320" y="76" text-anchor="middle" font-size="11" fill="#9C7A3C">2 · Dampers</text>
  <path d="M300,128 L356,112" stroke="#9C7A3C" stroke-width="3.4" stroke-linecap="round"/>
  <rect x="352" y="104" width="16" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M280,144 L360,144" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="320" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">release stops the sound</text>
  <text x="320" y="192" text-anchor="middle" font-size="10.5" fill="#9C7A3C">pedal lifts the limit</text>
  <rect x="432" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="516" y="76" text-anchor="middle" font-size="11" fill="#E07A3F">3 · Soundboard</text>
  <path d="M462,140 C492,120 540,120 570,140" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M462,150 C492,170 540,170 570,150" fill="none" stroke="#E07A3F" stroke-width="2" stroke-dasharray="4 3"/>
  <text x="516" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">strings amplified by the board</text>
  <text x="516" y="192" text-anchor="middle" font-size="10.5" fill="#E07A3F">enough volume for a hall</text>
  <text x="20" y="234" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">All three matter: dynamics without volume is a clavichord; volume without dynamics is a harpsichord;</text>
  <text x="20" y="256" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">and without control of the ring there would be no such thing as holding the pedal down.</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">The piano became the 19th century's universal instrument precisely because it has all three.</text>
  <text x="20" y="306" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">So "the piano's expressiveness" rests on three concrete mechanical designs.</text>
</svg>
```

## The keyboard is only the interface

One row of keys can sit on four different things: a piano strikes strings, a harpsichord plucks them, an organ drives air, a celesta strikes steel plates. The first two are chordophones, the third an aerophone, the fourth an idiophone.

So keyboard instrument describes how it is operated, not what vibrates. Classification asks the second question.

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Piano, harpsichord and clavichord compared by trigger: struck strings allow dynamics, plucked strings do not, struck copper tangents allow dynamics but are very quiet">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One keyboard, three ways of setting a string going</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="66" fill="#5B7FA8">Piano · struck</text>
    <text x="20" y="88" fill="#A9A49B">felt hammer strikes, then leaves</text>
    <text x="20" y="110" fill="#6E6A64">dynamics YES · loud YES · ring control YES</text>
    <text x="20" y="146" fill="#9C7A3C">Harpsichord · plucked</text>
    <text x="20" y="168" fill="#A9A49B">a quill plucks and returns</text>
    <text x="20" y="190" fill="#6E6A64">dynamics NO · fixed volume · ring control YES</text>
    <text x="20" y="226" fill="#E07A3F">Clavichord · struck (tangent)</text>
    <text x="20" y="248" fill="#A9A49B">a brass tangent strikes and stays in contact</text>
    <text x="20" y="270" fill="#6E6A64">dynamics YES · very quiet NO · can even add vibrato</text>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M316,50 L316,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="332" y="66">The trigger difference is one thing:</text>
    <text x="332" y="88">a strike touches the string for an instant, but</text>
    <text x="332" y="110">its speed follows the key → that is "dynamics".</text>
    <text x="332" y="146">A pluck's force is fixed by the mechanism, so key</text>
    <text x="332" y="168">speed changes nothing → no dynamic layering.</text>
    <text x="332" y="204">The clavichord's tangent stays pressed against</text>
    <text x="332" y="226">the string, so the player can keep adding</text>
    <text x="332" y="248">pressure after the key is down (Bebung) —</text>
    <text x="332" y="270" fill="#E07A3F">a rare "after-touch" effect in keyboard playing.</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"Can it control dynamics" is not a matter of taste but of 「mechanism」.</text>
</svg>
```

## Eighty-eight keys are a ruler

A0 to C8, eighty-eight keys, more than seven octaves. The working range stops at C7; the top octave is mostly for solo and display.

Its width became the keyboard group's measure: set a harpsichord, a clavichord or an organ against it and you see at once which stretch they occupy.

```range
{"range":"A0–C8","common":"A0–C7","caption":"钢琴的音域（88 键）","caption_en":"Piano range (88 keys)","note":"钢琴属弦鸣乐器 —— 键盘只是操作界面，振源是弦。标准 88 键，音域 A0–C8，是这里键盘条目的参照尺度：其他键盘乐器的音域都可以在这上面标出位置。"}
```

## Dynamics are its language

One instrument from almost inaudible to very loud — the reason it became the universal instrument of the nineteenth century. Around 1700 Cristofori built the first keyboard instrument whose touch controlled dynamics; by the 1800s iron frames, overstringing and felt hammers had widened volume and compass together, and eighty-eight keys settled as the standard.

It also cannot do one thing: a struck note only decays. It will not hold like an organ or a bowed string. Music written for it is music about a sound that leaves.

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["A0","A2","A4","C6","C8"],"label":"钢琴的音域：从最低 A0 到最高 C8","label_en":"The piano's range — from A0 up to C8","hint":"注意低音的厚与高音的亮 —— 这个跨度是它成为「通用乐器」的原因","hint_en":"Hear the depth at the bottom and the brightness at the top — this span is why it became the universal instrument."}
```
:::
