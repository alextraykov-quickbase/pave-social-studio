# Pave social studio

Make on-brand Pave posts and short videos from a photo and one line of copy. It runs in your browser. There's nothing to install, and you don't need an admin password or a GitHub account.

**Open it:** https://alextraykov-quickbase.github.io/pave-social-studio/

Use Chrome or Edge. Safari and Firefox work too (see "Your posts" below).

## The first time

1. Open the link above. There's nothing to set up: headlines are set in Geist Mono, so no font is needed.
2. Optional: put the studio in your Dock or Start menu. In Chrome or Edge, choose the install icon at the right end of the address bar, then Install. It then opens in its own window, even with no internet.

## Make a post

Drop a photo on the post (or try a sample), type one line, then choose **Export** for a sharp image or a video.

## Your posts

- **Save to Library** (in the Export menu) keeps a post in this browser. Another browser or another computer won't see it.
- **Back it up or hand it over:** in the Library, choose **Share file**, then keep the file or send it to a teammate. They choose **Import** and pick it.
- **Copy link** sends one post without its photo. A teammate who opens the link gets it in their Library.
- Safari clears a site's saved data if you don't open it for about a week. If you use Safari, use Share file now and then to keep a copy.

## Fonts

This public copy sets headlines in Geist Mono, which is free to share. It doesn't carry Pave Slab, which is licensed for Quickbase only.

---

For the people who look after the site: the files under `docs/` are built by `build-pages.mjs` in the studio's package folder, and GitHub Pages serves them from `main`, folder `/docs`. To update the site, build, copy into `docs/`, commit and push. Teammates get the new version the next time they open the studio.
