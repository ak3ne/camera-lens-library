---
name: camera-lens-library
description: Grab-and-paste library of real cameras, lenses, rigs, lighting setups and LUT/grade looks for AI image/video generation prompts — cinema, commercial, broadcast, vlog, stills, drone, phone, surveillance. Use whenever writing generation prompts that need photographic realism (keyframes, i2v, t2v): declare a real capture device, a real light, a real grade instead of abstract "cinematic" language. Triggers: "camera settings for this shot", "what lens for", "make it look shot on real camera", "rig block", "lens recipe", "lighting block", "LUT", "grade look", keyframe prompt writing, cyane generation work.
---

# Camera / Lens / Lighting / LUT Library — device-truth blocks for generation prompts

**Law (2026-07-05 haidilao camera-grammar crisis): realism is decided at GENERATION time and cannot be added in post; tone/filter CAN. Every prompt buys realism first — declare a real camera, a real lens at a real stop, a real support, ONE motivated light, and name the grade — then let post own the final tone.** Companion doctrine: `~/Projects/cyane/docs/cyane-camera.md` (device-truth + operator + speed law). Naming real brands (ARRI, Canon, Sony, Nikon, iPhone) is not decoration — it retrieves that device's actual artifact signature from the model.

**Reference override (Akane's law, 2026-07-05 round 4): when a visual reference EXISTS, don't rebuild its look from words — anchor on the image itself (i2i) and use these blocks to describe only what must CHANGE. Full protocol: `cyane-references.md` §"Reference-anchored generation".**

## How to use
Pick ONE recipe (or compose body+lens+support+light+grade from the tables), paste into the prompt's Style/Camera lines, keep the rest of the prompt about subject + action. One rig per shot. Never stack two cameras. Never write "8K ultra cinematic masterpiece" — a sensor, a focal length, a T-stop, and a named light do the work. Angle + framing psychology belong IN the block (see the recipes: where the camera is, why it's there, what it can't see).

## 1 — CAMERAS by duty

### Cinema A-camera (features / premium TVC)
| Body | Format | Signature in the image |
|---|---|---|
| ARRI Alexa 35 / 35 XR | S35 4.6K, ~17 stops | THE commercial+narrative default; gentle highlight rolloff, filmic color, zero digital edge |
| ARRI Alexa Mini LF | LF 4.5K | large-format shallow planes, premium spot look |
| ARRI Alexa 65 | 65mm 6.5K | epic scale, creamy compression at wide FoV (Dune/Revenant energy) |
| Sony Venice 2 | FF 8.6K, dual-ISO 800/3200 | clean color science, unbeatable low light, night ext king |
| RED V-Raptor [X] | VV 8K | crisp digital texture, high-frame offspeed, action/tabletop |
| RED Komodo-X | S35 6K | crash-cam small, global-shutter-ish stunts, car rigs |
| Blackmagic URSA Cine 12K/17K | LF–65 | budget large-format resolution monster, indie epic |

### Commercial / tabletop / high-speed
| Rig | Spec | Use |
|---|---|---|
| Phantom VEO 4K / Flex4K | 1000fps 4K | food/liquid physics; slow-mo as DEVICE truth |
| Phantom TMX 7510 | up to 76,000fps | extreme micro-moments (droplet crowns, shatter) |
| Bolt X / Cinebot robotic arm | repeatable high-speed path | choreographed orbital/whip passes synced to food events |
| Motion-control slider + macro | programmed cm-moves | product passes, repeatable A/B |

### Broadcast / documentary / ENG
| Body | Character |
|---|---|
| ARRI Amira (shoulder) | doc weight sway, practical zooms, news-mag texture |
| Sony FX9 / FX6 | run-and-gun doc, clean AF, variable ND look |
| Canon C300 III / C500 II | NGO/branded-doc staple, Canon skin color |
| ENG box-lens studio cam (86x zoom) | sports/stadium compression, deep focus, hard sun |

### Hybrid / vlog / creator
| Body | Character |
|---|---|
| Sony FX3 / A7S III | 4K120 FF low-light; the indie-creator cinema look |
| Sony ZV-E1 | FF vlog AI-framing; gimbal-smooth solo creator |
| Canon R5 C | 8K RAW hybrid; editorial-crisp stills-video |
| Fujifilm X-H2S / X-M5 | Fuji film-sim color straight out of camera; open-gate 6K |
| Panasonic S5 IIX / GH7 | V-Log doc-indie; GH = MFT deep focus gimbal cam |
| Sony ZV-E10 II | budget APS-C creator truth (kit-lens sharpness, AWB drift) |
| DJI Osmo Pocket 3 / 4 | 1" gimbal cam; floaty-smooth walk-and-talk, 4K240 on the 4 |

### Action / POV
GoPro Hero 13 (ultra-wide barrel distortion, hypersmooth, chest/helmet POV) · Insta360 X4 / Ace Pro (360 reframe, invisible-selfie-stick third-person) · DJI Osmo Action 5 (vertical-native social).

### Phone (UGC truth)
iPhone 17 Pro (ProRes Log, 5x tele, LiDAR AF; the "shot on iPhone" clean look) · iPhone 13/14 as older-UGC truth (clipped windows, AWB shifts) · Samsung S25 Ultra (8K, punchy HDR color) · Xiaomi 15 Ultra (1" Leica look). Artifacts to declare: AF breathing, rolling-shutter on pans, auto white balance shifting between rooms, mild compression, imperfect framing.

### Stills / photo bodies
| Body | Signature |
|---|---|
| Canon R5 II / 5D IV + L glass | the wedding/editorial standard; warm skin, creamy 50L/85L bokeh |
| Nikon Z9 / Z8 | sports/wildlife stills, ruthless AF, neutral color |
| Sony A1 II | commercial catalog crispness |
| Fujifilm GFX100 II (medium format 102MP) | luxury editorial: huge tonal depth, slice-thin planes |
| Hasselblad X2D | product/beauty MF; HNCS color, sculpted falloff |
| Leica M11 / Q3 | reportage classic; Summilux drawing, quiet vignette |
| Phase One XF IQ4 150MP | archival/advertising ultra-detail |

### Drone / aerial
| Platform | Spec | Use |
|---|---|---|
| DJI Mavic 4 Pro | 100MP Hasselblad 4/3", 6K60 HDR, D-Log, 360° gimbal | premium establishing orbits/reveals |
| DJI Inspire 3 | FF 8K75 ProRes RAW, dual-op | cine aerials, top-down cathedral moves |
| DJI Mini 4 Pro | consumer light | travel-vlog aerial truth |
| FPV / cinewhoop (Avata 2) | one continuous dive | chase energy, fly-through-window one-ers |

### Specialty device-truth kits (each is its own realism genre)
CCTV/security cam (high-angle corner mount, wide, low-fps, timestamp, IR-washed night) · dashcam (windshield wide, exposure pumping, plate-level detail) · bodycam (chest POV fisheye, motion shake, auto-gain audio implication) · webcam/laptop (eye-level-low, backlit window blowout, compression) · VHS/MiniDV camcorder (interlace smear, date stamp, tape noise) · 16mm film ARRI 416/Bolex (grain, gate weave, halation) · 35mm film Panavision Millennium XL (anamorphic-era Hollywood) · IMAX/65mm (Panavision System 65) for maximal-scale set pieces.

## 2 — LENSES

### Cine primes
| Set | Stop | Drawing |
|---|---|---|
| ARRI Signature Primes | T1.8 | modern clean, soft skin rendering — commercial default |
| Zeiss Master Primes | T1.3 | clinical sharpness, high micro-contrast |
| Zeiss Supreme Primes | T1.5 | LF neutral-clean |
| Cooke S8/i (S4 legacy) | T1.4/T2 | "the Cooke look": warm, round, gentle falloff |
| Panavision Primo | T1.9 | Hollywood 90s-00s gloss |
| Canon K35 (vintage) | T1.3 | 70s bloom, warm flares (Aliens-era) |
| Cooke Speed Panchro (vintage) | T2.2 | classic-film softness on modern sensors |

### Anamorphic
Panavision C/E/G-series (the Hollywood squeeze: oval bokeh, horizontal blue streak) · Atlas Orion 2x (indie anamorphic staple) · Cooke Anamorphic/i FF · Hawk V-Lite · Kowa vintage (dreamy, low-contrast). Declare: "2x anamorphic squeeze, oval bokeh, subtle horizontal flare, 2.39:1".

### Zooms
Angénieux Optimo 24-290 T2.8 (THE commercial zoom; compression choices mid-move) · Fujinon Premista 28-100 T2.9 (LF zoom) · Canon CN20x50 box (broadcast super-tele).

### Macro / probe / special
Laowa 24mm Probe & Periprobe 15-24 T8-T14 (snorkel POV *through* food/objects, deep-focus macro) · 100mm macro T2.8-T5.6 class (tabletop food standard, 1:1) · Canon TS-E 90 tilt-shift (miniature plane tricks, product plane control) · Lensbaby (selective-focus dream) · Petzval 85 (swirl bokeh portrait) · Helios 44-2 58mm (Soviet swirl, flare-happy vintage character).

### Telephoto / wildlife / surveillance
400mm f/2.8 and 600mm f/4 super-teles (Canon RF/EF, Sony GM, Nikon Z) · 150-600mm zooms (Sigma/Tamron; the budget-paparazzi truth) · 2x teleconverter stacking (softer, shimmer). Signature physics: brutal perspective compression (background towers over subject), slice-thin DoF, heat-haze shimmer on long air paths, any occluder near the lens melts to a colored wash.

### Stills classics (for photo-real keyframes)
50mm f/1.2L (editorial hero) · 85mm f/1.4 (portrait compression) · 35mm f/1.4 Summilux (reportage wide) · 24-70 f/2.8 (event workhorse) · 110mm f/2 on GFX (luxury MF portrait).

## 3 — RECIPES (paste-ready; angle + framing psychology included)

- **Food macro, locked action (slice/drop/pour):** `Shot on a Phantom VEO 4K with a 100mm macro lens at T4, ISO 640, 180-degree shutter, locked on a heavy tripod at tabletop height, focus tack-sharp on the subject, background falls off to soft darkness`
- **Food orbit / pass-through:** `Bolt high-speed robotic arm carrying a RED Komodo-X with a Laowa 24mm probe lens at T8, one fast choreographed orbital pass synchronized to the food action`
- **High-speed splash/pour slow-mo (device truth):** `Phantom Flex4K at 1000fps played back at 24fps, hard specular key light, every droplet resolved` — slow motion is legitimate ONLY when the rig says so.
- **Product hero on set:** `ARRI Alexa 35, 47mm Signature Prime at T2.8, ISO 800, slow 30cm dolly-in completing in 1.5 seconds then locking`
- **Field/location establishing:** `ARRI Alexa 35 on a jib, 32mm Signature Prime at T4, ISO 800, 180-degree shutter, one confident descent with foreground elements wiping past the lens edge, easing into a locked final composition`
- **Epic aerial establish:** `DJI Inspire 3, full-frame 8K, one slow 40-meter orbit at constant radius around the landmark, horizon level, no drift` — or Mavic 4 Pro D-Log for travel-doc flavor.
- **FPV chase:** `FPV cinewhoop, one continuous dive from the rooftop through the alley gap, speed builds, near-miss proximity, no cuts`
- **Portrait/emotion closeup:** `Alexa Mini LF, 85mm Signature Prime at T1.8, subject eyes tack-sharp, background melts, motivated window key light`
- **Luxury editorial still:** `RAW photo on a Fujifilm GFX100 II, 110mm f/2, medium-format tonal depth, subject lit by one large softbox camera-left, seamless grey background`
- **Handheld follow / doc energy:** `Amira shoulder rig, 25mm at T2.8, operator walks with the subject, frame breathes and settles with each step`
- **Broadcast sports/stadium:** `ENG box lens at 400mm equivalent from the high gantry, deep stopped-down focus, hard noon sun, heat shimmer over the field`
- **UGC/vlog truth:** `filmed on an iPhone held by a friend, autofocus breathing, slight rolling shutter on quick pans, auto white balance shifting between rooms, mild compression, imperfect framing`
- **Gimbal walk-and-talk:** `DJI Osmo Pocket 3, 1-inch sensor, gimbal-floating walk beside the subject at conversation distance, occasional micro-corrections`
- **Paparazzi / long-lens surveillance (the hidden shooter):** `Long-lens telephoto (400-600mm) from across the street, heavy perspective compression, shallow depth of field. Foreground partially obstructed by out-of-focus shapes — leaves, a fence, a crew member's shoulder, glass — suggesting the photographer is hiding. Subject angled 3/4 away or in profile, fully committed to something off-frame; they do NOT look at, acknowledge, or face this camera. Imperfect framing, subject off-center and partially clipped, one frame of a motor-drive burst` — add `on-camera flash hard frontal, red-eye risk, night street` for the flash-pap variant.
- **Security/CCTV:** `high corner-mounted security camera, wide fixed lens, slight fisheye, washed IR-adjacent color, low frame rate feel, timestamp overlay region left clean`
- **Dashcam:** `windshield dashcam wide, exposure pumping between shade and sun, compression artifacts in shadows, hood edge at frame bottom`
- **Bodycam:** `chest-mounted bodycam fisheye, walk shake, auto-gain shifts, close subjects loom wide`
- **Webcam/laptop:** `built-in laptop webcam at screen height, slightly low angle, window blowout behind, soft compression, fluorescent-ish AWB`
- **Music-video anamorphic:** `Alexa 35 with Atlas Orion 2x anamorphics at T2, oval bokeh, horizontal flares kissed by practicals, 2.39:1, one whip-pan per section`
- **Night doc / neon street:** `Sony Venice 2 at dual-native ISO 3200, 35mm Supreme Prime at T1.5, sodium-vapor and neon mixed sources carry the frame, no added light`
- **Period 16mm:** `ARRI 416 on Kodak Vision3 500T 16mm, visible grain, gate weave, halation on practicals, slightly lifted blacks`
- **Wedding/event stills:** `Canon R5 II with 50mm f/1.2L wide open, warm window light, candid mid-laugh moment, editorial crop`

## 4 — LIGHTING library (ONE motivated source statement per prompt)

**Natural:** `luminous golden hour, low warm sun with soft bloom, sky holding vivid blue` · `magic hour afterglow, no direct sun, cyan-rose gradient sky` · `hard noon sun, short black shadows, squint-bright` · `overcast sky as one giant softbox, shadowless even light` · `north-window soft directional daylight` · `dappled light through leaf canopy, moving spots` · `storm light: dark sky behind a sunlit subject` · `blue-hour ambient with tungsten windows glowing`.

**Studio/set:** `single large softbox key camera-left, gentle falloff, seamless background` · `book light (bounced then diffused), wrap-around beauty softness` · `hard fresnel key with cutter shadows, film-noir slats` · `ARRI SkyPanel wash + practical lamps carrying warmth` · `Aputure 1200d punched through 8x8 diffusion as faux sun` · `ring light frontal beauty flat, catchlight circle` · `top-down food softbox with white bounce cards, glossy speculars on sauce`.

**Practical/ambient:** `tungsten household practicals, warm pools in shadow` · `fluorescent office green-tinge flicker` · `sodium-vapor street amber monochrome` · `neon sign color wash (pink/cyan) as key` · `candlelight/firelight low warm flicker, deep shadows` · `car headlights raking through night fog` · `projector/screen glow on faces in a dark room` · `stadium floodlights, multi-shadow crosshatch` · `police/ambulance red-blue strobe wash` · `moonlight blue at quarter level, silver rims`.

**On-camera:** `direct hard flash, flat frontal, hard falloff to black background (paparazzi/Y2K snapshot)` · `phone-torch harsh close light, horror-adjacent`.

### Fixture spec table (name the instrument when the set is part of the story)
| Fixture | Type | Signature |
|---|---|---|
| ARRI SkyPanel S60-C | RGBW LED panel | broad soft color-tunable wash; the studio standard |
| ARRI M18 / M40 | HMI daylight fresnel | hard punchy faux-sun; through 8x8 diffusion = window sun |
| Aputure 600d / 1200d Pro | LED daylight point | budget sun punch; + Spotlight Max = crisp gobo slashes |
| Astera Titan tubes | RGB LED tubes | practical neon lines, car-interior rigs, color accents |
| Kino Flo Diva / 4Bank | soft fluorescent-style | interview key, even greenscreen wash |
| Dedolight DLED | focusable prime spot | precise eye-lights and slashes |
| Nanlite Forza | compact LED point | run-and-gun key through a dome |
| Tungsten 2K/5K fresnel | classic warm hard | period/studio-era look, real dimmer warmth |
| China ball / paper lantern | omni soft warm | overhead table scenes, walk-and-talk float |
| Ring light | on-axis LED | beauty-flat catchlight circle (also the "influencer" tell) |
| 4x4 floppy / ultrabounce / neg fill | modifiers | shape and subtract — declare `soft bounce fill from camera right, negative fill left` |

## 5 — LUT / GRADE library (name the finish; post can still re-grade)

**Print/film emulation:** `Kodak 2383 print-film emulation, theatrical contrast, teal-leaning shadows, warm skin` · `Fuji Eterna soft low-saturation cine` · `Kodak Vision3 500T scanned-negative look, halation on highlights` · `CineStill 800T: tungsten night, red halation around lights` · `Kodachrome 64: dense vivid vintage chrome` · `Portra 400: warm gentle skin negative` · `Ektachrome slide: clean cool chrome` · `bleach bypass: desaturated, crushed, silver-retention war-film` · `cross-processed: shifted greens, blown yellows`.

**Digital/broadcast:** `ARRI 709 (K1S1/Reveal): neutral broadcast filmic` · `ACES neutral: honest color, no stylization` · `teal-and-orange blockbuster grade, complementary skin-vs-shadow split` · `Netflix-doc clean: neutral, slightly lifted, HDR-ish headroom` · `music-video high-chroma with gelled color blocking` · `day-for-night: underexposed blue, suppressed sky`.

**Commercial food (OUR house, from the haidilao benchmark):** `vivid commercial food-film grade: saturated hero red, lifted shadows, glossy specular highlights, high color contrast, luminous` — bright DIGITAL commercial ≠ film grime; NO grain/gate-weave stack on bright product work (Akane's law, round 2).

**Era/degradation:** `90s VHS: interlace smear, chroma bleed, tape noise, 4:3` · `2000s MiniDV camcorder: sharp-harsh video, date stamp` · `2010s Instagram filter era: faded blacks, warm cast, vignette` · `8mm home movie: gate weave, dust, warm fade`.

## 6 — Reference-anchored i2i + reverse-prompting (the overrides)
1. **A reference image/frame exists → anchor on it** (nano banana pro / gpt-image-2 with `--image`): instruction = "match the reference's camera character, lens compression, filter, color grade, tone and atmosphere", then describe only the NEW content. Text-from-scratch (t2i) is for when no reference exists. Proof: haidilao round 4 — i2i on the client's own field frame beat every t2i attempt on the first roll.
2. **Reverse-prompt the reference before writing any prompt**: read the frame/clip and extract its device block (body/lens/stop guess), light statement, grade name, atmosphere terms — using THIS library as the vocabulary — then reuse those exact terms in generation. Full protocol: `cyane-references.md` §"Reverse-prompt extraction".

## 7 — Speed vocabulary (pairs with any recipe)
`completes in N seconds` · `whips in a third of a second, settles instantly` · `one decisive stroke` · `eases into a locked composition` (NOTE: video models often ignore in-prompt easing — plan the ease as a post time-remap; seedance confirmed 2/2 constant-velocity) · `holds locked, zero drift, subject motion only`.

## 8 — Cinema prompt architecture (distilled from the Higgsfield Soul cinema community, 2026-07-06)
*Source: 68-prompt corpus scraped from higgsfield.ai/soul-cinema-community (archived: `~/Altixena/studio-cyane/_references/_studies/soul-cinema-community/corpus-68-prompts.txt`). 67/68 share ONE standardized JSON template — community-proven replicable structure for hero-grade cinematic stills. Their taste cluster is A24/neo-noir; **import the ARCHITECTURE, never their mood — fill every field from YOUR project's anchors.***

**The template (JSON-labeled blocks; image models parse the hierarchy):**
```json
{"Caption": "<4-6 sentences of FILM PROSE: time of day first, subjects, movement,
  light behavior, camera behavior, the closing beat — a mini-treatment, not tags>",
 "STYLE": {"Artistic Medium": "…", "Aesthetic Movement / Genre": "<with real anchors: 'A24 / …'>",
           "Cultural / Historical Influence": "…"},
 "COMPOSITION": {"Framing": "…", "Layout": "<GEOMETRY: triangular arrangement, receding line,
                 leading lines, negative space>", "Perspective": "<angle + WHY: 'low to elongate legs'>"},
 "SCENE": {"Subject Characteristics": "<age/build/wardrobe/posture — castable specificity>",
           "Setting": "…", "Geographic / Cultural Context": "…"},
 "CINEMATOGRAPHY_AND_LIGHTING": {"Lighting Style": "<key/fill/rim logic with color>",
           "Color Palette": "…", "Overall Color Tone": "…", "Tone & Mood": "…"},
 "CAMERA_AND_LENS": {"Camera Type and Era": "…", "Camera model": "…", "Lens model": "…",
           "Lens size": "…", "Lens Effects": "<flares, breathing, edge softness>",
           "Depth of Field": "…", "Film Grain / Noise": "<density spec: '25-35mm film density'>"},
 "PHYSICAL_ATTRIBUTES": {"Material & Texture": "<per surface>",
           "Physics & Effects": "<volumetrics, cloth/liquid behavior>",
           "Execution Style": "<the in-prompt negative: 'photoreal practical, no CG'>"},
 "HEX VALUES": ["<8-15 exact swatches — the LUT as data>"]}
```

**What this adds over our block prompts:** Caption-as-treatment opener (prose scene BEFORE spec) · WHY-clauses on composition choices · camera ERA as its own signal · lens EFFECTS as a first-class field · grain DENSITY numbers · per-surface material blocks · **the hex palette declaration**.

**PALETTE-AS-DATA law:** extract the dominant swatches FROM the project's reference anchors (`PIL Image.quantize(colors=12)` → hex) and declare them in HEX VALUES — palette compliance moves from post-grade hope to GENERATION-time instruction, and feeds the keyframe gate's reference-fidelity axis directly.

**Scope:** proven on cinematic STILLS (Soul community; transfers to nano banana pro / gpt-image). For VIDEO, flatten the blocks into the bible prompt (`cyane-camera.md` template) — motion models want prose blocks, not JSON.

**Worked example (haidilao ① slice, client-anchor palette):**
```json
{"Caption": "Bright studio daylight. A hand grips a slim paring knife held perfectly vertical, its tip resting on the crown of one large glossy tomato; behind it a wall of ripe red fruit fills every corner of the frame, softly defocused. The blade waits one beat, then drives through in a single continuous stroke as fine watery spray catches the key light.",
 "STYLE": {"Artistic Medium": "Live-action commercial food film still", "Aesthetic Movement / Genre": "High-key Chinese food TVC (Haidilao house style)", "Cultural / Historical Influence": "Contemporary CN appetite commercial"},
 "COMPOSITION": {"Framing": "Macro close-up, hero centered", "Layout": "Hero fruit on the vertical cut axis; red wall as depth field", "Perspective": "Tabletop level to keep the blade plane readable"},
 "SCENE": {"Subject Characteristics": "One large ripe de-stemmed tomato, taut glossy skin, water droplets", "Setting": "Edge-to-edge ripe tomato wall, no visible set hardware", "Geographic / Cultural Context": "Chinese hotpot brand world"},
 "CINEMATOGRAPHY_AND_LIGHTING": {"Lighting Style": "High-key top softbox with white bounce fill, glossy speculars on skin", "Color Palette": "Saturated hero reds on warm highlight skin-tones", "Overall Color Tone": "Luminous poster red, zero dark voids", "Tone & Mood": "Appetizing, confident, bright"},
 "CAMERA_AND_LENS": {"Camera Type and Era": "Contemporary digital cinema, filmic intent", "Camera model": "Phantom VEO 4K food rig", "Lens model": "100mm macro", "Lens size": "100mm at f4", "Lens Effects": "Clean modern coating, no flare", "Depth of Field": "Hero tack-sharp, wall melts", "Film Grain / Noise": "Fine broadcast grain"},
 "PHYSICAL_ATTRIBUTES": {"Material & Texture": "Taut tomato skin with micro-droplets; brushed steel blade; matte hand skin", "Physics & Effects": "Watery juice spray as droplets under real gravity, never strings", "Execution Style": "Photoreal practical, no CG, no HDR glow, no 3D render look"},
 "HEX VALUES": ["#8b0001", "#ab0c09", "#d62817", "#ec4229", "#f36047", "#c65641", "#d57c67", "#db8975", "#e8a694", "#6b0000"]}
```
