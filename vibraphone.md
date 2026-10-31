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

## 电机一转，声音开始闪

颤音琴的马达在琴箱下面，一根皮带带着所有共鸣管里的阀片同时旋转。阀片周期性挡住管口，音量一涨一落，听起来像音在闪。转速可以调，慢的时候像呼吸，快的时候像电流。关掉马达，它立刻变回一台普通的金属条琴。

| 分类 | 归属 |
|---|---|
| HS 分类 | 体鸣 · 有音高 |
| 结构 | 铝合金条 + 共鸣管 + 旋转阀（一台电机同步驱动）+ 延音踏板 |
| 八音：不适用 | 周代八音不收金属条琴 |

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

## 名字说的是另一件事

vibrato 是音高在抖，弦乐与歌声用它；tremolo 是音量在抖，颤音琴做的是后者。中文把两个词都译成颤音，英文名 vibraphone 也沿用了错的那个。所有阀片由一台电机带动，起伏同步，所以整台琴闪得整齐。这一点在配器上很实用：给弦乐写颤音是音高，给颤音琴写颤音是开电机。名字错了一百多年，用法却一直很清楚。

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

## 三个八度，一块踏板

常见音域 F3 到 F6，三个八度，比马林巴窄。常用区在 C4 到 C5，金属光泽最舒服，爵士乐手大多待在这里。多数琴有延音踏板，踩下去余音互相叠加；四根槌可以同时按下四个音，于是它能像钢琴一样弹和弦。音域窄是它的限制，和声能力把它补了回来。

```range
{"range":"F3–F6","common":"C4–C5","caption":"颤音琴的音域","caption_en":"Vibraphone range","note":"颤音琴属体鸣的有音高乐器。常见音域 F3–F6（三组）。共鸣管内的旋转阀产生周期性的音量起伏 —— 严格说这是振幅调制（tremolo），不是音高颤动。"}
```

## 1916 年之后

1916 年，美国的 Herman Winterhoff 在金属条琴上加装共鸣管与旋转阀，现代颤音琴定型。1920 年代它进入爵士乐，此后既是独奏乐器，也是和声层；四槌技术普及之后，一个人就能同时给出旋律与伴奏。它是琴条家族里最年轻的一件，也是唯一把效果装进琴体的一件：不是换材料，而是加一个可控变量。听它时先注意余音有多长，再注意那层闪匀不匀。匀，说明电机在转。

```audiolab
{"type":"instrument","gm":"Vibraphone","synth":"metal","phrase":["C4","E4","G4","C5","E5","G5"],"label":"颤音琴的常用区：C4 到 G5","label_en":"The vibraphone's working register — C4 up to G5","hint":"注意音色的金属光泽与余音 —— 以及「闪烁」感来自音量的周期性起伏","hint_en":"Hear the metallic sheen and the long tail — and how the shimmer comes from periodic changes in loudness."}
```

:::

::: en

## The motor turns, and the sound begins to flicker

Under the frame a belt drives every vane in every resonator tube at once. The vanes cover the tube mouths in turn, the volume rises and falls, and the note seems to flicker. Switch the motor off and it becomes an ordinary metal-bar instrument.

| Class | Assignment |
|---|---|
| HS class | Idiophone · pitched |
| Form | aluminium bars + resonator tubes + rotating vanes (one motor, all in step) + damper pedal |
| Bayin | outside it — the Zhou system took no metal-bar instruments |

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

## The name describes something else

Vibrato is a wobble in pitch, which strings and voices use; tremolo is a wobble in volume, which is what the vanes do. Chinese translates both with one word, and the English name kept the wrong one. A single motor drives all the vanes, so the flicker is synchronised across the instrument, and that is why it sounds unified. In scoring the distinction is practical: vibrato for strings means pitch, vibrato for the vibraphone means switching the motor on.

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

## Three octaves and a pedal

The range runs F3 to F6, three octaves, narrower than the marimba. The working register is C4 to C5, where the metal sheen sits most comfortably and where jazz players spend their time. Most instruments have a damper pedal; hold it down and notes stack, and four mallets can press four notes at once, so it plays chords like a piano. The narrow range is a limit; the harmony makes up for it.

```range
{"range":"F3–F6","common":"C4–C5","caption":"颤音琴的音域","caption_en":"Vibraphone range","note":"颤音琴属体鸣的有音高乐器。常见音域 F3–F6（三组）。共鸣管内的旋转阀产生周期性的音量起伏 —— 严格说这是振幅调制（tremolo），不是音高颤动。"}
```

## After 1916

In 1916 the American Herman Winterhoff added resonator tubes and rotating vanes to a metal-bar instrument, and the modern vibraphone settled into shape. It entered jazz in the 1920s and has been both a solo voice and a harmony layer since. It is the youngest of the bar family and the only one with an effect built into the body: not a new material, a new variable. Listen first to the length of the tail, then to whether the flicker is even. If it is even, the motor is running.

```audiolab
{"type":"instrument","gm":"Vibraphone","synth":"metal","phrase":["C4","E4","G4","C5","E5","G5"],"label":"颤音琴的常用区：C4 到 G5","label_en":"The vibraphone's working register — C4 up to G5","hint":"注意音色的金属光泽与余音 —— 以及「闪烁」感来自音量的周期性起伏","hint_en":"Hear the metallic sheen and the long tail — and how the shimmer comes from periodic changes in loudness."}
```
:::
