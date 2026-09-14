# Website structure

The root `index.html` is the homepage. `css/` and `js/` contain shared site code. `images/` contains homepage and site-wide images.

Each major content section is its own top-level page folder. The folder contains its own `index.html`, its own `images/` folder, and the content files that belong to that section.

- `videos/` — Videos page, video content, and thumbnails in `videos/images/`
- `documents/` — Documents page, document files, and related images in `documents/images/`
- `presentations/` — Presentations page, presentation files, and thumbnails in `presentations/images/`

Future pages should follow the same pattern: `<page>/index.html`, with `<page>/images/` when that page needs images.

Asset filenames should be lowercase, descriptive, and use hyphens instead of spaces.
