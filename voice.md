---
id: voice
site: inst
cat: I13
title: 人声
title_en: The human voice
summary: 肺提供气流，声带产生有声音源，声道塑造元音与音色
summary_en: Airflow powers vocal-fold vibration, while the vocal tract shapes vowels and timbre
range_policy: variable
range_basis: 个人音域、舒适音区与当天发声状态不同，本页只提供具体旋律的音高示例，不把全部人类声部拼成一种统一乐器音域。
level: standard
tags:
  - 人声
  - 歌唱
  - 声乐
  - 发声
tags_en:
  - voice
  - singing
  - vocal-production
alias: [人声, voice, 歌唱, 歌喉, 声带, vocal folds, SATB]
order: 199
links:
 - "[[instrument:talk-box]]"
 - "[[instrument:vocoder]]"
 - "[[instrument:auto-tune]]"
 - "[[instrument:moog-modular]]"
 - "[[concept:pitch]]"
 - "[[concept:timbre]]"
instances:
 - chinafolk-004861 | 《沙沙的喉咙噪不高》 — 在曲目页找出旋律最高与最低音，区分这条旋律的音域和歌手本人的音域。（仅限学习研究）
 - chinafolk-002119 | 《党给的好歌喉》 — 比较长音与短音的连接，观察乐句轮廓；MIDI播放不提供真人咬字证据。（仅限学习研究）
 - chinafolk-000570 | 《姑嫂对唱》 — 查看旋律的起落与分句；不能仅凭“对唱”的标题认定文件含两个声部。（仅限学习研究）
sources:
  - "UNSW — Voice Acoustics: an introduction. https://www.phys.unsw.edu.au/jw/voice.html"
  - "NIDCD — Taking Care of Your Voice. https://www.nidcd.nih.gov/health/taking-care-your-voice"
updated: 2026-11-02
---

::: zh

人声由呼吸、喉部发声和声道调节共同产生。它既能唱出持续音高，也能通过元音、辅音和语调传递语言；无词歌唱、哼鸣和气声则展示了其他用法。

| 说明 | 内容 |
|---|---|
| HS 分类 | 人声（人体发声，非电鸣）；此页不套用独立器乐的HS编号 |

## 肺、声带与声道

肺呼出的空气提供能量。有声歌唱时，喉内两片声带周期性振动，把气流调制成声波；声带的长度、张力、参与振动的组织和发声方式共同影响音高。不能把“越用力，音越高”当成发声方法。

喉部以上的咽腔、口腔与鼻腔影响共振。舌、唇、下颌与软腭改变声道形状，调整频谱中的共振峰，因此同一音高也能唱成不同元音。声源与声道会互相作用，“声源—滤波器”是帮助理解的模型，不是人体与电子合成器完全相同的证明。

```svg
<svg viewBox="0 0 640 244" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="人声发声：供气、振动与共振">
<text x="24" y="30" font-family="system-ui,sans-serif" font-size="17" font-weight="700" fill="#A9A49B">人声发声：供气、振动与共振</text>
<rect x="24" y="52" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="70" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">呼吸系统</text>
<text x="38" y="87" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">提供发声所需的气流与气压</text>
<rect x="24" y="110" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="128" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">声带</text>
<text x="38" y="145" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">有声歌唱时周期性振动，形成声源</text>
<rect x="24" y="168" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="186" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">声道与发音器官</text>
<text x="38" y="203" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">舌、唇、下颌、软腭改变共振与语音</text>
</svg>
```

## 音高相同，元音仍可不同

在舒适的中音区持续唱一个音，从“啊”转成“衣”，目标音高可以保持，口型与共振峰却会改变。反过来，用同一个“啊”由 C4 唱到 E4，是音高上升大三度；这两种变化分别说明音高与音色不能混为一谈。

## 音域与声部

音域是能够发出的音高范围，常用音区则是能持续、清楚、较轻松完成乐句的区域。二者都随个人、训练和当天状态而变；不存在适用于所有人的固定“两八度标准”。合唱的 S、A、T、B 是四个声部，独唱还常用次女高、男中音等分类，见 [[instrument:voice-types|声部分类]]。

```audiolab
{"type":"instrument","gm":"Choir Aahs","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"合成人声：跨两个八度的琶音","label_en":"Synthesised voice: a two-octave arpeggio","hint":"C3 到 C5 展示音高跨度。GM 合唱音色不包含可辨认歌词，也不能展示真人的换声与呼吸控制。","hint_en":"C3–C5 illustrates a pitch span. A GM choir program does not demonstrate a real singer’s words, register changes or breath control."}
```

## 读谱与听录音

MIDI 保存的是音符、时值、力度等演奏信息，播放时由音源发声。合成人声可帮助确认旋律，但不能据此判断真人的声部、唱法或声带状态。比较歌手时，应听实际录音中的元音、起音、句尾、换声与语言处理。

歌唱时若出现持续嘶哑、疼痛或明显疲劳，应减少负荷并查明原因，参见 [[instrument:vocal-health|嗓音保护]]。


:::

::: en

The voice combines breathing, sound production in the larynx and shaping by the vocal tract. It can sustain musical pitches and convey language through vowels, consonants and intonation. Wordless singing, humming and breathy sounds offer other possibilities.

| Classification note | Description |
|---|---|
| HS class | Human voice: bodily sound production, not an electrophone; no separate instrument number is assigned here |

## Airflow, vocal folds and vocal tract

Exhaled air supplies energy. In voiced singing, the two vocal folds vibrate periodically, modulating airflow into sound waves. Pitch depends on their length, tension, vibrating tissue and mode of vibration. “Push harder to go higher” is not a sound description of technique.

Above the larynx, the pharynx, mouth and nasal passages affect resonance. Tongue, lips, jaw and soft palate change the tract’s shape and its spectral resonances, helping produce different vowels at one pitch. Source and tract also interact: the source–filter model is a useful approximation, not proof that a body works identically to an electronic synthesiser.

```svg
<svg viewBox="0 0 640 244" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Voice production: air, vibration and resonance">
<text x="24" y="30" font-family="system-ui,sans-serif" font-size="17" font-weight="700" fill="#A9A49B">Voice production: air, vibration and resonance</text>
<rect x="24" y="52" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="70" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">Respiratory system</text>
<text x="38" y="87" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Supplies airflow and pressure</text>
<rect x="24" y="110" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="128" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">Vocal folds</text>
<text x="38" y="145" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Periodic vibration produces a voiced source</text>
<rect x="24" y="168" width="592" height="45" rx="8" fill="#17171A"/>
<text x="38" y="186" font-family="system-ui,sans-serif" font-size="12" font-weight="700" fill="#E07A3F">Vocal tract and articulators</text>
<text x="38" y="203" font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">Tongue, lips, jaw and soft palate shape resonances and speech</text>
</svg>
```

## Same pitch, different vowel

On a comfortable middle note, moving from “ah” to “ee” can preserve pitch while changing articulation and resonances. Conversely, singing C4 then E4 on “ah” raises pitch by a major third. These are different kinds of change: pitch and timbre are related but not interchangeable.

## Range and parts

Range describes available pitches; tessitura describes the region in which a singer can sustain phrases comfortably and clearly. Both depend on the person, training and current condition. A fixed two-octave standard does not fit everyone. Choral S, A, T and B are four parts; solo classification also includes mezzo-soprano and baritone. See [[instrument:voice-types|voice classification]].

```audiolab
{"type":"instrument","gm":"Choir Aahs","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"合成人声：跨两个八度的琶音","label_en":"Synthesised voice: a two-octave arpeggio","hint":"C3 到 C5 展示音高跨度。GM 合唱音色不包含可辨认歌词，也不能展示真人的换声与呼吸控制。","hint_en":"C3–C5 illustrates a pitch span. A GM choir program does not demonstrate a real singer’s words, register changes or breath control."}
```

## Scores and recordings

MIDI stores performance information such as notes, durations and velocities; a sound source produces the playback. A synthetic voice can clarify a melody but cannot establish a real singer’s voice type, technique or vocal-fold condition. Use actual recordings to compare vowels, attacks, endings, register transitions and diction.

Persistent hoarseness, pain or marked fatigue calls for reduced load and assessment of the cause; see [[instrument:vocal-health|vocal health]].

:::
