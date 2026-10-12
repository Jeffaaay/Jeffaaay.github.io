# 3D model sources and licences

All files under `public/models/` were downloaded on 2026-10-10 from the sources below and are redistributed under the licences stated by those sources. No Crayon Shin-chan material was used as input anywhere.

## In use

| File | Model | Author | Licence | Source |
| --- | --- | --- | --- | --- |
| `dog/quaternius-shiba.glb` | Shiba Inu (rigged, 12 animation clips) | Quaternius | CC0 1.0 (public domain) — stated on the Poly Pizza page and on quaternius.com for all Quaternius packs | https://poly.pizza/m/y4wdQpg767 (file: https://static.poly.pizza/ba6d0ee3-bcc0-4ef0-9d3c-a3e245b41c77.glb); pack: https://quaternius.com/packs/ultimateanimatedanimals.html |

The Shiba is reshaped at runtime (shorter legs, bigger ears, shorter tail) and recoloured with the game's toon materials into an original tricolour corgi; the GLB itself is unmodified.

## Candidates kept for review only (`candidates/`)

| File | Model | Author | Licence | Source |
| --- | --- | --- | --- | --- |
| `candidates/quaternius-shiba.glb` | same as above | Quaternius | CC0 1.0 | see above |
| `candidates/gobkit-corgi.glb` | Corgi (rigged: idle / attack / dead / walk) | Gobkit | CC0 1.0 — "free for any use, commercial or personal, no attribution required" (manifest `https://gobkit.com/api/free`, GLB `asset.copyright`) | https://gobkit.itch.io/gobkit-free-animal-pack ; https://gobkit.com/freebies/animal/Corgi.glb |
| `candidates/madtroll-corgi.glb` | Corgi (static mesh, textured, not rigged) | madtrollstudio | CC BY 3.0 — attribution required if used (https://creativecommons.org/licenses/by/3.0/) | https://poly.pizza/m/2neHxHTY3t (file: https://static.poly.pizza/152ff42e-dc8f-4e84-b129-ef54fadf8916.glb) |
| `candidates/quaternius-dog.fbx` | Dog (rigged: Walking / Idle), from "Animal Pack Vol.2" | Quaternius | CC0 1.0 | https://opengameart.org/content/animated-animales-low-poly (zip: https://opengameart.org/sites/default/files/Animal%20Pack%20Vol.2%20by%20%40Quaternius.zip) |
| `candidates/quaternius-pug.glb` | Pug (rigged: Idle / Jump) | Quaternius | CC0 1.0 | https://poly.pizza/m/1gXKv15ik8 |

Candidates that are not chosen can be deleted; only `dog/` is loaded by the game.

## Not usable without a purchase or an account

- Superhive "Pembroke Corgi Puppy Dog" (paid, royalty-free): the owner decides whether to buy; a purchased file would go to `public/models/dog/corgi.glb` and must not be committed to a public repository unless its licence allows redistribution.
- Sketchfab CC-BY corgis (e.g. "Dog corgi animated" by zinaida): download requires a Sketchfab account; not fetched.
