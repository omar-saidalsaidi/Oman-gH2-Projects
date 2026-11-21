<!-- Generated from PROMPT_PIPELINE in index.html -->
# Omani National Identity & Flag — Fiber, Wool & Silk Thread Storytelling

**Format:** Vertical 9:16 · 1080×1920 · 30 fps · 35.0 s (1050 frames)

## Style lock
- Seed: `--seed 7716`
- Style reference: After generating Scene 1 END, append  --sref <S1-END image URL> --sw 150  to every later Midjourney prompt for a consistent textile look.
- Palette: Omani crimson #DB161B, deep crimson #9E1115, emerald #008000, olive emerald #2E5A36, silk white #FFFFFF, burlap/sand #D9C7B2 / #C4AE94, falaj turquoise #4A8B9C
- Midjourney params: `--ar 9:16 --v 6.0 --style raw --s 250 --seed 7716`
- Kling: Kling AI (2.x) · Image to Video · Professional mode · Start & End Frame · 5 s or 10 s · Creativity/Relevance 0.5 · paste NEGATIVE into Negative Prompt
- Runway: Runway Gen-3 Alpha / Turbo · Image to Video · First + Last keyframe · 10 s · Camera control: Zoom In (subtle) · then retime in the editor
- Negative prompt:

```
text, letters, arabic script, subtitles, watermark, logo, signature, people, hands, faces, plastic CGI look, glossy 3D render, low detail, blur, flicker, jump cut, warped flag, extra stripes, distorted emblem
```

## Pipeline
1. Midjourney v6: generate the 10 keyframes below (Start + End per scene). Upscale (Subtle) and crop/resize to exactly 1080×1920.
2. Lock the look: keep --seed 7716 and add --sref of Scene 1 END to all later prompts.
3. Kling / Runway: one Start→End clip per scene using the MOTION prompt (5 clips).
4. Render 4 BRIDGE clips (End of scene N → Start of scene N+1, ~1.5 s) for the seamless Z-axis morphs.
5. Edit at 30 fps / 1080×1920: place clips at the timecodes below, overlap each bridge by 12 frames with a slight zoom-dissolve.
6. Typography in post (After Effects / Premiere / CapCut): IBM Plex Sans Arabic Bold for titles (white, shadow 0 4 20 rgba(0,0,0,.65)); Aref Ruqaa hollow outline 1.5 px for the outro, revealed with a stroke-draw over 3 s; bottom black gradient scrim 0→78%.
7. Audio: ambient D-Hijaz pad, desert wind, loom clacks (S1), falaj water (S3), soft oud plucks; or capture this page's synthesized audio.
8. Export H.264 MP4, 1080×1920, 30 fps, 12–16 Mbps, AAC 320 kbps.

---

## Scene 1 · The Loom & Foundation · البداية والنسيج
**00:00–00:06** · F0–F179 @30fps  
On-screen text: ثلاثة ألوان... تروي قصة مجد  (in 00:00.5, out 00:05.7) · macro dive + red cords lift from 00:04.4

### Midjourney v6 — START keyframe
```
Overhead macro photograph of coarse natural burlap hessian with a high-relief basket weave and visible stitch holes, warm beige jute (#D9C7B2, #C4AE94), a silver embroidery needle threaded with a chunky twisted crimson red (#DB161B) yarn cord beginning the first diagonal stitch, coils of thick twisted pure white and emerald green (#008000) cords waiting at the edge, soft warm side light, fuzzy wool fibres, shallow depth of field, tactile handcrafted textile art, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Midjourney v6 — END keyframe
```
Overhead macro photograph of the flag of the Sultanate of Oman hand-embroidered into coarse natural burlap with chunky twisted multi-ply yarn cords, set at a slight organic angle: a vertical crimson red (#DB161B) hoist band (one third of the length) stitched in thick diagonal herringbone satin stitches with the white khanjar and crossed-swords emblem embroidered in its upper part, and three equal horizontal bands of thick parallel twisted cords to the right: pure white on top, crimson red in the middle, emerald green (#008000) at the bottom, cords entering and exiting visible burlap stitch holes, fuzzy wool micro-fibres, deep soft shadows, warm natural light, only red, white and green yarn, no black, tactile handcrafted textile art, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Kling AI / Runway Gen-3 — image-to-video (Start → End)
```
Start frame: S1 START. End frame: S1 END. Stop-motion embroidery: chunky twisted yarn cords stitch themselves through the burlap holes one by one from top to bottom; red herringbone stitches fill the hoist band while white, red and green parallel cords fill the three bands, and the white khanjar emblem appears last. Slow continuous push-in (about 8%), cords tighten with small fibre wobbles, holes darken where the yarn enters the fabric. Macro lens, warm light, 24 fps, no cuts.
```
- Camera: Kling: Camera Movement → Zoom (+3) · Runway: Zoom In 2, Horizontal 0
- Render: Render 5 s → retime to 6.0 s (≈83% speed) · place at F0

### Bridge morph → Scene 2 (1.5 s)
```
Start frame: S1 END. End frame: S2 START. The camera dives to a low macro angle across the embroidery; the thick red cords unstitch and rise toward the lens like a wave while the white and green cords fall into soft bokeh behind them, and the background warms to golden-hour amber. 1.5–2 s, one continuous move, no cut.
```

---

## Scene 2 · Crimson Red — Heritage & Strength · الأحمر — الأصالة والعزم
**00:06–00:13** · F180–F389 @30fps  
On-screen text: Title الأحمر (in 00:06.9) · Subtitle أصالةٌ وعزمٌ لا يلين (in 00:07.6) · out 00:12.7

### Midjourney v6 — START keyframe
```
Extreme low-angle macro of thick twisted crimson red (#DB161B) wool yarn cords rising from coarse burlap like a wave toward the camera, shallow depth of field with white and emerald green yarn cords softly blurred in bokeh behind, the red cords flowing into rolling sand-dune ridges of the Wahiba Sands knitted from crimson and desert-sand yarn, warm golden-hour light, glowing fibres, handcrafted textile art, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Midjourney v6 — END keyframe
```
The monumental round cylindrical tower of Nizwa Fort, Oman, crafted entirely from tightly wrapped rows of sand-colored and crimson wool yarn, crenellated parapet ring, small arched window slits, an adjoining crenellated wall, standing behind layered knitted crimson and sand yarn dunes of Wahiba Sands, warm golden-hour sunlight from the left, long soft shadows, glowing fuzzy fibers, handcrafted 3D woven sculpture, centered composition with calm empty dunes in the lower third, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Kling AI / Runway Gen-3 — image-to-video (Start → End)
```
Start frame: S2 START. End frame: S2 END. Continuous slow push-in with a gentle upward crane. Red yarn threads rise from the bottom of frame and coil into dune ridges that swell like breathing fabric, layer after layer from back to front; the round Nizwa Fort tower knits itself upward row by row from its base with a glowing stitching line travelling up the tower; sand-colored fibers drift in a light desert wind; warm golden light flickers through loose fibers. Textile stop-motion feel, smooth, cinematic, 24 fps.
```
- Camera: Kling: Zoom (+2) + Tilt (+2) · Runway: Zoom In 2, Tilt Up 1
- Render: Render 10 s → trim/retime to 7.0 s · place at F180

### Bridge morph → Scene 3 (1.5 s)
```
Start frame: S2 END. End frame: S3 START. The camera flies toward the fort; its sand and crimson yarn rows unravel into long strands that re-color from crimson to emerald and olive green as they fall into stepped terraces; golden light cools to a soft morning green-gold. Continuous Z-axis push-through, 1.5 s.
```

---

## Scene 3 · Emerald Green — Growth & Nature · الأخضر — النماء والطبيعة
**00:13–00:20** · F390–F599 @30fps  
On-screen text: Title الأخضر (in 00:13.9) · Subtitle نماءٌ يكسو أرض عُمان (in 00:14.6) · out 00:19.7

### Midjourney v6 — START keyframe
```
Sand and crimson yarn unravelling in mid-air and re-knitting into emerald green (#008000) and olive (#2E5A36) silk threads that form stepped mountain terraces, the transition moment between a woven desert fort and the green mountains of Oman, floating threads, soft morning light, handcrafted textile art, macro, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Midjourney v6 — END keyframe
```
Lush terraced mountains of Jabal Akhdar, Oman, every terrace stitched from layered emerald green and olive silk threads, date palm trees with fronds of fine layered green silk fibers and woven wool trunks framing both sides, a traditional Omani falaj irrigation channel of shimmering turquoise (#4A8B9C) silk water running straight toward the camera through the center of the frame, sand-colored yarn channel walls, soft morning mist, gentle sunlight, handcrafted textile diorama, deep one-point perspective, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Kling AI / Runway Gen-3 — image-to-video (Start → End)
```
Start frame: S3 START. End frame: S3 END. Continuous low glide forward along the falaj, camera pushing in slowly just above the water. Turquoise silk water threads ripple and flow toward the lens with glints of white light; terraces settle into place layer by layer; palm fronds sway softly in the breeze; thin mist drifts across the mountains. Smooth, calm, organic, cinematic, 24 fps.
```
- Camera: Kling: Zoom (+3) · Runway: Zoom In 3 (forward glide)
- Render: Render 10 s → retime to 7.0 s · place at F390

### Bridge morph → Scene 4 (1.5 s)
```
Start frame: S3 END. End frame: S4 START. The turquoise falaj water lifts off the channel and rises vertically in silk ribbons, fading from turquoise to white as it climbs and curls into frankincense smoke; the greenery dissolves into soft pearl dawn light. 1.5 s continuous upward rise.
```

---

## Scene 4 · Pure White — Peace & Frankincense · الأبيض — السلام واللبان
**00:20–00:27** · F600–F809 @30fps  
On-screen text: Title الأبيض (in 00:20.9) · Subtitle سلامٌ يعمّ الأرجاء (in 00:21.6) · out 00:26.7

### Midjourney v6 — START keyframe
```
Turquoise (#4A8B9C) silk water threads rising vertically into the air and turning into swirling white Omani frankincense smoke, delicate curling white silk strands, a traditional painted Omani clay incense burner (mabkhara) glowing on a whitewashed rooftop, white Omani houses below, soft pearl dawn light, ethereal, handcrafted textile art, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Midjourney v6 — END keyframe
```
A majestic pure white dove with wings spread wide, crafted from delicate white silk threads and soft white feathers, gliding above traditional whitewashed Omani architecture with stepped crenellated parapets, arched wooden windows, a round watchtower and a slender minaret, wisps of frankincense smoke curling around, soft pearl dawn light with gentle sun rays, serene, handcrafted textile art, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Kling AI / Runway Gen-3 — image-to-video (Start → End)
```
Start frame: S4 START. End frame: S4 END. Slow push-in. White frankincense smoke curls upward from the incense burner in silky spirals; the smoke strands gather and coalesce into a white dove, threads tightening into feathers; the dove beats its wings once and glides gently left to right above the white rooftops; soft rays of light. Ethereal, graceful, no sudden motion, 24 fps.
```
- Camera: Kling: Zoom (+2) · Runway: Zoom In 1, Pan Right 1
- Render: Render 10 s → retime to 7.0 s · place at F600

### Bridge morph → Scene 5 (1.5 s)
```
Start frame: S4 END. End frame: S5 START. The dove banks and glides directly toward the camera until it fills the frame; the sky warms from pearl to rich gold. 1.5 s, one continuous move.
```

---

## Scene 5 · The Flag of Oman — Outro · الختام — راية الوطن
**00:27–00:35** · F810–F1049 @30fps  
On-screen text: Hollow calligraphic سلطنة عُمان (stroke reveal 00:29.4–00:32.4, F882–F972) · Subtitle عِزٌّ وَفَخْر wide spacing (in 00:32.0, F960) · hold to end

### Midjourney v6 — START keyframe
```
A white silk dove flying directly toward the camera with wings spread, its wing feathers unravelling into long flowing ribbons of crimson red, pure white and emerald green silk streaming outward, warm golden sky, sunlit translucent fibers, handcrafted textile art, dynamic, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 250 --seed 7716
```

### Midjourney v6 — END keyframe
```
The national flag of the Sultanate of Oman made of woven silk fabric waving majestically from a golden pole: a vertical crimson red band along the hoist with the white national emblem (a khanjar dagger in its curved sheath over two crossed swords) finely embroidered in the upper hoist, and three equal horizontal bands to the fly: white on top, red in the middle, green at the bottom, the vertical red hoist band spanning one third of the flag length, flag proportions 7:4, warm golden sunset sky, backlit silk sheen, flag in the upper half of the frame with clear golden sky below for a title, cinematic, ultra-detailed, no text --ar 9:16 --v 6.0 --style raw --s 200 --seed 7716
```

### Kling AI / Runway Gen-3 — image-to-video (Start → End)
```
Start frame: S5 START. End frame: S5 END. The dove flies into the lens; its wings unravel into red, white and green silk ribbons that sweep across the frame and weave together into the flag of Oman; the flag then ripples majestically in slow motion (0.5x) from the pole, golden backlight glinting through the silk weave, floating golden dust. Hold the waving flag for the final 3 seconds. Keep the flag geometry stable: vertical red hoist band with white emblem, white top band, red middle band, green bottom band. 24 fps.
```
- Camera: Kling: Static after 2 s (slight Zoom +1) · Runway: Zoom In 1 then static
- Render: Render 10 s → retime to 8.0 s · place at F810

> **Note:** AI video models often distort flag stripes and the emblem. For an accurate flag, screen-record the last 5 s of this web experience (it renders the official flag artwork, vectorised from the reference image: 1600×914, hoist band = 1/3 of the length) and use a frame of it as the END keyframe, or composite official flag artwork over the AI plate.
