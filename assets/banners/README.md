# Profile banner

`github-octocat.png` is the original image supplied by the user.

`github-octocat-cropped.png` is the selected built-in imagegen edit, resized to 646px wide for the README. It removes the side margins and bottom screenshot border so the colored strip aligns with the button row.

## Built-in imagegen prompt

```text
Use case: precise-object-edit. Edit target: attached local GitHub Octocat banner, exactly 646 x 240 pixels. Primary request: CROP ONLY. Remove 13 pixels of white margin on the left, 11 pixels of white margin on the right, and 7 pixels from the bottom (thin screenshot border/white fringe). Keep the top edge unchanged to preserve the character's ears. The resulting content crop is x=13..634 inclusive, y=0..232 inclusive, 622 x 233 pixels. Preserve every retained pixel exactly: same original Octocat, pose, white backdrop, purple/yellow pattern on left, orange/lavender center pattern, green pattern on right. Do not redraw, restyle, sharpen, regenerate, add text, change colors, add border, round corners, or add padding. The colored rectangle at the bottom must extend exactly to the left, right and bottom edges of the image canvas so it can align with rectangular buttons below it.
```
