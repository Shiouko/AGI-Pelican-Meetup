# AGI-Pelican-Meetup

**Pelican Noir — Showdown at the Social Club**: a 75-second, fully procedural cinematic mafia
showdown in a single self-contained HTML file (`index.html`). Three.js is the only external
dependency, loaded from jsDelivr; everything else (geometry, textures, shaders, particles, music
and sound effects) is generated in code at load time.

Open `index.html` directly in a modern browser (an internet connection is needed for the
Three.js CDN). Click the speaker button to start the sound. The score and effects are
synthesized when the page loads, so the speaker may show "Preparing sound…" for a few seconds.

## Controls

| Button | Key | Action |
| --- | --- | --- |
| Speaker | `M` | Start the Web Audio score/SFX, then mute/unmute |
| Pause | `Space` | Pause / resume (audio pauses in sync) |
| Replay | `R` | Restart from the top |

Append `?t=SECONDS` to the URL to start part-way through (e.g. `index.html?t=33` for the
slow-motion wheelie).

## What's in it

### World and look
- Rain-soaked 1940s dockside: wet cobblestones with rain ripples in the puddles, brick warehouses,
  steaming manholes, a lit freighter in the harbour, a clock tower across the water, lightning,
  and the flickering **@vulkan42069 SOCIAL CLUB** neon sign above the back door.
- Voxel pelicans (gang in pinstripes, rivals in trench coats, the boss with cigar and white scarf,
  the hero with aviators, red headband and twin pistols, the sharpshooter in a flat cap) and the
  hero's bright red voxel bicycle. Everything else uses physically based materials.
- Lofted 1940s sedans with chrome, whitewalls, opening doors, visible passengers, working
  suspension, steering and headlights that can be shot out.
- Detailed weapons: parkerized pistols, a Thompson with drum magazine and finned barrel, and a
  scoped bolt-action sniper rifle with bipod and muzzle brake.

### Action and effects
- Spring-driven character animation: gait-synced footsteps, recoil, flinches when rounds land
  close, glances, and tumbling ragdoll exits (bloodless: feathers, sparks and fades).
- 3D muzzle flashes that light the scene, tracers, bullet-hole decals, sparks, splinters, brick
  chips, glass, brass casings and voxel debris.
- Post-processing: bloom, camera motion blur, anamorphic lens flares, raindrops on the lens,
  chromatic aberration, shell-shock blur, a heartbeat-pulsing vignette, ACES filmic tone mapping,
  colour grade, film grain, letterbox bars and a scope view with breathing sway.

### Sound
- Every sound is synthesized: layered gunfire with mechanical action, supersonic crack and
  street echo trains; a sniper report that rolls across the harbour; bullet whizzes, ricochets,
  wood, brick, metal and glass impacts; idling straight-eight engines, doors, tyres, a bicycle bell and skid.
- Convolution reverbs for the street, the back room and the open harbour; distance, panning and
  air absorption per source; slow-motion pitch drop and shell-shock tinnitus after close blasts.
- Tension devices: rising Shepard tones, a heartbeat that speeds up, a ticking clock and
  church-bell toll, the sniper's breathing, radio static, and moments of near silence.
- A noir score of strings, brass and percussion that resolves into a D-major finale.

Adaptive resolution keeps the frame rate smooth on slower GPUs.
