---
id: linndrum
site: inst
cat: I11
title: LinnDrum
title_en: The LinnDrum
summary: 1982年推出的采样鼓机，以音序器编排鼓声，并可调整部分音色与混音
summary_en: A sampling drum machine released in 1982, with sequencing and controls for selected sounds and their balance
level: standard
range_policy: variable
range_basis: LinnDrum回放不同的鼓采样，各声音可用音高和调节范围不同，不能用一个键盘式音域代表整台鼓机。
tags: [乐器, 电子, 电鸣, 西洋, 鼓机, LinnDrum, LM-1, 采样鼓机]
tags_en: [instrument, electronic, electrophone, western, drum-machine, linndrum, lm-1, sampling]
alias: [LinnDrum, linndrum, LM-1, LM-2, Linn 9000, Roger Linn]
order: 190
links:
 - "[[instrument:tr-808]]"
 - "[[instrument:tr-909]]"
 - "[[instrument:midi-controller]]"
 - "[[instrument:samplers]]"
 - "[[concept:articulation]]"
 - "[[concept:pitch]]"
instances:
  - chinafolk-000533 | 观察音符的起音位置与时值 | Inspect note onsets and durations
  - chinafolk-005954 | 查看声部与通道安排 | Inspect parts and channel assignments
  - chinafolk-000653 | 查看力度值与重复音型 | Inspect velocity values and repeated patterns
sources:
  - "https://www.rogerlinndesign.com/about/about-museum"
  - "https://www.rogerlinndesign.com/about/roger-faq"
updated: 2026-11-02
---

::: zh
HS 分类：电鸣；这是电子采样回放系统，所采鼓声的原始乐器另有各自分类。

```svg
<svg viewBox="0 0 640 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="LinnDrum：功能示意">
<text x="24" y="30" font-size="16" fill="#A9A49B">LinnDrum：功能示意</text><rect x="22" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="80" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">节奏步骤</text><rect x="182" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="240" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">样本触发</text><rect x="342" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="400" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">混音控制</text><rect x="502" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="560" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">音频输出</text><path d="M144,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/><path d="M304,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/><path d="M464,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/>
</svg>
```

LinnDrum 是 Linn Electronics 在1982年推出的采样鼓机，接续 LM-1。它把预先录制的鼓声存入芯片，再由音序器安排触发时间。应把采样声音、节奏编程和机器的混音功能分开理解：一段节奏像不像鼓手，并不只由采样决定。

## 它与前后型号有什么区别

| 型号 | 区别 |
|---|---|
| LM-1 | 更早的 Linn 采样鼓机，不能与 LinnDrum 混用名称 |
| LinnDrum | 增加镲片、较长采样及外部鼓触发输入；可开盖更换声音芯片 |
| Linn 9000 | 后来的另一款机器，加入用户采样、力度垫与多轨MIDI音序功能 |

这些变化来自不同型号，不能把 Linn 9000 的功能全部算到 LinnDrum 上。老机器的改装也可能改变同步和声音配置，查看实物时应核对型号、芯片及接口。

## 从一个小节理解编程

先写稳定的底鼓与军鼓，再加入踩镲。保留一份等时值版本，另一份只改变部分音符的时间位置，比较节奏重心。Swing 不是随机把每一击移走；不同步进分组会产生不同的长短关系。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q e e q","bpm":90,"label":"一个四拍节奏型","label_en":"A four-beat rhythm pattern","hint":"拍数为1＋1＋半拍＋半拍＋1。这是节奏参考，不是LinnDrum硬件音色。","hint_en":"The durations are 1 + 1 + ½ + ½ + 1 beats. This is a rhythm reference, not a LinnDrum sound."}
```

下方MIDI可用来观察起音位置、时值和力度。播放器的声音由所选音源产生，不能据此认定文件由某台鼓机录制。

## 写作时怎样比较

先保持速度和音符相同，只更换鼓声；再固定声音，只修改节奏。最后回到整首音乐，检查底鼓与贝斯、军鼓与重拍的关系。这样能分清变化来自声音、时间安排还是配器，避免把所有效果都归给“复古”。
:::

::: en
HS class: electrophone; an electronic sample-playback system, distinct from the acoustic classification of each sampled drum.

```svg
<svg viewBox="0 0 640 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="LinnDrum: functional outline">
<text x="24" y="30" font-size="16" fill="#A9A49B">LinnDrum: functional outline</text><rect x="22" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="80" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">Pattern</text><rect x="182" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="240" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">Samples</text><rect x="342" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="400" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">Mix</text><rect x="502" y="85" width="116" height="54" rx="8" fill="#17171A" stroke="#E07A3F"/><text x="560" y="117" text-anchor="middle" font-size="13" fill="#A9A49B">Audio</text><path d="M144,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/><path d="M304,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/><path d="M464,112 h26 l-7,-5 m7,5 l-7,5" fill="none" stroke="#E07A3F"/>
</svg>
```

The LinnDrum is a sampling drum machine released by Linn Electronics in 1982 as the successor to the LM-1. Stored drum recordings are triggered by a sequencer. Sample choice, timing and mixing are separate parts of the result.

## Keep the models distinct

| Model | Distinction |
|---|---|
| LM-1 | The earlier Linn sampling machine, a different model |
| LinnDrum | Added cymbals, longer samples and external drum-trigger inputs; sound chips could be exchanged inside |
| Linn 9000 | A later machine with user sampling, velocity pads and multi-track MIDI sequencing |

Do not assign every Linn 9000 feature to the LinnDrum. Modifications may also change an old machine’s sounds or synchronisation. Check the actual model, chips and connections.

## Program one bar

Begin with kick and snare, then add hi-hat. Keep an evenly spaced version and change selected timing positions in a second version. Swing creates a particular long–short relationship; it is not random movement of every hit.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q e e q","bpm":90,"label":"一个四拍节奏型","label_en":"A four-beat rhythm pattern","hint":"拍数为1＋1＋半拍＋半拍＋1。这是节奏参考，不是LinnDrum硬件音色。","hint_en":"The durations are 1 + 1 + ½ + ½ + 1 beats. This is a rhythm reference, not a LinnDrum sound."}
```

Use the MIDI examples below to inspect onsets, durations and velocities. The selected player sound bank generates their audio; playback does not identify the hardware on which a file originated.

## Compare one change at a time

Keep timing fixed while replacing sounds, then keep the sounds while changing timing. Finally check kick against bass and snare against the main pulse in the arrangement. This separates sound choice, sequencing and scoring instead of attributing every difference to a vintage label.
:::
