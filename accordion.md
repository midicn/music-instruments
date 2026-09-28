---
id: accordion
site: inst
cat: I5
title: 手风琴
title_en: Accordion
summary: 手动风箱驱动自由簧的便携乐器，风箱压力直接控制力度
summary_en: A portable free-reed instrument whose hand bellows give direct dynamic control
level: standard
tags: [乐器, 键盘, 西洋, 世界]
tags_en: [instrument, keyboard, western, world]
alias: [手风琴, accordion, 键钮手风琴, 钢琴手风琴, 风琴（手风箱）]
order: 84
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:harmonium]]"
  - "[[instrument:harmonica]]"
  - "[[instrument:organ]]"
  - "[[instrument:piano]]"
instances:
  - pdmx-000322 | 鲁特琴与竖笛的协奏曲 —— 巴洛克室内乐的编制，可对照手风琴所继承的"旋律 + 伴奏"格局
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— 独奏乐器加伴奏键盘的写法，手风琴常担此职
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 无键盘无风箱的编制，可作对照
sources:
  - 结构依通行制琴资料：**手动风箱**送气，气流使**自由簧（free reed）**振动；右侧为旋律键（钢琴键式或按钮式），左侧为低音与和弦键
  - 「手风琴属**气鸣**乐器（自由簧）」依 Hornbostel–Sachs 分类
  - 「常见音域 F3–A6，视形制与键数而定」依通行乐器资料
  - 「**风箱的推拉速度快慢直接改变气流强度，因此演奏者能实时控制音量** —— 并在推与拉之间做不同的音色处理」依乐器声学与演奏通识
updated: 2026-09-26
---

::: zh
手风琴是自由簧一族里**最"自给自足"的一件**：
演奏者用左臂推拉风箱，同时用右手弹旋律、左手弹和声 ——
**一个人同时具备旋律、和声与动态控制三种能力。**

它在键盘组里还有一个别的乐器都没有的特点：
**力度由风箱直接控制**，而且这种控制**比管风琴精细、比簧风琴灵活**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）—— 气流使**自由簧**振动 |
| **次级类型** | **手动风箱**送气 · 自由簧发声 · 右侧旋律键（琴键或键钮）+ 左侧低音与和弦键 |
| **所属族** | 西洋 · 键盘（自由簧支系）· 同时是**世界乐器** |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，手风琴不在其中 |

> ⚠️ **一个概念上的要点**：**"力度从哪来"，在这三件自由簧乐器上是三个不同的答案。**
> - [[instrument:organ|管风琴]]：气流由**机械鼓风** → 力度**不可控**（靠音栓与渐强箱）。
> - [[instrument:harmonium|簧风琴]]：气流由**脚踏** → 力度**有限可控**。
> - **手风琴**：气流由**左臂推拉** → 力度**完全可控**，而且能做出极细的渐强渐弱。
>
> 所以"能不能控制力度"这个问题的答案，**不在于乐器属于哪一类，而在于"谁在供气、供气的方式能不能被实时调节"**。
> 这一条把手风琴与整个键盘组区分开来：**它是键盘乐器里动态控制最自由的一件。**

## 结构：风箱、两套键与簧

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="手风琴的结构：中央手动风箱、右侧旋律键盘、左侧低音与和弦键，气流经风箱驱动内部的自由簧">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">手风琴 · 结构（左臂供气 + 两套键）</text>
  </g>
  <rect x="70" y="96" width="70" height="110" rx="5" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g stroke="#5B7FA8" stroke-width="1.2">
    <path d="M80,104 L80,198"/><path d="M92,104 L92,198"/><path d="M104,104 L104,198"/>
    <path d="M116,104 L116,198"/><path d="M128,104 L128,198"/>
  </g>
  <g fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.3">
    <rect x="84" y="100" width="7" height="20" rx="2"/>
    <rect x="96" y="100" width="7" height="20" rx="2"/>
    <rect x="120" y="100" width="7" height="20" rx="2"/>
  </g>
  <path d="M150,110 C176,110 176,192 150,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M176,110 C202,110 202,192 176,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M202,110 C228,110 228,192 202,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M228,110 C254,110 254,192 228,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M254,110 C280,110 280,192 254,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M280,110 C306,110 306,192 280,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <rect x="316" y="96" width="108" height="110" rx="5" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <g stroke="#9C7A3C" stroke-width="0.9">
    <path d="M328,108 L328,192"/><path d="M344,108 L344,192"/><path d="M360,108 L360,192"/>
    <path d="M376,108 L376,192"/><path d="M392,108 L392,192"/><path d="M408,108 L408,192"/>
  </g>
  <g fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.2">
    <rect x="334" y="104" width="7" height="24" rx="2"/>
    <rect x="350" y="104" width="7" height="24" rx="2"/>
    <rect x="366" y="104" width="7" height="24" rx="2"/>
    <rect x="390" y="104" width="7" height="24" rx="2"/>
    <rect x="406" y="104" width="7" height="24" rx="2"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,80 L100,92"/><path d="M186,220 L104,212"/>
    <path d="M486,120 L430,132"/><path d="M486,204 L430,192"/>
    <path d="M186,264 L200,208"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="77" text-anchor="end" fill="#9C7A3C">右侧旋律键</text>
    <text x="180" y="223" text-anchor="end">左侧低音与和弦键</text>
    <text x="492" y="117" fill="#E07A3F">中央：手动风箱</text>
    <text x="492" y="207">左手同时供气与弹和声</text>
    <text x="180" y="267" text-anchor="end" fill="#E07A3F">左臂推拉 → 力度可控</text>
  </g>
  <text x="20" y="290" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">风箱的推与拉都由同一条手臂完成，所以演奏者能像"呼吸"一样控制音量 —— 这是管风琴与簧风琴都做不到的。</text>
</svg>
```

三处要点：

1. **左臂同时是"供气"和"和声"的手**。左手既按键（低音与和弦），
   也通过手臂的推拉控制风箱 —— **这是它技术上最难协调的地方**。
2. **两套键，两种体系**。右侧旋律键有**钢琴键式**（piano accordion）与**按钮式**（button accordion）两种传统；
   左侧是预设好的低音与和弦键。
3. **推与拉的音色可以不同**。许多手风琴在推与拉时切换到不同的簧组，
   所以同一个键在推和拉时音色略有差别 —— 这是它的一个特色（也被作曲家利用）。

## 力度控制：它是键盘乐器里最自由的一件

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="三种气流乐器由谁供气与力度是否可控：管风琴靠机械鼓风不可控，簧风琴脚踏有限可控，手风琴手动完全可控">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">"力度从哪来"：三件气流乐器，三个答案</text>
  </g>
  <rect x="50" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="134" y="80" text-anchor="middle" font-size="11" fill="#5B7FA8">管风琴</text>
  <text x="134" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">机械鼓风</text>
  <text x="134" y="130" text-anchor="middle" font-size="10.5" fill="#6E6A64">力度：不可控</text>
  <text x="134" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">靠音栓与渐强箱</text>
  <rect x="236" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <text x="320" y="80" text-anchor="middle" font-size="11" fill="#9C7A3C">簧风琴</text>
  <text x="320" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">脚踏</text>
  <text x="320" y="130" text-anchor="middle" font-size="10.5" fill="#9C7A3C">力度：有限可控</text>
  <text x="320" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">有一点呼吸感</text>
  <rect x="422" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.8"/>
  <text x="506" y="80" text-anchor="middle" font-size="11" fill="#E07A3F">手风琴</text>
  <text x="506" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">左臂推拉风箱</text>
  <text x="506" y="130" text-anchor="middle" font-size="10.5" fill="#E07A3F">力度：完全可控</text>
  <text x="506" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">可做极细的渐强渐弱</text>
  <text x="20" y="204" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三者的发声体都是气流驱动的（一件是空气柱、两件是自由簧），差别全在"谁在供气"。</text>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">所以"能不能控制力度"不是分类问题，而是"供气方式能否被实时调节"的问题。</text>
</svg>
```

**这也是手风琴在民间音乐里极受欢迎的原因**：
它**一个人就能同时给出旋律、和声与动态**，而且**携带方便**（自由簧的功劳）——
这正好满足舞蹈伴奏与街头演出的全部需求。

## 音域

```range
{"range":"F3–A6","common":"F3–C6","caption":"手风琴的音域（以钢琴键式常见形制为例）","caption_en":"Accordion range (a common piano-keyboard instrument)","note":"手风琴属气鸣乐器（自由簧）。常见音域约 F3–A6，视形制与键数而定；常用区 F3–C6。左侧低音与和弦键另有一组更低的音，但音域按右侧旋律键标注。"}
```

- **约 F3–A6**（视形制），常用区 F3–C6。
- **左侧低音键另有更低的音**，但音域通常按**右侧旋律键**标注。
- **它的音域取决于键数**：从两三个八度的小型琴到四个八度的大型琴都有。

## 音色与听辨

四条线索：

1. **明亮、带"簧"的甜味**。它的音色比[[instrument:harmonium|簧风琴]]更亮、更外放，
   因为簧组调校与共鸣箱都不同。
2. **力度层次极宽**。这是它与管风琴、簧风琴最明显的差别 ——
   它能做真正的渐强渐弱。
3. **音头由风箱控制**。改变推拉的速度与起始方式，就能做出不同的音头 —— 从"软起"到"硬起"。
4. **推与拉的音色可以不同**（视乐器与音栓设置）。
   演奏者会刻意安排乐句的推拉方向以利用这一点。

```audiolab
{"type":"instrument","gm":"Accordion","synth":"blown","phrase":["F3","A3","C4","F4","A4","C5"],"label":"手风琴的常用区：F3 到 C5","label_en":"The accordion's working register — F3 up to C5","hint":"注意音色的明亮与力度的可塑性 —— 它比簧风琴更外放，比管风琴自由得多","hint_en":"Hear the brightness and the dynamic flexibility — more outgoing than a harmonium, far freer than an organ."}
```

## 演奏技法

- **风箱控制是核心技术**。推拉的速度、力度与方向变化构成它的整个动态语言。
- **左手同时供气与弹和声**（这是协调难点）。
- **两种键式**：钢琴键式（右手像弹钢琴）与按钮式（更适合快速与远距离跳进，在东欧与俄罗斯常见）。
- **换向（bellows change）**：推与拉的切换可以在乐句中进行，
  熟练的演奏者让它几乎听不出来；也可以刻意利用它做音色变化。
- **抖风箱（bellows shake）**：快速推拉制造颤音与节奏效果 —— 现代与民间演奏都常用。

## 家族与近亲

| 乐器 | 发声体 | 供气 | 力度 | 便携性 |
|---|---|---|---|---|
| [[instrument:organ\|管风琴]] | 空气柱 | 机械鼓风 | 不可控 | 不可移动 |
| [[instrument:harmonium\|簧风琴]] | 自由簧 | 脚踏 | 有限可控 | 较重但可搬动 |
| **手风琴** | 自由簧 | **左臂手动** | **完全可控** | **便携** |
| [[instrument:harmonica\|口琴]] | 自由簧 | **嘴吹吸** | 可控 | **可放进口袋** |

**从这张表往下看，"便携性"逐步提升，"音域与音量"逐步下降** ——
这是一条清晰的工程取舍链：**自由簧让乐器变小，供气方式决定它的表现力与便携度的平衡。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 1820 年代 | 在欧洲出现（与中国**笙**的原理相关——笙是最早的自由簧乐器之一，18 世纪传入欧洲后启发了这类设计） |
| 19 世纪 | 形制快速演进；成为欧洲民间音乐与移民社区的常用乐器 |
| 19 世纪末—20 世纪初 | 随移民传播到美洲（探戈 · 蓝调 · 卡津音乐）与世界各地；在不同文化里形成各自的流派 |
| 20 世纪 | 在俄罗斯、东欧、法国、南美与中国都发展出独特传统；也有古典作品为它而写 |
| 20 世纪后期至今 | 民间、流行、影视配乐的常用乐器；按键式体系分化为多种地方标准 |

**它有一条很有意思的传播史**：
它的原理源头之一是**中国的笙**（18 世纪传入欧洲），
而它后来又在**探戈、卡津音乐、俄罗斯民谣与中国民间音乐**里各自开花 ——
**一件乐器的"血统"与它的"国籍"常常是两回事。**

## 常见误解

- **"手风琴是儿童乐器。"** 它有完整的古典与民间曲目，
  在探戈、卡津音乐与东欧民谣里是核心乐器，技术难度极高。
- **"它只能伴奏。"** 它的右手是完整的旋律键盘，左手是和声，
  一个人可以独立演奏完整的作品。
- **"它和簧风琴是一回事。"** 同为自由簧，但**供气方式不同**（手动 vs 脚踏），
  因此**力度控制能力差别很大**。
- **"它的音色就是"手风琴味"。"** 音栓与簧组配置不同，
  音色可以从"单簧的干净"到"多簧的浓厚"，差别相当大。
- **"它只能演奏民间音乐。"** 20 世纪以来有大量古典与当代作品为它写作，
  也有专门的国际比赛与独奏传统。

## 下一步

自由簧一族只剩 [[instrument:harmonica|口琴]] ——
它把"便携"推到极致：**供气方式从"手臂"变成了"呼吸"**。
三件放在一起，就构成"同一原理、三种送气方式、三种表现力"的完整对照。
:::

::: en
The accordion is the most **self-sufficient** member of the free-reed family: the left arm works the bellows
while the right hand plays melody and the left plays harmony — **one person simultaneously holds melody,
harmony and dynamic control.**

It also has a feature no other keyboard instrument has: **dynamics come directly from the bellows**, and that
control is **finer than an organ's and more flexible than a harmonium's.**

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** — the air sets **free reeds** vibrating |
| **Sub-type** | **Hand bellows** supply air · free reeds sound · melody keys on the right (piano or button) + bass and chord keys on the left |
| **Family** | Western · Keyboard (free-reed branch) · also a **world instrument** |
| **Bayin** | Not applicable — a Chinese system; the accordion is outside it |

> ⚠️ **One conceptual point**: **"where does the dynamics come from?" has three different answers among these
> aerophones.**
> - [[instrument:organ|Organ]]: air from a **mechanical blower** → dynamics **not controllable** (stops and a
>   swell box instead).
> - [[instrument:harmonium|Harmonium]]: air from the **foot** → **limited** dynamic control.
> - **Accordion**: air from **the left arm** → dynamics **fully controllable**, down to very fine crescendos.
>
> So "can it control dynamics" is decided not by the instrument's class but by **who supplies the air and
> whether that supply can be adjusted in real time** — which is what sets the accordion apart from the rest of
> the keyboard group: **it has the freest dynamic control of any keyboard instrument.**

## Structure: bellows, two sets of keys, reeds

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Accordion structure: central hand bellows, a melody keyboard on the right, bass and chord keys on the left, air driving free reeds inside">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Accordion — structure (left-arm air supply plus two key sets)</text>
  </g>
  <rect x="70" y="96" width="70" height="110" rx="5" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g stroke="#5B7FA8" stroke-width="1.2">
    <path d="M80,104 L80,198"/><path d="M92,104 L92,198"/><path d="M104,104 L104,198"/>
    <path d="M116,104 L116,198"/><path d="M128,104 L128,198"/>
  </g>
  <g fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.3">
    <rect x="84" y="100" width="7" height="20" rx="2"/>
    <rect x="96" y="100" width="7" height="20" rx="2"/>
    <rect x="120" y="100" width="7" height="20" rx="2"/>
  </g>
  <path d="M150,110 C176,110 176,192 150,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M176,110 C202,110 202,192 176,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M202,110 C228,110 228,192 202,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M228,110 C254,110 254,192 228,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M254,110 C280,110 280,192 254,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M280,110 C306,110 306,192 280,192" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <rect x="316" y="96" width="108" height="110" rx="5" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <g stroke="#9C7A3C" stroke-width="0.9">
    <path d="M328,108 L328,192"/><path d="M344,108 L344,192"/><path d="M360,108 L360,192"/>
    <path d="M376,108 L376,192"/><path d="M392,108 L392,192"/><path d="M408,108 L408,192"/>
  </g>
  <g fill="#0E0E10" stroke="#9C7A3C" stroke-width="1.2">
    <rect x="334" y="104" width="7" height="24" rx="2"/>
    <rect x="350" y="104" width="7" height="24" rx="2"/>
    <rect x="366" y="104" width="7" height="24" rx="2"/>
    <rect x="390" y="104" width="7" height="24" rx="2"/>
    <rect x="406" y="104" width="7" height="24" rx="2"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,80 L100,92"/><path d="M186,220 L104,212"/>
    <path d="M486,120 L430,132"/><path d="M486,204 L430,192"/>
    <path d="M186,264 L200,208"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="77" text-anchor="end" fill="#9C7A3C">Melody keys (right)</text>
    <text x="180" y="223" text-anchor="end">Bass and chord keys (left)</text>
    <text x="492" y="117" fill="#E07A3F">Hand bellows (centre)</text>
    <text x="492" y="207">Air and harmony</text>
    <text x="180" y="267" text-anchor="end" fill="#E07A3F">Left arm → live dynamics</text>
  </g>
  <text x="20" y="290" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Both directions of the bellows are worked by one arm, so a player can shape volume like breathing.</text>
</svg>
```

Three points:

1. **The left arm supplies air *and* plays harmony.** It works the bellows while also pressing bass and chord
   keys — **the hardest coordination in the instrument**.
2. **Two key sets, two traditions.** The melody side is either a **piano keyboard** or **buttons** (two distinct
   traditions); the left side holds preset bass and chord keys.
3. **Push and pull can differ in colour.** Many instruments switch reed sets between directions, so the same key
   sounds slightly different pushed and pulled — a feature composers exploit.

## Dynamic control: the freest in the keyboard group

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Who supplies the air and whether dynamics are controllable: the organ uses a blower, the harmonium the foot, the accordion the hand">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">"Where does the dynamics come from?" — three answers</text>
  </g>
  <rect x="50" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="134" y="80" text-anchor="middle" font-size="11" fill="#5B7FA8">Organ</text>
  <text x="134" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">mechanical blower</text>
  <text x="134" y="130" text-anchor="middle" font-size="10.5" fill="#6E6A64">dynamics: no</text>
  <text x="134" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">stops and swell box instead</text>
  <rect x="236" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <text x="320" y="80" text-anchor="middle" font-size="11" fill="#9C7A3C">Harmonium</text>
  <text x="320" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">foot</text>
  <text x="320" y="130" text-anchor="middle" font-size="10.5" fill="#9C7A3C">dynamics: limited</text>
  <text x="320" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">a little breathing</text>
  <rect x="422" y="56" width="168" height="120" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.8"/>
  <text x="506" y="80" text-anchor="middle" font-size="11" fill="#E07A3F">Accordion</text>
  <text x="506" y="106" text-anchor="middle" font-size="10.5" fill="#A9A49B">left arm on the bellows</text>
  <text x="506" y="130" text-anchor="middle" font-size="10.5" fill="#E07A3F">dynamics: full</text>
  <text x="506" y="152" text-anchor="middle" font-size="10.5" fill="#6E6A64">very fine crescendos</text>
  <text x="20" y="204" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">All three are air-driven (one air column, two free reeds) — the difference is entirely who supplies the air.</text>
  <text x="20" y="226" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">So dynamic control is not a matter of class but of whether the air supply can be adjusted in real time.</text>
</svg>
```

**That is also why the accordion is so popular in folk music**: **one person can supply melody, harmony and
dynamics**, and it is **portable** (thanks to the free reed) — exactly what dance accompaniment and street
performance require.

## Range

```range
{"range":"F3–A6","common":"F3–C6","caption":"手风琴的音域（以钢琴键式常见形制为例）","caption_en":"Accordion range (a common piano-keyboard instrument)","note":"手风琴属气鸣乐器（自由簧）。常见音域约 F3–A6，视形制与键数而定；常用区 F3–C6。左侧低音与和弦键另有一组更低的音，但音域按右侧旋律键标注。"}
```

- **About F3–A6** depending on the instrument; working register F3–C6.
- **The left-hand bass keys reach lower**, but the range is normally given for the right-hand melody keys.
- **Range follows key count**: from small instruments of two or three octaves to large ones of four.

## Timbre, and how to hear it

Four cues:

1. **Bright, with a reedy sweetness** — more outgoing and brighter than a [[instrument:harmonium|harmonium]],
   since reed voicing and resonator design differ.
2. **A very wide dynamic range** — the clearest difference from an organ or harmonium: it makes real crescendos.
3. **The attack comes from the bellows.** Changing how fast you start moving them gives anything from a soft to
   a hard onset.
4. **Push and pull can differ in colour** (depending on instrument and stop settings); players deliberately
   choose phrase directions to exploit it.

```audiolab
{"type":"instrument","gm":"Accordion","synth":"blown","phrase":["F3","A3","C4","F4","A4","C5"],"label":"手风琴的常用区：F3 到 C5","label_en":"The accordion's working register — F3 up to C5","hint":"注意音色的明亮与力度的可塑性 —— 它比簧风琴更外放，比管风琴自由得多","hint_en":"Hear the brightness and the dynamic flexibility — more outgoing than a harmonium, far freer than an organ."}
```

## Playing techniques

- **Bellows control is the core technique**: the speed, force and direction of the push and pull make up its
  entire dynamic language.
- **Air and harmony** — the coordination challenge.
- **Two keyboard systems**: piano-key (right hand plays as on a piano) and button (better for fast and wide
  leaps; common in Eastern Europe and Russia).
- **Bellows changes** can happen mid-phrase; a skilled player hides them, or deliberately uses them for colour.
- **Bellows shake**: rapid push-pull produces tremolo and rhythmic effects, used in both folk and modern
  playing.

## The family

| Instrument | Vibrating body | Air supplied by | Dynamics | Portability |
|---|---|---|---|---|
| [[instrument:organ\|Organ]] | air columns | mechanical blower | none | immovable |
| [[instrument:harmonium\|Harmonium]] | free reeds | foot | limited | heavy but movable |
| **Accordion** | free reeds | **left arm** | **full** | **portable** |
| [[instrument:harmonica\|Harmonica]] | free reeds | **breath** | controllable | **pocket-sized** |

**Reading down this table, portability rises while range and volume fall** — a clear engineering trade-off
chain: **the free reed makes instruments small, and the way air is supplied balances expression against
portability.**

## History

| Period | State |
|---|---|
| 1820s | appears in Europe (connected to the Chinese **sheng**, one of the earliest free-reed instruments, which reached Europe in the 18th century and inspired this family) |
| 19th c. | forms evolve quickly; becomes a common instrument in European folk music and immigrant communities |
| Late 19th–early 20th c. | travels with migration to the Americas (tango, blues, Cajun music) and worldwide, producing distinct regional traditions |
| 20th c. | develops unique traditions in Russia, Eastern Europe, France, South America and China; classical works are also written for it |
| Late 20th c. onward | a common instrument in folk, pop and film music; keyboard systems diverge into several local standards |

**It has an interesting transmission history**: one of its ancestral principles is the **Chinese sheng** (which
reached Europe in the 18th century), and the accordion later blossomed separately in **tango, Cajun music,
Russian folk and Chinese folk music** — **an instrument's ancestry and its "nationality" are often two
different things.**

## Common misconceptions

- **"The accordion is a children's instrument."** It has a full classical and folk repertoire, is central to
  tango, Cajun and Eastern European music, and demands considerable technique.
- **"It can only accompany."** The right hand is a complete melody keyboard and the left supplies harmony — one
  player can perform a whole work.
- **"It is the same as a harmonium."** Both use free reeds, but **the air supply differs** (hand versus foot), so
  **dynamic control differs greatly**.
- **"It has one accordion sound."** Stop and reed configurations vary widely, from a clean single reed to a thick
  multi-reed chorus.
- **"It only plays folk music."** Since the 20th century much classical and contemporary music has been written
  for it, with international competitions and a solo tradition.

## Next

One free-reed entry remains: the [[instrument:harmonica|harmonica]] — which takes portability to its limit,
changing the air supply from **an arm to breath**. The three together form a complete comparison of "**one
principle, three ways of supplying air, three expressive ranges**".
:::
