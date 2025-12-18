---
title: "Neuko.ai TV Portal (Post #15) - Cipher Chain & Takeover Archive"
description: "Post #15 escalated the NeukoAI ARG into a full cipher chain involving QR codes, Pastebins, classical cryptography, and a locked takeover archive."
date: "2025-12-19"
author: "@DendiRedemption"
tags: ["ARG", "NeukoAI", "GBOY", "Cipher", "Pastebin", "ZIP", "Lore"]
draft: false
---

# Neuko.ai TV Portal (Post #15) – Cipher Chain & Takeover Archive

> **Debrief by [@DendiRedemption](https://x.com/DendiRedemption)**

**Post #15 (Dec 3, 2025):** Video released by [@NeukoAI](https://x.com/neukoai) - [https://x.com/neukoai/status/1996332652492943710](https://x.com/neukoai/status/1996332652492943710)

Post #15 marked a shift from passive observation to an explicit **cipher chain**, forcing solvers to loop between video, external links, and classical encryption methods.

<video controls width="100%"><source src="../../media/videos/posts/stack-up-x.mp4" type="video/mp4"></video>

---

## The Post

<video controls width="100%">
  <source src="../../media/videos/posts/post_2025_12_03.mp4" type="video/mp4">
</video>

At the timing of "00:08", a **QR code** flashes briefly on screen.

---
![QRBOX](https://raw.githubusercontent.com/dendiredemptionarc-svg/wiki/main/.gitbook/assets/QRBOX.png)


## QR Code → Pastebin #1

The QR code resolves to the following Pastebin:

```
https://pastebin.com/YY7LYT0v
```

Contents:

```
xgor lktik qke zcu ullykz luax  https://pastebin.com/srSMbcaM
```

At first glance, the message appears opaque, but its structure strongly suggests a classical substitution cipher.

---

## Caesar Cipher (-6)

Applying a **Caesar shift of -6** reveals:

```
rail fence key two offset four
```

Rather than a plaintext message, this line provides **explicit decryption parameters** for the next step.

---

## Pastebin #2 – Locked

The linked Pastebin is password-protected:

```
https://pastebin.com/srSMbcaM
```

With no password yet available, solvers were forced to return to the source: the video itself.

---

## Hidden Morse Code in the Video

Scene-by-scene inspection revealed subtle symbols in the top-left corner of the video:

<video controls width="100%"><source src="../../media/videos/posts/stack-up-morse.mp4" type="video/mp4"></video>

```
-  .  /
```

Interpreted as Morse code, the sequence resolves to:

```
-..- -. / ..- . ----- .--. .--.
```

Decoded output:

```
XN UE0PP
```

This string clearly does not resolve on its own, but matches the parameters revealed earlier.

---

## Rail Fence Cipher (Key: 2, Offset: 4)

Using:

- **Rail Fence key:** 2
- **Offset:** 4

Decrypting `XN UE0PP` produces:

```
XEN0 PUP
```

This serves as the **password** for Pastebin #2.

---

## Pastebin #2 – Unlocked

Unlocked contents:

```
it calls itself special, but the special thing is underneath.

GSVB ZIV MRSRORHN YFG DV YVMW GSVN DRGS SFNZMRGB
```

The phrasing immediately points toward a specific gboyspecial.com wesbite.

---

## GBOYSPECIAL – Underneath the Surface

The line *“it calls itself special”* references:

```
[https://gboyspecial.com](https://www.gboyspecial.com/)
```

Inspecting the site via DevTools reveals a console message:

```
special
ZG93bmxvYWRzL3Rha2VvdmVyLnppcA==
```

The encoded string is **Base64**.

Decoded result:

```
downloads/takeover.zip
```

Combined URL:

```
https://gboyspecial.com/downloads/takeover.zip
```

---

## takeover.zip – Archive Discovery

Inside the downloaded archive:

- `final_payload_locked.zip`
- `password.txt`

`password.txt` contains the following numeric sequence:

```
54 60 76 34 57 56 86 99 56
```

At this point, the archive remains locked.

---

![Takeoverzip files](https://raw.githubusercontent.com/dendiredemptionarc-svg/wiki/main/.gitbook/assets/takeoverzip.png)



## Atbash Cipher – Narrative as Instruction

Returning to the earlier encrypted line:

```
GSVB ZIV MRSRORHN YFG DV YVMW GSVN DRGS SFNZMRGB
```

Applying **Atbash cipher** yields:

```
THEY ARE NIHILISM BUT WE BEND THEM WITH HUMANITY
```

This line functions as both lore and a direct technical hint.

---

## Nihilist Cipher – Final Decryption

The message explicitly points to:

- **Cipher:** Nihilist
- **Key:** `HUMANITY`
- **Ciphertext:**

```
54 60 76 34 57 56 86 99 56
```

Using a standard Nihilist square with the key *HUMANITY*, the decrypted result is:

```
LETHIMRUN
```
---

![nihilist](https://raw.githubusercontent.com/dendiredemptionarc-svg/wiki/main/.gitbook/assets/nihilist.png)



## Final Payload

`LETHIMRUN` unlocks `final_payload_locked.zip`.

Inside is a collection of **lore documents, images, and the full GBOY manifesto**, marking the completion of Post #15’s cipher chain.

---

## Closing Notes

Post #15 stands apart for its structure

Those who followed the full path didn’t just unlock files - they proved themselves part of the decoding crew.

[index0]

## Related Posts

* [Post #14: TBD](post-14.md) - Previous post
* [Post #16: TBD](post-16.md) - Next post
