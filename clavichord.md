---
id: clavichord
site: inst
cat: I5
title: 击弦古钢琴
title_en: Clavichord
summary: 用铜片击弦的键盘乐器，力度可控、能做出后触颤音，但音量极小
summary_en: The keyboard instrument whose brass tangents strike the strings — dynamic, capable of vibrato, and extremely quiet
level: standard
tags: [乐器, 键盘, 西洋, 早期乐器]
tags_en: [instrument, keyboard, western, early]
alias: [击弦古钢琴, clavichord, 古钢琴, 小键琴]
order: 81
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:piano]]"
  - "[[instrument:harpsichord]]"
  - "[[instrument:organ]]"
  - "[[instrument:celesta]]"
instances:
  - pdmx-001939 | 六首圆号四重奏 Op.35 —— 古典早期的重奏语言，可对照击弦古钢琴所处的时代
  - pdmx-002479 | 为圆号与钢琴的四首小品 Op.35 —— 钢琴与独奏乐器的组合，可对照"大音量键盘"与"极小音量键盘"的差别
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— 室内乐编制，正是击弦古钢琴最合适的场合
sources:
  - 结构依通行制琴资料：**键盘**经杠杆驱动一枚**铜片（tangent）**从下方击弦；铜片击弦后**继续抵住弦**，同时充当弦的"上端"
  - 「击弦古钢琴属**弦鸣**乐器（键盘击弦）」依 Hornbostel–Sachs 分类
  - 「常见音域 C2–C6」依通行乐器资料
  - 「铜片持续抵弦这一结构使其能做 Bebung（后触颤音）—— 按键后再改变压力即可让音高微动；但音量极小，只能在小房间内使用」依乐器声学与演奏通识
updated: 2026-09-26
---

::: zh
击弦古钢琴是键盘组里最"私密"的一件：**它能控制力度，甚至能做颤音，
但音量小到你必须安静下来才听得见。**

它在三种早期键盘里占据一个奇特的位置：
**去掉了[[instrument:harpsichord|大键琴]]的限制（不能控制力度），
却付出了[[instrument:piano|钢琴]]没有付出的代价（几乎没有音量）。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）· **键盘击弦** |
| **次级类型** | 铜片（tangent）从下方击弦 · 击后仍抵住弦 · **音量极小** |
| **所属族** | 西洋 · 键盘（击弦支系的"轻量版"）· 同时是**早期乐器** |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，击弦古钢琴不在其中 |

> ⚠️ **一个概念上的要点**：**"能不能在按键之后继续改变声音"，是一种很少有人讨论的乐器属性。**
> - [[instrument:piano|钢琴]]：击弦的槌**立刻离开** → 按键后无法再改变这个音。
> - [[instrument:harpsichord|大键琴]]：拨子**立刻离开** → 同样无法。
> - **击弦古钢琴**：铜片**一直抵住弦** → 按键后继续加压，**可以让音高微动** → 得到颤音。
>
> 这个效果叫 **Bebung**（德语"颤动"），是键盘乐器里极罕见的"**后触**"（after-touch）。
> 它说明：**"发声之后还有没有控制权"，是一件乐器的结构性差异** ——
> 而这与"能不能控制力度"是**两个不同的问题**。

## 结构：铜片从下方击弦并持续抵住

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="击弦古钢琴的结构：键盘经杠杆驱动铜片从下方击弦，铜片击后仍抵住弦">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">击弦古钢琴 · 结构（铜片从下方击弦，并继续抵住弦）</text>
  </g>
  <rect x="70" y="150" width="230" height="30" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M88,150 L88,180"/><path d="M106,150 L106,180"/><path d="M124,150 L124,180"/>
    <path d="M142,150 L142,180"/><path d="M160,150 L160,180"/><path d="M178,150 L178,180"/>
    <path d="M196,150 L196,180"/><path d="M214,150 L214,180"/><path d="M232,150 L232,180"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2.6">
    <path d="M178,146 L178,106"/><path d="M232,146 L232,106"/>
  </g>
  <rect x="174" y="96" width="8" height="12" rx="3" fill="#9C7A3C"/>
  <rect x="228" y="96" width="8" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M120,88 L380,88" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M120,102 L380,102" stroke="#E07A3F" stroke-width="2" stroke-dasharray="5 3"/>
  <path d="M120,116 L380,116" stroke="#9C7A3C" stroke-width="2.4"/>
  <path d="M280,150 L330,124" stroke="#5B7FA8" stroke-width="3" stroke-dasharray="4 3"/>
  <path d="M322,120 L336,124 L324,134 Z" fill="#5B7FA8"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,66 L186,84"/><path d="M186,132 L186,128"/>
    <path d="M186,206 L186,186"/><path d="M486,100 L400,108"/>
    <path d="M486,196 L214,150"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="63" text-anchor="end">同一音的多根弦</text>
    <text x="180" y="135" text-anchor="end" fill="#9C7A3C">铜片（tangent）击弦</text>
    <text x="180" y="209" text-anchor="end">键盘与杠杆</text>
    <text x="492" y="97">铜片持续抵住弦</text>
    <text x="492" y="199">加压 → 音高微动</text>
  </g>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">铜片击弦后不离开 —— 它同时充当弦的"上端支点"，所以按键后的压力变化会直接改变音高。</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">这是它与钢琴最根本的机械差别：钢琴的槌击完就走，铜片却一直"按"着弦。</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">代价是：铜片的力量很小，声音几乎传不出两米。</text>
</svg>
```

三处要点：

1. **铜片（tangent）是"支点"兼"击弦器"**。它击弦后不离开，而是一直抵住 ——
   于是弦的**有效长度**由铜片位置决定，音高也因此由铜片位置设定。
2. **所以按键后的压力能改变音高** → 得到 Bebung（颤音）。
   这是钢琴与[[instrument:harpsichord|大键琴]]都做不到的。
3. **力量小、音量极小**。铜片能给出的能量有限，声音几乎传不出房间 ——
   它是一件**只能给自己听**的乐器。

## Bebung：键盘乐器里罕见的"后触"

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bebung 后触颤音：按键之后继续改变压力，使音高轻微起伏">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">按键之后还能改变声音吗？三种键盘的答案不同</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="2.6">
    <path d="M80,110 L200,110"/>
  </g>
  <text x="80" y="132" font-size="10.5" fill="#5B7FA8">钢琴：击完即走</text>
  <text x="80" y="154" font-size="10.5" fill="#6E6A64">按键后无法改变这个音</text>
  <text x="80" y="176" font-size="10.5" fill="#6E6A64">（余音只能靠踏板整体处理）</text>
  <g stroke="#9C7A3C" stroke-width="2.6">
    <path d="M280,110 L400,110"/>
  </g>
  <text x="280" y="132" font-size="10.5" fill="#9C7A3C">大键琴：拨完即回</text>
  <text x="280" y="154" font-size="10.5" fill="#6E6A64">按键后无法改变这个音</text>
  <text x="280" y="176" font-size="10.5" fill="#6E6A64">（力度也不可控）</text>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M470,110 C482,92 494,92 506,110 C518,128 530,128 542,110 C554,92 566,92 578,110"/>
  </g>
  <text x="470" y="132" font-size="10.5" fill="#E07A3F">击弦古钢琴：持续抵住</text>
  <text x="470" y="154" font-size="10.5" fill="#6E6A64">按键后继续加压 →</text>
  <text x="470" y="176" font-size="10.5" fill="#6E6A64">音高轻微起伏（Bebung）</text>
  <text x="20" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Bebung 不是装饰音，也不是"演奏者的颤音" —— 它是「乐器结构允许的一种实时控制」。</text>
  <text x="20" y="238" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">它在 18 世纪的德国音乐里被明确要求过（如 C. P. E. 巴赫的著作里就讨论过这种奏法）。</text>
  <text x="20" y="264" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">所以：「"能不能控制力度"与"发声后还有没有控制权"，是两个独立的结构问题。」</text>
</svg>
```

## 音域

```range
{"range":"C2–C6","common":"C2–C5","caption":"击弦古钢琴的音域","caption_en":"Clavichord range","note":"击弦古钢琴属弦鸣乐器（键盘击弦）。常见音域约 C2–C6（不同形制差别较大）；常用区 C2–C5。它是三种早期键盘里音域较窄、音量最小的一件。"}
```

- **约 C2–C6**（视形制），比[[instrument:harpsichord|大键琴]]窄，比[[instrument:piano|钢琴]]窄得多。
- **常用区 C2–C5**：它的音乐几乎全在这里，因为高音区更细弱。
- **音域窄不是问题**：它的曲目主要是**教学与私人演奏**用的 ——
  巴赫的儿子们（C. P. E. 巴赫、W. F. 巴赫）为它写了大量作品。

## 音色与听辨

四条线索：

1. **极轻、极近、极私密**。它的音量小到人声可以盖过它 ——
   所以它从来不是音乐厅乐器。
2. **音色柔软、有"金属的细"**。铜片击弦的音头比钢琴柔，比大键琴"软"。
3. **余音极短**。铜片持续抵住弦，振动被阻尼 → 声音一击即收。
4. **能做 Bebung**。这是它唯一一个别的键盘乐器做不到的效果。

```audiolab
{"type":"instrument","gm":"Harpsichord","synth":"struck","phrase":["C3","E3","G3","B3","D4"],"label":"击弦古钢琴的常用区：C3 到 D4","label_en":"The clavichord's working register — C3 up to D4","hint":"注意音量极小而柔和、余音极短 —— 它是一件给自己听的乐器","hint_en":"Hear how quiet, soft and short-lived it is — an instrument for the player alone."}
```

## 演奏技法

- **触键直接控制力度**（这一点与[[instrument:piano|钢琴]]同侧，与[[instrument:harpsichord|大键琴]]相反）。
- **Bebung（后触颤音）**：按键后继续加压使音高微动。
- **音量限制决定了它的使用场合**：私人演奏、教学、小型室内乐 —— 不需要"传出去"。
- **它的触键技术极细**。因为音量太小，任何不均匀都会被听出来 ——
  所以它被认为是**训练手指控制力**的好乐器。

## 家族与近亲

| 乐器 | 触发 | 力度可控 | 后触可控 | 音量 | 音域 |
|---|---|---|---|---|---|
| [[instrument:piano\|钢琴]] | 击弦（毡槌） | **可** | 不可 | 大 | A0–C8 |
| [[instrument:harpsichord\|大键琴]] | 拨弦 | 不可 | 不可 | 中 | F1–F6 |
| **击弦古钢琴** | 击弦（铜片） | **可** | **可（Bebung）** | **极小** | C2–C6 |
| [[instrument:organ\|管风琴]] | 气流 | 不可 | 不可（但可持续） | 极大 | C2–C7 |

**四种键盘乐器，"可控性"的组合各不相同**：
钢琴与击弦古钢琴可控力度；击弦古钢琴还能做后触；管风琴的音**可以一直持续**；
大键琴则两头都不可控，但余音短、音型清楚。

## 历史演变

| 时期 | 状态 |
|---|---|
| 14—15 世纪 | 出现早期的击弦键盘乐器；铜片击弦的原理逐步定型 |
| 16—17 世纪 | 成为家庭与教学用的小型键盘乐器；形制趋于紧凑（如"束腰式"） |
| **18 世纪** | **它的黄金期**：C. P. E. 巴赫等人为它写了大量作品，并讨论过 Bebung 的奏法 |
| 18 世纪末 | 被[[instrument:piano\|钢琴]]取代（后者力度范围大得多，能上厅堂） |
| 19 世纪 | 退为小众与复古乐器 |
| 20 世纪 | 古乐运动复兴；今天仍有制作者与演奏者 |

**它与大键琴的退场原因不同**：
大键琴输在"**不能控制力度**"，击弦古钢琴的力度控制其实很好 ——
它输在"**音量太小**"。**同一场乐器更替，有两套不同的解释。**

## 常见误解

- **"击弦古钢琴就是"小钢琴"。"** 结构不同（铜片 vs 毡槌），
  而且它有一项钢琴没有的能力：**后触颤音**。
- **"它的音量小是因为弦少。"** 音量小是**铜片能给出的能量有限**决定的；
  弦的数量与钢琴类似（同音多弦）。
- **"它没有表现力。"** 它的力度层次很细，还能做 Bebung ——
  它的限制是**音量**，不是**表现力**。
- **"它和大键琴一样不能控制力度。"** 相反，它**能**控制力度；
  不能控制力度的是大键琴。
- **"它只能在博物馆里听。"** 20 世纪以来有仿古乐器与现代制作，
  当代也有人在演奏与录音。

## 下一步

键盘组还剩 4 条：[[instrument:organ|管风琴]] · [[instrument:harmonium|簧风琴]] ·
[[instrument:accordion|手风琴]] · [[instrument:harmonica|口琴]]。
后三件同属"**自由簧**"一类 —— 它们会与管风琴形成"**同是气鸣，但发声体不同**"的对照。
:::

::: en
The clavichord is the most **private** instrument in the keyboard group: **it controls dynamics, and can even
produce vibrato, but it is so quiet you must fall silent to hear it.**

Among the three early keyboards it occupies a peculiar position: **it removes the
[[instrument:harpsichord|harpsichord]]'s limitation (no dynamic control) while paying a price the
[[instrument:piano|piano]] never paid (almost no volume).**

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** · **keyboard-struck** |
| **Sub-type** | A brass tangent strikes the string from below and **stays in contact** · **extremely quiet** |
| **Family** | Western · Keyboard (the "light" struck branch) · also an **early instrument** |
| **Bayin** | Not applicable — a Chinese system; the clavichord is outside it |

> ⚠️ **One conceptual point**: **"can you keep changing the sound after the key is down?" is an instrument
> property rarely discussed.**
> - [[instrument:piano|Piano]]: the hammer **leaves at once** → nothing can change afterwards.
> - [[instrument:harpsichord|Harpsichord]]: the plectrum **releases at once** → likewise.
> - **Clavichord**: the tangent **stays pressed** → extra pressure after the key is down **moves the pitch** →
>   vibrato.
>
> The effect is called **Bebung** (German, "trembling") and is a rare **after-touch** in keyboard playing. It
> shows that **"is there control after the sound has started" is a structural difference** — and a **different
> question** from "can it control dynamics".

## Structure: a tangent strikes from below and stays

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Clavichord structure: the key drives a brass tangent that strikes the string from below and stays in contact">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Clavichord — structure (a tangent strikes from below and stays pressed)</text>
  </g>
  <rect x="70" y="150" width="230" height="30" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M88,150 L88,180"/><path d="M106,150 L106,180"/><path d="M124,150 L124,180"/>
    <path d="M142,150 L142,180"/><path d="M160,150 L160,180"/><path d="M178,150 L178,180"/>
    <path d="M196,150 L196,180"/><path d="M214,150 L214,180"/><path d="M232,150 L232,180"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="2.6">
    <path d="M178,146 L178,106"/><path d="M232,146 L232,106"/>
  </g>
  <rect x="174" y="96" width="8" height="12" rx="3" fill="#9C7A3C"/>
  <rect x="228" y="96" width="8" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M120,88 L380,88" stroke="#5B7FA8" stroke-width="2.4"/>
  <path d="M120,102 L380,102" stroke="#E07A3F" stroke-width="2" stroke-dasharray="5 3"/>
  <path d="M120,116 L380,116" stroke="#9C7A3C" stroke-width="2.4"/>
  <path d="M280,150 L330,124" stroke="#5B7FA8" stroke-width="3" stroke-dasharray="4 3"/>
  <path d="M322,120 L336,124 L324,134 Z" fill="#5B7FA8"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,66 L186,84"/><path d="M186,132 L186,128"/>
    <path d="M186,206 L186,186"/><path d="M486,100 L400,108"/>
    <path d="M486,196 L214,150"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="63" text-anchor="end">Several strings per note</text>
    <text x="180" y="135" text-anchor="end" fill="#9C7A3C">Tangent strikes the string</text>
    <text x="180" y="209" text-anchor="end">Keys and levers</text>
    <text x="492" y="97">Tangent stays in contact</text>
    <text x="492" y="199">More pressure → pitch</text>
  </g>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The tangent does not leave: it also serves as the string's upper stop, so pressure changes pitch.</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">That is the fundamental mechanical difference from a piano, whose hammer strikes and leaves at once.</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">The price: a tangent delivers very little energy, so the sound barely carries two metres.</text>
</svg>
```

Three points:

1. **The tangent is both striker and stop.** It stays in contact, so the string's **speaking length** — and
   hence the pitch — is set by the tangent's position.
2. **Pressure after the strike therefore changes pitch** → Bebung. Neither a piano nor a
   [[instrument:harpsichord|harpsichord]] can do this.
3. **Little energy, tiny volume.** A tangent cannot deliver much, so the sound barely leaves the room — an
   instrument **you play for yourself**.

## Bebung: a rare "after-touch"

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bebung after-touch: continued pressure after the key is down makes the pitch waver">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Can the sound be changed after the key is down? Three keyboards differ</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="2.6">
    <path d="M80,110 L200,110"/>
  </g>
  <text x="80" y="132" font-size="10.5" fill="#5B7FA8">Piano: strikes and leaves</text>
  <text x="80" y="154" font-size="10.5" fill="#6E6A64">nothing can change that note</text>
  <text x="80" y="176" font-size="10.5" fill="#6E6A64">(only the pedal acts globally)</text>
  <g stroke="#9C7A3C" stroke-width="2.6">
    <path d="M280,110 L400,110"/>
  </g>
  <text x="280" y="132" font-size="10.5" fill="#9C7A3C">Harpsichord: plucks and returns</text>
  <text x="280" y="154" font-size="10.5" fill="#6E6A64">nothing can change that note</text>
  <text x="280" y="176" font-size="10.5" fill="#6E6A64">(nor its dynamics)</text>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M470,110 C482,92 494,92 506,110 C518,128 530,128 542,110 C554,92 566,92 578,110"/>
  </g>
  <text x="470" y="132" font-size="10.5" fill="#E07A3F">Clavichord: stays pressed</text>
  <text x="470" y="154" font-size="10.5" fill="#6E6A64">more pressure →</text>
  <text x="470" y="176" font-size="10.5" fill="#6E6A64">pitch wavers (Bebung)</text>
  <text x="20" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Bebung is neither an ornament nor a player's "vibrato" — it is a 「real-time control the mechanism allows」.</text>
  <text x="20" y="238" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">It was explicitly required in 18th-century German music (C. P. E. Bach's writings discuss the technique).</text>
  <text x="20" y="264" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">So: 「"can it control dynamics" and "is there control after the attack" are two independent questions.」</text>
</svg>
```

## Range

```range
{"range":"C2–C6","common":"C2–C5","caption":"击弦古钢琴的音域","caption_en":"Clavichord range","note":"击弦古钢琴属弦鸣乐器（键盘击弦）。常见音域约 C2–C6（不同形制差别较大）；常用区 C2–C5。它是三种早期键盘里音域较窄、音量最小的一件。"}
```

- **About C2–C6** depending on the instrument — narrower than a [[instrument:harpsichord|harpsichord]] and far
  narrower than a [[instrument:piano|piano]].
- **The working register is C2–C5**; almost all its music sits there, since the top is thinner still.
- **A narrow range is not a problem**: its repertoire is mainly for **teaching and private playing** — Bach's
  sons (C. P. E. and W. F. Bach) wrote extensively for it.

## Timbre, and how to hear it

Four cues:

1. **Very soft, very close, very private.** It is quiet enough that a voice can cover it — never a concert-hall
   instrument.
2. **A soft tone with a fine metallic edge**: the tangent's attack is gentler than a piano's and less brittle
   than a harpsichord's.
3. **A very short tail**: the tangent keeps damping the string, so the note stops almost at once.
4. **Bebung**, the one effect no other keyboard here can produce.

```audiolab
{"type":"instrument","gm":"Harpsichord","synth":"struck","phrase":["C3","E3","G3","B3","D4"],"label":"击弦古钢琴的常用区：C3 到 D4","label_en":"The clavichord's working register — C3 up to D4","hint":"注意音量极小而柔和、余音极短 —— 它是一件给自己听的乐器","hint_en":"Hear how quiet, soft and short-lived it is — an instrument for the player alone."}
```

## Playing techniques

- **Touch directly controls dynamics** — the same side as the [[instrument:piano|piano]], the opposite of the
  [[instrument:harpsichord|harpsichord]].
- **Bebung**: continued pressure after the key is down moves the pitch.
- **Volume limits its setting**: private playing, teaching, small chamber music — nothing that must carry.
- **Its touch technique is extremely fine.** Precisely because it is so quiet, any unevenness is audible —
  which is why it is regarded as a good instrument for **training finger control**.

## The family

| Instrument | Trigger | Dynamics | After-touch | Volume | Range |
|---|---|---|---|---|---|
| [[instrument:piano\|Piano]] | struck (felt) | **yes** | no | large | A0–C8 |
| [[instrument:harpsichord\|Harpsichord]] | plucked | no | no | medium | F1–F6 |
| **Clavichord** | struck (tangent) | **yes** | **yes (Bebung)** | **tiny** | C2–C6 |
| [[instrument:organ\|Organ]] | air | no | no (but sustains) | huge | C2–C7 |

**Four keyboards, four different combinations of controllability**: the piano and the clavichord control
dynamics; the clavichord also has after-touch; the organ's sound **can be sustained indefinitely**; the
harpsichord controls neither, but its short tail keeps figuration clear.

## History

| Period | State |
|---|---|
| 14th–15th c. | early struck keyboard instruments appear; the tangent principle settles |
| 16th–17th c. | becomes a small household and teaching keyboard; forms grow compact (including "fretted" types) |
| **18th c.** | **its golden age**: C. P. E. Bach and others write extensively for it and discuss Bebung |
| Late 18th c. | replaced by the [[instrument:piano|piano]] (whose far wider dynamic range could fill a hall) |
| 19th c. | retreats to a niche and to revival interest |
| 20th c. | revived by the early-music movement; makers and players remain active today |

**Its departure has a different cause from the harpsichord's**: the harpsichord lost because it **could not
control dynamics**; the clavichord controls them well and lost because it is **too quiet**. **One round of
instrument replacement, two different explanations.**

## Common misconceptions

- **"A clavichord is a small piano."** The mechanism differs (tangent versus felt hammer), and it has an ability
  the piano lacks: **after-touch vibrato**.
- **"It is quiet because it has few strings."** The quietness follows from **how little energy a tangent can
  deliver**; the string count is similar to a piano's.
- **"It has no expression."** Its dynamic layering is fine and it adds Bebung — its limitation is **volume**, not
  **expression**.
- **"Like a harpsichord, it cannot control dynamics."** The opposite: it **can**; the harpsichord cannot.
- **"You can only hear it in museums."** Since the 20th century there are copies and modern instruments, and
  performers record on it today.

## Next

Four keyboard entries remain: the [[instrument:organ|organ]], the [[instrument:harmonium|harmonium]], the
[[instrument:accordion|accordion]] and the [[instrument:harmonica|harmonica]]. The last three belong to the
**free-reed** family — and they form a contrast with the organ as **aerophones whose vibrating body differs**.
:::
