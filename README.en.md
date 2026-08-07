<div align="center">

# Gathered Scenes Zine

### 拾景纸刊

Turning ordinary scenes into pages worth lingering over.

**Author · zeejay**

[简体中文](README.md) · [Two creative paths](#two-creative-paths) · [Get started](#get-started) · [Scene archive](#scene-archive)

</div>

![Gathered Scenes Zine cover](assets/brand/gathered-scenes-cover.jpg)

> A SMALL PRESS FOR EVERYDAY SCENES.

Gathered Scenes Zine is a collection of image-generation skills for Codex. Instead of applying a fixed visual filter, the skills first read a photograph—its subjects, spatial relationships, color, movement, and emotional residue—then either preserve the scene or distill it into a new paper artwork.

The photograph provides the facts. Art direction decides how they remain.

---

## How we read a photograph

```text
photograph → observe → extract relationships → choose a path → bind a new page
```

The visual system follows five principles: truthful photography as an anchor, illustration as a field, color as structure, negative space as an active voice, and tactile paper boundaries as material language.

![We collect fragments of the world and bind fleeting moments into a new page](assets/brand/gathered-scenes-manifesto.jpg)

## Two creative paths

| | 实景拼贴 · Gathered Scenes | 影像蒸馏 · Scene Distillation |
| --- | --- | --- |
| **Best for** | Keeping the source photograph and its identity | Creating a fully independent illustrated artwork |
| **Role of the photo** | A truthful visual anchor in the final poster | Semantic and emotional evidence only; no source pixels remain |
| **Method** | Photography, source-derived abstraction, structural color, and torn paper | Proposition, tension, visual metaphor, paper, color, and authorial type |
| **Skill** | `$scenes-gathered-zine-v1-3` | `$scene-distillation-zine-v1-3` |

### 01 · 实景拼贴 / Gathered Scenes

`scenes-gathered-zine-v1-3` keeps the photograph's irreplaceable spatial relationships. It extends the scene through simplified abstract forms, one high-chroma structural hue, active negative space, and a visible hand-torn fibrous edge.

```text
Use $scenes-gathered-zine-v1-3 to turn this photo into a Gathered Scenes poster.
Preserve the relationship between the figure and the shoreline.
```

[Read the full skill](skills/scenes-gathered-zine-v1-3/SKILL.md)

### 02 · 影像蒸馏 / Scene Distillation

`scene-distillation-zine-v1-3` does not retain the original photograph in the finished image. It extracts a semantic nucleus, emotional tension, and visual metaphor, then authors a new paper-based editorial artwork.

```text
Use $scene-distillation-zine-v1-3 to reinterpret this photo.
Do not preserve the photograph itself; express “approaching and missing.”
```

[Read the full skill](skills/scene-distillation-zine-v1-3/SKILL.md)

## From scene to page

| Stage | What happens |
| --- | --- |
| **01 · Observe** | Locate the core subject, spatial relationships, direction, weight, and quiet areas |
| **02 · Reduce** | Keep the minimum that makes this particular scene recognizable |
| **03 · Translate** | Turn contours, paths, light, material, or emotion into paper-native form and color |
| **04 · Compose** | Build a clear eye path through image, type, boundary, and negative space |
| **05 · Bind** | Deliver a flat, restrained, tactile artwork that stands on its own |

## Scene archive

Representative work will be presented as **source photograph → field note → finished poster**, documenting what was retained, removed, and transformed. The first collection is being prepared in [`examples/`](examples/).

## Get started

Clone the repository and copy either or both skills into the Codex Skills directory:

```bash
git clone https://github.com/Zeejay0/gathered-scenes-zine-skill.git
mkdir -p ~/.codex/skills
cp -R gathered-scenes-zine-skill/skills/scenes-gathered-zine-v1-3 ~/.codex/skills/
cp -R gathered-scenes-zine-skill/skills/scene-distillation-zine-v1-3 ~/.codex/skills/
```

Restart Codex if the skills do not appear immediately. Upload a photograph, choose whether to preserve or distill the scene, and invoke the corresponding skill by name.

## Repository

```text
assets/       brand and README media
examples/     curated source-to-result scene archives
skills/       installable Codex skills and interface metadata
```

Source photographs are used only as references for the requested generation. They should not be browsed, shared, uploaded elsewhere, or saved unless the user explicitly asks.

## Find the author

**Author: zeejay**

The same username, `zeejay`, is used on Douyin and other content platforms. Search for it on the platform you use to find the author and future work.

If you publish work made with these skills, a quiet credit at the end of the caption is appreciated: `Visual Skill by @zeejay`.

## License

[MIT](LICENSE) © zeejay

<div align="center">

**Collect the scene. Keep the moment.**

AI-GENERATED PAPER ART · 2026

</div>
