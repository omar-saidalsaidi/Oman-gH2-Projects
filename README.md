# Oman-gH2-Projects

## نسيج عُمان — Fiber, Wool & Silk Thread Storytelling

`oman-flag-threads/index.html` is a self-contained, 35-second vertical (9:16, 1080×1920) motion experience celebrating the Omani flag and national identity. Open the file in any modern browser; nothing needs to be built.

- 5 procedurally rendered Canvas scenes linked by Z-axis push-through morphs: the Omani flag embroidered into burlap with chunky twisted yarn cords, which lift in a macro shot with depth-of-field blur → crimson Wahiba dunes + Nizwa Fort in yarn → emerald Jabal Akhdar terraces, silk palms & falaj → frankincense smoke coalescing into a silk dove → woven flag of Oman with the hollow calligraphic outro.
- Arabic RTL captions (IBM Plex Sans Arabic, Aref Ruqaa), a synthesized Web Audio soundtrack with a mute toggle, a scrubbable progress bar, and Play/Pause/Replay controls.
- **Download Video** (حفظ الفيديو): records the full 35 s as a clean 1080×1920 video (canvas, burned-in captions and soundtrack, no player controls) with `MediaRecorder` and saves it as MP4 (H.264) where the browser supports it, otherwise WebM. Recording runs in real time, so keep the tab visible.
- **Video prompts drawer**: frame-accurate Midjourney v6 (`--ar 9:16`) start/end keyframe prompts and Kling AI / Runway Gen-3 image-to-video and bridge prompts, with Copy, Copy all, Markdown and JSON export. The same content is in [`oman-flag-threads/PROMPTS.md`](oman-flag-threads/PROMPTS.md).

Keyboard: `Space` play/pause · `R` replay · `M` mute · `P` prompts.
