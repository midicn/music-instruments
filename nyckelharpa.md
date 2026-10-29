---
id: nyckelharpa
site: inst
cat: I12
title: 尼古赫帕
title_en: The nyckelharpa
summary: 瑞典键控提琴：木键止弦，弓发声，共鸣弦在底下嗡鸣
summary_en: Sweden's keyed fiddle — wooden keys stop the string, a bow sets it singing, and twelve sympathetic strings hum underneath
level: standard
tags: [乐器, 世界, 欧洲, 瑞典, 弦鸣, 键控提琴, 民间]
tags_en: [instrument, world, europe, sweden, chordophone, keyed-fiddle, folk]
alias: [尼古赫帕, nyckelharpa, 键控提琴, 瑞典键控提琴, keyed fiddle, 北方西塔琴, 尼古赫巴琴]
order: 234
links:
  - "[[instrument:hurdy-gurdy]]"
  - "[[instrument:hardanger-fiddle]]"
  - "[[instrument:violin]]"
instances:
  - norbeck-000956 | 《Nyckelharpspolska》直译就是尼古赫帕波尔斯卡；曲库是单线旋律，能听清三拍 polska 分组，不含共鸣弦
  - norbeck-000952 | 《Eklundapolska #1》是瑞典 polska 舞曲；与上一首并置，能听出这类曲调短小、重复、适合加装饰
  - norbeck-000957 | 《Polska efter From-Olle》保存曲目谱系；efter 意为传自，标题记的是传承，不是风格标签
sources:
  - 14 世纪 Källunge 浮雕、1408 锡耶纳壁画、Moraharpa 1526、Bohlin 1926 与 Sahlström 1950 年代，参 Wikipedia 与 UNESCO 2023
  - 321.322-71、三旋律弦 + 一持续弦 + 12 共鸣弦、37 键三排，参 Grove "Nyckelharpa"
  - 曲库无尼古赫帕录音，实例取 C1 瑞典 polska 旋律并说明
updated: 2026-10-28
---

::: zh
尼古赫帕是瑞典的**键控提琴**：弓发声，木键把**切线**顶到弦上改变有效弦长；琴桥下十二根**共鸣弦**应声而鸣。

## 主线与结构：木键、切线、四组弦

它把提琴的弓和手摇琴的键拆开再组合：**弓保留，手指按弦被机械替代**。三排共三十七个木键，按下时切线顶住旋律弦，弦长变短；三条旋律弦加一条持续弦用弓，十二条共鸣弦从琴桥下穿过，不被弓触及。

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="尼古赫帕结构示意">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">尼古赫帕 · 木键止弦，弓发声</text>
  <path d="M118,160 C150,142 190,150 210,168 C225,182 225,196 214,210 C202,226 202,244 218,260 C236,278 226,300 190,304 L150,304 C126,300 118,282 122,258 L122,190 Z" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="2"/>
  <path d="M210,168 L450,160 L468,202 L468,282 L210,290 Z" fill="#FBF3E4" stroke="#9C7A3C" stroke-width="2"/>
  <rect x="150" y="112" width="210" height="46" fill="#F2EEE6" stroke="#9C7A3C" stroke-width="1.6"/>
  <g fill="#B5761E">
    <rect x="170" y="120" width="14" height="8"/><rect x="220" y="120" width="14" height="8"/>
    <rect x="170" y="134" width="14" height="8"/><rect x="220" y="134" width="14" height="8"/>
    <rect x="170" y="148" width="14" height="6"/><rect x="220" y="148" width="14" height="6"/>
  </g>
  <g stroke="#5A554E" stroke-width="1.4">
    <path d="M177,158 L177,196"/><path d="M227,158 L227,196"/>
  </g>
  <g stroke="#B5761E" stroke-width="2">
    <path d="M128,206 L458,198"/><path d="M128,216 L458,208"/><path d="M128,226 L458,218"/>
  </g>
  <g stroke="#6B4FA8" stroke-width="1" stroke-dasharray="5 4">
    <path d="M128,250 L458,242"/><path d="M128,258 L458,250"/><path d="M128,266 L458,258"/>
  </g>
  <path d="M448,186 L462,292" stroke="#A8452C" stroke-width="4"/>
  <path d="M300,178 L362,300" stroke="#8A6B34" stroke-width="3"/>
  <text x="255" y="106" font-size="11" fill="#5A554E" text-anchor="middle">三排木键 · 切线</text>
  <text x="300" y="296" font-size="10" fill="#6B4FA8" text-anchor="middle">共鸣弦 12</text>
  <text x="486" y="292" font-size="11" fill="#A8452C">琴桥</text>
</svg>
```

## 音域与音色

```range
{"range":"C3–C6","common":"G3–G5","caption":"现代半音阶尼古赫帕的音域（三排键 · 示意）","caption_en":"Modern chromatic nyckelharpa range (three rows of keys, schematic)","note":"三排 37 键覆盖三个八度；C3 是持续弦，C6 是最高键位。音域随定弦与键列而变，本图为常见配置示意，记谱即实音。","note_en":"Three rows of 37 keys cover three octaves; C3 is the drone, C6 the highest key. The compass depends on tuning and key layout; this schematic is at sounding pitch."}
```

三排键覆盖三个八度；C3 是持续弦，C6 是最高键位。

```audiolab
{"type":"instrument","gm":"Fiddle","synth":"bowed","phrase":["C3","G3","D4","A4","C5"],"label":"尼古赫帕的常用区","label_en":"The nyckelharpa's working register","hint":"GM 没有尼古赫帕，借 Fiddle；它没有木键咔哒声与共鸣弦","hint_en":"GM has no nyckelharpa; Fiddle gives neither key clatter nor sympathetic strings."}
```

## 十四世纪图像，二十世纪复兴

14 世纪图像证据有两处：哥特兰 Källunge 教堂门浮雕（定为 1350 年）与锡耶纳 1408 年壁画；Moraharpa 标 1526 年。18 世纪是民间庆典核心，20 世纪初仅十余人会奏。1926 年 Bohlin 做出三排键半音阶型号；1950 年代 Sahlström 改进推广，成为现代标准。2023 年 UNESCO 列入良好保护实践。**它先被图像记住，再被复兴接住。**

## 与哈丁费德尔、手摇琴对照

| 乐器 | 发声 | 止弦 | 共鸣弦 | 持续音 |
|---|---|---|---|---|
| 尼古赫帕 | 弓 | 木键 + 切线 | 12 根 | 1 根持续弦 |
| 哈丁费德尔 | 弓 | 手指 | 4–5 根 | 无 |
| 手摇琴 | 轮 | 键盘推键 | 无 | 多根持续弦 |

哈丁费德尔也有共鸣弦，但用手指按弦；尼古赫帕用键换稳定与快速半音。手摇琴用轮，持续音不停；尼古赫帕仍靠弓，所以能停、能断句。

### HS 分类

| 项 | 内容 |
|---|---|
| HS 类 | **弦鸣**（Chordophone）· 321.322-71（有颈箱型琉特琴，用弓） |
| 次级类型 | 键控提琴 · 三排木键 + 切线 · 3 旋律弦 + 1 持续弦 + 12 共鸣弦 |
| 关键特征 | 横置腰间 · 木键止弦 · 共鸣弦 · 按键咔哒声 |

## 常见误解

- **"尼古赫帕是手摇琴的一种。"** 它用弓，手摇琴用轮；共同点只是用键止弦。
- **"它是小提琴加键。"** 弦数、定弦、共鸣弦与持琴方式都不同；它横放腰间，不夹肩。
- **"共鸣弦是装饰。"** 它们从琴桥下穿过，按音高被动共鸣，决定这件乐器最容易被认出的底色。

## 带走三件事

1. **键止弦、弓发声**：机械只接管音高，不接管发音。
2. **共鸣弦是音色的一半**：12 根弦在琴桥下共鸣。
3. **14 世纪有图像，20 世纪才复兴**：传统断过又接上。
:::

::: en
The nyckelharpa is Sweden's **keyed fiddle**: a bow sounds the strings, wooden keys press **tangents** against them to change the speaking length, and twelve **sympathetic strings** ring under the bridge.

## The main line and structure: keys, tangents, four string groups

It recombines the fiddle's bow with the hurdy-gurdy's keys: **the bow stays, finger-stopping is mechanised**. Three rows hold thirty-seven wooden keys; pressing one brings a tangent against a melody string and shortens its speaking length. Three melody strings and one drone are bowed, while twelve sympathetic strings pass under the bridge, untouched by the bow.

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Nyckelharpa structure">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">Nyckelharpa — keys stop, the bow sings</text>
  <path d="M118,160 C150,142 190,150 210,168 C225,182 225,196 214,210 C202,226 202,244 218,260 C236,278 226,300 190,304 L150,304 C126,300 118,282 122,258 L122,190 Z" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="2"/>
  <path d="M210,168 L450,160 L468,202 L468,282 L210,290 Z" fill="#FBF3E4" stroke="#9C7A3C" stroke-width="2"/>
  <rect x="150" y="112" width="210" height="46" fill="#F2EEE6" stroke="#9C7A3C" stroke-width="1.6"/>
  <g fill="#B5761E">
    <rect x="170" y="120" width="14" height="8"/><rect x="220" y="120" width="14" height="8"/>
    <rect x="170" y="134" width="14" height="8"/><rect x="220" y="134" width="14" height="8"/>
    <rect x="170" y="148" width="14" height="6"/><rect x="220" y="148" width="14" height="6"/>
  </g>
  <g stroke="#5A554E" stroke-width="1.4">
    <path d="M177,158 L177,196"/><path d="M227,158 L227,196"/>
  </g>
  <g stroke="#B5761E" stroke-width="2">
    <path d="M128,206 L458,198"/><path d="M128,216 L458,208"/><path d="M128,226 L458,218"/>
  </g>
  <g stroke="#6B4FA8" stroke-width="1" stroke-dasharray="5 4">
    <path d="M128,250 L458,242"/><path d="M128,258 L458,250"/><path d="M128,266 L458,258"/>
  </g>
  <path d="M448,186 L462,292" stroke="#A8452C" stroke-width="4"/>
  <path d="M300,178 L362,300" stroke="#8A6B34" stroke-width="3"/>
  <text x="255" y="106" font-size="11" fill="#5A554E" text-anchor="middle">Three rows of keys, tangents</text>
  <text x="300" y="296" font-size="10" fill="#6B4FA8" text-anchor="middle">12 sympathetic strings</text>
  <text x="486" y="292" font-size="11" fill="#A8452C">Bridge</text>
</svg>
```

## Range and timbre

```range
{"range":"C3–C6","common":"G3–G5","caption":"现代半音阶尼古赫帕的音域（三排键 · 示意）","caption_en":"Modern chromatic nyckelharpa range (three rows of keys, schematic)","note":"三排 37 键覆盖三个八度；C3 是持续弦，C6 是最高键位。音域随定弦与键列而变，本图为常见配置示意，记谱即实音。","note_en":"Three rows of 37 keys cover three octaves; C3 is the drone, C6 the highest key. The compass depends on tuning and key layout; this schematic is at sounding pitch."}
```

Three rows cover three octaves; C3 is the drone and C6 the highest key.

```audiolab
{"type":"instrument","gm":"Fiddle","synth":"bowed","phrase":["C3","G3","D4","A4","C5"],"label":"尼古赫帕的常用区","label_en":"The nyckelharpa's working register","hint":"GM 没有尼古赫帕，借 Fiddle；它没有木键咔哒声与共鸣弦","hint_en":"GM has no nyckelharpa; Fiddle gives neither key clatter nor sympathetic strings."}
```

## Fourteenth-century images, twentieth-century revival

The Källunge relief (1350) and a 1408 Siena fresco are the earliest images; the Moraharpa is dated 1526. After eighteenth-century prominence and near-extinction by 1900, August Bohlin built a three-row chromatic model in 1926 and Eric Sahlström made it standard in the 1950s; UNESCO listed the network in 2023. **It was first remembered in images, then caught by a revival.**

## Compared with the hardanger fiddle and the hurdy-gurdy

| Instrument | Sound source | Stopping | Sympathetic strings | Drone |
|---|---|---|---|---|
| nyckelharpa | bow | wooden keys + tangents | 12 | one drone |
| hardanger fiddle | bow | fingers | 4–5 | none |
| hurdy-gurdy | wheel | keyboard tangents | none | several |

The hardanger fiddle also has sympathetic strings but is stopped by fingers; the nyckelharpa trades that for stability and fast semitones. The hurdy-gurdy replaces the bow with a wheel, so its drone never stops; the nyckelharpa still depends on a bow, so it can stop and phrase.

### HS classification

| Item | Content |
|---|---|
| HS class | **Chordophone** · 321.322-71 (necked box lute, bowed) |
| Sub-type | keyed fiddle · three rows of keys and tangents · 3 melody strings + 1 drone + 12 sympathetic |
| Key features | held across the waist · keys stop the strings · sympathetic strings · key clatter |

## Common misconceptions

- **"The nyckelharpa is a kind of hurdy-gurdy."** It uses a bow, the hurdy-gurdy a wheel; the only shared idea is stopping strings with keys.
- **"It is a violin with keys."** String count, tuning, sympathetic strings and playing position all differ; it lies across the waist, not under the chin.
- **"The sympathetic strings are decoration."** They pass under the bridge and resonate passively, shaping the instrument's most recognisable colour.

## Three things to take away

1. **Keys stop, the bow sounds**: the mechanism takes over pitch, not excitation.
2. **Sympathetic strings are half the timbre**: twelve strings answer under the bridge.
3. **Fourteenth-century images, twentieth-century revival**: the tradition broke and was reconnected.
:::
