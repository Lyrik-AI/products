# Lyrik-AI/products

The LyrikTrip product catalogue, mirrored from www.lyriktrip.com: `tours/<slug>.md`, `experiences/<slug>.md`, `README.md` (index), `llms.txt` and `data/products.json`. Slugs match the official URLs (`/tours/<slug>`, `/experience/<slug>`).

## Pull requests

- Merge your own pull requests automatically as soon as they are ready; do not wait for a human review.
- "Ready" means: no merge conflict, every CI check on the latest commit green (if the repo has CI), and no unresolved blocking review comment.
- Merge with a squash merge, then delete the head branch.

## Content conventions

- Every product page starts with YAML front matter (`title`, `seo_title`, `tagline`, `duration`, `days`, `price_from_usd`, `cities`, `themes`, `cover`, `official_url`, `notion_url`, `contact_email`, `whatsapp`).
- Every product page ends with a "Contact us about this trip" block: a `https://wa.me/85269280475?text=...` WhatsApp link and a `mailto:cs@lyriktrip.com` link, both prefilled with that product's name and official URL.
- Escape literal dollar signs in page bodies as `\$` so GitHub does not render them as math.
- When a product is added or changed, keep `README.md`, `llms.txt` and `data/products.json` in sync.
