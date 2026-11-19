# The Fixture Edit

Static mobile-friendly fixture planning website. No build system or dependencies required.

## Publish on GitHub Pages
1. Create a GitHub repository (private is fine for source control).
2. Upload all files from this folder into the **repository root** (`index.html` and the `.webp` images).
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, select `main` and `/ (root)`.
4. Once published, share the resulting Pages URL.

**Privacy:** For standard GitHub Pages, a private repository does **not** make the published site private. Only publish non-sensitive information.

## Features and limits
- Room-by-room navigation, product links, votes and notes, copyable selection summary, and printable layout.
- Votes and notes are stored in each device's `localStorage`. They **do not sync** between you and your spouse.
- Some lighting product photos are not embedded. The cards link to the exact product variants, allowing a quick check of the actual images and specifications.
- The basement faucet was supplied as an image in a later message, but that image was not available in the build's file inputs. Its place is reserved pending a locally accessible copy.
- Product/finish titles were supplied by the user; check actual dimensions, availability, and prices before ordering.
- Google Fonts and a few product photos load over the internet. Everything else is static.
