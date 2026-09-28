---
id: cymbals
site: inst
cat: I4
title: 铙钹
title_en: Cymbals
summary: 用青铜合金制成的体鸣片状乐器，两片对击或单面吊击，泛音极丰富
summary_en: Bronze idiophones struck in pairs or hung singly — an extremely rich, noise-like spectrum
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [铙钹, cymbals, 镲, 镲片, 钹, piatti]
order: 60
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:snare-drum]]"
  - "[[instrument:gong]]"
  - "[[instrument:drum-kit]]"
  - "[[instrument:triangle]]"
instances:
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里铙钹的实际用法
  - pdmx-000510 | Drake's Drum —— 标题指向鼓类的曲目，可作时代语汇的参照
  - pdmx-002820 | 为三支小号与定音鼓而作的协奏曲 TWV 54:D4 —— 巴洛克打击乐的写法，与铙钹的现代用法形成对照
sources:
  - 结构依通行制琴资料：多为**青铜合金**（如 B20）制成的圆形薄片，中心有隆起（bell），经手工锤打与车削成型
  - 「铙钹属**体鸣**乐器 —— 合金材料本身整体振动，没有膜、没有空气柱」依 Hornbostel–Sachs 分类
  - 「无固定音高，但不同尺寸与厚度有相对的音高感（小的偏高、大的偏低）」依乐器制作通识
  - 「常见形态：两片对击（对镲 / crash）、单面吊击（吊镲 / ride）、踩镲（hi-hat）」依通行打击乐惯例
updated: 2026-09-26
---

::: zh
铙钹是[[instrument:snare-drum|小鼓]]之外的另一个"高频来源"，但它的振动方式完全不同：
**不是一张膜，而是一整片青铜合金**。这就是**体鸣**。

它也是打击乐里"制作工艺最讲究"的一件：**同样的铜锡比例，锤打的方式决定音色**，
所以不同品牌、甚至同一品牌的不同批号，声音都可能不同。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **体鸣**（Idiophone）—— **合金片本身整体振动**，没有膜、没有空气柱 |
| **次级类型** | 圆形薄片（中心隆起）· 无固定音高 · 对击 / 吊击 / 脚踏 |
| **所属族** | 西洋 · 打击（体鸣支系 · 无音高） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，铙钹不在其中 |

> ⚠️ **一个概念上的要点**：**"膜鸣"与"体鸣"的差别，在这里最能看清。**
> [[instrument:snare-drum|小鼓]]的高频来自**一张被拉紧的膜**；
> 铙钹的高频来自**整片合金的复杂振动模式**。
> 结果是两者听起来"都是噪声"，但**质感完全不同**：小鼓是"沙"（颗粒清晰），
> 铙钹是"嘶"（能量铺满整个高频段，余音极长）。
> **判据仍然是"什么在振动"** —— 而这一条判据顺带解释了它们的音色差别。

## 结构：一片合金的复杂振动

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="铙钹的结构：圆形青铜合金薄片、中心隆起的bell、同心车削纹与两片对击的用法">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">铙钹 · 结构（一片合金的整体振动，没有膜）</text>
  </g>
  <ellipse cx="230" cy="164" rx="128" ry="86" fill="#17171A" stroke="#9C7A3C" stroke-width="2"/>
  <ellipse cx="230" cy="164" rx="98" ry="64" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="164" rx="66" ry="42" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="164" rx="34" ry="22" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="158" rx="22" ry="15" fill="#0E0E10" stroke="#E07A3F" stroke-width="1.8"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,52 L222,146"/><path d="M186,132 L216,148"/>
    <path d="M186,262 L214,236"/><path d="M186,202 L186,190"/>
    <path d="M486,150 L350,158"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="49" text-anchor="end" fill="#E07A3F">中心隆起（bell）</text>
    <text x="180" y="135" text-anchor="end">较厚的中心区（音色干）</text>
    <text x="180" y="265" text-anchor="end">薄而外张的边缘（音色散）</text>
    <text x="180" y="205" text-anchor="end" fill="#5B7FA8">同心车削纹（决定音色细节）</text>
    <text x="492" y="147">合金薄片整体在振动</text>
  </g>
  <text x="20" y="290" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">击鼓心附近音色干、控制好；击边缘音色散、余音长 —— 同一片镲上的"音色地图"很宽。</text>
</svg>
```

三处要点：

1. **没有膜也没有空气柱** —— 整片合金在振动。所以它的泛音**极其丰富且不规则**，
   听起来是"嘶"而不是"音"。
2. **片上有明显的"音色地图"**。击**中心附近**（接近 bell）音色干、控制好；
   击**边缘**音色散、余音极长。鼓手就在这张地图上工作。
3. **制作工艺决定一切**。铜锡比例、锤打的分布、车削纹 ——
   这三项一起决定最终音色，所以镲是打击乐里最"因乐器而异"的一件。

## 三种常见形态

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="铙钹的三种常见形态：两片对击、单面吊击与一对踩镲">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">一片合金，三种用法</text>
  </g>
  <text x="120" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">两片对击（对镲）</text>
  <ellipse cx="94" cy="140" rx="46" ry="68" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <ellipse cx="146" cy="140" rx="46" ry="68" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <path d="M120,60 L120,86" stroke="#9C7A3C" stroke-width="1.4" stroke-dasharray="3 3"/>
  <text x="120" y="212" text-anchor="middle" font-size="10.5" fill="#A9A49B">管弦乐的标准用法</text>
  <text x="120" y="234" text-anchor="middle" font-size="10.5" fill="#9C7A3C">一击即收，用来强调</text>
  <text x="320" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">单面吊击（吊镲）</text>
  <ellipse cx="320" cy="150" rx="66" ry="44" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M320,106 L320,74" stroke="#5B7FA8" stroke-width="1.4"/>
  <path d="M296,72 L344,72" stroke="#5B7FA8" stroke-width="3"/>
  <text x="320" y="212" text-anchor="middle" font-size="10.5" fill="#A9A49B">悬吊起来自由振动</text>
  <text x="320" y="234" text-anchor="middle" font-size="10.5" fill="#5B7FA8">余音最长、最"嘶"</text>
  <text x="520" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">踩镲（hi-hat）</text>
  <ellipse cx="520" cy="132" rx="56" ry="34" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <ellipse cx="520" cy="164" rx="56" ry="34" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <path d="M520,190 L520,222" stroke="#E07A3F" stroke-width="4"/>
  <text x="520" y="248" text-anchor="middle" font-size="10.5" fill="#A9A49B">两片叠放，脚踏与鼓棒同时控制</text>
  <text x="520" y="268" text-anchor="middle" font-size="10.5" fill="#E07A3F">节奏组的"时间标尺"</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三种形态的物理原理相同，但"怎么让它停"完全不同 —— 这才是它们音色差异的来源。</text>
</svg>
```

**三种形态的差别本质上是"余音控制方式"的差别**：

| 形态 | 振动时长 | 用途 |
|---|---|---|
| **对镲**（两片） | 短（可手按止音） | 强调、重音 |
| **吊镲**（单面悬挂） | **最长** | 高潮的"炸"、持续的气氛 |
| **踩镲**（两片叠放 + 脚踏） | 可控（踩紧即止） | 节奏的时间标尺 |

## 音域

铙钹属于**无固定音高**乐器，本站不为其生成音域图。它在实践中的"高低"体现为**尺寸与厚度的相对音高感**：

| 类型 | 尺寸倾向 | 相对音高感 | 音色 |
|---|---|---|---|
| **踩镲（hi-hat）** | 中等（常 14 英寸） | 高、短 | 紧、清晰 |
| **吊镲（crash）** | 中偏小 | 中高 | 炸、余音长 |
| **叮叮镲（ride）** | 较大（常 20–22 英寸） | 中低 | 清、有"叮"的定音感 |
| **大吊镲 / 锣镲** | 大 | 低 | 深沉、余音极长 |

**注意"ride 有定音感"这一条**：叮叮镲的音色里有一种相对明确的音高感，
所以它在爵士里能承担"时间标尺"的角色 —— 但这仍不是**固定音高**，本站不为其画音域图。

## 音色与听辨

四条线索：

1. **"嘶"而不是"沙"**。与小鼓的颗粒感不同，铙钹的能量是**连续铺满**整个高频段的。
2. **余音极长**（吊镲）。所以它是"制造空间感"的乐器 —— 一次重击可以撑起几秒的气氛。
3. **不同击奏位置差别巨大**。边缘"散"、中心"干"、bell"清"。
4. **强弱层次极宽**。从鼓刷轻扫的"嘶嘶"到全力的"炸"，动态范围在打击乐里数一数二。

```audiolab
{"type":"instrument","drum":49,"synth":"perc","phrase":[49,49,42,42,49],"label":"吊镲与踩镲的对比","label_en":"Crash against closed hi-hat","hint":"注意余音的差别 —— 吊镲能撑几秒，踩镲一踩就收","hint_en":"Hear the tail: a crash rings for seconds, a closed hi-hat stops at once."}
```

## 演奏技法

- **对击（管弦乐）**：两片对撞后立即分开或按住 —— 控制余音长短。
- **吊击**：用鼓棒、鼓刷或槌头击打；击不同位置得到不同音色。
- **闷击（choke）**：击后用手抓住镲片立即止音 —— 得到短促的一击。
- **踩镲的开合**：脚踏控制两片之间的距离，"闭"得到干短的"呲"，"开"得到延长的"嘶"。
- **叮叮镲的节奏型**：爵士鼓手用 ride 打出持续的节奏线，并靠击打位置变化制造层次。

## 家族与近亲

| 乐器 | 类别 | 振动 | 音色 |
|---|---|---|---|
| **铙钹** | 体鸣 | 合金片整体 | 宽带噪声，余音长 |
| [[instrument:snare-drum\|小鼓]] | **膜鸣** | 膜 + 响弦 | 颗粒清晰的高频 |
| [[instrument:gong\|锣]] | 体鸣 | 合金整体（更不规则） | 低频 + 长余音 |
| [[instrument:triangle\|三角铁]] | 体鸣 | 钢棒弯曲体 | 极亮、高度集中 |

**铙钹与锣是同一类（体鸣的金属片/盘），但形状与敲法完全不同** ——
一个被"击"，一个被"撞"（或击其中心）。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代 | 金属片状打击乐器在西亚、中亚与东亚出现；中国的**铙**与**钹**是独立来源 |
| 中世纪—文艺复兴 | 通过土耳其军乐（mehter）传入欧洲 |
| 18—19 世纪 | 随土耳其风格进入管弦乐；成为标准打击乐器 |
| 20 世纪初 | **爵士鼓组**把镲片系统化：踩镲、吊镲、叮叮镲各有分工 |
| 20 世纪后半 | 镲片制作工艺高度专业化；不同品牌与型号的音色差异成为鼓手的重要选择 |
| 20 世纪后期至今 | 管弦乐、管乐团、爵士、摇滚、流行的通用乐器 |

## 常见误解

- **"铙钹与小鼓是一类，都是通过敲击发声。"** 类别不同：铙钹是**体鸣**（材料整体振动），
  小鼓是**膜鸣**（膜是振源）。"敲击"是演奏方式，不是分类。
- **"镲没有音色层次，就是'炸'。"** 它的击奏位置、力度、止音方式带来极宽的音色范围。
- **"镲越贵越好。"** 音色与价格有关，但**匹配比价格更重要** ——
  一套镲要按音乐风格搭配（爵士要薄而暖，摇滚要厚而亮）。
- **"中国的钹就是西洋的铙钹。"** 两者**形制相似但来源独立**，
  中国的钹在民族音乐里有一套自己的用法；**相似不等于同源**。
- **"它有音高。"** 无固定音高。不同尺寸有相对的音高感，但那不是音域意义上的音高。

## 下一步

体鸣里还有一件与它同族但性格相反的乐器：[[instrument:gong|锣]] ——
同样是金属整体振动，但能量更偏低频、余音更长。
想对照"高频的另一个来源"，就去看 [[instrument:snare-drum|小鼓]]（膜鸣）。
:::

::: en
The cymbals are the snare drum's counterpart as a source of high frequency, but their vibration is entirely
different: **not a head, but a sheet of bronze alloy.** That is **idiophone**.

They are also the most craft-dependent instrument in percussion: **given the same copper-tin ratio, the
hammering decides the sound** — so one brand, even one batch, can differ from another.

| Classification | Value |
|---|---|
| **HS class** | **Idiophone** — **the alloy sheet vibrates as a whole**, with no head and no air column |
| **Sub-type** | Round thin sheet (with a raised bell) · unpitched · struck in pairs, hung, or pedal-operated |
| **Family** | Western · Percussion (idiophone branch, unpitched) |
| **Bayin** | Not applicable — a Chinese system; cymbals are outside it |

> ⚠️ **One conceptual point**: **the difference between membranophone and idiophone is clearest here.**
> The [[instrument:snare-drum|snare]]'s high frequencies come from **a stretched head**; the cymbals' come
> from **the complex vibration of a whole alloy sheet**.
> Both end up "noisy", but of **completely different grain**: a snare is a *crackle* (clear grains), cymbals
> are a *hiss* (energy spread across the whole high band, with a long tail).
> **The test is still what vibrates** — and it incidentally explains why they sound so different.

## Structure: one sheet vibrating in complex modes

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cymbal structure: a round bronze sheet with a raised bell, concentric lathed grooves, and its use as a pair">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Cymbals — structure (one alloy sheet vibrating, no head)</text>
  </g>
  <ellipse cx="230" cy="164" rx="128" ry="86" fill="#17171A" stroke="#9C7A3C" stroke-width="2"/>
  <ellipse cx="230" cy="164" rx="98" ry="64" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="164" rx="66" ry="42" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="164" rx="34" ry="22" fill="none" stroke="#343439" stroke-width="1.1"/>
  <ellipse cx="230" cy="158" rx="22" ry="15" fill="#0E0E10" stroke="#E07A3F" stroke-width="1.8"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,52 L222,146"/><path d="M186,132 L216,148"/>
    <path d="M186,262 L214,236"/><path d="M186,202 L186,190"/>
    <path d="M486,150 L350,158"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="49" text-anchor="end" fill="#E07A3F">Bell (raised centre)</text>
    <text x="180" y="135" text-anchor="end">Thicker centre — drier</text>
    <text x="180" y="265" text-anchor="end">Thin flaring edge — open</text>
    <text x="180" y="205" text-anchor="end" fill="#5B7FA8">Concentric lathing</text>
    <text x="492" y="147">The whole sheet vibrates</text>
  </g>
  <text x="20" y="290" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Near the bell the sound is dry; at the edge open with a long tail. One cymbal is a map of colours.</text>
</svg>
```

Three points:

1. **No head, no air column** — the whole alloy sheet vibrates, so its overtones are **extremely rich and
   irregular**: it reads as a hiss, not a note.
2. **The surface is a colour map.** Near the **centre (bell)** the sound is dry and controlled; at the
   **edge** it is open with a very long tail. Players work that map.
3. **Craft decides everything** — alloy ratio, hammering pattern and lathing together fix the final sound,
   making cymbals percussion's most instrument-specific purchase.

## Three common forms

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Three forms of cymbals: a pair struck together, a single hung cymbal and a hi-hat pair">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One alloy sheet, three ways of using it</text>
  </g>
  <text x="120" y="62" text-anchor="middle" font-size="11" fill="#9C7A3C">A pair (orchestral)</text>
  <ellipse cx="94" cy="140" rx="46" ry="68" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <ellipse cx="146" cy="140" rx="46" ry="68" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <path d="M120,60 L120,86" stroke="#9C7A3C" stroke-width="1.4" stroke-dasharray="3 3"/>
  <text x="120" y="212" text-anchor="middle" font-size="10.5" fill="#A9A49B">the orchestral standard</text>
  <text x="120" y="234" text-anchor="middle" font-size="10.5" fill="#9C7A3C">one crash, then damped</text>
  <text x="320" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Suspended (crash / ride)</text>
  <ellipse cx="320" cy="150" rx="66" ry="44" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M320,106 L320,74" stroke="#5B7FA8" stroke-width="1.4"/>
  <path d="M296,72 L344,72" stroke="#5B7FA8" stroke-width="3"/>
  <text x="320" y="212" text-anchor="middle" font-size="10.5" fill="#A9A49B">hung to ring freely</text>
  <text x="320" y="234" text-anchor="middle" font-size="10.5" fill="#5B7FA8">the longest, hissiest tail</text>
  <text x="520" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">Hi-hat</text>
  <ellipse cx="520" cy="132" rx="56" ry="34" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <ellipse cx="520" cy="164" rx="56" ry="34" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <path d="M520,190 L520,222" stroke="#E07A3F" stroke-width="4"/>
  <text x="520" y="248" text-anchor="middle" font-size="10.5" fill="#A9A49B">two stacked, worked by foot and stick</text>
  <text x="520" y="268" text-anchor="middle" font-size="10.5" fill="#E07A3F">the rhythm section's clock</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Same physics, but the way each is stopped differs completely — which is where their colours differ.</text>
</svg>
```

**The three forms differ essentially in how their ring is controlled**:

| Form | Duration | Use |
|---|---|---|
| **Pair** (two) | short (hand-damped) | accents, emphases |
| **Suspended** (one, hung) | **longest** | climaxes, sustained atmosphere |
| **Hi-hat** (two stacked + pedal) | controllable (closed = stopped) | the rhythm section's clock |

## Range

Cymbals are **unpitched**, so no range chart is generated. In practice their "height" shows up as a
**relative sense of pitch from size and weight**:

| Type | Size tendency | Relative height | Colour |
|---|---|---|---|
| **Hi-hat** | medium (often 14") | high, short | tight, clear |
| **Crash** | medium-small | medium-high | explosive, long tail |
| **Ride** | larger (often 20–22") | medium-low | clear, with a "ping" |
| **Large crash / gong cymbal** | large | low | deep, very long tail |

**Note the ride's "ping"**: it carries a relatively definite sense of pitch, which is how it can act as the
clock in jazz — but this is still not **definite pitch**, so no range chart is drawn.

## Timbre, and how to hear it

Four cues:

1. **A hiss rather than a crackle.** Unlike a snare's grains, cymbal energy fills the **whole high band
   continuously**.
2. **An extremely long tail** (suspended). It is a space-making instrument: one crash can sustain several
   seconds of atmosphere.
3. **Striking position changes everything**: edge open, centre dry, bell clear.
4. **A huge dynamic range**, from a brush's whisper to a full crash — among the widest in percussion.

```audiolab
{"type":"instrument","drum":49,"synth":"perc","phrase":[49,49,42,42,49],"label":"吊镲与踩镲的对比","label_en":"Crash against closed hi-hat","hint":"注意余音的差别 —— 吊镲能撑几秒，踩镲一踩就收","hint_en":"Hear the tail: a crash rings for seconds, a closed hi-hat stops at once."}
```

## Playing techniques

- **Pairs (orchestral)**: collide the two, then either separate or press them together to control the tail.
- **Suspended**: struck with sticks, brushes or mallets; different spots give different colours.
- **Choke**: grab the cymbal right after the stroke for a short, cut-off hit.
- **Hi-hat opening and closing**: the pedal sets the gap — closed gives a dry tick, open a longer hiss.
- **Ride patterns**: jazz drummers play a continuous line on the ride, varying the striking spot for shape.

## The family

| Instrument | Class | Vibrating part | Colour |
|---|---|---|---|
| **Cymbals** | idiophone | the alloy sheet as a whole | broadband noise, long tail |
| [[instrument:snare-drum\|Snare drum]] | **membranophone** | head plus snares | grainy high frequencies |
| [[instrument:gong\|Gong]] | idiophone | alloy, more irregular | low plus a very long tail |
| [[instrument:triangle\|Triangle]] | idiophone | a bent steel rod | extremely bright and focused |

**Cymbals and the gong are the same class (metal sheets and discs)**, but their shapes and ways of being set
in motion differ entirely — one is **struck**, the other **struck at its centre or hit**.

## History

| Period | State |
|---|---|
| Antiquity | sheet-metal percussion appears in West, Central and East Asia; China's **nao** and **bo** are an independent line |
| Medieval–Renaissance | reaches Europe through Turkish military music (mehter) |
| 18th–19th c. | enters the orchestra with Turkish style and becomes standard percussion |
| Early 20th c. | the **jazz drum kit** systematises cymbals: hi-hat, crash and ride each get a role |
| Later 20th c. | cymbal making becomes highly specialised; brand and model differences become a player's key choice |
| Late 20th c. onward | universal across orchestra, band, jazz, rock and pop |

## Common misconceptions

- **"Cymbals and snares are the same class, both struck."** They are not: cymbals are **idiophones** (the
  material vibrates), snares **membranophones** (the head is the source). Striking is a playing method, not a
  classification.
- **"A cymbal has one colour: crash."** Striking position, dynamics and damping give it a very wide range.
- **"More expensive is better."** Price matters, but **matching matters more** — a set is chosen for a style
  (thin and warm for jazz, heavy and bright for rock).
- **"Chinese bo are the same as Western cymbals."** Similar in form but **independently originated**, with
  their own practice in Chinese music — **resemblance is not common origin**.
- **"They have pitch."** Unpitched. Different sizes carry a relative sense of height, but that is not pitch
  in the sense of a range.

## Next

Among the idiophones, one relative has an opposite character: the [[instrument:gong|gong]] — also a metal
body vibrating as a whole, but with more energy low down and an even longer tail.
For the other source of high frequency, see the [[instrument:snare-drum|snare drum]] (a membranophone).
:::
