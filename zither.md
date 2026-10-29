---
id: zither
site: inst
cat: I12
title: 齐特琴
title_en: The zither
summary: 平放的琴箱上，一组弦按音，一组弦伴奏
summary_en: A flat soundbox with a fretted melody board and open accompaniment strings — a family before it is an instrument
level: standard
tags: [乐器, 世界, 欧洲, 弦鸣, 齐特琴, 民间]
tags_en: [instrument, world, europe, chordophone, zither, folk]
alias: [齐特琴, zither, 齐特尔琴, 阿尔卑斯齐特琴, 音乐会齐特琴, 康采特齐特琴, 拨弦齐特琴]
order: 233
links:
  - "[[instrument:zheng]]"
  - "[[instrument:guqin]]"
  - "[[instrument:yangqin]]"
  - "[[instrument:cimbalom]]"
instances:
  - giantmidi-001481 | 卡尔·博姆的钢琴小品《Zitherständchen》把齐特琴写成沙龙小夜曲；曲库版本是钢琴，正好听齐特琴如何被当作一种情绪符号
  - mutopia-001274 | 莫扎特《Komm, liebe Zither, komm》标题直接呼唤齐特琴；这首为人声与曼陀林而作的小歌，说明 zither 曾泛指拨弦伴奏乐器
  - openscore-000764 | 埃米莉·楚姆施特格《An meine Zither》把齐特琴当作家庭歌唱的伴奏；这首艺术歌曲补上齐特琴作为闺房乐器的一面
sources:
  - 结构、慕尼黑定弦 F1–A4、五根旋律弦与37根伴奏弦，参 Wikipedia 与 Britannica
  - HS 314.122 板面齐特与筝、古琴、扬琴的归类，参 Hornbostel–Sachs 分类与 Grove "Zither"
  - 《The Third Man》与 Anton Karas 的配乐，参电影史资料；曲库无齐特琴录音，实例取 C1 作品
updated: 2026-10-28
---

::: zh
zither 是**类名**：弦绷在扁平的琴箱上，与面板平行，琴体兼作共鸣箱，没有从琴体分出去的琴颈。现代语境里它多半指**音乐会齐特琴**：五根旋律弦走在按弦板上，三十七根伴奏弦全部开放。

## 结构：平放、两组弦、按弦板

在 HS 里，板面齐特包括筝、古琴、扬琴，甚至钢琴；现代英语的 the zither 却常指十九世纪的音乐会齐特琴。

五根旋律弦由左手在按弦板上止音；三十七根伴奏弦全开放，右手拨。两组弦共享一个琴箱，一个人就能同时做旋律与伴奏。

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="齐特琴结构示意：旋律弦在按弦板上，伴奏弦开放">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">齐特琴 · 平放的琴箱，两组弦分工</text>
  <path d="M96,120 L500,108 L536,300 L58,314 Z" fill="#FBF3E4" stroke="#9C7A3C" stroke-width="2"/>
  <circle cx="330" cy="218" r="28" fill="#FFFDF6" stroke="#B5761E" stroke-width="2"/>
  <rect x="108" y="140" width="128" height="126" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="1.5"/>
  <g stroke="#5A554E" stroke-width="1">
    <path d="M126,140 L126,266"/><path d="M148,140 L148,266"/><path d="M170,140 L170,266"/>
    <path d="M192,140 L192,266"/><path d="M214,140 L214,266"/>
  </g>
  <g stroke="#B5761E" stroke-width="1.4">
    <path d="M96,156 L500,144"/><path d="M96,176 L502,164"/><path d="M96,196 L504,184"/>
    <path d="M96,216 L506,204"/><path d="M96,236 L508,224"/>
  </g>
  <g stroke="#8A6B34" stroke-width="1">
    <path d="M58,248 L510,232"/><path d="M58,258 L512,242"/><path d="M58,268 L514,252"/>
    <path d="M58,278 L516,262"/><path d="M58,288 L518,272"/>
  </g>
  <path d="M500,116 L516,286" stroke="#A8452C" stroke-width="3"/>
  <text x="172" y="132" font-size="11" fill="#5A554E" text-anchor="middle">旋律弦 5</text>
  <text x="360" y="294" font-size="11" fill="#5A554E" text-anchor="middle">伴奏弦 37（开放）</text>
  <text x="528" y="312" font-size="11" fill="#A8452C">琴桥</text>
</svg>
```

## 音域与音色

```range
{"range":"F1–A4","common":"C3–A4","caption":"音乐会齐特琴的音域（42 弦 · 慕尼黑定弦）","caption_en":"Concert zither range (42 strings, Munich tuning)","note":"五根旋律弦定 C3、G3、D4、A4、A4，37 根伴奏与低音弦向下到 F1；记谱即实音。阿尔卑斯齐特琴弦数较少，音域随弦数变化。","note_en":"Melody strings C3, G3, D4, A4, A4; 37 accompaniment and bass strings reach F1. Written pitch is sounding pitch. Alpine zithers have fewer strings."}
```

旋律弦跨一个多八度，伴奏弦铺到 F1。金属弦音头清脆，开放弦一掃就是和弦；**按音与空弦两种拨弦方式装在同一件乐器里**。

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (nylon)","synth":"plucked","phrase":["C3","G3","D4","A4","E4","A4"],"label":"齐特琴的两层","label_en":"Two layers of the zither","hint":"GM 没有齐特琴，借尼龙弦吉他；它给不出 37 根开放弦与按弦板分工","hint_en":"GM has no zither; a nylon guitar cannot give 37 open strings or the fretboard split."}
```

## 边界：筝、古琴、扬琴

| 乐器 | 与齐特琴的关系 | 关键差异 |
|---|---|---|
| 筝 | HS 板面齐特 | 可移动雁柱，每弦一音 |
| 古琴 | HS 板面齐特 | 无柱无品，左手按弦取音 |
| 扬琴 | 击弦齐特 | 用琴竹击弦，不是拨弦 |
| 钢琴 | HS 板面齐特 | 有键盘与击弦机，没人叫它 zither |

guzheng 常被叫 Chinese zither；差别在**雁柱、定弦与演奏传统**。钢琴也属板面齐特，却没人叫它 zither。**分类看结构，名字看习惯。**

### HS 分类

| 项 | 内容 |
|---|---|
| HS 类 | **弦鸣**（Chordophone）· 板面齐特 314.122 |
| 次级类型 | 有按弦板的旋律弦 + 无品伴奏弦；琴体即共鸣箱，无独立琴颈 |
| 所属族 | 欧洲 · 阿尔卑斯（奥地利、巴伐利亚、瑞士、斯洛文尼亚） |
| 关键特征 | 平放 · 两组弦 · 左手按旋律、右手拨伴奏 |

## 电影里的齐特琴

1949 年《The Third Man》让 Anton Karas 用独奏齐特琴弹遍全片，开放弦扫奏与颤音成了“旧欧洲”的声音符号。**刻板印象不是错，只是窄**：它把有沙龙独奏、阿尔卑斯合奏与当代创作的乐器压成一个怀旧标签。

## 常见误解

- **"齐特琴就是一件乐器。"** 它是一个类；现代常指音乐会或阿尔卑斯齐特琴。
- **"筝不是齐特琴。"** 在 HS 里筝是板面齐特，英语也常叫 Chinese zither；边界在雁柱与演奏传统。
- **"齐特琴只能弹民间小调。"** 十九世纪有沙龙独奏作品，也有当代创作。

## 带走三件事

1. **zither 是类名**：板面、弦与面板平行、无独立琴颈。
2. **两组弦分工**：左手按旋律，右手拨开放伴奏弦。
3. **边界看结构**：筝、古琴、扬琴、钢琴都属板面齐特，叫不叫 zither 是语言习惯。
:::

::: en
"Zither" is a **class name**: strings stretched over a flat soundbox, parallel to the soundboard, with the body as resonator and no separate neck. In modern usage it usually means the **concert zither**: five melody strings over a fretted board and thirty-seven open accompaniment strings.

## Structure: flat, two string groups, a fretboard

In Hornbostel–Sachs, board zithers include the zheng, the guqin, the yangqin and even the piano; in modern English, "the zither" usually means the nineteenth-century concert zither.

Five melody strings are stopped by the left hand; thirty-seven accompaniment strings stay open and are plucked by the right. Both groups share one soundbox, so one player carries melody and accompaniment at once.

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Zither structure: melody strings over the fretboard, open accompaniment strings">
  <rect width="640" height="380" fill="#FFFDF6"/>
  <text x="20" y="24" font-size="12" font-weight="700" fill="#2A2724">Zither — a flat box with two string groups</text>
  <path d="M96,120 L500,108 L536,300 L58,314 Z" fill="#FBF3E4" stroke="#9C7A3C" stroke-width="2"/>
  <circle cx="330" cy="218" r="28" fill="#FFFDF6" stroke="#B5761E" stroke-width="2"/>
  <rect x="108" y="140" width="128" height="126" fill="#E9DCC6" stroke="#9C7A3C" stroke-width="1.5"/>
  <g stroke="#5A554E" stroke-width="1">
    <path d="M126,140 L126,266"/><path d="M148,140 L148,266"/><path d="M170,140 L170,266"/>
    <path d="M192,140 L192,266"/><path d="M214,140 L214,266"/>
  </g>
  <g stroke="#B5761E" stroke-width="1.4">
    <path d="M96,156 L500,144"/><path d="M96,176 L502,164"/><path d="M96,196 L504,184"/>
    <path d="M96,216 L506,204"/><path d="M96,236 L508,224"/>
  </g>
  <g stroke="#8A6B34" stroke-width="1">
    <path d="M58,248 L510,232"/><path d="M58,258 L512,242"/><path d="M58,268 L514,252"/>
    <path d="M58,278 L516,262"/><path d="M58,288 L518,272"/>
  </g>
  <path d="M500,116 L516,286" stroke="#A8452C" stroke-width="3"/>
  <text x="172" y="132" font-size="11" fill="#5A554E" text-anchor="middle">5 melody strings</text>
  <text x="360" y="294" font-size="11" fill="#5A554E" text-anchor="middle">37 open accompaniment strings</text>
  <text x="528" y="312" font-size="11" fill="#A8452C">Bridge</text>
</svg>
```

## Range and timbre

```range
{"range":"F1–A4","common":"C3–A4","caption":"音乐会齐特琴的音域（42 弦 · 慕尼黑定弦）","caption_en":"Concert zither range (42 strings, Munich tuning)","note":"五根旋律弦定 C3、G3、D4、A4、A4，37 根伴奏与低音弦向下到 F1；记谱即实音。阿尔卑斯齐特琴弦数较少，音域随弦数变化。","note_en":"Melody strings C3, G3, D4, A4, A4; 37 accompaniment and bass strings reach F1. Written pitch is sounding pitch. Alpine zithers have fewer strings."}
```

Melody strings span a little over an octave, while accompaniment reaches F1. Metal strings give a bright attack, and open strings turn a sweep into a chord; **stopped and open plucking live in one body**.

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (nylon)","synth":"plucked","phrase":["C3","G3","D4","A4","E4","A4"],"label":"齐特琴的两层","label_en":"Two layers of the zither","hint":"GM 没有齐特琴，借尼龙弦吉他；它给不出 37 根开放弦与按弦板分工","hint_en":"GM has no zither; a nylon guitar cannot give 37 open strings or the fretboard split."}
```

## Boundaries: zheng, guqin, yangqin

| Instrument | Relation to the zither | Key difference |
|---|---|---|
| zheng | HS board zither | movable bridges, one pitch per string |
| guqin | HS board zither | no bridges or frets, left hand stops the strings |
| yangqin | struck zither | struck with bamboo hammers, not plucked |
| piano | HS board zither | keyboard and hammer action, never called a zither |

So calling the guzheng a Chinese zither is not a contradiction; it differs in **bridges, tuning and tradition**. The piano is a board zither in HS but never a zither in speech. **Classification follows structure; naming follows habit.**

### HS classification

| Item | Content |
|---|---|
| HS class | **Chordophone** · board zither 314.122 |
| Sub-type | fretted melody strings plus open accompaniment strings; body as resonator, no separate neck |
| Family | Europe · Alpine (Austria, Bavaria, Switzerland, Slovenia) |
| Key features | laid flat · two string groups · left hand stops melody, right hand plucks accompaniment |

## The zither in film

In 1949 "The Third Man", Anton Karas played a solo zither across the whole score; its open-string sweep and tremolo became a sound of old Europe. **The stereotype is not wrong, only narrow**: it turns an instrument with salon solos, Alpine ensembles and contemporary works into one nostalgic label.

## Common misconceptions

- **"The zither is one instrument."** It is a class; modern usage usually means the concert or Alpine zither.
- **"The zheng is not a zither."** In HS it is a board zither, and English often calls it a Chinese zither; the boundary is bridges and tradition.
- **"The zither only plays folk tunes."** There are salon solos and contemporary works.

## Three things to take away

1. **Zither is a class name**: a flat body, strings parallel to the soundboard, no separate neck.
2. **Two string groups**: the left hand stops melody, the right hand plucks open accompaniment.
3. **Boundaries follow structure**: zheng, guqin, yangqin and piano all fall under board zithers; whether we call them zithers is a matter of habit.
:::
