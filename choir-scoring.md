---
id: choir-scoring
site: inst
cat: I13
title: 合唱编制
title_en: Choir scoring
summary: 从SATB到分部与双合唱，按音区、声部线条、人数和空间安排合唱
summary_en: Arrange choral registers, lines, numbers and placement, from SATB to divisi and double choir
range_policy: variable
range_basis: 合唱总音域取决于具体声部、歌手和作品，SATB等缩写不能给出固定边界，因此本页只展示明确的和弦排列。
level: standard
tags:
  - 人声
  - 歌唱
  - 声乐
  - 声部
tags_en:
  - voice
  - singing
  - voice-types
alias: [合唱编制, choir scoring, SATB, 双合唱, 分隔合唱, cori spezzati, 混声合唱]
order: 207
links:
  - "[[instrument:voice-types]]"
  - "[[instrument:voice]]"
  - "[[instrument:popular-voice]]"
  - "[[instrument:vocal-production]]"
  - "[[concept:timbre]]"
instances:
  - chinafolk-003920 | 《隔山应》 — 若把旋律安排为一部领唱、另一部回应，应如何划分句子？这是改编设想，不是原文件编制说明。（仅限学习研究）
  - chinafolk-009261 | 《高山打锣应得宽》 — 在谱面上寻找可分组呼应的乐句；现场空间效果不能由MIDI标题证明。（仅限学习研究）
  - chinafolk-004628 | 《锣鼓一打三不齐》 — 尝试给旋律配一个持续低音，比较单声部与两声部的区别；新增声部属于自己的改编。（仅限学习研究）
sources:
  - "American Choral Directors Association — High School SATB Honor Choir Files. https://acda.org/conferences/honorchoirs/high-school-satb-honor-choir-files"
  - "Robert Duff and Brandeis Chamber Singers — Chamber Singers Learning Module 2: Coro Spezzati (2020). https://scholarworks.brandeis.edu/esploro/outputs/activity/Chamber-Singers-Learning-Module-2-Coro/9924126024701921"
updated: 2026-11-02
---

::: zh
合唱编制说明有哪些声部、每部如何分工，以及是否需要独唱、伴奏或分组。声部数与人数是两个问题：四部混声既可由四位歌手演唱，也可由每部多位歌手组成合唱团。

| 说明 | 内容 |
|---|---|
| HS 分类 | 人声（人体发声，非电鸣）；此页不套用独立器乐的HS编号 |

## 读懂常见缩写

| 标记 | 声部安排 |
|---|---|
| SATB | Soprano 女高、Alto 女低、Tenor 男高、Bass 男低四部 |
| SSA / SSAA | 两个女高加一个女低，或两个女高加两个女低；也用于适合该音区的童声等编制 |
| TTBB | 两个男高、两个男低声部 |
| SSAATTBB | S、A、T、B 各分为两部，合计八条声部 |
| SATB / SATB | 两组各有四部的合唱队，可分别或共同演唱 |

Alto、Tenor 等在这里首先是乐谱声部名称。实际分配要结合歌手的舒适音区，不宜仅以性别或某一个最高音决定。

```svg
<svg viewBox="0 0 640 244" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="四声部、八声部与双合唱">
<text x="24" y="30" font-family="system-ui,sans-serif" font-size="17" font-weight="700" fill="#A9A49B">四声部、八声部与双合唱</text>
<rect x="24" y="52" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="70" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SATB</text>
<text x="38" y="87" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">四条线：S / A / T / B，人数由各部实际配置决定</text>
<rect x="24" y="110" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="128" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SSAATTBB</text>
<text x="38" y="145" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">每部再分两条：S1 S2 / A1 A2 / T1 T2 / B1 B2</text>
<rect x="24" y="168" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="186" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SATB / SATB</text>
<text x="38" y="203" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">两组合唱队，各有四部；可呼应，也可合奏</text>
</svg>
```

## 四个音怎样排成和弦

以 C 大三和弦为例，可由低到高安排 B=C3、T=G3、A=E4、S=C5。四条声部中根音 C 被加倍，整体跨两个八度；这是和弦排列，不是要求每个团都能唱到的音域标准。

下一和弦到来时，还要看各声部自己的旋律是否顺口、是否频繁跨过换声区，不能只把和弦音按高低堆上去。分部越多，排练与音准配合的要求通常也越细。

```audiolab
{"type":"scale","notes":["C3","G3","E4","C5"],"label":"C 大三和弦的四声部排列：C3–G3–E4–C5","label_en":"A four-part C-major voicing: C3–G3–E4–C5","hint":"依次播放可分辨四个声部音高；一起响比较和弦排列。它是构造谱例，不是真人合唱或四条完整旋律。","hint_en":"Play separately to identify the four pitches, or together to compare the voicing. This is a constructed example, not a live choir or four complete melodies."}
```

## 分部、人数与呼吸

同一个声部内再分两条不同旋律叫 divisi，不等于每次都要增加人数。某一部人数偏少时，八部写作可能让每条线过薄；伴奏很密时，增加歌手也未必比调整织体更有效。排练时要统一元音、辅音位置、句尾和换气，长句还可安排错开换气。

## 双合唱与空间

文艺复兴晚期威尼斯的 cori spezzati 使用分组呼应，人的位置与场地混响会影响听到的对比。这是空间化表演的历史实例，不能称为人类“第一套立体声”。

今天写双合唱，可以让 A 组提出一句、B 组回答，再让两组同时进入。距离较远时，指挥视线、声音延迟与混响都会影响齐奏；因此位置也是排练安排的一部分，不是把音箱声像旋钮向左右转即可替代。


:::

::: en
Choral scoring specifies parts, their roles and any soloists, accompaniment or groups. Part count and singer count are different: four-part music can be sung by four solo voices or by several singers on each part.

| Classification note | Description |
|---|---|
| HS class | Human voice: bodily sound production, not an electrophone; no separate instrument number is assigned here |

## Read the abbreviations

| Marking | Parts |
|---|---|
| SATB | Soprano, alto, tenor and bass |
| SSA / SSAA | Two sopranos and one alto, or two of each; also used for suitable children’s ensembles |
| TTBB | Two tenor and two bass parts |
| SSAATTBB | Each SATB part divided in two, eight lines in total |
| SATB / SATB | Two four-part choirs, performing separately or together |

Here alto and tenor are score-part names. Assignment depends on comfortable tessitura, rather than gender or one highest note alone.

```svg
<svg viewBox="0 0 640 244" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Four parts, eight parts and double choir">
<text x="24" y="30" font-family="system-ui,sans-serif" font-size="17" font-weight="700" fill="#A9A49B">Four parts, eight parts and double choir</text>
<rect x="24" y="52" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="70" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SATB</text>
<text x="38" y="87" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Four lines: S / A / T / B, with variable numbers on each</text>
<rect x="24" y="110" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="128" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SSAATTBB</text>
<text x="38" y="145" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Each section divides: S1 S2 / A1 A2 / T1 T2 / B1 B2</text>
<rect x="24" y="168" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="186" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">SATB / SATB</text>
<text x="38" y="203" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Two four-part groups, contrasting or singing together</text>
</svg>
```

## Four notes in a chord

A C-major chord can be voiced B=C3, T=G3, A=E4 and S=C5. The root C is doubled, and the whole chord spans two octaves. This is a voicing example, not a range requirement for every choir.

For the next chord, check each line’s melodic shape and register transitions rather than simply stacking chord tones. Additional parts also require more detailed coordination of balance and tuning.

```audiolab
{"type":"scale","notes":["C3","G3","E4","C5"],"label":"C 大三和弦的四声部排列：C3–G3–E4–C5","label_en":"A four-part C-major voicing: C3–G3–E4–C5","hint":"依次播放可分辨四个声部音高；一起响比较和弦排列。它是构造谱例，不是真人合唱或四条完整旋律。","hint_en":"Play separately to identify the four pitches, or together to compare the voicing. This is a constructed example, not a live choir or four complete melodies."}
```

## Divisi, numbers and breathing

Divisi splits one section into different lines; it does not necessarily add singers. If a section is small, eight-part writing may leave lines underpowered. Dense accompaniment may be better addressed by changing the texture than by adding singers. Rehearsal coordinates vowels, consonants, releases and breaths; staggered breathing can sustain long phrases.

## Double choir and space

Late-Renaissance Venetian cori spezzati used contrasting groups whose positions and room acoustics affected the result. This is a historical example of spatial performance, not humanity’s “first stereo.”

A modern double-choir passage can let group A state a phrase, group B answer, and both later enter together. Greater distance introduces issues of sightline, delay and reverberation. Placement therefore belongs in rehearsal planning and cannot be replaced simply by turning a pan control.

:::
