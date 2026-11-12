# The Lantern Whale — make.fun coolest-art-01

A colossal whale made of glowing paper lanterns swims through a deep indigo
night sky above a tiny sleeping coastal town. Its body is a constellation of
warm lanterns; its one huge eye is a ring of light. Thin threads of gold trail
from its fins. One mood: indigo night against lantern gold, one bold diagonal
silhouette that still reads at 300 pixels across.

The image is an original work generated for this entry (not the kit's starter
image, not a copy of any existing artwork or photo). It ships base64-encoded
as `entry.png.b64` so the repository stays plain UTF-8 text; the program
decodes it to `/output/entry.png` — so both grader runs write identical
bytes.

## Files

- `entry.png.b64` — the art, base64-encoded. JPEG bytes once decoded (the
  rules allow PNG or JPEG, told apart by their first bytes). 1024x1024,
  325,333 bytes, sha256 `ee4d7e5ca4899d77fdb232f493e407a5b86e2f2e8f30c4e946778dd6866feaab`.
- `main.ts` — Node 22, standard library only. Decodes `entry.png.b64` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png` in the grader).

## Run it locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# out/entry.png is the decoded art, sha256 ee4d7e5ca4899d77fdb232f493e407a5b86e2f2e8f30c4e946778dd6866feaab
```
