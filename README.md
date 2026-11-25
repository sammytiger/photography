# Christine Mary Photography

Static site for Christine Mary Photography, Boulder, Colorado.

- `index.html`: the main site. Words, prices, photos, email and Instagram live in the `CONFIG` block near the bottom of the file.
- `aspen/index.html`: the Aspen Christmas Card Concierge booking page. Dates, time slots and packages live in its `CONFIG` block.
- `img/` and `aspen/img/`: photos.
- `_headers`: cache settings for Cloudflare.

No build step. On Cloudflare (Workers & Pages → connect this repo), leave the build command empty and set the output directory to `/`.
