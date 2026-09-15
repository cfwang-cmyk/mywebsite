# Images

Drop an image into the matching folder using the exact file name below. The site picks it up automatically on the next page load.
Supported extensions: `.jpg` `.jpeg` `.png` `.webp` `.gif` (only the base name has to match).
If a file is missing, the site shows its built-in placeholder instead.

| Folder | File name | Where it shows | Suggested size |
|---|---|---|---|
| `images/avatar/` | `avatar.jpg` | The "JW" circle (sidebar on desktop, top of page on mobile) | Square, ≥ 400×400 |
| `images/background/` | `background.jpg` | Full-page background (replaces the animated pattern) | Landscape, ≥ 1920×1080 |
| `images/projects/` | `asl.jpg` | Cover of the "ASL Recognition" project card | 16:9, ≥ 800×450 |
| `images/projects/` | `ftc.jpg` | Cover of the "FTC Robotics" project card | 16:9 |
| `images/projects/` | `parks.jpg` | Cover of the "Reexamining Our Past" project card | 16:9 |
| `images/projects/` | `placeholder.jpg` | Cover of the "Coming Soon" project card | 16:9 |

## Other settings — `data/content.json`

- `bg_blur` (px) / `bg_opacity` (0–100): how much the background image is blurred and darkened
- `gradient_colors` / `gradient_animate`: colors of "Jerry Wang" in the title
- `wechat`: shown under Contact when filled in (empty `""` = hidden)
- `project_links`: URL for each project card (leave `""` for no link)
