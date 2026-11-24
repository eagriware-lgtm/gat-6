# GAT 6 — Coastline

An original open-world driving and exploration prototype, built as a browser-playable vertical slice.

## Play
Serve the repository root with any static web server and open `index.html`. The project loads Three.js 0.160.0 from jsDelivr, so an internet connection is required.

## Controls
- **W A S D** — walk / drive
- **Shift** — sprint / boost
- **E** — talk to nearby mission NPCs, continue dialogue, or enter / exit the vehicle
- **Mouse drag** — orbit the gameplay camera
- **Space** — jump while on foot; skip the opening cinematic while it is playing

## Current build
- Procedurally assembled coastal city blockout with roads, buildings, palm trees and ocean
- Third-person on-foot exploration and a drivable vehicle
- Acceleration, braking, steering and boost
- Three-stage checkpoint route
- HUD, speed display and minimap
- A 10-second multi-shot opening cinematic with letterbox bars, camera moves and title captions
- A segmented humanoid player model with a head, torso, arms, legs and shoes
- Two named NPCs, Maya and Leo, with simple idle animation
- In-world NPC conversations through a dialogue panel (not cinematic cutscenes)
- A four-stage mission: meet Maya, deliver supplies, check in with Leo, activate the coast signal
- On-foot jumping with gravity and landing
- Mission progression stays gameplay-only: NPC dialogue panels, no cinematic mission cutscenes
- Voice recordings are intentionally not included; the project can add user-recorded dialogue later

## Visual target and honest scope
GAT 6 aims for cinematic open-world presentation, but this browser prototype is **not** at the graphical fidelity of Grand Theft Auto VI. Achieving that class of visuals requires a full 3D production pipeline, detailed original assets, character animation, performance capture, lighting and extensive optimisation. This repository is the playable prototype and cinematic foundation, not a finished AAA game.

## Creative direction
Build an original coastal city game with original characters, places, missions, story and assets. This is a fan-made project and is not affiliated with Rockstar Games. Do not use Rockstar-owned characters, maps, music, logos or game assets.

## Technology
- HTML, CSS and JavaScript modules
- Three.js 0.160.0 via CDN
