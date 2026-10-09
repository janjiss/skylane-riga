# Surface textures

CC0 PBR materials from [ambientCG](https://ambientcg.com) (public domain, no attribution required),
downloaded at 1K and repacked for the game by hand:

- `<id>_color.jpg` — albedo (sRGB), 1024² (`MetalWalkway014_color.png` has an alpha cut-out)
- `<id>_normal.jpg` — OpenGL normal map, 1024²
- `<id>_orm.jpg` — R ambient occlusion, G roughness, B metalness, 512²
- `<id>_height.jpg` — displacement, 512²

Concrete042C, Concrete036, Concrete032, Concrete044D, Concrete013, Metal021, Metal063, MetalPlates013,
MetalPlates017A, CorrugatedSteel008A, MetalWalkway014, Bricks097, Bricks089, Bricks085, Bricks100,
PaintedPlaster016, Plaster007, Asphalt033, Road013A, PavingStones142, PavingStones070, RoofingTiles014B.

The originals live in `~/.local/share/skylane-assets/textures/` (zips from
`https://ambientcg.com/get?file=<id>_1K-JPG.zip`). Load them through `src/world/textures.js`.
