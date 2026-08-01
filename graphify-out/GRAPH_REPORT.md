# Graph Report - camera-lens-library  (2026-07-06)

## Corpus Check
- 2 files · ~3,777 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 27 nodes · 26 edges · 3 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `fb7c78f7`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]

## God Nodes (most connected - your core abstractions)
1. `Camera / Lens / Lighting / LUT Library — device-truth blocks for generation prompts` - 10 edges
2. `1 — CAMERAS by duty` - 10 edges
3. `2 — LENSES` - 7 edges
4. `4 — LIGHTING library (ONE motivated source statement per prompt)` - 2 edges
5. `How to use` - 1 edges
6. `Cinema A-camera (features / premium TVC)` - 1 edges
7. `Commercial / tabletop / high-speed` - 1 edges
8. `Broadcast / documentary / ENG` - 1 edges
9. `Hybrid / vlog / creator` - 1 edges
10. `Action / POV` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (3 total, 0 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.20
Nodes (9): 3 — RECIPES (paste-ready; angle + framing psychology included), 4 — LIGHTING library (ONE motivated source statement per prompt), 5 — LUT / GRADE library (name the finish; post can still re-grade), 6 — Reference-anchored i2i + reverse-prompting (the overrides), 7 — Speed vocabulary (pairs with any recipe), 8 — Cinema prompt architecture (distilled from the Higgsfield Soul cinema community, 2026-07-06), Camera / Lens / Lighting / LUT Library — device-truth blocks for generation prompts, Fixture spec table (name the instrument when the set is part of the story) (+1 more)

### Community 1 - "Community 1"
Cohesion: 0.20
Nodes (10): 1 — CAMERAS by duty, Action / POV, Broadcast / documentary / ENG, Cinema A-camera (features / premium TVC), Commercial / tabletop / high-speed, Drone / aerial, Hybrid / vlog / creator, Phone (UGC truth) (+2 more)

### Community 2 - "Community 2"
Cohesion: 0.29
Nodes (7): 2 — LENSES, Anamorphic, Cine primes, Macro / probe / special, Stills classics (for photo-real keyframes), Telephoto / wildlife / surveillance, Zooms

## Knowledge Gaps
- **22 isolated node(s):** `How to use`, `Cinema A-camera (features / premium TVC)`, `Commercial / tabletop / high-speed`, `Broadcast / documentary / ENG`, `Hybrid / vlog / creator` (+17 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Camera / Lens / Lighting / LUT Library — device-truth blocks for generation prompts` connect `Community 0` to `Community 1`, `Community 2`?**
  _High betweenness centrality (0.794) - this node is a cross-community bridge._
- **Why does `1 — CAMERAS by duty` connect `Community 1` to `Community 0`?**
  _High betweenness centrality (0.582) - this node is a cross-community bridge._
- **Why does `2 — LENSES` connect `Community 2` to `Community 0`?**
  _High betweenness centrality (0.415) - this node is a cross-community bridge._
- **What connects `How to use`, `Cinema A-camera (features / premium TVC)`, `Commercial / tabletop / high-speed` to the rest of the system?**
  _22 weakly-connected nodes found - possible documentation gaps or missing edges._