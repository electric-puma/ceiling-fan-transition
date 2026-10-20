---
name: ceiling-fan-transition
description: Create a ceiling-fan blade reveal video from one transparent rotor and five scene images, optionally with five supplied sound effects. Use when a user requests this specific fan wipe effect.
---

# Ceiling fan transition

Create a continuous clockwise fan reveal across five scenes. Default output: 8 seconds, 720×1280, 24 fps. The bundled sample contains five alien images and five matching sound effects.

Read [references/workflow-he.md](references/workflow-he.md) for the tested geometry, mask equation, timing, quality checks, and delivery requirements. Paths in that reference are relative to this skill folder. Locate bundled media relative to this file, then copy them into the working video project.

Use supplied scene media when the user provides their own. Otherwise use assets/images/01–05 and their matching assets/sfx/01–05 for the bundled demonstration. Preserve the complete transparent rotor in assets/images/fan-rotor-transparent.png: its centered pivot and dimensions are part of the tested geometry.

Animate only scene content with the image-to-video provider; build the rigid rotor, reveal masks and assembly in HyperFrames. This workflow depends on access to an image-to-video provider and HyperFrames; check the target environment before promising execution. Use applicable installed HyperFrames skills when available. Do not install tools, switch to a different paid provider, or purchase services implicitly.

Default to silent image-to-video generation plus the supplied effects. Five effects are separate audio assets, not embedded in the reference images. The supplied demo MP4 predates adding those five effects; it illustrates the visual transition.

Present current generation costs before submitting paid jobs and obtain approval for the expenditure. Do not generate replacement images, extra audio, or paid retries without authorization. If required tooling is missing, report the specific dependency and preserve the inputs.

Deliver the rendered MP4, a silent version, and a portable source project; verify the exported artifact. Keep the user's language and file handoff conventions. The sample geometry applies to the bundled rotor and portrait frame; recompute and check it if either changes.
