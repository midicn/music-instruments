---
id: vocal-production
site: inst
cat: I13
title: 发声原理
title_en: How the voice works
summary: 肺部气流支持声带振动，声道共鸣进一步改变音色
summary_en: Air from the lungs supports vocal-fold vibration, with vocal-tract resonance further shaping the sound
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 人声, 发声原理, 声学, MEAD]
tags_en: [instrument, electronic, electrophone, western, voice, vocal-production, acoustics, mead]
alias: [发声原理, vocal production, 声带振动, myoelastic, 自持振荡, 黏膜波, 歌唱家共振峰]
order: 202
links:
 - "[[instrument:voice]]"
 - "[[instrument:children-voice]]"
 - "[[instrument:talk-box]]"
 - "[[instrument:auto-tune]]"
 - "[[concept:timbre]]"
 - "[[concept:pitch]]"
instances:
  - chinafolk-000869 | 《大风吹来竹叶飞》MIDI音符从A3到E4，可把这段较窄的旋律范围与下两条对照；曲名中的风不是发声机制的证据（C3，仅学习研究） | The MIDI notes of this song span A3 to E4, a narrower range to compare with the following two; the wind in its title is not evidence about phonation (C3, study only)
  - chinafolk-010459 | 《一口气叫卖》MIDI音符从E4到G5，含59次发音事件；这些事件记录旋律，不记录一次呼吸能维持多久（C3，仅学习研究） | This song spans E4 to G5 with 59 note-on events, recording melody rather than the duration of a breath (C3, study only)
  - chinafolk-000980 | 《风吹竹叶皮皮青》MIDI音符从A4到E6，可观察谱面音区与旋律跨度；是否适合某位歌者须另按实际音域考虑（C3，仅学习研究） | This MIDI spans A4 to E6 for studying register and melodic span; suitability for a singer depends separately on that singer’s range (C3, study only)
sources:
  - "https://www.nidcd.nih.gov/health/taking-care-your-voice"
  - "https://onlinelibrary.wiley.com/doi/abs/10.1002/j.1538-7305.1972.tb02651.x"
updated: 2026-11-02
---

::: zh

## 吹一口气，两片声带自己响

把嘴唇放松，吹气，它们会自己振动。声带做的是同一件事：肺给出气压，两片声带靠拢，气流经过，振动自己维持下去，不需要神经一下一下地敲。神经只负责设条件：闭合多紧、拉多长、张力多大。

| 分类 | 归属 |
|---|---|
| HS 分类 | 人体气鸣（簧振 + 滤波） |
| 起振门槛 | 约 2–3 cmH₂O |
| 八音：不适用 | 八音按材料分类，人体不在其中 |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="How the voice works: the MEAD cycle — convergent glottis pushes open, divergent glottis presses closed, the mucosal wave sets the phase, aerodynamic force always in phase with motion; plus the phonation threshold and the singer's formant">
 <rect x="0" y="0" width="640" height="380" fill="#0D0C0A"/>
 <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
 <text x="20" y="22">发声原理 · 声音是被风吹出来的</text>
 <text x="20" y="44" font-size="11" fill="#6E6A64">神经只设边界条件，剩下的交给风 —— 一台自持振荡的乐器</text>

 <!-- MEAD 循环两态 -->
 <text x="20" y="76" font-size="11" fill="#A9A49B" font-weight="600">收敛 → 发散：风永远顺着它推（Titze 1980）</text>
 <!-- 收敛（开启相） -->
 <g transform="translate(30,90)">
 <rect x="0" y="0" width="270" height="96" rx="6" fill="none" stroke="#3A3733" stroke-width="1"/>
 <text x="12" y="18" font-size="10" fill="#E8C547" font-weight="600">开启相 · 收敛（下闭上开）</text>
 <path d="M20 44 L20 76 M120 30 L120 76" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
 <path d="M20 44 L120 30" stroke="#E8C547" stroke-width="1" stroke-dasharray="3 3"/>
 <path d="M20 76 L120 76" stroke="#6E6A64" stroke-width="0.8"/>
 <text x="134" y="42" font-size="9" fill="#E8C547">气流外推 →</text>
 <text x="134" y="58" font-size="9" fill="#6E6A64">助力开启</text>
 <path d="M12 84 L250 84" stroke="#3A3733" stroke-width="0.6"/>
 <text x="12" y="94" font-size="8.5" fill="#6E6A64">肺内气压 ↑（声门下方）</text>
 </g>
 <!-- 发散（闭合相） -->
 <g transform="translate(340,90)">
 <rect x="0" y="0" width="270" height="96" rx="6" fill="none" stroke="#E07A3F" stroke-width="1.2"/>
 <text x="12" y="18" font-size="10" fill="#E07A3F" font-weight="600">闭合相 · 发散（上闭下开）</text>
 <path d="M20 30 L20 76 M120 44 L120 76" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
 <path d="M20 30 L120 44" stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3"/>
 <path d="M20 76 L120 76" stroke="#6E6A64" stroke-width="0.8"/>
 <text x="134" y="42" font-size="9" fill="#E07A3F">← 压力内压</text>
 <text x="134" y="58" font-size="9" fill="#6E6A64">助力闭合</text>
 <path d="M12 84 L250 84" stroke="#3A3733" stroke-width="0.6"/>
 <text x="12" y="94" font-size="8.5" fill="#6E6A64">黏膜波：下缘先动（行波上行）</text>
 </g>

 <!-- 门槛 -->
 <rect x="20" y="200" width="600" height="46" rx="6" fill="none" stroke="#E8C547" stroke-width="1.2"/>
 <text x="32" y="220" font-size="10.5" fill="#E8C547" font-weight="600">起振门槛：2–3 cmH₂O（a very small force）</text>
 <text x="32" y="238" font-size="9.5" fill="#6E6A64">干燥 · 肿胀 · 僵硬 → 门槛升高 —— 「嗓子哑了」的物理学是门槛升高，不是肺变小了。</text>

 <!-- singer's formant -->
 <text x="20" y="272" font-size="11" fill="#A9A49B" font-weight="600">Singer's formant：穿透乐队的那道缝（2,500–3,500 Hz）</text>
 <rect x="20" y="284" width="600" height="40" rx="4" fill="none" stroke="#3A3733" stroke-width="0.8"/>
 <rect x="20" y="284" width="180" height="40" fill="#6E6A64" opacity="0.4"/>
 <rect x="380" y="284" width="240" height="40" fill="#6E6A64" opacity="0.4"/>
 <rect x="380" y="284" width="90" height="40" fill="#E07A3F" opacity="0.85"/>
 <text x="30" y="308" font-size="9" fill="#A9A49B">乐队最响区（低频）</text>
 <text x="388" y="308" font-size="9" fill="#E8C547">人声共振峰</text>
 <text x="500" y="308" font-size="9" fill="#6E6A64">乐器泛音区</text>
 <text x="20" y="344" font-size="9.5" fill="#6E6A64">声带提供声源，声道共鸣与发声方式共同影响音色和穿透力。</text>

 <!-- 声质谱 -->
 <text x="20" y="368" font-size="9.5" fill="#A9A49B">声质谱：breathy（闭合不紧）→ flow（平衡）→ pressed（气流不够）—— 好声音是中间的流量平衡。</text>
 </g>
</svg>
```

## 伯努利解释不了一半

旧说法是气流快、压力低，两片声带被吸在一起。可只靠这个，振动很快会衰减。Titze 在 1980 年给出修正：声门开启时呈收敛形，气流向外推；闭合时呈发散形，压力反过来向内压。气动力始终与运动同相，风永远顺着它正在走的方向推，这才是自持振荡。让几何成立的是黏膜波：覆盖层比声带主体松，一层松一层紧，表面波才能从下往上走。疤痕或水肿限制这层波，声音就变粗、变费力。

## 门槛只有两三厘米水柱

健康嗓音起振只需要 2 到 3 厘米水柱的气压，很小。干燥、肿胀、僵硬都会把门槛抬高，所以脱水或喉炎时说话费劲，不是肺变小了。音高由一对对抗肌管理：环甲肌拉长拉紧，音升高；甲杓肌缩短放松，音降低。男声说话基频约 85 到 180 Hz，女声 165 到 255 Hz，儿童中位数约 250 Hz。

```range
{"range":"C2–C7","common":"C2–C7","caption":"发声原理的「音域」（人声全幅 · 各声区合幅）","caption_en":"How the voice works 「range」 (the voice's full span · all registers combined)","note":"发声原理属人体气鸣（簧振 + 滤波）：肺设气压，声带在肌弹性-空气动力学说（MEAD）下自持振荡——神经只设初始条件（闭合度/张力/长度），不直接驱动振动周期；Titze 1980 证明主导机制是声门的收敛-发散几何（开启相下闭上开、闭合相上闭下开，气动力永远与运动同相），黏膜波（覆盖层比体层松、行波上行）是相位差的来源。起振门槛 2–3 cmH₂O（干燥/肿胀/僵硬则升高）。音域取人声全幅（约 C2–C7）：modal（胸声）· head（头声）· falsetto（假声）· whistle（哨声）· vocal fry 各声区；singer's formant 聚集在 2,500–3,500Hz。男声基频 85–180Hz · 女声 165–255Hz · 儿童约 250Hz。","note_en":"Vocal production is a bodily aerophone (reed vibration + filtering): the lungs set pressure, the folds oscillate self-sustained under the myoelastic-aerodynamic theory (MEAD) — nerves only set initial conditions (adduction, tension, length), never driving the cycle directly; Titze 1980 showed the dominant mechanism is the glottis's convergent-divergent geometry (opening: closed at bottom, open at top; closing: the reverse — the aerodynamic force always in phase with motion), with the mucosal wave (the cover looser than the body, the wave travelling upward) as the source of the phase difference. The phonation threshold is 2–3 cmH₂O (higher when dry, swollen or stiff). The range spans the voice's full compass (roughly C2–C7): modal · head · falsetto · whistle · vocal fry; the singer's formant clusters at 2,500–3,500Hz. Male fundamental 85–180Hz · female 165–255Hz · children about 250Hz."}
```

## 那道 2.5 kHz 的缝

声带振动提供声源，咽腔、口腔和鼻腔参与改变声音的共鸣特征。歌唱中的高频能量分布会受声道形状、音高、元音和唱法影响，不能写成“训练与演化各占一半”。听辨时可比较同一音高、相近响度下不同元音的音色，不要把气声或压迫感只归因于某一个气流数值。

```audiolab
{"type":"instrument","gm":"Choir Aahs","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"合唱音色上的音高短句","label_en":"A pitched phrase using a choir sound","hint":"这段GM Choir Aahs短句用来听相近元音上的音高变化，不是声带振动或气压测量。仅凭采样音色不能区分具体声门状态，也不能用于判断嗓音健康。","hint_en":"This GM Choir Aahs phrase illustrates pitch changes on a similar vowel, not vocal-fold motion or pressure measurements. A sample alone cannot establish a glottal condition or voice health."}
```

:::

::: en

## One breath turns two folds into an instrument

Relax your lips and blow: they start to buzz. The vocal folds do the same. The lungs supply pressure, the folds come together, air passes, and the vibration sustains itself without a nerve striking it beat by beat. Nerves only set the conditions: how tightly the folds close, how long they are, how much tension they carry.

| Class | Assignment |
|---|---|
| HS class | bodily aerophone (reed vibration + filtering) |
| Threshold | about 2–3 cmH₂O |
| Bayin | outside it — the bayin sorts by material, and a body is not one |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="How the voice works: the MEAD cycle — convergent glottis pushes open, divergent glottis presses closed, the mucosal wave sets the phase, aerodynamic force always in phase with motion; plus the phonation threshold and the singer's formant">
 <rect x="0" y="0" width="640" height="380" fill="#0D0C0A"/>
 <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
 <text x="20" y="22">How the voice works · blown into being</text>
 <text x="20" y="44" font-size="11" fill="#6E6A64">Nerves set the boundary conditions, the wind does the rest — a self-sustained instrument</text>

 <text x="20" y="76" font-size="11" fill="#A9A49B" font-weight="600">Convergent → divergent: the wind always pushes with it (Titze 1980)</text>
 <g transform="translate(30,90)">
 <rect x="0" y="0" width="270" height="96" rx="6" fill="none" stroke="#3A3733" stroke-width="1"/>
 <text x="12" y="18" font-size="10" fill="#E8C547" font-weight="600">Opening · convergent</text>
 <path d="M20 44 L20 76 M120 30 L120 76" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
 <path d="M20 44 L120 30" stroke="#E8C547" stroke-width="1" stroke-dasharray="3 3"/>
 <path d="M20 76 L120 76" stroke="#6E6A64" stroke-width="0.8"/>
 <text x="134" y="42" font-size="9" fill="#E8C547">air pushes out →</text>
 <text x="134" y="58" font-size="9" fill="#6E6A64">assists opening</text>
 <path d="M12 84 L250 84" stroke="#3A3733" stroke-width="0.6"/>
 <text x="12" y="94" font-size="8.5" fill="#6E6A64">subglottal pressure ↑</text>
 </g>
 <g transform="translate(340,90)">
 <rect x="0" y="0" width="270" height="96" rx="6" fill="none" stroke="#E07A3F" stroke-width="1.2"/>
 <text x="12" y="18" font-size="10" fill="#E07A3F" font-weight="600">Closing · divergent</text>
 <path d="M20 30 L20 76 M120 44 L120 76" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
 <path d="M20 30 L120 44" stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3"/>
 <path d="M20 76 L120 76" stroke="#6E6A64" stroke-width="0.8"/>
 <text x="134" y="42" font-size="9" fill="#E07A3F">← pressure presses in</text>
 <text x="134" y="58" font-size="9" fill="#6E6A64">assists closing</text>
 <path d="M12 84 L250 84" stroke="#3A3733" stroke-width="0.6"/>
 <text x="12" y="94" font-size="8.5" fill="#6E6A64">mucosal wave: lower edge leads</text>
 </g>

 <rect x="20" y="200" width="600" height="46" rx="6" fill="none" stroke="#E8C547" stroke-width="1.2"/>
 <text x="32" y="220" font-size="10.5" fill="#E8C547" font-weight="600">Phonation threshold: 2–3 cmH₂O (a very small force)</text>
 <text x="32" y="238" font-size="9.5" fill="#6E6A64">Dry · swollen · stiff → the threshold rises — a hoarse voice is a threshold problem, not smaller lungs.</text>

 <text x="20" y="272" font-size="11" fill="#A9A49B" font-weight="600">The singer's formant: the gap that pierces an orchestra (2,500–3,500 Hz)</text>
 <rect x="20" y="284" width="600" height="40" rx="4" fill="none" stroke="#3A3733" stroke-width="0.8"/>
 <rect x="20" y="284" width="180" height="40" fill="#6E6A64" opacity="0.4"/>
 <rect x="380" y="284" width="240" height="40" fill="#6E6A64" opacity="0.4"/>
 <rect x="380" y="284" width="90" height="40" fill="#E07A3F" opacity="0.85"/>
 <text x="30" y="308" font-size="9" fill="#A9A49B">orchestra's loud band (low)</text>
 <text x="388" y="308" font-size="9" fill="#E8C547">voice formant</text>
 <text x="500" y="308" font-size="9" fill="#6E6A64">instrument harmonics</text>
 <text x="20" y="344" font-size="9.5" fill="#6E6A64">The vocal folds provide the source; vocal-tract resonance and technique shape tone and projection.</text>

 <text x="20" y="368" font-size="9.5" fill="#A9A49B">Timbre spectrum: breathy (loose closure) → flow (balanced) → pressed (too little air) — a good voice is the balance.</text>
 </g>
</svg>
```

## Bernoulli explains only half

The old account says fast air means low pressure, and the folds are sucked together. On that alone the oscillation would soon die. Titze corrected it in 1980: the glottis is convergent while opening, so pressure pushes outward, and divergent while closing, so pressure reverses and pushes inward. The aerodynamic force stays in phase with the motion, always pushing the way the folds are already going, and that is what sustains the cycle. The geometry depends on the mucosal wave: the cover is looser than the body, and a loose layer over a stiff one lets a surface wave travel upward. Scarring or swelling limits that wave, and the voice turns rough and effortful.

```range
{"range":"C2–C7","common":"C2–C7","caption":"发声原理的「音域」（人声全幅 · 各声区合幅）","caption_en":"How the voice works 「range」 (the voice's full span · all registers combined)","note":"发声原理属人体气鸣（簧振 + 滤波）：肺设气压，声带在肌弹性-空气动力学说（MEAD）下自持振荡——神经只设初始条件（闭合度/张力/长度），不直接驱动振动周期；Titze 1980 证明主导机制是声门的收敛-发散几何（开启相下闭上开、闭合相上闭下开，气动力永远与运动同相），黏膜波（覆盖层比体层松、行波上行）是相位差的来源。起振门槛 2–3 cmH₂O（干燥/肿胀/僵硬则升高）。音域取人声全幅（约 C2–C7）：modal（胸声）· head（头声）· falsetto（假声）· whistle（哨声）· vocal fry 各声区；singer's formant 聚集在 2,500–3,500Hz。男声基频 85–180Hz · 女声 165–255Hz · 儿童约 250Hz。","note_en":"Vocal production is a bodily aerophone (reed vibration + filtering): the lungs set pressure, the folds oscillate self-sustained under the myoelastic-aerodynamic theory (MEAD) — nerves only set initial conditions (adduction, tension, length), never driving the cycle directly; Titze 1980 showed the dominant mechanism is the glottis's convergent-divergent geometry (opening: closed at bottom, open at top; closing: the reverse — the aerodynamic force always in phase with motion), with the mucosal wave (the cover looser than the body, the wave travelling upward) as the source of the phase difference. The phonation threshold is 2–3 cmH₂O (higher when dry, swollen or stiff). The range spans the voice's full compass (roughly C2–C7): modal · head · falsetto · whistle · vocal fry; the singer's formant clusters at 2,500–3,500Hz. Male fundamental 85–180Hz · female 165–255Hz · children about 250Hz."}
```

## The threshold is two or three centimetres of water

A healthy voice starts with 2 to 3 cmH₂O, a very small force. Dryness, swelling and stiffness raise the threshold, which is why speaking feels hard when you are dehydrated or have laryngitis; the lungs have not shrunk. Pitch is managed by a pair of opposing muscles: the cricothyroid lengthens and tightens the folds and the note rises, the thyroarytenoid shortens and relaxes them and it falls. Speaking fundamentals run about 85–180 Hz for men, 165–255 Hz for women, and around 250 Hz for children.

## That gap at 2.5 kHz

The vibrating vocal folds provide the source, while the throat, mouth and nasal cavities shape resonance. High-frequency energy in singing varies with vocal-tract shape, pitch, vowel and technique; there is no basis here for dividing its cause equally between training and evolution. Compare vowels at similar pitch and loudness rather than attributing breathiness or pressed quality to a single airflow value.

```audiolab
{"type":"instrument","gm":"Choir Aahs","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"合唱音色上的音高短句","label_en":"A pitched phrase using a choir sound","hint":"这段GM Choir Aahs短句用来听相近元音上的音高变化，不是声带振动或气压测量。仅凭采样音色不能区分具体声门状态，也不能用于判断嗓音健康。","hint_en":"This GM Choir Aahs phrase illustrates pitch changes on a similar vowel, not vocal-fold motion or pressure measurements. A sample alone cannot establish a glottal condition or voice health."}
```
:::
