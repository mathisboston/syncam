# Syncam

Synchronized multi smartphone video capture for dynamic 3D/4D reconstruction.

## Goal

Join 2–12 phones from a browser session, start and stop capture together, and keep original videos with timing metadata for offline alignment.

## Status

Early prototype. Browser based recording cannot guarantee synchronized sensor exposure. Timing accuracy must be measured on real devices before making performance claims.

## Planned MVP

- Create a session and join phones by link or QR code.
- Show device readiness and camera settings.
- Schedule a shared start and stop using monotonic clock estimates.
- Save original recordings locally with timing metadata.
- Evaluate alignment using a shared visual or audio reference.

## Tech stack

React, TypeScript, Vite, FastAPI, WebSockets, Python and FFmpeg.
