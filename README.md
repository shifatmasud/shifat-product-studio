# Shifat / Studio

Live, interactive Apple-style product studio in three.js r187.

- Three-point lighting only (key, fill, rim), camera-relative rig, reflections mirror the same softboxes
- Procedural iPhone 17 Pro-style model: aluminum unibody, full-width camera plateau, Ceramic Shield glass panel with Apple logo, three lenses, flash, LiDAR, mic, buttons incl. Camera Control, USB-C + grilles, Dynamic Island
- Screen is unlit (only its own light)
- Pull-up / pull-down drawer UI; scene reframes above it
- Agent API on `window.studio` (goTo, setColor, setLighting, toggleScreen, shot, loadModel, build, setDrawer)

## URL params

`?still` (no motion), `noui`, `closed`, `mode=light|dark`, `color=titanium|silver|ink|shade|peach`, `angle=hero|front|back|side|top`, `screen`, `rot=<deg>`, `model=<glb url>`

Static site: just `index.html`. Deployed on Vercel.
