# Standard courtroom: 2D defense style test

An AI-generated style study made with the built-in image generation tool. Keeps the standard DD/SoJ courtroom composition while aiming for the painted 2D background treatment of Apollo Justice: Ace Attorney. This is an experimental alternative, not official game artwork.

- `defense-v1.png`: clean background, without a character.
- Original architecture reference: `../defense.webp` ([source](https://aceattorney.fandom.com/wiki/File:Defense_Bench.png)).
- Style reference: [Apollo Justice defense background](https://aceattorney.fandom.com/wiki/File:AJ_Defense%27s_Bench.png).
- Original game architecture, characters, and reference artwork: Capcom.
- Use a separate foreground defense desk when previewing a character.

## Generation prompt

Use case: style-transfer. Create a single clean usable courtroom DEFENSE POSITION BACKGROUND for objection.lol, as a 2D illustrated redraw of reference image 1, not a composite preview. Image 1 is the composition/architecture target: the standard courtroom from Dual Destinies / Spirit of Justice, a side-on close view of the golden wood paneling and elevated gallery balustrade behind the defense attorney, balcony descending diagonally toward the right, cream wall and sconce at upper right, low thin sloping wood rail at the very bottom. Image 2 is STYLE ONLY: the clean hand-painted 2D background rendering of Apollo Justice Ace Attorney. Keep image 1's recognizable two-level courtroom architecture, gallery vertical balusters, framed lower wood panels, camera angle, perspective, and all major edge positions. Redraw these shapes with deliberate crisp 2D contour edges, simplified broad cel-painted light/shadow shapes, warm honey-gold wood, restrained painted gradients, muted ivory walls, like a 2000s Nintendo DS visual-novel background restored cleanly at high resolution. Make it visibly drawn, flatter and more graphic than the 3D source; no blurred 3D textures, CGI, realism, volumetric glow, or heavy textured brushwork. Leave the central attorney silhouette area visually calm. The background must contain NO characters, no face, no sprite, no lettering, dialogue box, watermark, layout, comparison labels, or border. Do not invent an extra desk across the middle. Preserve the thin foreground rail at the bottom edge; the actual attorney and separate desk will be composited by the application later. Landscape frame, approximately 5:3 aspect matching reference 1. Output only the complete background illustration, edge to edge.
