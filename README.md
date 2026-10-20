# AGI-Pelican-Meetup

**Pelican Noir — Showdown at the Social Club**: a 75-second, fully procedural cinematic mafia
showdown in a single self-contained HTML file (`index.html`). Three.js is the only external
dependency, loaded from jsDelivr; everything else (geometry, textures, shaders, particles, music
and sound effects) is generated in code at load time.

Open `index.html` directly in a modern browser (an internet connection is needed for the
Three.js CDN). Click the speaker button to start the sound.

## Controls

| Button | Key | Action |
| --- | --- | --- |
| Speaker | `M` | Start the Web Audio score/SFX, then mute/unmute |
| Pause | `Space` | Pause / resume (audio pauses in sync) |
| Replay | `R` | Restart from the top |

Append `?t=SECONDS` to the URL to start part-way through (e.g. `index.html?t=33` for the
slow-motion wheelie).

## What's in it

- Rain-soaked 1940s dockside: wet cobblestones with puddles, brick warehouses, steaming manholes,
  a lit freighter in the harbour, a clock tower across the water and the flickering
  **@vulkan42069 SOCIAL CLUB** neon sign above the back door.
- Voxel pelicans (gang in pinstripes, rivals in trench coats, the boss with cigar and white scarf,
  the hero with aviators, red headband and twin pistols, the sharpshooter in a flat cap) and the
  hero's bright red voxel bicycle — everything else uses physically based materials.
- Volumetric streetlight and headlight beams, drifting fog, instanced rain that freezes in slow
  motion, light-reflection streaks on the wet street, muzzle-flash lighting, tracers, sparks,
  feathers, glass, splinters and brass casings.
- Post-processing: bloom, camera motion blur, anamorphic lens flares, chromatic aberration,
  ACES filmic tone mapping, colour grade, film grain, letterbox bars, cut dips and a scope view.
- Single master timeline with a warped "story clock" for slow motion and the bullet-cam.
- Web Audio: rain bed, foghorns, walking jazz bass with brushes, car engines and doors, layered
  gunfire, ricochets, shattering glass, bicycle bell, a booming sniper crack with echo, and a noir
  score that resolves into a D-major finale.
- Adaptive resolution keeps the frame rate smooth on slower GPUs.
