# Helix Hustle: art

**Status:** no art yet. The game runs now with stand-ins (brand-kit badges, `logo.svg`, a code-drawn Dex).

## Request

**22 images total: 1 game logo + 16 badges + 5 mascot moods.**

Every molecule and diagram in the game (bases, sugars, nucleotides, strands, the replication fork, tRNA, ribosome, splicing) is drawn by the game's code, because the rings, bonds and 5′/3′ directions have to be exact. Don't make those.

When a file with the exact name below is dropped in, the game uses it automatically. No code changes are needed.

Style: glossy cartoon, like the 35-badge sheet, Sig Fig Sleuth and Lipid Lab sets. Transparent background, thick dark-navy outlines, soft pastels with a mint-teal accent. No text except the letters or symbols listed.

## 1 game logo

| File | Size | Subject |
|---|---|---|
| `logo.png` in this repo, `assets/logo-256.webp` in this repo, and `assets/games/nucleicacids.webp` in the games repo (study hub card) | 1024 × 1024 (logo.png can be 512) | Round badge. A cheerful short DNA double helix with a face (Dex) dashing forward with little speed lines, one blue strand and one orange strand, rungs in pink, yellow, mint and sky blue. A small ribosome and a curly mRNA ribbon trail behind. Name: Helix Hustle. |

Use the brand prompt from itsdrdan.github.io/games/brand and change only the Subject line.

## Mascot: Dex the DNA helix (5 moods)

Dex is a short, chubby double helix: a round mint-teal head on top, with one blue strand and one orange strand twisting below it as legs, and three colorful base-pair rungs (pink, yellow, mint) between them. Small stubby arms are fine. Same character, same size and position in every mood, so the game can swap them smoothly.

| File | Mood |
|---|---|
| `assets/mascot/dex-idle.webp` | Calm, friendly smile, standing on both strands |
| `assets/mascot/dex-thinking.webp` | Looking up, one hand on chin, small thought bubble |
| `assets/mascot/dex-correct.webp` | Big happy grin, eyes closed in joy, a thumbs-up |
| `assets/mascot/dex-oops.webp` | Worried brows, wobbly smile, strands a little tangled |
| `assets/mascot/dex-victory.webp` | Jumping with both arms up, sparkles and a little gold star |

Make them on one sheet if that's easier; they get cut to **320 × 320 transparent WebP**.

## 16 badges

Make them on one sheet. Each badge is cut to **256 × 256 transparent WebP** and saved in `assets/` in this repo.

### 6 menu badges

| File | Used for | Subject |
|---|---|---|
| `cat-blocks.webp` | Building Blocks | A cute nucleotide: a pentagon sugar holding a two-ring base flag, with a small round phosphate ball on a stick |
| `cat-structure.webp` | DNA & RNA Structure | A short glossy double helix ladder with colored rungs |
| `cat-copy.webp` | Replication & Transcription | A Y-shaped DNA fork unzipping, with a tiny copy machine page coming out |
| `cat-protein.webp` | Translation & Mutations | A ribosome (two rounded blobs) reading a ribbon of mRNA, with a bead chain (protein) coming out the top |
| `skillcheck.webp` | Skill Check Prep | A gold trophy with a small double helix on it and a checkmark ribbon |
| `finalreview.webp` | Final-exam review | A thick review book with a small crown on top and a DNA helix bookmark |

### 10 achievement badges

| File | Achievement | Subject |
|---|---|---|
| `ach-first.webp` | First Base | A baseball base (home plate shape) with a little "A" on it and a sparkle |
| `ach-streak5.webp` | On a Roll | A row of 5 green check marks rolling like a wave |
| `ach-streak10.webp` | Unstoppable | A flaming rocket with a "10" on its side |
| `ach-bases.webp` | Base Collector | Five little letter tiles A, G, C, T, U in a happy row |
| `ach-pair.webp` | Perfect Pair | Two puzzle pieces, "A" and "T", clicking together with a heart |
| `ach-copy.webp` | Copy Machine | Two identical double helices side by side, one shiny new |
| `ach-transcribe.webp` | Transcriber | A quill pen writing a ribbon of mRNA letters (A U G) |
| `ach-code.webp` | Code Cracker | A padlock opening, with "AUG" on its tag |
| `ach-mutant.webp` | Mutation Detective | A magnifying glass over a DNA rung that is a different color |
| `ach-skill.webp` | Skill Check Ready | A gold medal with a ribbon and a small double helix on it |

## Where the images go

- `nucleicacids/logo.png` and `nucleicacids/assets/logo-256.webp` (game header and Canvas)
- `nucleicacids/assets/mascot/dex-idle.webp` … `dex-victory.webp` (5 files)
- `nucleicacids/assets/cat-blocks.webp` … `nucleicacids/assets/ach-skill.webp` (16 files)
- `games/assets/games/nucleicacids.webp` (the study hub card; that file lives in the games repo)

Bring the sheets back to Claude and they'll be cut, sized and dropped in.
