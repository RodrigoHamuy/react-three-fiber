---
'@react-three/fiber': minor
---

feat: add `state.timer` (THREE.Timer) and deprecate `state.clock`

Adds `state.timer`, a `THREE.Timer` instance, available on three r178+ (otherwise `undefined`). `state.clock` is unchanged but marked deprecated; prefer `state.timer` where available.
