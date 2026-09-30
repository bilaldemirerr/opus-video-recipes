# Kinetic typography explainer: what's new in Opus 5.5 (HyperFrames)

[![poster](../media/whats-new-opus-5-5.jpg)](out.mp4)

16 s, 1920×1080, 30 fps, one HTML file, no assets. [Watch on the site](https://bilallabs.vercel.app/ai/opus-video/kinetic-typography-explainer).

## Prompt to reproduce

```
Make a 16-second 1920×1080 kinetic typography video with HyperFrames: "What's new in Claude Opus 5.5". One fact per ~2 s beat, big bold numbers, warm off-white background, one accent color, a progress bar along the bottom and a source line. Facts only from anthropic.com/claude-opus-5-5 and platform.claude.com: released Sep 22 2026; $4 / $20 per million input/output tokens (20% less than Opus 5); cache reads $0.20 (60% less); ~40% cheaper on typical workloads; 30%+ faster output; 1M context, 128K max output; adaptive thinking always on, default effort medium; model ID claude-opus-5-5. Run hyperframes check, then render.
```

## Measured

- `npx hyperframes check`: lint, layout and contrast (24/24 WCAG AA) passed.
- Render: **11.0 s** on an M4 MacBook, hardware GPU, `--quality delivery`. Output 2.2 MB.
- Tokens / cost: **not measured.** Built by Claude Opus 5.5 inside a longer multi-task agent session in Cursor with no per-recipe token counter.

## Run

```bash
npx hyperframes check
npx hyperframes render --quality delivery --output out.mp4
```
