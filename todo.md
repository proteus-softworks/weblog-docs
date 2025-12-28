---
title: "Site Todo"
description: "A work in progress."
draftDate: "Dec 31 3000"
---

# Weblog Post Ideas
- [ ] Supabase studio as a standalone Postgres GUI
- [ ] Guitar hero drums to midi
- [ ] Pocket operator sync
- [ ] Blogging with Astro and Obsidian
# Formatting, etc
- [ ] Bottom margin following checklists
- [ ] Block quotes
- [ ] Links to other obsidian blog posts
	- [ ] This format (This is an alt title)[[the-dilettantes-garden]] should render with the alt title and link to the post
	- [ ] This format [[the-dilettantes-garden]] should render with the post title and link to the post
- [ ] Indented lists
- [ ] Opengraph site banner
- [ ] Opengraph blog heroes
# Misc
- [ ] Pre-load fonts

Example from [fontsource](https://fontsource.org/docs/getting-started/preload)

```typescript
import '@fontsource-variable/open-sans';
import openSansWoff2 from '@fontsource-variable/open-sans/files/open-sans-latin-wght-normal.woff2?url';

<link rel="preload" as="font" type="font/woff2" href={openSansWoff2} crossorigin="anonymous" />

```

- [ ] More fun facts
- [ ] Dynamic fun facts?
	- Extract them into a yml/json/text file for easy mobile editing?
	- Maybe a markdown file so I can edit in obsidian? In theory the whole file can be just top matter?
- [ ] Collage page with simple dynamic rendering of external images
	- I’m imagining like a table full of Polaroids?   
- [x] Pic of me n beans on Home Screen
- [ ] Break out the “beliefs” sections into separate posts with a “belief” tag, reconstitute them into the beliefs post as a special type of post?
- [ ] Look into using [uniorg](https://github.com/rasendubi/uniorg) for live org-mode parsing
	- Once this happens, I can probably just move away from MDX and rely entirely on server-side org mode parsing
	- Publish a formal org-mode astro.js package?
	- Would maybe be nice for TODO stuff as well (like this doc)
- [ ] 