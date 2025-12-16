---
title: "First ARG Treasure Hunt by Neuko Team"
description: "A full breakdown of NeukoAI’s first ARG treasure hunt: hidden channels, encrypted messages, riddles, and the final on-chain reward."
date: "2025-12-16"
author: "@DendiRedemption"
tags: ["ARG", "NeukoAI", "Treasure Hunt", "Crypto", "Puzzle"]
draft: false
---

# First ARG Treasure Hunt by Neuko Team

> **Debrief by [@DendiRedemption](https://x.com/DendiRedemption)**

On **November 5, 2025**, the Neuko team published a post on X linking to their website, **neuko.ai**, with a live update applied. The update introduced a page containing a **6-symbol password field**.
https://x.com/neukoai/status/1984362507784351883

This password was discoverable from a **previous community-solved puzzle**, originally posted on October 31, 2025:  (WILL PUT LINK TO THE ARTICLE)

---

## The TV Interface & Channel Discovery

After entering the correct password, a **full interface unlocked**, revealing a TV-style display with channels numbered **0–999**.

Most channels showed only white noise. However, the community quickly discovered that **certain channels contained signals**.

A major contribution was made by **@afkboom**, who used software tools to identify all channels that carried active content.

---

## Active Channels at the Time

| Channel | Title |
|------:|------|
| 1 | G*BOY |
| 13 | GAMBLIN! |
| 28 | The Crubtub |
| 49 | Real History |
| 55 | No Signal |
| 77 | archives_x_01.vid |
| 86 | archives_x_02.vid |
| 101 | archives_x_03.vid |
| 200 | Rabbits! |
| 203 | archives_x_04.vid |
| 463 | Moths! |
| 550 | archives_x_05.vid |
| 717 | archives_x_06.vid |
| 777 | archives_x_07.vid |

Initial attention focused on channels with visible broadcasts  
**1, 13, 28, 49, 200, 463**

However, the **most important channels** turned out to be:

**55, 77, 86, 101, 203, 550, 717, 777**

These channels appeared empty at first, but if watched long enough, they revealed **hidden messages**.

---

## Channel 55 - Spectrogram Message

Channel 55 had no visible broadcast but contained an **audio file with a hidden spectrogram message**.

<details>
<summary><strong>Click to view image</strong></summary>

![Spectrogram decode](./spectrogram.png)

</details>

Decoded message:

> **“signals hide where the channels hum.  
> the key is underneath the static.”**

---

## The `archives_x` Series (01–07)

Channels **77, 86, 101, 203, 550, 717, 777** followed a consistent naming pattern:

- from archives_x_01.vid  to archives_x_07.vid  

<details>
<summary><strong>View archives_x_01-07 frames</strong></summary>

![Frame 1](./archives_x_01_frame_1.png)
![Frame 2](./archives_x_01_frame_2.png)
![Frame 3](./archives_x_01_frame_3.png)

</details>

Each video contained **one or more clues** contributing to the final solution.

---

## Hidden Messages by Channel

### Channel 77 - archives_x_01.vid  
Related post: https://x.com/neukoai/status/1977763395408429229

- “EVERY SCREEN COUNTS”  
- “COUNT THE BLINKS OF THE MARK”

---

### Channel 86 - archives_x_02.vid  
Related post: https://x.com/neukoai/status/1979268208340406384

- “WHEN G304 ENTERS THE FRAME, MARK THE TIME.”

---

### Channel 101 - archives_x_03.vid  
Related post: https://x.com/neukoai/status/1980355518771392550

- “RECORD THE HOURS GIVEN.”  
- “COUNT THE BLOSSOMS TINTED PINK”

---

### Channel 203 - archives_x_04.vid  
Related post: https://x.com/neukoai/status/1981125805104312473

- “HOW MANY TIMES DOES THE SIREN BREAK THE SILENCE?”

---

### Channel 550 - archives_x_05.vid  
Related post: https://x.com/neukoai/status/1981740247504269582

- “CHECK THE MONITOR ID. KEEP THE FIRST PAIR OF NUMBERS.”  
- “FIND THE EMERGENCY CODE. KEEP ITS FIRST DIGIT ONLY.”

---

### Channel 717 - archives_x_06.vid  
Related post: https://x.com/neukoai/status/1982894878280569063

- “THE SNAKE STRIKES. RECORD ITS CHANNEL.”  
- “THE NUMBER BRIEFLY CARRYING STREETWISE.”

---

### Channel 777 - archives_x_07.vid  
Related post: https://x.com/neukoai/status/1984362507784351883

- “COUNT THE FROGS THAT FELL.”  
- “THE SIGNAL RUNS THROUGH HEMLET. RECORD ITS MODEL.”

---

## Interpreting the Riddles

Exactly **7 channels** contained messages.

Each riddle referenced a previously released **NeukoAI video on X**. Coincidentally, **exactly 7 such videos existed** at the time.

Each riddle resolved to a **number**. Across all messages, **12 numbers** were extracted - strongly suggesting a **12-word seed phrase**.

---

## Extracted Numbers

9 10 17 7 24 4 12 8 14 15 25 2

---

## Discovering `key.txt`

By inspecting the **network tab** in browser dev tools on neuko.ai, the following file was discovered:

https://www.neuko.ai/key.txt

It contained **30 indexed words**:

| # | Word | # | Word | # | Word |
|--:|------|--:|------|--:|------|
| 1 | ember | 11 | moss | 21 | synth |
| 2 | farm | 12 | focus | 22 | delta |
| 3 | static | 13 | gravel | 23 | echo |
| 4 | first | 14 | step | 24 | chicken |
| 5 | pulse | 15 | ready | 25 | square |
| 6 | fracture | 16 | lantern | 26 | coil |
| 7 | apple | 17 | crawl | 27 | fever |
| 8 | wife | 18 | glass | 28 | shrine |
| 9 | record | 19 | tether | 29 | token |
| 10 | deny | 20 | marrow | 30 | hush |

---

## Final Seed Phrase

Mapping the extracted numbers to the indexed words produced the final **12-word seed phrase**:

**record deny crawl apple chicken first focus wife step ready square farm**

---

## The Reward

The seed phrase unlocked the wallet: 71o2Q6oKUbTujnHmKXSSj2VD3EJZ3vUbwGTRN9yei32D


Inside were **3 Snake Badges**, claimed in a timed race by **@DendiRedemption**.

---

## Extra Fact

Originally, Channel 717 broadcasted:

> “JPX SPEAK ONCE. NOT ITS CHANNEL.”

This was later identified as an error and updated mid-solve to:

> **“THE SNAKE STRIKES. RECORD ITS CHANNEL.”**

---

*End of debrief.*

[index0]


