# Christine Mary Photography

Static site for Christine Mary Photography, Boulder, Colorado.

- `public/index.html`: the main site. Words, prices, photos, email and Instagram live in the `CONFIG` block near the bottom of the file.
- `public/aspen/index.html`: the Aspen Christmas Card Concierge booking page. Dates, time slots and packages live in its `CONFIG` block.
- `public/img/` and `public/aspen/img/`: photos.
- `public/_headers`: cache settings for Cloudflare.

No build step.

- **Cloudflare Workers** (Workers & Pages → Create → Import a repository): pick this repo; `wrangler.jsonc` tells it to serve the `public` folder. Leave the build command empty.
- **Cloudflare Pages** (Connect to Git): framework preset None, build command empty, build output directory `public`.
