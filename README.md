# The Hallway Art

Portfolio and commission site for **Alicia Hall** — graphite pencil portrait and nature artist.

**Live site:** [www.thehallwayart.com](https://www.thehallwayart.com)

## Structure

- `index.html` — the entire site (single page: hero, portrait gallery, about, nature gallery, commission form)
- `images/` — full-resolution artwork images, sepia-toned to match

## Notes

- Pure static HTML/CSS — no build step. Deploy by serving this folder as-is.
- The commission form posts to [FormSubmit](https://formsubmit.co/) and relays to thehallwayart@gmail.com. The first submission after deployment triggers a one-time activation email that must be confirmed.
- Gallery images open full-resolution in a new tab when clicked.
