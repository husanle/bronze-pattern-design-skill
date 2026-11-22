# Bronze Pattern Design

[简体中文](README.zh-CN.md)

A bilingual Codex skill for turning ancient Chinese bronze ornament into practical product design. Use it to distinguish a close redraw from production artwork, place the design where it will not obstruct use, and make a print-ready presentation board.

| Task | What the skill helps produce |
|---|---|
| Identify motifs | Candidate names, visible features, uncertainty, and source notes |
| Redraw | A close study compared with a source crop, plus a separate vector application if needed |
| Design products | Motif placement, functional clear zones, materials and prototype checks |
| Present and print | A product-led board, source credits, and a checked monochrome PDF |

## Install

Clone or download this repository. Copy [`skills/bronze-pattern-design`](skills/bronze-pattern-design) as a complete folder into `~/.agents/skills/` for your account, or into `.agents/skills/` within the target project. See the [Codex skills guide](https://developers.openai.com/codex/skills) for discovery and invocation.

## Try it

Attach source photos or provide collection links. Then ask:

> Use $bronze-pattern-design to identify these motifs from the exhibition labels. Redraw the dragon and bird closely with ImageGen, then design a pen and notebook. Keep the grip and writing zones clean. Deliver a monochrome A4 landscape board with products on the left, redraws on the upper right, and sources below without figure numbers.

ImageGen is optional unless requested. The skill needs no API key, scripts, or additional services to provide guidance. It does not authenticate objects, grant image rights, or create an official museum collaboration. No source photographs are bundled.

## Skill contents

- [Skill instructions](skills/bronze-pattern-design/SKILL.md)
- [Motif field guide](skills/bronze-pattern-design/references/motif-field-guide.md)
- [Product and board workflow](skills/bronze-pattern-design/references/product-and-board.md)
