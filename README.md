# camera-lens-library

A grab-and-paste library of **real cameras, lenses, rigs, lighting setups and LUT/grade looks** for AI image/video generation prompts — cinema, commercial, broadcast, vlog, stills, drone, phone, surveillance. Born 2026-07-05 from the haidilao camera-grammar crisis: abstract "cinematic" language generates AI mush; a named sensor, focal length, T-stop, motivated light and grade generate photographs.

The skill itself is `SKILL.md` — a Claude Code user-level skill.

## Install

```bash
git clone git@github.com:ak3ne/camera-lens-library.git ~/Projects/camera-lens-library
ln -sfn ~/Projects/camera-lens-library ~/.claude/skills/camera-lens-library
```

## Contents

- **§1 Cameras by duty** — cinema A-cams, high-speed/tabletop, broadcast/ENG, hybrid/vlog, action/POV, phone UGC, stills/medium format, drone, specialty device-truth kits (CCTV/dashcam/bodycam/VHS/16mm…)
- **§2 Lenses** — cine primes, anamorphics, zooms, macro/probe, telephoto/paparazzi, vintage character, stills classics
- **§3 Recipes** — paste-ready per shot-type blocks with angle + framing psychology (incl. the hidden-shooter paparazzi block)
- **§4 Lighting library** — natural/studio/practical/on-camera statements + a fixture spec table
- **§5 LUT / grade library** — print-film emulations, digital/broadcast grades, the food-commercial house grade, era/degradation looks
- **§6 Reference-anchored i2i + reverse-prompting** — when a reference exists, anchor on the image; extract its device/light/grade block first
- **§7 Speed vocabulary**

## Sync contract (LAW)

**Canonical:** this repo (`~/Projects/camera-lens-library`, GitHub `ak3ne/camera-lens-library`).
**Live skill:** `~/.claude/skills/camera-lens-library` is a SYMLINK into this repo — editing the skill edits the repo.
**Vendored copy:** `~/Projects/cyane/docs/cyane-camera-library.md` (the cyane pipeline reads it offline).

Every edit to `SKILL.md` must, in the same session: (1) be committed + pushed here, and (2) be re-copied over the cyane vendored file and committed in cyane. Same law as moviola (`cyane/tools/MOVIOLA-VENDORED.md`). A drifted vendored copy is a bug.

## Companion doctrine

`~/Projects/cyane/docs/cyane-camera.md` — the grammar (device-truth + operator, speed + destination, one move per shot). This library is the vocabulary; that doc is the grammar.
