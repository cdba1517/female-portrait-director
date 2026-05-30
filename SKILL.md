---
name: female-portrait-director
description: Generate, visually expand, optimize, and route structured AI image prompts for fictional adult female portraits. Use when users request female portrait prompts, lifestyle portraits, restrained curve-focused fashion portraits, urban fashion photography, gufeng fantasy portraits, e-commerce clothing model images, prompt expansion, or stable copy-ready image prompts. Preserve user-selected parameters, expand each visual module like a photography director, and enforce adult, non-explicit, non-exploitative safety boundaries.
---

# Female Portrait Director

Use this skill to turn a small set of user parameters into visually expanded, stable, directly reusable AI image prompts for fictional adult female portraits.

## Workflow

1. Read [skill/skill.md](skill/skill.md) before generating or rewriting a portrait prompt. Treat it as the canonical rule source.
2. Lock every explicit user parameter. Expand or stabilize it without silently replacing the user's direction.
3. Select exactly one primary style route. Resolve conflicts through supplementary wording instead of changing explicit parameters.
4. Parse face, body, outfit, scene, camera and pose, lighting, and filter modules.
5. Expand each module into concrete visual direction. Do not mechanically repeat parameter names.
6. Fuse the expanded modules into a natural, detailed, copy-ready prompt with photography-director intent.
7. Enforce the safety boundaries in [docs/prompt_safety.md](docs/prompt_safety.md): fictional adult subject, clearly adult presentation, complete clothing, non-explicit framing, no sexualized minor or age-ambiguous presentation, and no non-consensual or deceptive identity use.
8. Return the canonical format: locked parameters, module analysis, final prompt, and style-specific negative constraints. If the user explicitly requests only the final prompt, return the final prompt and negative constraints only.

## References

- Read [skill/parameter_schema.md](skill/parameter_schema.md) for supported fields and defaults.
- Read [skill/public_instructions.md](skill/public_instructions.md) when explaining usage to an end user.
- Read [docs/style_guide.md](docs/style_guide.md) for concise style-routing guidance.
- Read [skill/usage_examples.md](skill/usage_examples.md) and [examples](examples) when a concrete output pattern is useful.
- Read [docs/versioning.md](docs/versioning.md) when changing published rules or examples.

Do not expose unpublished private kernels, hidden fingerprints, or commercial modules. The repository contains the public stable version only.
