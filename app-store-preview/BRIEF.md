# Brief: Lovely App Store preview video (translated from Turkish)

Written by Claude Opus 5.5 for a content-creator agent. The first Turkish cut was built from this brief; the US version reused the result.

## 1. Goal
A vertical App Preview video: the **first thing** on Lovely's App Store page. In search, a vertical preview takes the first slot with 2 screenshots beside it. It **autoplays muted**, so it must work without sound. The first 3 seconds decide whether people stop scrolling.

One-line goal: *the answer to "what is my partner doing right now?" is on your Lock Screen and Home Screen.*

## 2. The app
Lovely is a private app for two partners. Made by a couple. No games, no ads.
- **Live location:** share for 15 min / 1 h / 8 h. A Live Activity card appears on the partner's **Lock Screen** ("sharing live location · 1.2 km · ~4 min") and says "arrived" at the end. Our strongest differentiator.
- **Stories:** photo + short text, live for 6 hours, land on the partner's **Home Screen widget**.
- **Mood:** presets like "Miss you", one tap to share; shown as a bubble and in the widget.
- **Home:** two avatars, the distance between them, mood bubbles, story card.
- **Shared journal:** photo memories (place + date), special-day countdowns, a memories map.
- **Widgets:** story, mood, "Together 1,201 days".
- No price or subscription in the video.

## 3. Audience
Couples, long-distance and same-city. Don't lead with long distance alone; "always close" works for everyone.

## 4. App Store hard limits (verify in App Store Connect)
- 15–30 s (target ~25 s). 886×1920 portrait for 6.9"/6.5" iPhone. H.264 (or ProRes 422 HQ), max 30 fps, under 500 MB. Audio optional, stereo AAC, licensed or royalty-free.
- Footage must be **real screen recordings** of the app. You may crop, zoom and put text over them. Do not redraw the UI as animation.
- Not allowed: "Download" calls to action, prices or "free", "#1" or rating claims, hands holding devices, real human face video.
- App icon and name may appear as a short card at the start or end.
- Poster frame defaults to **second 5**; that frame must work on its own.

## 5. Visual language
Competitors are purple-pink gradients and mascots. We are warm, calm and real.
- Colors: cream `#FBF6EF` → `#F6E6DA`, ink `#2B1D16`, secondary `#7A6558`, coral accent `#E2674A` (text on light: `#A8402A`), soft coral `#FBE3DA`.
- Type: serif headline, the emphasized word *italic and coral*. Rounded sans body. Match the store screenshots.
- Motion: soft spring animations, calm transitions. No fast cuts, flashes or confetti.
- Device: thin dark iPhone frame (as in the screenshots) or full-screen capture.

## 6. Storyboard (~25 s, 30 fps). Each line on screen at least 1.5 s.
| # | Time | Picture | Text |
|---|---|---|---|
| 1 | 0–3 s | Live Activity clip, first half: card arrives, distance drops | **Is your partner on the way?** |
| 2 | 3–7 s | Same clip, end: "arrived". **Poster frame ~5 s**: no dimming | ***Live location* on the Lock Screen** |
| 3 | 7–11 s | Home Screen: big story widget, mood and "1,201 days" widgets | **Your story on their *Home Screen*** |
| 4 | 11–15 s | Mood picker: tap "Miss you" → bubble appears on home | **Share your *mood* in one tap** |
| 5 | 15–19 s | Home: two avatars, distance, story card; gentle scroll | **Close to your partner, *always*** |
| 6 | 19–23 s | Journal (special days) → memories map, pins appear one by one | **Your memories and *anniversary countdown*** |
| 7 | 23–25 s | Closing card: app icon + "Lovely", small badge "Made by a couple" | **Lovely** |

No download call to action at the end.

## 7. Assets
`screens/` real raw screenshots (1320×2868), `clips/` real simulator recordings (1320×2868, 30 fps, silent) for moving scenes, `store-screenshots/` the live store set for style, `photos/` the demo couple (AI-generated, not real people), `brand/` icon and founder photos.

## 8. Delivery
886×1920, 30 fps, H.264, ≤30 s, plus a suggested poster frame. Checklist: understandable muted · all footage real app screens · no price, download CTA or rating claim · 15–30 s · 886×1920 · ≤30 fps.

## 9. Feedback on the first cut
1. Replace still images with the real recordings; a slideshow risks rejection.
2. Show the "arrived" moment.
3. Show the tap in the mood scene.
4. The dimming at 2–7 s makes the poster frame grey: remove it.
5. Technical: audio 256 kbps AAC, pixel format yuv420p.
