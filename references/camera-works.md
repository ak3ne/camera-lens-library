# Camera works / distance / angle — the separated axes

Born 2026-08-04 for the on_one one-click feature and the cyane prompt stack. The problem this file kills: community prompts fuse style, camera and grade into one blob, so you can't swap one without rewriting everything. Here the camera language lives ALONE, as composable atoms. Style comes from the `style-library` skill, device/light/grade blocks from the main SKILL.md, grammar from `prompt-master`, surface syntax from `seedance-20`.

**LAW: one prompt = one style block + one camera-works chain + one grade name. A style block never smuggles a camera move; a camera atom never smuggles a mood word.**

Sources: 158-prompt Seedance 2.0 community corpus (YouMind `awesome-seedance-2-prompts` + youmind.com category pages, harvested 2026-08-04), frequency pass over the 15,089-prompt nano-banana photo DB, dexhunter Jimeng tables, and the seedance-20 shot contract. Numbers in [brackets] are corpus occurrence counts: what the community actually ships and what demonstrably renders.

## 0 — The shot contract (shared grammar with seedance-20)

Every serious shot declares: size / angle / lens feel / support / movement / subject relation / start frame / end frame / fragile anchors.

Pattern: `Shot: [size, angle, lens feel]. Camera starts [readable composition], [ONE movement] at [speed] while [subject action], ending on [clear endpoint]. Preserve [face, logo, wardrobe, prop anchors].`

## 1 — MOVEMENTS (video camera works)

### 1a. Locked and micro
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Locked-off static | `one continuous static shot, locked camera, no cuts, zero drift, subject motion only` | lip-sync, product identity, text, VFX anchors | dead air if the subject also holds still |
| Fixed frame (surveillance) | `fixed camera locked between [A] and [B], subjects move through frame` | tension, deadpan comedy, CCTV truth | pair with a device kit from SKILL.md §1 |
| Micro drift | `nearly static with barely perceptible handheld drift` | documentary honesty on an interview | do not add a second move |

### 1b. Advance and retreat
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Push-in [15] | `slow push-in from a medium shot to a close-up of [subject]` | discovery, intimacy, realization | declare start AND end distance |
| Extreme slow push | `extremely slow push-in, completing only at the final second` | dread, romance tension | pair with a hold at the end |
| Rapid push | `camera snaps forward into a dead-on close-up` | impact beat, comedy punch | one per clip |
| Pull-back | `camera slowly pulls back, revealing [context]` | scale reveal, loneliness, punchline context | the reveal must contain new information |
| Dolly-in / out [10] | `smooth camera dolly tracking shot toward [subject]` | premium commercial glide | needs gimbal/dolly smoothness words |

### 1c. Rotate in place
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Pan [22] | `camera pans left to right across [scene]` | space survey, follow a look | slow unless whip |
| Whip pan [5] | `whip pan between angles, motion blur masking the cut` | energy transitions, chase chaos | corpus uses it as a TRANSITION device |
| Tilt [22] | `camera tilts up from [detail] to [face/sky]` | reveal along the vertical | slow tilt = reverence, fast = shock |
| Pedestal rise | `camera ascends vertically while holding frame on [subject]` | drone-adjacent lift without flight | declare the endpoint height |
| Camera roll | `camera smoothly rotates 90 degrees counter-clockwise to reveal [gag]` | disorientation, illusion comedy, dream logic | corpus-proven on Seedance for visual-illusion gags |

### 1d. Travel
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Lateral track [45] | `exterior side tracking shot, camera travels parallel to [subject]` | speed, procession, choreography | keep foreground layers wiping past |
| Follow [53] | `camera follows [subject] from behind at walking pace` | journey, immersion | the most-shipped travel atom in the corpus |
| Lead | `camera leads the subject, facing them as they advance` | performance to lens, MV energy | reserve eye-contact for this |
| Low ground track | `low-angle tracking shot skimming the ground` | menace, wheels, boots, paws | pairs with speed vocabulary |
| Through-water follow | `camera follows the subject, submerging smoothly under the surface` | one-take spectacle beat | corpus-proven seamless environment hop |

### 1e. Orbit family
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Arc [5] | `camera arcs 45 degrees around [subject] while they hold` | dimensionality without dizziness | the subtle orbit |
| Orbit [27] | `camera slowly orbits [subject] clockwise` | product hero, statuesque subjects | identity can drift on faces; anchor wardrobe |
| Slow 360 [7] | `the camera slowly orbits 360 degrees around her clockwise` | showpiece, transformation reveals | budget the full rotation into the duration |
| Orbit + ascend | `camera orbits while ascending vertically, revealing the [skyline]` | finale scale beat | endpoint = wide reveal |

### 1f. Lens motion
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Zoom-in | `ultra-telephoto lens zoom-in on [subject]` | surveillance feel, compression jump | zoom is not a dolly; feels optical |
| Snap zoom | `sudden snap zoom onto [detail]` | comedy, mockumentary, action punch | UGC and action only |
| Dolly zoom | `Hitchcock dolly zoom, background stretching away while the subject holds size` | vertigo, dread epiphany | one per film, honestly |

### 1g. Operator textures (support as movement)
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Handheld subtle [62] | `subtle handheld camera movement, organic camera breathing` | realism, warmth | the corpus default for authenticity |
| Handheld shake | `slight handheld shake, natural micro-jitter` | UGC/vlog truth | pair with phone/camcorder device kit |
| Handheld intense | `intense handheld chase camera, frame whipping to keep up` | panic, pursuit | let the frame lose the subject for beats |
| Gimbal float [8] | `smooth gimbal stabilization, floating walk beside [subject]` | modern premium glide | kills UGC truth; choose one world |
| Selfie cam | `handheld selfie shot, arm-length framing, lens looks back at the face` | vlog POV intro | switch to normal coverage after the hook |
| Zero-G float | `one continuous handheld-style zero-gravity camera move, floating with the subject, believable inertia` | space, underwater, dreams | corpus-proven on Seedance astronaut work |

### 1h. Air
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Crane up / jib down | `crane rises from eye level to high wide` | arrival, departure, finale | slow and confident |
| Drone lift [13] | `rapid upward drone lift, camera climbs above the [battlefield]` | geography reveal | declare altitude endpoint |
| Flyover orbit | `aerial flyover shot circling the [landmark]` | establishing money shot | horizon level, constant radius |
| Top-down cathedral | `slow top-down aerial descent, perfectly perpendicular to the ground` | patterns, formations, god view | compose the ground like a poster |
| FPV dive [6] | `one continuous FPV drone shot, no cuts, one unbroken take, extreme real-time speed, near-miss proximity` | chase adrenaline, fly-through-window one-ers | the corpus phrase insists: never reverses, never slows |

### 1i. Time
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Slow motion [18] | `everything enters slow motion, floating debris nearly freezes` | impact savoring, grace | device truth: pair with a Phantom/high-fps rig from SKILL.md §1 |
| Selective slow motion | `the world slows while [subject] continues at normal speed` | hero focus, anime energy | corpus-proven Seedance trick |
| Speed ramp [3] | `speed ramp transitions, motion blur masking cuts` | action montage glue | ramps live BETWEEN beats, not during dialogue |
| Time-lapse | `time-lapse sky, shadows sweeping across the ground` | passage of time | lock the camera |

### 1j. Focus works
| Atom | Paste phrase | Buys you | Caution |
|---|---|---|---|
| Rack focus [1] | `rack focus from [foreground] to [background]` | attention handoff between two anchors | do not stack with a camera move |
| Focus pull-back [3] | `extreme close-up, focus rapidly pulls back` | shock cut inside one shot | corpus uses it before reveals |
| Focus hunting | `occasional focus hunting, imperfect framing, natural zoom adjustments` | camcorder/UGC truth | belongs to the device-truth kits |

### 1k. Chains (multi-move sequences, the corpus power pattern)
Movement atoms chain BETWEEN shots with arrows; never stack two moves inside one shot.

- Racing chase chain: `interior close-up → over-the-shoulder → exterior side tracking → low ground shot, whip pans + speed ramps masking the cuts`
- One-take waypoint chain: `one continuous shot: [beach orbit] → [follow into water] → [rise to skyline] → [orbit + ascend finale], environments transition seamlessly mid-move`
- Coverage chain (drama default): `wide establishes → medium follows action → close-up reveals consequence`
- Match-cut chain: `continuous move until MATCH CUT on [shape/action], then the move continues in the new world`
- Alternating chase coverage: `camera alternates between intense handheld chase shots, dramatic close-ups, low-angle tracking, and wide cinematic reveals`

## 2 — SHOT DISTANCE ladder

| Distance | Paste phrase | Duty | Seedance caution | Corpus |
|---|---|---|---|---|
| Extreme close-up | `extreme close-up on [eyes / lips / texture]` | emotion spike, texture, tension | tiny motions only | [26] |
| Close-up | `close-up, face filling the frame` | THE workhorse: emotion, lip-sync, product detail | keep camera stable | [155] |
| Medium close-up | `medium close-up, head and shoulders` | dialogue, talking head, UGC | default for spoken lines | — |
| Medium | `medium shot, waist up` | product use, gesture, interviews | good commercial default | [21] |
| Cowboy | `cowboy shot, mid-thigh up` | swagger, holsters, fashion attitude | corpus-alive in shot headers | [2] |
| Medium wide | `medium wide, full body with breathing room` | blocking, dance, outfit | keep action readable | [2] |
| Full shot | `full shot, entire body head to toe` | choreography, OOTD, silhouette | faces get small | [3] |
| Wide | `wide shot establishing [space]` | geography, blocking | do not demand facial acting | [21] |
| Extreme wide | `extreme wide, figure tiny against [landscape]` | scale, loneliness, arrival | logos/faces will drift | [10] |
| Macro | `extreme macro on [material]` | food, jewelry, mechanics | avoid large motion; pair with macro lens from SKILL.md §2 | [16] |

Distance TRAVEL is a movement property: always write moves as `from [start distance] to [end distance]`, e.g. `slow push-in from medium shot to close-up`, `WS gradually collapsing into MCU`, `pull-back from extreme close-up to extreme wide`.

Photo equivalents: headshot = CU, half-body = MS, three-quarter body = cowboy/MW, full-body = FS, environmental portrait = WS.

## 3 — ANGLES

| Angle | Paste phrase | Psychology | Photo corpus |
|---|---|---|---|
| Eye-level | `eye-level angle, honest neutral framing` | equality, documentary trust; the stills default | [2192] |
| Low angle | `low-angle upward shot` | power, heroism, menace | [1009] |
| Extreme low | `extremely low-angle upward shot, ultra-telephoto` | monument, runway domination | corpus fashion staple |
| High angle | `high angle looking down at [subject]` | vulnerability, smallness, cute | [339] |
| Overhead / top-down | `directly overhead top-down shot` | patterns, food, flat lay, god view | [1605 + 604] |
| High-altitude overhead | `high-altitude overhead, camera rapidly rotates and descends` | finale vortex, scale | corpus showpiece |
| Ground level | `ground-level shot, lens millimeters off the floor` | wheels, boots, spilled things | — |
| Worm's eye | `worm's-eye view straight up` | towers, canopies, falling POV inversion | — |
| Dutch tilt | `dutch angle, horizon tilted 15 degrees` | unease, villain energy | use once, on purpose |
| Profile | `strict profile view, side-on` | portrait dignity, duel standoffs, side-by-side intimacy | [197] |
| Three-quarter | `three-quarter view, sharp 45-degree turn` | THE portrait default: depth on a face | [812 + 192] |
| Over-the-shoulder | `over-the-shoulder shot past [A] onto [B]` | conversation geometry, pursuit | [5] video |
| Dead-on frontal | `dead-on symmetrical frontal framing` | Wes Anderson formality, confrontation | pairs with centered composition |
| POV | `strict first-person POV, hands visible at frame edges, face never shown` | immersion, gaming energy | [23] video |

## 4 — PHOTO CAMERA WORKS (stills-specific)

### 4a. Lens + aperture recipes (declare BOTH)
| Recipe | Paste phrase | Duty | Corpus |
|---|---|---|---|
| 85mm portrait | `85mm lens, f/1.8 aperture, creamy background separation` | THE portrait engine | [2900] |
| 50mm candid | `shot on 50mm lens, f/1.8, shallow bokeh, natural perspective` | lifestyle, candid intimacy | [1419] |
| 35mm editorial | `shot on 35mm f/1.4, environmental context kept in frame` | street, reportage, fashion editorial | [2000] |
| 24mm wide | `24mm wide-angle, foreground exaggeration` | interiors, dynamic full-body | [417] |
| Ultra-wide play | `ultra-wide-angle lens perspective making hands and feet loom exaggerated` | comedy, pet noses, energy | corpus-alive |
| Fisheye | `fisheye lens, barrel distortion` | Y2K, skate, CCTV | [208] |
| Telephoto compression | `telephoto compression stacking the background against the subject` | paparazzi, sports, skyline stacking | [178] |
| Macro | `macro lens, 1:1 magnification on [texture]` | product texture, food pores | [1935] |
| Tilt-shift | `tilt-shift lens, miniature-world plane of focus` | city-as-toy, product plane control | — |

### 4b. Composition works
| Atom | Paste phrase | Duty | Corpus |
|---|---|---|---|
| Centered symmetry | `centered symmetrical composition` | formality, posters, architecture | [1265 + 242] |
| Rule of thirds | `rule-of-thirds placement, subject on the left third` | editorial ease | [171] |
| Negative space | `generous negative space above the subject` | premium calm, copy room | — |
| Flat lay | `overhead flat lay arrangement on [surface]` | food, gear spreads, unboxing | [200] |
| Grid / multi-panel | `2x2 grid photo, four-panel composition, same subject four moods` | expression sheets, catalogs | corpus-proven |
| Framing device | `subject framed through [doorway / leaves / window]` | voyeur depth, layers | — |
| Leading lines | `leading lines converging on the subject` | eye control | — |

### 4c. Aspect ratios by duty
`9:16` [2225] vertical social and story · `4:5` [1772] feed portrait · `1:1` [552] avatar and catalog tile · `16:9` [387] hero banner and video cover · `3:4` deck and print portrait · `21:9` cinematic strip.

### 4d. Photo defaults the 15k DB actually ships
`depth of field` [6951] and `bokeh` [3562] near-universal · `golden hour` [3316] the default hour · `studio lighting` + `softbox` [3267] the default indoor · `eye-level` dominates angle · `film grain` [1563] the default texture · `shot on iPhone` [2247] the UGC device truth vs `DSLR` [1142] the clean truth.

## 5 — MODIFIER SCALES (attach to any movement atom)

- Speed ladder: `extremely slow` → `slow` → `confident` → `brisk` → `rapid` → `whips` (with `completing in N seconds` for precision)
- Smoothness ladder: `locked` → `gimbal-smooth` → `steadicam glide` → `organic handheld breathing` → `slight shake` → `violent shake`
- Imperfection ladder (UGC truth): `imperfect framing` → `slight tilt` → `focus hunting` → `auto-exposure shifts` → `one-handed phone grip`
- Endpoint vocabulary: `ending locked on [composition]` · `settling into a hold` · `easing into the final frame` (video models often ignore in-prompt easing: plan the ease as a post time-remap, seedance confirmed 2/2 constant-velocity) · `forming a perfect seamless loop`

## 6 — COMPOSITION RULES (the grammar hooks)

1. ONE movement atom per shot. Chains live BETWEEN shots (§1k arrows), stacks do not exist.
2. Every move declares speed + destination: `[atom] at [speed], from [start] to [end distance], ending on [endpoint]`.
3. Movement follows duty: dialogue = locked or micro; product hero = orbit or push-in; travel = follow or track; scale = air family; chaos = handheld intense + whip pans between shots.
4. Anti-stack list, corpus-verified failure smells: `static camera` + `orbit` in one segment · orbit on a face whose identity must hold · crane during dialogue · dolly zoom anywhere except the one earned moment · slow motion without a high-fps device declared.
5. The angle is an argument: write WHY when it matters, `low to elongate the legs`, `high to shrink him against the desk`. Models weight motivated clauses.
6. Photo work composes the same way: [lens+aperture recipe] + [angle] + [distance] + [composition atom] + [aspect ratio], then light from SKILL.md §4 and grade from §5.
