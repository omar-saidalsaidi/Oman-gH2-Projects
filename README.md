# Oman-gH2-Projects

## نسيج عُمان — Fiber, Wool & Silk Thread Storytelling

`oman-flag-threads/index.html` is a self-contained, 40-second vertical (9:16, 1080×1920) motion experience celebrating the Omani flag and national identity. Open the file in any modern browser; nothing needs to be built.

- 5 procedurally rendered Canvas scenes linked by Z-axis push-through morphs: the Omani flag embroidered into burlap with chunky twisted yarn cords, which lift in a macro shot with depth-of-field blur → crimson Wahiba dunes + Nizwa Fort in yarn → emerald Jabal Akhdar terraces, silk palms & falaj → frankincense smoke coalescing into a silk dove → woven flag of Oman with the hollow calligraphic outro, then a closing card crediting the student (عبدالعزيز بن عمر السعيدي · الصف الأول · مدرسة الريان للتعلم الأساسي).
- Arabic RTL captions (IBM Plex Sans Arabic, Aref Ruqaa), a synthesized Web Audio soundtrack with a mute toggle, a scrubbable progress bar, and Play/Pause/Replay controls.
- **Download Video** (حفظ الفيديو): records the full 40 s as a clean 1080×1920 video (canvas, burned-in captions and soundtrack, no player controls) with `MediaRecorder` and saves it as MP4 (H.264) where the browser supports it, otherwise WebM. Recording runs in real time, so keep the tab visible.
- **Video prompts drawer**: frame-accurate Midjourney v6 (`--ar 9:16`) start/end keyframe prompts and Kling AI / Runway Gen-3 image-to-video and bridge prompts, with Copy, Copy all, Markdown and JSON export. The same content is in [`oman-flag-threads/PROMPTS.md`](oman-flag-threads/PROMPTS.md).

Keyboard: `Space` play/pause · `R` replay · `M` mute · `P` prompts.

## مغامرة الهيدروجين الأخضر — Green Hydrogen Kids' Game

`green-hydrogen-game/index.html` is a self-contained, Arabic (RTL) interactive game for children under 14 about green hydrogen. Open it in any browser; it works on phones, tablets and computers.

Hydro, a friendly H₂ molecule, guides players through four stations, each worth up to 3 stars:

1. **الإنتاج (Production)**: tap the sun and the wind turbine to make clean electricity, then run the electrolyser to split water into H₂ and O₂. Tapping the gas factory teaches the difference between grey and green hydrogen. A passing cloud shows why solar and wind work together.
2. **التخزين (Storage)**: press and hold to compress hydrogen to 700 bar, then cool it to −253 °C until it turns liquid. Go past the green zone and the safety valve resets the tank.
3. **النقل (Transport)**: rotate pipe pieces to connect the green plant to the city, then choose pipeline, truck or ship for three delivery cases (Duqm, a remote fuel station, export by sea).
4. **الاستخدام (Use)**: solve riddles to send hydrogen to a fuel-cell school bus, a green-steel plant, a farm (ammonia fertiliser) and a ship, then see how a fuel cell turns H₂ + O₂ into electricity and water.

The game ends with a printable-style certificate (شهادة مهندس الهيدروجين الأخضر) showing the child's name and stars. Each station shows "هل تعلم؟" facts, including Oman-specific ones (sun and wind in Dhofar and Duqm, the 2030 goal).
