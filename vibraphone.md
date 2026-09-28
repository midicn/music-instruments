---
id: vibraphone
site: inst
cat: I4
title: 颤音琴
title_en: Vibraphone
summary: 金属条加共鸣管与旋转阀的体鸣乐器，音色闪烁，"颤音"其实是音量起伏
summary_en: Metal bars over resonators with rotating vanes — a shimmering idiophone whose "vibrato" is really amplitude
level: standard
tags: [乐器, 打击, 西洋, 爵士]
tags_en: [instrument, percussion, western, jazz]
alias: [颤音琴, vibraphone, vibes, 颤音琴（铁琴）]
order: 64
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:marimba]]"
  - "[[instrument:glockenspiel]]"
  - "[[instrument:xylophone]]"
  - "[[instrument:tubular-bells]]"
instances:
  - pdmx-002767 | 赖希《Six Marimbas》—— **马林巴**演奏；同族的木质版本，可对照金属条的差别
  - pdmx-000746 | 霍尔斯特《行星组曲》Op.32 —— 配器里打击乐丰富，金属条一族的用法可在此听到
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里颤音琴类乐器的用法
sources:
  - 结构依通行制琴资料：**铝合金条**按音高排列，下方各有**共鸣管**；管内装有**旋转阀（vanes）**，由电机带动同步旋转
  - 「颤音琴属**体鸣**的有音高乐器」依 Hornbostel–Sachs 分类
  - 「常见音域 F3–F6（三组）」依通行乐器资料
  - 「共鸣管内的旋转阀周期性遮挡管口，产生的是**音量（振幅）周期性变化**，即 tremolo；不是音高颤动（vibrato）」依乐器声学
updated: 2026-09-26
---

::: zh
颤音琴是[[instrument:marimba|马林巴]]的"金属版"：结构几乎一样（琴条 + 共鸣管），
但琴条换成**铝合金**，并且共鸣管里多了一组**旋转阀**。

它身上有一个名不副实的地方，值得单独说清：
**它的"颤音"颤的是音量，不是音高。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **体鸣**（Idiophone）· **有音高** |
| **次级类型** | 铝合金条按音高排列 · 共鸣管内装**旋转阀**（电机驱动） · 用软头或硬头槌击奏 |
| **所属族** | 西洋 · 打击（体鸣·木条族的金属支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，颤音琴不在其中 |

> ⚠️ **一个概念上的要点**：**"颤音琴"这个名字其实不准确。**
> - **vibrato（颤音）**：音**高**的快速起伏 —— 弦乐、人声、管乐常用。
> - **tremolo（颤吟）**：音**量**的快速起伏 —— 颤音琴管内的旋转阀做的是这个。
>
> 电机带动共鸣管内的阀片同步旋转，周期性遮挡管口 →
> **音量按固定频率起伏** → 听感是"闪烁"，而不是"音在抖"。
> 所以它的英文名 vibraphone 也是沿用了错的名字 ——
> **乐器名称常常是历史遗留，不能当成声学描述来读**（与[[instrument:english-horn|英国管]]那条同类）。

## 结构：金属条 + 共鸣管 + 旋转阀

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="颤音琴的结构：铝合金琴条、下方共鸣管、管内的旋转阀与驱动电机">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">颤音琴 · 结构（金属条 + 共鸣管 + 旋转阀）</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5">
    <rect x="130" y="84" width="58" height="24" rx="3" fill="#0E0E10"/>
    <rect x="192" y="84" width="48" height="24" rx="3" fill="#0E0E10"/>
    <rect x="244" y="84" width="40" height="24" rx="3" fill="#0E0E10"/>
    <rect x="288" y="84" width="34" height="24" rx="3" fill="#0E0E10"/>
    <rect x="326" y="84" width="30" height="24" rx="3" fill="#0E0E10"/>
  </g>
  <g stroke="#343439" stroke-width="2.4">
    <path d="M118,68 L404,68"/><path d="M118,130 L404,130"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5" fill="#17171A">
    <rect x="142" y="138" width="24" height="128" rx="4"/>
    <rect x="198" y="138" width="24" height="118" rx="4"/>
    <rect x="248" y="138" width="24" height="108" rx="4"/>
    <rect x="292" y="138" width="24" height="100" rx="4"/>
    <rect x="330" y="138" width="24" height="94" rx="4"/>
  </g>
  <g stroke="#E07A3F" stroke-width="3.4" stroke-linecap="round">
    <path d="M142,168 L166,186"/><path d="M198,164 L222,182"/>
    <path d="M248,160 L272,178"/><path d="M292,158 L316,176"/>
    <path d="M330,156 L354,174"/>
  </g>
  <circle cx="430" cy="200" r="17" fill="none" stroke="#E07A3F" stroke-width="2.6"/>
  <path d="M430,183 L430,217" stroke="#E07A3F" stroke-width="2.6"/>
  <path d="M404,232 L456,232" stroke="#6E6A64" stroke-width="3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,54 L186,78"/><path d="M186,158 L186,146"/>
    <path d="M186,282 L186,266"/><path d="M486,146 L470,164"/>
    <path d="M486,232 L452,232"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="51" text-anchor="end" fill="#5B7FA8">铝合金琴条</text>
    <text x="180" y="161" text-anchor="end">共鸣管</text>
    <text x="180" y="285" text-anchor="end" fill="#E07A3F">管内旋转阀（同步转动）</text>
    <text x="492" y="143">阀片遮挡管口</text>
    <text x="492" y="235">驱动电机</text>
  </g>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所有共鸣管里的阀片由同一台电机带动，因此整台琴的"起伏"是同步的 —— 这正是它音色统一的原因。</text>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">关掉电机，它就变成一台普通的金属条琴。</text>
</svg>
```

三处要点：

1. **金属条 + 共鸣管**（与马林巴同构），所以它同时有金属的亮与共鸣管的暖。
2. **旋转阀由一台电机同步驱动**。整台琴的阀片同步转动 →
   **所有音的起伏相位一致** → 音色统一而不混乱。
3. **可以关掉**。关掉电机就是一台普通的金属条琴 —— 所以"颤音"是**可选的效果**，
   不是乐器不可分割的属性。

## "颤音"到底颤的是什么

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="颤音与颤吟的对比：颤音是音高起伏，颤吟是音量起伏；颤音琴的旋转阀做的是后者">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">两个名字容易混，波形完全不同</text>
  </g>
  <text x="160" y="58" text-anchor="middle" font-size="11" fill="#5B7FA8">vibrato · 音高起伏</text>
  <path d="M60,120 C80,80 100,80 120,120 C140,160 160,160 180,120 C200,80 220,80 240,120 C260,160 260,160 260,140"
        fill="none" stroke="#5B7FA8" stroke-width="3"/>
  <path d="M60,120 L260,120" stroke="#343439" stroke-width="1" stroke-dasharray="3 3"/>
  <text x="160" y="188" text-anchor="middle" font-size="10.5" fill="#A9A49B">频率上下摆动，音高在抖</text>
  <text x="160" y="210" text-anchor="middle" font-size="10.5" fill="#5B7FA8">弦乐 · 人声 · 管乐常用</text>
  <text x="160" y="232" text-anchor="middle" font-size="10.5" fill="#6E6A64">听起来："音在颤"</text>
  <text x="160" y="258" text-anchor="middle" font-size="10.5" fill="#E07A3F">颤音琴不做这个</text>
  <text x="480" y="58" text-anchor="middle" font-size="11" fill="#E07A3F">tremolo · 音量起伏</text>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M380,120 L392,88"/><path d="M392,88 L404,152"/><path d="M404,152 L416,88"/>
    <path d="M416,88 L428,152"/><path d="M428,152 L440,88"/><path d="M440,88 L452,152"/>
    <path d="M452,152 L464,88"/><path d="M464,88 L476,152"/><path d="M476,152 L488,88"/>
    <path d="M488,88 L500,152"/><path d="M500,152 L512,120"/>
  </g>
  <path d="M380,120 L512,120" stroke="#343439" stroke-width="1" stroke-dasharray="3 3"/>
  <text x="480" y="188" text-anchor="middle" font-size="10.5" fill="#A9A49B">音高不变，音量在起伏</text>
  <text x="480" y="210" text-anchor="middle" font-size="10.5" fill="#E07A3F">旋转阀遮挡管口造成的</text>
  <text x="480" y="232" text-anchor="middle" font-size="10.5" fill="#6E6A64">听起来："音在闪"</text>
  <text x="480" y="258" text-anchor="middle" font-size="10.5" fill="#E07A3F">颤音琴做的就是它</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">两个词在中文里都常译作"颤音"，但一个是频率调制、一个是振幅调制 —— 听感完全不同。</text>
</svg>
```

**这条区分在配器上很实用**：
写"要颤音"时，如果是[[instrument:violin|弦乐]]，写的是音高起伏；
如果是颤音琴，写的是**开电机**（音量起伏）。两者的记谱与听感都不一样。

## 音域

```range
{"range":"F3–F6","common":"C4–C5","caption":"颤音琴的音域","caption_en":"Vibraphone range","note":"颤音琴属体鸣的有音高乐器。常见音域 F3–F6（三组）。共鸣管内的旋转阀产生周期性的音量起伏 —— 严格说这是振幅调制（tremolo），不是音高颤动。"}
```

- **F3–F6**（三组），比[[instrument:marimba|马林巴]]窄得多，也比[[instrument:xylophone|木琴]]低一些。
- **常用区 C4–C5**：这一段它的金属光泽最舒服，也是爵士里最常停留的地方。
- **音域窄是它的局限** —— 但它靠音色与和声能力补回了这一点。

## 音色与听辨

四条线索：

1. **金属光泽 + 长余音**。它比马林巴更"亮"、更"冷"，余音也更长。
2. **"闪烁"是它的签名**（开电机时）。这种周期性的音量起伏很难与其他乐器混淆。
3. **延音踏板可控制余音**。多数颤音琴有踏板，踩下则余音相互叠加 ——
   这让它能像钢琴一样"踩踏板弹和弦"。
4. **既能当旋律乐器，也能当和声乐器**。四槌技术 + 踏板使它在爵士里常承担和声层。

```audiolab
{"type":"instrument","gm":"Vibraphone","synth":"metal","phrase":["C4","E4","G4","C5","E5","G5"],"label":"颤音琴的常用区：C4 到 G5","label_en":"The vibraphone's working register — C4 up to G5","hint":"注意音色的金属光泽与余音 —— 以及「闪烁」感来自音量的周期性起伏","hint_en":"Hear the metallic sheen and the long tail — and how the shimmer comes from periodic changes in loudness."}
```

## 演奏技法

- **四槌技术**（与马林巴共用一套技法体系）。
- **踏板（damper pedal）**：控制余音长短，踩下则音相互叠加。
- **电机的开关与转速**：可以根据音乐需要关掉或调节起伏速度。
- **槌头选择**：软硬不同的槌头配合电机，能做出从"冷冽"到"朦胧"的多种质感。

## 家族与近亲

| 乐器 | 琴条 | 共鸣管 | 附加装置 | 音域 | 音色 |
|---|---|---|---|---|---|
| [[instrument:xylophone\|木琴]] | 硬木 | 短 | — | F4–C8 | 干、脆 |
| [[instrument:marimba\|马林巴]] | 软木 | 长 | — | C2–C7 | 暖、厚 |
| **颤音琴** | **铝合金** | 长 | **旋转阀 + 踏板** | F3–F6 | 金属、闪烁 |
| [[instrument:glockenspiel\|钟琴]] | 钢 | — | — | G5–C8 | 极亮、通透 |
| [[instrument:celesta\|钢片琴]] | 钢片（键盘） | 共鸣箱 | 键盘击奏 | C3–C8 | 玻璃般 |

**"琴条一族"到这里已经有五件** —— 它们的区别可以完全归结为
**材料、共鸣管长度、附加装置**三项。这是全站"同构不同音色"最完整的一组。

## 历史演变

| 时期 | 状态 |
|---|---|
| 1916 年（美国） | 由 Herman Winterhoff 等人在金属条琴基础上加装共鸣管与旋转阀 → 现代颤音琴成型 |
| 1920—1930 年代 | 进入**爵士乐**；成为爵士颤音琴演奏家的乐器 |
| 20 世纪中期 | 在爵士里确立了独奏与和声双重角色；四槌技术普及 |
| 20 世纪后期 | 进入流行、影视配乐与当代古典；电机的使用方式也更灵活 |
| 20 世纪后期至今 | 爵士、流行、影视、当代音乐的通用乐器 |

**它是"琴条一族里最年轻的一件"**（1916 年才定型）——
而它加装旋转阀的思路，也说明**打击乐器可以被"现代化"**：
不是改材料，而是增加可控变量。

## 常见误解

- **"颤音琴的颤音是音高在抖。"** 恰恰相反：旋转阀做的是**音量起伏**（tremolo），
  音高不变。名字是历史遗留。
- **"它和木琴是一回事。"** 同族但材料不同（金属 vs 木），且多出旋转阀与踏板 ——
  音色与用法都不同。
- **"它只有三组音域，所以用处有限。"** 它靠音色与和声能力立足，
  在爵士里是很重要的独奏与伴奏乐器。
- **"旋转阀只是装饰。"** 它改变了颤音琴的**音色身份** ——
  关掉电机后它就不再是"颤音琴"了。
- **"它不能当独奏乐器。"** 四槌技术 + 踏板让它能独立演奏旋律与和声，有完整的独奏文献。

## 下一步

金属一族还有三件：[[instrument:glockenspiel|钟琴]]（钢条、极亮）、
[[instrument:tubular-bells|管钟]]（悬挂金属管、钟声）、
[[instrument:celesta|钢片琴]]（键盘击奏"钢片"、玻璃般）。
再往外是 [[instrument:gong|锣]] —— 同样是金属整体振动，但无音高、余音极长。
:::

::: en
The vibraphone is the [[instrument:marimba|marimba]]'s "metal version": nearly the same structure (bars
over resonators), but the bars are **aluminium** and the resonators hold a set of **rotating vanes**.

It carries a misnomer worth stating plainly: **its "vibrato" modulates loudness, not pitch.**

| Classification | Value |
|---|---|
| **HS class** | **Idiophone** · **pitched** |
| **Sub-type** | Aluminium bars arranged by pitch · **rotating vanes** inside the resonators (motor-driven) · struck with soft or hard mallets |
| **Family** | Western · Percussion (idiophone; metal branch of the bar family) |
| **Bayin** | Not applicable — a Chinese system; the vibraphone is outside it |

> ⚠️ **One conceptual point**: **"vibraphone" is a misnomer.**
> - **vibrato**: rapid variation of **pitch** — used by strings, voices and winds.
> - **tremolo**: rapid variation of **loudness** — what the vanes actually do.
>
> A motor turns the vanes in the resonators so they periodically cover the tube openings →
> **loudness pulses at a fixed rate** → the effect is a shimmer, not a wobble.
> The English name inherited the same mistake — **instrument names are often historical leftovers and must
> not be read as acoustic descriptions** (the same as the [[instrument:english-horn|English horn]]).

## Structure: metal bars, resonators and vanes

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Vibraphone structure: aluminium bars, resonators below, rotating vanes inside them and a drive motor">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Vibraphone — structure (metal bars, resonators, rotating vanes)</text>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5">
    <rect x="130" y="84" width="58" height="24" rx="3" fill="#0E0E10"/>
    <rect x="192" y="84" width="48" height="24" rx="3" fill="#0E0E10"/>
    <rect x="244" y="84" width="40" height="24" rx="3" fill="#0E0E10"/>
    <rect x="288" y="84" width="34" height="24" rx="3" fill="#0E0E10"/>
    <rect x="326" y="84" width="30" height="24" rx="3" fill="#0E0E10"/>
  </g>
  <g stroke="#343439" stroke-width="2.4">
    <path d="M118,68 L404,68"/><path d="M118,130 L404,130"/>
  </g>
  <g stroke="#5B7FA8" stroke-width="1.5" fill="#17171A">
    <rect x="142" y="138" width="24" height="128" rx="4"/>
    <rect x="198" y="138" width="24" height="118" rx="4"/>
    <rect x="248" y="138" width="24" height="108" rx="4"/>
    <rect x="292" y="138" width="24" height="100" rx="4"/>
    <rect x="330" y="138" width="24" height="94" rx="4"/>
  </g>
  <g stroke="#E07A3F" stroke-width="3.4" stroke-linecap="round">
    <path d="M142,168 L166,186"/><path d="M198,164 L222,182"/>
    <path d="M248,160 L272,178"/><path d="M292,158 L316,176"/>
    <path d="M330,156 L354,174"/>
  </g>
  <circle cx="430" cy="200" r="17" fill="none" stroke="#E07A3F" stroke-width="2.6"/>
  <path d="M430,183 L430,217" stroke="#E07A3F" stroke-width="2.6"/>
  <path d="M404,232 L456,232" stroke="#6E6A64" stroke-width="3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,54 L186,78"/><path d="M186,158 L186,146"/>
    <path d="M186,282 L186,266"/><path d="M486,146 L470,164"/>
    <path d="M486,232 L452,232"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="51" text-anchor="end" fill="#5B7FA8">Aluminium bars</text>
    <text x="180" y="161" text-anchor="end">Resonators</text>
    <text x="180" y="285" text-anchor="end" fill="#E07A3F">Rotating vanes inside</text>
    <text x="492" y="143">Vanes over the mouth</text>
    <text x="492" y="235">Drive motor</text>
  </g>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">One motor drives every vane, so the whole instrument pulses in phase — which is why its colour stays unified.</text>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Switch the motor off and it becomes an ordinary metal-bar instrument: the shimmer is optional.</text>
</svg>
```

Three points:

1. **Metal bars over resonators** (the same structure as a marimba), giving it both metal brightness and
   resonator warmth.
2. **One motor drives all the vanes together**, so every note pulses in phase → a unified colour rather than a
   muddle.
3. **It can be switched off.** Without the motor it is simply a metal-bar instrument — the shimmer is an
   **optional effect**, not an inseparable property.

## What the "vibrato" actually modulates

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Vibrato and tremolo compared: vibrato varies pitch while tremolo varies loudness; the vibraphone's vanes do the latter">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Two easily confused names, two completely different waveforms</text>
  </g>
  <text x="160" y="58" text-anchor="middle" font-size="11" fill="#5B7FA8">vibrato · pitch varies</text>
  <path d="M60,120 C80,80 100,80 120,120 C140,160 160,160 180,120 C200,80 220,80 240,120 C260,160 260,160 260,140"
        fill="none" stroke="#5B7FA8" stroke-width="3"/>
  <path d="M60,120 L260,120" stroke="#343439" stroke-width="1" stroke-dasharray="3 3"/>
  <text x="160" y="188" text-anchor="middle" font-size="10.5" fill="#A9A49B">frequency swings; the note wobbles</text>
  <text x="160" y="210" text-anchor="middle" font-size="10.5" fill="#5B7FA8">common in strings, voices, winds</text>
  <text x="160" y="232" text-anchor="middle" font-size="10.5" fill="#6E6A64">heard as: the note trembling</text>
  <text x="160" y="258" text-anchor="middle" font-size="10.5" fill="#E07A3F">the vibraphone does not do this</text>
  <text x="480" y="58" text-anchor="middle" font-size="11" fill="#E07A3F">tremolo · loudness varies</text>
  <g stroke="#E07A3F" stroke-width="3">
    <path d="M380,120 L392,88"/><path d="M392,88 L404,152"/><path d="M404,152 L416,88"/>
    <path d="M416,88 L428,152"/><path d="M428,152 L440,88"/><path d="M440,88 L452,152"/>
    <path d="M452,152 L464,88"/><path d="M464,88 L476,152"/><path d="M476,152 L488,88"/>
    <path d="M488,88 L500,152"/><path d="M500,152 L512,120"/>
  </g>
  <path d="M380,120 L512,120" stroke="#343439" stroke-width="1" stroke-dasharray="3 3"/>
  <text x="480" y="188" text-anchor="middle" font-size="10.5" fill="#A9A49B">pitch steady, loudness pulsing</text>
  <text x="480" y="210" text-anchor="middle" font-size="10.5" fill="#E07A3F">caused by the vanes</text>
  <text x="480" y="232" text-anchor="middle" font-size="10.5" fill="#6E6A64">heard as: the note shimmering</text>
  <text x="480" y="258" text-anchor="middle" font-size="10.5" fill="#E07A3F">what the vibraphone does</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Both are often translated as "颤音" in Chinese, but one is frequency modulation and the other amplitude.</text>
</svg>
```

**This distinction matters in scoring**: asking for "vibrato" means pitch movement on a
[[instrument:violin|violin]], but on a vibraphone it means **switching the motor on** (loudness movement). The
notation and the result differ.

## Range

```range
{"range":"F3–F6","common":"C4–C5","caption":"颤音琴的音域","caption_en":"Vibraphone range","note":"颤音琴属体鸣的有音高乐器。常见音域 F3–F6（三组）。共鸣管内的旋转阀产生周期性的音量起伏 —— 严格说这是振幅调制（tremolo），不是音高颤动。"}
```

- **F3–F6** (three octaves), much narrower than a [[instrument:marimba|marimba]], a little lower than a
  [[instrument:xylophone|xylophone]].
- **The working register is C4–C5**, where its metallic sheen is most comfortable and where jazz mostly lives.
- **A narrow range is its limitation** — but its colour and harmonic ability compensate.

## Timbre, and how to hear it

Four cues:

1. **Metallic sheen with a long tail** — brighter and cooler than a marimba, and longer-ringing.
2. **The shimmer is its signature** (with the motor on); that periodic loudness pulse is hard to confuse with
   anything else.
3. **A damper pedal controls the tail.** Most vibraphones have one, so notes can pile up — letting it play
   chords like a piano with the pedal down.
4. **Both melodic and harmonic.** Four mallets plus the pedal let it carry harmony in jazz.

```audiolab
{"type":"instrument","gm":"Vibraphone","synth":"metal","phrase":["C4","E4","G4","C5","E5","G5"],"label":"颤音琴的常用区：C4 到 G5","label_en":"The vibraphone's working register — C4 up to G5","hint":"注意音色的金属光泽与余音 —— 以及「闪烁」感来自音量的周期性起伏","hint_en":"Hear the metallic sheen and the long tail — and how the shimmer comes from periodic changes in loudness."}
```

## Playing techniques

- **Four-mallet technique** (a shared system with the marimba).
- **Damper pedal** to control the tail; held down, notes accumulate.
- **Motor on/off and speed**, adjusted to the music.
- **Mallet choice**: hard and soft heads combined with the motor give textures from icy to hazy.

## The family

| Instrument | Bars | Resonators | Extra | Range | Colour |
|---|---|---|---|---|---|
| [[instrument:xylophone\|Xylophone]] | hard wood | short | — | F4–C8 | dry, brittle |
| [[instrument:marimba\|Marimba]] | softer wood | long | — | C2–C7 | warm, thick |
| **Vibraphone** | **aluminium** | long | **vanes + pedal** | F3–F6 | metallic, shimmering |
| [[instrument:glockenspiel\|Glockenspiel]] | steel | — | — | G5–C8 | very bright, clear |
| [[instrument:celesta\|Celesta]] | steel plates (keyboard) | soundbox | keyboard action | C3–C8 | glassy |

**The bar family now has five members**, and their differences reduce entirely to **material, resonator
length and added devices** — the most complete "same structure, different colours" group on the site.

## History

| Period | State |
|---|---|
| 1916 (USA) | Herman Winterhoff and others add resonators and rotating vanes to a metal-bar instrument → the modern vibraphone |
| 1920s–30s | enters **jazz**; becomes the instrument of jazz vibraphonists |
| Mid-20th c. | its solo and harmonic roles in jazz are established; four-mallet technique spreads |
| Late 20th c. | enters pop, film scoring and contemporary classical; the motor is used more flexibly |
| Late 20th c. onward | a standard in jazz, pop, film and contemporary music |

**It is the youngest member of the bar family** (settled only in 1916) — and the way it added vanes shows that
**percussion can be modernised**: not by changing material but by adding a controllable variable.

## Common misconceptions

- **"Its vibrato is pitch movement."** The opposite: the vanes modulate **loudness** (tremolo), leaving pitch
  unchanged. The name is a historical leftover.
- **"It is the same as a xylophone."** Same family but a different material (metal versus wood), plus vanes and
  a pedal — different sound and use.
- **"Three octaves makes it limited."** It stands on colour and harmony, and is an important solo and
  accompanying instrument in jazz.
- **"The vanes are decorative."** They define its identity — switch the motor off and it is no longer a
  "vibraphone".
- **"It cannot be a solo instrument."** Four mallets plus the pedal allow melody and harmony together, and it
  has a full solo repertoire.

## Next

Three metal instruments remain: the [[instrument:glockenspiel|glockenspiel]] (steel bars, extremely bright),
[[instrument:tubular-bells|tubular bells]] (hung metal tubes, bell sound) and the
[[instrument:celesta|celesta]] (keyboard-struck steel plates, glassy). Beyond them lies the
[[instrument:gong|gong]] — also a metal body vibrating as a whole, but unpitched with an extremely long tail.
:::
