# Media assets

Drop images/screenshots here. Pages look for these filenames and show a
dashed placeholder until the file exists (the `<img>` hides itself on error).

## drones.html
- `gazebo-sim.jpg`   — screenshot or GIF still of the Gazebo Harmonic multi-UAV sim
- `telemetry.jpg`    — telemetry / odometry validation view
- `coverage-2d.png`  — the 2D coverage abstraction plot (25 targets, 5x5 grid)
- `dqn-curve.png`    — DQN training reward curve (export from matplotlib)

## vtol.html
- `vtol-render.jpg`   — full airframe CAD render (isometric)
- `vtol-tilt.jpg`     — 2-axis tilt-rotor mechanism detail
- `vtol-print.jpg`    — FDM-printed structural component
- `vtol-assembly.jpg` — physical assembly (wing + motor mounts)

## frc.html
- `frc-robot.jpg`     — 2026 swerve-drive competition robot
- `frc-match.jpg`     — team competing / drive coaching on the field

## Social preview (used by og:image)
- `social-card.jpg`   — 1200x630 link-preview card (falls back to profile-photo.jpeg if absent)

## Tips
- For the swarm sim, a short screen recording exported as an MP4/GIF loop is far
  more compelling than a still. If you add video, embed it with
  `<video autoplay muted loop playsinline>` in place of the `<img>`.
- Keep images reasonably sized (< ~500 KB each) so pages stay fast.
- Landscape 16:10 crops fit the gallery frames best.
