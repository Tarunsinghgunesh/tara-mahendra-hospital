# Advanced Animation & 3D Specification

## Level 1 — Core
- fade-up reveals
- staggered cards
- smooth section transitions
- button micro-interactions
- header compression

## Level 2 — Premium
- mouse parallax hero
- 3D card tilt
- floating medical cards
- animated ECG line
- ambient blobs
- number count-up
- magnetic CTA

## Level 3 — Optional WebGL
If performance permits:
- abstract medical sphere
- translucent rings
- floating particles
- cyan/blue light field
- slow camera movement

Rules:
- desktop only for heavy 3D
- disable/reduce on mobile
- pause when tab is hidden
- support prefers-reduced-motion
- no distracting continuous rotation

Suggested implementation:
CSS transforms first.
Use requestAnimationFrame only where needed.
If Three.js is introduced, keep scene extremely lightweight.
