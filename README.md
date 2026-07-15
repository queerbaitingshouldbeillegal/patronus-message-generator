# Patronus Workskin HTML Generator

The html generator for the Patronus Message workskin.

## What it does

You fill in the form:
- Who's sending the patronus (Harry, Draco, or a custom character/image).
- The paragraph right before the reveal (e.g. "...and casts his patronus") or just leave it blank if there's nothing before.
- The trigger phrase itself (the clickable text) (in my ao3 fic example, it's the glowing text saying "casts his patronus" but you can customize this obviously).
- The paragraph right after, before the message appears. Or just leave it blank if there's nothing after.
- The message the patronus delivers.

Click **Generate**, and it gives you:
1. **HTML** for that specific scene. Paste it directly into your AO3 chapter wherever the patronus moment happens.
2. **CSS** Paste this into your workskin's CSS panel *once*. It doesn't need to be regenerated per scene; it's sized to handle any message up to 500 characters long

There's also a live preview at the bottom of the page so you can click the trigger and watch the reveal animation before you paste anything into AO3. To see and fix timing if you need to.

## Customizable Stuff

- **Timing**: the "delay starts at" and "step" fields control how fast the message types out. Larger step = slower typing.
- **New characters**: pick "Custom" as the sender, then supply your own image URL and alt text. The image needs to be hosted somewhere externally (file.garden, Imgur, etc.).

---
